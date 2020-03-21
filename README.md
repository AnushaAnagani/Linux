# Linux

## Pipeline Master Project
### Task
List all the contents in /etc and /run directories and redirect those contents to a files called “file1.txt” and “file2.txt” respectively . 
Combine the contents of file1.txt and file2.txt into another file called “unsorted.txt”.
Also reverse the combined contents of “file1.txt” and “file2.txt” output to another file called “reversed.txt”.
https://github.com/AnushaAnagani/Linux/blob/master/Linux_Assignment_Pipes.pdf
https://github.com/AnushaAnagani/Linux/blob/master/Cmds_Pipe_Tee_Usage

## “Super Secret” Project (usage of Locate and Find commands)
### Task 1
Create a folder called super_secret_stuff and inside that folder place a file called top_secret.txt.
top_secret.txt may contain whatever content you wish. 
Once the file is created, use the updatedb command and the locate command to find the path to top_secret.txt . 
Using redirection, save the path that the locate command gives you to a new file called secret_place.txt in your home directory. 

### Task 2
Part A) 
Create an advanced pipeline that will create a sorted list of the various file sizes on your system. 
Firstly, use the find command to search entire file tree; starting from the / directory, for all files that are over 1 MebiByte in size. 
Use the maxdepth option to limit the find command’s search to only go 4 levels deep. 
The search should only show files, not directories. 
Use the -exec option of the find command to run the ls -lh command on each of those results.

Part B) 
Sort the output from Part A using the sort command. 
You should sort the data so that the largest file sizes are at the top of the list and the smallest file sizes are at the bottom. 
Using redirection, output this data to a file called filesizes.txt in your home directory. 
Hint 1: You will need to use the –k option for the sort command and define a KEYDEF. 
Hint 2: The file sizes are the 5th column of data. Hint 3: You need to let the sort command to be able to deal with “human-readable” data. 

## “Hungry for Data” Project 
### Task 1 
Create a bash script called hungry.sh in your home directory.
hungry.sh should do two things:
Firstly, it should output the text “I am hungry. Feed me data.“ to a file in your home directory called demands.txt .
Secondly, hungry.sh should also output the date and time that the demand was made to a file in your home directory called demands.log 
Do ensure that each output is appended to the previous one. 

### Task 2
Once you have created hungry.sh , edit your crontab and add a new row so that hungry.sh runs every minute. 

https://github.com/AnushaAnagani/Linux/blob/master/Linux_project_sheduling.pdf
https://www.loom.com/share/ce6427d009c84bea865d65f53a8e243f




