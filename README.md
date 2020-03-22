# jenkins
## Jenkins set up
1. Log in Jenkins.
1. Click New Item.
1. Select Pipeline.
   1. Specify name of the item.
   1. Scroll down to Pipeline section (tab).
   1. Select Definition = Pipeline script from SCM.
   1. Secect SCM = Git
   1. Enter Repositories, e.g. "https://github.com/blackwindsy/jenkins.git".
   1. Optionally, specify Branches to build, by default, master.
   1. Click Apply, then Save.
1. Click Build Now.
1. Review result.
