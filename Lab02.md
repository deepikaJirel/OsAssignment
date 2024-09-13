## Lab 02

- Name: Dipika Jirel
- Email: jirel.2@gmail.com

## Part 1 Answers

1. Command & steps to create an SSH key pair:
2. Steps to add public key to GitHub profile:
3. git command to clone the repository: 

## Part 2 Answers

The answers for this section are to help you record what steps  
are needed to create a file locally (in your cloned repo)  
and push them (sync) with GitHub.  Only `git` commands are 
valid answers

1. git command to view the status of the repository: </br>
       ` git status`
2. git command example to add a file for tracking: </br>
    `git add <file_name>`
3. git command to commit changes: </br>
    `git commit -m "type a message"` 
4. git command to sync local commits with GitHub: </br>
    `git push origin <branch-name>`
5. git command to sync commits on GitHub to `clone`d repository: </br>
    `git pull origin <branch-name>`


## Part 3 Answers

1. `chmod u+r bubbles.txt`
    - Means:
             `chmod`: `command to change the file permission.`
              `u+r`: `u is the owner of the file (user).  `r` stands for the read permission.`
              `bubbles.txt`: `files we are modifying`
      `so the command `chmod u+r bubbles.txt` permits the user to read the .txt file. If the user already has permission to read it, it remains the same. 
                                   
2. `chmod u=rw,g-w,o-x banana.cabana`
    - Means: `The user will have read and write permission, The group will have no write permission others will have no execute permission while the read, write permission is unaffected and the banana.cabana file that we are modifying.`
3. `chmod a=w snow.md`
    - Means: `This command sets the permission for all the users only have `write` on the file snow.md. `
4. `chmod 751 program`
    - Means: `
5. `chmod -R ug+w share`
    - Means: 

## Part 4 Answers

1. Command to create new user: 
2. Path to user's home directory: 
3. Evaluate if `ubuntu` can add files to user's home directory:
4. Command to switch to user:
5. Command(s) to go to user's home directory:
6. Evaluate if user can add files to user's home directory:
7. Command to switch to `ubuntu`:
8. Command to return to `ubuntu` home directory: 

## Part 5 Answers

For each, write the command used or answer the question posed.

1. Command to create group named `crew`:
2. Command(s) to add `ubuntu` & user to group `crew`:
3. Command to modify `share` to have group ownership of `crew`:
4. Command to switch to user:
5. Command to add file to `share`: 
6. Evaluate why these steps allowed the above action:

## Part 6 Answers

For each, write the command used or answer the question posed.

1. Command to create file using `sudo`: 
2. Evaluate (in plain text) the permission of the file: 
3. Provide a method to edit the file without modifying permissions: 
4. Command(s) to modify permissions:
