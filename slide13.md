# Amazon Simple Storage Service (IV)

*** 
#### Pricing
Users pay 3 separate fees

Storage:
	* $0.03/(Gb/Month) is the _starting_ rate

Requests: (must pay each time content is accessed)
	* GET Request $0.01/10,000 Requests (pratically nothing)
	* Other requests $0.01/1000 Requests (PUT POST etc.)
	* Rates/request reduce up to 5x as requests increase
	
Transfer: (must pay for data downloaded)
	* $0.09/Gb (approx = 3 months cost to store equivalent amount of data)

Tbe AWS Glacier service is cheaper, meant for archival storage
	* Cost/Gb/month < $0.01
	* Request/Transfer rates ~5x more

_AWS S3 has a free tier rates as well_
	* 5 Gb storage 
	* 20000 GET Request/Month
	* 15 Gb data transfer/Month
***

[Next](https://github.com/AustinCerny/CSCI582_Presentation4/blob/master/slide14.md)
[Prev](https://github.com/AustinCerny/CSCI582_Presentation4/blob/master/slide12.md)
