# BSNL-CAN-Internship
A Campus Area Network for an Engineering college using Virtual Local Area Network(VLAN) with Physical Network Security implementation and connectivity of Internet with wired and wireless access.

This repository contains the final .pkt file of my project for my summer internship with Bharat Sanchar Nigam Limited(BSNL).

## PROJECT DESCRIPTION

In this project, I have designed a college Campus Area Network with VLANs with different Hosts and Departments as per the following requirements. 

-College campus is a (Ground + 4)5 Floor building.

-Ground Floor has a 100Mbps connectivity to ISP for Internet with a CISCO 2811 Router with a single LAN port . 

-First, Second, Third and Fourth floors have Hosts belonging to CSE/IT/ECE/EEE departments related to I year, II year, III Year and Final year students class rooms. Each Floor has a switch connecting these hosts.

-Switch from the top floor is connected directly to its next floor switch and finally from the First floor switch, a cable is extended to ground floor to the LAN port of CISCO Router 2811.

-Administrator has been asked to configure the departments in different VLAN domains and also instructed that the communication between the departments is also required.

-Administrator has been asked to place an Access point for wireless connectivity with security password from the Fourth Floor on need basis

-Administrator has been asked to create security credentials for login to the Router and Switches such that authorized person only logs in.

-Administrator has been asked to make sure that if anyone connect a host in the vacant ports of switch in any floor they should not work.

-Administrator has been asked to allocate 40 Mbps bandwidth to CSE department, 30 Mbps bandwidth to IT department, 20 Mbps bandwidth for ECE department & 10 Mbps bandwidth to EEE department for Internet access.

-ISP has given 10.10.10.0/30 subnet to college and asked the college administrator to configure the WAN link IP 10.10.10.1 at College side WAN interface on the router. The Internet IP pool given to college is 117.117.117.0/29.

-Administrator has been instructed to make sure that all computers available in the campus should be connected with Internet.
