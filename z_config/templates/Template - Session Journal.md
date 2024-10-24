---
tags:
  - timeline
  - SessionJournals
icon: 📓
---


## Session Overview 
 
Brief session overview.






## Locations 
- 
- 
- 


## Key Learnings

- Description of any important information that the party learned.
- 
- 
 
## NPCs?
 
- 
- 
- 
 
## Items Of Importance
 
- Description
- 
- 

## What Worked 
 
- Small description.
- 
- 
- 

## Last Session
<%*
// Set folder you want to get latest file for here
const folder = "~Session Notes";
// Get all files in that folder, including nested folders
const filesInFolder = app.vault.getMarkdownFiles().filter(file => file.path.startsWith(folder));
// Sort files by ctime
filesInFolder.sort((a, b) => a.stat.ctime < b.stat.ctime ? 1 : -1);
// Get basename of latest TFile to be used in link
const latestFileName = filesInFolder[1].basename;
_%>
[[<% latestFileName %>]]




