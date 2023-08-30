# learn-git


working dir-----stagging dir----local repo----remote repo

status: red color----status: green color----local repo-----remote repo


| git   | description |
| ------------- | ------------- |
|  git init |   |
|  git add . |   |
|  git status |  red color: working directory, green color: staging directory |
|  git diff | difference between git add . and without git add .  |
|  git restore filename.extention |  git difference এর কনটেন্ট বাদ দিতে, যদি git diff এ কনটেন্ট না থাকে তাহলে কাজ করবে নাহ  |
|  git rm --cached filename.ext | একটি file কে staging directory থেকে working directory  তে নিয়ে আস্তে এই command টি use করা হয়   |
|  git commit -m "message" | staging directory থেকে local repo তে নিয়ে আসতে এই command টি use করা হয় |
|  git push |  for second time push in a certain repo |
|  git log --oneline |  to show all commit |
|  git checkout <commit_number> |  to go a specific commit |
|  git branch | to show the branches  |
|  git branch dev | make a branch named dev  |
|   |   |
|   |   |
|   |   |
|   |   |
|   |   |
|   |   |
|   |   |
|   |   |
|   |   |
|   |   |

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
