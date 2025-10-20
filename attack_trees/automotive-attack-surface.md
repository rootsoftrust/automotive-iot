The attack surface for cars (especially Connected and Automated Vehicles, or CAVs) refers to the sum of all the different points or attack vectors where an unauthorized entity can potentially interact with or gain unauthorized access to the vehicle's systems, software, data, or network.

Due to the increasing integration of electronics, software complexity, and high connectivity, the attack surface of modern vehicles has increased enormously, making them vulnerable to cyberattacks. Since cars are now exposed at their boundaries, security must be an integral part of their design.

The attack surface can be broadly classified based on the location of the interface (internal vs. external) and the method of access (wired/physical vs. wireless/remote).

<h1>I. External and Wireless Attack Surfaces (Remote Access)</h1>
Wireless connections are changing the game, as they form new entry points for hackers into the vehicle networks, removing the need for physical proximity to attack the vehicle at scale.

<h3>Vehicle-to-Everything (V2X) Communication:</h3> This general category encompasses all communication between the vehicle and external entities. V2X communication is considered a big risk to the car because every wireless interface opens the door for remote attacks.

<h3>V2V (Vehicle-to-Vehicle) and V2I (Vehicle-to-Infrastructure) Interfaces:</h3> These communication technologies (like DSRC/802.11p and cellular V2X) are designed to exchange information for safety and traffic efficiency applications. Attack surfaces include the DSRC-Based Receiver.

<h3>V2N (Vehicle-to-Network) / Cellular Connectivity:</h3> Systems utilizing public mobile phone networks (GSM, UMTS, LTE, 5G) for far-field communication, remote services (like remote diagnosis), and providing Internet access. The cellular interface is a significant attack surface.

<h3>Short-Range Wireless Interfaces:</h3> These interfaces allow unauthorized access remotely without physical contact.

<h3>Bluetooth and Wi-Fi:</h3> Used for connectivity, infotainment applications, and telematics. Exploiting the Wi-Fi connection can gain remote access to the in-vehicle network.

<h3>NFC (Near Field Communication):</h3> Rapidly adopted by vehicle manufacturers and used for communication.

<h3>Remote Key Systems:</h3> Communication systems for keyless entry/start, including wireless key fobs and Remote Link Type Apps. Manipulation of functions designed to remotely operate systems, such as the remote key and immobilizer, is a vulnerability.

<h3>TPMS (Tire Pressure Monitoring System):</h3> Radio sensors used for internal communication are attack surfaces.

<h3>Cloud and Back-End Services:</h3> The vehicle's connection to the Internet and external networks, such as the back-end servers and cloud platforms, creates an entry point.

<h3>APIs</h3> (Application Programming Interfaces) for third parties and applications connected to vehicles.

<h3>Hosted Third-Party Software (Apps):</h3> Corrupted applications, such as entertainment applications or those with poor software security, can be used as a method to attack vehicle systems via cloud connectivity.

<h3>Remote Operation Systems:</h3> Systems that permit remote operation (e.g., remote unlocking or starting).

<h1>II. Internal and Wired Attack Surfaces (Physical/Local Access)</h1>
These surfaces require an attacker to be in physical proximity or possess the vehicle, but provide a direct path into the internal communication networks.

Diagnostics and Maintenance Interfaces:

OBD-II Port (On-Board Diagnostics II): A wired interface, typically installed in the vehicle's interior, originally the only exception to car isolation. It is widely used for diagnostics and allows access to the in-vehicle network. The OBD port is easily accessible and a common point of attack for code injection or manipulation of vehicle parameters.

Diagnostic Port (General): Allows access to outsiders during maintenance and servicing. Most gateways offer unprotected powerful diagnostic functions and interfaces that allow complete access to the vehicular network without restrictions.

Infotainment and User-Facing Ports (IVI System): The In-Vehicle Infotainment (IVI) system is a critical component from a cybersecurity perspective, hosting the telematics interface and providing a lot of attack surfaces.

USB Ports: External interfaces where devices (like mobile phones, pen drives, or computers) are connected. They can be used to install malicious codes or update firmware with malicious code.

Multimedia Playback Systems: Software radio and audio players can be used to carry out certain types of attacks.

User Input: Data supplied directly by the user via the interface.

Meta Data: Supplementary data that could influence parsers or drivers, such as CAN or Ethernet frame IDs.

Apps (Third-Party Software): Third-party software supplied via the IVI system.

EV Charging Ports: Electric Vehicle (EV) charging ports are connection points where vehicles may be susceptible to attacks via the charging infrastructure when charging.

Physical ECU and Hardware Access Points: Physical attacks can target hardware security mechanisms. Internal attackers (like garage personnel or the owner) have full physical access to the internal components and transmission media of the automotive network.

ECU Interfaces and Components: The ECUs themselves and their communication interfaces are the primary targets.

Hardware Attack Surface Spots: These can be tampered with only via physical access.

Boot Memory: Storage that could allow the execution of attacker-supplied code, such as EEPROM or external flash memory.

Debug Interfaces (e.g., JTAG): Ports not used in regular operation but used during development, which allow deep analysis and manipulation.

Inter-Chip Communication Channels: Data exchange links inside an ECU (e.g., UART, I2C, SPI) that could be revealed and tampered with.

Side Channel Attack points: Measuring or manipulating an ECU physically (e.g., power glitches) for information gathering or control flow change.

Unused Hardware: Superfluous internet ports left open, providing access to network systems.

<h1>III. Internal Network Architecture and Vulnerable Components</h1>
The complexity of the internal network topology, particularly the interconnection of heterogeneous bus systems via gateways, significantly increases the attack surface.

In-Vehicle Communication Networks (IVN): The underlying protocols themselves are vulnerable if they lack security mechanisms.

CAN Bus (Controller Area Network): Used for soft real-time communication for safety-critical components like ABS and engine management. It is virtually unsecured against malicious encroachments because messages are unencrypted and controllers cannot verify the sender's identity. An attacker can gain control of safety-critical functions such as steering or braking if they gain access to the vehicle bus system.

LIN (Local Interconnect Network): Used for local sub-networks (e.g., window control, door locking).

FlexRay: Time-triggered hard real-time bus systems used for highly safety-relevant areas such as drive-by-wire systems (steering, braking).

MOST (Media Oriented Systems Transport): Multimedia bus systems used for in-car entertainment.

Ethernet / BroadR-Reach: Used for high-bandwidth applications and telematics.

Gateways and ECUs (Electronic Control Units):

Gateway ECU/TCU (Telematics Control Unit): These devices interconnect diverse networks and act as the bridge between internal systems and the external world. Vulnerabilities in these gateways allow attackers to bypass protections and gain access to other network segments to perform malicious acts. If a hacker gains access to the TCU, they can potentially send spoofed CAN messages and gain control of safety-critical items.

Individual ECUs: Modern cars contain a multitude of controllers (up to 100 ECUs) that may contain vulnerabilities. The attack surface of an ECU includes the sum of the interaction opportunities with it, such as accessible services, inbound communication, and I/O and hardware interfaces.

Safety-Critical ECUs: Such as Engine and Transmission ECUs, Steering and Braking ECUs, Airbag ECUs, and ADAS System ECUs.

Reflash Routines: The mechanisms used to replace an ECU’s software with a supplied flash image are attack surfaces.

Sensors and Actuators: Automated Driving Systems (ADSs) rely heavily on sensors, which are perception channels that create a large and highly vulnerable attack surface.

Lidar, Radar, and Camera Systems: Vulnerable to tampering and manipulation, including sensor-level attacks and physical-world attacks (e.g., objects mounted to hide the vehicle from Lidar).

In-Vehicle Sensors: Devices like magnetic encoders or inertial sensors.

This extensive attack surface requires a defense-in-depth strategy, addressing security across multiple architectural layers (interfaces, gateways, networks, and components).
