# Supply-Chain
- Create a "Supplier Overview" dashboard, which gives us a supplier status and its capabilities. This will help the resposible Buyer get a focused quick insight for the suppliers.
- Create a "Volume Movement" dashboard, to help analyze the Purchase volume and Tonnage volume movement throught different years for past comparisons and business planning.
- Improving the way our visuals interact with each other, and give more exposure to insightful data.

## Introduction
The Accounts Department of the Company maintains the invoice level details of all vendors for each part procured. The Business Planner receives invoice data from the Accounts Department for each vendor and collects the supplier and part level information separately from the Purchase Department. The Business Planner has to study the relevant data and identify the Procurement trends, Supplier limitations, Product based supplier consolidation and minimise cost impact to company.
* [Supply Chain Overview](https://github.com/KopiteArnab/Supply-Chain/blob/4e35d9ec85ad269462bc7d8110a6ad7e7e3a94f4/Supply%20Chain%20Overview.md)

## Problem Description
As the collected Data is of different years for multiple Plants grouped by different Business Units. The parts are either made of Aluminium or Ferrous of different raw material grade alloys, with the source being either Tier 1 supplier or Tier 2 supplier. Considering all these factors, create a dashboard which is insightful on all these factors and can help the Procurement Department make better supply chain strategic decisions.

## Dataset Description

- [Supplier Data File](https://github.com/KopiteArnab/Supply-Chain/blob/dc877e82a6f09ece00bf1fc9e2b4d0f896e1d383/csv/Supplier%20data.csv):
   - The data is specific to our suppliers, thes are the only suppliers we are responsible for and have to focus on.
   - The data is classified into multiple categories like Commodity,Supplier Number and Name,Buyer Code and Name,MSME,Strategy Status,Payment terms,locations.
- [Material weights and source Data File](https://github.com/KopiteArnab/Supply-Chain/blob/dc877e82a6f09ece00bf1fc9e2b4d0f896e1d383/csv/Material%20weights%20and%20source.csv)
  - The data set consists of part level data with its weight and the source from where our suppliers are getting raw material.
  - The data is classified into multiple categories like Part Number,Part Family,Part Weight(System weight),RM Grade,Supplier Number.
- [Master Report Data File](https://github.com/KopiteArnab/Supply-Chain/blob/dc877e82a6f09ece00bf1fc9e2b4d0f896e1d383/csv/Master%20Report.csv)
  - The data set is a collection of invoice records(Billing data) of the payments made to supplier
  - The data is classified into multiple categories like BU(Business Unit), MCR Material Group, Supplier Number,Invoice Quantity,Invoice Value,Purchasing Group(Buyer     Group).








