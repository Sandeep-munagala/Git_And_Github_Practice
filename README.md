# my_first_repo
practice repository for learning Git and GitHub from the local device 

 The following steps are done for creating a file locally from the terminal and pushing the file to GitHub through the terminal.

# 1. Create a file
touch test.txt

# 2. Insert some text into it using cat
cat > test.txt

# 3. Add it to the staging area 
git add test.txt

# 4. Commit the test.txt file to the committed files
git commit -m "updated"

# 5. Push it onto the remote repository
git push -u origin

# 6. To create a branch 
git checkout -B branch_name

# 7. To check the status of the file
git status
