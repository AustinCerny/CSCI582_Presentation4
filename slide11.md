# Amazon Simple Storage Service (II)

*** 
* Each bucket in a S3 account has a unique-user assigned key
* This allows objects to be addressable using a HTTP URL
`http://s3.amazonaws.com/bucket/key`
or 
`http://bucket.s3.amazonaws.com/key`

This functionality means that Static websites can be hosted entirely on AWS S3
	* Domain Name Alias needed from bucket/key HTTP URL to `http://www.example.com`
	* Setting can provide redirection to a "Home Page" instead of the default XML page when navigating to the HTTP URL
	* Redirection to a error page can be set up for a partially invalid URL

***

[Next](https://github.com/AustinCerny/CSCI582_Presentation4/blob/master/slide12.md)
[Prev](https://github.com/AustinCerny/CSCI582_Presentation4/blob/master/slide10.md)
