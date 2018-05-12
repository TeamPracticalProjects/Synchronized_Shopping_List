# Synchronized_Shopping_List
## An app that uses Google Firebase to synchronize a shopping list across multiple users.

### Do you share shopping chores with other people?  Do you have trouble creating and maintaining complete and accurate shopping lists?  Do you and others sometimes purchase duplicate items?  Do you fail to purchase a needed item thinking someone else is buying it?  If these problems resonate with you, then you need the Synchronized Shopping List app!

The Synchronized Shopping List is an app that multiple people use to add items to a common Shopping List as they are needed, and to remove items from the common Shopping List as they are purchased.  The idea is that all people who share shopping chores for a household, facility, club or organization have the app installed on their personal mobile device(s).  At any time, anyone who sees a need to purchase an item simply opens the app and adds the item to the Shopping List.  Whenever anyone in the group of users is shopping for items, that user displays the Shopping List and removes (or updates) the item from the Shopping List. 
 
The Shopping List that appears on each user’s mobile device is synchronized with all other users’ Shopping Lists because the Shopping List is stored in a Google Firebase Real-time Database.  The Shopping List is always current on all users’ mobile devices. Every time anyone uses the app to change something, the change is reflected in the apps of all of the users who share shopping chores.

The app is written using the MIT App Inventor 2 (AI2) integrated development environment (IDE).   At present, AI2 can only create apps for Android mobile devices.  The MIT team has promised support for iOS (Apple) mobile devices later this year. 
 
One person in the user group must create the Firebase database using their Google account and enter the access credentials into the app’s source code file (.aia file) in this repository.  That person must then create the app installation file (.apk) that is used by each member of the group.  Instructions for creating the cloud database and installing the app with the database access credentials included are provided in the document “Synchronized Shopping List Setup and Installation Instructions” which is located in the Documents folder in this repository. A User Manual is also included in this folder.

### No more missing items!  No more duplicate purchases!  Happy Shopping :)

All materials contained in this repository are (c) 2018 by Bob Glicksman, Jim Schrempp and Team Practical Projects and are distributed freely under an open source, non-commercial license, see: https://creativecommons.org/licenses/by-nc/4.0/. Use of the material in this repository is subject to the document “Terms_of_Use_License_And_Disclaimer”, included in this repository.

### Enjoy, Team Practical Projects.
 

