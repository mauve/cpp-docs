---
title: "PROVIDER_COLUMN_ENTRY_TYPE_LENGTH | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: ["cpp-data"]
ms.topic: "reference"
f1_keywords: ["PROVIDER_COLUMN_ENTRY_TYPE_LENGTH"]
dev_langs: ["C++"]
helpviewer_keywords: ["PROVIDER_COLUMN_ENTRY_TYPE_LENGTH macro"]
ms.assetid: a60b1a8b-0903-4ff4-91ec-ed62126449fb
author: "mikeblome"
ms.author: "mblome"
ms.workload: ["cplusplus", "data-storage"]
---
# PROVIDER_COLUMN_ENTRY_TYPE_LENGTH
Represents a specific column supported by the provider.  
  
## Syntax  
  
```cpp
PROVIDER_COLUMN_ENTRY_TYPE_LENGTH(name  
, ordinal, dbtype, size, member )  
```  
  
#### Parameters  
 *name*  
  
 [in] The column name.  
  
 `ordinal`  
 [in] The column number. Unless the column is a Bookmark column, the column number must not be 0.  
  
 `dbtype`  
 [in] The data type in [DBTYPE](https://msdn.microsoft.com/en-us/library/ms711251.aspx).  
  
 `size`  
 [in] The column size in bytes.  
  
 `member`  
 [in] The member variable in the data class that stores the data.  
  
## Remarks  
 Similar to [PROVIDER_COLUMN_ENTRY_LENGTH](../../data/oledb/provider-column-entry-length.md) but also allows you to specify the column's data type as well as size.  
  
## Requirements  
 **Header:** atldb.h  
  
## See Also  
 [Macros for OLE DB Provider Templates](../../data/oledb/macros-for-ole-db-provider-templates.md)   
 [OLE DB Provider Templates](../../data/oledb/ole-db-provider-templates-cpp.md)   
 [OLE DB Provider Template Architecture](../../data/oledb/ole-db-provider-template-architecture.md)   
 [Creating an OLE DB Provider](../../data/oledb/creating-an-ole-db-provider.md)