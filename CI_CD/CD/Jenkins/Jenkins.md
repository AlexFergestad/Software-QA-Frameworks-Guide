<h1>
  <img src="https://logos-world.net/wp-content/uploads/2023/12/Jenkins-Emblem.png" alt="Jenkins Logo" width="50" style="vertical-align:middle">
  Jenkins
</h1>

## What is Jenkins

Jenkins is an open-source tool built in Java that enables teams to perform continuous integration and continuous deployment activities, regardless of the platform used. Jenkins offers a vast plugin ecosystem to extend its functionality and usability. Most plugins are extensible and we can also customize plugins the way we want.

## Why is It Used?

- Jenkins can distribute builds to multiple computers built with different operating systems.
- The most important feature of Jenkins is that it increases developer productivity tremendously by automating many manual tasks.

## How Does it Work?

Jenkins uses a master/slave architecture to manage distributed builds. The main Jenkins server in the distributed architecture is called the master server. The master's job is to pull the code from any SCM, schedule build jobs, dispatch scheduled jobs to slave instances for execution, monitor slaves (which can be online or offline as required), and finally to record and present build results. The primary job of the master is to orchestrate the various builds and jobs.

Slave instances are Java executables running on remote machines. Slaves accept requests from the master instance, execute specific jobs, and report build statuses and results back to the master. Slaves can run on different types of operating systems. 

## To Run Jenkins on this Computer, Run these Commands:

Type: "cd C:Tools"
>> java -jar jenkins.war --httpPort=8080

## Additional Info

- Jenkins uses a Distributed Architecture
- The Master in Jenkins does not monitor slave instances