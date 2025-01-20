# INTRO
xitbash is a simple bash script to allow display and editing of an [x]it formated task file

Suggestions for improving the code welcome :-)

# REF
[x]it https://github.com/jotaen/xit

initial terminal code discussion https://github.com/jotaen/xit/discussions/12

grep gensub https://github.com/coderofsalvation/kanban.bash

# NOTES
There are two versions. 

xitbash tries to follow the [x]it format 

xitbash-todo has made some changes to the [x]it format to allow todo.txt task lists to work

( ) used instead of [ ] 

(A) used to match (@)

(W) used to match (.)

Use # and + to mark tags

# USAGE
-o open file in editor

-e 'line' open file in editor at line specified

-a 'new task' add new task

-s 'search term' search

-c 'line' 'new status' change task status

-x print task list in terminal

-k print kanban view in terminal
