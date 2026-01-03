###### **Components of the Google Cloud SDK**

**gcloud**: cli interface

**Client libraries**: libraries for different programming languages

**Service specific CLIs**: 
bq = Big Query
gsutil = interacting with Cloud Storage

###### **gCloud**

Example commands:

1) gcloud app deploy
	Deploys an app to App Engine

2) gcloud compute instances list
	Lists all compute engine VMs

3) gcloud projects create my-project-id --name="project name"
	Creates a new project called "project name"


###### **Configurations**

**Motivation**: without configs, you would have to specify every flag value. Instead, you can create a config designed to work in one project, and set all the values you know will be the same for everything you do in the project. Also you can set the value of what project you want to create any service for. 

Can set up gCloud configuration for common usage patterns (i.e production configuration)

**Create command**: 
-gcloud config configurations create {name}

**Setting properties commands**
-gcloud set compute/region {region}

**Activating a configuration**:
-gcloud config configurations activate {name}

**Common gCloud commands**:

-gcloud init 
	Guides you through setting up gCloud with default settings
	You can configure a new or existing project

-gcloud projects list
	Lists all the projects associated with your Google account

-gcloud service list
	Shows all the APIs and service enabled in your current project

-gcloud projects describe
	Provide metadata about specified project

-gcloud compute instances list
	Lists all the vm instances running in your project

-gcloud config configurations create/activate
	Mentioned earlier