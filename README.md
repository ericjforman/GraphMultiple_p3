# GraphMultiple_p3
Graph multiple sensors in Processing from Arduino serial data

This example shows modifying the code for 2 data packets. In this example, reading 1 sensor in Arduino and sending both its raw value and its smoothed value. (This could also work for sending 2 sensor values but this emphasizes it's the number of data values sent that really matters.)

This code can be easily adjusted for fewer or more sensors. 

It works with Processing 3 by putting draw functions inside draw() instead of inside serialEvent(). 

