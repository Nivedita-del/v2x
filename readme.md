# Problem statement
Simulation of V2X communication system using DSRC framework with WLAN and Analysis of how vehicles transfer data within less period time.

# Introduction

* V2X is a technology not only allows vehicles to “talk” to each other but also gets the information from environment.
* V2X are an emerging type of networks in which nearby vehicles exchange the data wirelessly in real time.
* They share information like traffic updates, collision to ensure a safer and more comfortable drive.


# Motication
* In the current scenario, 5g technology is used for network communication in autonomous cars. Due to this technology there’s a communication lag between two systems. To resolve this problem we are using WLAN (wireless local area network) with DSRC (Dedicated short range communication technology .
* 5g is an open network .Open networks are usually prone to hacking. To resolve this we use WLAN with security.
* In the present technology there’s a latency (such as processing delay and delay due to contention) in communication. In this project we’ll use faster WiFi modules and reduce the latency in order to achieve seamless connection.

# Objectives

* Design and simulation of the environment files using OMNETT++.
* Building of the network communication system using SUMO.
* Development and implementation of code for behavioral pattern setting.
* Implementation of V2X communication and analysis of the complete system.

# Methodology

* Setting Up OMNET++ and linking it with GCC, configuring terminal with G++ path and OMENT++ path.
* Once the configurations are done, a gui-controller gets initiated where communication between the cars and the environment (i.e traffic signals, collision information etc) is visible.
* Using OMNETT++, environment (ie .env) files can be created to simulate cars and environment (i.e maps, trees, road).
* Generating a DSRC network framework which consist of junction (i.e nodes), server can be done using SUMO.

# Tools Required

* C Language
* Python
* OMNETT++
* Sumo
* Network simulator (used in OMNETT++)
* Matlab lib (used in OMNETT++)

# Simulation

<a href="https://www.youtube.com/watch?v=ydfMuaADFxc" target="_blank"><img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Faminoapps.com%2Fc%2Fthe-ink-machine%2Fpage%2Fblog%2Fclick-here-gif%2FMQdg_Qe2Iku7wKEqBLRXxrMJXq8gbwznv50&psig=AOvVaw2s8lpt62YVNg5L4EVglcf5&ust=1604381232746000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCLiRsYmQ4-wCFQAAAAAdAAAAABAE" alt="Click me" width="240" height="180" border="10" /></a>


# Reference

* Byun Seungbok , Kang Sangpil , Hong Choulhee , Kim Heeyoung ; Kim yoongi “Design of a V2X Vehicle Antenna” Date of Conference: 23-26 Oct. 2018, ISBN: 978-89-5708-304-8

* Erwin Anggadjaja , Ian Mcloughlin “Point-to-Point OMNeT++ Based Simulation of Reliable Transmission Using Realistic Segmentation and Reassembly with Error Control” Date of Conference: 2-3 Dec. 2010 ISBN: 978-1-4244-8746-2 .

* Mohammad Kawser, Syed Safwan Sajjad, Saymon Fahad, Sakib Ahmed “The Perspective of Vehicle-to-Everything (V2X) Communication towards 5G” JSCNS International Journal of computer Science and network security VOL.19 No.4, April 2019.

* Muhammad Ali Imran ; Yusuf Abdulrahman Sambo ; Qammer H. Abbasi “Evolution of Vehicular Communications within the Context of 5G Systems” Publisher:Wiley-IEEE Press ISBN: 9781119515579 , 2019
