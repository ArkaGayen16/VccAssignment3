# Auto-Scaling from Local VM to GCP

## Overview  
This project demonstrates the process of auto-scaling from a local Virtual Machine (VM) to Google Cloud Platform (GCP) when resource usage exceeds 75%. It involves monitoring system resources on the local VM, triggering auto-scaling through GCP CLI, and deploying new VM instances on GCP to handle the increased load.

## System Requirements  
- VirtualBox or VMware for local VM setup  
- Google Cloud SDK (gcloud CLI)  
- Python (for custom monitoring script)  
- GCP account

## Setup Steps  
1. Set up a local VM using VirtualBox or VMware.  
2. Install the Google Cloud SDK and authenticate.  
3. Create a custom Python script to monitor CPU and memory usage.  
4. Configure the system to trigger auto-scaling when usage exceeds 75%.  
5. Use GCP CLI to create new VM instances on GCP.

## Testing  
- Test resource monitoring with the custom Python script.  
- Verify VM creation on GCP when load exceeds 75%.  
- Ensure workloads are distributed across local and cloud VMs.

## Conclusion  
This project demonstrates an automated auto-scaling solution that dynamically shifts workloads from local infrastructure to the cloud, ensuring optimal performance without manual intervention.