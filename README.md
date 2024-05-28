# VM Launch Guide

This repository contains comprehensive guides for launching virtual machines (VMs) across three major cloud platforms: AWS EC2, Azure VM, and Google Cloud Platform (GCP) VM. Follow the steps below and refer to the accompanying video for a live implementation of each process.

## Platforms Covered
- **AWS EC2 Launch**
- **Azure VM Launch**
- **Google Cloud Platform VM Launch**

## AWS EC2 Launch

### Steps to Launch an Amazon EC2 Instance:

1. **Open Amazon EC2 Console:**
   - Navigate to the [Amazon EC2 console](https://console.aws.amazon.com/ec2/).
   - Click `Launch Instance` to create and configure your virtual machine.

2. **Configure Your Instance:**
   - **Choose an Amazon Machine Image (AMI):** AMIs are preconfigured server templates that include an operating system and can also include applications and application servers.
   - **Choose an Instance Type:** Instance types vary in CPU, memory, storage, and networking capacity. Select the appropriate mix for your applications.
   - **Review Configuration:** Check the selected configuration, storage, tagging, and security settings for your instance.

3. **Create and Use a Key Pair:**
   - **Key Pair Selection:** Choose an existing key pair or create a new one.
   - **Create a New Key Pair:** 
     - Name the key pair `MyKeyPair`.
     - Click the `Download Key Pair` button.
   - **Secure Your Key:** Store the downloaded `MyKeyPair` key in a secure location. Losing your key means losing access to your instance, while unauthorized access to your key allows others to access your instance.

4. **Connect to Your Instance:**
   - Use SSH to securely access your Linux instance.

5. **Terminate Your Instance:**
   - Go to the console, select the VM, and under `Actions`, choose `Terminate`.

## Azure VM Launch

### Steps to Launch an Azure VM:

1. **Open Azure Portal:**
   - Navigate to the [Azure Portal](https://portal.azure.com/).
   - Click `Create a resource` and select `Virtual Machine`.

2. **Configure Your VM:**
   - **Basics:** Choose your subscription, resource group, and enter instance details (name, region, availability options).
   - **Image:** Select an operating system image.
   - **Size:** Choose a VM size based on CPU, memory, and storage requirements.
   - **Administrator Account:** Create an admin username and password or use SSH public key.

3. **Disks Configuration:**
   - Select the OS disk type (SSD or HDD).
   - Optionally add data disks.

4. **Networking Configuration:**
   - Configure the network settings including virtual network, subnet, public IP, and security group.

5. **Management, Monitoring, and Tags:**
   - Configure management and monitoring options.
   - Optionally add tags to organize resources.

6. **Review and Create:**
   - Review your configuration settings.
   - Click `Create` to deploy the VM.

7. **Connect to Your VM:**
   - Use SSH or RDP to connect to your instance.

8. **Delete Your VM:**
   - Go to the portal, select your VM, and click `Delete`.

## Google Cloud Platform VM Launch

### Steps to Launch a Google Cloud VM:

1. **Open Google Cloud Console:**
   - Navigate to the [Google Cloud Console](https://console.cloud.google.com/).
   - Click `Navigation Menu` and select `Compute Engine` > `VM instances`.

2. **Create a New VM Instance:**
   - Click `Create Instance` to configure your virtual machine.

3. **Configure Your VM:**
   - **Name and Region:** Enter a name and select a region and zone.
   - **Machine Configuration:** Choose a machine type with the desired CPU and memory.
   - **Boot Disk:** Select an operating system image or a custom image.

4. **Identity and API Access:**
   - Configure service account and API access.

5. **Firewall and Security:**
   - Configure firewall rules to allow HTTP/HTTPS traffic if needed.

6. **Create and Download SSH Keys:**
   - Generate and download SSH keys to securely connect to your instance.

7. **Create the VM:**
   - Review your settings and click `Create` to deploy the VM.

8. **Connect to Your VM:**
   - Use SSH from the console or your local terminal.

9. **Delete Your VM:**
   - Go to the console, select your VM, and click `Delete`.

## Follow the Video Tutorial
For a detailed, step-by-step walkthrough, watch the video tutorial provided in this repository.

## Contributing
We welcome contributions from the community! If you have suggestions for improvements or additional features, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss your proposed modifications.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments
We would like to thank the developers and the open-source community for their invaluable contributions.

---
