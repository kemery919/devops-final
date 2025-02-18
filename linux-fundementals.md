# Make directory
mkdir "directory name without quotes"

# Create file
touch fileA

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