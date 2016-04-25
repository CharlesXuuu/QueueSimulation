The simulation project is implemented using Java programming language and I used eclipes IDE to develop the project. I was planning to implement an user interface for this project but due to the urgent time I did not implement it. However, so far the code can simulate all different kinds of situation by adjust the following input parameter:

1. Pessenger Numbers
2. Arriving Period
3. Arriving rate
4. Service rate
5. Agent Numbers
6. Canadian Agent Numbers
7. Visitor Agent Numbers   



The simulation project contains five major parts:
The directory is \Simulation\src\sim\queue\




The source code has five *.java files

SimulationMonitor.java
Pessenger.java
Agent.java
WaitingQueue.java
SimulationAnalyzer.java





Detailed comments are in these files, and the following are module descriptions:

SimulationMonitor.java

/**                        
* Project: Queueing Model Simulation                                       
* Module ID: Simulation Monitor
* JDK version used: <JDK1.7>                            
* Author: Charles Xu                        
* Create Date: 2014-03-12
* Version: 1.0             
* 
* Comments:  This class performs the whole simulation process, it is designed using event-driven strategy, 
* and it contains the main functions, the process is mainly in four steps:
* 
* 1. Generating the passenger, the queue and the agent
* 2. Setting the simulation strategy, is either 2-queue strategy or 16-queue strategy.
* 3. Begin simulation, monitor the discrete event, currently there are three events: (1). Arriving Event (2). Canadian Agent finishing Event
* 		(3). Visitor Agent finishing event. All events will be handled in different ways.
*                                             
* The simulation class has high adaptivity to simulate different number of agents, passenger and queues. 
*/ 

Pessenger.java

/**                        
* Project: Queueing Model Simulation                                       
* Module ID: Pessenger
* JDK version used: <JDK1.7>                            
* Author: Charles Xu                        
* Create Date: 2014-03-11
* Version: 1.0             
* 
* Comments:  This class is a representation for each passenger, it contains passengers' attribute and actions
* 
*/ 

Agent.java

/**                        
* Project: Queueing Model Simulation                                       
* Module ID: Agent
* JDK version used: <JDK1.7>                            
* Author: Charles Xu                        
* Create Date: 2014-03-11
* Version: 1.0             
* 
* Comments:  This class is a representation for each agent, it contains agents' attribute and actions
* 
*/ 

WaitingQueue.java

/**                        
* Project: Queueing Model Simulation                                       
* Module ID: Waiting Queue
* JDK version used: <JDK1.7>                            
* Author: Charles Xu                        
* Create Date: 2014-03-11
* Version: 1.0             
* 
* Comments:  This class is a representation for each waiting queue, it contains queues' attribute and actions
* 
*/

SimulationAnalyzer.java

/**                        
* Project: Queueing Model Simulation                                       
* Module ID: Simulation Analyzer
* JDK version used: <JDK1.7>                            
* Author: Charles Xu                        
* Create Date: 2014-03-13
* Version: 1.0             
* 
* Comments:  This class analyze the result of the simulation process
*/