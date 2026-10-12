<h1> Setting  up your Wazuh Server</h1>

 This step will be fairly easy because Wazuh's website contains an installation guide for anyone to view.

* Before continuing setting up your Wazuh Manager, make sure to install curl using the command:
```
sudo apt install curl
```

## Step 1: Wazuh Manager Installation 

Wazuh contains the installation command on their official installation guide.

<img width="1501" height="1359" alt="image" src="https://github.com/user-attachments/assets/9ab3144b-a02a-46e5-8986-93087106a8fa" />

Installation Syntax: 
```
curl -sO https://packages.wazuh.com/4.14/wazuh-install.sh && sudo bash ./wazuh-install.sh -a
```

Run the script and when it completes you will be granted the credentials to log in to your Wazuh dashboard.

<img width="2545" height="1297" alt="Screenshot 2026-10-12 125457" src="https://github.com/user-attachments/assets/3677dd7a-f09e-40fa-8058-531971150202" />

### Login Credentials:

Username: admin 

Password: [ Generated and displayed after installation ] 

<img width="2549" height="1301" alt="Screenshot 2026-10-12 130314" src="https://github.com/user-attachments/assets/496fc29c-bc79-4bcd-998b-440026285d27" />


### THE NEXT STEP IS INSTALLING WAZUH AGENTS 
