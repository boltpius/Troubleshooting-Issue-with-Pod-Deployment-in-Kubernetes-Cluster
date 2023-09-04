# Troubleshooting-Issue-with-Pod-Deployment-in-Kubernetes-Cluster

In this task, I was assigned to troubleshoot an issue with a pod deployment in a Kubernetes cluster. The pod, named "webserver", was failing to come up and generating errors. After thorough investigation, I identified that the root cause of the issue was an incorrect image being used by the pod, "httpd:latests", which resulted in an error when Kubernetes attempted to pull it from the Docker registry.
To resolve the issue, I updated the pod's configuration to use the correct image version. Additionally, there was a sidecar container named "sidecar-container" that was utilizing the "ubuntu:latest" image. I ensured that both containers were properly configured and addressed any other errors that were impeding the successful deployment of the pod.

With the necessary corrections made, the pod was successfully deployed and functioning as expected in the Kubernetes cluster. I have attached a screenshot showcasing the completed task, demonstrating the pod's successful deployment.
![FC2C6883-D00D-402F-BEEE-3D7170812F34](https://github.com/boltpius/Troubleshooting-Issue-with-Pod-Deployment-in-Kubernetes-Cluster/assets/127052041/a1b5f5d0-a143-4006-b13a-6472cb68eb3f)
<img width="1509" alt="Screenshot 2023-09-04 at 08 05 10" src="https://github.com/boltpius/Troubleshooting-Issue-with-Pod-Deployment-in-Kubernetes-Cluster/assets/127052041/24cb4b1a-a022-45b1-8b16-8d833905f61c">
<img width="1509" alt="Screenshot 2023-09-04 at 08 05 40" src="https://github.com/boltpius/Troubleshooting-Issue-with-Pod-Deployment-in-Kubernetes-Cluster/assets/127052041/769809a1-c331-4e04-816e-ae9c3f0c1c85">
