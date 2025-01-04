to delete local branch
- git branch -d dev

to delete remote branch
- git push origin :dev

Annotated Tags:
- They can include metadata like the tagger's name, email, and a message.
- Useful for release versions or milestones.
- ex :git tag -a v1.7 -m "Version 1.7"

Lightweight Tags:
- Simple references to a specific commit
- No metadata or message
- ex: git tag v1.7

when to use rebase :
- to incorporate upstream changes into your branch
- to avoid merge commits in Feature Branches
  
to list tags :
- git tag

to delete tags locally :
- git tag -d v1.7

to delete tags remotly :
- git push origin --delete v1.7
  

![Alt text](images/basket.png)
  
