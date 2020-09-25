# PeopleSoft Migration to Oracle Cloud Infrastructure (OCI)

## Introduction
In this hands on lab, the users are provided with step-by-step instructions on setting up a user group, creating and adding users to group, creating compartment and respective policies in the Oracle Cloud Infrastructure (OCI). Subsequently, this guide instructs how to install the Cloud Manager 11 using Marketplace. The final section provides the steps to provision a PeopleSoft Environment followed by some simple hands-on exercises for you to get familiar with the system.

The lab is divided into the following sections:

## Overview of Labs

Lab 100: Setup Oracle Cloud Infrastructure.

Lab 200: Create Identity and Access Management (IAM) resources.

Lab 300: Provision Peoplesoft Cloud Manager using Marketplace.

Lab 400: Configure Cloud Manager Settings 

Lab 500: Subscribe to PeopleSoft Download Channels 

Lab 600: Review and Update a Topology

Lab 700: Create a new Environment template

Lab 800: Create Environment in Peoplesoft

## Time duration

Lab 300 should take about 90 minutes approximately for runnign the bootstrp script after provisioning Cloud Manager resources. 

Lab 500, when you subscribe to download channels, time taken for downloads to complete depends on network speed and the number of subscribed download channels. If only one application channel and one PeopleTools channel with only the latest patch is subscribed, then downloads should complete in about 60 to 90 minutes depending on the download speed. 

Lab 600, 700, 800, should take you approximately 60 to 75 minutes, you will be able to create a Topology, an Environment Template and provision a new PeopleSoft environment.


## Reviewing Pre-requisistes

1. User already has a tenancy with Administrator user access. 

2. My Oracle Support credentials. Please make sure that you can successfully login to https://support.oracle.com. Note down this login credential in a notepad, you will use it later to configure Cloud Manager.

3. User brings their own workstation/laptop to access OCI console, PSFT Cloud Manager and provisioned instances. 

4. User has access to a workstation/laptop with the following installed:

	a. If you have a windows machine, please download Git Bash for Windows from here: https://git-scm.com/download/win  

	b. User must have admin privileges on their laptop to update the **etc/hosts** file to be able to add URL/IP address for PSFT Cloud Manager. Please let the team know if you can't get this access.

	**NOTE: If you don't have admin privileges in your local machine, please make sure to follow Lab Windows VM Compute Lab during Lab 300 before starting Part 6. You can use the windows compute to follow this Workshop. Please also make sure to install Git Bash in Windows Compute.**

	You will also need to install **Remote Desktop Connection** in your local machine from this [link](https://www.microsoft.com/en-us/p/microsoft-remote-desktop/9wzdncrfj3ps).

	c. A web browser to connect to OCI web console and Cloud Manager PIA – Firefox or Chrome recommended.

	