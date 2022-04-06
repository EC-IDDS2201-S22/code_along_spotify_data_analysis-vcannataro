

Dr. Cannataro generated these datasets using the `spotifyr` R package.


`IDDS_class_playlist.rds` is the playlist our class put together https://open.spotify.com/playlist/1InDSrfzYQaHYbmp8q2Etz?si=2332d5f360a64214 

`spotify_big_data` is adapted from Kaylin Pavlik's awesome blog post https://www.kaylinpavlik.com/classifying-songs-genres/ and includes 29,000 unique songs. It was built by grabbing songs from 20 playlists corresponding with the top 4 sub-genres of the top 5 genres on spotify. 

# Data dictionary

Danceability = Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.


Speechiness = Speechiness detects the presence of spoken words in a track. If the speechiness of a song is above 0.66, it is probably made of spoken words, a score between 0.33 and 0.66 is a song that may contain both music and words, and a score below 0.33 means the song does not have any speech.


Instrumentalness = This value represents the amount of vocals in the song.The closer it is to 1.0, the more instrumental the song is.


Acousticness = This value describes how acoustic a song is. A score of 1.0 means the song is most likely to be an acoustic one.


Liveness = This value describes the probability that the song was recorded with a live audience. According to the official documentation “a value above 0.8 provides strong likelihood that the track is live”.


Key = Denotes the major or minor scale in which a piece of music operates, and thus, the notes that belong in it.


Tempo = The pace of a piece of music is known as its tempo. Tempo can be measured by beats per minute, or bpm; classical music tempos are described by a set of terms ranging from larghissimo (very slow) to andante (a moderate speed) to prestissimo (very fast).


Valence = Describes the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).


Loudness = Loudness values are averaged across the entire track. It is the quality of a song. It ranges from -60 to 0 DB. Higher the value, the louder the song.

