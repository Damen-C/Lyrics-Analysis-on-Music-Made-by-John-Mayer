
# Lyrics Analysis on Songs made by John Mayer with Natural Language Processing Techniques 

John Mayer is an American signer, songwriter, and guitarist who made music across genres including rock, pop, and blues. Personally, I enjoy his album Continuum and The Search for Everything the most. I think it would be interesting to visualize John Mayer's music and see if we can get gain some information on how he developed as an artist.  


## Visualization 
Figure 1: Albums Made by John Mayer
![Albums Made by John Mayer](https://raw.githubusercontent.com/beeman-93/Lyrics-Analysis-on-Music-Made-by-John-Mayer/main/visualization-4.png)

Figure 2: Word Clouds of Albums
![Word Clouds John Mayer](https://raw.githubusercontent.com/beeman-93/Lyrics-Analysis-on-Music-Made-by-John-Mayer/main/WordClouds_SmallerVer.png)

Figure 3: Sentiment Distribution (Bar Charts)
![Sentiment Distribution (Bar)](https://raw.githubusercontent.com/beeman-93/Lyrics-Analysis-on-Music-Made-by-John-Mayer/main/sentiment_distribution.png)

Figure 4: Sentiment Distribution (Pie Charts)
![Sentiment Distribution (Pie)](https://raw.githubusercontent.com/beeman-93/Lyrics-Analysis-on-Music-Made-by-John-Mayer/main/visualization-6.png)
## Conclusion
- From Figure 1, we can gather that John Mayer does not release music frequently. In fact, his latest album Sob Rock was released in 2021, following a gap of 4 years since his previous album, The Search for Everything, which was released in 2017. It is worth noting that John Mayer's yearly output has not exceeded 13 songs to date. This indicates that he places great emphasis on quality control when it comes to his music, preferring to take his time to craft each piece meticulously. 
- Figure 2 reveals that John Mayer frequently uses words such as "love," "need," "want," and "life" in his songs. This observation suggests that his music revolves around common human emotions and experiences. By tackling these themes in his music, John Mayer connects with his audience on a personal level. It is no wonder that so many people can relate to his music and find solace in his lyrics. 
- Figure 3 and 4 provide insight into the sentiment distribution of John Mayer's albums over the years. Generally, the distribution of negative sentiments outweighs that of positive sentiments in his albums. However, an exception to this pattern is seen in his album "Paradise Valley," which has a more positive sentiment distribution. This album was released in 2013, during a time when John Mayer was dating Katy Perry. The song "Who You Love" from this album is believed to have been inspired by their relationship and the time they spent together. This could explain the album's more positive sentiment distribution, as John Mayer may have been in a particularly happy and contented state of mind during this period. 
## API Reference

#### Genius API - Scrap lyrics

```http
https://docs.genius.com
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `CLIENT_ACCESS_TOKEN` | `string` | **Required**. Your API key |

#### Check my tutorial on how to use Genius API: 
```http
https://medium.com/@cd_24/lyrics-analysis-with-nlp-techniques-1-ef73e1f8c958
```

#### Hugging Face API - Conduct sentiment analysis

```http
  https://huggingface.co/inference-api
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `hf_token`      | `string` | **Required**. Your API key |

#### Check my tutorial on how to use Hugging Face API: 
```http
https://medium.com/@cd_24/using-bertopic-to-analyze-qatar-world-cup-twitter-data-part-3-b220630fd894
```




## Code
The codes programmed in this project are displayed in this repository. Feel free to check and use them. 
