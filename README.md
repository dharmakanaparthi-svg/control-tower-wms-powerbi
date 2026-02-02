# Control Tower for WMS – Power BI Template App

## Overview
This Power BI Template App provides operational visibility into Warehouse Management System (WMS) data including throughput, lead time, inventory movement, and order processing KPIs.

## Prerequisites
- Power BI Pro or Premium
- Access to SQL Server database
- On-premises data gateway installed and running
- Valid SQL credentials

## Parameters Required During Installation

### 1. Server Name
Enter the SQL Server name in the following format:
vm-powerbidb.database.windows.net
 

### 2. Database Name
Enter the database name:
hindwaredb

Installation Steps:
1. Download the app from Microsoft AppSource.
2. Open Power BI Service or Power BI Desktop.
3. Import the app from Apps > Get apps.
4. Complete installation.

Configuration Steps:
1. Open the installed app.
2. Navigate to Settings.
3. Provide required parameters such as:
   - Server Name
   - Database Name
   - User Credentials (if applicable)
4. Save the configuration.

Connect Data:
1. Select "Connect Data".
2. Enter the required credentials.
3. Validate the connection.
4. Load data into the dashboard.

Supported Data Sources:
- SQL Server
- Azure SQL Database
- REST API (if applicable)

Troubleshooting:
- Ensure credentials are correct.
- Verify firewall/network access.
- Check gateway configuration if using on-premise data.

## Support
For support, contact:
support@technoforte.co.in
