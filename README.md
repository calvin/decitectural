decitectural
=========

A small library providing utility methods to convert measurements `toDecimal` or `toArchitectural` notation.

## Installation

	npm install decitectural --save

## Usage

	var decitectural = require('decitectural'),
		toDecimal = decitectural.toDecimal,
		toArchitectural = decitectural.toArchitectural;
	
	console.log(toArchitectural(53.93, "inches", "1/16"));
	console.log(toDecimal("4' 5 7/8\"", "inches", "1/10000"));

## Tests

	npm test

## Release History

* 1.0.0 Initial Release
