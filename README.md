### Note: please try refreshing the notebook if it fails to load (notebook filesize is too big)

## EDA of crimes in los angeles 


The analysis is structured as follow: In part 1, an overview of the database is provided and queries using the database API is perform to retrieve some basic information on the particular dataset. Specifically, the API allows users to perform queries via SoQL. SoQL has similar functionality and syntax with SQL where it is able to perform for e.g., SELECT, WHERE and ORDER.

After which the crime dataset is downloaded via the API onto a csv file. Part 2 can be separated into 2 sections: Crime and Temperature. First, for the crime analysis, i looked at the overall trend, followed by detailed analysis of each Ws. Before beginning each analysis, some data cleaning such as checking for duplicates, NaN values and meaningless 0 values is carried out to minimise spurious results. Also, interesting observations are also provided as comments at the end of each plot. Next, i looked at the daily average temperature in LA city and using Ordinary Least square regression to try to determine if there's any relationship between increasing temperature and crime occurrence. Finally in the last section, i summarised and highlights some of the results that i find is informative from this analysis
