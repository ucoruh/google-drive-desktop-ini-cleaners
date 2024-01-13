# Google Drive + Github

![](assets/2024-01-13-22-08-41-image.png)

![](assets/2024-01-13-22-09-15-image.png)

### desktop.ini cleaners

This scripts are used in any github repository to clean up desktop.ini files before commit and push

## Installation and Usage Steps

### Step-1

Clone or create repository

### Step-2

Run `configure-git-hooks.bat`. This will copy `pre-commit` and `pre-push` script to git/hooks folder to clean desktop.ini files

### Step-3

Run `create-git-ignore.bat` to add `desktop.ini` files to gitignore. Also add this files to global gitignore files

#### Step-4

Finally run `delete_desktop_ini.bat `on windows and `delete_desktop_ini.sh` on linux 

### Step-5

Add and commit files. You will see desktop.ini files will be cleaned.

## Warning!!

After each clone you need to process Step-1 to Step-5 again. 

If you forget and submit desktop.ini files they will be copied in .git folders and this will corrupt all structure.
