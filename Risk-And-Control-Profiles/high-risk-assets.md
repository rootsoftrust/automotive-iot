The systems and components within cars and connected vehicles that have high protection needs are primarily those whose compromise would lead to catastrophic failures, severe financial damage, loss of intellectual property (IP), or major violations of safety and privacy (SFOP).

These high-protection-needs systems are identified through Threat Analysis and Risk Assessment (TARA). The ISO 26262 standard assigns high criticality levels, such as Automotive Safety Integrity Level D (ASIL-D), to systems with the most stringent requirements.

Here is a list of vehicle systems and components that require a high degree of protection:

<h1>I. Safety-Critical Systems (ASIL-C/D)</h1>
Compromise of these systems can result in functional failure leading to severe injury or death.

Primary Car Functions: Basic car functions, such as engine control, steering, and braking systems, require strong protection. The component responsible for braking and acceleration is highly critical.

Drive-by-Wire Systems: Future systems like Steer-by-Wire (SbW) and Brake-by-Wire fully depend on the underlying automotive data networks and demand high protection.

Automated Driving Systems (ADSs) / ADAS ECUs: The software and Electronic Control Units (ECUs) supporting autonomous driving functionalities are safety critical units. This includes the Advanced Driver Assistance Systems (ADAS) ECU, which processes data from sensors and makes decisions, such as the system used in Autonomous Emergency Braking (AEB). ADAS systems require high reliability, especially for data transmission.

Airbag and Restraint Systems: Components like airbag ECUs are critical and highly valuable. Delays in the messages from impact sensors to airbag deployment systems due to security overhead could be catastrophic.

Components with Fail-Operational Requirements: The architecture of systems like the RACE core platform must provide the basis for functions with fail-operational requirements and guarantee correct execution even if a subsystem fails.

Electronic Stability Program (ESP): This is a valuable component that needs strong protection measures.

<h1>II. Components Handling Cryptographic Secrets and Identity</h1>
These systems are crucial for establishing trust, integrity, and preventing large-scale attacks through cloning or manipulation.

Cryptographic Modules/Keys: Devices that store and use secret cryptographic keys must be protected, as obtaining the key allows the device to be manipulated and/or cloned. This requires the use of tamper-resistant memory.

Security Anchors (HSM/SHE/TPM): Dedicated hardware security modules, such as Secure Hardware Extension (SHE) or Hardware Security Modules (HSM), and Trusted Platform Modules (TPM), are designed to protect critical keys and operations. These require a secure platform to avoid manipulation.

Electronic Immobilizers and Key Systems: Theft protection systems, including the electronic immobilizer, are high-protection assets because they handle driver authentication and critical data.

Motor Control Unit and Transponder: The motor control unit needs protection against disclosure and modification of secret initialization data, and its substitution should be detectable. The transponder (key) also requires protection against disclosure and modification of its initialization data.

<h1>III. Data and IP Protection Assets</h1>
These assets require high security measures to protect proprietary business information and user privacy.

Proprietary Software/IP: Copyright or proprietary software extracted from vehicle systems represents a financial asset requiring protection against reverse engineering and product piracy. Confidentiality must be enforced to protect new algorithms from competitors.

Vehicle Data Recorders: Legal applications like the digital tachograph (for trucks) and Event Data Recorders (EDR) collect, store, and retrieve data with financial, legal, and personal meaning. This data must be protected against alteration and requires secure storage.

Data Related to Feature Activation: Software enabling feature activation (e.g., enhanced engine performance or comfort functions) requires strong security measures to protect the underlying business model against unauthorized activation.

Tachograph Components: The components of the digital tachograph system, including the on-board unit, are specifically noted to have high protection needs and must not be manipulable at any time. These components must achieve a security certificate with a confirmation of "high" strength.

<h1>IV. Connectivity and Gateways</h1>
These components function as bridges and, if compromised, expose safety-critical domains to remote attackers.

Secure Gateways (SG): The gateway ECU acts as a bridge between diverse networks and often isolates the Infotainment system (IVI) from the safety-critical ECUs. The central gateway must be protected to shield the safety-critical functions.

Software Update Mechanisms: Since software updates and flashing routines are critical for liability, warranty, and business, the process and the mechanisms used to deliver and authenticate them must be secured with a high level of environmental security.

V2X Communication: Given the crucial role of V2X (Vehicle-to-Vehicle and Vehicle-to-Infrastructure) in time-critical road safety applications (like collision avoidance), the messages exchanged require extremely high reliability, integrity, and authenticity.

<h1>V. Components with Restricted Resources</h1>
Systems with small processors, limited memory, and tight cost requirements often face physical security challenges because they are susceptible to physical attacks like side-channel or reverse-engineering attacks intended to steal secrets. These limitations mean that implementing sufficient security mechanisms is especially challenging, making them highly vulnerable if protection is not robust.
