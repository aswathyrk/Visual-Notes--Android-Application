# Visual-Notes--Android-Application

A social media application(Android-Application) which will allow students to share notes with each other. With image processing, students can search for notes based off their contents. 
For developing on Android, I have used Android Studio to model the UI and write the code of the application.
This application stores the images of notes be it whiteboard, pdfs, presentations, flash cards, or pages from notebooks, etc along with metadata associated with them.
The data flows between Krumbs and a local database. The photos are stored on the Krumbs domain as well as the on the local storage. 
The searching is performed by Algolia, which is a hosted search API. For the search, I implemented an indexing based software system named Algolia that allowed me to customize the ranking of pictures based on description, intent categories, location and other attributes. 
Based upon the query entered at the top of the “Home Page” by the user, Algolia will then rank the results based on our given index and return a JSON file with the results of the query. 

