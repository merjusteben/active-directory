# Lab 07: Group Policy Management

## Objective

The objective of this lab was to implement centralized Group Policy settings within the `itlab.local` Active Directory domain. I configured desktop wallpaper, Windows Firewall, and Folder Redirection policies intended for all domain users and IT OUsto demonstrate centralized configuration management and consistent user settings.

## Implementation Steps

### Step 1: Configure Desktop Wallpaper for IT OU

>Configured a Group Policy setting to standardize desktop wallpaper for the IT OUs.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/gpo-wallpaper.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/gpo-wallpaper2.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/gpo-wallpaper3.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/gpo-wallpaper4.png" alt="Azure Active Directory Project Overview" width="350">

### Step 2: Configure Windows Firewall

> Configured Windows Firewall settings through Group Policy to manage firewall behavior centrally. This helps maintain consistent security configurations across the domain environment.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/gpo-firewall.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/gpo-firewall2.png" alt="Azure Active Directory Project Overview" width="350">

### Step 3: Configure Folder Redirection

> Configured Folder Redirection through Group Policy for domain users. This feature redirects supported user folders to a designated network location, helping centralize user data and provide access to redirected folders from supported domain-joined computers.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/gpo-folder.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/gpo-folder2.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/gpo-folder3.png" alt="Azure Active Directory Project Overview" width="350">
