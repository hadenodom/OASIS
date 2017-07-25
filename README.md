# OASIS
OASIS (Open Audio Streaming Implementation (Spotify-Killer) aims to be a FOSS spotify killer, allowing its user to host a music server and stream music from it, and add music from a variety of sources (Youtube, Torrents, LibreVox, Etc) on the go using a fully-featured and open source client.


Simply put, I want to a create a project that will facilitate the following goals:

1.  Allow a user to easily deploy a streaming music server on their home computer or anywhere else
2.  Develop Mobile, Web, and Desktop clients to interact with this server
  
  2A.  The client should be able to search a variety of sources for music, including Youtube, LibreVox, etc, and download music from these sources to the server library
  
  2B.  The client should be able to sync the user's library from the server and keep an offline copy of the library.
  
  2C.  The process of creating the officially-supported client should be so well documented that creating new clients for other platforms is child's play.  
  
  
  
While "make a program that gets music from youtube and torrents" sounds like asking to get arrested, keep in mind that quite a large amount of Public Domain material is hosted in these formats, and the user alone makes the decision of what to download using this app.  We do not encourage users to break copyright law.  I myself plan to develop and use this so that I can download and manage a collection of Public Domain audiobooks and audio content.  And I encourage future users of this app to check out what's out there in the public domain - you'd be surprised how much music is out there for free, legally.  


TODO:   Develop the mobile client.  The backend will be mpd.  The client will make calls to already-existing scripts such as youtube-mp3 and transmission to accomplish remote downloads.  The server-side will just be a matter of creating a package that installs mpd and these scripts and configures them for interaction from the client.  The first client developed will need to be a web client.  The other clients will be derivative.  The first feature implemented will be playing music remotely and browsing existing playlists(code already exists to do this from mpd!).  Next will come the ability to search various sources (along with the ability to select sources to search/not search from), and the ability to preview search results (not sure how this can be accomplished for torrents?), and finally, to trigger the download on the server and monitor results (notify when done).  Additonally, consideration needs to be made for the client-only or client-on-device model.  

This is obviously going to take a backseat to the STCE project I'm working on, for now.  
