# Rails Friend by John Elder (codemy.com)

This project is in progress as I learn Ruby on Rails based on [this course video](https://www.youtube.com/watch?v=fmyvWz5TUWg) from Free Code Camp. 3.06 (Next chapter: Style Modifications)


## GIT Cheat Sheet

* git add .

Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.

* git commit -m "First commit"

Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD1' and commit and add the file again

* git remote -v

Verifies the new remote URL

* git push -u origin master

Pushes the changes in your local repository up to the remote repository you specified as the origin

## Notes
Path to master branch:
cd Desktop/Salsify/Ruby\ Learning/RailsFriends/Friends

<%= %> - This means we can type Ruby code inside the HTML and print the result in the page (with the = sign)

* Example to create a new DB table:

Command to create the migrate

#rails g scaffold friends first_name:string last_name:string email:string phone:string twitter:string 
Command to create the schema:

#db:migrate

Rembember this will create a new css file that might conflict with an existing one (like bootstrap), just check it under the folder app/assets/stylesheets

