---
page_type: sample
languages:
- powerautomate-comma
products:
- powerautomate
name: Scheduled quote email
description: A power automate flow that automatically sends a weekly email with quote details
urlFragment: scheduled-quote-email
ms.date: 1/30/2023
author: diantaylor
ms.author: pnp
level: intermediate
ms.prod: power-automate
---

# Scheduled Quote Email

## Summary

Schedule a weekly email send containing a list of quote rows that need follow up, including a clickable link to each quote row. [More details](https://d365goddess.com/schedule-weekly-email-with-quote-details-and-hyperlink-part-1/) here and [here.](https://d365goddess.com/schedule-weekly-email-with-quote-details-and-hyperlink-part-2/)

## Applies to

* [Microsoft Power Automate](https://learn.microsoft.com/en-us/power-automate/)

## Compatibility


![Premium License](https://img.shields.io/badge/Premium%20License-Required-red.svg "Premium Power Automate license required")
![On-Premises Connectors](https://img.shields.io/badge/On--Premises%20Connectors-No-green.svg "Does not use on-premise connectors")
![Custom Connectors](https://img.shields.io/badge/Custom%20Connectors-Not%20Required-green.svg "Does not use custom connectors")

## Authors

Solution|Author(s)
--------|---------
Scheduled quote email | [Dian Taylor](https://github.com/d365goddess) ([@d365goddess](https://www.twitter.com/d365goddess) )

## Version history

Version|Date|Comments
-------|----|--------
1.0|January 30, 2023|Initial release


## Features

This sample demonstrates:

* Using the recurrence trigger to schedule the flow
* Get future and current dates 
* Query Dataverse to list quote rows
* Create an HTML table for the list of quotes
* Add the ability to create a clickable record link
* Send an email containing the list of rows in an HTML table 

## Preview
Below are images of the email and the power automate flow.

![Preview](https://raw.githubusercontent.com/d365goddess/main/main/Power%20Automate%20Samples/ScheduledQuoteEmail/assets/EmailMessage.PNG)  
![Preview](https://raw.githubusercontent.com/d365goddess/main/main/Power%20Automate%20Samples/ScheduledQuoteEmail/assets/ScheduledQuoteEmailFlow.PNG)  

## Installing the power automate flow
### Minimal Path to Awesome

* Download the zip file from the solution folder
* Browse to [Power Automate Portal](https://make.powerautomate.com) and select the environment you want to import the sample to
* Click on 'Solutions' and select 'Import solution'
* In the Import package page, select Upload and choose the .zip file containing the sample flow
* Select import


## For more information

- [Create your first flow](https://docs.microsoft.com/en-us/power-automate/getting-started#create-your-first-flow)
- [Microsoft Power Automate Documentation](https://learn.microsoft.com/en-us/power-automate/)

