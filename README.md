# Interview exercises
A repository for developing and administering exercises related to software 
engineering and data analysis.

Instructions here are only loosely described and how you solve the problem is 
open-ended. This is in done to test your current abilities, and/or ability to 
search online, find, and implement solutions. 

## Rules
1. Pick a problem and follow the steps.
2. You'll be given an amount of time to complete the exercise. Complete it by that time. 
3. You can search online as much as you want.
4. You can use any language or library.

## Steps
1. Fork this repository.
2. Write out and commit code that solves the problem.
3. Describe what you did, either/both (a) comments throughout your code, 
   (b) a summary. If (b), you can write it in the pull request, or as a block of text somewhere in your code. 
4. Make a pull request with your solution.

If you can solve the problem, but are having issues with Git/GitHub, you can zip 
your code and submit your solution via email to jflack@jhu.edu.

## Available problems
There's only one problem available to work on right now.

### 1. Common values
This exercise is in `1_common_values/`:
- `input/`: Contains input files.
- `solution.py`: A placeholder file is here for you. If you're using Python, you
can start editing this file. If you're using another language, you can delete 
  this file and replace it with a file type corresponding to a language of your 
  choice. If you want to split up your code into multiple modular files, that is
  fine too.

The `input/` directory has two files, `a.csv` and `b.csv`. Both files have only 
1 column, `id`. The idea here is that there are 2 different datasets, `a` and 
`b`, and values in the `id` column represent identifiers for entities in those 
datasets.

Mostly, the members of each dataset are different. Howeer, they do have some 
common members. Additionally, some members are listed multiple times within a 
dataset. For example, in `b.csv`, member with ID `264731` appears twice.

Your goal is to produce a table of results that show all of the IDs that exist 
in either set, and show how many times they appear in each set.

Bonus kudos points if the `id` column is sorted (either ascending or descending 
is fine). 
 
id | a | b |
--- | --- | --- |
264731 | 1 | 2 |

You can either (a) output this table as a CSV file and commit it, or (b) simply 
have your script print out the table to the console when it runs. If (b), you 
can print it out using whatever formatting you like, so long as it's readable.