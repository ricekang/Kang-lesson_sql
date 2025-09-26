.git --version
.git config --global user.name 'Kang'
.git config --global user.email "a0985558249@gmail.com"
.git init

#Common Used Instruction
.git status
.git log --oneline

#Track File and Folder
create a new README.md file,ctrl +s
.git add [full file name]
.git add *.file_sub_name
.git add .
.git commit -m 'message'

#Supplementary: other instruction of modify file
.git reset --soft HEAD~ #回到上一動/canceling commit
.git reset --hard [version.nunber]