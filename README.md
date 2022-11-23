# Jenkins Pipeline

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=DevSecOpsSamples_jenkins-pipeline&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=DevSecOpsSamples_jenkins-pipeline) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=DevSecOpsSamples_jenkins-pipeline&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=DevSecOpsSamples_jenkins-pipeline)

Provide Declarative Pipelines for Java, Python, Sonarqube, and CDK.

To setup Jenkins and Sonarqube, refer to below repositories:

* https://github.com/DevSecOpsSamples/gke-jenkins
* https://github.com/DevSecOpsSamples/jenkins-fargate-cdk
* https://github.com/DevSecOpsSamples/sonarqube-fargate-cdk

## Java

| Pipeline                                                     | Description                                             |
|--------------------------------------------------------------|---------------------------------------------------------|
| [Jenkinfile.gradle.ci](Jenkinfile.gradle.ci)                 |  Gradle, UnitTest, and Sonarqube                |
| [Jenkinfile.gradlew.ci](Jenkinfile.gradlew.ci)               |  Gradle Wrapper, UnitTest, and Sonarqube                |
| Jenkinfile.mavenw.ci    (TBD)               |  Maven Wrapper, UnitTest, and Sonarqube                 |
| Jenkinfile.mavenw-alpine.ci (TBD)    |  Maven Wrapper, UnitTest, and Sonarqube inside Docker   |
  
## Python

| Pipeline                                                     | Description                                    |
|--------------------------------------------------------------|------------------------------------------------|
| TBD            | TBD             |

## CDK

| Pipeline                                                     | Description                                    |
|--------------------------------------------------------------|------------------------------------------------|
| [Jenkinfile.cdk.ci](Jenkinfile.cdk.ci) (TBD)                 | CI Pipeline for CDK                            |
| Jenkinfile.cdk.deploy    (TBD)      | Deployment Pipeline for CDK                    |

## References

* https://www.jenkins.io/doc/book/pipeline/