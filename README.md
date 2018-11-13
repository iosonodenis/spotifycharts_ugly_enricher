# A very ugly script to enrich Spotify Charts data

## How it works:

*   Load a csv file/data downloaded from spotifycharts.com
*   Isolate unique track_id in another df, and get the audio feature
*   From the artist_id, get the genres. In spotify they are associated with the artist
*   Join the dataset

## Todo:

* Create checks to keep input going in case of errors
* Some people made decent scrapers, while I patiently downloaded each files. See how to make that work cohexist.
* Import also the artist image from spotify
* Make sure that for the same track_id, the track name is the same (I merged several csv after all). Same for artist_id

## Backlog:
* Export feat artist in a several column
* Find an unique genre
* Export artist image

## Documentation:
*   Spotipy Documentation: http://spotipy.readthedocs.io/en/latest/
*   Developer Portal: https://developer.spotify.com/web-api/authorization-guide/
