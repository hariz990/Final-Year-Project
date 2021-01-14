# parkingfinder
Repaired prarkingfinder repo for Project 1.
# Project Capstone 2019 semester 2
# Contributers: Timothy Novice s3572290, Syed Hariz Bin Syed Azmi s3701799, Yazeed Othman # 3543535, Raymond Chi 3660737

## Application Repo
https://github.com/Riger73/parkingfinder/tree/1.0

### Andoroid Car Space Booking App
Uses Google CLoud REST API ad has a datastore on Firestore. Authentication is by email address and is handled by Firebase Auth.

## Release notes are found here:
https://drive.google.com/drive/folders/1R0VSeq2kIg6Ep1E4FVwfEoNxWlzb_whW

##The applicaiton installers can be located here:
https://drive.google.com/drive/folders/1SqbS14kj4HJSZi0IBH2ApiI65meuRaEo
The APK key is password protected with the password : "password"


The structure of the app follows MVP (Model View Presentation) with the following directory structure:

#app


###src


#####main


#######java/com/pp1/parkingfinder


#########adapter


#########model


#########view


#########util


#####res


#######layout

All of the presentation is handled in view - thus all the "activities". Model has casses that form the object models for customers, Listings, and bookings objects. Utils handles services such as geocoding. Adapters contains classes that handleobject model adapters such as for moving listing or booking objects between client and server.

Requires Marshmello or above.




