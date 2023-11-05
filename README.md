# Intent-Based-Network-Management-Automation
This is the Intent-Based Network Management Automation in 5G Networks.

![github image](https://github.com/IBN-based-5G-Management-Automation/ibnbased5gmanagement/assets/47199564/5b35ba69-562c-4b36-854d-9645c659ecda)

**(Objective)**

IBN User sends a configuration file to 5G Core Network.

5G Core Network changes its internal policy according to the configuration file. 

&nbsp;

**(Installation guide)**

Open5gs: https://open5gs.org/open5gs/docs/guide/02-building-open5gs-from-sources/

srsRAN: https://docs.srsran.com/projects/4g/en/latest/general/source/1_installation.html

&nbsp;

**(Construction of Testbed)**

1. Install Open5gs, srsRAN22.04, MongoDB, and the dependencies

2. Modify Open5gs configuration (AMF and UPF) 

3. Modify srsRAn22.04 configuration (enb.conf and rr.conf)

4. Add SIM information (imsi, key, and opc) on both Open5GS and srsUE

5. Create the TUN device with the interface name ogstun

6. Run Open5GS, gNodeB, and srsUE

&nbsp;

**(specific configuration setting)**

**Open5gs setting**

1. sample.yaml file setting
2. Adding USIM informaiton
3. Setting up TUN device and running Open5gs


**srsRAN setting**

4. Installing srsRAN configure files
5. Modify enb.conf file
6. Modify rr.conf file


**srsUE setting**

7. Modify ue.conf file


**Running Open5gs + srsRAN + srsUE**

8. Run Open5gs 5gc file and srsRAN enb.conf file
9. Run srsUE file
10. check the connection between Open5gs + srsRAN and srsUE

&nbsp;

**Demo Youtube video**

https://www.youtube.com/watch?v=DSxbhpWRvaI

