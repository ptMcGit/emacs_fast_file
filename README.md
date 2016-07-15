# Fast-File

## What does it do?

Uses completion to list a set of relevant files depending on the flag provided e.g. `-h` for files in the home directory.
The `f` option will list files located in your home folder in the directory `fast_file`.

Once fast file is invoked it opens selected file with emacserver, and alternatively emacs if no server is available.

## How to use it

Source the main file into the environment:

    source emacs_fast_file

List files to open in your home directory:

    emacs_fast_file -h <tab>
