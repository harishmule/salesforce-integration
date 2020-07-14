##########################################################
- Welcome to  "salesforce-integration"
- This API is to learn salesforce integration
	- Query accounts
	- Create accounts
- Please create a salesforce account in sf developer portal
##########################################################
- This API is implemented by using below
	* Mule4
	* Runtime version 4.2.2
	* HTTP Listener
	* Salesforce Connector
		dependency:
			<!-- <dependency>
				<groupId>com.mulesoft.connectors</groupId>
				<artifactId>mule-salesforce-connector</artifactId>
				<version>10.2.1</version>
				<classifier>mule-plugin</classifier>
			</dependency>  -->
##########################################################
- Getting started
	1) clone project 
	2) Import jar into anypoint studio 7 (mule 4)
	3) Make sure you'll get all files 
	6) Right click the application and RUN in anypoint studio
	7) To execute the application: 
		GET: http://localhost:8081/accounts
		POST: http://localhost:8081/accounts --> Body formate is below

		<!-- [
			{
				"name": "ranga",
				"address": "123 ranga street",
				"city": "edison",
				"state": "new jersey",
				"zip": "08820",
				"phone": "0009990022"
			},
			{
				"name": "vijay",
				"address": "123 vijay street",
				"city": "edison",
				"state": "new jersey",
				"zip": "08820",
				"phone": "1230009999"
			}
		] -->
##########################################################



