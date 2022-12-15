# IaC 2 - PowerShell
[<img src="https://img.shields.io/badge/PowerShell%205.1%20&%207.3-Ready-blue.svg?color=5391FE&style=flat&logo=powershell">](https://microsoft.com/PowerShell)

<h2 align=center> 📑 Introduction </h2>

For the deliverables, repository was created with Powershell scripts which were introduction to PowerShell scripting. Each walkthroughs represents diffrent study material covered as part of the IaC module.

<h2 align=center> 📃 Scripts Available </h2>

Following four directories were craeted:
   - ***Walkthroughs - 1. Installing Powershell 7*** - this directory contains set of scripts to install PowerShell7 on Windows 10 machine.
   - ***Walkthroughs - 2. PowerShell Variables and Loops*** - folder has some basic set of scripts, which show how to work with variables, types, loops and usage of piplines.
   - ***Walkthroughs - 3. Remote Control*** - folder contains scripts which can be used to:
  	    - installing Active Directory and promoting server to become Domain Controller (Setup DC1.ps1, Setup DC2.ps1)
        - installing DHCP server (DHCP.ps1)
        - Removing domain controller role (DemoteDC.ps1) 
        - creating OU structure and importing users (PGDipCLOD2022.ps1)
        - VM backup using export method (ExportVMs.ps1)
        - Get Storage reliability counters for the specified disk (DiskRecce.ps1)
-  ***Walkthroughs - 4. W2019 DSC***  - set of scripts to configure Desired State Configuration (DSC) on the server

<h2 align=center> 📃 Usage</h2>
  - Each folder contains the scripts, download the .zip file on the main page of the GitHub and extract the .zip file to your local PC.</br>
  - Extracts the files</br>
  - Open PowerShell as an Administrator</br>
  - Enable PowerShell execution <code>Set-ExecutionPolicy Unrestricted -Force</code></br>
  - Scripts tested with version 5.x and 7.x on Windows 10 and Windows 2019</br>
</br>
<h2 align=center> 🧑 Contributors </h2>
Student: L00177544

<h2 align=center> 📃 Updates</h2>

- 1.1 / 15-12-2022 
  - [x] Modifed script content using Feature_branch
  - [x] Updated README.md
- 1.0 / 12-12-2022 
  - [x] Initial entry
