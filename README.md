# Learning_GIT01
This is a guide to learn GIT and GIthub 
# Learn_GIT01
 This is my first GIT repositry.
<br> 
Author-> Pratyush Rastogi
hello guys,
Here I will be learning about the features of GITHUB and GIT
the commands we have learned till now are---

GIT ??? 
 => git is a version control system that helps to track changes in code or to track the history of our project and collaborate with different developers as team 
 we can use GIT bash to access GIT 

GITHUB???
 => github is a website that allows developers to store and manage their code using git 
     https://github.com/
    firstly make an account on github using a email id
    then got to the symbol at the topmost right when you click it you will get and option "Your repositry"
    after clicking on it thier will be an option to make a new repoisitry 
    make a new repositry and then add a readme file 

a readme file is like the index of your notebook you can write the content of your project of what you are going 
to do and what your aims are of the project or details about the project 
and make your repositry public so that others can view your profile 
then comes the next part 

download GIT
https://git-scm.com/downloads
1. go to this website and c hoose accordingly whichever device you have(macos,linux,windows)
<br>
<br>
2.after selecting click on "click here to download"
<br>
<br> 
3. after installing the file open it and click next then without changing the fiel location click on next again 
<br>
<br>
4. then a window pops up with the name select components now some of the components might already be selected and you have to select some yourself additional icons on desktop select the above components 
<br>
<br>
5. now another window pops up with name select start menu folder
just press next 
now again next by leaving files at default value then comes a window "adjusting the name of the initial branch in new repositries " choose 
"override the default branch name for new repositries "
<br>
<br>

6. now the next window will be "adjusting you PATH environment"
here choose "use git and optional unix tools from command prompt"
and click next 
 now you just have to click next until it gets intalled itself 
 and you will see an icon with the name "Git Bash" click on it and then use command "git config --global user.name "yourname" now in your name you are going to put the user id of your github account then use command 
"git config --global user.email "youremail@gmail.com" now in this you will add the email which you used to make your github account 
now run "git config --list"
now at the last you will see the name and email changed 
    why we have used global???
    => there are two ways global and local 
     in global it makes chnages in entire system 
     whereas in local only in a single repo

 REMEMBER these settings are for beginners if you already know about GIT and want to install it differently you can" 
 now also install vscode 
 so that we can code and learn about GIT better 

 after installling vscode
  make a folder of your choice and open it and then go to github and open your repositry and access your repositry you made in the starting there will be and option "Code" click on it and you can find the link of the repositry in https format copy it 
then open the terminal in vscode using ctrl+shift+'
write the code in the ternminal 
git "clone then  the  link"
you will see that the github repositry files are now available at the folder you just made by this way you can access any kind of file from remote location?(github) to your local system or device
gi<br>
<br>
<br>
1. git clone <- github repositry link (in http form)>
<br>
2. git status to find out the status of the files in the folder 
-----There are four kinds of status 
  >>>Untracked = new files that git doesn't yet track
  <br>
  >>>modified  = the files in which changes are made but they are not yet committed or added
  <br>
  >>>staged    = when the file is ready to be committed but it is just added so it ghoes to the git staging area 
  to be committed
  <br>
  >>>unmodified= when there is no change made in the file 
<br>
  3.Add git add <-"file name "->
  >>> if there are many files to be added the     "git add ."
 
 <br>
  4.Commit -> it is the record of change
     " git commit -m "some-message" 
<br>
  5.Push -> It helps in pushing the local repositry into the remote repositry 
  "git push main origin"
  
<br>
<br>

  Now what is remote and Local ????
-> remote is when the file is stored in platforms like github and local means means stored locally on our 
  own system or computer/device 
  and when we use push command we will be tranfering the contents of local repositry and changfes made to 
  the file to the remote repositry from where we started our project.
<br>
