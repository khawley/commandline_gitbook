# Command Summary

Note for below.  `[]` will be used to signify _optional_ flags or arguments. `<>` will be used to signify _placeholders_ for argument text. `...` will be used to signify a _repeat_ of the type before


- `pwd` - shows your current working directory
- `ls [-al] [<files_or_folder> ...]` - used to show the contents of the current or specified directory/files. 
    + `-a` reveals hidden files
    + `-l` presents in a table/list like format
- `cd [<folder_path>]` - changes directory to the specified folder
    + if no folder given, will go to the home `~` directory
- `mkdir <new_directory_path>` - creates a new directory
- `touch <filename>` - creates an empty file, if it doesn't already exist
- `rm [-r] [<path> ...]` - removes the files listed
    + `-r` must be used when deleting a _non empty_ directory.  It will delete the directory and its contents.
- `mv <current_file> <new_file_name>` - rename a file to a new name
    + `mv <current_file> <new_folder_path>` - move a file to a different folder
    + `mv <current_file> <new_folder_path>/<new_file_name>` - combined move and rename of the file
- `mkdir <new_folder>` - create a new folder
- `rmdir <folder>` - remove an empty folder
    + for a non-empty folder, see the above `rm -r`
- `clear` - scroll history up and provide a blank space on your terminal
