## Comparing my Spotify 2020 and 2023 Data

** Motivation **
* I want to see the alteration of my taste in music through 2020 to 2023 years. I had 5 hypothesis that motivated me to do this project:
* 1) Through 2020 to 2023 my music genre did not change and stayed same and stayed as Rock (Turkish).
  2) Through 2020 to 2023 the tempo (BPM) of the musics that I listened increased.
  3) Duman (Turkish rock group) was always in my top 5 artists.
  4) The average Energy of the songs that I listened through 2020 to 2023 was increased.
  5) Correlation values between BPM and Energy were need to be very strong for both 2020 and 2023 years.*

  ** Data Source **
  * I used my spotify datas. I used my 2020 most listened (top 100) songs playlist and my 2023 most listened (top 100) songs playlist). I created two seperated csv files that show my 2020 most listened (top 100) songs playlist and my 2023 most listened (top 100) songs playlist) which you can see in my CS-210-Sotify-Project repository. I imported this files by using
[chosic](https://www.chosic.com/spotify-playlist-analyzer/).

** Data Analysis **
* I used Explotary Data Analysis (EDA) technique:
* 1) I build a dataframe from my spotify 2020 and 2023 datas.
  2) I cleaned the dataframe and I tried that if each column and row describe single object.
  3) I made statistical analysis of my datas.
  4) I explored global properties by using histogram.

  * I also used visualization technique to show my analysis as in various charts. I prefered to use Matplotlib library to present the analysis that I made. The reason of this is make the audience understand my comparsions easier. I prefered column chart to compare few (2) items. I used pie chart to show various items in one chart clearly. I used line chart to show the correlation between two seperate items through 2020 to 2023.
 
  ** Findings **
  * I found out 2 of my hypothesis is true and 3 of them are wrong.
  * The wrong hypothesis are:
  * 1) Through 2020 to 2023, my music genre changed Turkish Rock to Turkish Drill.
    2) Duman (Turkish rock group) was not in my top 5 artists lists in 2023. My [2020 the most listened artist](https://github.com/omertarim/CS210-Spotify-Project/blob/main/top10_artist_2020.png) was Duman however my [2023 most listened artist](https://github.com/omertarim/CS210-Spotify-Project/blob/main/top10_artist_2023.png) was BLOK3 (Turkish drill artist).
    3) Correlation values between BPM and Energy was very weak for both 2020 and 2023 years. Correlation between BPM and Energy for the top 100 songs in 2020 is -0.10 and Correlation between BPM and Energy for the top 100 songs in 2023 is 0.01. Here you can see the Correlation between BPM and Energy. ![correlation](https://github.com/omertarim/CS210-Spotify-Project/blob/main/correlation_bpm_energy.png)
* The true hypothesis are:
* 1)  Through 2020 to 2023 the tempo (BPM) of the musics that I listened increased. In 2020 the average tempo of 100 songs was 122.04 and in 2023 the average tempo of 100 songs was 123.28. There is slightly difference between this two years but the average tempo of 100 songs was increased. Here you can see the Average of BPM and Energy. ![avg](https://github.com/omertarim/CS210-Spotify-Project/blob/main/average_bpm_energy.png) 
  2)  The average Energy of the songs that I listened through 2020 to 2023 was increased. Average Energy for 2020 dataset is 57.72 and average Energy for 2023 dataset was 59.96. 


     
