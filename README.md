Project Report
Overview and Guiding Questions
Goals:
    Create an easy way for both patients / people in pain and casual marijuana smokers to explore different solutions to their conditions.
    Present medical rating data and casual smoker feedback side by side so that people can draw comparisons across the data in their search.
Extract:
    Our original data came from three sources, one in a CSV file, Json file and another was a SQLite database with multiple tables.
    The data in CSV came from kaggle.com, a cannabis supply with educational content and reviews for various strains
    The data in Json came from Kaggle.com, <https://www.kaggle.com/gthrosa/leafly-cannabis-strains-metadata>.
    The data in SQLite database came from leafly.com.
Transform: what data cleaning or transformation was required.
    From the SQLite database, we selected data that pertained to medical effects and medical rating
    From the CSV file, we selceted Name, Type, THC_Level, Terpene, Relaxed,Happy, Euphoric, Uplifted data
    My goal is to extract Json to collect sleepy, dry_mouth, depression, anxiety, pain data.
Load: the final database, tables/collections, and why this was chosen
    My final table will consiste of following:
    Description (Name, THC_level, and Type )
    Effects (Relaxed,Happy, Euphoric, Uplifted, Description)
    Ratings (Medical effects, Medical rating)
I will use a postgreSQL database to load our final tables to easily load the data.