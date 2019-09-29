# Useful tips how to use GitHub

## assumption - you have installed one of GIT client for your operation system.

If you did not do it yet, please use this [link](https://git-scm.com/download/win) to get one.

hold ```Ctrl``` key when you are clicking the link, otherwise you will departure this page.

## How to get (to clone) somebody else's source code
1. Go to Github.com

Find a project.

On the main page of any project it is a <button>Download or Clone</button> button

Click on this button and copy repository link

It should look something like this: 
```https://github.com/QueM775/ASP_iis_World.git```

2. Go to any folder on your disk and type this command

(New subfolder will be created in the current folder (the folder where you run your command))

```git clone <Git URL>```

<strong>*** Sample ***</strong>

```git clone https://github.com/QueM775/ASP_iis_World.git```

## Upload new files to existing repository

1. go to the local repository folder.

Example ```c:\some-folder\some-sub-folder\cloned-folder-from-github\```

2. check status

```git status```

you should see your new file(s) (what you are about to upload) <span style="color:red;">in red</span>

3. Now you can add you file... files... all files

add a single file
```git add <sinngle-file-name>```

add bunch of files 
```git add 	<file1> <file2> <file3> ...```

add all new files
```git add . ```  <span style="color:red;">what about subfolders, does it include them?</span>

now your new file added to your __local__ repository

4. Now you should __commit__ your new file(s)

```git commit -m "Comments to THIS commit"```

5. Finally you should push your new files from you local repository to the remote one.

```git push```

Now your local repository should be in sync with the remote one.


## Other commands which I do not know how to use

##### Show all available branches 
```git branch```

##### Show all activities 
```git log```

##### Show all activities in more compact format 
```git log --oneline --decorate --graph --all```

##### To sync local copy with web folder
```git pull```

### Notification Settings
Go in to the folder you want to  set up the notification on
you select settings  on the left is a panel with notificaation 
select it then add the email addresses you want notified. You 
can add 2 email addresses with a space between.
