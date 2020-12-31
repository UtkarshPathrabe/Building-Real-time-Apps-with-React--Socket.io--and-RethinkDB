Building Real-time Apps with React, Socket.io, and RethinkDB
============================================================  

Q01. You are working with Socket.io on the server and you have it on a variable called `io`. How can you get a reference to a connected client?  
A. By calling the subscribe method on io and specifying the connected event  
B. By calling the then method on io, the promise will return the connected client  
C. With Socket.io, you don't need to deal with specific clients because you can broadcast  
D. By calling the on method on io and specifying the connected event  
Answer: `By calling the on method on io and specifying the connected event`  

Q02. You are working on the server and you have a reference to a connected client on a variable called `client`. How do you send events to the client?  
A. By calling sendEvent on the client reference  
B. By calling submit on the client reference  
C. By calling emit on the client reference  
D. By calling send on the client reference  
Answer: `By calling emit on the client reference`  

Q03. You have the following RethinkDB query:  
```r.table('names')```  
How can you subscribe to any new rows that get saved to the `names` table?  
A. By adding subscribeToChanges() on to the query  
B. You cannot subscribe to updating data on a RethinkDB query  
C. By calling then on the result of this query  
D. By adding changes() on to the query  
Answer: `By adding changes() on to the query`  

Q04. What is the main benefit that you get by adding RethinkDB to a Websocket stack?  
A. Because it's schemaless, it makes sending records over a socket much easier  
B. It's faster than other databases which is needed for real-time services  
C. It allows you to scale out your Websocket servers  
D. It's best of breed query language makes it easier to do Websocket programming  
Answer: `It allows you to scale out your Websocket servers`  

Q05. When you need to make an event available on an Observable, what RxJS method can you use?  
A. handleEvent  
B. fromEventPattern  
C. onEvent  
D. mapEventToObservable  
Answer: `fromEventPattern`  