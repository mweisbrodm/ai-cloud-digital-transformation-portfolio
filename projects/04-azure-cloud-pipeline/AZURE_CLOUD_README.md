# Azure Cloud Data Pipeline

## Project Type
Cloud Computing | Azure Architecture | Virtual Machines | Database Services | Blob Storage

## Executive Summary

This project demonstrated a basic Azure cloud architecture for processing a text file, converting it into a CSV file, storing output in Blob Storage, and sending data to an Azure-hosted MySQL database. The assignment required resource creation, virtual machine configuration, database setup, storage configuration, and cloud resource cleanup.

The value of this project is not only the technical setup. It demonstrates how cloud services can be assembled to support a simple business data workflow.

## Business Problem

Organizations often need to process raw data, store outputs securely, and make structured data available for reporting or analysis. Cloud platforms make this possible without purchasing and maintaining physical infrastructure.

This project modeled a small-scale workflow that could support data ingestion, transformation, storage, and database integration.

## Architecture Overview

- Azure Resource Group
- Azure Storage Account
- Blob Storage
- Ubuntu Virtual Machine
- Azure Database for MySQL
- Python script
- CSV output file
- Cloud cleanup process

## Workflow

1. Create an Azure resource group.
2. Create a storage account and obtain a connection string.
3. Create an Ubuntu virtual machine.
4. Create an Azure Database for MySQL flexible server.
5. Create a database inside the MySQL server.
6. Configure the provided Python script with database and storage values.
7. Run the program on the virtual machine.
8. Convert a text file to CSV.
9. Upload the CSV to Blob Storage.
10. Send data to the MySQL database.
11. Clean up cloud resources after completion.

## Tools and Concepts

- Azure Portal
- Resource groups
- Virtual machines
- Linux/Ubuntu
- SSH
- Blob Storage
- Azure Database for MySQL
- Python script configuration
- Cloud resource management
- Pay-as-you-go cost awareness

## Skills Demonstrated

- Understanding how cloud services work together
- Configuring basic Azure infrastructure
- Working with virtual machines and database services
- Connecting storage, compute, and database components
- Following cloud resource cleanup practices
- Translating infrastructure into a business workflow

## Executive Takeaway

Cloud computing allows organizations to build flexible data workflows without owning physical infrastructure. Even a simple architecture can demonstrate the core cloud pattern: compute processes data, storage preserves files, and databases support structured access for future reporting and decision-making.

![Azure Cloud Data Pipeline (Color-Coded)](azure-pipeline-color.png)

