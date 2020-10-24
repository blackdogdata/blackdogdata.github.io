[RoadMap starting Point](https://roadmap.sh/devops)
* AWS
  * AWS RAM Console - Resource Access Management
  * AWS Control Tower, LandingZone
  * API Gateway
  * VPC
	* VPG - Virtual Private Gateway
	* BGP - Border Gateway Prototcol 
		* ASN
	* RouteTable - destination based
	* ENI
	* Subnets
		* 5 Addresses allocated for AWS
			- 0 Network Address
			- 1 VPC router
			- 2 DNS
			- 3 Reserved / spare
			- x Broadcast - last address 
	* Peering connections
	* DirectConnect
	* TransitGateway - Layer 3
	* ALB (layer 7)
	* NLB (layer 4)
	* Internet Gateway
	* VPC EndPoints
	* VPC Peering - doesn't support overlapping CIDR.
	* VPC Sharing
	* PrivateLink
  * Serverless
  * Organizations
	* SCP - Service Control Policies
	* Naming Convention
  * STS - Security Token Service
  * IAM - Identity and Access Management
	* User in Groups 
	* Roles
	* Policies
	* Global Service
	* Policy Simulator
	* Authenitcation - Who are you? and Authorisation - What can you do?
	* ARN - Amazon Resource Number
	* Access Key ID =approx  - username
	* Secret Access Key =approx - password
	* Policy 
		- Effect - Allow / Deny
		- Action
		- Resource
		- Condition
	* Trust and Permission Policy
	* Service Roles
  * EC2
	* EBS - Elastic Block Store
	* SSM
	* Auto Scaling Group
  * EFS - Elastic File Store
  * Lambda
  * S3
	* Object store
  * KMS
  * Cloudwatch
	* Logs
	* Monitoring
	* Alarms
	* Metrics
  * CloudTrail
  * Route53
	* Hosted Zones
  * CloudFormation
  * Data Tooling
	* Kinesis	
	* AWS Glue
	* Redshift
  * SNS
  * RDS
  * DynamoDB
  * SQS
  * ELB
  * WAF & Shield
  * Security Hub
	* Guard Duty
	* CVE - Common Vulnerabilities and Exposures
  
* IaC
  * Hashicorp
	* Terraform
	* Packer
	* Vault
	* Consul
  * Configuration Management
    * Ansible 
    * Chef
	* Puppet
	* SaltStack
*Scripting
	* Python
		* Black Code Formatter
	* Ruby  
	* Go
	* Bash
* CI/CD
  * Jenkins
  * Hudson 
  * Bamboo
* Operating System Theory
  * IO
  * Virtualisation
  * Processes, Threads
  * Sockets
  * Filesystem
  * Memory
* Linux
  * Distros 
	* CentOS
	* Linux AMI
  * Tools
    * awk
    * sed
    * grep
    * sort
    * cat
    * ps
    * top
    * htop
* Containers
  * Docker
  * kubernetes
* Git
  * Hooks on Windows
  * BitBucket
  * GitHub
  * GitLab
* Networking
  * NAT
    * NAT Traversal NAT-T
    * Source NAT - SNAT
    * Destination NAT - DNAT
  * IP/TCP
    * ARP - Address Resolution Protocol
    * BGP - Border Gateway Protocol
  * Firewall
  * HTTP
  * DNS
  * DHCP
  * FTP
  * SSL/TLS
  * SSH
    * Putty  
* Active Directory
  * SSO
  * SAML
* SQL
* Server Apps
  * Web Server
    * NGINX
    * Tomcat
    * Apache
    * IIS
    * Caddy
  * Reverse Proxy
  * Caching Server
  * Load Balancer
  * Forward Proxy
  * Firewall
* VMWare
* DevOps
* Security Tooling
* Migrations
* Testing
	* Test Driven Development
	* Automated testing
* Job Roles
	- Dev Ops
	- Site Reliability Engineer
	- Cloud Engineer
	- Platform Engineer
	- Cloud Architect
IPSec VPN
Private Virtual Interface 
IPTables
RFC-1918

* Agile
  * Scrum
  * Kanban
  * Writing Requirements
  * Definition of Done

## Service Considerations
[Infra as Code Checklist](https://www.youtube.com/watch?v=jiWRTuF4yXk)
* Plan
* Provision
* Install
* Configure
* Deploy
* Security
* Automation
* Monitoring
	Nagios
	Grafana
* Shut down / End of Life
* Billing
* Logging
* Backup / Restore
* High Availability
* Performance
* Documentation
* Testing


