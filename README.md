# AWS-Projects
Connecting a Web App with an Amazon Aurora Database
This project was to specifically to create an EC2 instance to host a web app and connect with a relational database in amazon called Aurora
When I connecting the web app hosted on an EC2 instance to the Amazon Aurora database. This procedure covered the Security pillar of the Well Architectured Framework. The data and connections between the web app and database were protected ensuring that Aurora is in a private subnet and only accessible by the EC2 instance. Also with the Cost Optimization, the EC2 instance size met that of the performance needs so there were no cost. Lastly under the Performance Efficiency the appropriate EC2 instance type was used for the web app based on the expected traffic and usage patterns.
With regards to the Reliabilty, the web app should've been able to can handle failures in the EC2 instance and the Aurora database. 
