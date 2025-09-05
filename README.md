<h1>Server Deployment and Management with Ansible (Apache)</h1>


<h2>Project Description</h2>
This project focuses on using Ansible, an open-source automation tool, to streamline the deployment and configuration of multiple Linux servers. Instead of manually setting up each server, I automated the process using Ansible playbooks, ensuring consistency, security, and efficiency across all nodes.

<h2>Project Overview</h2>

- <b> Set up a control node (WSL Ubuntu on Windows) and two managed nodes (Ubuntu servers in VirtualBox with bridge networking).</b>
- <b> Configured Ansible inventory to manage servers by IP and user credentials.</b>
- <b> Generated and distributed SSH keys to enable secure, passwordless connections.</b>
- <b> Created an Ansible playbook to:</b>
  - <b> Update system packages</b>
  - <b> Install Apache web server</b>
  - <b> Ensure Apache is running and enabled at boot</b>
 - <b> Validated the automation by accessing Apache’s default page on both servers.</b>


<h2>What I learnt</h2>

- <b>How to set up and configure Ansible on a control machine.</b>

- <b> Writing and running Ansible playbooks in YAML format.</b>

- <b>Using inventory files to manage multiple servers.</b>
  
- <b>Automating repetitive system administration tasks like software installation and service configuration.</b>

- <b>Troubleshooting SSH, sudo permissions, and Python dependencies on remote servers.</b>


<h2>Importance of this Project as a System Administrator</h2>

- <b>Efficiency: Saves time by automating repetitive tasks such as software installation, updates, and configuration.</b>

- <b>Consistency: Ensures all servers are configured identically, reducing human error.</b>

- <b>Scalability: Makes it easy to deploy changes across dozens or even hundreds of servers with a single command.</b>

- <b>Practical Skills: Demonstrates real-world sysadmin and DevOps practices that are highly sought after in the IT industry.</b>

- <b>Foundation for DevOps: Provides hands-on experience with automation, which is essential for modern cloud and DevOps workflows.</b>


<h2>Tools Covered:</h2>

- <b>WSL (Windows Subsystem for Linux): Used as the control machine to run Ansible on Windows.</b>

- <b>VirtualBox: Virtualization platform to create and manage the two Ubuntu Server VMs.</b>

- <b>Ubuntu Linux (Server & WSL): Operating system for both the control and managed nodes.</b>

- <b>Ansible: Automation tool used to deploy, configure, and manage multiple servers at once.</b>

- <b>SSH (Secure Shell): Enabled secure, passwordless communication between control and managed nodes.</b>

- <b>YAML: Format used to write Ansible playbooks for automation tasks.</b>

- <b>Apache Web Server: Installed and configured as the test service to validate automation.</b>




<h2>Practical Knowledge Gained:</h2>

- <b>Server Provisioning: Learned how to set up multiple virtual servers with consistent configurations.</b>

- <b>Automation with Ansible: Gained hands-on experience in writing and executing playbooks to perform tasks like installing and starting services.</b>

- <b>Inventory Management: Understood how to organize and define multiple servers for automation in inventory files.</b>

- <b>Configuration Management: Applied automation to ensure that services (like Apache) are installed, started, and enabled on boot across all servers.</b>

- <b>SSH Key Management: Learned how to set up secure, passwordless SSH access for automation.</b>

- <b>Troubleshooting Skills: Dealt with real-world issues such as SSH permissions, sudo password prompts, and missing dependencies (Python).</b>

- <b>Scalability Concepts: Practiced deploying changes to multiple servers at once, a key concept in modern sysadmin and DevOps roles.</b>


<h2>Documentation Link:</h2>


(https://brief-foam-edd.notion.site/Automated-Server-Deployment-with-Ansible-2638ff75bed380a68652f111f78f8a34?source=copy_link)

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
