# MGT-4250 Fall 2023 Course-Project at Elon University
Authors: Sasha Nainani, Marshall Tanz, and Karsen Williams

## Project Description
Link to Tablaeu Public Visualization App: [LINK](https://public.tableau.com/authoring/DVS_Final/Dashboard1#1)
### Question of Interest
- What factors make certain songs more popular than others on Spotify?

### Importance
1. The music industry is a highly lucrative field with a diversified set of offerings for consumers.
2. As of 2022, the music industry’s revenues amounted to about $25.9 billion, a number that is continuing to rise [LINK](https://www.ft.com/content/89b30d4b-cd30-4dea-a0e8-0a41f2ce802c).
3.  If a song becomes extremely popular, this will in turn generate revenue for the brand who produces the song.
4.  Understanding which of these factors plays the greatest role in the public perception of a song has the potential to be a savvy investment for a plethora of roles within the music industry, from artists to producers
5.  Combining our knowledge of data visualizations and the stories that data can tell with an application in a creative field like the music industry has the potential to bring in high earnings and inspire decision-making in a niche market[LINK](https://onlinelibrary.wiley.com/doi/10.1111/isj.12369?af=R)

### Data Description
The data we are using allows us to look at and analyze different variables such as tracks, genres, and artists to allow us to create visualizations in which we will be able to successfully answer our research question. The data gives us plenty of different factors to work with so that we can fully understand the most important factors that make certain songs more popular than others on Spotify

Our dataset contains information about 232,725 tracks on Spotify, which is a much more ideal quantity of data. This file contains the following measures: genre, artist_name, track_name, track_id, popularity, acousticness, danceability, duration_ms, energy, instrumentalness, key, liveness, loudness, mode, speechiness, tempo, time_signature, and valence. Each of these measures are explained on SpotifyWeb API’s [LINK](https://developer.spotify.com/documentation/web-api) website, where the data was pulled from. Most of them are fairly self-explanatory and they work on different standardized scales. For example, valence is a measure of 0.0 to 1.0 describing the music's positiveness conveyed by a track. High valence tracks might be described as happy, cheerful, and euphoric. Danceability measures how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. Popularity is a value between 0 and 100, with 100 being the most popular. It is created on an algorithm based on the total number of plays. Each of these factors offer potential interesting findings when combined with data regarding the success of trending short videos.

The dataset was retreived from Kaggle [LINK](https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db). 

### Interpreting Visualizations
Each of the three visualizations depicts insights into the factors influencing song popularity on Spotify. To measure the popularity of a track Spotify uses a value between 0 and 100, with 100 being the most popular. Popularity’s value is calculated through an algorithm that is based on statistics surrounding the total number of plays the track has and how recent those plays are. If a song has 400k plays but they are all from 10 years ago the song is currently not as popular as a song that has 400k plays in the last year. The first compares song popularity by Genre in descending order, from most popular to least popular. It seems fitting that Pop would be the most popular genre as the name quite literally stands for popular. Genres like Reggae, Blues, and Classical tend to be more niche genres which is why they likely have fewer streams on Spotify. The least-played genre is Opera, which peaked in the 20th century and has reduced in popularity since.
The second visualization is another bar graph comparing song popularity to the keys of certain songs. Each key is represented by a different color ordered from most popular to least popular. It is evident that songs in the C key are the most popular and songs in the D sharp (D#) are the least popular while many keys hover in the middle such as F, B, and E. This visualization is important when considering the factors that affect the popularity of songs as scale/key is a critical factor that could determine how popular a song will be.
Our final visualization is a tree map that displays the popularity of artists. Visually representing the distribution of popularity across different artists allows us to find patterns and draw conclusions about what contributes to the success of certain songs. This visualization helps identify trends, such as whether specific artists consistently produce popular songs or if there are particular genres dominating in terms of popularity. Analyzing the tree map can shed light on the influence of an artist's reputation, musical style, and listener preferences.
This contributes to an understanding of what elements make certain songs stand out and become more popular on Spotify. All three of our visualizations collectively answer the question: what factors make certain songs more popular than others on Spotify? Which outside of this project could be used in the real world for producers or artists who want to create music with factors that will lead to its popularity on Spotify.

### Discusion and Summary 
Our Article questions what factors make songs in Spotify popular. [LINK](https://medium.com/@sunsunvirojsirasak/what-are-factors-that-make-song-in-spotify-popular-3cdcb3fb3a10)

This article explores the key factors influencing song popularity on Spotify, focusing on the 2019 "Top 50 Spotify Songs" dataset and using Power BI for visualization. Analyzing features like energy, danceability, loudness, valence, acousticness, and speechiness, the study suggests that songs with moderate energy (43-65) and danceability (64-84) are more likely to be popular. Loudness varies, but common levels are around -18 to -5 dB. Valence has minimal impact, while acousticness is best between 1 and 59. Less spoken words (lower speechiness) enhance a song's popularity.

Average values for these features are provided to guide song creation. The article also notes the influence of popular artists like Ed Sheeran on song success, emphasizing the importance of genre, with dance pop, pop, latin, Canadian hip hop, and EDM being prevalent. In essence, the visualizations suggest that aspiring musicians should consider these factors for creating songs with a higher chance of reaching Spotify's Top 50.
GPT Response:
Several factors contribute to the popularity of a song on Spotify:

Quality of the Song: The most important factor is the quality of the song itself. This includes the lyrics, melody, rhythm, and overall production quality.

Artist's Popularity: If the artist is already popular, their songs are more likely to be popular as well.

Promotion: How well the song is promoted can greatly affect its popularity. This includes promotion on social media, radio, TV, concerts, and other platforms.

Playlists: Being included in popular playlists can increase a song's visibility and popularity.

Collaborations: Songs that feature or are made in collaboration with other popular artists often gain more attention.

Virality: If a song goes viral, for example through a challenge or trend on social media platforms like TikTok, it can quickly become popular.

Listener's Feedback: Positive feedback and high engagement from listeners can boost a song's popularity. This includes likes, shares, and positive comments.

Algorithm: Spotify's algorithm plays a significant role in determining a song's popularity. The algorithm takes into account factors like the number of times a song is played, skipped, saved, and added to playlists.

Cultural Relevance: Songs that resonate with current cultural moments or trends often gain popularity.

Release Timing: The timing of a song's release can also impact its popularity. For example, holiday-themed songs tend to be more popular during certain times of the year.

Upon reading the article that assessed the factors that make songs popular 
While the article explores more features than we did, there is some overlap.
For example, the article notes the influence of popular Artists on song requests and emphasizes the importance of genre with dance pop, rap, and hip hop being prevalent which is what is found as well in our visualizations. 
GPT.4 response does not have as much overlap with our findings and the article's findings because it is pulling from a  wider range of information; the entire internet. The factors that GPT-4 states are much more vague and subjective while the factors that our findings and the article discuss are much more measurable.
