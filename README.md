IOT DASHBOARD
=============

A node.js project to get real time data from the sensors and to display that on the Dashboard.This Project includes real time graph generation.
	
	To learn more about IOT click <a href="https://en.wikipedia.org/wiki/Internet_of_things">here</a>.


Installation
============

* In the main folder, run: `npm install`
	>>This will install all dependencies.

* You also need to change the following files:

 	>> `app.js` - change mongodb url accordingly, in order to have data persistence;
			    - change mysql password accordingly;


To Run The Application
======================

* Go to main folder from the command line;
* run : 'node app.js';
* On your favourite browser , go to 'localhost:3000'


External Libraries Used
=======================

<ul>
<li><a href = ' http://c3js.org/'>C3 Charts</a></li> 

<li><a href = ' https://www.pubnub.com/developers/eon/'>EON Charts</a></li>

<li><a href = ' https://www.amcharts.com/'>AM Charts</a></li> 
</ul>