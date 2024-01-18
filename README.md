# How to Begin !!!


## Deploy app & infrastructure using Terraform and GithubAction.

### Pre-requiste:

#### For Code Repository :-

##### Create a account in Github & pull the source code
We will use Github action which comes under Github

----

##### For Infrastructure :-

Azure Account - For Infrastructure & Deployment
Create Resources and .....

----

##### For Repository :-

Use Docker Hub & create account 

----

##### To test the application on local machine, you need to have below packages:-

Visual Studio - Code Editor

Docker Desktop 

Minikube

JDK 8

Clojure

Leiningen

Terraform



### How code CI/CD works in our project

![Infra_Problem](https://github.com/nik-god/T2S/assets/53073638/aefe9df7-596e-4888-b195-cad95c5781a4)



### Steps To follow

#### Azure

Step 1 : Register an App in Azure under App Registrations [twapp]
Step 2 : Create a Secret for that application.
Step 3 : Copy Client ID , Tenant ID , Client Secret and Subscription ID.
Step 4 : Add copied IDs from Step 3 in GitHub Repository Secrets under repo Settings.
Step 5 : Add Docker Hub Credentials in Github Repository Secrets under repo Settings.
Step 6 : Create storage account & Container in Azure to store Terraform state file.
Step 7 : Add Azure Stirage Secret to ithub Repository Secrets under repo Settings.

Github is used for CI/CD






