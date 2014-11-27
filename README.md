vmcGas
======

Simple JavaScript project to capture fuel fill up info, and save to a PouchDB database, then retrieve averages and the like.

As of 2014-11-26, user inputs work. Retrieving the last MPG works. 

Current problem: I can retrieve every last Odometer added to the database, and every total gallons, but having trouble ALSO retrieving every second-to-last Odometer, without going past the .length of the database. 
