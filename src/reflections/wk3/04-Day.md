# Day 4 of Week 3 at Codeworks
__12/17/2020__

## What problems does the Observer Pattern seek to solve?

 The Observer Pattern fixes many different issues with javascript. Namely keeping a bunch of equal elements that carry the same data.

## What are the three mechanisms of the Observer Pattern?

 There is three mechanisms within the Observer Pattern. Those three are the Subscribe method, which adds events, the Unsubscribe method, which removes events, & the Broadcast method which calls all events.

## Review the code from bcw-template and reflect on the proxy objects from yesterday, and your understanding of the Observer Pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

 The use of Proxy and Observer Pattern in the bcw-template adds a level of access and security of objects and events between the js files. Proxy can be implemented as a memory of sorts to be axcessed by any part of the js files which can be used to input or remove objects or axcess, remove/add events within the logic of the dom. Proxy also provides security of objects or elements from other lines of code that can produce interference.  