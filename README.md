1. What Is a Git Remote?

A Git remote is a reference to a remote repository (like GitHub, GitLab, Bitbucket).

Think of it like:

Your local system = your computer
Your remote = GitHub URL

Git connects them using:

git remote add <name> <url>

The default remote name is:

origin

This simply means:

“origin = GitHub repository URL where my code goes.”


🔗 2. Checking Existing Remotes
To see what remotes are already configured:
 remote -v 

Example output:

origin  git@github.com:OldUser/oldrepo.git (fetch)
origin  git@github.com:OldUser/oldrepo.git (push)

 
 Git Remote Commands Cheat Sheet

➕ Add a remote

 remote add origin <url>Show more lines

❌ Remove a remote

 remote remove originShow more lines

🔧 Update an existing remote

 remote set-url origin <new-url>Show more lines

🔍 Check remotes

 remote -v 
Update all remotesgit remote update

<img width="587" height="410" alt="image" src="https://github.com/user-attachments/assets/83e8b200-e8b0-41e9-a979-39cccdebe972" />



