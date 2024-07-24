# music-time-machine
A Python script to create a private Spotify playlist with the top 100 songs of a requested date

Requires the external libraries: request, spotipy, bs4.

Once you run the script, you will be asked for the requested date, and for your Spotify User ID/Username, which can be found here: https://www.spotify.com/account/profile/ (it is different from the display name).

When all the information has been input successfully, you will be prompted to authorize the script in Spotify on a browser window, and you will be asked to copy the URL that will be opened. It starts with example.com, this is irrelevant, just copy and paste the entire URL in the Python script execution when it asks you.

The songs will start being loaded, and once complete the script will stop, and you should have the new playlist on your account.
