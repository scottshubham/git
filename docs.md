***
# This is a file to store all the git commands.
To initialize a git repo in any folder:
```php
git init
```
To see the status of any git repo:
```php
git status
```
If there are untracked files in your git repo:
```php
git add . // To add all the untracked files 
git add <filename> // To add specific files
git add -p
git add --patch // To add only a specific part of a file
```
Added something you did not wanted to add:
```php
git reset
```
Done with adding:
```php
git commit -m "<your message here>" // Saves all the added changes to a commit
git commit -am "<your message here>"// Shortcut to add all modified files and commit
```
***


