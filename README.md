# Animals: Real or Myth!? Lab

Use Classes in an Android app to store data [Classes, Android 101]

We're going to build a game over the next few days: **Animals: REAL OR MYTH!?** This game will be a quiz game that queries users if an animal is real or mythological. Before we can complete it, we need to feel comfortable adding classes to a project and using them. You're going to _fork this repository_ and then _clone it_. You will then create a **new** Android Studio project inside of the repository on your computer. When completed, please push your changes live and submit a pull request.

## Test Drive 

* Clone the following repository: https://github.com/code-for-coffee/animals-real-or-myth
* Run the application in Android studio
* Identify what the app is doing; what works? What doesn't?
* Inspect the source code for inspiration 
* Now, prepare to write something like this on your own (but not broken)

>> **Groups!** We recommend that everyone work together in pairs/groups to brainstorm how to work this process out before going it alone to write the code. Ask your peers for help if you run into a problem!

## Class Requirements

* Create a custom Animal class with the following properties: numLegs, topSpeed, isEndangered, name, isMythological, decription, habitat
* Complete the constructor for the Animal class
* Create all getters and setters for the Animal  properties
* Instantiate an Animal in your activity's onCreate, and display some of its properties in a TextView with an id of `txt_animal` and a variable of `mTxtAnimal
* Use the setter methods to modify some of the animal's properties and show the modified animal in a second TextView; make sure to prefix all _member variables_ with an `m`, such as `mTxt` or `mEditTxt`.
* Bonus: Add additional methods to your Animal class that return a formatted String using the class properties (such as `toString()`.

## App Requirements

* Add an `EditText` to your app. Give it the id of `edit_txt_animal` and a variable of `mEditTxtAnimal`
* Create an `[]` or `ArrayList` of your animal.
* Place an ItemClickListener on your EditText and have it store the name of each animal you have added to your collection.
* Using `saveInstanceState`, store your animal data. Whenever an activity is `onCreate`'d, render the names of every animal that has been added. You may need to write a method that loops through and gets the name of every animal and puts it into a String.
* Create a simple, single view application that allows users to enter in animals on one portion on the screen.
* On another portion of the screen, allow the user to cycle through your collection of animals and answer if they are Mythological or not.
* You do not need to keep track of score or attempts (but it is a nice stretch goal).

## Submission

* Add/commit changes to your fork.
* Push/publish them live.
* Create a pull request.
