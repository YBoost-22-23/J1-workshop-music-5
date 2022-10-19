# workshop-music-5
YBoost workshop #5 | 12/10/2022

# PartyMix

## Objective :
You are in a night party with your friends. Everybody wants to add his song to the waiting list on the mobile which plays music. Create a central platform where everybody can add song no matter of the streaming platform. 


## Notion :
* [Golang documentation : Flag](https://pkg.go.dev/flag)
* [Golang documentation : Os](https://pkg.go.dev/os)
* [Golang documentation : Termui](https://pkg.go.dev/github.com/gizak/termui/v3)
* [Retrive data from API in golang](https://tutorialedge.net/golang/consuming-restful-api-with-go/)

## Step 1 : Retrieve data
You have to retrieve data from API like : 
* [Shazam](https://rapidapi.com/apidojo/api/shazam)
* [Spotify](https://developer.spotify.com/documentation/web-api/)
* [Deezer](https://developers.deezer.com/api)
* [Last.fm](https://www.last.fm/api)
* [Genius](https://docs.genius.com/)
* [Musixmatch](https://developer.musixmatch.com/)
* [Soundcloud](https://developers.soundcloud.com/docs/api/guide)
* [Youtube](https://developers.google.com/youtube/v3)
* [Apple Music](https://developer.apple.com/documentation/applemusicapi)
* [Tidal](https://developers.tidal.com/)
* [Beatport](https://www.beatport.com/developer)
* [Discogs](https://www.discogs.com/developers/)

*Shazam API seems to be the easiest to use*  
Often, to use an API, you have to create an account and get an API key.
You are limited to a number of request per day. You can find the limit in the documentation of the API.

You can use [Postman](https://www.postman.com/) to test your API request.

## Step 2 : Create the central platform

Create something easy to use and where it's easy to add some new users.

## Step 3 : Connect it all !

Create a good display for your playlist

## What is an API ?
An API is an interface that allows you to retrieve data from a website. API are set up by developers to allow other developers to use their data and make applications with it.

## ORGANISATION PROPOSITION

Dev 1 (easy) : Get songs from minimum 3 streaming platforms and create local playlists on it  
Dev 2 (medium) : Create all the differents interface and connection with the differents platforms  
Dev 3 (medium) : Use websockets to communicate with an other device. Try to send basical text and after musical links  
Dev 4 (medium) : Create rooms and invitation system to connect multiple devices  
Dev 5 (hard) : Create a system which translate all requests from different streaming platforms into one and create a common playlist  
