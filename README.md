# driveby
batch files that may or may not be useful. 

each lift file (one for document folder and one for downloads) will automatically locate the documents folder of the current user and copy the files to a flash drive that the batch file is ran on. will not copy files larger than 250mb by design. If you want to change that, edit the robocopy line "/max:" batch file also maps what flash drive you plugged in and assigns it the drive letter of d:/ everytime to make copying and running of other commands easier. 
