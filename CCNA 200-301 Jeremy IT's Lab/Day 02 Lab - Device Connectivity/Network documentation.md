Network Documentation: Day 02 Lab – Device Connectivity
Objective
Connect the network devices together according to the labels.

Use the appropriate type of cable .

For practice, assume that Auto MDI-X is disabled, or not supported on the devices.

NOTE: Packet Tracer doesn't differentiate between single-mode 
and multimode fiber, but think about which one is appropriate when you 
use a fiber connection.

Network Topology Overview
The following devices are included in the network setup:
•	Routers: R1, R2, R3, R4
•	Switches: SW1, SW2, SW3, SW4, SW5, SW6, SW7, SW8
•	Computers: PC1, PC2, PC3
•	Server: SRV1

Cabling Specifications
The types of cables used for connections are:
1.	Unshielded Twisted Pair (UTP) – Straight-through cable
2.	Unshielded Twisted Pair (UTP) – Crossover cable
3.	Fiber Optic Cable – Single-mode
4.	Fiber Optic Cable – Multimode

Device Connections
Below is a detailed list of device connections, port assignments, and cable types:
1.	PC1 to SW1
o	Cable: UTP Straight-through
o	Ports: PC1 (Fa0) ↔ SW1 (Fa0/1)
2.	PC2 to SW2
o	Cable: UTP Straight-through
o	Ports: PC2 (Fa0) ↔ SW2 (Fa0/1)
3.	PC3 to SW7
o	Cable: UTP Straight-through
o	Ports: PC3 (Fa0) ↔ SW7 (Fa0/1)
4.	SRV1 to SW8
o	Cable: UTP Straight-through
o	Ports: SRV1 (Fa0) ↔ SW8 (Fa0/1)
5.	SW3 to SW1
o	Cable: UTP Crossover
o	Ports: SW3 (Fa1/1) ↔ SW1 (Fa0/1)
6.	SW4 to SW2
o	Cable: UTP Crossover
o	Ports: SW4 (Fa1/1) ↔ SW2 (Fa0/1)
7.	SW7 to SW5
o	Cable: UTP Crossover
o	Ports: SW7 (Fa1/1) ↔ SW5 (Fa0/1)
8.	SW8 to SW6
o	Cable: UTP Crossover
o	Ports: SW8 (Fa1/1) ↔ SW6 (Fa0/1)
9.	SW1 to SW2
o	Cable: UTP Crossover
o	Ports: SW1 (Fa2/1) ↔ SW2 (Fa2/1)
10.	SW5 to SW6
o	Cable: UTP Crossover
o	Ports: SW5 (Fa2/1) ↔ SW6 (Fa2/1)
11.	SW1 to R2
o	Cable: UTP Straight-through
o	Ports: SW1 (Fa1/1) ↔ R2 (Fa0/0)
12.	SW2 to R2
o	Cable: UTP Straight-through
o	Ports: SW2 (Fa1/1) ↔ R2 (Fa1/0)
13.	SW5 to R4
o	Cable: UTP Straight-through
o	Ports: SW5 (Fa1/1) ↔ R4 (Fa0/0)
14.	SW6 to R4
o	Cable: UTP Straight-through
o	Ports: SW6 (Fa1/1) ↔ R4 (Fa1/0)
15.	R2 to R1 (Distance: 50 meters)
o	Cable: UTP Straight-through
o	Ports: R2 (Fa2/0) ↔ R1 (Fa0/0)
16.	R4 to R3 (Distance: 250 meters)
o	Cable: Multimode Fiber Optic
o	Ports: R4 (Gig3/0) ↔ R3 (Gig2/0)
17.	R1 to R3 (Distance: 3 kilometers)
o	Cable: Single-mode Fiber Optic
o	Ports: R1 (Gig3/0) ↔ R3 (Gig3/0)
