A comprehensive risk assessment framework for automotive and cars is primarily based on the Threat Analysis and Risk Assessment (TARA) methodology. TARA is considered the efficient way to maintain systems at an acceptable level of risk, as mandated by the UNECE R155 regulation and the ISO/SAE 21434 standard.

TARA is a valuation methodology whose essence is identifying cybersecurity threats and appraising the risks associated with those determined threats. It is seen as the relevant automotive cybersecurity management tool to support the secure development of highly automated vehicles.

The standard TARA framework, particularly the TARA 1.0 process defined by ISO/SAE 21434, involves a structured series of activities that integrates threat modeling and risk scoring.

<h1>Core Components and Steps of the Automotive Risk Assessment Framework (TARA 1.0)</h1>
The ISO/SAE 21434 standard provides a detailed workflow for TARA (referred to as TARA 1.0). This process is crucial in the concept phase of automotive development and consists of several sequential activities:

<h2>1. Prerequisite: Item Definition</h2>
Before TARA activities begin, the Target of Evaluation (TOE) or Item Definition must be clarified. This step includes defining the boundaries, functions, and preliminary architecture of the item being secured, along with interfaces with internal and external items.

<h2>2. Asset Identification</h2>
This initial step involves identifying all valuable assets that need protection from malicious harm. Assets can be physical components (e.g., ECUs, sensors, actuators), software (applications running on in-vehicle devices), or communication data.

TARA 1.0 suggests that asset identification can be supported by a data flow diagram to help enumerate the assets.

Assets must be protected based on cybersecurity properties (Confidentiality, Integrity, Availability, etc.).

<h2>3. Threat Scenario Identification</h2>
This step identifies the potential causes of compromise to an asset's cybersecurity properties, which could lead to damage scenarios.

Threat scenarios can be identified through methods like group discussions among experts or systematic threat modeling approaches such as STRIDE (Spoofing, Tampering, Repudiation, Information disclosure, Denial of service, Elevation of privilege) or Attack Tree Analysis (ATA).

For example, spoofing CAN messages for the brakes ECU is a threat scenario that leads to the loss of message integrity and subsequent loss of braking functionality integrity.

<h2>4. Impact Rating</h2>
This phase involves assessing the severity of the threat. The risk impact compiles the expected loss per stakeholder.

TARA 1.0 utilizes four impact categories: Safety, Finance, Operations, and Privacy (SFOP).

The impact rating determines the severity of the consequences resulting from a security breach.

<h2>5. Attack Path Analysis and Feasibility Rating</h2>
This step determines the effort required for an attacker to successfully compromise the asset.

Attack Path Analysis: This step may use tools like Attack Tree Analysis (ATA), where the attack target is the parent node and children nodes depict the events triggering the attack. The top-down analysis showcases the attack paths.

Attack Feasibility Rating: This rating quantifies the attack difficulty, considering factors like attack ease and proximity to the asset. TARA 1.0 offers three main approaches for feasibility rating:

Attack Potential-Based: Feasibility rates are retrieved from standards like ISO/IEC 18045.

CVSS-Based: Using the Common Vulnerability Scoring System (CVSS) calculator.

Qualitative Vector-Based: Based on qualitative assessment of attack vectors.

Older methodologies like EVITA also consider the driver controllability in risk assessment, which reflects the ability of the driver or the Automated Driving System (ADS) to react in a threat scenario.

<h2>6. Risk Determination</h2>
The risk determination phase combines the impact rating and the attack feasibility rating to derive the risk value.

The risk value is typically computed as a combination or product of Impact (I) and Feasibility (F).

The result is a risk value, which is derived from the preceding analysis, and a decision must be made regarding its treatment.

<h2>7. Risk Treatment Decision and Cybersecurity Goals</h2>
Based on the determined risk value, a Risk Treatment Decision is made. The determined risks must be treated in one of four ways according to ISO 21434:

Avoid the risk: By not starting or continuing a specific activity.

Reduce the risk: By using proper security mechanisms.

Share or transfer the risk: For example, with insurance.

Accept or retain the risk: Including formulating cybersecurity claims.

The key output of the TARA 1.0 process is the derivation of Cybersecurity Goals and Claims, which then feed into updating the general vehicular cybersecurity governance. A cybersecurity goal is a requirement to protect an asset against a threat.

<h1>Key Methodologies Integrated into Automotive TARA</h1>
The ISO/SAE 21434 TARA (TARA 1.0) was developed based on or utilizes fundamental concepts from several pioneering and related methodologies:

<h4>OCTAVE (Operationally Critical Threat, Asset, and Vulnerability Evaluation):</h4> A foundation for TARA 1.0, focusing on assets, threats, and vulnerability assessments from management, organizational, and technical perspectives.

<h4>EVITA (E-safety Vehicle Intrusion proTected Applications):</h4> A pioneer in asset-based TARA for the automotive environment, evaluating risks based on severity and attack probability, often considering driver controllability. EVITA remains limited to SAE L0, L1, and L2 vehicles.

<h4>STRIDE:</h4> Used as a potential tool for identifying threat scenarios.

<h4>ATA (Attack Tree Analysis):</h4> Used to analyze attack paths.

<h4>HEAVENS (HEAling Vulnerabilities to Enhance Software Security and Safety):</h4> Adopted the EVITA methodology, aligning with ISO 26262 and SAE J3061 requirements. HEAVENS derives an asset's security level by combining the "threat level" and "impact level".

<h4>TVRA (Threat, Vulnerability, Risk Analysis):</h4> Standardized by ETSI, TVRA relies on occurrence likelihood and impact value to assess risk, generating quantified risks and mapping them to mitigation techniques.

<h4>SAHARA (Security-Aware Hazard and Risk Analysis):</h4> Combines hazard analysis methods (HARA) and threat modeling tools (STRIDE) to assess security threats over safety-critical systems, often during the vehicle conceptual phase.

<h1>Challenges and Evolving Needs in Automotive Risk Assessment</h1>
Current TARA methodologies, including TARA 1.0, face several challenges, particularly when applied to advanced CAVs:

<h4>Lack of Granularity and Readiness:</h4> Existing TARA methodologies lack granularity and are not "ready-to-use".

<h4>SAE Automation Level Distinction:</h4> Many methods remain generic and do not explicitly distinguish risk assessment per SAE automation level (L3, L4, L5). A risk that is low on SAE L3 may be high in L4 and even higher in an L5 CAV where human driver control is substituted by the ADS self-risk mitigation.

<h4>Controllability Factor:</h4> Metrics often vary, and the controllability factor (reflecting driver or ADS reactivity) remains optional in some methods.

<h4>Privacy Impact:</h4> While privacy is recognized as a critical risk, most TARA methodologies assign privacy impact a weight equal to other SFOP categories (Safety, Finance, Operations), rather than emphasizing the high privacy risks within the CAV ecosystem.

<h4>Cyber Resilience Integration:</h4> Newer methods, like PIER (Probability, Impact, Exposure, and Recovery), propose criteria like exposure and recovery in addition to probability and impact to evaluate cyber resilience and real-time follow-up measures against advanced threats. This ensures quick assessment and establishment of appropriate response strategies during ongoing attacks.

<h4>Quantitative vs. Qualitative:</h4> TARA methodologies are either Qualitative (QL), Quantitative (QT), or both. Quantitative assessments often require expert knowledge to subjectively assess scores for risk metrics.
