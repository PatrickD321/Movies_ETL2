# Module 8 Challenge Movies ETL

## Summary
This challenge was to allow us to use the following:
### Deliverable 1
How to manipulate the use of functions in Pandas to read datafiles and convert these files into dataframes. Files were pulled from two websites wikipedia and kaggle, using the starter code provided and our understanding from this module the results were determine as in figure 1.![fig1](https://user-images.githubusercontent.com/78861458/114310802-20cf8e80-9aba-11eb-8027-a792d145f4c0.png)

### Deliverable 2
Here we learn how use ETL (Extract Transform Load) process to remove data that are unnecessary for analysis. Extract relevant information and more importantly reduce data size to a more manageable Dataframe. Wikipedia file had many flaws, typical for file coming from that source, Modules 8 shows how special emphasis had to place on this source to clean the files and present them in a meaningful manner. The Figures below displays instances of this.![fig3](https://user-images.githubusercontent.com/78861458/114311600-693c7b80-9abd-11eb-865a-1070f78c10e8.png)![fig2](https://user-images.githubusercontent.com/78861458/114311479-ee736080-9abc-11eb-95ef-a8cb86dfa5fa.png)

### Deliverable 3
For dataframes that are considerable larger than others, here we learn how to transform and merge them together. Kaggle metadata and ratings dataframe demonstrated how this process was accomplished. Suffix were added for each columns to distinguish between the two dataframes that have similar names. Lesson 8.4 shows how to compare each similar columns using graphic means that involving ploting graphs with values in the two respective data columns or simply by inspections to determine which is more important or have the required information that we need.

### Deliverable 4
Transfering the dataframe to a database (SQL was used) was demostrated in this part of the challenge. This database which is stored on a sever can be access for information at anytime, similar to what is used in previous module, for example, OpenWaether API, was used to plan a vacation for near perfect weather conditions. Time dependencies which was added to, 
- 1. show that code is working, 
- 2. a connection is or was made to the database PostSQL and Pandas, 
- 3. the elasped time to transfer the data. 
![ETL_create_database](https://user-images.githubusercontent.com/78861458/114320379-b6334880-9ae3-11eb-982c-7636c34bcf36.png)

Codes were refactored, re-used, and re-purposed , which is one the areas that were highlighted in this module. Keeping things organiszed by defining functions, and the introduction "Lambda" function in Pandas, helps with understanding how coding works in most programmable languages.


