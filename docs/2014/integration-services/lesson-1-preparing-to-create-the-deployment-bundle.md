---
title: "Lesson 1: Preparing to Create the Deployment Bundle | Microsoft Docs"
ms.custom: ""
ms.date: "06/13/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "integration-services"
ms.tgt_pltfrm: ""
ms.topic: conceptual
ms.assetid: b6fe283c-9856-4ba1-a497-e3912424fd18
caps.latest.revision: 19
author: "douglaslM"
ms.author: "douglasl"
manager: craigg
---
# Lesson 1: Preparing to Create the Deployment Bundle
  In this lesson, you will create the working folders and environment variables that support the tutorial, create an [!INCLUDE[ssISnoversion](../includes/ssisnoversion-md.md)] project, add several packages and their supporting files to the project, and implement configurations in packages.  
  
 [!INCLUDE[ssISnoversion](../includes/ssisnoversion-md.md)] deploys packages on a project basis; therefore, as the first step in creating the deployment bundle, you must collect all the packages and package dependencies into one [!INCLUDE[ssISnoversion](../includes/ssisnoversion-md.md)] project. Frequently it is useful to include other information with the deployed packages: for example you will also add to the project a Readme file that provides basic documentation for this group of packages.  
  
 After you have added the packages and files, you will add configurations to packages that do not already use configurations. The configurations update properties of packages and package objects at run time. In a later lesson, you will modify the values of these configurations during package deployment to support the packages in the deployed-to environment.  
  
 After you have added the configurations, you should open the packages in [!INCLUDE[ssIS](../includes/ssis-md.md)] Designer, the [!INCLUDE[ssISnoversion](../includes/ssisnoversion-md.md)] graphical tool for building ETL packages, and examine the properties of packages and package elements as well as the package configurations to better understand the issues that the deployment needs to address. For example, one of the packages extracts data from text files, so the location of the data files must be updated before the deployed packages will run successfully.  
  
 **Estimated time to complete this lesson:** 1 hour  
  
## Lesson Tasks  
 This lesson contains the following tasks:  
  
-   [Step 1: Creating Working Folders and Environment Variables](../integration-services/lesson-1-1-creating-working-folders-and-environment-variables.md)  
  
-   [Step 2: Creating the Deployment Project](../integration-services/lesson-1-2-creating-the-deployment-project.md)  
  
-   [Step 3: Adding Packages and Other Files](../integration-services/lesson-1-3-adding-packages-and-other-files.md)  
  
-   [Step 4: Adding Package Configurations](../integration-services/lesson-1-4-adding-package-configurations.md)  
  
-   [Step 5: Testing the Updated Packages](../integration-services/lesson-1-5-testing-the-updated-packages.md)  
  
## Start the Lesson  
 [Step 1: Creating Working Folders and Environment Variables](../integration-services/lesson-1-1-creating-working-folders-and-environment-variables.md)  
  
![Integration Services icon (small)](media/dts-16.gif "Integration Services icon (small)")  **Stay Up to Date with Integration Services**<br /> For the latest downloads, articles, samples, and videos from Microsoft, as well as selected solutions from the community, visit the [!INCLUDE[ssISnoversion](../includes/ssisnoversion-md.md)] page on MSDN:<br /><br /> [Visit the Integration Services page on MSDN](http://go.microsoft.com/fwlink/?LinkId=136655)<br /><br /> For automatic notification of these updates, subscribe to the RSS feeds available on the page.  
  
  