**Read: 03 - Revisions and the Cloud**

[Git Intro](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

Version Control
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. 
By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

Local Version Control
A Local VCS entails one database on your hard disk that stores changes to files.

Centralized Version Control
The need for collaboration within a developer team on a single file or set of files led to the advent of the Centralized Version Control System (CVCS). This system entails a single server storing all changes and file versions, which can be accessed by various clients. 

Distributed Version Control
A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure
a DVCS allows clients to create mirrored repositories

**what is Git?**
Snapshots
  Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of    the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.
Local Operations
  Git mostly relies on local operations because most necessary information can be found in local resources
Tracking Changes
  Every single change applied to any file or directory is tracked by Git.
Loss of Data
States
 Commited // Modified // Staged
