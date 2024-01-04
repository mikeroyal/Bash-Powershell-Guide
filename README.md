<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121950775-ecbd5780-cd0e-11eb-81cf-de1e503e0723.png">
  <br />
 Bash/PowerShell Guide
</h1>

 <a href="https://github.com/mikeroyal?tab=followers">
         <img alt="followers" title="Follow me for Updates" src="https://custom-icon-badges.demolab.com/github/followers/mikeroyal?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=person-add&label=Follow&logoColor=white"/></a> 	

![Maintenance](https://img.shields.io/maintenance/yes/2024?style=for-the-badge)
![Last-Commit](https://img.shields.io/github/last-commit/mikeroyal/bash-powershell-guide?style=for-the-badge)

A guide covering Bash/PowerShell scripting languages including the applications and tools that will make you a better and more efficient Bash/PowerShell developer.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121950781-ed55ee00-cd0e-11eb-98e5-9816a77d4eb8.png">
  <br />
</p>

# Table of Contents

1. [Bash/PowerShell Learning Resources](https://github.com/mikeroyal/Bash-PowerShell-Guide#bashpowershell-learning-resources)

2. [Bash/PowerShell Tools, Libraries, and Frameworks](https://github.com/mikeroyal/Bash-PowerShell-Guide#bashpowershell-tools-libraries-and-frameworks)

3. [DevOps Tools Integration](https://github.com/mikeroyal/Bash-PowerShell-Guide#devops-tools-integration)

4. [Kubernetes](https://github.com/mikeroyal/Bash-PowerShell-Guide#kubernetes)

5. [Docker](https://github.com/mikeroyal/Bash-PowerShell-Guide#docker)

6. [Azure Development](https://github.com/mikeroyal/Bash-PowerShell-Guide#azure-development)

7. [AWS Development](https://github.com/mikeroyal/Bash-PowerShell-Guide#aws-development)

8. [Google Cloud Platform Development](https://github.com/mikeroyal/Bash-PowerShell-Guide#google-cloud-platform-development)

9. [VMware Development](https://github.com/mikeroyal/Bash-PowerShell-Guide#vmware-development)

10. [Oracle Cloud Development](https://github.com/mikeroyal/Bash-PowerShell-Guide#oracle-cloud-development)


# Bash/PowerShell Learning Resources
[Back to the Top](https://github.com/mikeroyal/Bash-PowerShell-Guide#table-of-contents)

[Introduction to Bash Shell Scripting by Coursera](https://www.coursera.org/projects/introduction-to-bash-shell-scripting)

[Bash: Shell Script Basics by Pluralsight](https://www.pluralsight.com/courses/bash-shell-scripting)

[Bash/Shell by Codecademy](https://www.codecademy.com/catalog/language/bash)

[Windows Remote Management in Ansible using PowerShell](https://docs.ansible.com/ansible/latest/user_guide/windows_winrm.html)

[Getting Started with PowerShell](https://docs.microsoft.com/en-us/powershell/)

[PowerShell in Azure Cloud Shell](https://aka.ms/cloudshell/powershell-docs)

[Azure Functions using PowerShell](https://docs.microsoft.com/en-us/azure/azure-functions/functions-create-first-function-vs-code?pivots=programming-language-powershell)

[Azure Automation runbooks](https://docs.microsoft.com/en-us/azure/automation/automation-runbook-types)

[Using Visual Studio Code for PowerShell Development](https://docs.microsoft.com/en-us/powershell/scripting/dev-cross-plat/vscode/using-vscode?view=powershell-7)

[Integrated Terminal in Visual Studio Code](https://code.visualstudio.com/docs/editor/integrated-terminal)

[AWS Tools for Windows PowerShell](https://aws.amazon.com/powershell/)

[PowerShell Best Practices and Style Guide](https://poshcode.gitbooks.io/powershell-practice-and-style)

[AWS Command Line Interface and aws-shell Sample for AWS Cloud9](https://docs.aws.amazon.com/cloud9/latest/user-guide/sample-aws-cli.html)

[Configuring Cloud Shell on Google Cloud](https://cloud.google.com/shell/docs/configuring-cloud-shell)

[Google's Shell Style Guide](https://google.github.io/styleguide/shellguide.html)

# Bash/PowerShell Tools, Libraries, and Frameworks
[Back to the Top](https://github.com/mikeroyal/Bash-PowerShell-Guide#table-of-contents)

[Bash](https://www.gnu.org/software/bash/) is the GNU Project's shell(Bourne Again SHell), which is an sh-compatible shell that integrates together useful features from the Korn shell (ksh) and the C shell (csh).

[Zsh](https://www.zsh.org/) is a shell designed for interactive use, although it is also a powerful scripting language. It comes with features of Bash, ksh, and tcsh. 

[Oh My Zsh](https://ohmyz.sh/) is a delightful, open source, community-driven framework for managing your Zsh configuration. It comes bundled with thousands of helpful functions, helpers, plugins, themes, and a few other helpful things.

[PowerShell Core](https://microsoft.com/PowerShell) is a cross-platform (Windows, Linux, and macOS) automation and configuration tool/framework that works well with your existing tools and is optimized for dealing with structured data (JSON, CSV, XML, etc.), REST APIs, and object models. It also includes a command-line shell, an associated scripting language and a framework for processing cmdlets.

[Azure PowerShell](https://docs.microsoft.com/en-us/powershell/azure/overview) is a set of cmdlets for managing Microsoft Azure resources directly from the PowerShell command line.

[Windows Subsystem for Linux (WSL)](https://docs.microsoft.com/en-us/learn/modules/get-started-with-windows-subsystem-for-linux/) is a compatibility layer developed by Microsoft for running Linux binary executables in a Executable/Linkable Format natively on Windows 10 and Windows Server.

[Azure CLI](https://docs.microsoft.com/en-us/cli/azure/?view=azure-cli-latest) is a set of commands used to create and manage Azure resources. The Azure CLI is available across Azure services and is designed to get you working quickly with Azure, with an emphasis on automation.

[Visual Studio Code Remote - WSL extension](https://code.visualstudio.com/docs/remote/wsl) lets you use the Windows Subsystem for Linux (WSL) as your full-time development environment right from VS Code. You can develop in a Linux-based environment, use Linux-specific toolchains and utilities, and run and debug your Linux-based applications all from the comfort of Windows. The extension runs commands and other extensions directly in WSL so you can edit files located in WSL or the mounted Windows filesystem (for example /mnt/c) without worrying about pathing issues, binary compatibility, or other cross-OS challenges.

[Visual Studio Code Remote Development and GitHub Codespaces](https://github.com/Microsoft/vscode-dev-containers) is a  repository of development container definitions for the VS Code Remote - Containers extension and GitHub Codespaces. A development container is a running [Docker](https://www.docker.com/) container with a well-defined tool/runtime stack and its prerequisites. The [VS Code Remote Containers](https://aka.ms/vscode-remote/download/containers) extension allows you to clone a repository or open any folder mounted into (or already inside) a dev container and take advantage of VS Code's full development feature set. [GitHub Codespaces](https://github.com/features/codespaces) both use this same concept to quickly create customized, cloud-based development environments accessible from VS Code or the web.

[Windows Terminal](https://github.com/microsoft/terminal) is a new, modern, feature-rich, productive terminal application for command-line users. It includes many of the features most frequently requested by the Windows command-line community including support for tabs, rich text, globalization, configurability, theming & styling, and more.

[Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/about/) is a hypevisor developed by Microsoft that delivers enterprise-class virtualization for your datacenter and hybrid cloud.

[AWS Shell](https://aws.amazon.com/cli/) is a command-line shell program that provides convenience and productivity features to help both new and advanced users of the AWS Command Line Interface.

[Google Cloud Shell](https://cloud.google.com/shell/) is a free admin machine with browser-based command-line access for managing your infrastructure and applications on Google Cloud Platform.

[VS Code Bash Debug](https://marketplace.visualstudio.com/items?itemName=rogalmic.bash-debug) is a bash debugger GUI frontend based on awesome bashdb scripts (bashdb now included in package).

[VS Code Bash IDE](https://marketplace.visualstudio.com/items?itemName=mads-hartmann.bash-ide-vscode) is a Visual Studio Code extension utilizing the [bash language server](https://github.com/bash-lsp/bash-language-server/blob/master/bash-lsp), that is based on [Tree Sitter](https://github.com/tree-sitter/tree-sitter) and its [grammar for Bash](https://github.com/tree-sitter/tree-sitter-bash) and supports [explainshell](https://explainshell.com/) integration.

# DevOps Tools Integration
[Back to the Top](https://github.com/mikeroyal/Bash-PowerShell-Guide#table-of-contents)

[Open Container Initiative](https://opencontainers.org/about/overview/) is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

[Buildah](https://buildah.io/) is a command line tool to build Open Container Initiative (OCI) images. It can be used with Docker, Podman, Kubernetes.

[Podman](https://podman.io/) is a daemonless, open source, Linux native tool designed to make it easy to find, run, build, share and deploy applications using Open Containers Initiative (OCI) Containers and Container Images. Podman provides a command line interface (CLI) familiar to anyone who has used the Docker Container Engine.

[Containerd](https://containerd.io)is a daemon that manages the complete container lifecycle of its host system, from image transfer and storage to container execution and supervision to low-level storage to network attachments and beyond. It is available for Linux and Windows.

[OKD](https://okd.io/) is a community distribution of Kubernetes optimized for continuous application development and multi-tenant deployment. OKD adds developer and operations-centric tools on top of Kubernetes to enable rapid application development, easy deployment and scaling, and long-term lifecycle maintenance for small and large teams.

[Red Hat OpenShift](https://www.openshift.com/) is an open source container application platform based on the Kubernetes container orchestrator for enterprise app development and deployment in the hybrid cloud Red Hat OpenShift, the open hybrid cloud platform built on Kubernetes.
[OpenShift CLI (oc)](https://docs.openshift.com/container-platform/4.4/cli_reference/openshift_cli/getting-started-cli.html) is a command line interface tool that extends the capabilities of kubectl with [many convenience functions](https://docs.openshift.com/container-platform/4.4/cli_reference/openshift_cli/usage-oc-kubectl.html) that make interacting with both Kubernetes and OpenShift clusters easier.

[Azure Red Hat OpenShift](https://azure.microsoft.com/en-us/services/openshift/) is a flexible, self-service deployment of fully managed OpenShift clusters. Maintain regulatory compliance and focus on your application development, while your master, infrastructure, and application nodes are patched, updated, and monitored by both Microsoft and Red Hat.

[OpenShift Serverless CLI (kn)](https://docs.openshift.com/container-platform/4.4/serverless/serverless-getting-started.html) is a command line interface tool to deploy serverless applications, then you’ll want access and control via the kn command.

[OpenShift Pipelines CLI (tkn)](https://docs.openshift.com/container-platform/4.4/pipelines/understanding-openshift-pipelines.html) is a command line interface tool for using Tekton to provide cloud-native CI/CD functionality within the cluster. The tkn command is used to manage the functionality from the CLI.

[Red Hat CodeReady Containers](https://developers.redhat.com/products/codeready-containers) is an option to host a local, all-in-one OpenShift 4 cluster on your workstation. CodeReady Containers replaces [minishift](https://www.okd.io/minishift/), used to run OpenShift 3 clusters on your workstation, as a quick and easy method of creating test and development clusters.

[Helm CLI](https://docs.openshift.com/container-platform/4.4/cli_reference/helm_cli/getting-started-with-helm-on-openshift-container-platform.html) is a command line interface tool for deploying and managing Kubernetes applications to your clusters.

[OpenShift Hive](https://github.com/openshift/hive) is an operator which runs as a service on top of Kubernetes/OpenShift. The Hive service can be used to provision and perform initial configuration of OpenShift 4 clusters.

[OpenShift Service Mesh](https://www.openshift.com/blog/introducing-openshift-service-mesh-2.0) is a tool that provides a layer on top of OpenShift for securely connecting services in a consistent manner. This provides centralized control, security and observability across your services without having to modify your applications.

[Red Hat® Quay](https://www.openshift.com/products/quay) is a secure, private container registry that builds, analyzes and distributes container images. It provides a high level of automation and customization.

[Kata Operator](https://github.com/openshift/kata-operator) is an operator to perform lifecycle management (install/upgrade/uninstall) of [Kata Runtime](https://katacontainers.io/) on Openshift as well as Kubernetes cluster.

[Ansible](https://www.ansible.com/)is a simple IT automation engine that automates cloud provisioning, configuration management, application deployment, intra-service orchestration, and many other IT needs. It uses a very simple language (YAML, in the form of Ansible Playbooks) that allows you to describe your automation jobs in a way that approaches plain English. Anisble works on Linux (Red Hat EnterPrise Linux(RHEL) and Ubuntu) and Microsoft Windows.

[Ansible cmdb](https://github.com/fboender/ansible-cmdb) is a tool that takes the output of Ansible’s fact gathering and converts it into a static HTML overview page containing system configuration information.

[Ansible Inventory Grapher](https://github.com/willthames/ansible-inventory-grapher) visually displays inventory inheritance hierarchies and at what level a variable is defined in inventory.

[Ansible Playbook Grapher](https://github.com/haidaraM/ansible-playbook-grapher) is a  command line tool to create a graph representing your Ansible playbook tasks and roles.

[Ansible Shell](https://github.com/dominis/ansible-shell) is an interactive shell for Ansible with built-in tab completion for all the modules.

[Ansible Silo](https://github.com/groupon/ansible-silo) is a self-contained Ansible environment by [Docker](https://www.docker.com/).

[Ansigenome](https://github.com/nickjj/ansigenome) is a command line tool designed to help you manage your Ansible roles.

[ARA](https://github.com/openstack/ara) is a records Ansible playbook runs and makes the recorded data available and intuitive for users and systems by integrating with Ansible as a callback plugin.

[GitHub](https://github.com/) provides hosting for software development version control using Git. It offers all of the distributed version control and source code management functionality of Git as well as adding its own features. It provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project.

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces) is an integrated development environment(IDE) on GitHub. That allows developers to develop entirely in the cloud using Visual Studio and Visual Studio Code.

[GitHub Actions](https://docs.github.com/en/actions) will automate, customize, and execute your software development workflows right in your repository with GitHub Actions. You can discover, create, and share actions to perform any job you'd like, including CI/CD, and combine actions in a completely customized workflow.[GitHub Actions for Azure](https://docs.microsoft.com/en-us/azure/developer/github/github-actions) you can create workflows that you can set up in your repository to build, test, package, release and deploy to Azure.Learn more about all other integrations with Azure.

[GitLab](https://about.gitlab.com/) is a web-based DevOps lifecycle tool that provides a Git-repository manager providing wiki, issue-tracking and CI/CD pipeline features, using an open-source license, developed by GitLab Inc.

[Jenkins](https://jenkins.io/) is a free and open source automation server. Jenkins helps to automate the non-human part of the software development process, with continuous integration and facilitating technical aspects of continuous delivery.

[Bitbucket](https://bitbucket.org/) is a web-based version control repository hosting service owned by Atlassian, for source code and development projects that use either Mercurial or Git revision control systems. Bitbucket offers both commercial plans and free accounts. It offers free accounts with an unlimited number of private repositories. Bitbucket integrates with other Atlassian software like Jira, HipChat, Confluence and Bamboo.

[Bamboo](https://www.atlassian.com/software/bamboo) is a continuous integration (CI) server that can be used to automate the release management for a software application, creating a continuous delivery pipeline.

[Codecov](https://codecov.io/) is the leading, dedicated code coverage solution. It provides highly integrated tools to group, merge, archive and compare coverage reports. Whether your team is comparing changes in a pull request or reviewing a single commit, Codecov will improve the code review workflow and quality.

[Drone](https://drone.io/) is a Continuous Delivery system built on container technology. Drone uses a simple YAML configuration file, a superset of docker-compose, to define and execute Pipelines inside Docker containers.

[Travis CI](https://travis-ci.org/) is a hosted continuous integration service used to build and test software projects hosted at GitHub.

[Circle CI](https://circleci.com/) is a continuous integration and continuous delivery platform that helps software teams work smarter, faster.

[Zuul-CI](https://zuul-ci.org/index.html) is a program that drives continuous integration, delivery, and deployment systems with a focus on project gating and interrelated projects. Using the same [Ansible playbooks](https://docs.ansible.com/ansible/latest/user_guide/playbooks.html) to deploy your system and run your tests.

[Artifactory](https://jfrog.com/artifactory/) is a Universal Artifact Repository Manager developed by JFrog. It supports all major packages, enterprise ready security, clustered, HA, Docker registry, multi-site replication and scalable.

[Team City](https://www.jetbrains.com/teamcity/) is a build management and continuous integration server from JetBrains.

[Shippable](https://www.shippable.com/) simplifies DevOps and makes it systematic with an Assembly Line platform that is heterogeneous, flexible, and provides complete visibility across your DevOps workflows.

[Spinnaker](https://www.spinnaker.io/) is an open source, multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence.

[AWS CodeBuild](https://aws.amazon.com/codebuild/) is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy. With CodeBuild, you don't need to provision, manage, and scale your own build servers.

[Selenium](https://www.seleniumhq.org/) is a free (open source) automated testing suite for web applications across different browsers and platforms.

[Cucumber](https://cucumber.io/) is a tool based on Behavior Driven Development (BDD) framework which is used to write acceptance tests for the web application. It allows automation of functional validation in easily readable and understandable format (like plain English) to Business Analysts, Developers, and Testers.

[JUnit](https://junit.org/junit5/) is a unit testing framework for the Java programming language.

[Mocha](https://mochajs.org/) is a JavaScript test framework for Node.js programs, featuring browser support, asynchronous testing, test coverage reports, and use of any assertion library.

[Karma](https://karma-runner.github.io/latest/index.html) is a simple tool that allows you to execute JavaScript code in multiple real browsers.

[Jasmine](https://jasmine.github.io/) is an open source testing framework for JavaScript. It aims to run on any JavaScript-enabled platform, to not intrude on the application nor the IDE, and to have easy-to-read syntax.

[Maven](https://maven.apache.org/) is a build automation tool used primarily for Java projects. Maven can also be used to build and manage projects written in C#, Ruby, Scala, and other languages. The Maven project is hosted by the Apache Software Foundation.

[Gradle](https://gradle.org/) is an open-source build-automation system that builds upon the concepts of Apache Ant and Apache Maven and introduces a Groovy-based domain-specific language instead of the XML form used by Apache Maven for declaring the project configuration.

[KubeInit](https://github.com/kubeinit/kubeinit) provides Ansible playbooks and roles for the deployment and configuration of multiple Kubernetes distributions.

[Salt](https://www.saltstack.com/) is Python-based, open-source software for event-driven IT automation, remote task execution, and configuration management. Supporting the "Infrastructure as Code" approach to data center system and network deployment and management, configuration automation, SecOps orchestration, vulnerability remediation, and hybrid cloud control.

[Terraform](https://www.terraform.io/) is an open-source infrastructure as code software tool created by HashiCorp.It enables users to define and provision a datacenter infrastructure using a high-level configuration language known as Hashicorp Configuration Language (HCL), or optionally JSON.

[Consul](https://www.consul.io) is a service networking solution to connect and secure services across any runtime platform and public or private cloud.

[Packer](https://www.packer.io/) is lightweight, runs on every major operating system, and is highly performant, creating machine images for multiple platforms in parallel. Packer does not replace configuration management like Chef or Puppet. In fact, when building images, Packer is able to use tools like Chef or Puppet to install software onto the image.

[Nomad](https://www.nomadproject.io/) is a highly available, distributed, data-center aware cluster and application scheduler designed to support the modern datacenter with support for long-running services, batch jobs, and much more.

[Vagrant](https://www.vagrantup.com/) is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time and increases production parity.

[Vault](https://www.hashicorp.com/products/vault/) is a tool for securely accessing secrets. A secret is anything that you want to tightly control access to, such as API keys, passwords, certificates, and more. Vault provides a unified interface to any secret, while providing tight access control and recording a detailed audit log.

[CFEngine](https://cfengine.com/) is an open-source configuration management system, written by Mark Burgess.Its primary function is to provide automated configuration and maintenance of large-scale computer systems, including the unified management of servers, desktops, consumer and industrial devices, embedded networked devices, mobile smartphones, and tablet computers.

[Octpus Deploy](https://octopus.com/) is the deployment automation server for your entire team, designed to make it easy to orchestrate releases and deploy applications, whether on-premises or in the cloud.

[AWS CodeDeploy](https://aws.amazon.com/codedeploy/) is a fully managed deployment service that automates software deployments to a variety of compute services such as Amazon EC2, AWS Fargate, AWS Lambda, and your on-premises servers. AWS CodeDeploy makes it easier for you to rapidly release new features, helps you avoid downtime during application deployment, and handles the complexity of updating your applications.

[Kubernetes](https://kubernetes.io/) is an open-source container-orchestration system for automating application deployment, scaling, and management. It was originally designed by Google, and is now maintained by the Cloud Native Computing Foundation.

[Docker](https://www.docker.com/) is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers. Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels. All containers are run by a single operating-system kernel and are thus more lightweight than virtual machines.

[Cloud Hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor) is an open source Virtual Machine Monitor (VMM) that runs on top of [KVM](https://www.kernel.org/doc/Documentation/virtual/kvm/api.txt). The project focuses on exclusively running modern, cloud workloads, on top of a limited set of hardware architectures and platforms. Cloud workloads refers to those that are usually run by customers inside a cloud provider. Cloud Hypervisor is implemented in [Rust](https://www.rust-lang.org/) and is based on the [rust-vmm](https://github.com/rust-vmm) crates.

[VMware vSphere Hypervisor](https://www.vmware.com/products/vsphere-hypervisor.html) is a bare-metal hypervisor that virtualizes servers; allowing you to consolidate your applications while saving time and money managing your IT infrastructure.

[VMware vSphere](https://www.vmware.com/products/vsphere.html) is the industry-leading compute virtualization platform, and your first step to application modernization. It has been rearchitected with native Kubernetes to allow customers to modernize the 70 million+ workloads now running on vSphere.

[VMware Tanzu](https://tanzu.vmware.com/tanzu) is a centralized management platform for consistently operating and securing your Kubernetes infrastructure and modern applications across multiple teams and private/public clouds.

[Rancher](https://rancher.com/) is a complete software stack for teams adopting containers. It addresses the operational and security challenges of managing multiple Kubernetes clusters, while providing DevOps teams with integrated tools for running containerized workloads.

[K3s](https://github.com/rancher/k3s) is a highly available, certified Kubernetes distribution designed for production workloads in unattended, resource-constrained, remote locations or inside IoT appliances.

[Rook](https://rook.io/) is an open source cloud-native storage orchestrator for Kubernetes that turns distributed storage systems into self-managing, self-scaling, self-healing storage services. It automates the tasks of a storage administrator: deployment, bootstrapping, configuration, provisioning, scaling, upgrading, migration, disaster recovery, monitoring, and resource management.

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for deploying containerized applications.

[Anthos](https://cloud.google.com/anthos/docs/concepts/overview) is a modern application management platform that provides a consistent development and operations experience for cloud and on-premises environments.

[AWS ECS](https://aws.amazon.com/ecs/) is a highly scalable, high-performance container orchestration service that supports Docker containers and allows you to easily run and scale containerized applications on AWS. Amazon ECS eliminates the need for you to install and operate your own container orchestration software, manage and scale a cluster of virtual machines, or schedule containers on those virtual machines.

[Apache Mesos](http://mesos.apache.org/) is a cluster manager that provides efficient resource isolation and sharing across distributed applications, or frameworks. It can run Hadoop, Jenkins, Spark, Aurora, and other frameworks on a dynamically shared pool of nodes.

[Apache Spark](https://spark.apache.org/) is a unified analytics engine for big data processing, with built-in modules for streaming, SQL, machine learning and graph processing.

[Apache Hadoop](http://hadoop.apache.org/) is a framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models. It is designed to scale up from single servers to thousands of machines, each offering local computation and storage. Rather than rely on hardware to deliver high-availability, the library itself is designed to detect and handle failures at the application layer, so delivering a highly-available service on top of a cluster of computers, each of which may be prone to failures.

[Rkt](https://coreos.com/rkt/) is a pod-native container engine for Linux. It is composable, secure, and built on standards.

[AWS Lambda](https://aws.amazon.com/lambda/) is an event-driven, serverless computing platform provided by Amazon as a part of the Amazon Web Services. It is a computing service that runs code in response to events and automatically manages the computing resources required by that code.

[Helm](https://helm.sh/) is the Kubernetes Package Manager.

[Kubespray](https://kubespray.io/) is a tool that combines Kubernetes and Ansible to easily install Kubernetes clusters that can be deployed on [AWS](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/aws.md), GCE, [Azure](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/azure.md), [OpenStack](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/openstack.md), [vSphere](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/vsphere.md), [Packet](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/packet.md) (bare metal), Oracle Cloud Infrastructure (Experimental), or Baremetal

[OKD](https://okd.io/) is a community distribution of Kubernetes optimized for continuous application development and multi-tenant deployment. OKD adds developer and operations-centric tools on top of Kubernetes to enable rapid application development, easy deployment and scaling, and long-term lifecycle maintenance for small and large teams.

[Odo](https://odo.dev/) is a fast, iterative, and straightforward CLI tool for developers who write, build, and deploy applications on Kubernetes and OpenShift.

[Knative](https://knative.dev/) is a Kubernetes-based platform to build, deploy, and manage modern serverless workloads. Knative takes care of the operational overhead details of networking, autoscaling (even to zero), and revision tracking.

[Etcd](https://etcd.io/) is a distributed key-value store that provides a reliable way to store data that needs to be accessed by a distributed system or cluster of machines. Etcd is used as the backend for service discovery and stores cluster state and configuration for Kubernetes.

[OpenStack](https://www.openstack.org/) is a free and open-source software platform for cloud computing, mostly deployed as infrastructure-as-a-service that controls large pools of compute, storage, and networking resources throughout a datacenter, managed through a dashboard or via the OpenStack API. OpenStack works with popular enterprise and open source technologies making it ideal for heterogeneous infrastructure.

[Cloud Foundry](https://www.cloudfoundry.org/) is an open source, multi cloud application platform as a service that makes it faster and easier to build, test, deploy and scale applications, providing a choice of clouds, developer frameworks, and application services. It is an open source project and is available through a variety of private cloud distributions and public cloud instances.

[Splunk](https://www.splunk.com/) software is used for searching, monitoring, and analyzing machine-generated big data, via a Web-style interface.

[Prometheus](https://prometheus.io/) is a free software application used for event monitoring and alerting. It records real-time metrics in a time series database (allowing for high dimensionality) built using a HTTP pull model, with flexible queries and real-time alerting.

[Loki](https://grafana.com/oss/loki/) is a horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus. It is designed to be very cost effective and easy to operate. It does not index the contents of the logs, but rather a set of labels for each log stream.

[Thanos](https://thanos.io/) is a set of components that can be composed into a highly available metric system with unlimited storage capacity, which can be added seamlessly on top of existing Prometheus deployments.

[Container Storage Interface (CSI)](https://www.architecting.it/blog/container-storage-interface/) is an API that lets container orchestration platforms like Kubernetes seamlessly communicate with stored data via a plug-in.

[OpenEBS](https://openebs.io/) is a Kubernetes-based tool to create stateful applications using Container Attached Storage.

[ElasticSearch](https://www.elastic.co/) is a search engine based on the Lucene library. It provides a distributed, multitenant-capable full-text search engine with an HTTP web interface and schema-free JSON documents. Elasticsearch is developed in Java.

[Logstash](https://www.elastic.co/products/logstash) is a tool for managing events and logs. When used generically, the term encompasses a larger system of log collection, processing, storage and searching activities.

[Kibana](https://www.elastic.co/products/kibana) is an open source data visualization plugin for Elasticsearch. It provides visualization capabilities on top of the content indexed on an Elasticsearch cluster. Users can create bar, line and scatter plots, or pie charts and maps on top of large volumes of data.

[New Relic](https://newrelic.com/) is a SaaS-based monitoring tool that fully supports the way DevOps teams work in the modern enterprise by streamlining your workflows with today's collaboration software and orchestration tools like Puppet, Chef, and Ansible.

[Nagios](https://www.nagios.org/) is a free and open source computer-software application that monitors systems, networks and infrastructure. Nagios offers monitoring and alerting services for servers, switches, applications and services. It alerts users when things go wrong and alerts them a second time when the problem has been resolved.

[SonarQube](https://www.sonarqube.org/) is an open-source platform developed by SonarSource for continuous inspection of code quality to perform automatic reviews with static analysis of code to detect bugs, code smells, and security vulnerabilities on 20+ programming languages.

[Genie](https://netflix.github.io/genie) is a federated job orchestration engine developed by Netflix. Genie provides REST APIs to run a variety of big data jobs like Hadoop, Pig, Hive, Spark, Presto, Sqoop and more. It also provides APIs for managing the metadata of many distributed processing clusters and the commands and applications which run on them.

[Inviso](https://github.com/Netflix/inviso) is a lightweight tool that provides the ability to search for Hadoop jobs, visualize the performance, and view cluster utilization.

[Fenzo](https://github.com/Netflix/Fenzo) is a scheduler Java library for Apache Mesos frameworks that supports plugins for scheduling optimizations and facilitates cluster autoscaling.

[Dynomite](https://github.com/Netflix/dynomite) is a thin, distributed dynamo layer for different storage engines and protocols, which includes [Redis](http://redis.io/) and [Memcached](http://www.memcached.org/). Dynomite supports multi-datacenter replication and is designed for High Availability(HA).

[Dyno](https://github.com/Netflix/dynomite) is a tool that is used to scale a Java client application utilizing [Dynomite](https://github.com/Netflix/dynomite).

[Raigad](https://github.com/Netflix/Raigad) is a process/tool that runs alongside Elasticsearch to automate backup/recovery, Deployments and Centralized Configuration management.

[Priam](https://github.com/Netflix/Priam) is a process/tool that runs alongside Apache Cassandra to automate backup/recovery, Deployments and Centralized Configuration management.

[Chaos Monkey](https://github.com/Netflix/chaosmonkey) is a resiliency tool  used to randomly terminates virtual machine instances and containers that run inside of your production environment. Chaos Monkey should work with any backend that [Spinnaker](http://www.spinnaker.io/) supports (AWS, Google Compute Engine, Microsoft Azure, Kubernetes, and Cloud Foundry).

[Falcor](https://netflix.github.io/falcor/) is a JavaScript library for efficient data fetching. Falcor lets you represent all your remote data sources as a single domain model via a virtual JSON graph, whether in memory on the client or over the network on the server.

[Restify](https://github.com/restify/node-restify) is a framework, utilizing [connect](https://github.com/senchalabs/connect) style middleware for building REST APIs.

[Traefik](https://traefik.io/traefik/) is an open source Edge Router that makes publishing your services a fun and easy experience. It receives requests on behalf of your system and finds out which components are responsible for handling them. What sets Traefik apart, besides its many features, is that it automatically discovers the right configuration for your services.

[Jira](https://www.atlassian.com/software/jira) is a proprietary issue tracking product developed by Atlassian that allows bug tracking and agile project management.

[Pivotal Tracker](https://www.pivotaltracker.com/) is the agile project management tool of choice for developers around the world for real-time collaboration around a shared, prioritized backlog.

# Kubernetes

[Back to the Top](https://github.com/mikeroyal/Bash-PowerShell-Guide#table-of-contents)

[Kubernetes (K8s)](https://kubernetes.io/) is an open-source system for automating deployment, scaling, and management of containerized applications.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/105645195-db9ea780-5e4e-11eb-8357-fb38b2f06d74.png">

**Building Highly-Availability(HA) Clusters with kubeadm. Source: [Kubernetes.io](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/high-availability/), 2020**
</p>

## Kubernetes Tools and Frameworks

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for running containerized applications.

[Azure Kubernetes Service (AKS)](https://azure.microsoft.com/en-us/services/kubernetes-service/) is serverless Kubernetes, with a integrated continuous integration and continuous delivery (CI/CD) experience, and enterprise-grade security and governance. Unite your development and operations teams on a single platform to rapidly build, deliver, and scale applications with confidence.

[Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html) is a tool that runs Kubernetes control plane instances across multiple Availability Zones to ensure high availability.

[AWS Controllers for Kubernetes (ACK)](https://aws.amazon.com/blogs/containers/aws-controllers-for-kubernetes-ack/) is a new tool that lets you directly manage AWS services from Kubernetes. ACK makes it simple to build scalable and highly-available Kubernetes applications that utilize AWS services.

[Container Engine for Kubernetes (OKE)](https://www.oracle.com/cloud-native/container-engine-kubernetes/) is an Oracle-managed container orchestration service that can reduce the time and cost to build modern cloud native applications. Unlike most other vendors, Oracle Cloud Infrastructure provides Container Engine for Kubernetes as a free service that runs on higher-performance, lower-cost compute.

[Anthos](https://cloud.google.com/anthos/docs/concepts/overview) is a modern application management platform that provides a consistent development and operations experience for cloud and on-premises environments.

[Red Hat Openshift](https://www.openshift.com/) is a fully managed Kubernetes platform that provides a foundation for on-premises, hybrid, and multicloud deployments.

[OKD](https://okd.io/) is a community distribution of Kubernetes optimized for continuous application development and multi-tenant deployment. OKD adds developer and operations-centric tools on top of Kubernetes to enable rapid application development, easy deployment and scaling, and long-term lifecycle maintenance for small and large teams.

[Odo](https://odo.dev/) is a fast, iterative, and straightforward CLI tool for developers who write, build, and deploy applications on Kubernetes and OpenShift.

[Kata Operator](https://github.com/openshift/kata-operator) is an operator to perform lifecycle management (install/upgrade/uninstall) of [Kata Runtime](https://katacontainers.io/) on Openshift as well as Kubernetes cluster.

[Thanos](https://thanos.io/) is a set of components that can be composed into a highly available metric system with unlimited storage capacity, which can be added seamlessly on top of existing Prometheus deployments.

[OpenShift Hive](https://github.com/openshift/hive) is an operator which runs as a service on top of Kubernetes/OpenShift. The Hive service can be used to provision and perform initial configuration of OpenShift 4 clusters.

[Rook](https://rook.io/) is a tool that turns distributed storage systems into self-managing, self-scaling, self-healing storage services. It automates the tasks of a storage administrator: deployment, bootstrapping, configuration, provisioning, scaling, upgrading, migration, disaster recovery, monitoring, and resource management.

[VMware Tanzu](https://tanzu.vmware.com/tanzu) is a centralized management platform for consistently operating and securing your Kubernetes infrastructure and modern applications across multiple teams and private/public clouds.

[Kubespray](https://kubespray.io/) is a tool that combines Kubernetes and Ansible to easily install Kubernetes clusters that can be deployed on [AWS](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/aws.md), GCE, [Azure](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/azure.md), [OpenStack](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/openstack.md), [vSphere](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/vsphere.md), [Packet](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/packet.md) (bare metal), Oracle Cloud Infrastructure (Experimental), or Baremetal.

[KubeInit](https://github.com/kubeinit/kubeinit) provides Ansible playbooks and roles for the deployment and configuration of multiple Kubernetes distributions.

[Rancher](https://rancher.com/) is a complete software stack for teams adopting containers. It addresses the operational and security challenges of managing multiple Kubernetes clusters, while providing DevOps teams with integrated tools for running containerized workloads.

[K3s](https://github.com/rancher/k3s) is a highly available, certified Kubernetes distribution designed for production workloads in unattended, resource-constrained, remote locations or inside IoT appliances.

[Helm](https://helm.sh/) is a Kubernetes Package Manager tool that makes it easier to install and manage Kubernetes applications.

[Knative](https://knative.dev/) is a Kubernetes-based platform to build, deploy, and manage modern serverless workloads. Knative takes care of the operational overhead details of networking, autoscaling (even to zero), and revision tracking.

[KubeFlow](https://www.kubeflow.org/) is a tool dedicated to making deployments of machine learning (ML) workflows on Kubernetes simple, portable and scalable.

[Etcd](https://etcd.io/) is a distributed key-value store that provides a reliable way to store data that needs to be accessed by a distributed system or cluster of machines. Etcd is used as the backend for service discovery and stores cluster state and configuration for Kubernetes.

[OpenEBS](https://openebs.io/) is a Kubernetes-based tool to create stateful applications using Container Attached Storage.

[Container Storage Interface (CSI)](https://www.architecting.it/blog/container-storage-interface/) is an API that lets container orchestration platforms like Kubernetes seamlessly communicate with stored data via a plug-in.

[MicroK8s](https://microk8s.io/) is a tool that delivers the full Kubernetes experience. In a Fully containerized deployment with compressed over-the-air updates for ultra-reliable operations. It is supported on Linux, Windows, and MacOS.

[Charmed Kubernetes](https://ubuntu.com/kubernetes/features) is a well integrated, turn-key, conformant Kubernetes platform, optimized for your multi-cloud environments developed by Canonical.

[Grafana Kubernetes App](https://grafana.com/grafana/plugins/grafana-kubernetes-app) is a toll that allows you to monitor your Kubernetes cluster's performance. It includes 4 dashboards, Cluster, Node, Pod/Container and Deployment. It allows for the automatic deployment of the required Prometheus exporters and a default scrape config to use with your in cluster Prometheus deployment.

[KubeEdge](https://kubeedge.io/en/) is an open source system for extending native containerized application orchestration capabilities to hosts at Edge.It is built upon kubernetes and provides fundamental infrastructure support for network, app. deployment and metadata synchronization between cloud and edge.

[Lens](https://k8slens.dev/)  is the most powerful IDE for people who need to deal with Kubernetes clusters on a daily basis. It has support for MacOS, Windows and Linux operating systems.

[kind](https://kind.sigs.k8s.io/) is a tool for running local Kubernetes clusters using Docker container “nodes”. It was primarily designed for testing Kubernetes itself, but may be used for local development or CI.

[Flux CD](https://fluxcd.io/) is a tool that automatically ensures that the state of your Kubernetes cluster matches the configuration you've supplied in Git. It uses an operator in the cluster to trigger deployments inside Kubernetes, which means that you don't need a separate continuous delivery tool.

## Kubernetes Learning Resources

[Getting Kubernetes Certifications](https://training.linuxfoundation.org/certification/catalog/?_sft_technology=kubernetes)

[Getting started with Kubernetes on AWS](https://aws.amazon.com/kubernetes/)

[Kubernetes on Microsoft Azure](https://azure.microsoft.com/en-us/topic/what-is-kubernetes/)

[Intro to Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/kubernetes-dashboard)

[Getting started with Google Cloud](https://cloud.google.com/learn/what-is-kubernetes)

[Getting started with Kubernetes on Red Hat](https://www.redhat.com/en/topics/containers/what-is-kubernetes)

[Getting started with Kubernetes on IBM](https://www.ibm.com/cloud/learn/kubernetes)

[YAML basics in Kubernetes](https://developer.ibm.com/technologies/containers/tutorials/yaml-basics-and-usage-in-kubernetes/)

[Elastic Cloud on Kubernetes](https://www.elastic.co/elastic-cloud-kubernetes)

[Docker and Kubernetes](https://www.docker.com/products/kubernetes)

[Deploy a model to an Azure Kubernetes Service cluster](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-deploy-azure-kubernetes-service?tabs=python)

[Simplify Machine Learning Inference on Kubernetes with Amazon SageMaker Operators](https://aws.amazon.com/blogs/machine-learning/simplify-machine-learning-inference-on-kubernetes-with-amazon-sagemaker-operators/)

[Running Apache Spark on Kubernetes](http://spark.apache.org/docs/latest/running-on-kubernetes.html)

[Kubernetes Across VMware vRealize Automation](https://blogs.vmware.com/management/2019/06/kubernetes-across-vmware-cloud-automation-services.html)

[VMware Tanzu Kubernetes Grid](https://tanzu.vmware.com/kubernetes-grid)

[All the Ways VMware Tanzu Works with AWS](https://tanzu.vmware.com/content/blog/all-the-ways-vmware-tanzutm-works-with-aws)

[VMware Tanzu Education](https://tanzu.vmware.com/education)

[Using Ansible in a Cloud-Native Kubernetes Environment](https://www.ansible.com/blog/how-useful-is-ansible-in-a-cloud-native-kubernetes-environment)

[Managing Kubernetes (K8s) objects with Ansible](https://docs.ansible.com/ansible/latest/collections/community/kubernetes/k8s_module.html)

[Setting up a Kubernetes cluster using Vagrant and Ansible](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/)

[Running MongoDB with Kubernetes](https://www.mongodb.com/kubernetes)

[Kubernetes Fluentd](https://docs.fluentd.org/v/0.12/articles/kubernetes-fluentd)

[Understanding the new GitLab Kubernetes Agent](https://about.gitlab.com/blog/2020/09/22/introducing-the-gitlab-kubernetes-agent/)

[Kubernetes Contributors](https://www.kubernetes.dev/)

[KubeAcademy from VMware](https://kube.academy/)

# Docker
[Back to the Top](https://github.com/mikeroyal/Bash-PowerShell-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113521410-2e32c900-954e-11eb-8311-065fa0099546.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113521413-2ffc8c80-954e-11eb-9d19-b9c996bc524b.png">
  <br />
</p>

**Container Architecture. Source: [Containerd.io](https://containerd.io)**

## Docker Learning Resources

[Docker Training Program](https://www.docker.com/dockercon/training)

[Docker Certified Associate (DCA) certification](https://training.mirantis.com/dca-certification-exam/)

[Docker Documentation | Docker Documentation](https://docs.docker.com/)

[The Docker Workshop](https://courses.packtpub.com/courses/docker)

[Docker Courses on Udemy](https://www.udemy.com/topic/docker/)

[Docker Courses on Coursera](https://www.coursera.org/courses?query=docker)

[Docker Courses on edX](https://www.edx.org/learn/docker)

[Docker Courses on Linkedin Learning](https://www.linkedin.com/learning/topics/docker)

## Docker Tools

[Docker](https://www.docker.com/) is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly working in collaboration with cloud, Linux, and Windows vendors, including Microsoft.

[Docker Enterprise](https://www.mirantis.com/software/docker/docker-enterprise/) is a subscription including software, supported and certified container platform for CentOS, Red Hat Enterprise Linux (RHEL), Ubuntu, SUSE Linux Enterprise Server (SLES), Oracle Linux, and Windows Server 2016, as well as for cloud providers AWS and Azure. In [November 2019 Docker's Enterprise Platform business was acquired by Mirantis](https://www.mirantis.com/company/press-center/company-news/mirantis-acquires-docker-enterprise/).

[Docker Desktop](https://www.docker.com/products/docker-desktop) is an application for MacOS and Windows machines for the building and sharing of containerized applications and microservices. Docker Desktop delivers the speed, choice and security you need for designing and delivering containerized applications on your desktop. Docker Desktop includes Docker App, developer tools, Kubernetes and version synchronization to production Docker Engines.

[Docker Hub](https://hub.docker.com/) is the world's largest library and community for container images Browse over 100,000 container images from software vendors, open-source projects, and the community.

[Docker Compose](https://docs.docker.com/compose/) is a tool that was developed to help define and share multi-container applications. With Docker Compose, you can create a YAML file to define the services and with a single command, can spin everything up or tear it all down.

[Docker Swarm](https://docs.docker.com/engine/swarm/) is a Docker-native clustering system swarm is a simple tool which controls a cluster of Docker hosts and exposes it as a single "virtual" host.

[Dockerfile](https://docs.docker.com/engine/reference/builder/) is a text document that contains all the commands a user could call on the command line to assemble an image. Using docker build users can create an automated build that executes several command-line instructions in succession.

[Docker Containers](https://www.docker.com/resources/what-container) is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another.

[Docker Engine](https://www.docker.com/products/container-runtime) is a container runtime that runs on various Linux (CentOS, Debian, Fedora, Oracle Linux, RHEL, SUSE, and Ubuntu) and Windows Server operating systems. Docker creates simple tooling and a universal packaging approach that bundles up all application dependencies inside a container which is then run on Docker Engine.

[Docker Images](https://docs.docker.com/engine/reference/commandline/images/) is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings. Images have intermediate layers that increase reusability, decrease disk usage, and speed up docker build by allowing each step to be cached. These intermediate layers are not shown by default. The SIZE is the cumulative space taken up by the image and all its parent images.

[Docker Network](https://docs.docker.com/engine/reference/commandline/network/) is a that displays detailed information on one or more networks.

[Docker Daemon](https://docs.docker.com/config/daemon/) is a service started by a system utility, not manually by a user. This makes it easier to automatically start Docker when the machine reboots. The command to start Docker depends on your operating system. Currently, it only runs on Linux because it depends on a number of Linux kernel features, but there are a few ways to run Docker on MacOS and Windows as well by configuring the operating system utilities.

[Docker Storage](https://docs.docker.com/storage/storagedriver/select-storage-driver/) is a driver controls how images and containers are stored and managed on your Docker host.

[Kitematic](https://kitematic.com/) is a simple application for managing Docker containers on Mac, Linux and Windows letting you control your app containers from a graphical user interface (GUI).

[Open Container Initiative](https://opencontainers.org/about/overview/) is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

[Buildah](https://buildah.io/) is a command line tool to build Open Container Initiative (OCI) images. It can be used with Docker, Podman, Kubernetes.

[Podman](https://podman.io/) is a daemonless, open source, Linux native tool designed to make it easy to find, run, build, share and deploy applications using Open Containers Initiative (OCI) Containers and Container Images. Podman provides a command line interface (CLI) familiar to anyone who has used the Docker Container Engine.

[Containerd](https://containerd.io) is a daemon that manages the complete container lifecycle of its host system, from image transfer and storage to container execution and supervision to low-level storage to network attachments and beyond. It is available for Linux and Windows.

# Azure Development
[Back to the Top](https://github.com/mikeroyal/Bash-PowerShell-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/143783606-58f4f708-dfe3-40f5-b9e3-c737479dc320.png">
  <br />
</p>

**[Start building with PowerShell on Azure](https://docs.microsoft.com/en-us/powershell/azure/install-az-ps)**

**[Azure PowerShell Documentation](https://docs.microsoft.com/en-us/powershell/azure/)**

<img src="https://user-images.githubusercontent.com/45159366/114321924-6009d980-9ad2-11eb-99f4-71868b48e28d.png">

**Microsoft Azure Architecture. Source: [Azure](https://docs.microsoft.com/en-us/azure/architecture/)**


## Azure Learning Resources

[Microsoft Azure](https://azure.microsoft.com/en-us/) is a cloud computing service created by Microsoft for building, testing, deploying, and managing applications and services through Microsoft-managed data centers.

[Get started with Azure](https://azure.microsoft.com/en-us/get-started/)

[Azure Demo and Q&A](https://azure.microsoft.com/en-us/get-started/webinar/)

[Microsoft Azure Training & Certification Courses](https://www.microsoft.com/en-us/learning/azure-training-certification.aspx)

[Azure on Microsoft Learn](https://docs.microsoft.com/en-us/learn/azure/)

[Microsoft Certified: Azure Fundamentals](https://docs.microsoft.com/en-us/learn/certifications/azure-fundamentals/)

[Microsoft Certified: DevOps Engineer Expert Cert.](https://docs.microsoft.com/en-us/learn/certifications/devops-engineer)

[Introduction to Azure DevOps from A Cloud Guru](https://acloud.guru/learn/introduction-to-azure-devops)

[Microsoft Certified: Azure IoT Developer Specialty](https://docs.microsoft.com/en-us/learn/certifications/azure-iot-developer-specialty)

[Microsoft Certified: Azure Security Engineer Associate](https://docs.microsoft.com/en-us/learn/certifications/azure-security-engineer)

[Microsoft Azure Certification Training Courses on Udemy](https://www.udemy.com/topic/microsoft-azure/)

[Free Microsoft Azure Courses & Tutorials on Udemy](https://www.udemy.com/topic/microsoft-azure/free/)

[Microsoft Azure Certification Training Courses on Coursera](https://www.coursera.org/learn/cloud-azure-intro)

[Microsoft Azure Certification Training Courses on edX](https://www.edx.org/learn/azure)

## Azure Tools

[Microsoft Azure Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/)

[Azure command-line interface (Azure CLI)](https://docs.microsoft.com/en-us/cli/azure/) is a command line that provides a set of commands used to create and manage Azure resources.

[Visual Studio Code](https://code.visualstudio.com/docs/azure/extensions) is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity).

[Azure Functions](https://azure.microsoft.com/en-us/services/functions/) is a solution for easily running small pieces of code, or "functions," in the cloud. You can write just the code you need for the problem at hand, without worrying about a whole application or the infrastructure to run it.

[Azure DevOps](https://azure.microsoft.com/en-us/services/devops/?nav=min) is a set of services for teams to share code, track work, and ship software; CLIs Build, deploy, diagnose, and manage multi-platform, scalable apps and services; Azure Pipelines Continuously build, test, and deploy to any platform and cloud; Azure Lab Services Set up labs for classrooms, trials, development and testing, and other scenarios.

[Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/what-is-azure-data-studio?view=sql-server-ver15) is a cross-platform database tool for data professionals using on-premises and cloud data platforms on Windows, macOS, and Linux. It offers a modern editor experience with IntelliSense, code snippets, source control integration, and an integrated terminal. It's engineered with the data platform user in mind, with built-in charting of query result sets and customizable dashboards.

[Azure Active Directory (Azure AD)](https://azure.microsoft.com/en-us/services/active-directory/) is Microsoft's cloud-based identity and access management service, which helps your employees sign in and access resources in: External resources, such as Microsoft 365, the Azure portal, and thousands of other SaaS applications.

[Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/overview) is a client tool that helps you maximize the availability and performance of your applications and services. It delivers a comprehensive solution for collecting, analyzing, and acting on telemetry from your cloud and on-premises environments.

[Azure Cognitive Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/) is a set of cloud-based services with REST APIs and client library SDKs available to help you build cognitive intelligence into your applications. You can add cognitive features to your applications without having artificial intelligence (AI) or data science skills. All it takes is an API call to embed the ability to see, hear, speak, search, understand, and accelerate decision-making into your apps.

[Azure Data Lake Storage](https://azure.microsoft.com/en-us/solutions/data-lake/) is a storage repository that holds a large amount of data in its native, raw format. Data lake stores are optimized for scaling to terabytes and petabytes of data. The data typically comes from multiple heterogeneous sources, and may be structured, semi-structured, or unstructured.

[Azure Service Fabric](https://azure.microsoft.com/en-us/services/service-fabric/) is a distributed systems platform that makes it easy to package, deploy, and manage scalable and reliable microservices and containers. Service Fabric also addresses the significant challenges in developing and managing cloud native applications. It powers core Azure infrastructure as well as other Microsoft services such as Skype for Business, Intune, Azure Event Hubs, Azure Data Factory, Azure Cosmos DB, Azure SQL Database, Dynamics 365, and Cortana.

[Microsoft Azure Storage Emulator](https://docs.microsoft.com/en-us/azure/storage/common/storage-use-emulator) is a tool that emulates the Azure Blob, Queue, and Table services for local development purposes. You can test your application against the storage services locally without creating an Azure subscription or incurring any costs.

[Azure Cosmos DB Emulator](https://docs.microsoft.com/en-us/azure/cosmos-db/local-emulator?tabs=cli,ssl-netstd21) is a tool that provides a local environment that emulates the Azure Cosmos DB service for development purposes. Using the Azure Cosmos DB Emulator, you can develop and test your application locally, without creating an Azure subscription or incurring any costs.

[Microsoft Azure Storage Explorer](https://www.storageexplorer.com/) is a standalone app that makes it easy to work with Azure Storage data on Windows, macOS, and Linux.

[Azure BatchExplorer](https://github.com/Azure/BatchExplorer#batchexplorer) is a  client tool to help create, debug and monitor Azure Batch Applications.

[Azure Key Vault Explorer](https://github.com/microsoft/AzureKeyVaultExplorer/blob/master/README.md)  is a  client tool to help be productive when working with secrets.

[Azurite](https://github.com/Azure/Azurite/blob/master/README.md) is an open source Azure Storage API compatible server (emulator). Based on Node.js, Azurite provides cross platform experiences for customers wanting to try Azure Storage easily in a local environment. Azurite simulates most of the commands supported by Azure Storage with minimal dependencies.

[Azure Cloud Shell](https://shell.azure.com/) is an interactive, authenticated, browser-accessible shell for managing Azure resources. It provides the flexibility of choosing the shell experience that best suits the way you work, either Bash or PowerShell.

[Azure Lab Services](https://azure.microsoft.com/en-us/services/lab-services/) is an easy to set up and provide on-demand access to preconfigured virtual machines (VMs) to support your scenarios. Teach a class, train professionals, run a hackathon or a hands-on lab, and more.

[Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines/) is a cloud-hosted pipelines for Linux, macOS, and Windows. Where you can build web, desktop and mobile applications. Deploy to any cloud or on‑premises.

[Azure Bots Service](https://azure.microsoft.com/en-us/services/bot-services/) is a service that develops intelligent, enterprise-grade bots that help you enrich the customer experience while maintaining control of your data. Build any type of bot—from a Q&A bot to your own branded virtual assistant—to quickly connect your users to the answers they need.

[Azure PlayFab](https://azure.microsoft.com/en-us/services/playfab/) is a service that enables developers to use the intelligent cloud to build and operate games, analyze gaming data and improve overall gaming experiences. Along with the Microsoft Game Stack that includes platforms, tools, and services like Visual Studio, DirectX, Havok, and Xbox.

[Azure Databricks](https://azure.microsoft.com/en-us/services/databricks/) is a tool that makes it fast, easy, and collaborative Apache Spark-based analytics platform. Azure Databricks, set up your Apache Spark™ environment in minutes, autoscale, and collaborate on shared projects in an interactive workspace. Azure Databricks supports Python, Scala, R, Java, and SQL, as well as data science frameworks and libraries including TensorFlow, PyTorch, and scikit-learn.

[Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/) is an enterprise-grade machine learning service to build and deploy models faster. It empowers data scientists and developers with a wide range of productive experiences to build, train, and deploy machine learning models and foster team collaboration. Accelerate time to market with industry-leading MLOps—DevOps for machine learning. Innovate on a secure, trusted platform, designed for responsible machine learning.

[Azure Open Datasets](https://azure.microsoft.com/en-us/services/open-datasets/) is a tool that curates open data made easily accessible on Azure.

[Azure Percept](https://azure.microsoft.com/en-us/services/azure-percept/) is a comprehensive, easy-to-use platform with added security for creating edge AI solutions.

[Azure Data Share](https://azure.microsoft.com/en-us/services/data-share/) is a simple and safe service for sharing big data. It  provides full visibility into your data sharing relationships with a user-friendly interface. Share data in just a few clicks, or build your own application using the REST API.

[Azure Data Factory](https://azure.microsoft.com/en-us/services/data-factory/) is a fully managed, serverless data integration solution for ingesting, preparing, and transforming all your data at scale.

[Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/) is a limitless analytics service that brings together data integration, enterprise data warehousing, and big data analytics. It gives you the freedom to query data on your terms, using either serverless or dedicated resources at scale.

[Azure HDInsight](https://azure.microsoft.com/en-us/services/hdinsight/) is an enterprise-ready, managed cluster service for open-source analytics.It let's you run popular open-source frameworks including Apache Hadoop, Spark, Hive, Kafka, and more.

[Azure Blockchain Service](https://azure.microsoft.com/en-us/services/blockchain-service/) is a service that simplifies the formation, management, and governance of consortium blockchain networks so you can focus on business logic and app development.

[Azure Logic Apps](https://azure.microsoft.com/en-us/services/logic-apps/) is a leading integration platform as a service (iPaaS) enables key enterprise scenarios for developers. Built on a containerized runtime that increases scale and portability while automating business-critical workflows anywhere.

[Azure Quantum](https://azure.microsoft.com/en-us/services/quantum/) is an innovative quantum computing and optimization solutions converge in a single marketplace quantum service.

[Azure VMware Solution](https://azure.microsoft.com/en-us/services/azure-vmware/) is a service that seamlessly moves VMware-based workloads from your datacenter to Azure and integrate your VMware environment with Azure. Keep managing your existing environments with the same VMware tools you already know while you modernize your applications with Azure native services.

[Azure Spring Cloud](https://azure.microsoft.com/en-us/services/spring-cloud/) is a fully managed Spring Cloud service, jointly built and operated with VMware.

[Azure CycleCloud](https://azure.microsoft.com/en-us/features/azure-cyclecloud/) is a serviece that creates, manages, operates, and optimizes HPC and big compute clusters of any scale.

[Azure API Apps](https://azure.microsoft.com/en-us/services/app-service/api/) is a service that quickly builds and consumes APIs in the cloud using the language of your choice.

[Azure Web Apps](https://azure.microsoft.com/en-us/services/app-service/web/) is an easy way to create and deploy mission-critical web applications that scale with your business.

[Windows Virtual Desktop](https://azure.microsoft.com/en-us/services/virtual-desktop/) is a service that enables a secure, remote desktop experience from anywhere.

[VMware Horizon Cloud on Microsoft Azure](https://azure.microsoft.com/en-us/services/virtual-desktop/vmware-horizon-cloud/) is a desktop virtualization service available in Azure Marketplace. Simplify your delivery of on-premises and cloud virtual desktops and applications by connecting your instance of Azure to VMware.

[Citrix Virtual Apps and Desktops for Azure](https://azure.microsoft.com/en-us/services/virtual-desktop/citrix-virtual-apps-desktops-for-azure/) is a desktop and app virtualization service available through Azure Marketplace or agreements with Citrix. Use familiar tools to manage on-premises Citrix deployments alongside Windows Virtual Desktop on Azure, supporting cloud modernization while maximizing your existing investment.

[Azure Container Registry](https://azure.microsoft.com/en-us/services/container-registry/) is a registry of Docker and Open Container Initiative (OCI) images, with support for all OCI artifacts.

[Azure Web App for Containers](https://azure.microsoft.com/en-us/services/app-service/containers/) is an easily deploy and run containerized applications on Windows and Linux.

[Azure SQL Edge](https://azure.microsoft.com/en-us/services/sql-edge/) is a service that makes a small-footprint, edge-optimized SQL database engine with built-in AI. This productivity tool for edge computing combines new capabilities such as data streaming and time series with in-database machine learning and graph features. Develop your application once and deploy anywhere across the edge, your datacenter, and Azure.

[Azure Arc](https://azure.microsoft.com/en-us/services/azure-arc/) is a service that offers simplified management, faster app development, and consistent Azure services. Standardize visibility, operations, and compliance across a wide range of resources and locations by extending the Azure control plane. Build cloud-native apps anywhere, at scale.

[Azure Artifacts](https://azure.microsoft.com/en-us/services/devops/artifacts/) is a services that provides fully integrated package management to your continuous integration/continuous delivery (CI/CD) pipelines with a single click. Create and share Maven, npm, NuGet, and Python package feeds from public and private sources with teams of any size.

[Azure Boards](https://azure.microsoft.com/en-us/services/devops/boards/) is a service that helps you plan, track, and discuss work across your teams. It let's you track work with Kanban boards, backlogs, team dashboards, and custom reporting.

[Azure ExpressRoute](https://azure.microsoft.com/en-us/services/expressroute/) is a tool that helps you experience a faster, private connection to Azure.

[Azure Sentinel](https://azure.microsoft.com/en-us/services/azure-sentinel/) is your birds-eye view across the enterprise. It uses the cloud and large-scale intelligence from decades of Microsoft security experience to work. Making your threat detection and response smarter and faster with artificial intelligence (AI).

[Azure Stack](https://azure.microsoft.com/en-us/overview/azure-stack/) is a service that builds and runs hybrid apps across datacenters, edge locations, remote offices, and the cloud.

[Azure Stack HCI](https://azure.microsoft.com/en-us/products/azure-stack/hci/) is a new hyperconverged infrastructure (HCI) operating system delivered as an Azure service that provides the latest security, performance, and feature updates. Deploy and run Windows and Linux virtual machines (VMs) in your datacenter or at the edge using your existing tools, processes, and skill sets.

[Azure Sphere](https://azure.microsoft.com/en-us/services/azure-sphere/) is a comprehensive IoT security solution including hardware (crossover microcontroller), OS, and cloud components for IoT device security to actively protect your devices, your business, and your customers.

[Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/) is a service that provides a cloud-hosted solution back end to connect virtually any device. Extend your solution from the cloud to the edge with per-device authentication, built-in device management, and scaled provisioning.

[Azure IoT Edge](https://azure.microsoft.com/en-us/services/iot-edge/) is a fully managed service built on Azure IoT Hub. Deploy your cloud workloads—artificial intelligence, Azure and third-party services, or your own business logic to run on Internet of Things (IoT) edge devices via standard containers.

[Azure Lighthouse](https://azure.microsoft.com/en-us/services/azure-lighthouse/) is a secure managed services and access control for partners and customers.

[Azure Backup](https://azure.microsoft.com/en-us/services/backup/) is a cost-effective, secure, one-click backup solution that’s scalable based on your backup storage needs. The centralized management interface makes it easy to define backup policies and protect a wide range of enterprise workloads, including Azure Virtual Machines, SQL and SAP databases, and Azure file shares.

[Azure Resource Manager](https://azure.microsoft.com/en-us/features/resource-manager/) is a tool that enables you to repeatedly deploy your app and have confidence your resources are deployed in a consistent state. You define the infrastructure and dependencies for your app in a single declarative template. This template is flexible enough to use for all of your environments such as test, staging or production.

[Azure Automanage](https://azure.microsoft.com/en-us/services/azure-automanage/) is a tool that implifies IT management with optimized, automated operations across the entire lifecycle of dev/test and production virtual machines (VMs).

[Azure Network Watcher](https://azure.microsoft.com/en-us/services/network-watcher/) is a tool that monitors, diagnoses, and gains insights to your network performance and health.

[Azure Resource Mover](https://azure.microsoft.com/en-us/services/resource-mover/) is a that that Simplifies how you move multiple resources between Global Azure regions.

[Azure Bastion](https://azure.microsoft.com/en-us/services/azure-bastion/) is a fully managed PaaS service that provides secure and seamless RDP and SSH access to your virtual machines directly through the Azure Portal. Azure Bastion is provisioned directly in your Virtual Network (VNet) and supports all VMs in your Virtual Network (VNet) using SSL without any exposure through public IP addresses.

[Azure Load balancing](https://azure.microsoft.com/en-us/products/azure-load-balancing/) is a service that instantly scale your applications with Azure load balancing services for high availability and high performance. Get started with a quick needs assessment and load balancing recommendation—using the service selection tool.

[Azure Orbital](https://azure.microsoft.com/en-us/services/orbital/) is a Ground Station As-a-Service that provides communication and control of your satellite. Orbital enables easy and integrated data processing and scale for your operations directly from Azure. Leverage familiar Azure services to process and store your data at scale.

[Azure Route Server](https://azure.microsoft.com/en-us/services/route-server/) is a tool that enables network appliances to exchange route information with Azure virtual networks dynamically. Configure your network appliances and Azure ExpressRoute and VPN gateways to automatically take the latest route information from Azure Route Server instead of manually talking to each network.

[Azure VPN Gateway](https://azure.microsoft.com/en-us/services/vpn-gateway/) is a service that connects your on-premises networks to Azure through Site-to-Site VPNs in a similar way that you set up and connect to a remote branch office. The connectivity is secure and uses the industry-standard protocols Internet Protocol Security (IPsec) and Internet Key Exchange (IKE).

[Microsoft Azure Attestation](https://azure.microsoft.com/en-us/services/azure-attestation/) is a unified solution for remotely verifying the trustworthiness of a platform and integrity of the binaries running inside it. Azure Attestation receives evidence from the platform, validates it with security standards, evaluates it against configurable policies, and produces an attestation token for claims-based applications. The service supports attestation of trusted platform modules (TPMs) and trusted execution environments (TEEs) like Intel® Software Guard Extensions (SGX) and virtualization-based security (VBS) enclaves.

[Azure Data Box](https://azure.microsoft.com/en-us/services/databox/) is a device that easily moves data to Azure when busy networks aren’t an option. Move large amounts of data to Azure when you're limited by time, network availability, or costs, using common copy tools such as Robocopy. All data is AES-encrypted, and the devices are wiped clean after upload, in accordance with NIST Special Publication 800-88 revision 1 standards.

[Azure Blob Storage](https://azure.microsoft.com/en-us/services/storage/blobs/) is a massively scalable and secure object storage for cloud-native workloads, archives, data lakes, high-performance computing, and machine learning.

[PowerShell/PowerShell Core](https://docs.microsoft.com/en-us/powershell/) is a cross-platform (Windows, Linux, and macOS) automation and configuration tool/framework that works well with your existing tools and is optimized for dealing with structured data (e.g. JSON, CSV, XML, etc.), REST APIs, and object models. It includes a command-line shell, an associated scripting language and a framework for processing cmdlets.

[Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/) creates virtual machines on Windows 10. Hyper-V can be enabled in many ways including using the Windows 10 control panel, PowerShell or using the Deployment Imaging Servicing and Management tool (DISM).

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces) is an integrated development environment(IDE) on GitHub. That allows developers to develop entirely in the cloud using Visual Studio and Visual Studio Code.

[GitHub Actions](https://docs.github.com/en/actions) will automate, customize, and execute your software development workflows right in your repository with GitHub Actions. You can discover, create, and share actions to perform any job you'd like, including CI/CD, and combine actions in a completely customized workflow.[GitHub Actions for Azure](https://docs.microsoft.com/en-us/azure/developer/github/github-actions) you can create workflows that you can set up in your repository to build, test, package, release and deploy to Azure.

# AWS Development
[Back to the Top](https://github.com/mikeroyal/Bash-PowerShell-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/114322508-7d8c7280-9ad5-11eb-807e-4dc63c9bc0e1.png">
  <br />
</p>

**[AWS Tools for PowerShell](https://aws.amazon.com/powershell/)**

<img src="https://user-images.githubusercontent.com/45159366/114321714-02c15880-9ad1-11eb-95ac-441aac6b438d.png">

**Amazon Web Services Architecture. Source: [AWS](https://aws.amazon.com/architecture/)**

## AWS Learning Resources

[Amazon Web Services](https://aws.amazon.com/about-aws/) is a reliable, scalable, and inexpensive on-demand cloud computing platforms, services and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis.

[AWS Training and Certification](https://aws.amazon.com/training/)

[Getting Started with Amazon Web Services (AWS)](https://aws.amazon.com/getting-started/)

[Hands-On Tutorials for Amazon Web Services (AWS)](https://aws.amazon.com/getting-started/hands-on/

[Getting started with AWS IoT Core ](https://docs.aws.amazon.com/iot/latest/developerguide/iot-gs.html)

[AWS Academy - Amazon Web Services (AWS)](https://aws.amazon.com/training/awsacademy/)

[AWS Educate](https://aws.amazon.com/education/awseducate/)

[Architecting on AWS Classroom Training](https://aws.amazon.com/training/classroom/architecting-on-aws/)

[DevOps Engineering on AWS from AWS Training](https://aws.amazon.com/training/course-descriptions/devops-engineering/)

[AWS Certified DevOps Engineer - Professional from A Cloud Guru](https://acloud.guru/learn/aws-certified-devops-engineer-professional)

[AWS Internet of Things Foundation Series Training](https://www.aws.training/Details/Curriculum?id=27289)

[AWS Certified Security - Specialty Certification](https://aws.amazon.com/certification/certified-security-specialty/)

[AWS Certification Training Courses on Udemy](https://www.udemy.com/topic/aws-certification/)

[Amazon Web Services Courses on Coursera](https://www.coursera.org/aws)

[Amazon Web Services Courses on edX](https://www.edx.org/school/aws)

## AWS Tools

[AWS Pricing Calculator](https://calculator.aws/)

[AWS Marketplace](https://aws.amazon.com/) is a digital catalog with thousands of software listings from independent software vendors that make it easy to find, test, buy, and deploy software that runs on AWS.

[AWS Cloud9](https://aws.amazon.com/cloud9/) is a cloud-based integrated development environment (IDE) that lets you write, run, and debug your code with just a browser. It includes a code editor, debugger, and terminal. Cloud9 comes prepackaged with essential tools for popular programming languages, including JavaScript, Python, PHP, and more, so you don’t need to install files or configure your development machine to start new projects.

[AWS Command Line Interface (CLI)](https://aws.amazon.com/cli/) is a unified tool to manage your AWS services through the command line interface.

[AWS Amplify Command Line Interface (CLI)](https://docs.amplify.aws/cli) is a unified toolchain to create, integrate, and manage the AWS cloud services for your app.

[AWS Serverless Application Model (SAM) CLI](https://github.com/aws/aws-sam-cli) is a command line tool for an open-source framework for building serverless applications. It provides shorthand syntax to express functions, APIs, databases, and event source mappings. With just a few lines of configuration, you can define the application you want and model it.

[AWS Copilot command line interface (CLI)](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Copilot.html) is a command line tool that simplifies building, releasing, and operating production-ready containerized applications on Amazon ECS from a local development environment. The AWS Copilot CLI aligns with developer workflows that support modern application best practices: from using infrastructure as code to creating a CI/CD pipeline provisioned on behalf of a user.

[Amazon Elastic Container Service (Amazon ECS) command line interface (CLI)](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ECS_CLI.html) is a command line tool that  provides high-level commands to simplify creating, updating, and monitoring clusters and tasks from a local development environment. The Amazon ECS CLI supports Docker Compose files, a popular open-source specification for defining and running multi-container applications.

[AWS ECS](https://aws.amazon.com/ecs/) is a highly scalable, high-performance container orchestration service that supports Docker containers and allows you to easily run and scale containerized applications on AWS. Amazon ECS eliminates the need for you to install and operate your own container orchestration software, manage and scale a cluster of virtual machines, or schedule containers on those virtual machines.

[Amazon Simple Storage Service (Amazon S3)](https://aws.amazon.com/s3/) is an object storage service that offers industry-leading scalability, data availability, security, and performance. This means customers of all sizes and industries can use it to store and protect any amount of data for a range of use cases, such as data lakes, websites, mobile applications, backup and restore, archive, enterprise applications, IoT devices, and big data analytics.

[AWS Cloud Development Kit (AWS CDK)](https://aws.amazon.com/cdk/) is an open-source software development framework to define cloud infrastructure in code and provision it through AWS CloudFormation. It offers a high-level object-oriented abstraction to define AWS resources imperatively using the power of modern programming languages.

[AWS Lambda](https://aws.amazon.com/lambda/) is an event-driven, serverless computing platform provided by Amazon as a part of the Amazon Web Services. It is a computing service that runs code in response to events and automatically manages the computing resources required by that code.

[AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) is an easy-to-use service for deploying and scaling web applications and services developed with Java,.NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and IIS.

[AWS IoT Greengrass](https://aws.amazon.com/greengrass/) is an Internet of Things (IoT) open source edge runtime and cloud service that helps you build, deploy, and manage device software. It is used for IoT applications on millions of devices in homes, factories, vehicles, and businesses.

[AWS CodeArtifact](https://aws.amazon.com/codeartifact/) is a fully managed artifact repository service that makes it easy for organizations of any size to securely store, publish, and share software packages used in their software development process. CodeArtifact can be configured to automatically fetch software packages and dependencies from public artifact repositories so developers have access to the latest versions.

[AWS CodeCommit](https://aws.amazon.com/codecommit/) is a fully-managed source control service that hosts secure Git-based repositories. It makes it easy for teams to collaborate on code in a secure and highly scalable ecosystem. CodeCommit eliminates the need to operate your own source control system or worry about scaling its infrastructure.

[AWS CodePipeline](https://aws.amazon.com/codepipeline/) is a fully managed [continuous delivery](https://aws.amazon.com/devops/continuous-delivery/) service that helps you automate your release pipelines for fast and reliable application and infrastructure updates. CodePipeline automates the build, test, and deploy phases of your release process every time there is a code change, based on the release model you define. This enables you to rapidly and reliably deliver features and updates. You can easily integrate AWS CodePipeline with third-party services such as GitHub or with your own custom plugin.

[AWS CodeStar](https://aws.amazon.com/codestar/) is a unified user interface, enabling you to easily manage your software development activities in one place. With AWS CodeStar, you can set up your entire [continuous delivery](https://aws.amazon.com/devops/continuous-delivery/) toolchain in minutes, allowing you to start releasing code faster.

[AWS X-Ray](https://aws.amazon.com/xray/) is a tool that traces user requests as they travel through your entire application. It aggregates the data generated by the individual services and resources that make up your application, providing you an end-to-end view of how your application is performing. It helps developers analyze and debug production, distributed applications, such as those built using a microservices architecture.

[AWS CodeDeploy](https://aws.amazon.com/codedeploy/) is a fully managed deployment service that automates software deployments to a variety of compute services such as Amazon EC2, AWS Fargate, AWS Lambda, and your on-premises servers. AWS CodeDeploy makes it easier for you to rapidly release new features, helps you avoid downtime during application deployment, and handles the complexity of updating your applications.

[AWS CodeBuild](https://aws.amazon.com/codebuild/) is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy. With CodeBuild, you don't need to provision, manage, and scale your own build servers.

[Red Hat OpenShift Service on AWS (ROSA)](https://www.openshift.com/products/amazon-openshift) is a fully-managed and jointly supported Red Hat OpenShift offering that combines the power of Red Hat OpenShift, the industry's most comprehensive enterprise Kubernetes platform, and the AWS public cloud.

[Amazon API Gateway](https://aws.amazon.com/api-gateway/) is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.

[AWS Storage Gateway](https://aws.amazon.com/storagegateway/) is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage.

[AWS Transit Gateway](https://aws.amazon.com/transit-gateway/) is a tool that connects VPCs and on-premises networks through a central hub. This simplifies your network and puts an end to complex peering relationships. It acts as a cloud router - each new connection is only made once.

[Gateway Load Balancer (GWLB)](https://aws.amazon.com/elasticloadbalancing/gateway-load-balancer/) is a tool that makes it easy to deploy, scale, and manage your third-party virtual appliances. It gives you one gateway for distributing traffic across multiple virtual appliances, while scaling them up, or down, based on demand.

[AWS Chalice](https://aws.amazon.com/blogs/developer/deploying-aws-chalice-application-using-aws-cloud-development-kit/) is a Python Serverless Microframework for AWS and allows you to quickly create and deploy applications that use Amazon API Gateway and AWS Lambda.

[AWS ParallelCluster](https://aws.amazon.com/hpc/parallelcluster/) is an AWS supported Open Source cluster management tool to deploy and manage HPC clusters in the AWS cloud.

[AWS Copilot CLI](https://aws.amazon.com/containers/copilot/) is a tool for developers to build, release and operate production ready containerized applications on Amazon ECS and AWS Fargate.

[AWS Fargate](https://aws.amazon.com/fargate/) is a serverless compute engine for containers that works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS).

[Amazon Chime](https://aws.amazon.com/chime/) is a communications service that lets you meet, chat, and place business calls inside and outside your organization, all using a single application.

[Amazon Virtual Private Cloud (Amazon VPC)](https://console.aws.amazon.com/vpc) is a service that lets you launch AWS resources in a logically isolated virtual network that you define. You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways.

[AWS Lightsail](https://aws.amazon.com/lightsail/) is an easy-to-use virtual private server (VPS) that offers you everything needed to build an application or website, plus a cost-effective, monthly plan.

[Amazon Relational Database Service (Amazon RDS)](https://console.aws.amazon.com/rds/home) is a tool that makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching and backups.

[Amazon Aurora](https://console.aws.amazon.com/rds/home) is a MySQL and PostgreSQL-compatible relational database built for the cloud, that combines the performance and availability of traditional enterprise databases with the simplicity and cost-effectiveness of open source databases.

[Amazon Athena](https://aws.amazon.com/athena/) is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run.

[Amazon CloudSearch](https://aws.amazon.com/cloudsearch/) is a managed service in the AWS Cloud that makes it simple and cost-effective to set up, manage, and scale a search solution for your website or application.

[Amazon Kinesis](https://aws.amazon.com/kinesis/) is a tool that makes it easy to collect, process, and analyze real-time, streaming data so you can get timely insights and react quickly to new information. Amazon Kinesis offers key capabilities to cost-effectively process streaming data at any scale, along with the flexibility to choose the tools that best suit the requirements of your application. With Amazon Kinesis, you can ingest real-time data such as video, audio, application logs, website clickstreams, and IoT telemetry data for machine learning, analytics, and other applications.

Amazon EMR is the industry-leading cloud big data platform for processing vast amounts of data using open source tools such as [Apache Spark](https://aws.amazon.com/emr/features/spark/), [Apache Hive](https://aws.amazon.com/emr/features/hive/), [Apache HBase](https://aws.amazon.com/emr/features/hbase/), [Apache Flink](https://aws.amazon.com/blogs/big-data/use-apache-flink-on-amazon-emr/),[Apache Hudi](https://aws.amazon.com/emr/features/hudi/), and [Presto](https://aws.amazon.com/emr/features/presto/).

[AWS RedShift](https://aws.amazon.com/redshift/) is a data warehouse tool that makes it as easy to gain new insights from all your data. With Redshift, you can easily query and combine exabytes of structured and semi-structured data across your data warehouse, operational database, and data lake using standard SQL. It lets you easily save the results of your queries back to your S3 data lake using open formats, like Apache Parquet, so that you can do additional analytics from other analytics services like Amazon EMR, Amazon Athena, and Amazon SageMaker.

[AWS Data Pipeline](https://aws.amazon.com/datapipeline/) is a web service that helps you reliably process and move data between different AWS compute and storage services, as well as on-premises data sources, at specified intervals. AWS Data Pipeline, let's you regularly access your data where it’s stored, transform and process it at scale, and efficiently transfer the results to AWS services such as Amazon S3, Amazon RDS, Amazon DynamoDB, and Amazon EMR.

[AWS Glue](https://aws.amazon.com/glue/) is a serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.

[AWS Lake Formation](https://aws.amazon.com/lake-formation/) is a service that makes it easy to set up a secure data lake in days. A data lake is a centralized, curated, and secured repository that stores all your data, both in its original form and prepared for analysis.

[Amazon Managed Blockchain](https://aws.amazon.com/managed-blockchain/) is a fully managed service that makes it easy to join public networks or create and manage scalable private networks using the popular open-source frameworks [Hyperledger Fabric](https://aws.amazon.com/blockchain/what-is-hyperledger-fabric/) and Ethereum.

[AWS Wavelength](https://aws.amazon.com/wavelength/) is an AWS Infrastructure offering optimized for mobile edge computing applications. Wavelength Zones are AWS infrastructure deployments that embed AWS compute and storage services within communications service providers’ (CSP) datacenters at the edge of the 5G network, so application traffic from 5G devices can reach application servers running in Wavelength Zones without leaving the telecommunications network.

[AWS Outposts](https://aws.amazon.com/outposts/) is a fully managed service that offers the same AWS infrastructure, AWS services, APIs, and tools to virtually any datacenter, co-location space, or on-premises facility for a truly consistent hybrid experience. AWS Outposts is ideal for workloads that require low latency access to on-premises systems, local data processing, data residency, and migration of applications with local system interdependencies.

[AWS Batch](https://aws.amazon.com/batch/) is atool that enables developers, scientists, and engineers to easily and efficiently run hundreds of thousands of batch computing jobs on AWS. AWS Batch dynamically provisions the optimal quantity and type of compute resources (e.g., CPU or memory optimized instances) based on the volume and specific resource requirements of the batch jobs submitted. AWS Batch plans, schedules, and executes your batch computing workloads across the full range of AWS compute services and features, such as [AWS Fargate](https://aws.amazon.com/fargate/), [Amazon EC2](https://aws.amazon.com/ec2/) and [Spot Instances](https://aws.amazon.com/ec2/spot/).

[Amazon Forecast](https://aws.amazon.com/forecast/) is a fully managed service that uses machine learning to deliver highly accurate forecasts.

[AWS Snow Family](https://aws.amazon.com/snow/) is a highly-secure, portable devices to collect and process data at the edge, and migrate data into and out of AWS.

[Amazon Neptune](https://aws.amazon.com/neptune/) is a fast, reliable, fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets. The core of Amazon Neptune is a purpose-built, high-performance graph database engine optimized for storing billions of relationships and querying the graph with milliseconds latency.

[Amazon Timestream](https://aws.amazon.com/timestream/) is a fast, scalable, and serverless time series database service for IoT and operational applications that makes it easy to store and analyze trillions of events per day up to 1,000 times faster and at as little as 1/10th the cost of relational databases.

[AWS IoT](https://aws.amazon.com/iot/) is a service that is built on a secure and proven cloud infrastructure, and scales to billions of devices and trillions of messages. It easily integrates with other AWS services, so you can build complete solutions.

[AWS IoT Core](https://aws.amazon.com/iot-core/) lets you connect IoT devices to the AWS cloud without the need to provision or manage servers. AWS IoT Core can support billions of devices and trillions of messages, and can process and route those messages to AWS endpoints and to other devices reliably and securely.

# Google Cloud Platform Development
[Back to the Top](https://github.com/mikeroyal/Bash-PowerShell-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/114321928-639d6080-9ad2-11eb-8297-5e6c10c1c792.png">
  <br />
</p>

**[Start building with PowerShell on Google Cloud](https://cloud.google.com/powershell/)**

**[PowerShell Documentation](https://cloud.google.com/powershell/docs/)**

<img src="https://user-images.githubusercontent.com/45159366/114321930-66985100-9ad2-11eb-9e7e-8eb883d7bf37.png">

**Google Cloud Platform (GCP) Architecture. Source: [Google Cloud](https://cloud.google.com/architecture/)**


## Google Cloud Learning Resources

[Google Cloud Platform] is a public cloud platform that lets you build, deploy, and scale applications, websites, and services on the same infrastructure as Google.

[Google Cloud Courses and Training](https://cloud.google.com/training/)

[Architecting with Google Compute Engine](https://google.qwiklabs.com/courses/1421?utm_source=gcp_training&utm_medium=website&utm_campaign=cgc)

[Get started with Cloud Storage on Web with Firebase](https://firebase.google.com/docs/storage/web/start)

[Getting started with BigQuery](https://cloud.google.com/bigquery/docs/quickstarts)

[Machine Learning Crash Course with Google Cloud](https://developers.google.com/machine-learning/crash-course/)

[Architecting with Google Kubernetes Engine in Google Cloud](https://google.qwiklabs.com/courses/1232?utm_source=gcp_training&utm_medium=website&utm_campaign=cgc)

[Google Cloud Internet of Things (IoT)](https://developers.google.com/iot/)

[Google Cloud Certified Professional Cloud Security Engineer](https://cloud.google.com/certification/cloud-security-engineer)

[Google Cloud Courses on Coursera](https://www.coursera.org/googlecloud)

[Google Cloud Courses on Udemy](https://www.udemy.com/topic/google-cloud/)

## Google Cloud Tools

[Cloud SDK](https://cloud.google.com/sdk/) is a clietn tool used to to manage Google Cloud resources and applications with command-line tools and libraries. The Cloud SDK contains gcloud, gsutil, and bq command-line tools, which you can use to access [Compute Engine](https://cloud.google.com/compute), [Cloud Storage](https://cloud.google.com/storage), [BigQuery](https://cloud.google.com/bigquery), and more.

[Google Cloud Shell](https://cloud.google.com/shell/) is a free admin machine with browser-based command-line access for managing your infrastructure and applications on Google Cloud Platform.

[Cloud Code](https://cloud.google.com/code) is a client tool that writes, debugs, and run cloud-native applications, locally or in the cloud—quickly and easily. Extensions to IDEs such as Visual Studio Code and IntelliJ are provided to let you rapidly iterate, debug, and deploy code to Kubernetes.

[gcloud](https://cloud.google.com/sdk/gcloud/) is a CLI (command line interface) manages authentication, local configuration, developer workflow, interactions with Google Cloud APIs.

[gsutil](https://cloud.google.com/storage/docs/gsutil) is a Python application that lets you access Cloud Storage from the command line.

[Compute Engine](https://cloud.google.com/compute) is a secure and customizable compute service that lets you create and run virtual machines on Google’s infrastructure.

[App Engine](https://cloud.google.com/appengine/) is a client tool that lets you build and run applications on Google's infrastructure. It automatically scales to support sudden traffic spikes without provisioning, patching, or monitoring.

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for deploying containerized applications.

[Cloud Storage](https://cloud.google.com/storage) is a Object storage for companies of all sizes. Where store any amount of data and retrieve it as often as you would like to.

[BigQuery](https://cloud.google.com/bigquery) is a serverless, highly scalable, and cost-effective multi-cloud data warehouse designed for business agility.

[Cloud Bigtable](https://cloud.google.com/bigtable/) is Google's fully managed NoSQL Big Data database service. It's the same database that powers many core Google services, including Search, Analytics, Maps, and Gmail.

[Cloud SQL](https://cloud.google.com/sql/) is a tool that makes it easy to set up, manage, and administer your Postgres databases on Google Cloud.

[Cloud Datastore](https://cloud.google.com/datastore/) is a schemaless database, which allows you to worry less about making changes to your underlying data structure as your application evolves.

[Cloud Pub/Sub](https://cloud.google.com/pubsub/) is a messaging middleware for traditional service integration or a simple communication medium for modern microservices.

[Cloud Dataflow](https://cloud.google.com/dataflow/) is a tool that brings streaming events to Google Cloud's AI Platform and TensorFlow Extended (TFX) to enable predictive analytics, fraud detection, real-time personalization, and other advanced analytics.

[Cloud Dataproc](https://cloud.google.com/dataproc/) is a fully managed and highly scalable service for running Apache Spark, Apache Flink, Presto, and 30+ open source tools and frameworks.

[Cloud Datalab](https://cloud.google.com/datalab/docs/) is a tool that provides a productive, interactive, and integrated tool to explore, visualize, analyze and transform data, bringing together the power of Python, SQL, JavaScript, and the Google Cloud Platform with services such as BigQuery and Storage.

[Cloud Vision API](https://cloud.google.com/vision/) is a library that offers powerful pre-trained machine learning models through REST and RPC APIs.

[Cloud Speech API](https://cloud.google.com/speech-to-text/) is a library that enables developers to convert audio to text by applying powerful neural network models. The API recognizes over 80 languages and variants, to support your global user base.

[Cloud Build](https://cloud.google.com/cloud-build) is a continuous build, test, and deploy software across all languages and in multiple environments—including VMs, serverless, Kubernetes, and Firebase.

[Anthos](https://cloud.google.com/anthos/docs/concepts/overview) is a modern application management platform that provides a consistent development and operations experience for cloud and on-premises environments.

[Jenkins on Google Cloud](https://cloud.google.com/jenkins) is a client tool that helps speed up, scale, and security from your Jenkins pipeline.

[Tekton on Google Cloud](https://cloud.google.com/tekton) is a client tool that standardizes CI/CD pipelines across languages, and tools on premises or in the cloud with a Kubernetes native open source framework.

[Artifact Registry](https://cloud.google.com/artifact-registry) is a client tool to manage container images and language packages such as Maven and npm all in one place, fully integrated with Google Cloud’s tooling and runtimes.

[Cloud Deployment Manager](https://cloud.google.com/deployment-manager) is a client that creates and manages cloud resources with simple templates. Specify all the resources needed for applications in a declarative format using yaml.

[Red Hat OpenShift on Google Cloud](https://cloud.google.com/solutions/partners/openshift-on-gcp) is a fully-managed and jointly supported Red Hat OpenShift offering that enables you to deploy stateful and stateless apps with nearly any language, framework, database, or service. It gives you a hosted environment entirely on Google Cloud. A hybrid environment where you maintain part of your workload on-premises or in a private hosting environment and migrate the rest to Google Cloud.

# VMWare Development
[Back to the Top](https://github.com/mikeroyal/Bash-PowerShell-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115159591-c5b51300-a048-11eb-8d94-643f711a3920.png">
  <br />
</p>

<img src="https://user-images.githubusercontent.com/45159366/115159594-cb125d80-a048-11eb-8cfb-fa6c632a09d2.png">

**VMware Horizon Cloud with Hosted Infrastructure Networking Overview. Source: [VMware](https://blogs.vmware.com/euc/2017/05/vmware-horizon-cloud-hosted-infrastructure-networking-overview.html)**

 <img src="https://user-images.githubusercontent.com/45159366/115299303-7a1b6b80-a113-11eb-9df6-f5951d8d2c83.png">

**VMware Multi-Cloud Optimization Strategy. Source: [VMware](https://www.vmware.com/content/microsites/possible/stories-uk/maximizing-the-value-of-multi-cloud.html)**

## VMware Learning Resources

[VMware](https://www.vmware.com/) is a cloud computing and virtualization technology company. Dell owns a 81% stake in VMware, which it picked up in its [2016 acquisition of EMC(data storage hardware maker) for $67 billion](https://en.wikipedia.org/wiki/Dell_EMC).

[VMware GitHub](https://github.com/vmware)

[VMware Technology Partner Hub](https://techpartnerhub.vmware.com/sdks?rel=/sdks)

[VMware API and SDK Documentation](https://www.vmware.com/support/pubs/sdk_pubs.html)

[VMware Infrastructure SDK Programming Guide](https://www.vmware.com/pdf/ProgrammingGuide201.pdf)

[VMware Learning Paths](https://www.vmware.com/learning.html)

[VMware Learning Online Store](https://store-us.vmware.com/vmware-education-online-store)

[VMware On Demand courses](https://www.vmware.com/learning/on-demand-courses.html)

[VMware IT academy courses](https://www.vmware.com/company/it-academy/courses.html)

[VMware Certifications](https://www.vmware.com/education-services/certification.html)

[VMware Certified Professional - Data Center Virtualization](https://www.vmware.com/education-services/certification/vcp-dcv.html)

[VMware Courses on Coursera](https://www.coursera.org/vmware)

[VMware Courses on Udemy](https://www.udemy.com/courses/search/?src=ukw&q=VMware)

[VMware Vsphere Certification Training on Udemy](https://www.udemy.com/topic/VMware-Vsphere/)

[VMware Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/vmware-company)

[VMware Courses on HPE Education Services ](https://education.hpe.com/us/en/training/portfolio/vmware.html)

[VMware Training Courses on New Horizons](https://www.newhorizons.com/courses-and-certifications/technical-courses/vmware)

[VMware Training Courses on Global Knowledge](https://www.globalknowledge.com/us-en/training/course-catalog/brands/vmware/)

## VMware Tools

[VMware PowerCLI](https://code.vmware.com/web/tool/12.3.0/vmware-powercli) is a command-line and scripting tool built on Windows PowerShell, and provides more than 800 cmdlets for managing and automating vSphere, VMware Cloud Director, vRealize Operations Manager, vSAN, NSX-T Data Center, VMware Cloud Services, VMware Cloud on AWS, VMware HCX, VMware Site Recovery Manager, and VMware Horizon environments.

[Fusion for MacOS](https://www.vmware.com/products/fusion.html) is an application for running multiple operating systems on Mac.

[Workstation Player](https://www.vmware.com/products/workstation-player.html) is a simple tool for running a second OS on your Windows or Linux PC, free for personal use.

[Workstation Pro](https://www.vmware.com/products/workstation-pro.html) is an application for running multiple operating systems on Windows and Linux.

[Tanzu Mission Control](https://tanzu.vmware.com/mission-control) is a single point of control to provision and apply policies to all of your Kubernetes across clouds.

[Tanzu Build Service](https://tanzu.vmware.com/build-service) is a automated container creation, management, and governance at enterprise scale.

[Tanzu Kubernetes Grid](https://tanzu.vmware.com/kubernetes-grid) is a ubiquitous Kubernetes runtime embedded in vSphere and operable across public clouds and edge.

[Tanzu Application Catalog](https://tanzu.vmware.com/application-catalog) is a curated and customized catalog of apps and components available in your private repository.

[Tanzu GemFire](https://www.vmware.com/products/pivotal-gemfire.html) is a distributed data management platform especially useful for high-volume, latency-sensitive, mission-critical, transactional systems.

[Tanzu RabbitMQ](https://www.vmware.com/products/pivotal-rabbitmq.html) is a protocol-based, highly scalable, and easy-to-deploy queuing system that makes handling message traffic virtually effortless.

[Tanzu Application Service](https://tanzu.vmware.com/application-service) is an application runtime optimized for Spring and Spring Boot with turnkey microservices, operations, and security.

[Tanzu Observability by Wavefront](https://tanzu.vmware.com/observability) is an enterprise observability that delivers metrics and insights from infrastructure to apps.

[Tanzu Service Mesh](https://tanzu.vmware.com/service-mesh) is an enterprise-class service mesh technology to connect and protect your microservices on multi-cluster Kubernetes.

[VMware Pivotal Labs](https://tanzu.vmware.com/labs) is a cloud native experts accelerate software delivery and modernize your apps while reducing operating costs and risk.

[Pivotal tc Server](https://www.vmware.com/products/pivotal-tcserver.html) is a lightweight Java application server that extends Apache Tomcat for use in large-scale mission-critical environments.

[Pivotal App Suite](https://www.vmware.com/products/pivotal-appsuite.html) is a middleware platform used by developers and ops to build and run cloud-scale custom applications.

[VMware Cloud Foundation](https://www.vmware.com/products/cloud-foundation.html) is an integrated cloud infrastructure and management services for private and public cloud.

[VMware Cloud on AWS](https://cloud.vmware.com/vmc-aws) is a consistent vSphere-based infrastructure delivered on AWS.

[VMware Cloud on AWS Outposts](https://cloud.vmware.com/vmc-aws-outposts) is a fully-managed VMware Cloud experience in your data center.

[Business-Critical Apps](https://www.vmware.com/solutions/business-critical-apps.html) is a consistent infrastructure and operations for your critical workloads, including: Microsoft SQL Server, Oracle, and SAP.

[VMware Cloud Provider Platform](http://cloudsolutions.vmware.com/) is a portfolio of private and hybrid cloud services delivered by VMware partners.

[VMware Cloud Director Availability](https://www.vmware.com/products/cloud-director-availability.html) is a cloud-based disaster recovery services that VMware Cloud Providers can offer their customers.

[Cloud Partner Navigator](https://www.vmware.com/products/cloud-partner-navigator.html) is a unified partner platform for multi-cloud service delivery and simplified business and customer operations.

[VMware Cloud on Dell EMC](https://www.vmware.com/products/vmc-on-dell-emc.html) is a fully-managed VMware Cloud experience deployed on a Dell EMC VxRail appliance.

[Cloud Verified Partners](https://cloud.vmware.com/vmware-cloud-verified) is a cloud providers delivering the full power of VMware Cloud infrastructure.

[VMware Cloud Director](https://www.vmware.com/products/cloud-director.html) is a leading cloud service delivery platform for secure, differentiated and elastic hybrid cloud services.

[VMware Cloud Director service (CDS)](http://cloud.vmware.com/cloud-provider-hub/cloud-director-service) is a SaaS implementation of VMware Cloud Director that enables multi-tenancy on VMware Cloud on AWS providing geo expansion and asset-light use cases for VMware Cloud Providers.

[NSX Data Center](https://www.vmware.com/products/nsx.html) is a network and security virtualization platform.

[vRealize Suite & vCloud Suite](https://www.vmware.com/products/vrealize-suite-vcloud-suite.html) is a cloud system management platform.

[Dell EMC VxRail](https://www.vmware.com/products/hyper-converged-infrastructure/dell-emc-vxrail.html) is a turnkey hyperconverged infrastructure appliance with full VMware integration.

[vSAN](https://www.vmware.com/products/vsan.html) is a flash-optimized, vSphere-native storage for private and public cloud.

[vSphere](https://www.vmware.com/products/vsphere.html) is an efficient and secure compute virtualization.

[vCenter Server](https://www.vmware.com/products/vcenter-server.html) is a centralized platform for controlling your vSphere environments.

[vRealize Cloud Management](https://www.vmware.com/products/vrealize-cloud-management.html) is a hybrid cloud management solution that enables you to consistently deploy and operate apps, infrastructure, and platform services.

[vRealize Cloud Universal](https://www.vmware.com/products/vrealize-cloud-universal.html) is a SaaS management suite that combines automation, operations, and log analytics in a single license.

[vRealize Suite & vCloud Suite](https://www.vmware.com/products/vrealize-suite-vcloud-suite.html) is an essential cloud management suites that combine automation and operations with lifecycle management.

[vRealize Operations](https://www.vmware.com/products/vrealize-operations.html) is a unified management platform for planning and scaling SDDC and multi-cloud infrastructure.

[vRealize Operations Cloud](https://cloud.vmware.com/vrealize-operations-cloud) is a self-driving operations for hands-off and hassle-free hybrid cloud management.

[vRealize True Visibility Suite](https://www.vmware.com/products/vrealize-operations/true-visibility-suite.html) is a suite of management packs to help you monitor heterogeneous environments within vRealize Operations.

[vRealize AI Cloud](https://www.vmware.com/products/vrealize-ai-cloud.html) is a platform for the self-driving data center that uses reinforcement learning to continuously optimize your infrastructure.

[Integrated OpenStack](https://www.vmware.com/products/openstack.html) is a distribution that runs enterprise-grade OpenStack on top of VMware infrastructure.

[vRealize Automation](https://www.vmware.com/products/vrealize-automation.html) is a software to accelerate the delivery of IT services with automation and pre-defined policies.

[CloudHealth](https://www.cloudhealthtech.com/) is a service to optimize and govern financial, operational, and security management in your multi-cloud environment.

[vRealize Log Insight](https://www.vmware.com/products/vrealize-log-insight.html) is an intelligent log management and analytics tool.

[VMware HCX](https://cloud.vmware.com/vmware-hcx) is an app mobility and infrastructure hybridity across any-to-any vSphere environment.

[vRealize Network Insight Cloud](https://cloud.vmware.com/network-insight-cloud) is an app-centric security and network visibility delivered as-a-service.

[VMware Site Recovery](https://cloud.vmware.com/vmware-site-recovery) is an on-demand disaster recovery as-a-service (DRaaS).

[SecureState](https://go.cloudhealthtech.com/vmware-secure-state) is a real-time insights for proactive management of cloud security and compliance risks.

[VMware Cloud Marketplace](https://cloud.vmware.com/cloud-marketplace) is a rich ecosystem of third-party solutions and services designed and tested to run on VMware-based clouds.

[NSX Cloud](https://www.vmware.com/products/nsx-cloud.html) is a hybrid cloud networking and security.

[NSX Distributed IDS/IPS](https://www.vmware.com/products/nsx-distributed-ids-ips.html) is an advanced threat detection engine purpose-built to detect lateral threat movement on east-west network traffic.

[VMware SD-WAN by VeloCloud](https://www.vmware.com/products/sd-wan-by-velocloud.html) is a platform to access cloud services, private data centers, and SaaS-based applications.

[Service-Defined Firewall](https://www.vmware.com/security/internal-firewall.html) is an internal firewall that protects both workloads and east-west traffic.

[NSX Data Center](https://www.vmware.com/products/nsx.html) is an L2-L7 network and security virtualization platform.

[NSX Advanced Load Balancer](https://www.vmware.com/products/nsx-advanced-load-balancer.html) is a multi-cloud load balancing, web application firewall, and application analytics.

[Carbon Black Workload](https://www.carbonblack.com/products/vmware-carbon-black-cloud-workload/) is an advanced security purpose-built for workloads that reduces the attack surface and protects critical assets.

[NSX Intelligence](https://www.vmware.com/products/nsx-intelligence-analytics-engine.html) is a distributed analytics engine that provides automated security policy recommendations & audit trail of security policies.

[VMware Carbon Black EDR](https://www.carbonblack.com/products/edr/) is an on-premises endpoint detection and response (EDR) for threat hunting and incident response.

[Extended detection and response (XDR)](https://www.vmware.com/security/xdr.html) is a cloud-native security incident detection, investigation, and response platform for continuous, connected, and automated security operations.

[VMware Carbon Black Cloud](https://www.carbonblack.com/products/vmware-carbon-black-cloud/) is a cloud-native endpoint protection platform that helps prevent, detect, and respond to cyberattacks.

[VMware Carbon Black App Control](https://www.carbonblack.com/products/app-control/) is an on-premises app control and critical infrastructure protection.

Workspace ONE](https://www.vmware.com/products/workspace-one.html) is an intelligence-driven digital workspace platform that delivers and manages any app on any device.

[Workspace ONE Intelligence](https://www.vmware.com/products/workspace-one/intelligence.html) gives you insights, app analytics, and automation for your entire digital workspace.

[Workspace ONE Assist](https://www.vmware.com/products/workspace-one/workspaceone-assist.html) is a digitally transform employee experience with remote support.

[Workspace ONE Intelligent Hub](https://www.vmware.com/products/workspace-one/intelligent-hub.html) is a securely stay connected and be productive from anywhere on any device.

[Workspace ONE UEM Powered by AirWatch](https://www.vmware.com/products/workspace-one/unified-endpoint-management.html) is a unified endpoint management (UEM) technology that powers Workspace ONE.

[Horizon](https://www.vmware.com/products/horizon.html) is a leading platform for managing virtual desktops (VDI), apps, and online services.

[Horizon Cloud](https://www.vmware.com/products/horizon-cloud-virtual-desktops.html) is a flexible cloud platform for hosting virtual desktops and apps.

[NSX for Horizon](https://www.vmware.com/products/horizon/horizon-nsx.html) is a Virtual desktop infrastructure (VDI) networking solution with policies that dynamically follow desktops.

[vRealize Operations for Horizon](https://www.vmware.com/products/vrealize-operations-horizon.html) is a monitoring and reporting tool to manage Horizon and XenDesktop/XenApp environments.

[Horizon Apps](https://www.vmware.com/products/horizon-apps.html) is a unified workspace for published, SaaS, and mobile apps.

[App Volumes](https://www.vmware.com/products/appvolumes.html) is a real-time application delivery software with lifecycle management.

[vSAN for Horizon](https://www.vmware.com/products/horizon/horizon-vsan.html) is a VDI storage solution with a number of pre-configured appliances optimized for Horizon, including vSAN ReadyNodes and Dell EMC VxRail.

[Dynamic Environment Manager](https://www.vmware.com/products/dynamic-environment-manager.html) is a software for managing consistent desktop experience across virtual, physical and cloud-based desktops.

[vSphere](https://www.vmware.com/products/vsphere.html) is an efficient and secure compute virtualization platform for hybrid cloud.

[vSphere Hypervisor](https://www.vmware.com/products/vsphere-hypervisor.html) is a free, bare-metal hypervisor that virtualizes servers.

[vCenter Server](https://www.vmware.com/products/vcenter-server.html) is a centralized platform for controlling your vSphere environments.

[vCenter Converter](https://www.vmware.com/products/converter.html) is a software that transforms Windows and Linux-based physical machines into virtual machines.

[Virtual Volumes](https://www.vmware.com/products/vsphere/virtual-volumes.html) is an industry-wide framework that streamlines storage operations and offers freedom of choice.

[Pulse IoT Center](https://www.vmware.com/products/pulse-iot-device-management.html) is an edge infrastructure and IoT device management.

[VMware Cloud on Dell EMC](https://www.vmware.com/products/vmc-on-dell-emc.html) is a fully-managed VMware Cloud experience deployed on a Dell EMC VxRail appliance.

[Telco Cloud Infrastructure](https://www.vmware.com/products/telco-cloud-infrastructure.html) is a multi-tenant platform with compute, storage, networking, management, and operations capabilities.

[Uhana by VMware](https://www.vmware.com/products/uhana.html) is an AI-based RAN analytics for mobile network operators.

[Telco Cloud Platform](https://www.vmware.com/products/telco-cloud-platform.html) is a service to deploy network functions, anytime, anywhere in your 5G networks without disruption.

[Telco Cloud Operations](https://www.vmware.com/products/telco-cloud-operations.html) is an automated service assurance for physical and virtual network management.

[VMware Integrated OpenStack Carrier Edition](https://www.vmware.com/products/network-functions-virtualization/integrated-openstack.html) is a carrier-grade OpenStack solution with the fastest path to a fully operational environment.

[Telco Cloud Automation](https://www.vmware.com/products/telco-cloud-automation.html) is a service to orchestrate and automate the management of any network function and service cross any network and any cloud.

[VMware Blockchain](https://www.vmware.com/products/blockchain.html) is a decentralized trust platform with support for leading execution frameworks.

[VMware Learning Platform](https://cloud.vmware.com/learning-platform) is a SaaS platform that delivers hands-on virtual IT labs to anyone on the planet at cloud scale.

# Oracle Cloud Development
[Back to the Top](https://github.com/mikeroyal/Bash-PowerShell-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/116304999-02bf8a80-a758-11eb-9e44-a9662805a01f.png">
  <br />
</p>

<img src="https://user-images.githubusercontent.com/45159366/116305017-094e0200-a758-11eb-96d5-d5436b243424.png">

**Oracle Database Offerings in Oracle Cloud Infrastructure. Source: [Oracle](https://blogs.oracle.com/cloud-infrastructure/oracle-database-offerings-in-oracle-cloud-infrastructure)**

# Oracle Cloud Learning Resources

[Oracle Cloud Infrastructure (OCI)](https://www.oracle.com/cloud/) is an IaaS that delivers on-premises, high-performance computing power to run cloud native and enterprise company’s IT workloads. OCI provides real-time elasticity for enterprise applications by combining Oracle's autonomous services, integrated security, and serverless compute.

[Oracle Cloud Portal](https://docs.oracle.com/en/cloud/)

[Oracle Cloud Training and Certification](https://www.oracle.com/education/)

[Cloud Training for Oracle Cloud Infrastructure](https://www.oracle.com/cloud/iaas/training/)

[Enterprise Performance Management (EPM) Cloud - Training](https://docs.oracle.com/en/cloud/saas/epm-cloud/training.html)

[Top Oracle Cloud Courses on Udemy](https://www.udemy.com/topic/oracle-cloud/)

[Oracle Integration Cloud Services (OIC) - Oracle ICS on Udemy](https://www.udemy.com/course/oic-oracle-integration-cloud/)

[Top Oracle Cloud Courses on Coursera](https://www.coursera.org/courses?query=oracle)


## Oracle Cloud Tools

[Oracle Cloud Command Line Interface (CLI)](https://docs.oracle.com/en-us/iaas/Content/API/Concepts/cliconcepts.htm#Command_Line_Interface_CLI) is a comman line tool that provides the same core capabilities as the Oracle Cloud Infrastructure Console and provides additional commands that can extend the Console's functionality. The CLI is convenient for developers or anyone who prefers the command line to a GUI.

[PL/SQL SDK The Oracle Cloud Infrastructure SDK for PL/SQL](https://docs.oracle.com/en-us/iaas/Content/API/SDKDocs/plsqlsdk.htm#SDK_for_PLSQL) is a service that enables you to write code to manage Oracle Cloud Infrastructure resources. The latest version of the PL/SQL SDK is pre-installed by Oracle for all Autonomous Databases using shared Exadata infrastructure.

[Container Engine for Kubernetes (OKE)](https://docs.oracle.com/iaas/Content/ContEng/Concepts/contengoverview.htm) is a reliable build, deploy, and manage cloud-native containerized applications. You specify the compute resources that your applications require, and Container Engine for Kubernetes provisions them on Oracle Cloud Infrastructure in an existing tenancy.

[Oracle Analytics Cloud](https://www.oracle.com/business-analytics/analytics-cloud.html) is a service embedded with machine learning, which helps organizations to discover unique insights faster with automation and intelligence.

[Oracle Big Data Service](https://www.oracle.com/big-data/big-data-service/) is a service that makes it easy for customers to deploy Hadoop clusters of all sizes, with VM shapes ranging from 1 OCPU to a dedicated bare metal environment. Customers choose between high-performance NVmE storage or cost-effective block storage, and can grow or shrink their clusters.

[Oracle Big Data SQL Cloud Service](https://www.oracle.com/big-data/big-data-sql/) is a service that enables organizations to immediately analyze data across Apache Hadoop, NoSQL and Oracle Database leveraging their existing SQL skills, security policies and applications with extreme performance. From simplifying data science efforts to unlocking data lakes, Big Data SQL makes the benefits of Big Data available to the largest group of end users possible.

[Oracle Cloud Infrastructure (OCI) Data Catalog](https://www.oracle.com/big-data/data-catalog/) is a metadata management service that helps data professionals discover data and support data governance. Designed specifically to work well with the Oracle ecosystem, it provides an inventory of assets, a business glossary, and a common metastore for data lakes.

[Oracle Cloud Infrastructure (OCI) Data Flow](https://www.oracle.com/big-data/data-flow/) is a fully managed Apache Spark service to perform processing tasks on extremely large data sets without infrastructure to deploy or manage. This enables rapid application delivery because developers can focus on app development, not infrastructure management.

[Oracle Cloud Streaming service](https://www.oracle.com/cloud-native/streaming/) is a real-time, serverless, Apache Kafka-compatible event streaming platform for developers and data scientists. Streaming is tightly integrated with Oracle Cloud Infrastructure (OCI), Database, GoldenGate, and Integration Cloud. The service also provides out-of-the-box integrations for hundreds of third-party products across categories such as DevOps, databases, big data, and SaaS applications.

[Oracle Essbase](https://www.oracle.com/business-analytics/essbase.html) is a service that gives organizations the power to rapidly generate insights from multidimensional data sets using what-if analysis, and data visualization tools.

[Oracle APEX Application Development (APEX Service)](https://www.oracle.com/application-development/apex/) is a fully managed, low-code application development platform for building and deploying modern, data-driven applications in Oracle Cloud. Business users and application developers can create enterprise applications 38X faster than coding—without having to learn complex web technologies.

[Oracle Content and Experience](https://www.oracle.com/content-experience/) is a service to drive consistent, multichannel experiences with a market-first, smart authoring platform and an API-first approach that separates content delivery from content creation. Oracle Content and Experience solutions dramatically reduce time to market and process complexity across your entire organization.

[Oracle MySQL Database Service](https://www.oracle.com/mysql/) is a fully managed database service that lets developers quickly develop and deploy secure, cloud native applications using the world’s most popular open source database. MySQL Database Service is the only MySQL cloud service with an integrated, high-performance analytics engine—HeatWave—that enables customers to run sophisticated analytics directly against their operational MySQL databases, eliminating the need for complex, time-consuming, and expensive data movement and integration with a separate analytics database.

[Oracle NoSQL Database Cloud Service](https://www.oracle.com/database/nosql-cloud.html) is a service that makes it easy for developers to build applications using document, columnar and key-value database models, delivering predictable single digit millisecond response times with data replication for high availability.

[Oracle Visual Builder](https://www.oracle.com/application-development/visual-builder/) is a service that quickly turns your ideas into powerful apps that help run your business. Oracle Visual Builder lets you create and deploy web, mobile, and progressive web interfaces.

[Oracle Visual Builder Studio](https://www.oracle.com/application-development/visual-builder-studio/) is a service that rapidly create and extend applications using a visual development environment with integrated agile and collaborative development, version control, and continuous delivery automation.

[Oracle API gateway](https://www.oracle.com/cloud-native/api-gateway/) is a fully managed service. There are no servers to provision and maintain.

[Oracle Cloud Functions](https://www.oracle.com/cloud-native/functions/) is a serverless platform that lets developers create, run, and scale applications without managing any infrastructure. Functions integrate with Oracle Cloud Infrastructure, platform services and SaaS applications. Because Functions is based on the open source Fn Project, developers can create applications that can be easily ported to other cloud and on-premises environments.

[Oracle Cloud Infrastructure Container Registry](https://www.oracle.com/cloud-native/container-registry/) is an open standards-based, Oracle-managed Docker registry service for securely storing and sharing container images. Engineers can easily push and pull Docker images with the familiar Docker Command Line Interface (CLI) and API. To support container lifecycles, Registry works with Container Engine for Kubernetes, Identity and Access Management (IAM), Visual Builder Studio, and third-party developer and DevOps tools.

[Oracle Cloud Infrastructure Events Service](https://www.oracle.com/cloud-native/events-service/) is a service that tracks resource changes using events that comply with the Cloud Native Computing Foundation (CNCF) CloudEvents standard. Developers can respond to changes in real-time by triggering code with Functions, writing to Streaming, or sending alerts using Notifications.

[Oracle Roving Edge Infrastructure](https://www.oracle.com/cloud/roving-edge-infrastructure/) is a service that accelerates deployment of cloud workloads outside the data center. Ruggedized Oracle Roving Edge Devices (Oracle REDs) deliver cloud computing and storage services at the edge of networks and in disconnected locations, allowing faster processing close to the data source and enabling faster insights into the data.

[Oracle Blockchain Platform Cloud Service](https://www.oracle.com/application-development/cloud-services/blockchain-platform/) is a service to reliably share trusted data with multiple parties using Oracle Blockchain Platform Cloud Service.

[Oracle Mobile Hub](https://www.oracle.com/application-development/cloud-services/mobile/) is a service to quickly build, deploy, and manage mobile apps that connect to Oracle ERP, HCM, CX or any third-party system, on-premise or in the cloud.

[Oracle Bare Metal Servers](https://www.oracle.com/cloud/compute/bare-metal.html) is a service that provides customers with isolation, visibility, and control with a dedicated server. The servers support applications that require high core counts, large amounts of memory, and high bandwidth - scaling up to 128 cores (the largest in the industry), 2 TB of RAM, and up to 1 PB of block storage.

[Oracle Cloud Infrastructure- Compute](https://www.oracle.com/cloud/compute/) is a service that provides secure, elastic, compute capacity in the cloud that ranges from virtual machines and bare metal servers to HPC, GPU, container orchestration, and management.

[Oracle Cloud HPC solutions](https://www.oracle.com/cloud/hpc/) is a service that combines the performance of on-premises solutions with the elasticity and consumption-based costs of the cloud, giving customers the option to either migrate away from, or supplement, capital intensive on-premises systems. The Oracle Cloud Infrastructure HPC platform includes bare metal compute instances, low latency cluster networks for RDMA, high-performance storage solutions and filesystems, network traffic isolation, and the tools you need to automate and run jobs seamlessly in the cloud.

[Oracle GPU–Virtual Machines and Bare Metal](https://www.oracle.com/cloud/compute/gpu.html) is a high-performance computing platform for demanding applications that run sophisticated algorithms. Applications that rely on machine learning, image processing, and massively parallel high-performance computing jobs benefit from running GPUs as they allow companies solve complex problems and innovate faster.

[Oracle Cloud Virtual Machines](https://www.oracle.com/cloud/compute/virtual-machines/) is a service that provides secure, elastic, compute capacity in the cloud for workloads ranging from small development projects to large-scale, global applications like real-time communication platforms. A variety of VM shapes are available, including the new E3.Flex shape, which lets customers specify the precise number of cores (up to 64) and corresponding memory (up to 64 GB per core) to match workload requirements.

[Oracle Autonomous Data Warehouse](https://www.oracle.com/autonomous-database/autonomous-data-warehouse/) is a cloud data warehouse service that eliminates all the complexities of operating a data warehouse, securing data, and developing data-driven applications. It automates provisioning, configuring, securing, tuning, scaling, and backing up of the data warehouse.  It includes tools for self-service data loading, data transformations, business models, automatic insights, and built-in converged database capabilities that enable simpler queries across multiple data types and machine learning analysis.

[Oracle Autonomous JSON Database](https://www.oracle.com/autonomous-database/autonomous-json-database/) is a cloud document database service that makes it simple to develop JSON-centric applications. It features simple document APIs, serverless scaling, high performance ACID transactions, comprehensive security, and low pay-per-use pricing.

[Oracle Autonomous Transaction Processing](https://www.oracle.com/autonomous-database/autonomous-transaction-processing/) is a cloud database service that eliminates the complexity of operating and securing high-performance databases. The service automates provisioning, configuring, tuning, scaling, patching, encrypting, and repairing of databases. Additionally, the service includes all of Oracle’s advanced database options, such as real application clusters (RAC), multitenant, partitioning, in-memory, advanced security, and advanced compression.

[Oracle Exadata Cloud@Customer X8M](https://www.oracle.com/engineered-systems/exadata/cloud-at-customer/?bcid=5195990601001) is the simplest way to migrate your Oracle Databases to the cloud. It helps meet your requirements for strict data sovereignty and security by delivering high-performance Exadata Cloud Service capabilities behind your data center’s firewall.

[Oracle Cloud Infrastructure (OCI) GoldenGate](https://www.oracle.com/integration/goldengate/) is a managed service providing a real-time data mesh platform, which uses replication to keep data highly available, and enabling real-time analysis.

[Oracle Cloud Infrastructure Data Integration](https://www.oracle.com/integration/oracle-cloud-infrastructure-data-integration/) is a service to easily combine and transform data for data science and analytics. Design code-free data flows into data lakes and data marts.

[Oracle Service-Oriented Architecture (SOA)](https://www.oracle.com/integration/soa/) is a service that offers the ability to move existing, on-premises integrations and composite applications to the cloud as-is with Bring Your Own License (BYOL), and the ability to create modern integrations with Oracle Integration.

[Oracle Cloud Infrastructure Audit service](https://docs.oracle.com/en-us/iaas/Content/Audit/Concepts/auditoverview.htm) is a service that automatically records calls to all supported Oracle Cloud Infrastructure public application programming interface (API) endpoints as log events. Currently, all services support logging by Audit. Object Storage service supports logging for bucket-related events, but not for object-related events. Log events recorded by the Audit service include API calls made by the Oracle Cloud Infrastructure Console, Command Line Interface (CLI), Software Development Kits (SDK), your own custom clients, or other Oracle Cloud Infrastructure services.

[Oracle Cloud Cost Analysis](https://docs.oracle.com/en-us/iaas/Content/GSG/Concepts/costs.htm#Checking_Your_Balance_and_Usage) is a visualization tool that helps you track and optimize your Oracle Cloud Infrastructure spending, allows you to generate charts, and download accurate, reliable tabular reports of aggregated cost data on your Oracle Cloud Infrastructure consumption.

[Oracle Cloud Infrastructure (OCI) Logging](https://www.oracle.com/devops/logging/) is a service built on open standards, OCI Logging is an intuitive, centralized platform for all types of logs, such as audit, infrastructure, database and applications, which are needed for DevOps and security compliance. Oracle Cloud Infrastructure (OCI) Logging uses the Cloud Native Computing Foundation (CNCF) [fluentd]() agent for log ingestion and the CNCF CloudEvents standard for log events.

[Oracle Cloud Infrastructure Logging Analytics](https://www.oracle.com/manageability/logging-analytics/) is a machine learning-based cloud service that monitors, aggregates, indexes, and analyzes all log data from on-premises and multicloud environments.

[Oracle Cloud Infrastructure Monitoring](https://www.oracle.com/devops/monitoring/) is a service that helps helps organizations optimize the resource utilization and uptime of their infrastructure and applications. This service provides fine-grained, out-of-the-box metrics and dashboards, enabling DevOps, IT, and Site Reliability Engineers (SREs) with the real-time insights to respond to anomalies as they occur.

[Oracle Cloud Infrastructure Notifications](https://www.oracle.com/devops/notifications/) is a highly available, low-latency publish/subscribe (pub/sub) service that sends alerts and messages to [Oracle Functions](https://www.oracle.com/cloud-native/functions/), email, SMS, and message delivery partners, including Slack, PagerDuty, and ServiceNow. This service integrates with [Oracle Identity and Access Management](https://www.oracle.com/cloud/security/cloud-services/identity-access-cloud.html) for secure access, and delivers each message, even during traffic bursts.

[Oracle Cloud Resource Manager](https://www.oracle.com/devops/resource-manager/) is an Oracle-managed service that automates deployment and operations for all Oracle Cloud Infrastructure resources. Unlike Infrastructure-as-Code (IaC) offerings from other cloud vendors, the service is based on Terraform, a widely used, open source industry standard that allows DevOps engineers to develop and deploy their infrastructure anywhere.

[Oracle Service Connector Hub](https://www.oracle.com/devops/service-connector-hub/) is a service that helps cloud engineers manage and move data between Oracle Cloud Infrastructure (OCI) services and from OCI to third-party services. Unlike competing cloud offerings, Service Connector Hub provides a central place for describing, executing and monitoring data movements between services, such as Logging, [Object Storage](https://www.oracle.com/cloud/storage/object-storage.html), [Streaming](https://www.oracle.com/cloud-native/streaming/), [Logging Analytics](https://www.oracle.com/manageability/logging-analytics/) and [Monitoring](https://www.oracle.com/devops/monitoring/). It can also trigger [Functions](https://www.oracle.com/cloud-native/functions/) for lightweight data processing and [Notifications](https://www.oracle.com/devops/notifications/) to set up alerts.

[Oracle Domain Name System (DNS)](https://www.oracle.com/cloud/networking/dns/) is a distributed internet system that maps human-readable names (like www.Oracle.com) to IP addresses and serves as the first link in the customers’ digital supply chain.

[Oracle Cloud Infrastructure Email Delivery](https://www.oracle.com/cloud/networking/email-delivery.html) is a service that helps organizations reach their intended audiences by enabling them to send bulk email with high rates of successful inbox placement.

[Oarcle Cloud FastConnect](https://www.oracle.com/cloud/networking/fastconnect/) is a service that allows customers to connect directly to their Oracle Cloud Infrastructure (OCI) virtual cloud network via dedicated, private, high-bandwidth connections. Then, based on the amount of data, customers simply choose an appropriate port speed and pay a consistent, low price each month.

[Oracle Health Checks](https://www.oracle.com/cloud/networking/health-checks.html) is a service that provides the ability to monitor and alert on the availability of any public-facing service hosted in Oracle Cloud Infrastructure. Additionally, Oracle Health Checks is fully integrated with the Oracle DNS Traffic Management service to enable automated detection of service failures and trigger DNS failovers to ensure continuity of service when needed.

[Oracle Cloud Infrastructure (OCI) Flexible Load Balancing](https://www.oracle.com/cloud/networking/load-balancing/) is a service that enables customers to distribute web requests across a fleet of servers or automatically route traffic across fault domains, availability domains, or regions—yielding high availability and fault tolerance for any application or data source. The OCI Flexible Load Balancer primarily manages HTTP/HTTPS traffic and provides advanced routing features that distribute the requests based on the requests’ contents. While, the OCI Flexible Network Load Balancer performs at low latency, offering extreme performance.

[Oracle Cloud Service Gateway](https://www.oracle.com/cloud/networking/service-gateway/) is a service that provides a customer’s on-premises network with private access to Oracle Cloud services. Once connected to your VCN, Service Gateway allows secure, private connectivity to Oracle Cloud services like compute instances, cloud storage, containers, and databases.

[Oracle Cloud Infrastructure Traffic Management](https://www.oracle.com/cloud/networking/traffic-management.html) is a service that enables users to configure routing policies to serve intelligent responses to DNS queries. Oracle Traffic Management steering policies are used to steer DNS traffic across multiple public Oracle Cloud Infrastructure instances and other private and third-party assets.

[Oracle virtual cloud networks (VCNs)](https://www.oracle.com/cloud/networking/virtual-cloud-network/) is a service that provides customizable and private cloud networks in Oracle Cloud Infrastructure (OCI). Similar to a traditional data center network, the VCN provides customers with complete control over their cloud networking environment.

[Oracle Cloud Access Security Broker (CASB)](https://www.oracle.com/security/cloud-security/casb-cloud/) is a service to gain visibility and detect threats on the entire cloud stack for workloads and applications with Oracle CASB.

[Oracle Cloud Guard](https://www.oracle.com/security/cloud-security/cloud-guard/) is a service to gain a unified view of cloud security posture across Oracle Cloud Infrastructure customer tenants. Oracle Cloud Guard detects misconfigured resources and insecure activity across tenants and provides security administrators with the visibility to triage and resolve cloud security issues.

[Oracle Cloud Database security](https://www.oracle.com/security/database-security/) is a service that helps reduce the risk of a data breach and simplify compliance with database security solutions for encryption, key management, data masking, privileged user access controls, activity monitoring, and auditing.

[Oracle Cloud Infrastructure Identity and Access Management](https://www.oracle.com/security/cloud-security/identity-access-cloud/) is a service to help control who has access to Oracle Cloud Infrastructure resources, what type of access they have, and to which specific resources using easy to define policies with logical groups of users and resources.

[Oracle Identity Cloud Service](https://www.oracle.com/security/cloud-security/identity-cloud/) is a service that manages user access and entitlements across a wide range of cloud and on-premises applications and services using a cloud-native, identity as a service (IDaaS) platform.

[Oracle Cloud Infrastructure Vault](https://www.oracle.com/security/cloud-security/key-management/) is a service that centrally manage and maintain control of the encryption keys that protect enterprise data and the secret credentials used to securely access resources.

[Oracle Security Zones](https://www.oracle.com/security/cloud-security/security-zones/) is a service that automatically set up and enforce security policies for cloud compartments in Oracle Cloud Infrastructure. Oracle Security Zones includes a rich policy library and embed security best practices to enable cloud security posture management, so administrators can immediately ensure their compartments are secure.

[Oracle Web Application Firewall (WAF)](https://www.oracle.com/security/cloud-security/web-application-firewall/) is a service that protects applications from malicious and unwanted internet traffic with a cloud-based, PCI-compliant, global web application firewall service.

[Oracle Cloud Infrastructure (OCI) Archive Storage](https://www.oracle.com/cloud/storage/archive-storage.html) is a service to securely store any type of data in its native format. This cost-effective solution is highly durable and used for storing and managing encrypted data for long periods of time.

[Oracle Cloud Block Volumes](https://www.oracle.com/cloud/storage/block-volumes.html) is a service that provides customers reliable, high-performance block storage designed to work with a range of virtual machines and bare metal instances. With built-in redundancy, Block Volumes are persistent and durable beyond the lifespan of a virtual machine and can scale to 1 PB per compute instance.

[Oracle Cloud Infrastructure Data Transfer Appliance](https://www.oracle.com/cloud/storage/data-transfer.html) is a service that securely moves terabytes or petabytes data between on-premise data centers and the cloud. The service reduces data migration times from weeks or months to just hours and is available for data import to the cloud and data export from the cloud.

[Oracle Cloud Infrastructure (OCI) File Storage](https://www.oracle.com/cloud/storage/file-storage.html) is a fully managed elastic file system built for the cloud that enables customers to migrate their enterprise workloads to the cloud. Every file system scales automatically to accommodate the growth of up to 8 exabytes. Also, File Storage also offers snapshot and clone capabilities to simplify business continuity for enterprise applications.

[Oracle Cloud Infrastructure (OCI) Object Storage](https://www.oracle.com/cloud/storage/object-storage.html) is a service that enables customers to securely store any type of data in its native format.

[Oracle Cloud Infrastructure (OCI) Storage Gateway](https://www.oracle.com/cloud/storage/storage-gateway.html) is a service that helps extend on-premises application data to Oracle Cloud. Integration with OCI Object Storage and Network File Storage (NFS) compliance make it easy to securely move files to and from Oracle Cloud. Data is encrypted both at rest and in-transit and built-in data integrity checks provides protection.


## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/Bash-PowerShell-Guide/pulls).


## License

[Back to the Top](https://github.com/mikeroyal/Bash-PowerShell-Guide#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).





