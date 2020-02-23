# DAAD-DST-Indo-German-Joint-Research-Collaboration-

# DAAD- DST Project First Work Package Description by the Interns at IIT Patna 
 
Running the five examples of Lena project of LTE/4G namely, lena-simple.cc, lena-simple-epc.cc, lenasimple-epc-emu.cc, lena-x2-handover.cc and lena-simple-epc-backhaul.cc. 
 
a. Run the lena-simple.cc lena-simple-epc.cc with varying number of UE node and Enb nodes and generated the .tr, .pcap, etc. files for each.  
b. Then vary the simulation time between 5s to 50s and for different numbers of UE-Enb pairs. 
c. Vary the different types of mobility (atleast 4 different mobility models) and propagation models (atleast 3 different mobility models) for the five lena-lte examples, but first use the standard Constant Position Mobility Model and any propagation model from the Multi-model spectrum channel. 
d. Then Configure the LTE model parameters for packet exchanged between pairs of UE and eNb nodes and customize the other parameters.  
e. When working on the lena-x2-handover.cc, modify the remote hosts and problem of buffer overflows due to packet transmissions happening exactly at the same time and finally generating the  .pcap file and trace files for the same. 
f. Try to implement the Frequency Reuse example, Carrier aggregation example, Radio link failure examples of user documentation of LTE in ns3 with the similar way of varying the mobility and propagation models. 
g. Furthermore, try to generate Traces of each layer (PHY, MAC, RRC, PPCP, RLC) in LTE and also finding the optimal configuration parameters for each layer of the UE, enb and EPC nodes. 
h. Try to incorporate different routing protocols, AODV, DSDV, DSR and OLSR for the UE nodes. Similar to how TS Pradeep sir managed for wireless wifi devices. It may work. 
i. Additionally, we can look for a hybrid of VANET-802.11p and LTE to use the internet based feature of LTE to model an apt vehicular environment. (future work). 
 
Try to plot the results attained with varying number of ue, enb nodes ; 
with different simulation time ; 
with different mobility and propagation models and different parameter configurations for points a to f first and then g to i later.  

# Links to understand LTE in details:- 
https://www.tutorialspoint.com/lte/index.htm 
https://www.nsnam.org/docs/models/html/lte-user.html#configuration-of-lte-model-parameters 
https://www.nsnam.org/doxygen/lena-x2-handover_8cc.html 
 
Search the questions related to LTE in the google forum, most of it is helpful. 
