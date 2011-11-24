jQuery - Tap and Hold
=====================

	This jQuery plugin lets you detect a tap and hould event on touch interfaces.

How to use it?

	1) Add the jQuery Tap and Hold plugin into your HTML

	<script src="https://raw.github.com/zaubersoftware/jquery-tap-and-hold/master/jquery.tapandhold.js" language="javascript"/>

	2) Bind a tap and hold handler function to the tap and hold event of an element.

	$("#myDiv").bind("taphold", function(event){
		alert("This is a tap and hold!");
	});

