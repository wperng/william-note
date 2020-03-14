Jenkins

### Start Jenkins
1. Start Jenkins by Java: 
    1. Reference: https://blog.couchbase.com/deployment-pipeline-docker-jenkins-java-couchbase/
    2. download war from from: https://jenkins.io
    3. JENKINS_HOME=~/.jenkins java -jar ~/Downloads/jenkins-2.21.war --httpPort=9090
    4. william's experience: Just go to the war folder and run java -jar jenkins.war --httpPort=9090 (admin/admin for the local version)
2. Start Jenkins by Docker
    1. (Approach 1) Start both Master and Slave: https://medium.com/@jagdale0210/deploy-jenkins-master-slave-as-docker-container-ea8557d0d52a
    2. (Approach 2) Start Master: https://wiki.jenkins.io/display/JENKINS/Installing+Jenkins+with+Docker
