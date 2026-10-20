
<h1>Deploying a new Agent to Endpoints</h1>

Adding agents will be done through the Wazuh Dashboard



| Agent  | OS|
|---------|----------|
| Agent 1 | Windows 11 |
| Agent 2 | Ubuntu Desktop| 


# Windows Agent: 

## Step 1: Deploy new Agent

<img width="1306" height="716" alt="image" src="https://github.com/user-attachments/assets/ccb903fc-be99-46ea-87e6-ae537ac1a5b0" />

<img width="2471" height="1122" alt="image" src="https://github.com/user-attachments/assets/b9ee36a1-2e4a-4f62-8b98-7b5c8c80ba6d" />



* The image above displays different options of the OS you can choose from depending on what desktop the agent is being deployed on.

**[The first agent we will deploy is for a Windows 11 system]**


## Step 2: Select and configure Agent deployment 

<img width="2096" height="1239" alt="image" src="https://github.com/user-attachments/assets/8e3062f5-d6b5-4ce3-a45c-aa5403189832" />


* Server address: [Wazuh Server IP]
* A command syntax will automatically be generated for you to copy and run on the intended agent host.
* Make sure to the read the requirements that pop up below it.



## Step 3: Install Agent onto the Windows system

<img width="997" height="610" alt="image" src="https://github.com/user-attachments/assets/5dd803b3-0d2e-4232-9399-0ccf99e9420b" />

* Do NOT forget to start the agent with the following command:
  ```
  NET START Wazuh
  ```
  
<img width="1000" height="215" alt="image" src="https://github.com/user-attachments/assets/0ebb938e-dd9c-4960-a702-e8488b957cee" />

## Step 4: Verifying Agent Deployment 

<img width="2548" height="931" alt="image" src="https://github.com/user-attachments/assets/0e3a7a46-8304-4dec-8e86-1de1a6f9caec" />



# Ubuntu Agent: 


## Step 1: Configure Agent


<img width="1851" height="860" alt="Screenshot 2026-10-19 164905" src="https://github.com/user-attachments/assets/5bfaaa43-4169-4de3-9f13-0a0b10892887" />

* A command will be generated, copy and run it like the last example.

## Step 2: Run installation commands: 

<img width="1910" height="947" alt="image" src="https://github.com/user-attachments/assets/84e29f1a-472c-4eb6-a954-77a8693309ac" />

* Run the following commands to start the agent:
```
sudo systemctl daemon-reload
sudo systemctl enable wazuh-agent
sudo systemctl start wazuh-agent
```
## Final Step: Verify 

<img width="1912" height="706" alt="image" src="https://github.com/user-attachments/assets/4915596c-b1fe-4bf1-80a6-dc0dafda6f10" />
