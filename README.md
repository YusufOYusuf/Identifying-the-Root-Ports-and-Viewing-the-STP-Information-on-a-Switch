<h1>Identifying the Root Ports and Viewing the STP Information on a Swtich</h1>


<h2>Description</h2>
In this lab, I learned to identify the root ports and view the STP information of a switch. STP (Spanning Tree Protocol) enables switches to become aware of other switches through the advertisement and receipt of BPDUs (bridge protocol data units). STP builds a layer 2 loop-free topology in an environment by temporarily blocking traffic on redundant ports.
<br />



<h2>Environments Used </h2>

- <b>Ubuntu 20.04.2 LTS</b> 
- <b>PuTTY SSH Client</b>

<h2>Program walk-through:</h2>

<p align="center">
From the left sidebar click PuTTY SSH Client and proceed to put in the IP address, port number, click Telnet and then click open: <br/>
<img src="https://i.postimg.cc/jjH6B1cw/Screen-Shot-2022-08-13-at-9-39-24-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
In the IOU1 terminal window type the "en" command to enter into enable mode <br/>
Then type "show spanning-tree root" to identify the root port
<img src="https://i.postimg.cc/3xJkFJfc/Screen-Shot-2022-08-13-at-9-42-11-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
In the IOU1 terminal windwo type "show spanning-tree vlan 1" command to view STP information <br/>
<img src="https://i.postimg.cc/Y92DpFdx/Screen-Shot-2022-08-13-at-9-46-09-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />






  
  
 

  
  
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
