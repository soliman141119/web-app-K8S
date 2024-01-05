# web-app-K8S
This repository contains the deployment and service files for a web app built with HTML, CSS, and JavaScript and deployed using Kubernetes.
## Description

This web app is designed to [We are your one-stop shop for all things fashionable and comfortable. At TPM Store, we pride ourselves on curating a wide selection of high-quality clothing made from the softest, most breathable fabrics.

Whether you're looking for the perfect t-shirt, cozy sweatpants, or lounge-worthy joggers, we have an array of styles sure to please. All of our clothing is designed with comfort in mind. You'll love how lightweight and flexible our fabrics feel, allowing you to move freely throughout your day.].

## Prerequisites

Before deploying the web app with Kubernetes, make sure you have the following prerequisites:

- A running Kubernetes cluster.
- `kubectl` command-line tool installed and configured to connect to your Kubernetes cluster.
- Basic knowledge of HTML, CSS, and JavaScript.
- [List any additional prerequisites or dependencies here]

## Deployment

To deploy the web app with Kubernetes, follow these steps:
1. Clone this repository to your local machine:
   ```bash
    git clone <repository-url>

  
2. Navigate to the deployment directory:
   ```bash
     cd web-app-K8S

3. Modify the deployment.yaml file to customize the deployment configuration. Update the image name, container ports, resource limits, etc., based on your requirements.
4. Apply the deployment to your Kubernetes cluster:
    ```bash
     kubectl apply -f deployment.yaml
5.Verify that the deployment is running:
   ```bash
   kubectl get deployments
  ```
6.Expose the deployment as a service:
   ```bash
   kubectl apply -f service.yaml
  ````
7.Verify the service is created and obtain the service URL:
   ```bash
    kubectl get services
   ```
8.Access the web app by opening a web browser and navigating to the service URL obtained in the previous step.


   
