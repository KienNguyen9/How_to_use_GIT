# HOW TO USE GIT

## CREATE A REPOSITOTY
### To create a new repository on GitHub, follow these steps:
1. Go to GitHub.com and sign in to your account.
2. Click the + button in the top right corner of the page.
3. Select New repository.
4. Enter a name for your repository and a short description.
5. Select whether you want your repository to be public or private.
6. Click Create repository.

   Once you have created a repository, you can clone it to your local machine using the following command:
   ``` python
   git clone https://github.com/your-username/your-repository.git
   ```
This will create a new directory on your local machine with the same name as your repository. The directory will contain all of the files from your remote repository.
### To pull changes from the remote repository to your local repository, run the following command:

``` python
   git pull origin master
```
This will download any changes that have been made to the remote repository since you last cloned it.

### To push changes from your local repository to the remote repository, run the following command:

``` python
   git push origin master
```
This will upload any changes that you have made to the local repository to the remote repository.

## Here is an example of how to use the git clone, git pull, and git push commands to create, pull, and push a repository:
``` python
   # Create a new repository on GitHub.
   git clone https://github.com/your-username/my-project.git

   # Change into the directory containing the repository.
   cd my-project

   # Make some changes to the repository.
   # For example, you could create a new file called `README.md`.

   # Add the changes to the staging area.
   git add .

   # Commit the changes with a descriptive message.
   git commit -m "Add README.md file."

   # Push the changes to the remote repository.
   git push origin master
```





