What is this?：The full list of genres included in the CSV includesTrap、Techno、Techhouse、Trance、Psytrance、Dark Trap、DnB（drums and bass）、Hardstyle、Underground Rap、Trap Metal、Emo、Rap、RnB、Pop and Hiphop.

This dataset was downloaded from https://www.kaggle.com/datasets/mrmorj/dataset-of-songs-in-spotify, and the creator was ANDRII SAMOSHYN


Source(s) & Methodology: https://www.spotify.com，
Spotify API used to collect this data.


The genres_v2 table contains variables related to describing music characteristics.

Variables (Columns)


| feature | Description | Data Type |
| --- | --- |--- |
| danceability | Used to describe the degree to which a song is danceable or induces physical movement| number
| energy | A measure of the musical energy and power of a song |number
| key |pitch categories,0 represents C | number
| mode|The mode type used in the song, 0 indicates Major mode, 1 indicates Minor mode | number
| loudness| Describes the overall audio intensity or perceived loudness of a song |number
| speechiness | The degree or proportion of spoken or vocal parts contained in a song | number
| acousticness | Non-electronic or non-synthetic vocal components in a song | floating-point number
| instrumentalness | A characteristic or measure that describes the purely musical elements of a song| number
| liveness | A characteristic or measure that describes the liveness or energy of a song or musical performance | number
| valence | Describes the emotional tendency of the song, 0 means negative emotional tendency, 1 means positive emotional tendency | number
| tempo | The rhythm of the music| number
| type | audio characteristics | text
| id | music track id| string
| uri | Used to identify music tracks | string 
| track_href | Hyperlink to a specific song | string
| analysis_url | Fields describing music analysis data| string
| duration_ms| Represents the duration of the music in milliseconds | number
| time_signature|Describes the beat structure of a musical piece| number
| genre| Describe a music type | text
|song_name| the name of the song | text

The playlist.csv file describes the genre types of different playlists, including Dark Trap,Underground Rap,Trap Metal,EMO,Rnb,Rap,hiphop,pop.

Variables (Columns)


| Header| Description | Data Type |
| --- | --- |--- |
| Playlist| Uniquely identifies a specific playlist | string
| Genre|Describes the genre type of the playlist | text



