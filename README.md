# Build-a-simple-website-with-azure-functions:Microsoft Azure
# step 1 prepare environment
- create resource group
- named it rg-gp-functions
  # step2 Configure the function app
  - search function app  and create
  - select flex Consumption
  - basic tab choose existing resource group
  - name Func-gp-endpoint-6332
  - stock time : Node.js
  - open monitoring tab ensure App insight enabled
# step 3 verify deployment
- Select Go to resource
# step4 open cloudshell
- open cluodshell in the Portal , open it in BASH
- The first commnd then press enter then run the second command in the picture<img width="1207" height="785" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/5be26923-8b78-4029-ac70-5b4873739571" />
- then run :func new ==name Getstatus ==template "HTTP trigger" authlevel anonymous<img width="1600" height="900" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/fe4b19d2-d5d5-476e-8496-102a9954edde" />
# step 5 Deploy the function to Azure 
- <img width="1600" height="900" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/ec484786-34c8-483a-9b16-b1f5d81c390e" />
- <img width="1600" height="900" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/226ddcb6-cca2-4a78-ba21-5b5787443b8b" />
- <img width="1600" height="900" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/f16279c2-a8a8-412e-821b-8127d0aeaa46" />
- <img width="1600" height="900" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/8b81fe3c-2069-4b3c-ba7d-cd4c6c66a8f5" />

