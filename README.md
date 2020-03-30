
# what is it about?
this repo contains a jupyter notebook for automatic processing of the dataset about the datasets files formats. The dataset comes from an daily automatic extraction of the number of datasets file formats available on the [EU open data portal](https://data.europa.eu/euodp/en/home). 

# data source
the input dataset is coming from the source: [datasets files formats](https://docs.google.com/spreadsheets/d/1L3jZ1lhESQEpdiU7Vd1BY9YvJ4KO0Po-sPEfhCfEKuI/edit#gid=1686327626)

# data processing
the processing in this notebook manage different cases: 
* data cleansing
* data reshaping
* data aggregation per dataset file format

# other files 
there are 2 CSV files: 
* datasets_formats_processed.csv: this is a sample of the output file of the data processing.
* processed_dates_update.csv: this is a sample of the files used to track the processed dates. It could be useful for dataset updates.
