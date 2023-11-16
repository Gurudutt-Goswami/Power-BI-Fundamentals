# Power-BI-Fundamentals


### What is Business Intelligence?
Set of techniques & tools for the transformation of your raw data into meaningful & useful information to take important business decisons.

### Why Power BI?
1) Access vast volume of data from multiple sources
2) Interactive UI/UX Features
3) Exceptional excel integration
4) Accelerate big data preperation with Azure
5) Turn insights into action
6) Real time stream analytics

### Features of Power BI
![1  Features](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/44e54963-c25f-4993-ab10-ccb35a0f8415)

### Power BI Components
```
Power Query is a data transformation & mashup engine.
Power pivot is a data modelling & calculation engine. Uses DAX(Data Analysis Expression) queries to model data.
Power visualisation is the visualisation component.
Power Map is used to map geospatial data in 3D mode. Works with bing maps to get visuals based on longitude, lattitude, country, state, city etc.
Power BI desktop is a Dev tool that contains (Power query + Power pivot + Power View)
Power Q&A is a natural language engine for your questions & answers on top of your data model.
```
#### Power BI 
Power BI is Saas(Service Software as a service) part of Power BI. Also called power bi online.(app.powerbi.com).
Here you can create dashboardS on canvas where we refer each visual areas as tiles. 
It allows you to create different reports on Power BI dasktop. These reports can be published on to power bi dashboard using Power BI service.

### Power BI Architecture
![2  power bi architecture](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/b9747de3-3498-4fdc-9fec-3fbc07f4ba4a)


### Power BI basics
1) Report (Visuals area)
2) Data (Table transform area)
3) Model (Relationship area)

### Power BI | Tableau
1) Microsoft Product | Salesforce aquired tableau
2) Supports NLP for Q&A for data insights | Tableau is also going to have this in near future
3) Very easy to integrate with microsoft products like excel,csv,azure etc. but not very diverse compared to tableau when it comes to data source connection.
4) Uses DAX Expression & M language for data manipulation & data modelling can also connect with R languages with Microsoft revolution analytics | Connects much better with R comparitively




```If you torture the data long enough, it will confess to anything.       - Ronald Coase (Noble prize Economist)```


### Why we should choose power BI

### How to upgrade latest functionalities

### Charts Created
1) Column Chart
2) Stacked Column Chart
3) Pie Chart
4) Donut Chart
5) Ribbon Chart  
Best chart if you want to see ranking order of any set of items per year along with their values
![ribbon chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/52ec286e-ccb6-4a79-a92e-32bda69f65d6)

6) Include & Exclude  
You can instantly include or exclude anything on visual level
![Include   Exclude](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/fe08ff17-e81d-4254-a20e-9290a388f371)

7) View data & Export  
You can right click any part of visual & see its corresponding data by clicking on 'show data pt as table'  
![show data pt as table](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/a4675b37-4c1e-4d3a-8a00-c5ec91d4471e)
You can also export the entire table or subselected data of any visual in csv format  
![export data](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/b6e21a81-e6b2-4956-b9da-89ff83a425fa)
You can hide whether user can do this table visual for any chart by :  
--> File --> Options & Settings --> Options --> Report Seeting (In Current File) --> check 'dont allow user to download data'
![restrict user to not see tables](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/094abfc3-fb6c-4e13-9277-f84a61eecadc)

### Map Chart
![map chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/7298ae93-2678-4027-b587-588f0b73f158)

#### Bubble with pie
Just add your legend & followed by bubble size value column 
![bubble with pie](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/90d304f2-def5-458d-91eb-4d81ac4b0dea)

#### Filled Chart
![filled chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/ced701be-0ac6-4629-bafe-605abef436ad)

#### Formatting 
1) You can individually format any bubble color
2) You can change even  background color of state label & map chart
3) You can even change tool option & values color separately & there are many other things like themes as well when it comes to formatting in map.
4) Note you can directly copy to clipboard & paste the data using 'enter data' icon.
![formatting map](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/4e1618c3-1b07-480a-ad98-decb9a10dba5)

### Conditional formatting
![table formatting](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/fe014bac-19f1-48b1-b2d0-1b821ec953fe)


#### Change aggregation of a field in table 
Note : If you want to see a single column in two or more aggregations then add that column multiple times & change aggregation in its multiple appearences.  
```To set a common theme for the entire dashboard go to view --> customise current theme```
![change aggregation of column](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/cc7a63dd-6566-4513-9391-67f61a7a440e)



### Matrix
![normal table vs matrix](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/b5933001-e7b3-48c6-8bba-fc8958641d8b)
Note : In earlier versions you will conditional formatting options for tables but in current version conditional formatting comes as cell elements. This you can apply via adding bars, text colors , icons or web url.
#### Matrix conditional formatting
![matrix formatting](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/768b04d7-4cc3-41d2-9f4c-cf7134b0b2e7)
#### Hierarchy in matrix
To make hierarchy just drag & drop fields under rows one below the other & a plus symbol will appear to drill down the values. You can add as many fields as you want. Also lets say you added a date field in values section then in the visual while drill downing you have to first select rows/columns which you want to drill down.  
Note : You can hide & format subtotal & Total of rows in the matrix .  
![hierarchy in matrix](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/63b0980c-e1d0-4006-8465-4054ad355e28)



### Some Other charts

#### Line Chart
trend over time  
![line chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/9f06fd2e-adf9-4ff6-b8c1-79af497f1878)

#### Area chart
![area chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/2af9ac6b-da53-446f-a875-dc376e752eca)

#### Line n clustered column chart
provided side by side comparison  
![line   clustered column chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/a6379ea0-4b26-49c9-bae0-c1997ba07fec)

#### Scatter Plot
Used to compare two measure relationship.  
Also this is only chart in power bi which has animation in it.  
For example lets suppose you wanted to see profits per year of different category items, then you can animate the same, along with lines connecting dots showcasing for all or selected items per year.

#### Line n Stacked chart
![line   stacked chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/eba864fb-0fc6-45db-b24b-41d2d9c0b77b)

#### Waterfall chart
![waterfall chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/0db2afda-a931-48b3-98ac-22185e8700a1)

#### Tree Map
hierarchical or descending showcase  
![tree chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/788cb0c3-3e91-43ab-9880-15147aebc96b)


#### Gauge Chart 
used to compare current value with target 
![guage chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/7798e177-84d3-4d1b-b2e2-98d1e75ca717)


### Cards & Filters

#### Number card
Card number will change as per selection in other visuals  
![number card](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/16039526-fbf6-4d42-bc18-b96c2e1c5148)

#### Text card 
To show highest profit,sales & quantity in card just add that field into the filter section, select top n > add that field > apply filter & change the text of the card.
![text card](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/fd90c61c-f438-4c9a-8bfd-d5ffc79c8f6d)

#### Date card 
Similar to text card we can add date field in filter on visual section & can view relevent results. But the good part is lets suppose we wanted to see something for a specific time period, lets say highest profit in last 2 years for that we can add date field in filter on visual section & then select relative dates options, here we get the option to set the range for which we are interested in.

#### Mulit row multi column card
Just like text & date card add field to the filter section & apply for top 3, this is a bot more fruitful then card as it shows multiple thing at once which can also be effected based on selection on other visuals.
![multi row card](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/438593f1-bb36-49e2-b7c0-70338fdf3298)


### Filter & Drillthrough
1) Filter on this visual
2) Filter on this page
3) Filter on all pages
As the names suggests they do exactly according to their name, so you can add multiple fields in any of those sections to use it.
4) Drillthrough : Lets suppose you have 3 pages PMO, Manager & associates and you want to see only respective managers which has been selected in PMO & so for the associated then you need to add this designation field in the drill through section in manager & associates. After this when you select anything on PMO > righ click > drill though then you will see managers & associates pages & on click you will go onto that page which will only contain values selected in PMO tab & this will work similar for managers tab as well.


### Slicers (Interactive filters)
You can add a slicer & a column to it, in this way it will be available for end users to select certain choices to filter on. Also you can add multiple columns in a single slicer in order to create a hirarchy for example lets suppose we have a state column then we can add city column under it, so if we are showing some bar chart for top 5 sub category profits, user can select any city under any specific state to look for its details. Also instead of selecting only single value & pressing ctrl to select multiple values you can change this into formatting section & many other aesthetics things as well like their alignment,color, fonts etc.

![slicers](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/e4da3e40-8858-4b35-bcd1-7ec1fa38de68)
Relative Date Slicer  
![date slicer](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/4e6c1166-169f-42d9-8c09-612a3a4adf83)
![relative date slicer](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/4c1df576-f8e2-48e5-8682-a075d1ef5e8e)  
Instead of a slider make k hirarchy  
![date slicer instead of slider](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/3388ee83-11f9-4543-85ff-07fc24dc38a6)
