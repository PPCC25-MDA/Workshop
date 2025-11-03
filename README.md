# Workshop
Model-Driven Apps Workshop

## Overview

This workshop provides hands-on learning for building Model-Driven Apps in Power Apps. The workshop is divided into three modules covering data modeling, UI/UX design, and business logic implementation.

## Workshop Labs

| Lab | Module | Document |
|-----|--------|----------|
| Lab 1 | Data Modeling | [01- All-In Workshop - Data Modeling Module.pdf](./Labs/01-%20All-In%20Workshop%20-%20Data%20Modeling%20Module.pdf) |
| Lab 2 | UI UX | [02 - All-In Workshop - UI UX Module.pdf](./Labs/02%20-%20All-In%20Workshop%20-%20UI%20UX%20Module.pdf) |
| Lab 3 | Business Logic | [03 - All-In Workshop - Business Logic Module.pdf](./Labs/03%20-%20All-In%20Workshop%20-%20Business%20Logic%20Module.pdf) |

## Solutions

The workshop includes both starter and complete solutions:

- **Starter Solution**: `Solutions/Starter-VehicleInspections.zip` - Use this to begin the workshop
- **Complete Solution**: `Solutions/Complete-VehicleInspections.zip` - Reference this for completed exercises
- **Sample Data**: `Solutions/data.zip` - Import this to populate your environment with sample data

### How to Import the Starter Solution

1. Navigate to the [Power Apps Maker Portal](https://make.powerapps.com)
2. Select your environment from the top-right environment selector
3. In the left navigation pane, click on **Solutions**
4. Click **Import solution** at the top of the page
5. Click **Browse** and select the `Starter-VehicleInspections.zip` file from the Solutions folder
6. Click **Next**
7. Review the solution details and click **Next**
8. If prompted for connections, create or select existing connections
9. Click **Import** and wait for the import to complete
10. Once completed, you'll see a success message and the solution will appear in your solutions list

### How to Import the Sample Data

The `data.zip` file is a Configuration Migration Tool (CMT) package containing pre-configured records to help you test and work with the Vehicle Inspections app.

**Step-by-Step Instructions:**

1. **Download the Configuration Migration Tool**
   - Go to the official Microsoft documentation: [Configuration Migration Tool](https://learn.microsoft.com/power-platform/alm/configuration-migration-tool)
   - Scroll to the download section and copy the NuGet package link (usually ends with `.nupkg`)
   - Download the `.nupkg` file to your computer

2. **Extract the Tool from the NuGet Package**
   - Rename the downloaded `.nupkg` file to `.zip` (e.g., `Microsoft.CrmSdk.XrmTooling.ConfigurationMigrationTool.zip`)
   - Right-click the file and choose **Extract All** to unzip it
   - Open the extracted folder and navigate to the `tools` directory

3. **Launch the Data Migration Utility**
   - In the `tools` directory, double-click `DataMigrationUtility.exe` to start the Configuration Migration Tool

4. **Connect to Your Environment**
   - In the Configuration Migration Tool, click **Import data**
   - Click **Login** 
   - Sign in with your Power Platform credentials
   - Select the environment where you imported the starter solution

5. **Import the Data**
   - Click **Browse** and select the `data.zip` file directly from the Solutions folder (no need to extract it)
   - Click **Import**
   - Wait for the import process to complete - you'll see a progress indicator

6. **Verify the Import**
   - Once complete, you'll see a summary of imported records
   - Open the [Power Apps Maker Portal](https://make.powerapps.com) and check your tables to verify the data was imported successfully