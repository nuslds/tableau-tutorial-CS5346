

# I. Connecting to a Data Source

Tableau is compatible with difference data sources.
![f1](../screenshots/f1.png)



The following features will be covered in this section.

- Data predview
- Metadata view
- Filter data
- Joining table



## Demo 1

We will be working on a sample Excel data data in this tutorial. For more information about data connectors in Tableau, please visit this [guide](<https://help.tableau.com/current/pro/desktop/en-us/datasource_prepare.htm>).

- Click [here](sample_data/sample_1_superstore.xls) to download the data ([source](<https://community.tableau.com/docs/DOC-1236>))
- Select `Microsoft Excel` and open the downloaded file

![f2](../screenshots/f2.png)



- The list of worksheets is displayed under the `Sheets`.

![f3](../screenshots/f3.png)



- You can take a quick look at each sheet.

![f7](../screenshots/f7.png)



- To import a sheet, do a simple drag and drop. You will be able to preview the data and the metadata (the list of fields).

  ![f4](../screenshots/f4.png)

  

  ## Demo 2

  - **Data Preview**

  ![f5](../screenshots/f5.png)

  

  - **Metadata View**
  
  ![f6](../screenshots/f6.png)



## Demo 3

- To filter the data, select `Edit Data Source Filters...` from `Data` - Click on`Add..` to select a field to filter - Choose what to exclude or to include - Click on `Ok` to apply the data filter. You can add more than one data filters. 

![f9](../screenshots/f9.png)



For complex filtering, try out `Wildcard`, `Condition`, and `Top` features. 

![f10](../screenshots/f10.png)





## Demo 4

You can join multiple sheets easily in Tableau. Drag another sheet and explore different ways of table joining.

- **Inner**: Include values that have matches in both tables only
- **Left**: Include all values from the left table and corresponding matches from the right table
- **Right**: Include all values from the right table and corresponding matches from the left table
- **Full Outer**: Include all values from both tables

![f8](../screenshots/f8.png)



##Demo 5

There is another feature called union in Tableau which allow you to join the rows.

- Click on `New Union` - Drag the tables you want to union into the box - OK

![f11](../screenshots/f11.png)

![f12](../screenshots/f12.png)

