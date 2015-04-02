###Exorcise One

date "+%A"

###Notes

misc

 * man _commandname_  gives info on command 
 * date _format argument_  gives date and time info in specified format 
 * history gives previously entered commands
 * uparrow gives previous command

Creating a File

 * touch _filename_ creates an empty file with that name in your working directory
  * or "touch $HOME/_filename_" creates an empty file with that name in your home directory
  * or "touch ~/_filename_" makes one in the home directory too
  * or "touch /_directorypath_/_directoryname_/_filename" creates an empty file with that name in the given directory (this is an absolute directory specification)
* cat > _filename_  creates file in working directory of given name, and starts giving it content straight from the terminal
  * note that "control D" ends the file and returns the normal command line 
 * nano
  * "control o" to save
  * "control x" to exit nano

Viewing a File

 * cat _filename_  displays file content in terminal
 * nano _filename_ opens file in word editer page in terminal
 * head _filename_  displays first 10 lines of file.
  * or "head -1 _filename_" shows first 1 line. numbers beside 1 also work
 * tail _filename_ display last 10 lines of file  
  * or "tail -1 _filename_" shows last 1 line. 

Navigating Directory

 * ls prints the names of the files within your working directory
  * or "ls .." gives the names of the files within your parent directory
  * note that . means home directory and .. means parent directory
  * or "ls /_direcorypath_/_directoryname" lists the files in the specified  
 directory, regaurdless of your working directory (it is an absolute path instead of relative path) 
 * pwd prints the name of working directory (the directory you are in)
 * cd /_directorypath_/_directoryname_  changes your working directory to what's specified
  * or "cd" changes your working directory to the home directory
  * or "cd /" changes your working directory to the root directory

Managing Files
 
* mkdir _directoryname_ makes a directory within the working directory of given name
* mv _filename_ _directoryname_ moves a file into the specified directory
 * or "mv _filename_ _newfilename_" renames a file
 * or "mv _filename_ _otherfilesname_ _otherfilename_ _directory_" moves miltiple files into the directory
 * or "mv _abrev_* _directorynaem_" will send all files with a name starting with the abreviation (hurray for wildcard *) 
* cp _locateddirectory_/_filename_ _targetdirectory_ creates a copy of a file in the given directory
* ln -s _directoryname_/_filename_ _targetdirectory_/_alliasname_    gives an alias that also calls the file in addition to its other name
* rm _filename_ deletes the file

