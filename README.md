# jenkins
## Jenkins set up
1. Log in Jenkins.
1. Click New Item.
1. Select Pipeline.
   1. Specify name of the item, "jenkins-git".
   1. Scroll down to Pipeline section (tab).
   1. Select Definition = Pipeline script from SCM.
   1. Secect SCM = Git
   1. Enter Repositories, e.g. "https://github.com/blackwindsy/jenkins.git".
   1. Optionally, specify Branches to build, by default, master.
   1. By default, Script Path = Jenkinsfile
   1. Click Apply, then Save.
1. Click Build Now.
1. Review result.

**NOTE** that your project root directory should have Jenkinsfile that is downloaded from git.  This is also placed at the project root directory under Jenkins workspace directory. 

Jenkinsfile at the root of this repository is the simple default one.  For more specialized examples, use the Jenkinsfile under the respective subdirectories.

For example, in order to use content-replace project example, set the Script Path field of the Pipeline section in Jenkins to point to the correct Jenkinsfile as desired.

    Script Path = content-replace/Jenkinsfile