# Movie-ETL
Module 8

## Data Assumptions
1. Files will be saved to the 'Resources' folder.
2. Raw data, particularly wikipedia as it is any user can modify, will maintain the same column headers. If column headers change then the transformation process of that data set will be comprimised.
3. An additional box office or budget style will come into play that is not already accounted for in the regular express piece of the transformation code.

4.Raw data sets will go by their same name i.e. movies_metadata, ratings, wikipedia.movies. The code searches for these names explicitly.

5. The raw data will come in the same format. For instance wikipedia data is assumed to be in json format. It will not be properly transformed otherwise.
