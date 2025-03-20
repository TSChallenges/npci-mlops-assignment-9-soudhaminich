# Kubernetes Exercise in KillerKoda Playground / Codepace

In this assignment, you will be creating:

* A Pod with an NGINX container
* A Deployment with 4 replicas and self-healing
* ClusterIP and NodePort Services
* Persistent Volume (PV) and Persistent Volume Claim (PVC)
* Assigning a PVC to a Pod


## Steps to Follow if you are using code space

- This GitHub repository will be accessible to you once you accept the Assignment.
- You have to work directly in this GitHub repository. It is like your own copy of the original repository.
- Start a new Codespace. It will have Kubernetes preinstalled.

  Note that it may take around 5 minutes for the Codespace to start after you click on "Create Codespace".

- If you are using Kubernetes from your system then below are the prerequisites:
  *   **GitHub Account** (for code submission).
  *   **Docker and Docker Compose** installed.
  *   **kind CLI** (for running local Kubernetes cluster) [https://kind.sigs.k8s.io/docs/user/quick-start/].
  *   **kubectl CLI** (for deploying updates to the Kubernetes cluster) [https://kubernetes.io/docs/tasks/tools/].

- Do not edit anything in `.devcontainer` and `cli` folders.


## **Task 1: Create a Pod with an NGINX Image** [2 marks]
* Open the KillerKoda playground or create a codespace with this repository (this repo is configured with kubernetes)
* Create a file named nginx-pod.yaml.
* Apply the pod.
* List the running pods.

## **Task 2: Create a Deployment with 4 Replicas** [2 marks]

* Create a file named nginx-deployment.yaml.
* Apply the deployment.
* List the pods and confirm that 4 replicas are running.

## **Task 2.1: Test Self-Healing (Delete a Pod)**

* Delete one of the pods.
* Check if Kubernetes recreates the pod (self-healing).

## **Task 3.1: Create a ClusterIP Service** [1 mark]

* Create a file named nginx-clusterip-service.yaml.
* Apply the service.
* Test the ClusterIP
* Curl the service from inside the cluster.

## **Task 3.2: Create a NodePort Service** [1 mark]

* Create a file named nginx-nodeport-service.yaml.
* Apply the service.
* Test the NodePort service.

## **Task 4.1: Create a Persistent Volume** (PV)(1gb) with RWO access [1 mark]

* Create a file named nginx-pv.yaml.
* Apply the PV.
* Check PV status.

## **Task 4.2: Create a Persistent Volume Claim** (PVC)(500mb) [1 mark]

* Create a file named nginx-pvc.yaml.
* Apply the PVC.
* Check PVC status.

## **Task 5: Assign PVC to a Pod** [2 marks]

* Create a file named nginx-pvc-pod.yaml.
* Apply the pod.
* Check pod status.
* Check volume mounting inside the pod.

## **Evaluation / Submission Criteria:**

Evaluation is based on the files and images you submit and you are required to complete the following Kubernetes exercise in the KillerKoda playground and submit the necessary files(.yml files) and screenshots(commands) as proof of completion.




