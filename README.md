# Using functions and cases in python
Using functions in python to make codes more compact and easier to reference and to load data into new tables. 
The assignment also covers conducting distribution analysis on data using python. 

## Approach

The approach is as follows: 
1. Filter first 1000 rows of the datasource "youtube_dataset.csv" which contains 4000 rows. 
2. Create a function that calculates the distribution of "channeltype"
3. Call the function to view results. 


### Prerequisites

Install Anaconda for launching Jupyter Notebook to execute Python Code.

## Deployment

1. Libraries are imported for plotting graphs 
2. Datasource is read and loaded to dataframe df 
3. Datasource is sorted in descending order to capture top 1000 channeltypes based on subscribers and assigned to a new df "sorted_df"
4. First 1000 rows are filtered using iloc and assigned to a new dataframe "filtered_df"
5. Tail of new dataframe shows that first 1000 rows have been filtered 
6. Function is created to calculate distribution of records in channel type from the top 1000 records. 
7. Function is called to display the output of the function. 
8. Function is created to plot the distribution of records in channel type from the top 1000 records. 
9. Function is called to display the output of the function. 


## Authors
1. Kiran Mukesh-100839944
2. Mahisha Nanayakkara-100872912
3. Gisna Joseph-100844690
4. Riya Gangani-100850012
5. Sujai Kumar Subramanian-100839966


## Acknowledgments
Prof. Omar Al-Trad
