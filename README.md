# README Pubsub GUI

### Table of Contents
* [Reason Behind The Code](https://github.com/LVivona/Libp2p-pubsub-gui/edit/master/README.md#reason-behind-the-code)
* [How To Run](https://github.com/LVivona/Libp2p-pubsub-gui/edit/master/README.md#how-to-run)
* [External Resources](https://github.com/LVivona/Libp2p-pubsub-gui/edit/master/README.md#external-resources)

 ## Reason Behind The Code

This was mainly for learning golang gui, and connecting that gui with a peer from libp2p, it is also well to note that most of the code has been ripped from the examples provided by go-libp2p in which they build a publish/subscription application in which two local peers can cominicate, You can check it out I provide a link in the resource section of the README.


## How To Run

connectiong made with other peers can only be done in a local network, Ideally due to limitation in my knowledge in libp2p I would want it to run over mutiple networks but it requires me to hole punch to access other routes from my understanding which will require more testing on the libp2p librarry to better understand how do that effectively. 

```
go run .

- OR

go build
./chat
```


## External Resources

* GUI [https://github.com/rivo/tview]
* libp2p [https://github.com/libp2p/go-libp2p]
