201 Day 4 Collaboration in Pairs
My name is David Zalk, I worked on Caleb Sattgast's Code.
Changes that were made to his code were as follows.
1. Added <h4> and <h5> tags with different id's in order to have answers
to questions show up in the proper area.
2. Wrote shorter, modified versions of Caleb's questions on HTML page, giving
answers a location to be printed out, and also so user would be able to
understand what the answers were in response to.
3. Turned all the questions into functions and called them in correct order.
4. Added Hint that only appeared if you guessed incorrectly Caleb's birth year.
5. Made it so the Guess Calebs Age Portion of his script showed up above the
 other answers on the browser window so that if browser is not fully open,
 instead of cutting off this part at the bottom, it was visible at the top.
6. Pushed to github, made a pull request, gave permission for Caleb to merge
his code work on my code with my code. Asked for Calebs permission to do same.

# 201-day-02-demo
A demo repo for practicing using GitHub! (And hopefully for avoiding gitshows)

This is an .md file (stands for markdown)

DATA TYPES
  * strings - text
  * numbers - numbers, including integers and floats
  * booleans - true/false

JS allows you to put any type of data into any variable. Like the honeybadger, JS don't care.

OPERATORS

= assignment
== equivalent (loose equals - tries to force types to be the same - "type coercion")
=== strict equals - cares about type


GIT BRANCHES
Use branches with git to avoid making changes to a master that might be running vital parts of your site.

git branch //lists your branches including the master

FOR EXAMPLE:
//running
git branch //returns the following:

age-guessing-feature
location-feature
* master //asterisk indicates active branch

git checkout -b new-branch-name //creates new branch (substitue your branch name for new-branch-name)
git checkout branch-name //navigates to the branch you want to access

When working in a team, work on the same file on different sections of code, but don't work on the same lines of code simultaneously, so avoid a conflict when merging versions later.
