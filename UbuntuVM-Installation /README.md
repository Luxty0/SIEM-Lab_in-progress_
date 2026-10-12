<h1>Setting up your Ubuntu Enviroment<h1>

  

## Step 1: Install VMware Workstation Pro



* Visit webpage https://www.vmware.com/ and install VMware Workstation Pro 


<img width="1295" height="848" alt="image" src="https://github.com/user-attachments/assets/15c282c7-e8d7-4fb6-81dc-dc289c0a32ce" />






* After selecting the option to see desktop hypervisors and then download now, you will be redirected to a different website where you will need to login/register for broadcom.

<img width="1798" height="728" alt="image" src="https://github.com/user-attachments/assets/db5be4dd-940d-460f-8753-3cceefde9e05" />






* Press on the link that says HERE highlighted in blue, then scroll down and look for VMware Workstation Pro

<img width="1586" height="665" alt="image" src="https://github.com/user-attachments/assets/4c8a1ed1-4243-4fcb-ae29-351e071154c1" />





* Select the most recent updated version that is compatible with your Desktop OS

<img width="1772" height="703" alt="image" src="https://github.com/user-attachments/assets/48486662-d5a4-46eb-b995-2b103521bfee" />

  

## Step 2: Download ISO image of Ubuntu/Linux and create a VM 

* Visit https://ubuntu.com/download and select the desktop version to download

<img width="1893" height="908" alt="image" src="https://github.com/user-attachments/assets/89f3e595-0d96-4e86-b3e0-3881662bfbce" />




* Open up your VMware, click on File on the top left to create a new VM with ubuntu installed.


<img width="728" height="701" alt="image" src="https://github.com/user-attachments/assets/4f71ecb1-a6d9-4414-8e30-cb859996995e" />




* To finish off with your fresh installation of Ubuntu, apply the following commands on the terminal to make sure ubuntu is updated 


```bash
sudo apt update
sudo apt upgrade -y
```

### The next step is to install our Wazuh Manager/Dashboard and Agents ! 





