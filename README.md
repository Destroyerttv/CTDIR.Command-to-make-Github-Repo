# CTDIR (Create Directory)

CTDIR. A command which simplifies the new programming directory process. 

This Command does the following:
* Creates and Moves into a directory
* Creates a README.md and a .gitignore
* Creates and adds files to the master branch
* Creates and adds files to the .gitignore
* First commit is done
* Creates and pushes changes to a private remote repository
* Opens VSCode 

All of this is done through the shell.


## Installation

After you have installed the file, first make the file an executable.
```bash
chmod +x ctdir
```
Second, you have to add your file to PATH. The process depends based on your operating system but the resource below will help you add the file to PATH

https://gist.github.com/nex3/c395b2f8fd4b02068be37c961301caa7

Then, on line 53 you need to add your github username to the USERNAME variable
```bash
USERNAME="YourGithubUsername"
```
Finally, you need to add a personal access token. To do this you need to go to developer settings in the Github settings page. Then go to personal access tokens section and create a new token. You need to click the first box "repo" and click create. Copy the token into line 52 of the script
```bash
TOKEN="YourPersonalAccessToken"
```

## Usage



## Contributing
Pull requests are welcome. Any ideas to simplify the process 

