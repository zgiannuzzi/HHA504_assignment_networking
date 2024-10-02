# 1. Create a Virtual Private Cloud (VPC)

## Azure 

- Created Azure Vm Instance
  
![Image of Azure overview](https://github.com/zgiannuzzi/HHA504_assignment_networking/blob/main/VCPA1.PNG)

- Created Virtual Network
  
![Image of Azure overview](https://github.com/zgiannuzzi/HHA504_assignment_networking/blob/main/VCPA4.PNG)

## GCP
- Created the VCP in GCP

![Image of Azure overview](https://github.com/zgiannuzzi/HHA504_assignment_networking/blob/main/VPC1.PNG)

![Image of Azure overview](https://github.com/zgiannuzzi/HHA504_assignment_networking/blob/main/VPC2.PNG)


# 2. Assign a Dedicated IP

- Couldnt figure out how to configure the dedicated IP for AZURE so I used the given one.
  
## Azure 
![Image of Azure overview](https://github.com/zgiannuzzi/HHA504_assignment_networking/blob/main/VCPA1.PNG)


## GCP

- Assigned the static IP to my GCP VM instance.
  
![Image of Azure overview](https://github.com/zgiannuzzi/HHA504_assignment_networking/blob/main/VPC9.PNG)


# 3. Map IP to a Domain Acquired via GitHub Student Pack
- Below is an image of me Mapping the IP to the static instances for both Azure and GCP 
![Image of Azure overview](https://github.com/zgiannuzzi/HHA504_assignment_networking/blob/main/VCP11.PNG)

# 4. Deploy Flask Application

- Did the following steps for both Azure and GCP
  1. Open and ssh connection to virtual instance
  2. Use sudo apt-get update to update virtual instance
  3. Download pip3 with sudo apt-install python3-pip3
  4. Clone github repository
  5. Navigate to the cloned repo
  6. Use pip3 install -r requirements.txt (worked for GCP not in Azure)
  7. I don't remember the command for Azure to dowload the packages becuse I deleted the instance however the terminal showed me the command and I ran that and was able to download flask 
  8. Run program with python3 app.py

## Azure 

![Image of Azure overview](https://github.com/zgiannuzzi/HHA504_assignment_networking/blob/main/VCPA3.PNG)

## GCP 

![Image of Azure overview](https://github.com/zgiannuzzi/HHA504_assignment_networking/blob/main/VCP12.PNG)

# 5. Configure Firewall Settings
- Added a firewall rule for both to allow port 5007.

## Azure 

![Image of Azure overview](https://github.com/zgiannuzzi/HHA504_assignment_networking/blob/main/VCPA5.PNG)

## GCP
![Image of Azure overview](https://github.com/zgiannuzzi/HHA504_assignment_networking/blob/main/VPC8.PNG)

# 6. Access Your Application via Domain
## Azure 
 - Could not find the reason why flask IP would not connect was able to get the flask application running in the SSH though.
![Image of Azure overview](https://github.com/zgiannuzzi/HHA504_assignment_networking/blob/main/VCP5.PNG)

 - Was succesful accessing application via my Domain 
## GCP 
![Image of Azure overview](https://github.com/zgiannuzzi/HHA504_assignment_networking/blob/main/VCP10.PNG)

