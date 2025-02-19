# Make directory
mkdir "directory name without quotes"

![mkdir-example](https://emery-devops-final.s3.us-east-1.amazonaws.com/mkdir.png)

# Create file
touch fileA

![touch-example](https://emery-devops-final.s3.us-east-1.amazonaws.com/touch.png)

# Copy file to another
cp fileA fileX

# Copy all files from folder to a new location
cp folderA/* folderX/

# Deleting a folder that has contents
Safe way:

rm folderA/*

rm -d folderA



Just remove it all at once:

rm -rf folderA

![rf-example](https://emery-devops-final.s3.us-east-1.amazonaws.com/rm-folder.png)