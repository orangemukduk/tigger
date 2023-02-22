# tigger
implements Tigger, a subset of the version control system Git

tigger-init : the tigger-init command creates an empty Tigger repository.

tigger-add filenames : The tigger-add command adds the contents of one or more files to the index.

tigger-commit -m message : The tigger-commit command saves a copy of all files in the index to the repository.

tigger-log: The tigger-log command prints a line for every commit made to the repository.

tigger-show [commit]:filename: The tigger-show should print the contents of the specified filename as of the specified commit.
