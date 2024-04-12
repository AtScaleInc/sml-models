# About this Repository
AtScale's semantic layer platform simplifies the access to data through a unified, business-friendly interface, allowing users with varying levels of technical expertise to understand and analyze data without needing to know complex query languages or database structures. This accessibility leads to better, faster decision-making across all levels of an organization. Moreover, by standardizing definitions and metrics, a semantic layer ensures consistency and accuracy in reporting and analytics, reducing errors and misinterpretations.

This repository contains a variety of semantic models encoded in the **S**emantic **M**odeling **L**anguage (SML).

# Model Library

## Tutorial Models
1. [Internet Sales](models/tutorials/internet-sales) - a simple, single fact model derived from the ficticious AdventureWorks retail dataset
2. [World Wide Importers](models/tutorials/world-wide-importers) - a more complex, multi-fact model that represents a fictional wholesale and distribution company
3. [TPC-DS](models/tutorials/tpc-ds) - a complex, multi-fact model that encodes the [TPC-DS](https://www.tpc.org/tpcds/) benchmark model in SML

# Getting Started

## How to Install AtScale
Download AtScale Developer Community Edition and follow the installation instructions here: [AtScale Developer Community Edition](http://www.atscale.com/community)

## How to Connect to Tutorial Data in AtScale
### How to Use the Pre-configured PostgresSQL Tutorial Data
When you download and install the AtScale Developer Community edition, a PostgresSQL database container with the data for all three models will be installed and configured automatically in AtScale Design Center. 

To explore and query the tutorial models, in AtScale Design Center:

1. **Deploy your Catalog:** Click on the "Repo Browser" icon in the Activity bar (left side) and Press the "Deploy" button.

![AtScale Design Center Deploy Catalog](images/AtScale-Design-Center-Deploy-Catalog.png)

2. **Connect your BI Tool:** Click on the "Deployed Catalogs: icon in the Activity bar (left side) and click on your deployed catalog. Instructions for connecting your BI tools will appear on the right side.

![AtScale Design Center Connect](images/AtScale-Design-Center-Connect.png)

### How to Connect to Snowflake Tutorial Data
The tutorial data for the sample models is available for free in the Snowflake Marketplace. To get access to the tutorial data in the Snowflake Marketplace:

1. **Go to the Snowflake Marketplace:** In the Snowflake console, Click on "Data Products" and then click on the "Marketplace" link.

![Snowflake Marketplace Page](images/Snowflake-Marketplace-Page.png)

2. **Find the "AtScale Tutorials" data product:** In the search bar, type in "AtScale" and select the "AtScale Tutorials" data product.

![Snowflake Marketplace Search](images/Snowflake-Marketplace-Search.png)

3. **Connect to the AtScale Tutorials Data Product:** On the right side of the screen, click on the "Get" button.

![Snowflake Marketplace AtScale Page](images/Snowflake-Marketplace-AtScale-Page.png)

4. **Name Your Database:** Click on the down arrow on the "Options" accordian control and enter `atscale_tutorial_data` in the "Database" field and assign the proper access role. Click the "Get" button.

![Snowflake Marketplace Get](images/Snowflake-Marketplace-Get.png)

### How to Connect to Databricks Tutorial Data

### How to Load to Tutorial Data into BigQUery

## Aditional Resources
