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

Q06. What method can you override on a React component in order to prevent unnecessary rendering?  
A. shouldComponentUpdate  
B. componentWillUpdate  
C. checkForUpdates  
D. skipUpdateWhen  
Answer: `shouldComponentUpdate`  

Q07. What is the benefit of handling buffering of events outside of your React component?  
A. React components can only take arrays and don't work well with events  
B. It makes the component simpler and unaware of the architecture around it  
C. React components are not able to handle multiple events and selectively updating  
Answer: `It makes the component simpler and unaware of the architecture around it`  

Q08. What Socket.IO event can you subscribe to on the client when you want to be notified that a connection to the server has been established?  
A. on-connect  
B. connection-established  
C. open  
D. connected  
Answer: `connected`  

Q09. How can you ensure that a Socket.IO server handled an event successfully?  
A. This is not possible because Socket.IO is fire and forget  
B. By sending a callback function through on emit  
C. By using the promise API of Socket.IO  
D. You should listen for another event on the client and emit it from the server  
Answer: `By sending a callback function through on emit`  

Q10. When you have an RxJS `Observable`, with events containing a timestamp value on a field called `ts`, how can you get the most recent value from the Observable?  
A. By mapping over the events in the Observable and storing the most recent value on a variable  
B. By using the scan operator on the Observable and using Math.max for each item  
C. By using the filter operator on the Observable and only returning events with a recent timestamp  
Answer: `By using the scan operator on the Observable and using Math.max for each item`  