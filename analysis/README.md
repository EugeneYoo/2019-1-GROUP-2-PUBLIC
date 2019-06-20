## How to Import Json Code ?
#### 1. Run Zeppelin Server


#### 2. Browse localhost:8080 / Set your own port


#### 3. Click **Import Note**

![step1](/captures/importjson/1.png)


#### 4. Select .json Files included in this folder

![step1](/captures/importjson/2.png)

## Code 

### prepare
#### Import library
![step1](/captures/CodeCapture/1_importLib.JPG)


#### CSV to pyspark dataframe
![step1](/captures/CodeCapture/2_dataload.jpg)

### DashBoard 1 : Population Map


### DashBoard 2 : Orders Comparison to Other regions
#### Select options (region, store_type, age, gender)
![step1](/captures/CodeCapture/4_selectForm.JPG)


#### Spark processing 
* get five region list in which selected region is median value from df_people dataframe <br>
* compute average of Orders in five regions <br>
* make dataframe which has (Date, Average Order of other regions, Order of selected region) Column <br>
![step1](/captures/CodeCapture/8_daily_hydashboard.JPG)

#### Select Specific options (start date, end date, Daily/Monthly view)
![step1](/captures/CodeCapture/5_selectForm.JPG)

#### Show Chart by Zeppelin
![step1](/captures/CodeCapture/7_daily_hydashboard.JPG)


