## Overview

`shrub.cd` is a decentralized social music management environment for Urbit. Discover 
new music, manage your library and chat with your friends, all in one place.

what.cd + cmus + turntable.fm = shrub.cd

## User Stories

1. I want to add tracks to my collection
2. I want to listen to random tracks from my collection
3. I want to create a playlist composed of tracks from my collection
4. I want to share a playlist (and their associated tracks) with my friends
5. I want to create rich notes/commentary for my playlist
6. I want to discover playlists that my friends have created
7. I want to chat while listening to a playlist synchronously with my friends
8. I want to tip the creator of a playlist
9. I want to gate access to a playlist on payment

## Architecture

```
shrub.cd
|
|-- track
|-- playlist
    |-- skin
```

## Implementation plan

-[ ] manually create YT tracks
-[ ] form to add YT tracks
-[ ] mine info from page
-[ ] playlist data type
-[ ] async playlist player
-[ ] sync playlist player
-[ ] Permissioning

