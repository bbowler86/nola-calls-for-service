# NOLA Calls for Service


In an effort to become more transparent and accountable the NOPD has released 9-1-1 records from 2011 to the present. The original dataset can be download from the [data.nola.gov](http://data.nola.gov) website. This data contains information around the call that was placed related to the time that it was created, the time that the authorities were dispatched, the type of call placed, and the disposition. <br>

The dataset has been cleaned up a bit and put into a format that is more easily digestable. It now includes the longitude and latitude instead of the map x and map y locations of the old dataset, although there are missing coordinates. There are now binary columns indicating if the call was a violent crime, non-violent crime, or not a crime at all. The year, year-month, and date have been added for each timestamp in the dataset.  <br>

The new dataset is available for download as a [CSV file](https://s3.amazonaws.com/datno-public-datasets/nola_calls_for_service_2011_2014.csv). It is also available in a much smaller format as an [RDS file](https://s3.amazonaws.com/datno-public-datasets/nola_calls_for_service_2011_2014.rds) which can be read by R. <br>
