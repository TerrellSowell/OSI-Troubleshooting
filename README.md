## OSI Troubleshooting

This Network Lab project aimed to establish deepen understanding on how to troubleshoot at every OSI layer. The primary focus was to ingest and analyze every potential troubleshooting layer approach on the network, generating test telemetry to mimic real-world issue scenarios. This hands-on experience was designed to gain experience with real Cicso equipment to understand network security, troubleshoot patterns, and bottom-up strategies.

Layer 1(Physical)-Are all cables correctly inserted? Are the cable ends bent or worn out? Has somebody forgotten to add the corrct speed to the interface? Has the speed of the Ethernet port been set correctly? Has thr interface been opened for use by the Network Admin?
Layer 2(Data Link)-Has the correct protocol been applied to the interface so it agrees with the other side, such as Ethernet/PPP/HDLC?
Layer 3(Network)-Is the interface using the correct IP address and subnet mask?
Layer 4(Transport)-Is the correct routing protocol being used, and is the correct networking being advertised from the router?

The most important part of troubleshooting any problem is to divide the tasks of problem resolution into a systematic process of elimination. Cisco has broken this process into eight steps:

- Define the problem.
- Gather detailed information.
- Analyze the information. Consider probable cause for the failure.
- Devise a plan to solve the problem.Eliminate potential causes.
- Implement the plan. Propose Hypothesis
- Test Hypothesis. Observe the results of the implementation.
- Repeat the process if the plan does not resolve the problem.
- Document the changes made to solve the problem.
  
 **Troubleshooting methods through the OSI stack include these three methods:**

![top down TS](https://github.com/TerrellSowell/OSI-Troubleshooting/assets/161978506/1253ca9e-8814-4b02-9cbb-661c144becf8)

**Troubleshooting Methods:**
- Comparing Configurations- For routing issues for an example you can look at a template to compare the configurations too and look for an typos or missing commands
- Trace the Path- For connectivity issues, start at the source and trace the path to the destination.
- Swap out Components- If you think you have narrowed the issue to particular device and you can't see any configuration issues, you can switch out the hardware like a cable

**Troubleshooting Connectivity Methods:**
-  Ping- Ping command checks two way connectivity; ICMP uses a packet from the source to the destination.
-  Traceroute- If Ping fails, if you have multiple routers the traceroute command does a hop to hop at each router verifying connectivity at each source to destination.
-  Telnet- Can check to see if a port open on a destination, example you can telnet to port 80 and see if its receiving communication.


### Skills Learned

- Advanced understanding of toubleshooting concepts and practical application.
- Proficiency in analyzing and interpreting network troubleshooting methods.
- Ability to generate and recognize troubleshooting signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in network security.

### Tools and Technology Used

- Putty.
- Ciso Router
- Cisco Switch


## Steps
drag & drop screenshots here or use imgur and reference them using imgsrc

Every screenshot should have some text explaining what the screenshot is about.

Example below.

*Ref 1: Network Diagram*
