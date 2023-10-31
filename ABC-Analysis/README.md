# ABC Analysis of Inventory

## Table of Contents
* [Introduction](#introduction)
* [Tools](#tools)
* [Approach](#approach)
* [Entity Relationship Diagram](#entity-relationship-diagram)
* [Step by Step ABC Analysis](#step-by-step-abc-analysis)
* [SQL Query & Microsoft Excel Workbook](#sql-query--microsoft-excel-workbook)
* [Results](#results)

## Introduction
ABC analysis is a popular inventory management technique that categorizes inventory into three segments based on the value or importance of each stock-keeping unit (SKU). It is done to understand which segment of the inventory is most valuable or critical to the business. Through this analysis, organizations can rank their inventory and manage them efficiently.

The value of each of the units or Stock keeping units (SKU) is analyzed and segmented into 3 buckets or segments — **A**, **B**, and **C**.

* **A**: High-value items which represent a smaller portion of the entire inventory. These items are most valued and critical to the business and are closely tracked and managed.

* **B**: Medium-value items are not as critical as segment A items, but they are still tracked and managed.

* **C**: Low-value items represent a large portion of the entire inventory. These items are not as closely tracked and are managed more loosely.

## Tools 
* MySQL
* Microsoft Excel

## Approach
* Calculate the **revenue** of each product and sort it in descending order.
* Calculate the **cumulative revenue**, **percentage of cumulative revenue**, and **percentage of inventory** for each product.
* Based on the **percentage of cumulative revenue**, each product is assigned a segment - A, B, or C.
* Calculate the **total inventory**, **percentage of inventory**, **total revenue**, and **percentage of revenue** for each segment.
* For graphical representation, plot **percentage of inventory** on the x-axis and **percentage of cumulative revenue** on the y-axis. 

## Entity Relationship Diagram
Two data tables are used: `products` and `order_details`.

![Entity Relationship Diagram](https://github.com/ritusantra/SQL-Projects/assets/75059347/7835b3cd-1739-4ff1-accf-0eb1d8f5d225)

## Step by Step ABC Analysis
[Step by Step ABC Analysis](https://medium.com/@ritusantra/abc-analysis-using-excel-sql-da3d158b0c18)

## SQL Query & Microsoft Excel Workbook
* [SQL Query](https://github.com/ritusantra/SQL-Projects/blob/main/ABC_Analysis/ABC_2.sql)
* [Microsoft Excel Workbook](https://github.com/ritusantra/SQL-Projects/blob/main/ABC_Analysis/ABC%20Analysis%20Final.xlsx)

## Results
* ABC Analysis using SQL

![Result Image](https://github.com/ritusantra/SQL-Projects/assets/75059347/eafb543b-92ee-4c88-b25d-6db0a8d990ce)


