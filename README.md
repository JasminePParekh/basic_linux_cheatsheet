# basic_linux_cheatsheet
```
pwd #absolute path of the current directory
ls #files in the directory
ls -a #hidden files in the directory
cd [PATH] #to a directory
cd.. #go to home directory
mkdir [DIRECTORY NAME] #make a directory
rmdir [EMPTY DIRECTORY NAME] #remove an empty directory
rm [FILES/DIRECTORY WITH FILES] #remove an a directory or files
rm -r [DIRECTORY] #just delete the directory
touch [NEW FILE] #create a new file
[COMMAND] --help #help about how to use a command
cp [LOCATION OF FILE TO COPY][LOCATION TO COPY IT TO] #copy files
mv [ORIGINAL LOC OF FILE][DESIRED LOC OF FILE] #to move files or to rename files
locate [FILE NAME] #find a file path
-i [FILTER SEARCH] # ignore case for search filter
echo [MESSAGE] >> [FILE NAME] #Add a message into file
cat [FILE NAME] #display the contents of a file
vi [FILE NAME] #cli editor for a file
sudo [COMMAND] #want any command to be done with admin/root privileges
zip/unzip [FILE NAME] #zip or unzip a file
ping [website] #check internet connection
ps -ef | grep -i [SEARCH FILTER] #find processes with specific search filter
scp jasmine@mr-dl31:file_path . #grabs file from remote server and puts it in current directory
scp /Users/jparekh/.../local_file jasmine@mr-dl31:/file_path/copied_file #copies file from local onto remote server

```
- TAB = fill up the command line
- CTRL+C = stop any command
- CTRL+Z = force stop any command
