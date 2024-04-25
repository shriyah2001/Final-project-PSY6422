# Final-project-PSY6422
For my final project I will be visualising an **Anime** dataset that has a list of the highest rated anime titles on *My anime list* given by the users. It was sourced on Kaggle by the user Md Kazi Sajiduddin iwth the Jikan API.
The project consists of a dataset acquired from Kaggle that has user ratings given to anime in the year 2023. The entire dataset is quite huge, with ratings given by users to more than 24k anime titles.
Other asepcts of the raw dataset include The original title, the english title, information on when the anime aired, finished airing, the day of airing, the broadcast time, user ID, studios, prouduction house, synopsis and so on.

I choose to visualise the themes of the top 1000 anime titles in the list to understand which themes occured the most in the top rated anime titles of the year 2023. I will be also creating an addtional plot of the demographics of the shows.

I was able to produce a dataset containing just the titles' themes and demographics after cleaning the data. In order to determine how often these variables appeared in the dataset, I further assisgned them. 
I used the *Kable* package to plot the count in a table after obtaining it. After that, I utilised the count to use ggplot's *Plotly* Library to make an interactive plot. As a result, I made two plots: one showing the theme count of the top 1000 anime series with the highest ratings, and the other showing the demographics of these anime releases.

