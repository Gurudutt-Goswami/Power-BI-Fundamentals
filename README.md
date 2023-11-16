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

Note: For any fields after its addition to slicer you can their types as well.


### Advanced Custom Charts
To add third party visuals you can click on three dots available at the bottom of the visuals section & add your either university or organisation account to that. 
After that you will see following screen, note that here in this app service you will see apps with blue ticks which means those are microsoft certified apps. You also can see ratings for all cutomised visuals.

f![app source](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/0f7d9500-7f20-4bce-b125-03c34d24ea24)


Note : When using custom visual apps it can hamper dashboard performance.

![advance charts](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/59270b6f-67a0-4e54-8594-24095e31f141)

#### Animated Bar Chart
![animated bar chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/91113f1a-a008-4311-b2b8-a6794039e133)

#### Drill Down Donut chart (zoomcharts)
Note : This is from zoomcharts so formatting will not be free you need to buy full version.
![drill down donut chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/00c1475e-f35e-4385-ac58-2ac21d31062b)

#### Drill down column chart (zoomcahart)
![drill down column chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/7f4dea10-0eb4-4462-96a2-d83321fc6b6e)

#### Word Cloud
![word cloud](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/8068cd05-fa21-4b0d-a092-7ae1a157295b)
![word cloud 1](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/44735b94-68c5-4b5b-a5df-83e4c34dbb1c)

#### Sankey Chart
To show relationship between two categories this chart is used.
The thickness of lines will tell from where we are getting most profits.
To get names of relationships on the line itself we can enbale data link label from formatting panel.
![sankey chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/6e128749-d302-4fca-a5f3-80af4029daf9)


#### Infographics chart
In this type of chart you can upload any image instead of normal bars & those images will appears as bars. Also you can format the images as normal.
![infographic chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/ac036f9d-d659-4620-b90d-5cee399e7e2a)


#### Play Axis
This is a dynamic slicer that has play, stop, forward, backward icons just like a video player add a date field into it along with other visual & when click play button the visuals will change as per your date field.
![play axis](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/282bdc37-cd5a-41fb-825d-773702f6a269)

#### Scroller
This is to add a scrolling dynamica bar that contains values just like stocks details
![scroller](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/f1909246-e715-4b7c-8e48-d2c330197af4)


#### Sunburst
![sunburst chart](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/038aeab1-8908-4276-9229-795edc1069fb)

#### Insert an image, textbox, shapes and buttons
To add an image go to insert -> Image (from elements section). Just like any other things you can format these images. Similarly you can add anything.
You can also add web URL/page navigation/back button/drill through/bookmark to these things by selecting & editing their action in formatting so that whenever someone clicks he will be redirected.
Note : To add bookmark you first need to create bookmark from View -> Bookmarks  
![buttons](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/7f307979-6ad5-483c-9484-3e9ca74fc4f7)  
![bookmark](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/f2c06212-cc91-4d24-9c5c-a42722043f55)  
For drill through just select drill through in action of the blank button & select that page on which you want to go.
![drill through](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/fd4001f2-b543-4831-8a60-29e5d0a15a65)


### Sample Report 
![report](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/f2d0ba7b-2ff7-4382-8a7b-16c626a6869f)

#### Power BI Service
![power bi service](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/41132b8f-cb9c-4862-8e68-aa4cf3862094)

#### Publish 
From home menu click on publish & login once you have logged in you need to create a workspace to publish you workbooks/dashboard. After login you can select that workspace & publish the workbook, one pop up with the link will come up which you can share with other just like any other tool.

#### pdf,ppt, pbix or web
You can export the report into ppt/pdf/pbix directly from power bi service.
Also if you have admin right you can embed this report into your custom web pages by embedding the link you get.
![ppt pdf](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/32d36190-f475-4b8f-b9eb-5e5a017654f9)
![web](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/81c78a25-98ec-47a5-815f-97d738cbb7a5)

#### Comment, share & subscribe
Comments : You can add a comment for the published report & to notify any people via comment just write @personname.com & that person will get notified via mail.
![comments](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/2745b8d0-07d6-4a44-9112-6f6652795c56)

Share : Once you have commented or shared the report to any person make sure that person has access & for that go to share then to access tab & make sure to give Editor/Owner/Readonly access to that user.
![share](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/7e5990f4-3e17-4f02-9158-60f88bc22164)

Subscribe : Lets suppose you have to send report to certain team members on friday 4 pm weekly then you can use subscribe & mention a sample mail along with time on which they should get notified. Here you also need to select which page out of your report they will get. Though you can have multiple subscriptions.
![subscribe](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/91583177-bd8d-4120-987c-df783e9d4d01)
![subscribe 2](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/c6e8cbb0-ad8e-496b-979c-a30e7189a26b)


#### Dashboard 
You can click on pin icon of any visual inorder to make that visual part of the dashboard. Or you can also create a dashboard from my workspace from scratch.
Once its done you will get a pop from where you can see the dashboard or from my workspace you can go.
![dashboard](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/cb540718-8c4f-479c-aacc-553d3020b194)
See all things (dashboards/workbook/reports/datasets) can be seen from my workspace
![dashboard 1](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/9700515b-442c-4418-b336-cfe658402e48)

#### Theme
![dashboard theme](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/26708353-5c97-45dd-950d-20cddf5db7e8)

#### Problem with dashboards
When you create a dashboard from pinning visuals then on clicking that visuals from dashboard it goes back to its origin so can't filter any visuals on dashboard. So to fix this you can use pin a live page option to convert entire report as a dashboard.
![pin a live page](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/91091403-f47c-4586-ba17-07862133f820)

#### Automatic Refresh - Data Gateway 
When you publish a report, a respective data set is also gets published, so now lets suppose you want that power bi service should automatically refresh your data set, then you need to configure data gateway else without configuration if you refresh a dataset in order for your report to load latest data you will get an error like following 
![error](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/8f82996a-f795-4138-bb65-8ceb8aa2d3db)

You can configure it via gateway connection or right top side option. Note for this to be able to configure you must have admin permissions. Also once it configures it will be shown in gateway configuration.
![gateway](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/c68f2fa3-d005-4968-b5dc-6aa261067ab8)
![gateway config](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/d0dac6a9-6eac-4153-b0fe-4df99e7e0bbc)
After that try refreshing data set to load latest data, in case you get any error check the setting for that data set, may be you have not configured something.
![settings](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/a44dc5c8-0c03-414b-9118-8548e2b3a2ac)
Lastly you can schedule the data set to refresh on a certain time, on pro account you can do this 8 times per day & with premium account you can refresh 48 times per day.
![schedule](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/b2ec6d39-57e5-4816-8734-5827b2dfdb86)



### Power Query 
Common tool between power bi & excel (data -> new query)
![power query in excel](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/a4442543-7f86-4164-9a44-92dce5be0166)
![function](https://github.com/Gurudutt-Goswami/Power-BI-Fundamentals/assets/86184439/90edc7df-4606-47e6-89dd-371fba51372e)


#### Text Functions
1) Merge
2) Split column & trim (format)
3) Upper, lower & proper (format)
4) Prefix & suffix (format)
5) Left, right & mid (Extract from add column not from tranform)
6) Extract text with delimeter (Extract from add column)

#### Date Functions
1) Year, month, quarter, day
2) Different, earliest & latest
3) Name of the day/month & then using firstcharacter to 3
4) Day of month,week & year
5) Week of month/year
6) Extract date from date & time
7) Age
8) Day of year (Start of yr - DOB), quarter(Start of Qtr - DOB),month your DOB

#### Number Functions
1) DMAS (standard)
2) %, percent of, modulo
3) Rounding the numbers
4) Even/Odd & Sign
