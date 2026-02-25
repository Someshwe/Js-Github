Git >> Version Control

    v1
    v2
    v3
new v4


>> It is distributed (on cloud)
>> Collabration
>> Tracking code changes
>> Recovery

https://git-scm.com/downloads

Github
BitBucket
GitLabs
GitPod


-- For 1st time need to configure github in our system

   >>' git config --global user.name "Someshwe" '
   >>' git config --global user.email "someshbehera2007@gmail.com" '
   >>' git config --global color.ui auto '


Mandatory Commands:
   >> git init
   >> git remote add origin https://github.com/Someshwe/Js-Github.git  (For making connection between remote server to local)


Pull Request :-
   >> git pull origin main (to pull the data files from repo)

Status :-
   >> git status (for cheacking the git update and status)

Branch :-
   >> git branch (for checking repo branch)

Push :-
   >>  "git add . " (for adding all file in repo "." is for all changes)
   >>  "git status "
   >>  "git commit -m "Commit Your Message" " (Used for commit the message for update)
   >>  "git push (Push the code) "
   >>  "git push --set-upstream origin master " (to push the code in master branch )
   >>  "git push -u origin main " (if your repo is in branch is main so use this command)


   // after this the code push to the master branch and for taking to main branch make a pull& compare to main branch 
        -- base is "main"  ->-> compare is "master"
        -- add some commit and description (optional)
        -- press the create pull request
        -- after that merge the master and main brnach -> enter the "Merge pull request" Button.
        -- hit confirm pull
        -- after that the files and code will be merged with both master and main brnach. 


