# Youtube_data_collection
This project involves the extraction of data from YouTube, specifically focusing on video-related information. The extracted data includes details such as channel information, video name, video ID, view count, like count, favorite count, and posting date. Additionally, all comment details are also collected.

The workflow of the project involves first extracting the desired data from YouTube using the Google apiclient.discovery package. The extracted data, which consists of both structured and unstructured information, is then stored in MongoDB.

Next, the non-structured data is migrated from MongoDB to a PostgreSQL database using the psycopg2 package. This allows for efficient analysis and querying of the data in a structured manner.

To provide an easy and user-friendly interface, the entire application is developed using Streamlit. Users can interact with the application, access the stored data, and perform various analyses as per their requirements.

Lastly, the project includes the provision of the top 10 questions and their corresponding answers for analysis purposes. These questions can be used as a starting point to gain insights from the collected data.

Overall, this project combines data extraction, storage in both MongoDB and PostgreSQL, and analysis using Streamlit, providing users with a comprehensive and interactive platform to explore YouTube video-related information.
