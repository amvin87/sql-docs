---
title: Cancel option admin tool
titleSuffix: SQL Server Distributed Replay
description: This article describes the cancel command-line option and syntax of the SQL Server Distributed Replay administration tool.
ms.prod: sql
ms.prod_service: sql-tools
ms.technology: tools-other
ms.topic: conceptual
author: markingmyname
ms.author: maghan
ms.reviewer: ""
ms.custom: seo-lt-2019
ms.date: 03/14/2017
---
# Cancel Option (Distributed Replay Administration Tool)

 [!INCLUDE [SQL Server](../../includes/applies-to-version/sqlserver.md)]

The [!INCLUDE[msCoName](../../includes/msconame-md.md)] [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] Distributed Replay administration tool, **DReplay.exe**, is a command-line tool that you can use to communicate with the distributed replay controller. This topic describes the **cancel** command-line option and corresponding syntax.  
  
 The **cancel** option cancels the current operation that is running on the controller.  
  
 ![Topic link icon](../../database-engine/configure-windows/media/topic-link.gif "Topic link icon") For more information about the syntax conventions that are used with the administration tool syntax, see [Transact-SQL Syntax Conventions &#40;Transact-SQL&#41;](../../t-sql/language-elements/transact-sql-syntax-conventions-transact-sql.md).  
  
## Syntax  
  
```  
  
dreplay cancel [-m controller] [-q]   
```  
  
#### Parameters
 **-m** *controller*  
 The computer name of the controller. You can use "`localhost`" or "`.`" to refer to the local computer.  
  
 If the **-m** parameter is not specified, the local computer is used.  
  
 **-q**  
 Quiet mode. Does not prompt for confirmation.  
  
 The **-q** parameter is optional.  
  
## Examples  
 In the following example, a cancel request is submitted in quiet mode. The value `localhost` indicates that the controller service is running on the same computer as the administration tool.  
  
```  
dreplay cancel -m localhost -q  
```  
  
## Permissions  
 You must run the administration tool as an interactive user, as either a local user or a domain user account. To use a local user account, the administration tool and controller must be running on the same computer.  
  
 For more information, see [Distributed Replay Security](../../tools/distributed-replay/distributed-replay-security.md).  
  
## See Also  
 [SQL Server Distributed Replay](../../tools/distributed-replay/sql-server-distributed-replay.md)  
  
  
