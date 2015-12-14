# Additional Web Services (II)

*** 
#### Amazon Lambda
![Alt text](https://github.com/AustinCerny/CSCI582_Presentation4/blob/master/web3.PNG)
* Brand new as of late 2015
* Users upload functions/code to AWS
* AWS will execute code when a trigger is set
	* Triggers are event driven
		* Data change in S3 or dynamoDB
		* HTTP request usign Amazon API gateway

* Potential applications in Big Data and Data management and more
* Useful example: Mobile Apps
	* AWS provides logic for mobile applications
	* Backend logic is lambda function, trigger is when mobile app make an HTTP call
	* Minimal code needed for client
		* Makes updates/deployment easier
	* Cashing layer can be added 
		* Reduces lamda function calls
		
* User pays for each execution of a lamda function
	* << $0.01 per instance


***

[Next](https://github.com/AustinCerny/CSCI582_Presentation4/blob/master/slide22.md)
[Prev](https://github.com/AustinCerny/CSCI582_Presentation4/blob/master/slide20.md)
