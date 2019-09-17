<div class="MCWHeader1">
Cosmos DB scenario-based Demo - Retail
</div>

<div class="MCWHeader2">
Hands-on demo step-by-step
</div>

<div class="MCWHeader3">
September 2019
</div>


Information in this document, including URL and other Internet Web site references, is subject to change without notice. Unless otherwise noted, the example companies, organizations, products, domain names, e-mail addresses, logos, people, places, and events depicted herein are fictitious, and no association with any real company, organization, product, domain name, e-mail address, logo, person, place or event is intended or should be inferred. Complying with all applicable copyright laws is the responsibility of the user. Without limiting the rights under copyright, no part of this document may be reproduced, stored in or introduced into a retrieval system, or transmitted in any form or by any means (electronic, mechanical, photocopying, recording, or otherwise), or for any purpose, without the express written permission of Microsoft Corporation.

Microsoft may have patents, patent applications, trademarks, copyrights, or other intellectual property rights covering subject matter in this document. Except as expressly provided in any written license agreement from Microsoft, the furnishing of this document does not give you any license to these patents, trademarks, copyrights, or other intellectual property.

The names of manufacturers, products, or URLs are provided for informational purposes only and Microsoft makes no representations and warranties, either expressed, implied, or statutory, regarding these manufacturers or the use of the products with any Microsoft technologies. The inclusion of a manufacturer or product does not imply endorsement of Microsoft of the manufacturer or product. Links may be provided to third party sites. Such sites are not under the control of Microsoft and Microsoft is not responsible for the contents of any linked site or any link contained in a linked site, or any changes or updates to such sites. Microsoft is not responsible for webcasting or any other form of transmission received from any linked site. Microsoft is providing these links to you only as a convenience, and the inclusion of any link does not imply endorsement of Microsoft of the site or the products contained therein.

© 2019 Microsoft Corporation. All rights reserved.

Microsoft and the trademarks listed at <https://www.microsoft.com/en-us/legal/intellectualproperty/Trademarks/Usage/General.aspx> are trademarks of the Microsoft group of companies. All other trademarks are property of their respective owners.

**Contents** 

<!-- TOC -->

- [Cosmos DB scenario-based demo - Retail hands-on demo step-by-step](#cosmos-db-scenario-based-demo---retail-hands-on-lab-step-by-step)
  - [Abstract and learning objectives](#abstract-and-learning-objectives)
  - [Overview](#overview)
  - [Solution architecture (High-level)](#solution-architecture-high-level)
  - [Requirements](#requirements)
  - [Before the hands-on lab](#before-the-hands-on-lab)
  - [Exercise 1: Deployment and Setup](#exercise-1-deployment-and-setup)
    - [Task 1: Deploy ARM Template](#task-1-blah)
    - [Task 2: Initialize and populate the Cosmos DB instance](#task-1-blah)
    - [Task 3: Configure resources](#task-1-blah)
  - [Exercise 2: Explore Contoso Movie Store](#exercise-2-explore-contoso-movie-store)
    - [Task 1: Explore the Contoso Movie Store](#task-1-blah-1)
  - [Exercise 3: Simulate data and events using Stream Analytics and Power BI](#exercise-3-simulate-data-and-events-using-stream-analytics-and-power-bi)
    - [Task 1: Open the Power BI Dashboard](#task-1-blah-2)
    - [Task 2: Start Stream Analytics and run the Data Generator](#task-2-blah-2)
  - [Exercise 4: Email alerts using Logic Apps](#exercise-4-email-alerts-using-logic-apps)
    - [Task 1: Review the Logic App and Emails](#task-1-review-the-logic-app-and-emails)
  - [After the hands-on lab](#after-the-hands-on-lab)
    - [Task 1: Delete resource group](#task-1-delete-resource-group)

<!-- /TOC -->

# Cosmos DB scenario-based labs - Retail hands-on lab step-by-step

## Abstract and learning objectives

In this hands-on-lab, TODO

At the end of this lab you will TODO

## Overview

Contoso Movies, Ltd. has TODO

## Solution architecture (High-level)

![TODO.](../Media/solution-diagram-1.png "Solution Architecture")

## Requirements

1. Microsoft Azure subscription must be pay-as-you-go or MSDN.

    - Trial subscriptions will not work.
    
## Before the hands-on lab

Refer to the Before the hands-on lab setup guide manual before continuing to the lab exercises.

## Exercise 1: Deployment and Setup

Duration: 60 minutes

Synopsis:  In this exercise you will TODO

### Task 1: Deploy ARM Template

1.  Deploy the provided ARM template

### Task 2: Initalize and populate the Cosmos DB instance

1.  Run the MovieDataImport

### Task 3: Configure resources

1.  Set all the Azure resource configurations

## Exercise 2: Explore Contoso Movie Store

Duration: 15 minutes

Synopsis: TODO

### Task 1: Explore the Contoso Movie Store

1.  Open the web site

2.  Mention that you are not logged in as any user and the results that are being displayed are based on the **top** purchased items in the Cosmso database.

3.  In the top navigation, cLick the **Login** link

4.  Mention that there are several pre-populated *personalities*.  Select the **comedy@contosomovies.com** personality

5.  Mention that you now have targeted movies based on two different algorithms

## Exercise 3: Simulate data and events using Stream Analytics and Power BI

Duration: 30 minutes

In this exercise you will TODO

### Task 1: Open the Power BI dashboard

1.  Browse to your PowerBI dashboard and open the Movie Dashboard

### Task 2: Start Stream Analytics and run the Data Generator

1.  Browse to your Stream Analytics service, click **Start**

2.  Open the **DataGenerator** project

3.  Update the app.config settings, then run the **DataGenerator** project, after a few moments, notice that your dashboard is being updated

4.  After 30 seconds, you will notice the **buy** events has stopped.

## Exercise 4: Email alerts using Logic Apps

Duration: 30 minutes

In this exercise you will TODO

### Task 1: Review the Logic App and Emails

1.  Open the Logic App, review the single logic app that is available

2.  Ensure that your email is set and re-execute the DataGenerator project

3.  You should recieve emails based on the **buy** event

## After the hands-on lab 

Duration: 10 minutes

In this exercise, attendees will deprovision any Azure resources that were created in support of the lab.

### Task 1: Delete resource group

1.  Using the Azure portal, navigate to the Resource group you used throughout this hands-on lab by selecting **Resource groups** in the menu.

2.  Search for the name of your research group, and select it from the list.

3.  Select **Delete** in the command bar, and confirm the deletion by re-typing the Resource group name and selecting **Delete**.

You should follow all steps provided *after* attending the Hands-on lab.
