![maico-amorim-SJWPKMb9u-k-unsplash](https://github.com/Kamorrra/global_bike_sales/assets/106885170/9777f63d-f5bc-40c8-bf7d-8525697c2c85)

**OVERVIEW**

My architectural background has drawn me to constantly factor in the state of the world's relationship with sustainability. As years past, the formation of pedestrian-friendly cities in battle against climate change are increasingly in the interest of nations across the world. This project sheds light on one of the ways that nations are addressing carbon emissions, Bikes. Within this project, we take a look at global bike sales and extract some insights from our findings.

------------------------------

**APPROACH**

Gather data related to Bike sales made globally that sheds light on sales demographics, marital status, income, and much more. We will then clean and transform our gatherings in order to pull insights about recorded global bike sales.

------------------------------

**TOOLSET**

- `Excel` `Tableau`

------------------------------

**ORIGINAL DATASET**

Below is a sample of the [[original dataset](https://github.com/Kamorrra/global_bike_sales/files/13192505/GlobalBikeSales.xlsx)]. I discovered areas where columns can be made clearer in order for audiences to understand exactly what it is that they are viewing while optimizing columns for later visualization.

<img width="947" alt="Bike_Sales_Original" src="https://github.com/Kamorrra/global_bike_sales/assets/106885170/18fc3ed2-40fb-4863-a9b5-e604688a4e13">

------------------------------

**PREPARED DATASET**

Although seemingly subtle, the prepared dateset optimizes columns and cells for visualization in the next step. One highlight of the data transformation takes place in the "Age Bracket" column where I was able to catergorize customers based on their age into categories named **Adolescent**, **Middle Age**, or **Old** using the formula below:

"**=IF(L598>55,"Old",IF(L598>=31,"Middle Age",IF(L598<31,"Adolescent","Invalid")))**"

<img width="1414" alt="Bike_Sales_Clean" src="https://github.com/Kamorrra/global_bike_sales/assets/106885170/419143f9-f4aa-448d-9284-733788f8f431">

------------------------------

**DASHBOARD**

Below is a dashboard I created using Tableau with filtering capabilities that offer a visual understanding of our insights. [Click here](https://public.tableau.com/app/profile/mike.kamorra/viz/GlobalBikeSales_16964145781460/Dashboard1) to use and interact with the dashboard in realtime.

![Dashboard 1](https://github.com/Kamorrra/global_bike_sales/assets/106885170/1630ac3a-e736-40f6-8ae4-f5704aff16ea)
