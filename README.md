# spotify_api_demo
Rough demo of the Spotify API

`index.html` is the landing page, it simply redirects to `spotify_auth`

`spotify_auth` gets a user's authorization to access/modify their public playlists, then redirects to `spotify_redirect`

`spotify_redirect` searches through the user's public playlists. If it finds one called `Test Playlist`, it adds Despacito to it.

Visit https://connor-penrod.github.io/spotify_api_demo/ to test it out.
