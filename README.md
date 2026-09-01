# **How Spotify's Algorithm Amplifies Fame Instead of Music**
This project was started as a question from an ethics paper I wrote analyzing Spotify's 2018 patent and recommendation algorithm. My argument was that Spotify does not actually care about your taste, it cares about profit. This data analysis uses a dataset of 114,000 Spotify tracks across 125 genres to see if the numbers back that up. And they do.
## **Findings**
1) Most songs are invisible. The average popularity score across 114,000 tracks is 33 out of 100. Half of all songs on Spotify have a popularity of 35 or below.
2) Audio features don't predict popularity. Danceability, energy, tempo, amount of speech; none of them have any meaningful correlation with how popular a song gets. The highest correlation was danceability at 0.035 (on a scale of -1 to 1). That's basically zero.
3) Genre and artist fame do matter a lot. Pop-film and K-pop dominate with average popularity scores above 55. Jazz sits at 13, classical at 13, and Iranian music at 2. The most popular artists in the dataset are all mainstream: Sam Smith, Bad Bunny, Harry Styles, Beyoncé.
4) Spotify doesn't promote music. It promotes fame.
## **SQL Analysis**
In addition to pandas, key analyses were reproduced using SQL to demonstrate proficiency in both tools. Queries include average popularity by genre, average popularity by artists and overall dataset statistics.
## **What This Means**
If audio features don't drive popularity, then Spotify's algorithm isn't matching you with music you'll love based on sound. It's amplifying what's already famous: recent, trending, TikTok-friendly music from artists who are already household names.
## **Tech Stack**
1) Python
2) Pandas
3) SQLite
4) Matplotlib
5) Seaborn
6) Jupyter Notebook
## **Dataset**
Spotify Tracks Dataset — 114,000 tracks across 125 genres via Kaggle

