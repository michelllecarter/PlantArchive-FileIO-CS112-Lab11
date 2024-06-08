# PlantArchive-FileIO-CS112-Lab11
Lab 11: File IO (Plant Archive)
Unsupported image

As a beginner urban forager, I want to keep a list of native plants that are edible and/or medicinal that are found in Southern California. I was given a text file with a list of plant names, along with, their average temperatures for planting, and their most common uses. This data is saved in a comma-seperated format.

Create a program that reads the text file, saves each line as a Plant object, and displays the objects to the console with labels. Example output:

Example Output

Lab Summary
Each object is on its own line in the CSV text file. Read in the comma-separated values (CSV) text file using Scanner and FileInputStream. As each object gets read, use String's split() method to separate each comma-separated value. Then load variables into a Plant object, which you'll add to an ArrayList. Display the foraging plants to the console to prove the file is being read and loaded correctly.

Given:

Forage.csv with multiple lines (records) of plants, each line's values are seperated by commas (CSV file format).
Plant.java completed model class, ready to be upgraded/used for File IO
Steps
Familiarize yourself with the Plant class code that contains all required methods.
Create a constructor that takes in a single parameter of type String that is in the CSV format (see any line from Forage.csv for examples). split the line and store each value into its corresponding instance variable
Make sure to error check the whole string and the parts of the string (after the split)
Prepare the file input code in Main
Follow the 5 steps needed to setup your method for file input:
Import the necessary classes for text file input
Declare variables you'll need to do the file input
Initialize those variables, make sure to use "Forage.csv" for your text file name
Create a loop that runs as long as there are lines of text in the file
Close the input stream after the loop ends
Build the Plant objects and store into an ArrayList
Create an ArrayList to store the Plant objects you'll build from the CSV file
for each run of the loop that reads a line of CSV text, build the Plant object and add it to your ArrayList object
TIP: before doing this part, just print the line of text read from the file to the console. If it matches Forage.csv that's proof that your loop is working! Then you can build the objects and add them to the ArrayList
To prove it runs, print out the ArrayList contents after you've closed the input stream.
This project was created by Jackie Walsh, GOALS in CS 112 intern Spring 2021.
