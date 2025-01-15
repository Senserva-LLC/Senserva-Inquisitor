<img src="https://github.com/user-attachments/assets/5ce51b46-cdd7-4828-926c-9e9c3ec82460" width="200">

# The Senserva Inq.Uisitor (Inq.exe) Overview

The Senserva Inq.Uisitor (Inquisitor) is a free product designed to make it easier to know the security state of all the Entra IDs a technical team supports.  It can be used by either IT teams or Security teams.

Inq.Uisitor, or inq.exe, runs out of the box, sets itself up automatically and creates the web pages as show below.  It also has a rich set of parameters and uses a Sqlite database to start data.  This data can be used to easily create custom reports.

## Key Features

* There are no servers used. No web servers, no database severs. None.  Yet there is a full releational database thanks to SQLite and rich web pages based on html files local to the inq.exe directly to review results. This is done by design, to keep the data local and to keep it simple on the outside but very advance do the inside.
* Each time you run an scan only changes are recorded in the database.  You can run inq.exe all you want and only new data is saved.
* Easy to login to Azure, including Zero setup options.
* Output text can be easily customized via auto-generated CSV files that are used to display all key text.
* Full logging support, makes it easy to understand what is going on inside Inq.exe
* Source code available

## How it Works

Inq.Uisitor runs scans on demand, with scheduling and Containers comming in a future beta.

### Many Options for Logging into Azure

Inq.exe and many options to login in to Azure.  The easiest way to go is to use the Azure CLI and inq.exe just uses your current login, you do not need to do anything if you are already using the Azure CLI, or you can easily set it up.  The Azure Powershell is also supported

### The Azure CLI

The Azure Command-Line Interface (CLI) is a cross-platform command-line tool to connect to Azure and execute administrative commands on Azure resources. It allows the execution of commands through a terminal using interactive command-line prompts or a script. [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/what-is-azure-cli)

### The Az PowerShell Module

The Az PowerShell module is a set of cmdlets for managing Azure resources directly from PowerShell. [The Az PowerShell Module](https://learn.microsoft.com/en-us/powershell/azure/new-azureps-module-az?view=azps-13.0.0)

### SQLite Database

The Senserva Inq.Uisitor is built with SQLite. SQLite is a small, fast, self-contained, high-reliability, full-featured, SQL database engine. SQLite is the most used database engine in the world. [More About Sqlite](https://www.sqlite.org/)

The default name of the Senserva database is senserva.sqlite and it is automaticly created in the directy inq.exe is run from.  You can copy the database, share it (securely) or just delete it and run inq.exe again to rebuild it.  Senserva inq.exe will update the database each time it is run, with full deduping so you only get new data.

It is easy to work with SQLite in Python and other languages. The Python SQLite3 module is used to integrate the SQLite database with Python. There is no need to install this module separately as it comes along with Python after the 2.5x version. [More About Python and Sqlite](https://docs.python.org/3/library/sqlite3.html) 

SQLite can also be used with Powershell to read Inq.Uisitor data.  [SQLite and PowerShell with SimplySql](https://www.powershellgallery.com/packages/SimplySql/2.0.2.70)

## Changing Content with the Senserva CSV file

## Web Pages

# Project Status
Runtimes for Senserva - early beta please contact us for assistance and information. Senserva provides public contains with signifigant support, and then we add more for partners and customers who work more closely with us. All for free. Source could available to select partners and customers, please check with us.

## Known Bugs

## What is Coming Next

* Scheduling
* Inq.exe in Containers
* Inq.exe in Powershell CommandLets

## FAQ

* Hobby 1
  * Nested Hobby 1
    * Sub-nested Hobby 1
* Hobby 2
* Hobby 3

# Desired Collaboration

Please post issues.

# Beta 1 Release Notes

# Recomendations

Senserva supports many types of login techniques, but the easiest way to get start is with the Azure Cli. [https://github.com/MicrosoftDocs/azure-docs-cli/blob/main/docs-ref-conceptual/install-azure-cli-windows.md](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli) or https://learn.microsoft.com/en-us/dotnet/azure/install-azure-cli 

# How to Uninstall Azure PowerShell Modules (it's not supported)

https://learn.microsoft.com/en-us/powershell/azure/uninstall-az-ps?view=azps-13.0.0

https://github.com/Azure/azure-sdk-for-net/blob/main/sdk/identity/Azure.Identity/TROUBLESHOOTING.md#troubleshoot-azurepowershellcredential-authentication-issues

# Usage Rights
Please review the SenservaLicnese file before using this software. And note These run times only for END USER USE ONLY. They cannot be used within other products or be embedded in paid services without Senserva's express written permission. Senserva has an established OEM program with a scalable pricing model that works for companies of all sizes.  Please contact us for use of these,and all our works, as part of your products or to be embedded in your services. Also be sure to read the text around PROVIDED "AS IS" AND WITH ALL FAULTS AND DEFECTS WITHOUT WARRANTY OF ANY KIND.

Please note these run times are not yet ready for use, we are testing out the builds etc.


# About Senserva

The Senserva team is built with a team Microsoft Security Industry leaders including former Microsoft employees. Senserva believes an essential component of computer security is the efficient application of security tools and automated processes.

We provide straightforward, continuous, and actionable insights into what needs the most immediate attention. Creating guidance on the proper use of Microsoft and other security products for all levels of security skills and driving the management of those insights.

Senserva, an ISV member of the exclusive Microsoft Intelligent Security Association (MISA) and 2024 ISV of the year finalist, was founded by industry leader and Microsoft Security expert, Mark Shavlik, along with TJ Dolan.

 [More About Senserva](https://senserva.com/about)
 
# Install

Please do not use any related zip files on this repository.  Just grab the inq.exe, its signed so double check that first.

These are runtimes only, source available upon request and approval by Senserva.

These run times do not require and services, cloud or otherwise.  The run local and the data stays local.  Web page UI runs off local data, the database is a no server SQLite database. 

There are 3 components, the Inquisitor that reads tenants and puts audit data into a SQlite database.  The Senserva Report Generator reads the database and creates local web files for you to view.  The Senserva Remediator will correct things based on your rules (release coming in a future beta)

There is no setup, just download and go.  No servers and no data leaves your device.

Please Read our terms of use https://senserva.com/senserva-terms-of-use

Usage of SenservaInquisitor.  Run SenservaInquisitor -help after downloading.

# Details

```json

Your JSON here

```






 
