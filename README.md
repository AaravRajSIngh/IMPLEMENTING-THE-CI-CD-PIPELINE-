# IMPLEMENTING-THE-CI-CD-PIPELINE-
We will be using a number of tools and will try to create a standard CI/CD pipeline.
<br>
github/AaravRajSIngh
![Screenshot from 2023-06-14 10-32-30](https://github.com/AaravRajSIngh/IMPLEMENTING-THE-CI-CD-PIPELINE-/assets/67210617/0fe6392f-dfe6-4c9e-82d6-f5b4fe955430)
We will not be using image updater instead we ll try to configure shell script for the same.



WHAT WILL WE DO?

<h4>
Build a java apk using maven
SonarQube is used for scanning of images.
we ll try to set up sonar server locally
after that we ll build docker image
then will be pushing this docker image to docker hub
using shell script we ll update the manifests repo.
we ll use argo CD to deploy manifest repo to k8 server.
</h4>
