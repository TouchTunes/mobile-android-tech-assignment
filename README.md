# TouchTunes Android Code Test #

## iTunes Album Search by Artist ##

Your mission, if you choose to accept it, is to write an app which calls the iTunes Public API to **create a list of albums** for a specified artist.

https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/iTuneSearchAPI/index.html

For this task, your objective is to create a simple Android app with one screen. At the top of the screen there should be a search field where the user can type in the name of a Band / Singer / Artist, and then generate a list of all the albums for that artist. Each row must display the Album **Artwork**, Album **Name**, and **Release Date**.

_(hint: Look closely at the iTunes API specs – there are ways to specify that the search only looks for artist name, and that results only include a list of albums)_

Each row must be clickable, and once clicked, it must display a small dialog containing the following information:
      
- Primary Genre Name
- Collection Price
- Currency
- Copyright

The dialog must have only an "OK" button that dismisses the dialog.

## Guidelines ##

The code must make use of Android Architecture **ViewModel** component and be written in **Kotlin**. LiveData is acceptable but we strongly encourage the use of kotlin flows. On the UI side, both xml layouts and Compose solutions are appropriate, go with what you are the most comfortable with. You are free to use any other third-party libraries you want. Unit tests are recommended but not not mandatory. Once finished, create a zip file with your solution and send it back to the interviewer that sent you the initial instruction. An acknowledgment will be sent to you after reception if everything is all right.

Please take the time to build a solution that you feel proud of and that would be a clear representation of your knowledge and expertise in Android Development.
