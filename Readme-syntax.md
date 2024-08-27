# Git Readme.md syntax:

<h1> Some Basic Commands </h1>

git init

git add (file name)

git add .

git status

git commit -m "message"

git log

git log --oneline

git revert commitid

git reset commitid

git show commitid

git pull 

git push


# ordered list:
1. list1
1. list2
1. list3

# ordered list with sub list:
1. list 1
 _item1
1. list2
  item 2
1. list3
  item 3

unordered list:
- list 1
- list2
- list3

# Anchor Tag
[google](https://www.google.com/search?q=google&oq=google&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIHCAEQABiPAjIHCAIQABiPAjIHCAMQABiPAjIGCAQQRRg8MgYIBRBFGDzSAQg0MjMwajBqN6gCALACAA&sourceid=chrome&ie=UTF-8)

# Image Tag
![image](Image link)

# Block:
> Block1
>> Sub block1

# New line
---
# checkbox:
-[x] checkbox


# Italic:
*italic*
---
# Bold:
*Bold*
---
#striked:
~~striked~~

# creating a table

|No|name |age|
|---|---|---|
|1|sai |23|8
|2|sai |24|

GIT REVERT & GIT RESET
> GIT REVERT:

git revert commitid

git revert HEAD

git revert HEAD ~number


> GIT RESET:

git reset commitid

git reset HEAD

git reset HEAD ~number


> Git Branching

git branch

git branch dev

git checkout dev - It will ceate a dev branch

git checkout -b dev - It will ceate and move to dev branch

git merge dev2 - To merge the branch

git branch -d dev2 - To delete the branch dev2

git branch -D dev2 - To delete the branch dev2 forcefully.


> Pull request

git commit -m "First file"

git commit -m "Second file"

git add .git commit -m "Third file"
   
git commit -m "Third file"

git push origin main
   - up to date 
   - To push to remote repositoy

git push origin Third file
   
