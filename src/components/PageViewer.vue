<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col p-3 bg-warning text-light col-md-2">
        <span class="badge rounded-pill bg-warning" style="font-size: medium;">RAM IT <br /> DevOps
          Instructor</span>
      </div>
      <div class="col p-3 bg-warning text-light rounded text-center col-md-6">
        <span class="badge rounded-pill bg-warning" style="font-size: medium;">
          DevOps New Batch <br />
          December 9th (Thrusday) <br />
          7:00 PM to 8:30 PM IST
        </span>
      </div>
      <div class="col p-3 bg-warning text-light">
        <span class="badge rounded-pill bg-warning float-end" style="font-size: medium;">WhatsApp <br />
          +9999988888</span>
      </div>
    </div>
  </div>


  <div id="demo" class="carousel slide" data-bs-ride="carousel">


    <div class="carousel-indicators">
      <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="3"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="4"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="5"></button>
    </div>


    <div class="carousel-inner">

      <div class="carousel-item active">
        <img src="kube.jpg" class="d-block" style="width:100%">
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>

      <div class="carousel-item">
        <img src="jenkins.jpg" class="d-block" style="width:100%">
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>

      <div class="carousel-item">
        <img src="ansible.jpg" alt="Chicago" class="d-block" style="width:100%">
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>

      <div class="carousel-item">
        <img src="terraform.jpg" class="d-block" style="width:100%">
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>

      <div class="carousel-item">
        <img src="prometheus.jpg" class="d-block" style="width:100%">
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>

      <div class="carousel-item">
        <img src="grafana.jpg" class="d-block" style="width:100%">
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>
    </div>


    <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
      <span class="carousel-control-next-icon"></span>
    </button>
  </div>

  <div class="m-4 text-center">
    <h4 class="ms-4">DevOps Syllabus</h4>
  </div>
    <div class="container d-flex mt-4 p-4">
      <div class="card mb-3" style="max-width:680px;">
      <div class="row g-0">
        <div class="col-md-2">
          <img src="devops.png" class="img-fluid rounded-start m-2" alt="...">
        </div>
        <div class="col-md-10">
          <div class="card-body">
            <h5 class="card-title">
              INTRODUCTION TO DEVOPS
            </h5>
            <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item p-0">What is Devops?</li>
                  <li class="list-group-item p-0">Why Devops?</li>
                  <li class="list-group-item p-0">Devops Tools</li>
                  <li class="list-group-item p-0">Differences between traditional methodologies and DEVOPS-approach</li>
                  <li class="list-group-item p-0">Big Picture of CI/CD Devops Delivery Pipeline</li>
                </ul>
            </p>            
          </div>
        </div>
      </div>
    </div>
      <div class="card mb-3" style="max-width:680px;">
        <div class="row g-0">
          <div class="col-md-2">
            <img src="linux.png" class="img-fluid rounded-start m-2" alt="...">
          </div>
          <div class="col-md-10">
            <div class="card-body">
              <h5 class="card-title">OPERATING SYSTEM & LINUX BASICS</h5>
              <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item p-0">Introduction to Operating Systems</li>
                  <li class="list-group-item p-0">Introduction to Virtual Machines</li>
                  <li class="list-group-item p-0">Linux File Systems</li>
                  <li class="list-group-item p-0">Introduction to Command Line Interface</li>
                  <li class="list-group-item p-0">Basic Linux Commands</li>
                  <li class="list-group-item p-0">Package Manager - Installing Software in Linux</li>
                  <li class="list-group-item p-0">Vim Text Editor</li>
                  <li class="list-group-item p-0">Users and Permissions</li>
                  <li class="list-group-item p-0">Shell Scripting</li>
                  <li class="list-group-item p-0">Environment Variables</li>
                  <li class="list-group-item p-0">SSH -Secure Shell</li>
                </ul>
              </p>              
            </div>
          </div>
        </div>
      </div>
    </div> 

  <div class="container d-flex mt-4 p-4">
      <div class="card mb-3" style="max-width:680px;">
      <div class="row g-0">
        <div class="col-md-2">
          <img src="git.png" class="img-fluid rounded-start m-2" alt="...">
        </div>
        <div class="col-md-10">
          <div class="card-body">
            <h5 class="card-title">
              VERSION CONTROL SYSTEM - GIT
            </h5>
            <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item p-0">Introduction to VCS</li>
                  <li class="list-group-item p-0">Types of VCS</li>
                  <li class="list-group-item p-0">Difference between CVCS and DVCS</li>
                  <li class="list-group-item p-0">What is GIT</li>
                  <li class="list-group-item p-0">GIT Architecture</li>
                  <li class="list-group-item p-0">GIT installation on Windows and Linux</li>
                  <li class="list-group-item p-0">GIT commands</li>
                  <li class="list-group-item p-0">Working with GIT</li>
                  <li class="list-group-item p-0">Creating repository</li>
                  <li class="list-group-item p-0">Cloning repository</li>
                  <li class="list-group-item p-0">Committing the changes</li>
                  <li class="list-group-item p-0">Fetch, pull and remote</li>
                  <li class="list-group-item p-0">Branching Strategy in GIT</li>
                  <li class="list-group-item p-0">Creating the Branches</li>
                  <li class="list-group-item p-0">Switching the branches</li>
                  <li class="list-group-item p-0">Merging the branches</li>
                  <li class="list-group-item p-0">Git reset</li>
                  <li class="list-group-item p-0">Git rebase</li>
                  <li class="list-group-item p-0">Git stash</li>
                  <li class="list-group-item p-0">Working with GitHub</li>
                </ul>
            </p>            
          </div>
        </div>
      </div>
    </div>
      <div class="card mb-3" style="max-width:680px;">
        <div class="row g-0">
          <div class="col-md-2">
            <img src="jenkinslogo.png" class="img-fluid rounded-start m-2" alt="...">
          </div>
          <div class="col-md-10">
            <div class="card-body">
              <h5 class="card-title">CONTINUOUS INTEGRATION - JENKINS</h5>
              <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item p-0">What is Jenkins?</li>
                  <li class="list-group-item p-0">Continuous Integration with Jenkins</li>
                  <li class="list-group-item p-0">Java installation and configuration</li>
                  <li class="list-group-item p-0">Exploring Jenkins Dashboard</li>
                  <li class="list-group-item p-0">Creating jobs in Jenkins</li>
                  <li class="list-group-item p-0">Running the Jobs</li>
                  <li class="list-group-item p-0">Setting up the global environment variables for Jobs</li>
                  <li class="list-group-item p-0">Adding and updating Plugins</li>
                  <li class="list-group-item p-0">Disabling and deleting jobs</li>
                  <li class="list-group-item p-0">Different authorization strategies in Jenkins</li>
                  <li class="list-group-item p-0">RBAC strategy in Jenkins</li>
                  <li class="list-group-item p-0">Best Practices for Jenkins</li>
                  <li class="list-group-item p-0">Plugin Management in Jenkins</li>
                  <li class="list-group-item p-0">Triggering email notifications in Jenkins</li>
                  <li class="list-group-item p-0">Scheduling jobs automatically in Jenkins</li>
                  <li class="list-group-item p-0">Poll SCM and web hooks in Jenkins</li>
                  <li class="list-group-item p-0">Compile, test and deploy jobs in Jenkins</li>
                  <li class="list-group-item p-0">Building Delivery Pipeline in Jenkins with java Maven Project</li>
                  <li class="list-group-item p-0">Create complete pipeline in Jenkins</li>
                  <li class="list-group-item p-0">Master Slave Architecture in Jenkins</li>
                  <li class="list-group-item p-0">Credentials in Jenkins</li>
                  <li class="list-group-item p-0">Adding Windows slave and run test job on windows</li>
                  <li class="list-group-item p-0">Adding Linux slave and configuring the job on Linux ec2 instance</li>
                  <li class="list-group-item p-0">Pipeline and Multi branch jobs in Jenkins</li>
                  <li class="list-group-item p-0">Pipeline as code in Jenkins (Jenkins file) using groovy script</li>
                  <li class="list-group-item p-0">Deploy to ec2-instance on AWS using Jenkins Pipeline</li>
                </ul>
              </p>              
            </div>
          </div>
        </div>
      </div>
    </div>

    <!---->
    <div class="container d-flex mt-4 p-4">
      <div class="card mb-3" style="max-width:680px;">
        <div class="row g-0">
          <div class="col-md-2">
            <img src="docker.png" class="img-fluid rounded-start m-2" alt="...">
          </div>
          <div class="col-md-10">
            <div class="card-body">
              <h5 class="card-title">CONTAINERIZATION USING DOCKER</h5>
              <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item p-0">What is container?</li>
                  <li class="list-group-item p-0">Containerization vs Virtualization</li>
                  <li class="list-group-item p-0">Docker Container Vs Vms</li>
                  <li class="list-group-item p-0">Docker Images</li>
                  <li class="list-group-item p-0">Docker Architecture</li>
                  <li class="list-group-item p-0">Docker Installation on Linux</li>
                  <li class="list-group-item p-0">Understanding the Docker components</li>
                  <li class="list-group-item p-0">Working with Images</li>
                  <li class="list-group-item p-0">Docker Containers</li>
                  <li class="list-group-item p-0">Docker Networking</li>
                  <li class="list-group-item p-0">Docker Files for building our own images</li>
                  <li class="list-group-item p-0">Docker Volumes for data persistency</li>
                  <li class="list-group-item p-0">Development and Deployment with Docker containers</li>
                  <li class="list-group-item p-0">Building Docker image from Jenkins job</li>
                  <li class="list-group-item p-0">Pushing own images to Docker hub</li>
                  <li class="list-group-item p-0">Pushing own images to ECR on AWS</li>
                  <li class="list-group-item p-0">Automating Docker image push to Docker hub/ECR on AWS from Jenkinsfile</li>
                  <li class="list-group-item p-0">What is Docker Compose?</li>
                  <li class="list-group-item p-0">Writing Docker Compose File</li>
                  <li class="list-group-item p-0">Deploying Micro service app with Docker compose</li>
                  <li class="list-group-item p-0">Configuring volumes with compose file</li>
                  <li class="list-group-item p-0">Automate deploying from Jenkins Pipeline to EC2 Instance Using Docker run</li>
                  <li class="list-group-item p-0">Automate deploying from Jenkins Pipeline to EC2 Instance Using Docker-Compose</li>
                  <li class="list-group-item p-0">Container Orchestrator tool Docker Swarm</li>
                  <li class="list-group-item p-0">High availability of app , Scaling and Load balancing on Docker Swarm Cluster</li>
                  <li class="list-group-item p-0">Networking in Docker swarm</li>
                  <li class="list-group-item p-0">Creating custom overlay networks in Docker swarm cluster</li>
                  <li class="list-group-item p-0">Deploying multiple containers on swarm cluster via Docker compose</li>
                </ul>
              </p>              
            </div>
          </div>
        </div>
      </div>
      <div class="card mb-3" style="max-width:680px;">
      <div class="row g-0">
        <div class="col-md-2">
          <img src="kuberneteslogo.png" class="img-fluid rounded-start m-2" alt="...">
        </div>
        <div class="col-md-10">
          <div class="card-body">
            <h5 class="card-title">
              CONTAINER ORCHESTRATOR - KUBERNETES
            </h5>
            <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item p-0">Introduction to Kubernetes</li>
                  <li class="list-group-item p-0">Kubernetes Architecture</li>
                  <li class="list-group-item p-0">Exploring your Cluster</li>
                  <li class="list-group-item p-0">Understanding YAML configuration in kubernetes</li>
                  <li class="list-group-item p-0">Creating a pod object in kubernetes</li>
                  <li class="list-group-item p-0">Creating a Deployment in Kubernetes using YAML Preview</li>
                  <li class="list-group-item p-0">Creating a Service Object in Kubernetes</li>
                  <li class="list-group-item p-0">Creating Headless service, Node Port, Load balancer Services</li>
                  <li class="list-group-item p-0">Creating secrets and configmaps</li>
                  <li class="list-group-item p-0">Working with Daemon Sets</li>
                  <li class="list-group-item p-0">Deploying database application using statefulsets</li>
                  <li class="list-group-item p-0">Working with Persistent Volumes, Persistent volume claims</li>                 
                  <li class="list-group-item p-0">Using Rolling Updates in Kubernetes</li>
                  <li class="list-group-item p-0">Blue Green Deployments in Kubernetes</li>
                  <li class="list-group-item p-0">Canary Deployment in Kubernetes</li>
                  <li class="list-group-item p-0">Helm Package manager for Kubernetes</li>
                  <li class="list-group-item p-0">Deploying Kubernetes Dashboard with Helm</li>
                  <li class="list-group-item p-0">Installing Prometheus and grafana on kubernetes cluster with Helm</li>
                  <li class="list-group-item p-0">Monitoring Kubernetes cluster with Prometheus</li>
                  <li class="list-group-item p-0">Deploying micro service application using statefulsets and Persistent volumes</li>
                </ul>
            </p>            
          </div>
        </div>
      </div>
    </div>      
    </div> 

    
    <!---->
    <div class="container d-flex mt-4 p-4">
      <div class="card mb-3" style="max-width:680px;">
        <div class="row g-0">
          <div class="col-md-2">
            <img src="ansiblelogo.png" class="img-fluid rounded-start m-2" alt="...">
          </div>
          <div class="col-md-10">
            <div class="card-body">
              <h5 class="card-title">CONFIGURATION MANAGEMENT - ANSIBLE</h5>
              <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item p-0">Introduction to Ansible</li>
                  <li class="list-group-item p-0">Ansible Architecture</li>
                  <li class="list-group-item p-0">Push configuration in Ansible</li>
                  <li class="list-group-item p-0">Installation of Ansible</li>
                  <li class="list-group-item p-0">Adhoc commands in Ansible</li>
                  <li class="list-group-item p-0">Playbooks in Ansible</li>
                  <li class="list-group-item p-0">Modules in Ansible</li>
                  <li class="list-group-item p-0">Roles in Ansible</li>
                  <li class="list-group-item p-0">Using Roles from Ansible Galaxy</li>
                  <li class="list-group-item p-0">Creating our own Roles</li>
                  <li class="list-group-item p-0">Deploying Docker container with Ansible</li>
                  <li class="list-group-item p-0">Deploying Docker compose with Ansible</li>
                  <li class="list-group-item p-0">Complete CI/CD on Jenkins with Ansible</li>
                </ul>
              </p>              
            </div>
          </div>
        </div>
      </div>
      <div class="card mb-3" style="max-width:680px;">
      <div class="row g-0">
        <div class="col-md-2">
          <img src="terraformlogo.png" class="img-fluid rounded-start m-2" alt="...">
        </div>
        <div class="col-md-10">
          <div class="card-body">
            <h5 class="card-title">
              INFRASTRUCTURE AS CODE WITH - TERRAFORM
            </h5>
            <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item p-0">Introduction to Terraform</li>
                  <li class="list-group-item p-0">Install Terraform</li>
                  <li class="list-group-item p-0">Terraform Providers</li>
                  <li class="list-group-item p-0">Resources and Data Sources</li>
                  <li class="list-group-item p-0">Change and destroy terraform resources</li>
                  <li class="list-group-item p-0">Terraform state commands</li>
                  <li class="list-group-item p-0">Output values in Terraform</li>
                  <li class="list-group-item p-0">Variables in Terraform</li>
                  <li class="list-group-item p-0">Environment variables in Terraform</li>
                  <li class="list-group-item p-0">Version controlling Terraform files with git</li>
                  <li class="list-group-item p-0">Automate Provisioning Ec2 instance on AWS with Terraform</li>
                  <li class="list-group-item p-0">Modules in Terraform</li> 
                  <li class="list-group-item p-0">Complete CI/CD on Jenkins with Terraform</li>
                  <li class="list-group-item p-0">Automate Provisioning of EKS cluster on AWS with Terraform</li>
                </ul>
            </p>            
          </div>
        </div>
      </div>
    </div>      
    </div> 

 <!---->
 <div class="container d-flex mt-4 p-4">
      <div class="card mb-3" style="max-width:680px;">
        <div class="row g-0">
          <div class="col-md-2">
            <img src="prometheuslogo.png" class="img-fluid rounded-start m-2" alt="...">
          </div>
          <div class="col-md-10">
            <div class="card-body">
              <h5 class="card-title">PROMETHEUS</h5>
              <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item p-0">What is Prometheus?</li>
                  <li class="list-group-item p-0">Prometheus Architecture</li>
                  <li class="list-group-item p-0">Prometheus Installation</li>
                  <li class="list-group-item p-0">Monitoring container metrics with Prometheus</li>
                  <li class="list-group-item p-0">Prometheus UI</li>
                  <li class="list-group-item p-0">Alerting rules in Prometheus</li>
                  <li class="list-group-item p-0">Monitoring Kubernetes cluster with Prometheus</li>
                </ul>
              </p>              
            </div>
          </div>
        </div>
      </div>
      <div class="card mb-3" style="max-width:680px;">
      <div class="row g-0">
        <div class="col-md-2">
          <img src="grafanalogo.png" class="img-fluid rounded-start m-2" alt="...">
        </div>
        <div class="col-md-10">
          <div class="card-body">
            <h5 class="card-title">GRAFANA</h5>
            <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item p-0">Grafana dashboard for Prometheus metrics</li>
                  <li class="list-group-item p-0">Grafana dashboard for kubernetes clusters</li>
                </ul>
            </p>            
          </div>
        </div>
      </div>
    </div>      
    </div> 
</template>

<script>
export default {
  props: ['page']
}    
</script>
