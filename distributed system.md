##  What are distributed systems?
Distributed System is a collection of autonomous computer systems that are physically separated but are connected by a centralized computer network that is equipped with distributed system software. The autonomous computers will communicate among each system by sharing resources and files and performing the tasks assigned to them.

`Characteristics of Distributed System`
- Resource Sharing: It is the ability to use any Hardware, Software, or Data anywhere in the System.
- Openness: It is concerned with Extensions and improvements in the system
- Concurrency: It is naturally present in Distributed Systems, that deal with the same activity or functionality that can be performed by separate users who are in remote locations. Every local system has its independent Operating Systems and Resources.
- Scalability: It increases the scale of the system as a number of processors communicate with more users by accommodating to improve the responsiveness of the system.
- Fault tolerance: It cares about the reliability of the system if there is a failure in Hardware or Software, the system continues to operate properly without degrading the performance the system.
- Transparency: It hides the complexity of the Distributed Systems to the Users and Application programs as there should be privacy in every system.
- Heterogeneity: Networks, computer hardware, operating systems, programming languages, and developer implementations can all vary and differ among dispersed system components.

`Distributed System Failures`

- Method failure:  In this type of failure, the distributed system is generally halted and unable to perform the execution. Sometimes it leads to ending up the execution resulting in an associate incorrect outcome. Method failure causes the system state to deviate from specifications, and also method might fail to progress.
- System failure: In system failure, the processor associated with the distributed system fails to perform the execution. This is caused by computer code errors and hardware issues. Hardware issues may involve CPU/memory/bus failure. This is assumed that whenever the system stops its execution due to some fault then the interior state is lost.
- Secondary storage device failure: A storage device failure is claimed to have occurred once the keep information can’t be accessed. This failure is sometimes caused by parity error, head crash, or dirt particles settled on the medium.
- Communication medium failure: A communication medium failure happens once a web site cannot communicate with another operational site within the network. it’s typically caused by the failure of the shift nodes and/or the links of the human activity system.

`Failure Models`

- Timing failure: Timing failure occurs when a node in a system correctly sends a response, but the response arrives earlier or later than anticipated. Timing failures, also known as performance failures, occur when a node delivers a response that is either earlier or later than anticipated.
- Response failure: When a server’s response is flawed, a response failure occurs. The response’s value could     be off or transmitted using the inappropriate control flow.
- Omission failure: A timing issue known as an “infinite late” or omission failure occurs when the node’s answer never appears to have been sent.
- Crash failure: If a node encounters an omission failure once and then totally stops responding and goes unresponsive, this is known as a crash failure.
- Arbitrary failure : A server may produce arbitrary response at arbitrary times. 
