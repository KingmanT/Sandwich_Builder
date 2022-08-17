# Sandwich_Builder

A Bash Sandwhich Ingredient Check

## Objectives

Group Project Bash Script to check if available ingredients
for a sandwich are availble to user

## Group Participants

Sasheeny H
Kingman T
Walter E
Rey R
Lorenzo M

## Methodology

### Files
We are using files to store the following
* Needed ingredients

### Script
The script does the following:
* Store sandwich ingredients in an array list
* Ask user for a desired sandwich
* Takes a predetermined available ingredient list and verifies available ingredients
  * User will verify with a yes or no if they have the necessary ingredient for their desired sandwich
  * Each element of the sandwich array selected will be verified by user for availability
  * If ingredients are available, says that sandwich was made
  * If not, populate ingredients in a separate text file
  * Populated list of missing ingredients will then be available

## Missing implementation
* The text files were supposed to be used to index into an array instead of creating arrays in the bash script itself
* There is missing implementation for what happens if all ingredients available
