### Simple Tcp Protocol

**This Project Includes Server and Client Module with Simple Protocol**

**Protocol Structure**
| Field  | Value  |
|---|---|
| Header  | Size Of Body  |
|  Body |  Massage Data |
|  EndOfMessage |  \quit! |


eg.  Client send `hello` Message :

```
12
hello/quit!
```

and Server Recieve :

```
  hello 
``` 