The National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF) provides a risk-based structure for managing and reducing cybersecurity risks. When applied to automotive cyber assets—which include physical components (ECUs, sensors), software, data, and critical functions—the NIST CSF's six core Functions (Govern, Identify, Protect, Detect, Respond, and Recover) must be tailored to address the unique constraints, complexity, and safety criticality of Connected and Autonomous Vehicles (CAVs).

Automotive manufacturers (OEMs) and suppliers use frameworks like NIST in alignment with industry standards such as ISO/SAE 21434 (Cybersecurity Engineering) and UNECE R155 (Cyber Security Management System or CSMS), which mandate similar structured, life cycle risk management approaches.

Here is a process to apply the NIST CSF to automotive cyber assets, derived from the CSF core functions:

<h2><b>1. GOVERN (GV):</b></h2> Establish Strategy and Organizational Context
The Govern function establishes the organizational context, policy, and strategy for cybersecurity risk management. In the automotive domain, this function ensures that security processes align with safety goals and regulatory mandates throughout the vehicle's long life cycle.

<h3><b>Establish Organizational Context (GV.OC):</b></h3> Understand the environment, mission objectives, stakeholder expectations, dependencies, and legal/regulatory requirements surrounding cybersecurity decisions. Automotive manufacturers must consider adherence to UNECE R155 and ISO/SAE 21434, which govern cybersecurity management and engineering.

Define Strategy and Policy: Develop a strategy for managing cybersecurity risk that integrates seamlessly into the overall enterprise risk management. This includes ensuring that the security process remains robust throughout the vehicle's total life cycle, which can be long.

<h3><b>Manage Supply Chain Risk (GV.SC):</b></h3> Identify and prioritize critical suppliers (Tier 1, Tier 2, etc.) and integrate cybersecurity requirements into contracts and agreements with these third parties who provide hardware (ECUs), software, and embedded devices. Manufacturers must collect and verify information required through the supply chain to demonstrate that supplier-related risks are identified and managed.

<h2><b>2. IDENTIFY (ID):</b></h2> Understand and Manage Cyber Risks
The Identify function develops an understanding of the cyber risk to organizational assets, including data, hardware, software, and people, allowing efforts to be prioritized. This phase heavily relies on Threat Analysis and Risk Assessment (TARA) methodologies.

<h3><b>Asset Management (ID.AM):</b></h3> Maintain inventories of all critical vehicle cyber assets and manage them throughout their life cycles. Automotive assets include:

Physical Assets: ECUs (e.g., Engine, Braking, Airbag ECUs), sensors, actuators, and hardware components (like Trusted Platform Modules or TPMs).

Logical Assets: Firmware, control system software, CAN frames, and cryptographic keys/secrets.

Data Assets: Payment credentials, activation keys, proprietary IP, and personal data (PII/location information).

<h3><b>Risk Assessment (ID.RA):</b></h3> Conduct TARA to identify and understand vulnerabilities and cyber threats.

Threat Identification: Identify threat scenarios by analyzing attack paths. Tools like STRIDE (Spoofing, Tampering, Repudiation, Information disclosure, Denial of service, Elevation of privilege) or ATA can be used to identify threats against specific system components.

Risk Calculation: Estimate the consequences for a potential security breach based on Impact (often using SFOP: Safety, Finance, Operations, Privacy) and Attack Feasibility. This step determines the risk level.

Security Requirements Derivation: Use the risk level to establish cybersecurity goals, claims, and derived requirements. For instance, highly safety-critical applications (ASIL-D based on ISO 26262) are assumed to have higher security requirements.

<h3><b>Cyber Threat Intelligence (ID.RA-02):</b></h3> Integrate cyber threat intelligence from information sharing forums and sources to keep the risk assessment current.

<h2><b>3. PROTECT (PR):</b></h2> Implement Safeguards and Defenses
The Protect function employs safeguards to manage cybersecurity risks, focusing on preventing or lowering the likelihood and impact of adverse events. This requires implementing a Defense in Depth strategy across multiple architectural layers.

<h3><b>Secure Architecture and Infrastructure Protection (PR.IR):</b></h3> Implement a multilayered framework to protect vehicle systems:

Layer 1: Secure Interfaces: Securely connect the vehicle to the external world. This involves securing wireless interfaces (V2X, cellular, Wi-Fi) and physical interfaces (e.g., OBD-II port, USB ports). Secure elements and specific authentication should be added to the TCU and OBD to provide maximum protection.

Layer 2: Secure Gateway(s): Use Secure Gateways (SGs) to provide domain isolation within the vehicle network, ensuring unauthorized access cannot tamper with safety-critical nodes.

Layer 3: Secure Networks: Secure communication between control units (ECUs). This involves message authentication, filtering, and implementing secure protocols, such as AUTOSAR's Secure On-Board Communication (SecOC), to protect the integrity and authenticity of messages on buses like CAN and FlexRay.

Layer 4: Secure Processing Units: Protect the ECUs (the "brains" of the car). Implement security primitives like secure boot and real-time integrity checking to ensure code is authentic and unaltered. Specialized tamper-resistant hardware (TPMs, SHE, HSMs) protects cryptographic keys.

<h3><b>Data Security (PR.DS):</b></h3> Protect the integrity and confidentiality of data. This includes utilizing cryptographic techniques like digital signatures for authenticity, and hybrid encryption for confidentiality.

<h3><b>Identity Management and Access Control (PR.AA):</b></h3> Manage identities and credentials for authorized users, services, and hardware, enforcing policies based on the principle of least privilege. Access control mechanisms prevent unauthorized access to restricted vehicular data or resources.

<h3><b>Maintenance (PR.MA):</b></h3> Implement processes to manage vulnerabilities and apply authenticated firmware updates and software patches throughout the vehicle life cycle.

<h2><b>4. DETECT (DE):</b></h2> Identify Cybersecurity Events
The Detect function enables the timely discovery and analysis of anomalies and potential adverse events. Since attacks can be active and adaptive, continuous monitoring is crucial.

Continuous Monitoring: Ensure monitoring is continuous and includes vehicles after first registration.

<h3><b>Anomaly and Intrusion Detection Systems (IDS):</b></h3> Deploy hardware or software-based systems to actively monitor the in-vehicle network without human intervention. This includes:

Monitoring network traffic for anomalous behavior.

Utilizing Machine Learning (ML) algorithms (such as recurrent autoencoders or deep learning models) to learn the normal system behavior at design time and detect deviations at runtime.

Employing lightweight IDS mechanisms due to the resource-constrained nature of automotive ECUs.

<h3><b>Data Collection and Analysis:</b></h3> Monitor for, detect, and analyze cyber threats, vulnerabilities, and cyber-attacks using vehicle data and vehicle logs.

<h3><b>Incident Declaration (DE.AE-08):</b></h3> Define incident criteria and formally declare incidents when adverse events meet those criteria.

<h2><b>5. RESPOND (RS):</b></h2> Take Action on Detected Incidents
The Respond function supports the ability to contain the effects of cybersecurity incidents.

<h3><b>Incident Management (RS.MA):</b></h3> Manage the response to detected cybersecurity incidents, coordinating activities with internal and external stakeholders.

<h3><b>Mitigation (RS.MI):</b></h3> Perform activities to prevent the expansion of an event and mitigate its effects. Response plans should include options for reverting malicious commands or disabling compromised connectivity modules. Identified threats and vulnerabilities that require a response must be mitigated within a reasonable timeframe.

<h3><b>Communication (RS.CO):</b></h3> Share information with designated internal and external stakeholders, including ISPs, attack device owners, and service providers.

<h2><b>6. RECOVER (RC):</b></h2> Restore Affected Capabilities
The Recover function supports the timely restoration of normal operations to reduce the effects of cybersecurity incidents. This function emphasizes the system's ability to restore services and capabilities.

<h3><b>Recovery Planning (RC.RP):</b></h3> Maintain and execute plans for resilience and restoration of impaired capabilities or services. Recovery plans may include safely executing software updates (OTA), system patching, and data restoration.

<h3><b>Resilience and Adaptation (RC.RP-03/05):</b></h3> Verify the integrity of backups before using them for restoration. Restoration activities should enable the system to recover from and adapt to adverse conditions. Recovery activities should be improved by incorporating knowledge gained from current activities into future activities.
