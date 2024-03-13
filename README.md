# Practice
# 1. Clone the repository
git clone <repository_url>
cd <repository_directory>

# 3. Create a directory
mkdir B1-2019300282-123456
cd B1-2019300282-123456

# 5. Create 5 new text files
touch B1-FILE1.txt B1-FILE2.txt B1-FILE3.txt B1-FILE4.txt B1-FILE5.txt

# 7. Write secret code to File 1
echo "123456" > B1-FILE1.txt

# 8. Write student number to File 4
echo "2019300282" > B1-FILE4.txt

# 9. Add all files from number 6
git add B1-FILE2.txt B1-FILE5.txt

# 10. Perform commit
git commit -m "Add files with vowels and consonants"

# 11. Create a new branch
git checkout -b new_branch

# 12. Create a new folder based on the date
mkdir $(date +%Y%m%d)
cd $(date +%Y%m%d)

# 13. Create a new file based on the port
touch putty_port.txt

# 14. Create a new file based on the boot order
touch boot_order.docs

# 15. Add the file from number 13
git add putty_port.txt

# 16. Commit
git commit -m "Add putty port file"

# 17. Add the file from number 14
git add boot_order.docs

# 18. Commit
git commit -m "Add boot order file"

# 19. Switch back to main
git checkout main

# 20. Perform branch check
git branch

# 21. Perform merge
git merge new_branch

# 22. Delete branch created on 11
git branch -d new_branch

# 23. Add all Unstaged
git add .

# 24. Commit
git commit -m "Add all unstaged files"

# 24. Push all files to your local repo to github repo
git push origin main

# 25. Copy all logs from gitbash
# (Manually copy the logs)

# 26. Create a new txt file based on firstname of your instructor-log.txt
touch John-log.txt

# 27. Paste all logs from 25 to file from 26
# (Manually paste the logs into John-log.txt)

# 29. Add file from 26
git add John-log.txt

# 30. Commit file from 26
git commit -m "Add logs from Git Bash"

# 32. Push from local to github repo
git push origin main

# 34. Paste this file (instruction) to the created repo from 3
cp <path_to_instruction_file> .

# 35. Add file from 35
git add instruction.txt

# 36. Commit file from 35
git commit -m "Add instruction file"

# 37. Push from local to github repo
git push origin main

# 38. Create a pull request
# (Create a pull request on the GitHub website)

# 4. Access the directory
cd B1-2019300282-123456

# 6. Files 2 must contain all vowels and file 5 must contain all consonants
echo "aeiou" > B1-FILE2.txt
echo "bcdfghjklmnpqrstvwxyz" > B1-FILE5.txt

# 28. Add all Unstaged
git add .

# 31. Push from local to github repo
git push origin main

# 33. Add file from 35
git add instruction.txt

# 38. Create a pull request
# (Create a pull request on the GitHub website)
