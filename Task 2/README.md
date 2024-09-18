# Dataset for analysis
- Reaction
- Content
- Reaction Types

# Data Cleaning
1. Reaction
- remove blank values under Type
- rename Type as Reaction Type
- remove User ID

2. Content
- remove URL column
- consistent the data type by removing "" under category column
- rename Type as Content Type
- remove User ID

3. Reaction Types
- rename Type as Reaction Type

# Data Modelling
1. Create a final data set by merging 3 tables together using "VLookUp" formula
- using VLookUp formula

2. Figure out the Top 5 performing categories
- using SumIF formula
