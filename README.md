# Books Booth

Books Booth is an Android application designed and developed as an assignment
from the ''Mobile Application Development'' (a.y. 2017/2018) course taught at
Politecnico di Torino (Italy). The team was composed by:

+ Eugenio Gallea
+ Marco Iorio
+ Stefano Malacrino
+ Nunzio Turco

## Assignment

Create an Android application that helps people to share books. It must have
the following features:

+ The application should easily allow users to sign up and setup a basic profile.
+ Users can make books available for sharing, providing all the relevant pieces
  of information by accessing some shared database.
+ Users can search for shared books and get in contact, via the app, with the
  book owner in order to arrange the withdrawal and successive return.
+ As a consequence of each sharing, users' reputation must be updated.

## Back-end

The project relies, for its back-end, on [Firebase](https://firebase.google.com),
a development platform owned and managed by Google that provides a plethora of
ready-to-use tools and services. In particular, we exploited

+ Firebase Authentication, for a smooth sign in experience;
+ Realtime Database, a NoSQL database used to keep track of all pieces of
  information;
+ Firestore, to store multimedia contents;
+ Cloud Functions, to trigger specific actions when an event occurs.

Additionally, we exploited [Algolia](https://www.algolia.com), a powerful
search-as-a-service solution, to allow users to look for their desired books
in a simple and effective way.

## License

This project is licensed under the [GNU General Public License version 3](
https://www.gnu.org/licenses/gpl-3.0.en.html).
