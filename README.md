# jenkins
## Jenkins set up
1. Log in Jenkins.
2. Click New Item.
3. Select Pipeline.
3.1. Specify name of the item.
3.2. Scroll down to Pipeline section (tab).
3.3. Select Definition = Pipeline script from SCM.
3.4. Secect SCM = Git
3.5. Enter Repositories, e.g. "https://github.com/blackwindsy/jenkins.git".
3.6. Optionally, specify Branches to build, by default, master.
3.7. Click Apply, then Save.
4. Click Build Now.
5. Review result.
