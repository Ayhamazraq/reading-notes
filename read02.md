# * Reflection and Discussion *

## So, what is __*Git*__ ?

#### Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

#### 1. Local Operations

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

#### 2. Tracking Changes

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

#### 3. Loss of Data

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.



#### 4. Committed

Data is securely stored in a local database

#### 5. Modified

File has been changed but not committed to the database

# Check File Status
$ git status

# add all new file
$ git add .

# Committing a File
$ git commit -m

#Pushing Changes
$ git push origin main