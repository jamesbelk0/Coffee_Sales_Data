# Coffee Sales Data
## Discovering customer spending habits

**James Belk**: 

<p align = "center"> 
  <img src = "https://github.com/jamesbelk0/Coffee_Sales_Data/blob/7564891adea3f22437e8468f161eee666d50c874/coffee_beans.jfif">
</p>

### Business problem:

Discover the spending habits of customers to maximize profits and limit margins.

### Data:
Coffee Sales Data - https://github.com/jamesbelk0/Coffee_Sales_Data/blob/7564891adea3f22437e8468f161eee666d50c874/coffeeOrdersData.xlsx
For this dataset, there are 1,000 rows and 16 columns

### Data Dictionary:

* Item_Identifier - Unique product ID
* Item_Weight - Weight of product
* Item_Fat_Content - Whether the product is low fat or regular
* Item_Visibility - The percentage of total display area of all products in a store allocated to the particular product
* Item_Type - The category to which the product belongs
* Item_MRP - Maximum Retail Price (list price) of the product
* Outlet_Identifier - Unique store ID
* Outlet_Establishment_Year - The year in which store was established
* Outlet_Size - The size of the store in terms of ground area covered
* Outlet_Location_Type - The type of area in which the store is located
* Outlet_Type - Whether the outlet is a grocery store or some sort of supermarket
* Item_Outlet_Sales - Sales of the product in the particular store. This is the target variable to be predicted.

## To prepare this data, the data was cleaned of extra rows and unneeded columns.The following processes were performed:

### Exploratory Data Analysis

 - During the exploratory data analysis, used the XLOOKUP and INDEX functions to combine information to a single "orders" spreedsheet for easier analysis. 
 - Created three new columns "Coffee Type Name", "Roast Type Name" and "Loyalty Card" for easier visualtions.
 - Created a pivot table to perform analysis and create visualizations

## Explanatory Visuals

<p align = "center"> 
  <img src = https://github.com/jamesbelk0/Coffee_Sales_Data/blob/7564891adea3f22437e8468f161eee666d50c874/Coffee_Sales_Dashboard_Screenshot.PNG>
</p>
