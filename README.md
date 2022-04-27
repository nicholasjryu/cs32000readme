# Spotify Playlist Review - cs3200 - Final Project
 Nicholas Ryu, Evan Eddleston, Matthew Vieira, Wilson King

## How to Use the Application

1) Add the Heroku Connection:
* username: svo8lfmx74emz9cb
* password: ksecveqmd2xrbatb
* hostname: Bv2rebwf6zzsv341.cbetxkdyhwsb.us-east-1.rds.amazonaws.com
* schema_name: em74miyb75k82ccz

2) Open & Run the "create_spotify.sql" file
+ Double check to make sure all tables were created in the schema correctly

3) Open & Run the "table_inserts.sql" file
+ Double check to make sure all table data was inserted correctly

4) Read the comments for each of the queries to find which data you need, and run

## How to Add a Review for Playlist
1) Open the "table_inserts.sql" file. 

2) Scroll down to the "user" section asd add an insert line with:  
     "insert into user (user_id, user_name, email)
      values (1, "mark", "mark11@gmail.com");"

3) Scroll down to the "playlist" section asd add under the "values" line:  
    (playlist_id, title, user_id)

4) Scroll down to the "playlist_song" section asd add under the "values" line:  
	(playlist_id, user_id, rating, description)

## How to Add a Review for Song
1) Open the "table_inserts.sql" file. 

2) Scroll down to the "user" section asd add an insert line with:  
     "insert into user (user_id, user_name, email)
      values (1, "mark", "mark11@gmail.com");"

3) Scroll down to the "playlist" section asd add under the "values" line:  
    (playlist_id, title, user_id)

4) Scroll down to the "song_review" section asd add under the "values" line:  
	(song_id, user_id, rating, description)

4) Scroll down to the "playlist_song" section asd add under the "values" line:  
    (playlist_id, song_id)
