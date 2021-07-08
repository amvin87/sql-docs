---
description: "Connecting to Data Sources"
title: "Connecting to Data Sources | Microsoft Docs"
ms.prod: sql
ms.prod_service: connectivity
ms.technology: ado
ms.custom: ""
ms.date: "01/19/2017"
ms.reviewer: ""
ms.topic: conceptual
helpviewer_keywords: 
  - "connections [ADO]"
ms.assetid: 82770486-37bd-4c90-885f-6817a7c77ad7
author: rothja
ms.author: jroth
---
# Connecting to Data Sources
An ADO **Connection** object represents a unique session with a data source, including a DBMS, a file store, or a comma-delimited text file. In the case of a client/server database system, the ADO connection can be an actual network connection to the server.  
  
 The **Connection** object supports various [properties and methods](../../reference/ado-api/connection-object-properties-methods-and-events.md) for specifying connection configurations, opening and closing connections, creating and executing commands against the data source, and providing information about the design of the underlying data source in the form of schema rowsets, etc. Depending on the functionality supported by the provider, some collections, methods, or properties of a **Connection** object might not be available.  
  
 You can connect to a data source either by using a **Connection** object or by using a **Recordset** object.  
  
 This section contains the following topics.  
  
-   [Using a Connection Object](./using-a-connection-object.md)  
  
-   [Using a Recordset Object](./using-a-recordset-object.md)  
  
-   [Creating a Connection String](./creating-a-connection-string.md)  
  
-   [Specifying Connection Properties](./specifying-connection-properties.md)  
  
-   [Controlling Transactions](./controlling-transactions-ado.md)