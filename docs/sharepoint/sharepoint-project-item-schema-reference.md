---
title: "SharePoint Project Item Schema Reference | Microsoft Docs"
ms.custom: ""
ms.date: "02/02/2017"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "office-development"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "VB"
  - "CSharp"
helpviewer_keywords: 
  - "FeatureProperty element"
  - "SafeControls element"
  - "SafeControl element"
  - ".spdata files"
  - "ExtensionData element"
  - "FeatureProperties element"
  - "ProjectOutputFile element"
  - "Files element"
  - "ProjectItemFolder element"
  - "ProjectItemFile element"
  - "ExtensionDataItem element"
  - "ProjectItem element"
ms.assetid: 12b63cbc-bf94-4175-bfa8-2117943d00d1
caps.latest.revision: 16
author: "gewarren"
ms.author: "gewarren"
manager: ghogen
ms.workload: 
  - "office"
---
# SharePoint Project Item Schema Reference
  Visual Studio uses the SharePoint project item schema to validate the contents of .spdata files. An .spdata file specifies the contents and behavior of a SharePoint project item. For more information about the contents of SharePoint project items, see [Creating Item Templates and Project Templates for SharePoint Project Items](../sharepoint/creating-item-templates-and-project-templates-for-sharepoint-project-items.md).  
  
 The SharePoint project item schema is named ProjectItemModelSchema.xsd and is installed by default in %Program Files (x86)%\Microsoft Visual Studio 11.0\Xml\Schemas.  
  
 The root element is the [ProjectItem](../sharepoint/projectitem-element.md) element. The following table describes all of the elements defined by the schema.  
  
|Element|Description|  
|-------------|-----------------|  
|[ExtensionData](../sharepoint/extensiondata-element.md)|Represents a collection of custom data items that are associated with the SharePoint project item.|  
|[ExtensionDataItem](../sharepoint/extensiondataitem-element.md)|Represents a custom data item that is associated with the SharePoint project item, in key/value format. Both the key and value must be strings.|  
|[FeatureProperties](../sharepoint/featureproperties-element.md)|Represents a collection of property values that are included with a Feature when it is deployed to SharePoint. After a Feature is deployed, you can access the property values in your code.|  
|[FeatureProperty](../sharepoint/featureproperty-element.md)|Represents a custom property that is included with a Feature when it is deployed to SharePoint. After a Feature is deployed, you can access the property in your code.|  
|[Files](../sharepoint/files-element.md)|Specifies the files to deploy with the SharePoint project item, such as a Feature element file or the output of a project.|  
|[ProjectItem](../sharepoint/projectitem-element.md)|Represents a SharePoint project item.|  
|[ProjectItemFile](../sharepoint/projectitemfile-element.md)|Represents a SharePoint file, such as Feature element file, to include with the project item when it is deployed to SharePoint.|  
|[ProjectItemFolder](../sharepoint/projectitemfolder-element.md)|Represents a mapped folder.|  
|[ProjectOutputFile](../sharepoint/projectoutputfile-element.md)|Represents the output of a project to include with the project item when it is deployed to SharePoint.|  
|[SafeControl](../sharepoint/safecontrol-element.md)|Represents an ASPX control or Web Part that is designated as secure for any user to access on any ASPX page on the SharePoint site.|  
|[SafeControls](../sharepoint/safecontrols-element.md)|Represents a collection of ASPX controls and Web Parts that are designated as secure for any user to access on any ASPX page on the SharePoint site.|  
  
## See Also  
 [Creating Item Templates and Project Templates for SharePoint Project Items](../sharepoint/creating-item-templates-and-project-templates-for-sharepoint-project-items.md)  
  
  