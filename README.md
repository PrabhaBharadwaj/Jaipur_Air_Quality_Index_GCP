# Jaipur_Air_Quality_Index_GCP


## Google Cloud Platform (GCP) IaaS(Infrastructure as a Service)


## JAIPUR'S Air Quality Index Problem:

https://github.com/krishnaik06/Google-Cloud-Platform-Deployment

To Understand Google Cloud Platform deployment, i have downloaded already built project folder from Krish naik Github
So actual pytho code i dont have. I have Krish already created .pkl file, app.yaml , main.py, requirement.txt , templates, static
Just i did deployment by syncing this in my github


## Approach:

By using Linear RandomForset Regressor , we are predicting the JAIPUR'S Air Quality Index based on user input data

Here we used Flask web application Framework and deployed in GCP (Infrastructure As A service-IAAS) using Google Cloud SDK.
Here we didnt use GitHub,directly copied from local

### High Level steps:
	1) Create new Project
	2) Activate Google cloud shell
	3) Enable app engine admin API
	4) Create APP Engine
	5) Deploy Application
	6) Disable Application 
		
### Deployment main files:
  app.yaml  (Specific config file of GCP)
  main.py
  model.pkl
  requirements.txt
  templates folder with home.html
  static folder with css folder with style file
