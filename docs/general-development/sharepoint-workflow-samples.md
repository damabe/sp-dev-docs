---
title: SharePoint workflow samples
description: Provides example workflows to show how to create and implement SharePoint workflows in the new Workflow Manager Client 1.0 framework.
ms.date: 06/13/2022
ms.prod: sharepoint
ms.assetid: ffaccd6b-426d-4ca0-b62f-bc7b14641a49
ms.localizationpriority: high
---

# SharePoint workflow samples
Provides sample workflows to help illustrate how to create and implement SharePoint workflows in the new Workflow Manager Client 1.0 framework.
## Workflow samples for SharePoint
<a name="bkm_wfsamples"> </a>

This series of sample workflows was developed to demonstrate the large range of workflow capabilities in SharePoint. They were developed using Visual Studio 2012 and are available in the  [MSDN Samples Gallery](https://code.msdn.microsoft.com/). Links to the individual samples are provided.
  
> [!NOTE]
> SharePoint 2010 workflows have been retired since August 1, 2020 for new tenants and removed from existing tenants on November 1, 2020. If you’re using SharePoint 2010 workflows, we recommend migrating to Power Automate or other supported solutions. For more info, see [SharePoint 2010 workflow retirement](https://support.microsoft.com/office/sharepoint-2010-workflow-retirement-1ca3fff8-9985-410a-85aa-8120f626965f).

### SharePoint workflow: Call an external web service

This sample uses Visual Studio to demonstrate creating a workflow that calls an external web service using the **HttpGet** activity. In calling the web service, the workflow also uses the new **DynamicValue** data type.
  
    
    
The sample, along with a readme file, is available here:  [SharePoint workflow: Call an external web service](https://code.msdn.microsoft.com/SharePoint-2013-workflow-48ea87d4)
  
    
    

### SharePoint workflow: Create a custom action

This sample uses Visual Studio to demonstrate creating a workflow that calls an external web service. In calling the web service, the workflow also uses the new **DynamicValue** data type. The part of the workflow that calls the web service and extracts the details from the response is contained within a custom activity, **GetNWCustomerDetailsWorkflow**.
  
    
    
The sample, along with a readme file, is available here:  [SharePoint workflow: Create a custom action](https://code.msdn.microsoft.com/SharePoint-2013-workflow-41e5c0f9)
  
    
    

### SharePoint workflow: Sales tax calculator

In this end-to-end sample, the workflow uses a web service to obtain the appropriate tax rate based on a purchaser's location, and then uses the base price to calculate the sales tax and total price.
  
    
    
The sample, along with a readme file, is available here:  [SharePoint workflow: Sales tax calculator](https://code.msdn.microsoft.com/SharePoint-2013-workflow-f7a1a8ba)
  
    
    

### SharePoint workflow: Use a task action in SharePoint Designer

An extended walkthrough of the process of implementing task actions in a workflow created using Microsoft SharePoint Designer 2013.
  
    
    
The sample, along with a readme file, is available here:  [SharePoint workflow: Using a task action in SharePoint Designer](https://code.msdn.microsoft.com/SharePoint-2013-workflow-942a5441)
  
    
    

### SharePoint workflow: Workflow OM in a SharePoint app

The **SharePoint workflow: Workflow OM in a SharePoint app** code sample is an example of an interactive SharePoint-hosted app that uses the SharePoint workflow JSOM to deploy workflow definitions to both an app web and to a "parent web" (that is, a SharePoint web that is hosting the app).
  
    
    
You can locate the sample code here:  [SharePoint workflow: Workflow OM in a SharePoint app](https://code.msdn.microsoft.com/SharePoint-2013-workflow-050f5211).
  
    
    

## See also
<a name="bkm_additional"> </a>


-  [Get started with workflows in SharePoint](get-started-with-workflows-in-sharepoint.md)
    
  
-  [Set up and configure SharePoint Workflow Manager](set-up-and-configure-sharepoint-workflow-manager.md)
    
  
-  [What's new in workflows for SharePoint](what-s-new-in-workflows-for-sharepoint.md)
    
  
-  [Workflow actions and activities reference for SharePoint](workflow-actions-and-activities-reference-for-sharepoint.md)
    
  
-  [SharePoint Add-ins](https://msdn.microsoft.com/library/cd1eda9e-8e54-4223-93a9-a6ea0d18df70%28Office.15%29.aspx)
    
  

