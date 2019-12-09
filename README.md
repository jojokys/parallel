# WQD7008 Parallel and Distributed Computing Project

## Project Title
Image Classification with Spark in Raspberry Pi
Image Processing with Hadoop in Raspberry Pi Cluster

## Team Members
- WQD180041 - MUHAMMAD HAFIZ BIN KHAIRUDIN
- WQD190039 - JONATHAN KOW YEE SENG
- WQD170100 - SYAIFUL ANUAR BIN ABD LATIF
- WQD180061 - XUXIANG
- WQD180027 - LIM SHIEN LONG

## 1. Introduction


## 2. The objective of the project (Hafiz)
- Build a cluster of machines
- Delegate work for the machines using a distributed storage and processing framework
- Orchestrate the communication between the machines using a central server
- Build edge computing node that transfers data to cluster

## 3. Scenario
<suggestions - where and why apply image classification with edge node>
common/commercially available example (may not want to use this but just as example) - home security, identify/classify person at door is authorized for entry.

idea1 - automated farming, chillie farms with automated robots that capture images of each chillie and classify as ready/not ready for picking. 
idea2 - remote environment monitoring, ie: monitor changing terrain to identify soil movement
idea3 - 

## 3. Methodology (Hafiz)
![alt text](https://github.com/shienlong/parallel/blob/master/Archi04.PNG)


Phase 1: Data Acquisition

- what type of data, format of data
- where obtain data from

Phase 2: Edge Pi

- what is happening in this phase...

Phase 3: HDFS (consist of namenode & datanode)

- what is happening in this phase...

Phase 4: Visualization

- what is the output


## 4. Explanation of all the components being involved in the project. Adjustment of why these components are being used. (Hafiz)

### Wireless Router
- Serve as a router and wireless access point
- Provide private wireless network
- Provide internet access to all the machines
- Why:
  - The main advantage of using private wireless network in this setup is we can maintain the internal IPs of the machines at all time and avoid dealing with connectivity issues

### Virtual Network Computing
- A GUI software that uses Remote Frame Buffer Protocol (RFB) to control other computers by transmitting all the mouse and keyboard events from the origin (VNC Server) to the target (VNC Client)
- Why:
  - Make it easier to interact with display-less computers like Raspberry Pi
  - 

### Laptop (Windows 10 machine)
- Act as the VNC server

### Raspberry Pi 4 (Model B)
- Low-cost compute unit
- Wifi support
- Come with Raspbian OS (Linux) easier to run applications like Hadoop and Node-RED
- 4GB SDRAM
- Why:
  - Running Hadoop framework (both namenode/datanode)
  - Act as a VNC client
  - Edge computing node

### Node-RED
- It's a programming tool to wire together hardwares devices, APIs and online services
- Why:
  - Comes with a very friendly browser-based flow editing
  - Rich ecosystem of flows that are shared by the community
  - Light-weight runtime (built on Node.js), so it's ideal for Raspberry Pi 


## 5. Results (visualization) and discussion about findings. here you should also include a roadmap of each objective that has been addressed.


## 6. Conclusion

## 7. References
