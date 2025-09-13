# SpotiFly: Using AIML to Predict Danceability for 17.1K Songs

## Our work!
* [Code](https://colab.research.google.com/drive/1sJ6XA-Sc8sAbSZuC7hCTYlq8eXrNXzP3?usp=sharing)
* [Report](https://docs.google.com/document/d/1i7t3OjU7PqQ0_981jD-2_zW7rRisRuh6FwNrmEvbabw/edit?usp=sharing)

## Overview
### Dataset: Spotify
The Spotify dataset provides a collection of data for tracks on Spotify. The data is related to musical, lyrical, and popularity-based attributes of approximately **114,000 songs**.

### Problem Addressed
The objective is to analyze a comprehensive dataset of **114,000** songs on Spotify to predict the `danceability` of songs. **Danceability** describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable. 

This has applications in the entertainment industry, with music generating over **28 billion dollars** in 2023. With such a large market, it’s important to consider factors that make music so appealing, one of which being danceability. Danceability plays a pivotal role in creating open, entertaining atmospheres, facilitating an environment to foster human connection and community. This is a key use case for music, and using data analysis, we can find valuable insights. For example, if we find the attributes that contribute the most to a song’s danceability, this may in turn affect the song’s public reception and revenue.

An alternative we considered for a response variable was popularity, but the algorithm to calculate `popularity` was flawed in that "...songs that are being played a lot *now* will have a higher popularity than songs that were played a lot in the *past*." This creates inaccuracies when considering songs that were previously, but no longer popular.

<br/>
<p align="center">
  <img src="https://github.com/user-attachments/assets/1fa11095-49c7-4733-b454-0899ce5bfb99" width="250" height="259" alt="image">
</p>
