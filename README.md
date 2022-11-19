# WeRateDogs
    The data was derived from the twitter account: @rate_dogs.

    The dataset used for the project is divided into three parts:

    Archived twitter data
    Image prediction data
    Retweet count and favourite count

    Anaconda's Jupyter Notebook was majorly used for this project. Visual assessment was done with Microsoft's Excel and PowerBI

## DATA GATHERING

    The archived twitter data was provided by WeRateDogs in a csv format for use by Udacity students for the purpose of this project. 
    The second data - Image prediction data was downloaded programmatically using the python requests module and saved in a single file in a tsv format. 
    The third data - retweet count and favourite count was downloaded from Twitter using Twitter's tweepy API to query the data. 
    The resulting data from the twitter query was saved in a json format.
    
    
   ## DATA ASSESSMENT

    Assessment of the data involves inspecting the data for quality and tidiness issues. Quality issues include:

    Incomplete data,
    Invalid data,
    Inaccuracy,
    Consistency issues.

    Tidiness issues were determined.

    Assessment was done visually - opening the data in Jupyter notebook, Excel and PowerBI(for the tsv data) 
    and randomly looking for quality and tidiness issues- and programmatically using pandas methods and functions e.g. (.shape, .info(), .describe()).

    The noted issues were itemized.

## DATA CLEANING

    This was done programmatically using the array of functions provided by the excellent pandas library with Jupyter notebook.

    The tidiness issues were first adressed as they were structural related issues. 
    json data which was loaded into the Jupyter Notebook and converted to a Pandas DataFrame was merged programmatically with the archived twitter data.
    Column values were "melted" into a single column and variable names provided.

    The quality issues were then subsequently addressed. 
    Incorrect datatypes were changed to the appropriate datatype, columns were renamed, invalid rows were removed and so on

## DATA STORAGE

    The two tables were stored as csv files

