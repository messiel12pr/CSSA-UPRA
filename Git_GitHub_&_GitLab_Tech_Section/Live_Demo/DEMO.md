<h3>TODO LIST</h3>

- Create a local repo
- Create a remote repo in GitHub
- Get Personal access token from GitHub
- Connect local repo to remote repo

<h3>Prerequisites</h3>

- Git installed
- GitHub account
- A terminal
  - VSCode integrated terminal
  - CLI
  - Git Bash 

<br>

<h3>Create a local repo</h3>

- Create a folder 
- In your terminal type the following command (make sure you are inside the folder you created):
  - `git init`
- Now configure your user details (use the same email as the one you use for GitHub)
  - `git config --global user.name "REPLACE-WITH-YOUR-NAME"`
  - `git config --global user.email replace-with-your-email@upr.edu`
 
<h3>Create a remote repo in GitHub</h3>

- Go to [GitHub](https://github.com)
- Sign-in into your account
- On the top-right corner click your profile icon
- Click:
  - ![image](https://github.com/messiel12pr/CSSA-UPRA/assets/95717805/afb62431-8f7c-4e93-ba70-fa75afb5dc0b)
- Click:
  - ![image](https://github.com/messiel12pr/CSSA-UPRA/assets/95717805/753f825f-542a-41b9-954f-2e90ea3327ba)
- Add a name for your repo and click:
  - ![image](https://github.com/messiel12pr/CSSA-UPRA/assets/95717805/982bd1f7-6144-4b2c-99b5-21d4634db94a)
- Now copy and save into a text file the following commands at the bottom of the page. It should look similar to this:
  - ![image](https://github.com/messiel12pr/CSSA-UPRA/assets/95717805/a2054bdf-1fef-4cb9-9cb1-c7ef3327a82a)
 
<h3>Get Personal access token from GitHub</h3>

- In the top-right corner click your profile icon
- Click:
  - ![image](https://github.com/messiel12pr/CSSA-UPRA/assets/95717805/ef0f8d31-98df-468e-90ed-85c1fd796ed8)
- In the menu bar to your left click:
  - ![image](https://github.com/messiel12pr/CSSA-UPRA/assets/95717805/aab20928-08e3-4903-bf44-f923c788cb86)
- In Personal access tokens click Tokens (classic):
  - ![image](https://github.com/messiel12pr/CSSA-UPRA/assets/95717805/e53a6d3b-11a8-4cda-a283-7113644e7d96)
- In Generate new token click Generate new token (classic):
  - ![image](https://github.com/messiel12pr/CSSA-UPRA/assets/95717805/3d270ebb-bd77-42a6-97d0-e7bcb4d5a0a4)
- Now add a note and check the repo box:
  - ![image](https://github.com/messiel12pr/CSSA-UPRA/assets/95717805/ff543324-f838-436b-9d98-e1fdef75fe1a)
- Click:
  - ![image](https://github.com/messiel12pr/CSSA-UPRA/assets/95717805/25c0580c-90b6-4b89-9041-222c948d8b95)
- Copy the token and save it in a text file. Do not share this with anyone.

<h3>Connect local repo to remote repo</h3>   

- Create a file named README.md
- Add this to your README.md file and save it:
  
```
<!---
Visitor counter code provided by: https://github.com/sagar-viradiya.
Make sure to use your username bellow
-->

<h1 align="center">Hello World, this is my repo :wave:</h1>
<p align="center">Visitor count<br>
<img src="https://profile-counter.glitch.me/REPLACE-WITH-YOUR-USERNAME/count.svg" />
</p>
```
- Run the add command in order to stage our changes:
  - `git add README.md`
- Run the commit command in order to commit our changes to our git history:
  - `git commit -m "First commit" README.md`  
- Copy the commands you saved when you created your remote repo in GitHub
- Paste these commands in your terminal:
  -  ![image](https://github.com/messiel12pr/CSSA-UPRA/assets/95717805/f36ef6d6-959c-4381-8964-52239c37db18)
- When prompted for a username provide your GitHub username
- When prompted for a password provide the Personal access token we generated earlier


 
