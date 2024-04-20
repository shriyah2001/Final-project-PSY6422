# Final-project-PSY6422
For my final project I will be visualising an **Anime** dataset that has a list of the highest rated anime titles on *My anime list* given by the users. It was sourced on Kaggle by the user Md Kazi Sajiduddin iwth the Jikan API.
The project consists of a dataset acquired from Kaggle that has user ratings given to anime in the year 2023. The entire dataset is quite huge, with ratings given by users to more than 24k anime titles.
Other asepcts of the raw dataset include The original title, the english title, information on when the anime aired, finished airing, the day of airing, the broadcast time, user ID, studios, prouduction house, synopsis and so on.

I choose to visualise the themes of the top 1000 anime titles in the list to understand which themes occured the most in the top rated anime titles of the year 2023. I will be also creating an addtional plot of the sources from which these top 1000 titles were derived.
After cleaning the data, I was able to create  dataset with only the Themes & Sources of the titles. I further assisgned these variables to get a count of them occuring in the dataset. 
After getting the count, I plotted the count in a table with *Kable* package. 

After that I used the count to create an interactive plot with the *Plotly* Library in ggplot. Thus, I created two plots, One that plotted The theme count of the top 1000 highest rated anime & the second that plotted the demographics of these anime titles.
