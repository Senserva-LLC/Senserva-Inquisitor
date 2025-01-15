<img src="https://github.com/user-attachments/assets/5ce51b46-cdd7-4828-926c-9e9c3ec82460" width="200">

# The Senserva Inq.Uisitor (Inq.exe) Overview

The Senserva Inq.Uisitor (Inquisitor) is a free product designed to make it easier to know the security state of all the Entra IDs a technical team supports.  It can be used by either IT teams or Security teams.

Inq.Uisitor, or inq.exe, runs out of the box and creates the web pages as show before.  It also has a rich set of parameters and uses a Sqlite database to start data.  This data can be used to easily create custom reports.

## SQLite Database

The Senserva Inq.Uisitor is built with SQLite. SQLite is a small, fast, self-contained, high-reliability, full-featured, SQL database engine. SQLite is the most used database engine in the world. [More About Sqlite](https://www.sqlite.org/)

It is easy to work with SQLite in Python and other languages. The Python SQLite3 module is used to integrate the SQLite database with Python. There is no need to install this module separately as it comes along with Python after the 2.5x version. [More About Python and Sqlite](https://docs.python.org/3/library/sqlite3.html) 

SQLite can also be used with Powershell to read Inq.Uisitor data.  [SQLite and PowerShell with SimplySql](https://www.powershellgallery.com/packages/SimplySql/2.0.2.70)

## Web Pages

# Project Status
Runtimes for Senserva - early beta please contact us for assistance and information. Senserva provides public contains with signifigant support, and then we add more for partners and customers who work more closely with us. All for free. Source could available to select partners and customers, please check with us.

## Known Bugs

## What is Coming Next

Scheduling
Containers
Powershell CommandLets

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

# Details

```json

Your JSON here

```
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






 
