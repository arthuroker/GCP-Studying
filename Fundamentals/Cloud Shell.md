**Definition**: fully-managed browser based cli in the Google cloud console

**Features**:
1) Google Cloud SDK, including gCloud, pre-installed
2) 5GB of persistent storage in the home directory
3) Security and software patches are automatically managed
4) Cloud Shell Editor (code editor)


###### **Storing Scripts for Persistence**

Home Directory = ~/

Common subdirectories:
-/tools =store utility scripts or resources
-/projects = store project specific files or source code
-/bin = special, part of default path, .exe can be run without outlining the whole path

**DevOps Use Case**:

**Benefits**: No external IP or SSH required, the shell communicates with GCP resources internally in Google's network

Good for security