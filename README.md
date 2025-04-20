📌 Objective Install and run Netdata on an EC2 instance using Docker to visualize system and application performance metrics through a real-time web dashboard.
# Task-7-Monitoring-using-Netdata

📌 Objective
Install and run Netdata on an EC2 instance using Docker to visualize system and application performance metrics through a real-time web dashboard.

🛠 Tools Used
Netdata – Open-source system monitoring tool
Docker – Containerization platform to run Netdata
Amazon EC2 – Virtual Machine instance on AWS
⚙️ Setup Instructions
Step 1: Connect to EC2 via SSH
Step 2: Install Docker (if not already installed)
![Screenshot (255)](https://github.com/user-attachments/assets/89690df0-14d5-4408-aeaa-3bc507654a64)

Step 3: Run Netdata Container
![Screenshot (256)](https://github.com/user-attachments/assets/bccf6504-0c5f-4030-a482-f499d0ac31a2)

Step 4: Configure EC2 Security Group
Update your EC2 security group to allow TCP traffic on port 19999:
Type: Custom TCP
Port: All Traffic
Source: Your IP (for security)

Step 5: Access Netdata Dashboard 
Open a browser and visit: http://ip-address:19999

Results:
![Screenshot (257)](https://github.com/user-attachments/assets/ab3a29a5-040f-4c9f-9511-92301c6be484)
![Screenshot (259)](https://github.com/user-attachments/assets/e5a0cfaf-d017-470e-a64e-4054b12bd891)
![Screenshot (260)](https://github.com/user-attachments/assets/ae378b54-c14f-47cf-906f-fa769e03c513)
![Screenshot (261)](https://github.com/user-attachments/assets/1d81ce5f-0c13-4100-a2fa-7f3edc1ba0e6)
![Screenshot (262)](https://github.com/user-attachments/assets/c14d94c7-46c8-4ee1-bcdd-98a079533b3d)
![Screenshot (263)](https://github.com/user-attachments/assets/105a660e-5959-42a7-92c7-10595ae416a2)
![Screenshot (266)](https://github.com/user-attachments/assets/0d29079e-4354-4c38-a68b-f5daf1f72f47)
![netdata-logs](https://github.com/user-attachments/assets/2938a30c-c503-4be3-9fd0-3b379e960705)

