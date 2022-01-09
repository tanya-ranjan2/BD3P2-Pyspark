# BD3P2-Pyspark
## Group 13 -  Entertainment - netflix shows analytics
Team Members:

1. Prathibha K S      -  20BDA15
2. Tanya Ranjan       -  20BDA32
3. Rakshith Kumar K N -  20BDA47
4. Nagavarun S N        -   20BDA67

### Work Done: 

#### i.Extract: Load the data

Read data as pandas dataframe and then create spark dataframe and create a table view "netflix" as spark SQL

##### ii.Transform: Exploratory data analysis using spark sql queries

- Unique showId count
- GroupBy type,release_year and count of showId
- Update column duration values as 90 min to 90 and 2 seasons to 2 and others
- groupby type and avg durations

#### iii.Load: Save analysis report

- save as tables - partitionby type
