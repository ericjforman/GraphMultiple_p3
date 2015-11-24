# GraphMultiple_p3
Graph multiple sensors in Processing from Arduino serial data

This code can be easily adjusted for fewer or more sensors. 

It works with Processing 3 by putting draw functions inside draw() instead of inside serialEvent(). 

Note this causes the graph to move at the constant framerate of the Processing sketch, NOT at the rate of serial data coming in. (Sometimes this is useful to see.)
