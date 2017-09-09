## This repository contains a notebook that serves as a primer for datetimes in the context of pandas data frames 

<b>The topics covered are:</b>: 
* examples of Timestamps 
* examples of Periods (with different frequencies) 
* creating a series with a datetimeIndex 
* creating a series with a periodIndex 
* use of pandas.to_datetime() function to convert a string series to a datetime 
* to_datetime on European formatted dates 
* computations that return timedeltas and adding timedelta to timestamp 
* pandas.date_range() function that creates a datetimeIndex beginning on a particular date (possibly with offset) with a certain period frequency and for a certain number of periods. 
* weekday_name function called on a timestamp 
* explicit and partial matching of time series 
* basic downsampling and upsampling, including filling missing upsampled data 
* accessors of time series (hour, minute, dayofweek, etc.) 
* Converting a timezone-naive index to a timezone-aware index, changing the timezone associated with the index and then restoring it to its original timezone-naive state. 
* Converting a timezone-naive column to a timezone-aware column, changing the timezone associated with the column and then restoring it to its original timezone-naive state. 
* Linear interpolation to fill in missing values on upsampled data 
* Other datetime tidbits 

<b>Included data files are:</b> 
* sales-feb-2015.csv 
* world_population.csv 

<b>Included IPython notebook</b> 
* DateTime.ipynb 

<b>Included HTML output file</b> 
* DateTime.html 

 