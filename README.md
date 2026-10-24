# CCNA-Study---Lab-2

<h1>Lab 2 - Connecting devices</h1>

<h2>LAB INSTRUCTIONS:</h2>

Connect the network devices together according to the labels.

Use the appropriate type of cable .

For practice, assume that Auto MDI-X is disabled, or not supported on the devices.

NOTE: Packet Tracer and switch lab.dev doesn't differentiate between single-mode 
and multimode fiber, but think about which one is appropriate when you 
use a fiber connection.

<h2>Lab description and objectives</h2>

UTP or ethernet cabling can be straight through or crossover cabling. Most modern devices have evolved and use Auto MDI-X to auto detect whether data is being transmitted or received. For this lab, we will assume that Auto MDI-X is disabled so straight through vs crossover cabling is important here. 

Routers, firewalls, and PCs transmit data on pins 1 and 2 and they receive data on pins 3 and 6. Switches, on the other hand transmit data on pins 3 and 6 and receive data on pins 1 and 2. Who connecting devices that transmit and receive data on the same pins a crossover cable is needed. 

UTP has a distance limit of ~100m.

Multi-mode fiber has a distance limit of ~550m.

Single-mode fiber has a distance limit of ~30km and is the most expensive. 

<h2>Lab start in Packet Tracer</h2>

<img width="734" height="450" alt="Screenshot 2026-10-24 at 12 04 20 PM" src="https://github.com/user-attachments/assets/cb04ac56-99d4-44b9-92f3-0de4baa1de3a" />

<h2>Lab start in Switchlab.dev</h2>

<img width="986" height="614" alt="Screenshot 2026-10-24 at 1 18 50 PM" src="https://github.com/user-attachments/assets/b77a99ac-1a30-42c8-9cab-8ee167d6c703" />

<h2>Cales connected in Switchlab.dev</h2>

R1-R3 (3 km distance) : Single-mode fiber

R1-R2 (50 m distance) : UTP Crossover

R2-SW1 : UTP Straight through

R2-SW2 : UTP Straight through

SW1-SW2 : UTP Crossover

SW1-SW3 : UTP Crossover

SW2-SW4 : UTP Crossover

SW3-PC1 : UTP Straight through

SW4-PC2 : UTP Straight through


R3-R4 (250 m distance) : Multi-mode fiber

R4-SW5 : UTP Straight through

R4-SW6 : UTP Straight through

SW5-SW6 : UTP Crossover

SW5-SW7 : UTP Crossover

SW6-SW8 : UTP Crossover

SW7-PC3 : UTP Straight through

SW8-SRV1 : UTP Straight through


<img width="838" height="528" alt="Screenshot 2026-10-24 at 1 37 39 PM" src="https://github.com/user-attachments/assets/2bd6a99b-c657-4ba8-9781-a5dec3bcf8e4" />
