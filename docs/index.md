# Awesome Kubernetes [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome references collected since 2018.
Microservices architectures rely on DevOps practices, automation, CI/CD (continuous integration and delivery), and API—focused designs.

"I do not believe you can do today's job with yesterday's methods and be in business tomorrow." ([Horatio Nelson Jackson](https://www.history.com/news/the-first-great-american-road-trip))

<center>
[![openshift videos](images/openshift_logo.jpg)](https://www.youtube.com/user/rhopenshift) [![jenkins videos](images/cloudbees_logo.jpg)](https://www.youtube.com/user/CloudBeesTV)
</center>
<!-- youtube player 
<div id="player"></div>
-->
<!--
<img alt="Container with cars" src="images/container_with_cars.png"> 
<head>
<meta property="og:image" content="https://awesome-kubernetes.readthedocs.io/images/container_with_cars.png">
</head>
-->
<center>
[![container with cars](images/container_with_cars.png)](https://www.cncf.io/certification/software-conformance/)
</center>
---

## Table of Contents

1. [Introduction. Openshift VS Kubernetes](introduction.md)
    - [microservices.io](https://microservices.io/)
    - [landscape.cncf.io](https://landscape.cncf.io/)
        - [Certified Kubernetes offerings](https://www.cncf.io/certification/software-conformance/)
    - [CRI-O Lightweight Container Runtime for Kubernetes](https://cri-o.io/)
    - [Open Container Initiative](https://www.opencontainers.org/)
    - [agilemethodology.org](http://agilemethodology.org/)
    - [agilemanifesto.org](http://agilemanifesto.org/)
    - [12factor.net](https://12factor.net/)
    - [roadmap.sh](https://roadmap.sh/) 
    - [API Landscape](https://www.apidays.co/api-landscape)
    - [From Java EE To Cloud Native](javaee-to-cloud-native.md)
    - [Microservices FAQ & Kubernetes Native](faq.md)
2. [Site Reliability Engineering (SRE)](sre.md)
3. [DevOps](devops.md)
    - [Cheat Sheets 🌟](cheatsheets.md)
    - [GitOps 🌟](gitops.md)
    - [Demos & Screencasts. OpenShift, Kubernetes, Jenkins Pipelines with JCasC and more 🌟](demos.md)
4. [NoOps](noops.md)
    - [Serverless Architectures & Frameworks. OpenFaaS, Knative & Kubeless](serverless.md)
5. [FinOps - Cloud Financial Management](finops.md)
6. [TestOps and Continuous Testing](testops.md)
7. [Project Management Methodology](project-management-methodology.md)
    - [Jira](https://www.atlassian.com/software/jira) 
    - [OpenProject](https://www.openproject.org/)
    - [Confluence](https://www.atlassian.com/software/confluence)
    - [Work From Home](workfromhome.md)
    - [Appointment Scheduling](appointment-scheduling.md)
8. [Docker](docker.md)
9. [Kubernetes 🌟](kubernetes.md)
    - [Kubernetes Matrix Table 🌟](matrix-table.md)
    - [Kubernetes Alternatives](kubernetes-alternatives.md)
10.  [OpenShift 🌟](openshift.md)
    - [Red Hat Developer @Youtube](https://www.youtube.com/channel/UC7noUdfWp-ukXUlAsJnSm-Q)
    - [OpenShift Dedicated](https://www.openshift.com/products/dedicated/)
11.  Software Delivery Pipeline
    - [CI/CD - Continuous Integration & Continuous Delivery](cicd.md)
    - [Git & Git Patterns. Trunk Devel, Git Flow & Feature Flags. Merge BOTs 🌟](git.md)
    - [Jenkins & CloudBees 😀](jenkins.md)
        - [Performance testing with Jenkins and JMeter or Gatling](performance-testing-with-jenkins-and-jmeter.md)
    - [OpenShift Pipelines with Jenkins, Tekton and more... 🌟](openshift-pipelines.md)
    - [Jenkins Alternatives for Continuous Integration](jenkins-alternatives.md)
    - Toolchain
        - [Container Runtimes/Managers & Base Images. Podman, Buildah & Skopeo](container-managers.md)
        - [Maven & Gradle](maven-gradle.md)
        - [SonarQube](sonarqube.md)
        - [Nexus & JFrog Artifactory](nexus-jfrog.md)
        - [Web Servers: Apache, HAProxy & Nginx](web-servers.md)
        - [Payara App Server](payara.md) 
        - [Embedded Servlet Containers in SpringBoot: Jetty, Tomcat, Undertow and more](embedded-servlet-containers.md)
        - [Selenium, Appium & Zephyr Jira plugin](selenium-appium-zephyr.md)
        - [Linux & SSH 🌟](linux.md)
        - [YAML processors](yaml-processors.md)
12. [Java Memory Management & Java Performance Optimization](java-and-java-performance-optimization.md)
    - [Java Parameters Matrix Table 🌟](jvm-parameters-matrix-table.md)
13. [Caching Solutions](caching.md)
14. [Monitoring and Performance. Prometheus, Grafana, APMs and more 🌟](monitoring.md)
15. Configuration Management
    - [Ansible](ansible.md)
    - [Liquibase](liquibase.md)
    - [Terraform & Packer](terraform.md)
16. Databases on Kubernetes
    - [Relational Databases and Database DevOps. CrunchyData Postgres Operator 🌟](databases.md)
    - [NoSQL Databases](nosql.md)
17. [Cloud Based Integration & Messaging. Data Processing & Streaming (aka Data Pipeline) 🌟](message-queue.md) 
18. [Service Mesh](servicemesh.md)
    - [Consul](consul.md)
    - [Envoy & xDS protocol](envoyproxy.md)
    - [Istio](istio.md)
    - [Linkerd](linkerd.md)
    - [Maesh](maesh.md)
    - [Traffic Director](trafficdirector.md)
19. [Security and DevSecOps. Container Security](devsecops.md)
    - [Security Policy as Code](securityascode.md)
20. [Cloud Native Storage](storage.md)
21. [APIs with SOAP, REST and gRPC 🌟](api.md)
    - [Swagger code generator for REST APIs](swagger-code-generator-for-rest-apis.md)
    - [API Test Automation with Postman](postman.md)
    - [API Marketplaces. API Management with API Gateways & Developer Portals 🌟](developerportals.md)
22. Development & Frameworks
    - [Angular](angular.md)
    - [Document Object Model (DOM)](dom.md)
    - [Java - Spring Framework](SpringFramework.md)
    - [Java - SpringBoot](SpringBoot.md)
    - [Java - Spring Cloud](SpringCloud.md)
    - [Java - Jakarta EE](https://jakarta.ee/)
    - [Java - Quarkus](quarkus.md)
    - [JavaScript - node.js & npm](javascript.md)
    - [Python - Django & Flask](python.md)
    - [Xamarin](xamarin.md)
23. Dev Environment 
    - [Visual Studio Code 🌟](visual-studio.md)
    - [WSL: Linux Dev Environment on Windows](linux-dev-env.md)
    - [Scaffolding Tools](scaffolding.md)
    - [ChromeDevTools](ChromeDevTools.md)
24. Public Cloud
    - [Public Cloud Solutions](public-cloud-solutions.md)
    - [Edge Computing](edge-computing.md)
    - [Cloud Architecture Diagram Tools](cloud-arch-diagrams.md)
    - [AWS](aws.md)
        - [Amazon Red Hat OpenShift](https://www.openshift.com/products/amazon-openshift/faq)
    - [Google Cloud Platform](GoogleCloudPlatform.md)
        - [OpenShift on Google Cloud](https://cloud.google.com/solutions/partners/openshift-on-gcp)
    - [Microsoft Azure](azure.md)
        - [Microsoft Azure Red Hat OpenShift](https://www.openshift.com/products/azure-openshift)
    - [IBM Cloud](ibm_cloud.md)
        - [Red Hat OpenShift on IBM Cloud](https://www.ibm.com/cloud/openshift)
    - [Oracle Cloud](oraclecloud.md)
    - [Digital Ocean](digitalocean.md)
    - [Cloudflare](cloudflare.md)
25. [E-Learning](elearning.md)
26. [Customer Success Stories 🌟](customer.md)
27. [Subreddits and Newsfeeds](newsfeeds.md)
28. [Other Awesome Lists 🌟](other-awesome-lists.md)

<!-- El fin de la memoria? Documental 
<center>
    
<div class="container">
<iframe src="https://www.youtube.com/embed/tentcmxz3Bo?start=633&end=654" frameborder="0" allowfullscreen class="video"></iframe>	
</div>
</br>
-->
---
<center>
[![automated_ansible](images/automated_ansible.jpg)](https://www.ansible.com/blog/migrating-the-runbook-a-journey-from-legacy-to-devops)
</center>
