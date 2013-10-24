# Create issues

Create a new issue
* without a risk for conflict
* easy ordering
* grouping per feature
* assigned to
* workflow
* quite no local installation
* version management (release notes)

# Usage
* create a new issue
* add comment
* add status
* commit

# Decisions/Problems
* Numbering can't be in the issue file name, to avoid systematic conflicts in new names.
** Manual hashing with creator name, date, hour ? (and conflicts resolution)
** Issues should be name-hash ?
* Be carefull with directories (hides files, and may result with duplicates)
* Issues should be the future Release Note of the product (with a part removed like comments, status)
* Release by creating a directory and moving related issues in it (batch of issues)
** Naming the stories