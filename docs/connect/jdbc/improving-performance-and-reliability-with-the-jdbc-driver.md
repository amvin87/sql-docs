---
title: Improving performance and reliability
description: Learn about various techniques for improving application performance and reliability when using the Microsoft JDBC driver for SQL Server.
ms.custom: ""
ms.date: 07/31/2020
ms.prod: sql
ms.prod_service: connectivity
ms.reviewer: ""
ms.technology: connectivity
ms.topic: conceptual
ms.assetid: e1592499-b87b-45ee-bab8-beaba8fde841
author: David-Engel
ms.author: v-daenge
---

# Improving performance and reliability with the JDBC driver

[!INCLUDE[Driver_JDBC_Download](../../includes/driver_jdbc_download.md)]

One aspect of application development that is common to all applications is the constant need to improve performance and reliability. There are a number of techniques for doing this with the [!INCLUDE[jdbcNoVersion](../../includes/jdbcnoversion_md.md)].

The articles in this section describe various techniques for improving application performance and reliability when using the JDBC driver.

## In this section

|Article|Description|
|-----------|-----------------|
|[Closing objects when not in use](closing-objects-when-not-in-use.md)|Describes the importance of closing JDBC driver objects when they are no longer needed.|
|[Managing transaction size](managing-transaction-size.md)|Describes techniques for improving transaction performance.|
|[Working with statements and result sets](working-with-statements-and-result-sets.md)|Describes techniques for improving performance when using the Statement or ResultSet objects.|
|[Using adaptive buffering](using-adaptive-buffering.md)|Describes an adaptive buffering feature, which is designed to retrieve any kind of large-value data without the overhead of server cursors.|
|[Sparse columns](sparse-columns.md)|Discusses the JDBC driver's support for [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] sparse columns.|
|[Prepared statement metadata caching for the JDBC driver](prepared-statement-metadata-caching-for-the-jdbc-driver.md)|Discusses the techniques for improving performance with prepared statement queries.|
|[Using bulk copy API for batch insert operation](use-bulk-copy-api-batch-insert-operation.md)|Describes how to enable Bulk Copy API for batch insert operations and its benefits.|
|[Not sending String parameters as Unicode](setting-the-connection-properties.md)|When working with **CHAR**, **VARCHAR**, and **LONGVARCHAR** data, users can set the connection property **sendStringParametersAsUnicode** to `false` for optimal performance gain.|

## See also

[Overview of the JDBC driver](overview-of-the-jdbc-driver.md)
