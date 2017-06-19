# droid_club
this is the repo for the droid club
This is the official repository where all the code would be present
Commands for pushing code in this repository
open a cmd (for windows ) , terminal for mac in your system
note: for windows you would be needing git bash , download git from internet and link your cmd to the bash terminal or you 
can simply run in the bash terminal (your choice ) . Then you are ready to rock

Step 1 :

open the terminal in the folder that you want to push to github repository .
for windows : shift+right click-->open cmd here
You can also reach by changing the directory in the terminal

Step 2 :

write the command :

git init

//this would initialize an empty git repository in that folder

Step 3 :

git status 

//this command would show you all the files present in the directory and checks their status
//red-->The files are not ready for upload right now
//green-->the files are ready to be uploaded

Step 4 :

git remote add origin https://github.com/shivamaggarwal1597/droid_club.git

//this would add the remote to the repository where you want to upload the code
//its just like typing the URL for the website you want to go :p

Step 5:

git add .

//this would add the files in the directory to the master and then the master is ready to be pushed to the remote
  
  Step 6:
  
  git commit -m " YOur message will come here "
  
  // IN this step you commit the code to the master . In the part inside " " you can write any description as you please
  
  Step 7(LAST ONE):
  
  git push -u origin master 

// YOu push the master to the origin and our code is uploaded . WE DID IT FINALLY

 

