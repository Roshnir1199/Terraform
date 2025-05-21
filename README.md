# Personal Website Deployment on Google Cloud using Terraform

This project demonstrates how to create and deploy a personal static website (HTML, CSS, JavaScript) to Google Cloud Platform (GCP) using Terraform.

## Steps to deploy the website

### 1️⃣ Install Required Tools  
Install **Terraform** and the **Google Cloud SDK (gcloud CLI)** on your system. These tools are used to write infrastructure as code and interact with GCP.

---

### 2️⃣ Authenticate Google Cloud  
Login to the GCP account using the gcloud CLI and set up authentication for Terraform. This allows Terraform to securely access your GCP project.

---

### 3️⃣ Create a GCP Project and Enable Billing  
Create a new GCP project and ensure billing is enabled. Also, enable required APIs like Compute Engine.

---

### 4️⃣ Set Up Terraform Project Structure  
Organize the Terraform files into a project directory named "terraform_deploy" with configuration files for provider settings, resource definitions, variables, and outputs.

---

### 5️⃣ Create a Personal Website  
Build a simple personal website using HTML, CSS, and JavaScript. Include basic styling and interactivity. And finally place these files in your Terraform startup script.

---

### 6️⃣ Write Terraform Configuration  
Defined the infrastructure resources needed:
- A VM instance running a Linux OS
- Startup script to install Apache and host the website
- Network interface and external IP

---

### 7️⃣ Deploy with Terraform  
Run Terraform commands to initialize the project and apply the configuration. This will create the VM and deploy the website.

---

### 8️⃣ Configure Firewall Rules  
Allow traffic on port 80 (HTTP) to access the website.

---

### 9️⃣ Access the Deployed Website  
Copy the external IP from the Terraform output and open it in a web browser to view the live website.
