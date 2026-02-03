1️⃣ Why reference Songs in Playlist instead of embedding?
Referencing avoids duplicating song data across playlists. Songs may appear in thousands of playlists, and embedding would cause massive duplication and update issues.

2️⃣ Why reference Artist in Song model?
A song belongs to one artist, but artists have many songs. Referencing prevents repeating artist details in every song and allows easy updates to artist information.