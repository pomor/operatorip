
geotools
========

Simple and fast IP to Country/Region lookup module for nodejs. **Pull Requests are welcome!**

## GEO databases

You can download fresh geo database from this website: http://ipgeobase.ru/.
Database contains major ranges for all countries worldwide and presice ranges for most Russian cities/regions.
Also it could be extended with another geo data.
operatorip
==========

custom version from geotools for mobile operator
add only ID Axis operator

## Installation

	npm install operatorip

## Usage

	var operator = require('operatorip');
	var res = geo.lookup("203.78.112.11");
	// output is { country: 'ID', operator: "ID_AXIS" }
