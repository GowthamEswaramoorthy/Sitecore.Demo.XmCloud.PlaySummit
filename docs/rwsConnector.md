# RWS XM Cloud Connector Package Installation Guide

## Overview
This guide provides step-by-step instructions on how to install the RWS XM Cloud Connector Package for seamless integration with your Platform or Website project.

## Installation Steps

1. **Unzip the Connector Package**
   - Unzip the provided connector package for XM Cloud.

2. **Folder Contents**
   - The extracted package will contain the following folders:
     - App_Config
     - App_Data
     - bin
     - sitecore modules

3. **Copy Connector Configuration**
   - Navigate to the `App_Config` folder and copy the `zzz.RWS.Sitecore.Tms.Connector` folder.
   - Paste it into your Platform or Website project under the same folder structure. Example path: `src/platform/App_Config/Include/zzz.RWS.Sitecore.Tms.Connector`

4. **Create and Populate 'rws' Folder**
   - Create a new folder named `rws` at the root of your solution.
   - Copy the DLLs from the `bin` folder in the connector package and paste them into the newly created `rws` folder.

5. **Reference DLLs in Your Project**
   - Reference the DLLs from the `rws` folder in your Platform or Website project.

6. **Copy App_Data Files**
   - Copy the extracted files from the `App_Data` folder into your Platform or Website project. Reference the structure in this example project: `src/platform/App_Data/`

7. **Copy Sitecore Modules**
   - Copy the extracted `sitecore modules` folder from the connector package.
   - Paste it into your Platform or Website project. View the example reference [here](src/platform/sitecore%20modules/RWS/).

8. **Commit and Deploy**
   - Commit your changes and deploy them to your XM Cloud instance.
   - Verify the changes in the RWS Connector.

9. **Configure Connector Credentials**
   - On your XM Cloud instance, configure your Connector credentials in `/sitecore/system/Modules/RWS Translation Module/Settings` item.
   - Start using the translation functionality.

Follow these steps carefully to successfully install and configure the RWS XM Cloud Connector Package.