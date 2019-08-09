# Jenkins Engineer Exam 

## Key CI/CD/Jenkins Concepts  
This topic comprises approximately 18% of the exam. Questions cover the following topics:
* Continuous Delivery/Continuous Integration Concepts
  * Define continuous integration, continuous delivery, continuous deployment
    * [Continuous Integration](https://www.martinfowler.com/articles/continuousIntegration.html)
    * [Continuous Delivery](https://martinfowler.com/bliki/ContinuousDelivery.html)
    * [Deployment Pipeline](https://martinfowler.com/bliki/DeploymentPipeline.html)
    * [CD Pipeline Anatomy](http://www.informit.com/articles/article.aspx?p=1621865&seqNum=2)
    * [What is a CD Pipeline](https://devops.com/continuous-delivery-pipeline/)
    * [Implementing Continuous Delivery](https://jaxenter.com/implementing-continuous-delivery-117916.html)
    * [Setup Continuous Delivery Pipelines](https://www.infoq.com/articles/orch-pipelines-jenkins/)
    * [Continuous Deliver Introduction to Concepts and Tools](https://technologyconversations.com/2014/04/29/continuous-delivery-introduction-to-concepts-and-tools/)
    * [Continuous Delivery - Wikipedia](https://en.wikipedia.org/wiki/Continuous_delivery)
    * [Artifact Software Development - Wikipedia](https://en.wikipedia.org/wiki/Artifact_%28software_development%29)
    * [Build Automation - Wikipedia](https://en.wikipedia.org/wiki/Build_automation)
    * [Distributed version control - Wikipedia](https://en.wikipedia.org/wiki/Distributed_version_control)
    * [List of version control software - Wikipedia](https://en.wikipedia.org/wiki/List_of_version_control_software)
    * [Smoke Testing - Wikipedia](https://en.wikipedia.org/wiki/Smoke_testing_(software))
  * Difference between CI and CD
  * Stages of CI and CD
  * Continuous delivery versus continuous deployment
* Jobs
  * What are jobs in Jenkins?
    * [Administering Jenkins](https://wiki.jenkins.io/display/JENKINS/Administering+Jenkins)
    * [Terminology](https://wiki.jenkins.io/display/JENKINS/Terminology)
    * [Extreme feedback lamp switch gear style](https://jenkins.io/blog/2013/09/05/extreme-feedback-lamp-switch-gear-style/)
    * [Remoting Issue](https://wiki.jenkins.io/display/JENKINS/Remoting+issue)
    * [Jenkins Job Builder](https://docs.openstack.org/infra/jenkins-job-builder/triggers.html)
  * Types of jobs
  * Scope of jobs
* Builds
  * What are builds in Jenkins?
    * [Jenkins Pipeline](https://jenkins.io/doc/book/pipeline/)
    * [Jenkins Handbook](https://jenkins.io/doc/book/)
    * [Jenkins Plugins](https://plugins.jenkins.io/)
  * What are build steps, triggers, artifacts, and repositories?
  * Build tools configuration
    * [Distributed Builds - Offline status and retention strategy](https://wiki.jenkins.io/display/JENKINS/Distributed+builds#Distributedbuilds-Offlinestatusandretentionstrategy)
* Source
  * What are source code management systems and how are they used?
  * Cloud-based SCMs
  * Jenkins changelogs
  * Incremental updates v clean check out
  * Checking in code
  * Infrastructure-as-Code
  * Branch and Merge Strategies
    * [Branching and Merging](https://www.red-gate.com/simple-talk/opinion/opinion-pieces/branching-and-merging-ten-pretty-good-practices/)
* Testing
  * Benefits of testing with Jenkins
  * Define unit test, smoke test, acceptance test, automated verification/functional tests
    * [What is unit test, integration test, smoke test, regression test?](https://stackoverflow.com/questions/520064/what-is-unit-test-integration-test-smoke-test-regression-test)
* Notifications
  * Types of notifications in Jenkins
    * [Notifications](https://www.cloudbees.com/blog/sending-notifications-pipeline)
  * Importance of notifications
* Distributed Builds
  * What are distributed builds?
  * Functions of masters and agents
* Plugins
  * What are plugins?
  * What is the plugin manager?
* Jenkins Rest API
  * How to interact with it
    * [Remote Access API](https://wiki.jenkins.io/display/JENKINS/Remote+access+API)
  * Why use it?
* Security
  * Authentication versus authorization
    * [Authentication, authorization and accounting](http://searchsecurity.techtarget.com/definition/authentication-authorization-and-accounting)
    * [Securing Jenkins](https://wiki.jenkins.io/display/JENKINS/Securing+Jenkins)
    * [Quick and simple Security](https://wiki.jenkins.io/display/JENKINS/Quick+and+Simple+Security)
  * Matrix security
    * [Matrix based security](https://wiki.jenkins.io/display/JENKINS/Matrix-based+security)
  * Definition of auditing, credentials, and other key security concepts
* Fingerprints
  * What are fingerprints?
  * How do fingerprints work?
* Artifacts
  * How to use artifacts in Jenkins
  * Storing artifacts
* Using 3rd party tools
  * How to use 3rd party tools
    * [Jenkins Plugins](https://plugins.jenkins.io/)
* Installation Wizard
  * What is the Jenkins Installation Wizard?
    * [Jenkins Installation and Setup](https://jenkins.io/doc/book/installing/)
    * [Jenkins Documentation](https://jenkins.io/doc/)
    * [Jenkins Pipeline]
  * How to use the Wizard?
  * Which configurations are covered by the Installation Wizard?

## Books
* [Jenkins Definitive Guide - SafariBooksOnline](https://www.safaribooksonline.com/library/view/jenkins-the-definitive/9781449311155/ch05.html)


## Jenkins usage (features and functionality)
This topic comprises approximately 23% of the exam. Questions cover the following topics:
* Jobs
  * Organizing jobs in Jenkins
  * Parameterized jobs
  * Usage of Freestyle/Pipeline/Matrix jobs
* Builds
  * Setting up build steps and triggers
    * [Parallelism and Distributed Builds](https://www.cloudbees.com/blog/parallelism-and-distributed-builds-jenkins)
  * Configuring build tools
  * Running scripts as part of build steps
    * [Post-initialization script](https://wiki.jenkins-ci.org/display/JENKINS/Post-initialization+script)
* Source Code Management
  * Polling source code management
  * Creating hooks
  * Including version control tags and version information
    * [Features controlled by system properties](https://wiki.jenkins.io/display/JENKINS/Features+controlled+by+system+properties)
* Testing
  * Testing for code coverage
  * Test reports in Jenkins
  * Displaying test results
  * Integrating with test automation tools
  * Breaking builds
* Notifications
  * Setup and usage
  * Email notifications, instant messaging
  * Alarming on notifications
* Distributed Builds
  * Setting up and running builds in parallel
    * [Distributed Builds](https://wiki.jenkins.io/display/JENKINS/Distributed+builds)
  * Setting up and using SSH agents, JNLP agents, cloud agents
  * Monitoring nodes
* Plugins
  * Setting up and using Plugin Manager
  * Finding and configuring required plugins
* CI/CD
  * Using Pipeline (formerly known as “Workflow”)
  * Integrating automated deployment
  * Release management process
  * Pipeline stage behavior
* Jenkins Rest API
  * Using REST API to trigger jobs remotely, access job status, create/delete jobs
* Security
  * Setting up and using security realms
  * User database, project security, Matrix security
  * Setting up and using auditing
  * Setting up and using credentials
* Fingerprints
  * Fingerprinting jobs shared or copied between jobs
* Artifacts
  * Copying artifacts
  * Using artifacts in Jenkins
  * Artifact retention policy
* Alerts
  * Making basic updates to jobs and build scripts
  * Troubleshooting specific problems from build and test failure alerts


## Building Continuous Delivery (CD) Pipelines
This topic comprises approximately 16% of the exam. Questions cover the following topics:
* Pipeline Concepts
  * Value stream mapping for CD pipelines
    * [Jenkins Handbook](https://jenkins.io/doc/book/)
  * Why create a pipeline?
  * Gates within a CD pipeline
    * [Jenkins Pipeline](https://jenkins.io/doc/book/pipeline/)
  * How to protect centralized pipelines when multiple groups use same tools
  * Definition of binary reuse, automated deployment, multiple environments
  * Elements of your ideal CI/CD pipeline - tools
    * [Controlling the flow with Stage, Lock and Milestone](https://jenkins.io/blog/2016/10/16/stage-lock-milestone/)
  * Key concepts in building scripts (including security/password, environment information, etc.)
    * [Pause and resume execution](https://github.com/jenkinsci/pipeline-plugin/blob/feb5bf44573dfc9379d9551f12b0372907e787be/README.md#pause-and-resume-execution)
* Upstream and downstream
  * Triggering jobs from other jobs
  * Setting up the Parameterized Trigger plugin
  * Upstream/downstreamjobs
* Triggering
  * Triggering Jenkins on code changes
    * [Executor Step Test](https://github.com/jenkinsci/pipeline-plugin/blob/feb5bf44573dfc9379d9551f12b0372907e787be/aggregator/src/test/java/org/jenkinsci/plugins/workflow/steps/ExecutorStepTest.java#L165-L214)
    * [Write File Step](https://github.com/jenkinsci/pipeline-plugin/blob/e0263fc7275e804785e4e93054ef0f2f2945a2dc/basic-steps/src/main/resources/org/jenkinsci/plugins/workflow/steps/WriteFileStep/help.html#L1)
  * Difference between push and pull
  * When to use push vs. pull
* Pipeline (formerly known as “Workflow”)
  * Benefits of Pipeline vs linked jobs
  * Functionalities offered by Pipeline
  * How to use Pipeline
    * [Pipeline Plugin 2.4](https://plugins.jenkins.io/workflow-aggregator#PipelinePlugin-2.4%28Sep21%2C2016%29)
  * Pipeline stage view
* Folders
  * How to control access to items in Jenkins with folders
    * [List Views](https://go.cloudbees.com/doc/index.html)
  * Referencing jobs in folders
* Parameters
  * Setting up test automation in Jenkins against an uploaded executable
    * [Injecting Secrets into Jenkins Build Jobs](https://support.cloudbees.com/hc/en-us/articles/203802500-Injecting-Secrets-into-Jenkins-Build-Jobs)
  * Passing parameters between jobs
  * Identifying parameters and how to use them: file parameter, string parameter
  * Jenkins CLI parameters
    * [Jenkins CLI](https://wiki.jenkins.io/display/JENKINS/Jenkins+CLI)
    * [Crontab](https://github.com/jenkinsci/jenkins/blob/3537831a42cd5b3b27a41fcde9b1f201962f38a1/core/src/main/grammar/crontab.g#L68-L71)
    * [Help Spec](https://github.com/jenkinsci/jenkins/blob/3537831a42cd5b3b27a41fcde9b1f201962f38a1/core/src/main/resources/hudson/triggers/TimerTrigger/help-spec.html#L45-L46)
* Promotions
  * Promotion of a job
  * Why promote jobs?
  * How to use the Promoted Builds plugin
* Notifications
  * How to radiate information on CD pipelines to teams
* Pipeline Multibranch and Repository Scanning
  * Usage of Multibranch jobs
    * [Pipeline Multibranch](https://jenkins.io/doc/book/pipeline/multibranch/)
  * Scanning GitHub and BitBucket Organization
  * ScanningbasicSCMrepositories
* Pipeline Global Libraries
  * How to share code across Pipelines
  * Usages of the Shared Libraries
    * [Pipeline Global Shared Libraries](https://jenkins.io/doc/book/pipeline/shared-libraries/)
  * Interaction with Folders and Repository scanning
  * Security and Groovy sandbox


## CD-as-Code Best Practices
This topic comprises approximately 10% of the exam. Questions cover the following topics:

* Distributed builds architecture
  * [Distributed Builds Architecture](https://go.cloudbees.com/docs/cloudbees-documentation/cookbook/book.html#_distributed_builds_architecture)
  * [Cookbook](https://go.cloudbees.com/docs/cloudbees-documentation/cookbook/book.html)
  * [Pipeline as code](https://go.cloudbees.com/docs/cloudbees-documentation/cookbook/book.html#pipeline-as-code)
* Fungible (replaceable) agents
* Master-agent connectors and protocol
* Tool installations on agents
  * [Choosing the right hardware](https://go.cloudbees.com/docs/cloudbees-documentation/cookbook/book.html#_choosing_the_right_hardware_for_masters)
* Cloud agents
  * [Remoting](https://wiki.jenkins.io/display/JENKINS/Remoting+issue)
* Traceability
* High availability
  * [Architecting for scale](https://go.cloudbees.com/docs/cloudbees-documentation/cookbook/book.html#_architecting_for_scale)


## Sample Questions

1. By definition, what does a Continuous Delivery pipeline consist of?  
a. Backlog items  
b. Artifacts  
c. Stages  
d. Tickets  
e. Commitments  
2. You need to execute a shell script (/usr/bin/prepare-env) just before a Linux agent is started. How do you achieve this?  
a. Use the "Suffix Start Agent Command" configuration option on the agent configuration.  
b. Use the "Prefix Start Agent Command" configuration option on the agent configuration.  
c. Configure a .profile file containing a call to /usr/bin/prepare-env in the home directory of the OS user which runs the agent process.  
d. Add a shell step to each Job tied to this agent to execute the shell script.  
3. Suppose you are asked to obtain the config.xml of a folder (myFolder) from a script or HTTP client using the Jenkins Remote API. The folder exists at the root of a Jenkins master. Which URL pattern is correct for obtaining this configuration file?  
a. root/job/myFolder/config.xml  
b. root/folder/myFolder/config.xml  
c. root/myFolder/config.xml  
d. root/myFolder?param=config.xml  
e. root/api/getConfig?source=myFolder  
4. What architecture is recommended by the Jenkins Cookbook for a scalable Jenkins environment?  
a. Distributed Builds Architecture  
b. Central Master Architecture  
c. Automatic Builds Architecture D. Manual Polling Architecture E. One-Shot Build Architecture  
5. In a Cluster Operations Job, which THREE of the following steps can be applied to a Client Master only?  
a. Install Jenkins  
b. Upgrade Jenkins  
c. Upgrade all plugins D. Install plugin  
d. Uninstall Jenkins  

Answers to Sample Questions:
1. C
2. B
3. A
4. A
5. B, C, D