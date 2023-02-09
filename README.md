# Supply-Chain
Create a "Supplier Overview" dashboard, which gives us a supplier status and its capabilities. This will help the resposible Buyer get a focused quick insight for the suppliers.
Create a "Volume Movement" dashboard, to help analyze the Purchase volume and Tonnage volume movement throught different years for past comparisons and business planning.
Improving the way our visuals interact with each other, and give more exposure to insightful data.

## Introduction
The Accounts Department of the Company maintains the invoice level details of all vendors for each part procured. The Business Planner receives invoice data from the Accounts Department for each vendor and collects the supplier and part level information separately from the Purchase Department. The Business Planner has to study the relevant data and identify the Procurement trends, Supplier limitations, Product based supplier consolidation and minimise cost impact to company.

## Problem Description
As the collected Data is of different years for multiple Plants grouped by different Business Units. The parts are either made of Aluminium or Ferrous of different raw material grade alloys, with the source being either Tier 1 supplier or Tier 2 supplier. Considering all these factors, create a dashboard which is insightful on all these factors and can help the Procurement Department make better supply chain strategic decisions.

## Overview
- Decluttering of supply chain is important process, many times we have multiple Tier 2 suppliers for our Tier 1 supplier, we always try to combine business. Having few Tier 2 suppliers will give more control over the supply chain.
- In case of a reduction in future forecast it is wiser to consolidate business with few best suppliers in advance, then have multiple suppliers.
- Supplier capabilities are into 2 categories, Casting and Machining. In case a supplier have both will be taken as fully capable, indication they would not need Tier 2 suppliers.
- A group of similar parts are combined into one "Part Family" and combination of many part families create the final product. Multiple suppliers supplying same part families create competition, this competition will help reduce prices and increase business with the cheapest supplier.
- Raw Material Grade is a way of classifying metals.There can be different types of metal alloys, which will be classified with a standard names.
Ferrous Commodity will have different types of Raw material grades than Non-Ferrous.
- MSME categories are basically divided into 3 sections
   Micro 
   Small
   Medium
- Any MSME type suppliers must be paid within 45 days as per government rules. Non-MSME companies are considered as Big companies, where this MSME rule don't apply.
- As we don't have any payment terms restrictions for Non-MSME suppliers. We can target those suppliers and increase our payment terms, in turn increasing cash flow in our company(indirect savings).
- Payment Terms that Supplier and the Buyer have agreed on.Number of days mentioned in Payment terms decides when the payment will be made to the supplier after the date of invoice.
- The higher the days of payment are, the better. It is an indirect savings to the company.
- Non-MSME suppliers are more financially stable and they will easily invest for new business if awarded, but in case these suppliers are categorized as 
NoGo we will not be able to award any business with them. Which puts a good resourceful suppliers growth on hold.
- Strategy Status  is an internally defined classification for suppliers to decide future business prospects.
- Go/NoGo-Defines if its wise for the company to grow(increase) more business with the Supplier based on Contracts,Insurance,Financial Risk,Internal Business plan and Supplier Dependency.
   Go - can Grow business
   NoGo - Not to Grow business
- Please note that will always filters any buyer code from the Supplier data table only. Every Buyer is assigned with a buyer code till his time in the company.
- In case of a supplier handover to a different buyer, the buyer code related to that supplier also changes.
- In this case one supplier can have different buyer codes (Purchasing Group) during the years. So to avoid confusion we always use buyer code from
supplier data as per the current running situation. Improving the way our visuals interact with each other, and give more exposure to insightful data.











