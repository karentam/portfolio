# Data Analysis Portfolio
## Karen Tam ##

-- Create a new table by combining all trip data from Jan 2022 to Dec 2022 in 12 tables

CREATE TABLE tripdata_2022.tripdata_2022_all AS
SELECT * 
FROM tripdata_2022.tripdata_202201
UNION DISTINCT
SELECT *
FROM tripdata_2022.tripdata_202202
UNION DISTINCT
SELECT *
FROM tripdata_2022.tripdata_202203
UNION DISTINCT
SELECT *
FROM tripdata_2022.tripdata_202204
UNION DISTINCT
SELECT *
FROM tripdata_2022.tripdata_202205
UNION DISTINCT
SELECT *
FROM tripdata_2022.tripdata_202206
UNION DISTINCT
SELECT *
FROM tripdata_2022.tripdata_202207
UNION DISTINCT
SELECT *
FROM tripdata_2022.tripdata_202208
UNION DISTINCT
SELECT *
FROM tripdata_2022.tripdata_202209
UNION DISTINCT
SELECT *
FROM tripdata_2022.tripdata_202210
UNION DISTINCT
SELECT *
FROM tripdata_2022.tripdata_202211
UNION DISTINCT
SELECT *
FROM tripdata_2022.tripdata_202212;


