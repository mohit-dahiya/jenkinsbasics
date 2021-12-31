# jenkinsbasics
Fundamentals of Jenkins

# Install Jenkins on Ubuntu 
1. Create a Ubuntu Box (I am using Azure)
2. Install Docker
3. Install Java: https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-on-ubuntu-18-04
4. Install Jenkins: https://www.jenkins.io/doc/book/installing/linux/
5. Access it: IP_Linux:8080
6. Put the Passoword first.
7. Run command: sudo su -root => cd /var/lib/jenkins/secrets => cat initialAdminPassword => Copy the password and paste it on the Web browser

For POC Only: select Install suggestion plugin


# Access Github repoistory from Pipeline
1. Create a new Pipeline 
2. Set Repository URL under Git block
3. Change branch name from master to main
4. Set Script Path: AccessGitRepo/Jenkinsfile
5. Click on Save and trigger a build.

# Run a script from pipeline
1. Create a new Pipeline 
2. Set Repository URL under Git block
3. Change branch name from master to main
4. Set Script Path: RunScript/Jenkinsfile
5. Click on Save and trigger a build.
