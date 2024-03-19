DCP - 18th Mar. 2024

########################
Day 1 - 18th Mar. 2024
########################


	Introduction to DevOps :::
	
	What is DevOps ???
	
	SDLC Process ::: - Software Development Life Cycle :
	
	- Requirement Analysis 
	- Design
	- Code
	- Testing 
	- Implementation 
	- Monitoring/Maintain
	
	
	Software - Applications :
	
		- Desktop Applications
		- Web Applications
		- Mobile Applications
		
		- System Applications
		- Embedded Applications
		
	Waterfall Model ::
	
			- Linear in approach 
			- Follows Top-Down Approach.
			- Monolith Application Architecture
				- Tightly coupled Applications
			
		Desktop Applications
			Billing System 			10 Months!
				10 functions + 1
	Project :
	
	- Requirement Analysis 
	- Design
	- Code						current 
	- Testing 
	- Implementation 
	- Monitoring/Maintain
	
	Enhancement - Project :
	
	- Requirement Analysis 
	- Design
	- Code						
	- Testing 
	- Implementation 
	- Monitoring/Maintain
	
	
	Agile Methologies ::: 


			
		Desktop Applications
			Billing System 			10 Months!
				10 functions/Modules. - Iterations

		Iteration 1 :	User Interface Design.
		
			- Requirement Analysis 
			- Design
			- Code
			- Testing 
			- Implementation 
			- Monitoring/Maintain

		Iteration 2 :	Stock Details.
		
			- Requirement Analysis 
			- Design
			- Code
			- Testing 
			- Implementation 
			- Monitoring/Maintain

		Iteration nth :	Payment Module.
		
			- Requirement Analysis 
			- Design
			- Code
			- Testing 
			- Implementation 
			- Monitoring/Maintain
			
		
		Using AGILE :
		
			we can achieve :
			
			Continuous Development
			Continuous Integration 
			Continuous Testing 
			Continuous Delivery
				- This expects a Manual approvals for Production Release 
				
			
			We cannot achieve :
			
			Continuous Deployment 
				- Without any Manual Intervension/approvals for Production Release
				
	DevOps :::
		DevOps is a Software Development Strategy which helps to promote the collaboration between the Teams like Development Teams and Operation Teams to achieve Continuous Development, Continuous Integration, Continuous Testing, Continuous Delivery, Continuous Deployment and Continuous Monitoring in more automated fashion.
		
	How to Implement DevOps ???
	
	1. Application Architecture:
	
		Monolith Application Architecture 
				- Tightly coupled Applications
				- There is not modularity
				
		For DevOps - Its always recommended to have :
		
		Micro-Service Based Application Architecture :
				- It is loosely couple Applications 
				- Here, each fuction will be considered as Micro-Service.
				- These Micro-Service can be independently developed, testing and implemented to production automatically
					
	2. Teams involved in overall SDLC :
	
		- Infra-Structure Management Team 
		- Application Development Team 
		- Testing Team 
		- Release Management Team 
		- Production Support Team 
		- Production Monitoring Team 
		- Security Team 
		
	
	3. DevOps Stages :
	
		- Continuous Development :
			- It is the capability of the Development Team to continuously develop code 
			- Improve the Productivity of the Developers
			
			How ?
			
			Role of Developer ?
			
			- Code 
			
			- Coding 
			- Manual Build Application - 
				- Build - Is a process of compiling the source code and create artifacts(Binaries - *.war/*.jar/*.exec/*.dll)
			- Perform Unit Testing 
			- Promote the code to higher environments (QA / UAT / Prod)
			- Notify the Testing team thru emails 
			
			Using DevOps Approach::
			
				- Create Source Code 
				- Save/Commit the Source Code in a Source Repository.
				
			Automate the process using DevOps Tools :
				- Build Application - 
					- Build - Is a process of compiling the source code and create artifacts(Binaries - *.war/*.jar/*.exec/*.dll)
				- Perform Unit Testing 
				- Promote the code to higher environments (QA / UAT / Prod)
				- Notify the Testing team thru emails 
				
			Tools ::
			
				- Eclipse based IDEs( Integrated Development Environment), Visual Studio, Pycharm, Visual Studio Code 
				- GIT / GIHUB
				- Build Tools - Maven integreted with IDEs 
				
		- Continuous Integration :
			- It is capability of the Development Team to continuously integrate the code for further testing without waiting for others.
			
				- Promote the code to higher environments (QA / UAT / Prod)
				- Notify the Testing team thru emails 
					
			Tools :
			
				- GIT/Github
				- Jenkins 
				- Docker, Kubernetes, Ansible 
				
		- Continuous Testing :
		
			- It is a process of automated Testing 
			
			Tools :
				
				- TestNG/JUnit
				- Selenium 
				- Jenkins
				
		- Continuous Delivery / Continuous Deployment ::
			- Both are related to production Release. 
			
			- Continuous Delivery :
				- It expect Manual Approval for Production Release 
				- Expect Downtime during Production Release
				
			- Continuous Deployment :
				- It NEVER expect Manual Approval for Production Release 
				- Production Release will be completly automated.
				- NO Downtime during Production Release	
					
			Tools :
				- Jenkins
				- Docker, Ansible 
				- Kubernetes
				
				
		- Continuous Monitoring :
			- It is used to Monitor the Production Environment and Applications
			
			www.amazon.com :
			
				- 10000 simultaneous users
				- 50000 ?
				
				CPU Utilization / Memory / Network / Traffic 
				
			Tools :
				Prometheus / Grafana / Splunk / Dynatrace 	- Infra-Structure Monitoring Tools 
				
				AppDynamics / DataDog						- Application Monitoring Tools 
				
				Jenkins 
				
	4. Infra-Structure Management :
		
		IAC - Infra-Structure As Code :
		
			Server Provisioning/ Creating 	- Terraform/CF/ARM
			
			Configuration Management 		- Ansible/Chef/Puppet
			
	
	5. DevOps Tools :
	
		Open-Source Tools 
			GIT,Jenkins,Docker,Kubernetes,Ansible,Terraform,Prometheus,Grafana
		
		Managed Services 
			AWS 	- Code commit, Code Pipeline, Code Build,....
			AZURE 	- Azure DeveOps Services 
			GCP 	- GCP DevOps Services 
			
			
	6. DevOps Team's Role :::
	
		- DevOps Team :
			- Infra-Structure Management Team 
			- Application Development Team 
			- Testing Team 
			- Release Management Team 
			- Production Support Team 
			- Production Monitoring Team 
			- Security Team 

		- Role is to support the teams to automate their process. 
		
	7. DevOps Assessment :

	DevOps is all about ::
	
		- People 
		
		- Process 
		
		- Tools 
	
	
	Waterfall, AGILE, DevOps, DevSecOps, GitOps, SRE, MLOps, AIOps

Next: 

	DevOps LifeCycle 
	
	Version Control System
	
gihub account ?
