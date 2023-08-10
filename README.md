# jenkin console output
Started by user surendar chintaginja
Running as SYSTEM
Building on the built-in node in workspace /var/lib/jenkins/workspace/testjon
The recommended git tool is: NONE
using credential 6b916e79-6627-4597-acb7-5e3879b2eeb6
 > git rev-parse --resolve-git-dir /var/lib/jenkins/workspace/testjon/.git # timeout=10
Fetching changes from the remote Git repository
 > git config remote.origin.url https://github.com/chintaginja/project2.git # timeout=10
Fetching upstream changes from https://github.com/chintaginja/project2.git
 > git --version # timeout=10
 > git --version # 'git version 2.34.1'
using GIT_ASKPASS to set credentials 
 > git fetch --tags --force --progress -- https://github.com/chintaginja/project2.git +refs/heads/*:refs/remotes/origin/* # timeout=10
 > git rev-parse refs/remotes/origin/main^{commit} # timeout=10
Checking out Revision 7b72980480ac0823c33b83be5b8726fda21f7b88 (refs/remotes/origin/main)
 > git config core.sparsecheckout # timeout=10
 > git checkout -f 7b72980480ac0823c33b83be5b8726fda21f7b88 # timeout=10
Commit message: "Added the file for project"
 > git rev-list --no-walk 7b72980480ac0823c33b83be5b8726fda21f7b88 # timeout=10
[Set GitHub commit status (universal)] PENDING on repos [] (sha:7b72980) with context:testjon
Finished: SUCCESS
