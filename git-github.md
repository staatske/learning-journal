# 102 - Feb 26 Notes

## What is git?
- it's a version control system
- it lets multiple developers work on the same code
- a history of changes to your files
- the ability to view, apply, and remove those changes
- keep all of your project files in one repository
- it makes collaboration possible

## Key terms
- **version control** - records changes so you can reference them in the future. will highlight the actual changes, who did them, and when.
- three types of version control
  1. **local version control** - stored on your hard disk
  1. **centralized version control** - allows various clients/deveelopers to access a single file collectively server. this was built out of the need to have more than one person work on the same file
  1. **distributed version control** - this is similar to CVS, but avoids the single point of failure by creating mirrored repositories on multiple servers
  
  ## Cool commands
 
 ```git fetch [remote-name]``` - this will fetch data you don't have from another project
 
 ```git remote [add shortname url]``` - creates a shorter name for the git repository
 
 ```git help command``` - shows a bunch of shortcuts and help
 
 
  
  
## What does git do and how does it work
- git sends a snapshot of changes as they occur. it is a distributed centralized version control system
- it mainly works locally since most changes/versions need to be referenced locally by the same user
- git keeps a detailed log of track changes
- git also works to minimize the chances that you lose data
- three stages of changing a file in git:
  1. committed - the change is finalized in local database
  1. modified - file has been changed but not committed to the system
  1. staged - changed is flagged but not committed in next snapshot
  




[Git intro webpage](https://www.udemy.com/blog/git-tutorial-a-comprehensive-guide/)
