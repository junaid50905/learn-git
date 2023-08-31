# learn-git


working dir-----stagging dir----local repo----remote repo

status: red color----status: green color----local repo-----remote repo


| git   | description |
| ------------- | ------------- |
|  git init |   |
|  git add . |   |
|  git status |  red color: working directory, green color: staging directory, no branch master: সবকিছু local repo তে আছে  |
|  git diff | difference between git add . and without git add . (difference between stagging dir and working dir) |
|  git restore filename.extention |  git difference এর কনটেন্ট বাদ দিতে, যদি git diff এ কনটেন্ট না থাকে তাহলে কাজ করবে নাহ  |
|  git rm --cached filename.ext | একটি file কে staging directory থেকে working directory  তে নিয়ে আস্তে এই command টি use করা হয়   |
|  git commit -m "message" | staging directory থেকে local repo তে নিয়ে আসতে এই command টি use করা হয় |
|  git push |  for second time push in a certain repo |
|  git log | display the history of the previous 3 commit, latest commit will be first of the commits  |
|  git log --oneline |  to show all commit |
|  git show | Show details of the last commit |
|  git show commit_id | to get details of a certain commit |
|  git show HEAD~2 | index 2 number commit er details show korbe (supose : Head->commit1, commit-id commit, commit-id-fff commit ) ekhane commit id fff show hobe karon er index 2 | 
| git reset --soft HEAD^ | local repo থেকে stagging directory  তে নিয়ে আস্তে(last commit, তার মানে যেই commit এ HEAD আছে, last commit a joto file and folder thakbe sob back korbe ) |
| git reset HEAD^ | local repo থেকে working directory  তে নিয়ে আস্তে (last commit, তার মানে যেই commit এ HEAD আছে, last commit a joto file and folder thakbe sob back korbe )|
| git reset --hard HEAD^  |  all files, folder, content will be romoved those are connected with last commit |
| git reset --soft HEAD~2 | last 2 commits (we can use here 2,3,...)|
| git reset HEAD~2 | local repor to working directory last 2 commit |
| git reset --hard HEAD~2 | local to remove last 2 commits (NOTE: proyojon chara git reset use korbo nah, git reset er poriborte git checkout use kobo) |
| git checkout commit_id |  last commit theke checkout er commit a back korbe. ekhon HEAD hobe checkout er commit, ekhon amra ager commits guloke dekte parbo nah, 'git checkout master' dile amra abar last commit a pire asbo |
| git checkout master | last commit a pire asbo |
| git remote add origin HTTPS_url | to connect local repo to remote repo. origin is name. we can write anything at origin, but everyone write this |
| git branch -M main | - |
| git push -u origin main | - |
| git remote | to check that local repo and remote repo is connect or not. if connect show origin(name) |
| git clone https_url | to clone a project |
|  git branch | to show the branches  |
|  git branch dev | make a branch named dev  |
|   |   |
|   |   |
|   |   |
|   |   |
|   |   |

#### git checkout
- to create a branch (when we write the following command a new branch will be created and will be redirect to features branch)
```
git checkout -b features
```

- to change the branch
```
git checkout branch_name
```

#### git branch
- to see the list of all branches
```
git branch
```

- to delete a branch
```
git branch -d branch_name 
```








### There are many different version control systems available. For example, 

    Subversion
    Perforce
    AWS Code Commit
    Mercurial
    Git
### Version control systems can be split into two types or categories. 
    Centralized version control systems(CVCS)
    distributed version control systems(DVCS)

#### Centralized version control systems(CVCS)

    There will be a central copy/server repository of the project somewhere programmers will 'commit' the changes to this central copy.


<img src="https://www.edureka.co/blog/wp-content/uploads/2016/11/Centralized-Version-Control-System-Workflow-What-Is-Git-Edureka.png" height='300' width='400'/>

<img src="https://www.researchgate.net/profile/Luis-Ribeiro/publication/23646260/figure/tbl1/AS:667686602285063@1536200299510/Advantages-and-disadvantages-of-the-centralized-approach-Barata-2003.png" height='200' width='200'/>
