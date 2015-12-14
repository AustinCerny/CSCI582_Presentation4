# Amazon Elastic Clompute Cloud (V)

***
#### Autoscaling
* Equivalent to load balancing, facilitates the addition/removal of instances automatically
* Uses Scalr framework
	* Open-sourced by Amazon in 2008

* 1) AMI selected as a template
* 2) Configure details
	* Can be left up to Amazon (typically this is expensive)
	* User can select policies for
		* How frequently nodes are checked
		* Rules/thresholds for new instances being created
			* RAM/CPU usage rates etc.
	* 3rd party software can analyze log data and help users optimize these settings
		
* 3) Users select how and when they are notified when instances are created/closed

* Creating new instances is fast but not instantanous
	* Typically ~10 minutes for medium+ sized machines
* Scaling can also be done by changing hardware on existing machines
	* Increase # cores, RAM etc.
	* Potentially faster/cheaper, depends on the user


***


[Prev](https://github.com/AustinCerny/CSCI582_Presentation4/blob/master/slide18.md)
[Next](https://github.com/AustinCerny/CSCI582_Presentation4/blob/master/slide20.md)
