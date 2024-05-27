# TravelApp

Extract the rar file

There are 2 folders and 1 file

Folder 1 : TravelAppDemo
This folder contains a springBootApplication of Java21 
Just run it as springBootApplication

Contents : 
1 Controller - PopularPlaceContoller
2 Service - OpenAI Service , PlaceService

Db used - Rdbms

For openAI chatgpt -3.5 turbo engine is used to fetch details

Prior fetching details its checked in Db if popular places for the same are already present in the db.
If yes then directly the response is passed without consuming the API.
Once the Api is consumed the search result is stored in DB.


Folder 2 : travelui
This is a ReactJs Application made using white
Run using following commmands
npm install
npm install axios
npm run dev

It is a Ui interface in which the user can search for a place and get the famous location of that place as the result.

file 1 : iml file 
Its part of frontend project make sure to have it in the same path as travelui folder.
