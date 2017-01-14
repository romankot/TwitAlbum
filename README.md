# TwitAlbum

The app should allow you to create albums for hashtags, and then fetch the most recent
photos posted on Twitter for that hashtag since the last fetching. The app should
show the images and each image should link to the original tweet.
Each fetch should get at most 100 results from Twitter. Fetching should happen when
a user clicks a button. The fetched tweets should be parsed and the necessary information
stored in the local db. There should not be any duplicate photos (hint: try to
avoid photos with duplicate URLs).
