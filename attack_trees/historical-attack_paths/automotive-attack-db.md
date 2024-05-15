<table>
 <tr><th>ID</th>
    <th>DESCRIPTION</th>
    <th>ATTACK TYPE</th></tr>
<tr><td> ID2010_Koscher_SSA1 </td><td> Brute force attack on security access lead to extraction of the key in 1.5 days.</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2010_Koscher_SSA2 </td><td> Deactivation of the ECU communication over CAN by using a standard diagnostic function</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2010_Koscher_SSA3 </td><td> Engine shutdown through setting the ECU into flash mode while the vehicle is driving by sending a standard command via CAN</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2010_Koscher_MSA1_Step1 </td><td> Reading memory contents from the telematics ECU without sufficient authentication</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2010_Koscher_MSA1_Step2_1 </td><td> Reverse Engineering of the firmware from the telematics ECU</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2010_Koscher_MSA1_Step4_3 </td><td> Bridging of two CAN networks by flashing modified firmware on the telematics ECU</td><td> Software Attack </td></tr> 
<tr><td> ID2010_Koscher_SSA4 </td><td> Unsafe activation of different vehicle functions by sending DeviceControl messages to different ECUs via CAN</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA1_Step1 </td><td> Firmware Extraction</td><td> Software Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA1_Step2_1 </td><td> Reverse Engineering Firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA1_Step3_2 </td><td> Memory Dump and identification of exploitable funtion pointers</td><td> Software Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA1_Step4_3 </td><td> Firmware update on ECU by a custom ISO 9660 formatted CD and Execution of any code function by exploiting a buffer overflow vulnerability in the WMA parser.</td><td> Software Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA2_Step1 </td><td> Information Gathering</td><td> Bus Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA2_Step2_1 </td><td> Reverse Engineering of Communication</td><td> Bus Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA2_Step3_2 </td><td> Unauthorized Sending of CAN messages on the bus through Wi-Fi connection to diagnostic PassThru device which is attached to OBD</td><td> Bus Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA3_Step1 </td><td> Firmware Extraction</td><td> Software Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA3_Step2_1 </td><td> Reverse Engineering Firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA3_Step3_2 </td><td> Development of malicious smartphone application for authorized user smartphone that checks for new Bluetooth connections. If a telematic device is in range the app connects to it.</td><td> Software Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA3_Step4_3 </td><td> Sending malicious Payload</td><td> Software Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA4_Step1 </td><td> Monitoring Data Traffic</td><td> Wireless Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA4_Step2_1 </td><td> Brute Forcing PIN</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA4_Step3_2 </td><td> Execution of malicious code by every connected Bluetooth device. Sending malicious messages</td><td> Software Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA5_Step1 </td><td> Firmware Extraction</td><td> Software Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA5_Step2_1 </td><td> Reverse Engineering Firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2011_Checkoway_MSA5_Step3_2 </td><td> Exploitation of a buffer overflow vulnerability over 3G interface in order to bring the telematics ECU to download additional payload code.</td><td> Software Attack </td></tr> 
<tr><td> ID2013_Miller_MSA8_Step1 </td><td> Monitoring CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_MSA8_Step2_1 </td><td> Replay of a valid CAN message to activate the open door control light in the instrument cluster</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_MSA9_Step1 </td><td> Monitoring CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_MSA9_Step2_1 </td><td> Replay of a valid CAN message to manipulate the vehicle speed displayed in the instrument cluster</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_MSA10_Step1 </td><td> Monitoring CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_MSA10_Step2_1 </td><td> Replay of a valid CAN message to manipulate the vehicle speed and the engines rotational speed displayed in the instrument cluster and changing the displayed vehicle position displayed in the navigation system</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_SSA1 </td><td> DoS-Angriff auf das CAN-Netzwerk mit CAN-ID 0, welche laut Standard nicht erlaubt ist, führt zum Ausfall der Lenkunterstützung und eines eingeschränkten maximalen Lenkwinkels</td><td> Ford).  </td></tr> 
<tr><td> ID2013_Miller_SSA2 </td><td> Denial of service attack to prevent the start of the vehicle engine by continous sending of CAN messages with ID 0</td><td> violation of CAN standard)  </td></tr> 
<tr><td> ID2013_Miller_SSA3 </td><td> Steering intervention by spoofing of a valid CAN message of the parking assistance system</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_SSA4 </td><td> Deceleration of the vehicle until standstill by spoofing of a valid pre-collision CAN message</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_SSA5 </td><td> Acceleration of the vehicle by spoofing the CAN message of the gas pedal.</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_MSA11_Step1 </td><td> Monitoring CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_MSA11_Step2_1 </td><td> Reverse Engineering Parking System CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_MSA11_Step3_2 </td><td> Steering intervention by spoofing a valid CAN message of the Intelligent Parking System.</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_MSA1_Step1 </td><td> Monitoring CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_MSA1_Step2_1 </td><td> Reverse Engineering Lane Keeping System CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_MSA1_Step3_2 </td><td> Steering intervention by replay of valid CAN messages of the Lane Keeping Assistant</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Miller_MSA2_Step1 </td><td> Extraction of the security access keys from the Parking Assistance Module or the Ford Integrated Diagnostic Software tool by Reverse Engineering of the firmware.</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_MSA2_Step2_1 </td><td> Prevent vehicle from moving by applying the brakes through a diagnostic CAN message.</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_MSA2_Step3_2 </td><td> Bleeding the brakes by spoofing a diagnotic CAN message when vehicle is slower than 5 mph</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_MSA3_Step1 </td><td> Monitoring CAN messages</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_MSA3_Step2_1 </td><td> Deactivating the lighting of the vehicle by spoofing a diagnostic message after overcoming the security access</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_MSA4_Step1 </td><td> Monitoring CAN messages</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_MSA4_Step2_1 </td><td> Engine shutdown by spoofing a modified diagnostic message.</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_SSA6 </td><td> Deactivation of the outer vehicle lighting and stoboscope effect of the inner lighting by setting the Smart Junction Box into programming mode</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_MSA5_Step1 </td><td> Breaking the security access by reverse engineering of the Toyota Calibration Update Wizard firmware.</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_MSA5_Step2_1 </td><td> Activating/Deactivating the outer lighting by spoofing a diagnostic message</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_MSA5_Step3_2 </td><td> Activating/Deactivating the horn by spoofing a diagnostic message</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_MSA5_Step4_3 </td><td> Activation of the belt tensioner by spoofing a valid diagnostic message while driving</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_MSA5_Step5_4 </td><td> Locking and unlocking the door locks by spoofing a diagnostic CAN message</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_MSA5_Step6_5 </td><td> Manupulation of fuel level displayed in the instrument cluster by spoofing a diagnostic CAN message</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_MSA6_Step1 </td><td> Extraction of the Parking Assistance Module firmware over an integrated Background Debug Mode interface.</td><td> Hardware Attack </td></tr> 
<tr><td> ID2013_Miller_MSA6_Step2_1 </td><td> Reverse Engineering Firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2013_Miller_MSA6_Step4_3 </td><td> Updating modified firmware on the Park Assistance Module in order to execute any code on the ECU to send CAN messages</td><td> Software Attack </td></tr> 
<tr><td> ID2013_Miller_MSA7_Step1 </td><td> Downloading and Reverse Engineering Firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2013_Miller_MSA7_Step2_1 </td><td> Monitoring Firmware Update</td><td> Software Attack </td></tr> 
<tr><td> ID2013_Miller_MSA7_Step3_2 </td><td> Reverse Engineering Update Algorithm</td><td> Software Attack </td></tr> 
<tr><td> ID2013_Miller_MSA7_Step4_3 </td><td> Modification of Calibration Update</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2013_Miller_MSA7_Step5_4 </td><td> Unauthorized flashing of malicious code on the engine ECU by using the diagnostic reprogramming routine</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2015_Miller_MSA1_Step1 </td><td> Reverse engneering of the OMAP chip in the WLAN module</td><td> Hardware Attack </td></tr> 
<tr><td> ID2015_Miller_MSA1_Step2_1 </td><td> Disassembling Firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Miller_MSA1_Step3_2 </td><td> Brute Forcing WLAN Password</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2015_Miller_MSA1_Step4_3 </td><td> Reverse engneering of the OMAP chip in the WLAN module and brute forcing the WLAN password. Reduction of the search room.</td><td> Hardware Attack </td></tr> 
<tr><td> ID2015_Miller_SSA1 </td><td> Update of the head unit with malicious firmware over a USB stick.</td><td> Hardware Attack </td></tr> 
<tr><td> ID2015_Miller_MSA2_Step1 </td><td> Reverse Engineering D-Bus</td><td> Bus Attack </td></tr> 
<tr><td> ID2015_Miller_MSA2_Step2_1 </td><td> Reverse Engineering D-Bus Services</td><td> Bus Attack </td></tr> 
<tr><td> ID2015_Miller_MSA2_Step3_2 </td><td> Shell-command injection over D-Bus in order to execute commands on the head unit with custom Python scripts </td><td> Software Attack </td></tr> 
<tr><td> ID2015_Miller_SSA2 </td><td> Identification of open ports by portscanning the default gateway.</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Miller_SSA3 </td><td> Detection of other vehicles by portscanning the port 6667 for different IP adresses. Vehicle worm possible.</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Miller_MSA3_Step1 </td><td> Firmware Extraction</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Miller_MSA3_Step2_1 </td><td> Reverse Engineering Firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Miller_MSA3_Step3_2 </td><td> Firmware Modification</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Miller_MSA3_Step4_3 </td><td> Flashing of the IOC chip which is reponsible for CAN communication with modified firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Miller_MSA4_Step1 </td><td> Sending CAN messages to activate update mode</td><td> Bus Attack </td></tr> 
<tr><td> ID2015_Miller_MSA4_Step2_1 </td><td> Sending CAN messages to activate bootrom mode</td><td> Bus Attack </td></tr> 
<tr><td> ID2015_Miller_MSA4_Step3_2 </td><td> Firmware Modification</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Miller_MSA4_Step4_3 </td><td> Mounting the /fs/mmc0 Partition of the Infotainment ECU and setting it writeable</td><td> in order to flash malicious </td></tr> 
<tr><td> ID2015_Miller_MSA5_Step1 </td><td> Reverse Engineering message protocol</td><td> Bus Attack </td></tr> 
<tr><td> ID2015_Miller_MSA5_Step2_1 </td><td> Reverse Engineering Firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Miller_MSA5_Step3_2 </td><td> Manipulating the turning signals, door locks and the speedometer by spoofing of standard CAN messages.</td><td> Bus Attack </td></tr> 
<tr><td> ID2015_Miller_MSA6_Step1 </td><td> Reverse Engineering the Security Access of the Park Assistence Module</td><td> PAM).  </td></tr> 
<tr><td> ID2015_Miller_MSA6_Step2_1 </td><td> Firmware Extraction</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Miller_MSA6_Step3_2 </td><td> Reverse Engineering Firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Ring_MSA1_Step1 </td><td> Monitoring CAN messages</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2015_Ring_MSA1_Step2_1 </td><td> Reverse Engineering Diagnostic Functions</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2015_Ring_MSA1_Step3_2 </td><td> Deactivating single engine cylinders by spoofing diagnostic CAN messages</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2015_Ring_MSA2_Step1 </td><td> Monitoring CAN messages</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2015_Ring_MSA2_Step2_1 </td><td> Reverse Engineering Diagnostic Functions</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2015_Ring_MSA2_Step3_2 </td><td> Activation of the chassis rodeo diagnostic function by replaying the captured diagnostic routine</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2015_Ring_SSA1</td><td> Systematische Security-Tests von KraftfahrzeugenRing--https://oparu.uni-ulm.de/xmlui/bitstream/handle/123456789/12225/Thesis_MR_OPARU.pdf?sequence=3&isAllowed=y-  </td><td>  </td></tr> 
<tr><td> ID2015_Ring_MSA3_Step1 </td><td> Monitoring CAN messages</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2015_Ring_MSA3_Step2_1 </td><td> Reverse Engineering Diagnostic Functions</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2015_Ring_MSA3_Step3_2 </td><td> Deactivation of the powertrain during driving by spoofing a CAN diagnostic message which leads to decelerate the vehicle until standstill.</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2015_Sommer_SSA1 </td><td> Portscanning the vehicle networks for ECUs, services and subroutines by sending diagnostic CAN requests and validating the responses</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2014_Rensen_MSA1_Step1 </td><td> Monitoring CAN messages</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2014_Rensen_MSA1_Step2_1 </td><td> Monitoring Security Access</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2014_Rensen_MSA1_Step3_2 </td><td> Breaking the security access by reverse engineering the data traffic and reverse engineering the the security access algorithm with extracted seed and key pairs</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2016_Lodge_MSA1_Step1 </td><td> Deauthentication of mobile device</td><td> Wireless Attack </td></tr> 
<tr><td> ID2016_Lodge_MSA1_Step2_1 </td><td> Extracting the Pre-Shared-Key of the Wi-Fi connection by brute force attack</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2016_Lodge_MSA1_Step3_2 </td><td> Monitoring WLAN connection</td><td> Wireless Attack </td></tr> 
<tr><td> ID2016_Lodge_MSA1_Step4_3 </td><td> Reverse Engineering Protocol</td><td> Wireless Attack </td></tr> 
<tr><td> ID2016_Lodge_MSA1_Step5_4 </td><td> Manipulating vehicle functions</td><td> battery charging, alarm, lighting, ) by spoofing of messages of the WLAN connection with the smart phone app of the vehicle manufacturer  </td></tr> 
<tr><td> ID2016_Lodge_SSA1 </td><td> Tracking of vehicle locations on the website www.wigle.net.</td><td> Software Attack </td></tr> 
<tr><td> ID2010_Hoppe_MSA1_Step1 </td><td> Monitoring CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2010_Hoppe_MSA1_Step2_1 </td><td> Sending malicious CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2010_Hoppe_MSA1_Step3_2 </td><td> Replay of a valid CAN message in order to open and close the window</td><td> Bus Attack </td></tr> 
<tr><td> ID2010_Hoppe_MSA1_Step4_3 </td><td> Activation of the control light in the instrument cluster by spoofing CAN messages from an emulated airbag ECU</td><td> Bus Attack </td></tr> 
<tr><td> ID2010_Hoppe_MSA1_Step5_4 </td><td> Information gathering by capturing the CAN traffic</td><td> Bus Attack </td></tr> 
<tr><td> ID2010_Rouf_MSA1_Step1 </td><td> Tracking of vehicles by triggering the TPMS sensors and capturing the responses</td><td> Wireless Attack </td></tr> 
<tr><td> ID2010_Rouf_MSA1_Step2_1 </td><td> Monitoring TPMS data traffic under real driving conditions</td><td> Wireless Attack </td></tr> 
<tr><td> ID2010_Rouf_MSA1_Step3_2 </td><td> Triggering of tire pressure warning for the vehicle driver by spoofing of TPMS messages</td><td> Wireless Attack </td></tr> 
<tr><td> ID2016_Hunt_MSA1_Step1 </td><td> Monitoring Bluetooth traffic</td><td> Wireless Attack </td></tr> 
<tr><td> ID2016_Hunt_MSA1_Step2_1 </td><td> Activation of different services</td><td> Start/Stop of charging, air conditioning, ...) by spoofing of messages.  </td></tr> 
<tr><td> ID2016_Hunt_MSA1_Step3_2 </td><td> Proxying Chrome with Burp Suite.</td><td> Software Attack </td></tr> 
<tr><td> ID2016_Hunt_MSA1_Step4_3 </td><td> Connection to random vehicles by brute forcing the Vehicle Identification Number in order to connect the smartphone app with the vehicle.</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2015_Spaar_SSA1 </td><td> Extraction of hard coded keys by dumping and reverse enginering the remote gateway firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Spaar_MSA1_Step1 </td><td> Monitoring Backend communication</td><td> Wireless Attack </td></tr> 
<tr><td> ID2015_Spaar_MSA1_Step2_1 </td><td> Unlocking the door locks by replaying the unlocking routine between the smartphone app and the backend server of the vehicle manufacturer</td><td> Wireless Attack </td></tr> 
<tr><td> ID2014_Hoppe_MSA1_Step1 </td><td> Firmware Extraction</td><td> Software Attack </td></tr> 
<tr><td> ID2014_Hoppe_MSA1_Step2_1 </td><td> Firmware Modification</td><td> Software Attack </td></tr> 
<tr><td> ID2011_Baile_MSA1_Step1 </td><td> Reverse Engineering GSM connection</td><td> Wireless Attack </td></tr> 
<tr><td> ID2011_Baile_MSA1_Step2_1 </td><td> Sending malicious messages to communicate with board computer</td><td> Wireless Attack </td></tr> 
<tr><td> ID2011_Baile_MSA1_Step3_2 </td><td> Unlocking and starting of vehicles by using a malicious SMS</td><td> Wireless Attack </td></tr> 
<tr><td> ID2011_Baile_MSA1_Step4_3 </td><td> Capturing GPS coordinates by setting um an ad-hoc GSM network and catching SMS</td><td> contains coordinates) that is sent from car to server  </td></tr> 
<tr><td> ID2010_Poulsen_SSA1</td><td> https://www.wired.com/2010/03/hacker-bricks-cars/ Poulsen----  </td><td>  </td></tr> 
<tr><td> ID2012_Howard_MSA1_Step1 </td><td> Disabling alarm and opening doors</td><td> Wireless Attack </td></tr> 
<tr><td> ID2012_Howard_MSA1_Step2_1 </td><td> Extraction of secret keys via OBD after breaking into vehicles</td><td> Software Attack </td></tr> 
<tr><td> ID2016_Miller_MSA1_Step1 </td><td> Deactivation of park assistance by setting the park assistance ECU into bootrom mode by sending CAN messages</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2016_Miller_MSA1_Step2_1 </td><td> Getting Security Access</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2016_Miller_MSA1_Step3_2 </td><td> Deleting Firmware</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2016_Miller_MSA1_Step4_3 </td><td> Sending malicious CAN messages with vehicle speed</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2016_Miller_MSA1_Step5_4 </td><td> Steering the vehicle by spoofing of park assistance CAN messages.</td><td> Bus Attack </td></tr> 
<tr><td> ID2016_Miller_MSA2_Step1 </td><td> Monitoring Flash Process</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2016_Miller_MSA2_Step2_1 </td><td> Getting Security Access</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2016_Miller_MSA2_Step4_3 </td><td> Control over steering by flashing of modified firmware on ECU</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2016_Miller_MSA2_Step5_4 </td><td> Brute Forcing Firmware Checksum during update</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2016_Miller_SSA1 </td><td> Acceleration and deceleration of the vehicle by sending valid ACC CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2016_Miller_MSA3_Step1 </td><td> Reverse Engineering Firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2016_Miller_MSA3_Step2_1 </td><td> Activation of diagnostic mode while driving</td><td> violation of diagnostic standard)  </td></tr> 
<tr><td> ID2016_Miller_SSA2 </td><td> Deceleration of the vehicle by injecting CAN messages from Pre-Collision System and ACC</td><td> Bus Attack </td></tr> 
<tr><td> ID2016_Miller_MSA4_Step1 </td><td> Sending malicious CAN messages to activate bootrom mode</td><td> Bus Attack </td></tr> 
<tr><td> ID2016_Miller_MSA4_Step2_1 </td><td> Deceleration of the vehicle by spoofing CAN message that contains the signal of the electronic parking brake</td><td> Bus Attack </td></tr> 
<tr><td> ID2016_Miller_MSA5_Step1 </td><td> Preventing vehicle from moving by spoofing CAN message of the electronic parking brake while vehicle stands still</td><td> Bus Attack </td></tr> 
<tr><td> ID2016_Miller_MSA5_Step2_1 </td><td> Sending malicious CAN messages to activate bootrom mode</td><td> Bus Attack </td></tr> 
<tr><td> ID2016_KeenLab_MSA1_Step1 </td><td> Activation of sunroof, truning signals and seat adjustment, Unlocking the car by connecting to WLAN and spoofing malicious CAN messages</td><td> Wireless Attack </td></tr> 
<tr><td> ID2016_KeenLab_MSA1_Step2_1 </td><td> Activation of</td><td> windscreen washer, outside mirror, trunk, Deceleration of the vehicle by connecting to WLAN and spoofing malicious CAN messages </td></tr> 
<tr><td> ID2012_Verdult_SSA1 </td><td> Extraction of secret keys and plaintexts by cryptoanalysis of the Hitag2 cipher</td><td> engine start possible)  </td></tr> 
<tr><td> ID2012_Verdult_SSA2 </td><td> Cryptoanalysis to reduce encryption complexity</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2012_Verdult_SSA3 </td><td> Using dependency between different sessions and a low degree determination of the filter function of the cipher.</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2013_Verdult_MSA1_Step1 </td><td> Monitoring RFID communication</td><td> Wireless Attack </td></tr> 
<tr><td> ID2013_Verdult_MSA1_Step2_1 </td><td> Reverse Engineering Cipher</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2013_Verdult_MSA1_Step3_2 </td><td> Cryptoanalysis of Cipher</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2013_Verdult_MSA1_Step4_3 </td><td> Exploiting Megamos Crypto Cipher weakness</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2013_Verdult_MSA1_Step5_3 </td><td> Exploiting immobilzers Key Update weakness</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2013_Verdult_MSA1_Step6_3 </td><td> Exploitation of weak secret keys by cryptoanalysis of the Megamos cipher</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2011_Francillon_SSA1 </td><td> Relay attack on keyless entry system of a vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2011_Francillon_SSA2 </td><td> Relay attack on keyless entry system of a vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2016_Burakova_MSA1_Step1 </td><td> Changing displayed values of different controls in the instrument cluster</td><td> oil pressure, oil temperature, fuel level, ...) by reverse engineering the CAN data traffic and spoofing false messages  </td></tr> 
<tr><td> ID2016_Burakova_MSA1_Step2_1 </td><td> Controlling vehicle speed by spoofing false CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2016_Burakova_MSA1_Step3_2 </td><td> Deactivation of engine brake by spoofing CAN message with modified parameters</td><td> Bus Attack </td></tr> 
<tr><td> ID2008_Eisenbarth_MSA1_Step1 </td><td> Analysis of Cipher</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2008_Eisenbarth_MSA1_Step2_1 </td><td> Energy measurment ECU</td><td> Hardware Attack </td></tr> 
<tr><td> ID2008_Eisenbarth_MSA1_Step3_2 </td><td> Reading Secret Key by Hardware Attack on the code hopping encoder.</td><td> Hardware Attack </td></tr> 
<tr><td> ID2008_Eisenbarth_MSA1_Step4_2 </td><td> Secret Key Derivation by Software Attack on the code hopping decoder.</td><td> Software Attack </td></tr> 
<tr><td> ID2008_Eisenbarth_MSA1_Step5_2 </td><td> Denial of Service on KeeLoq</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Davis_MSA1_Step1 </td><td> Remote Code Execution by exploiting a vulnerability of the image parser of the DAB radio</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Davis_MSA1_Step2_1 </td><td> SQL Injection on the DAB radio</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Davis_MSA1_Step3_2 </td><td> Cross-Site-Scripting on the DAB radio</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Davis_MSA1_Step4_3 </td><td> Buffer Overflow on the DAB radio</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Davis_MSA1_Step5_4 </td><td> Deactivation of</td><td> Advanced Driver-Assistance Systems </td></tr> 
<tr><td> ID2008_Iehira_MSA1_Step1 </td><td> Forcing Bit Error in CAN communication</td><td> Bus Attack </td></tr> 
<tr><td> ID2008_Iehira_MSA1_Step2_1 </td><td> Spoofing Attack Using Bus-off Attacks against a Specific ECU of the CAN Bus</td><td> Bus Attack </td></tr> 
<tr><td> ID2016_Palanca_MSA1_Step1 </td><td> Monitoring CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2016_Palanca_MSA1_Step2_1 </td><td> Denial-of-Service Attack between physical and data link layer of the CAN protocol</td><td> Bus Attack </td></tr> 
<tr><td> ID2014_Woo_MSA1_Step1 </td><td> Monitoring CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2014_Woo_MSA1_Step2_1</td><td> A Practical Wireless Attack on the Connected Car and Security Protocol for In-Vehicle CANWoo--IEEE Transactions on Intelligent Transportation Systems-  </td><td>  </td></tr> 
<tr><td> ID2014_Woo_MSA1_Step3_2 </td><td> Control of different vehicle functions by spoofing of CAN messages via Wireless connection</td><td> Wireless Attack </td></tr> 
<tr><td> ID2008_Blum_MSA1_Step1 </td><td> Sporadic Partial Jamming Attack to disrupt the WAVE</td><td> Wireless Access in Vehicular Environments) Standard network  </td></tr> 
<tr><td> ID2008_Blum_MSA1_Step2_1 </td><td> Substained Partial Jamming Attack to disrupt the WAVE</td><td> Wireless Access in Vehicular Environments) Standard network  </td></tr> 
<tr><td> ID2008_Blum_MSA1_Step3_2 </td><td> Complete Jamming Attack to disrupt the WAVE</td><td> Wireless Access in Vehicular Environments) Standard network  </td></tr> 
<tr><td> ID2013_Kim_SSA1 </td><td> LF Relay attack on keyless entry system of several vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2013_Kim_SSA2 </td><td> RF Relay attack on keyless entry system of several vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2014_Miller_SSA1 </td><td> Prevent engine start by spoofing commands via wireless connection</td><td> Wireless Attack </td></tr> 
<tr><td> ID2014_Miller_SSA2 </td><td> Deactivation of Smart Junction Box by spoofing commands via wireless connection</td><td> Wireless Attack </td></tr> 
<tr><td> ID2014_Miller_SSA3 </td><td> Prevent locking and unlocking of the vehicle, starting egnine by spoofing commands via wireless connection</td><td> Wireless Attack </td></tr> 
<tr><td> ID2014_Miller_SSA4 </td><td> Spoofing CAN messages to internal networks by spoofing commands via Bluetooth connection</td><td> Wireless Attack </td></tr> 
<tr><td> ID2014_Miller_SSA5 </td><td> Spoofing CAN messages to internal networks by spoofing commands via RDS connection</td><td> Wireless Attack </td></tr> 
<tr><td> ID2014_Miller_SSA6 </td><td> Voice recording and remote code execution by injecting commands via WLAN connection</td><td> Wireless Attack </td></tr> 
<tr><td> ID2007_Sparks_SSA1 </td><td> Bypassing TPM protection by executing software attacks</td><td> Software Attack </td></tr> 
<tr><td> ID2007_Sparks_SSA2 </td><td> Bypassing TPM protection by executing side channel attacks on TPM</td><td> Hardware Attack </td></tr> 
<tr><td> ID2007_Sparks_SSA3 </td><td> Getting the RSA key by side channel attacks on TPM</td><td> Hardware Attack </td></tr> 
<tr><td> ID2014_Miller_SSA7 </td><td> Control over many vehicle functions by building a testbench and spoofing of CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2014_Miller_SSA8 </td><td> Control over many vehicle functions by building</td><td> a mobile testing platform and spoofing of CAN messages </td></tr> 
<tr><td> ID2015_Mahaffey_MSA1_Step1 </td><td> Information Gathering about the vehicle. Analysis of vehicles internal networks and systems.</td><td> Hardware Attack </td></tr> 
<tr><td> ID2015_Mahaffey_MSA1_Step2_1 </td><td> Unknown connector on the CID turned out to be an Ethernet port, with non-standardized interface -> communication with the internal network possible.</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Mahaffey_MSA1_Step3_2 </td><td> Reverse Engineering Firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Mahaffey_MSA1_Step4_3 </td><td> Getting root access</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Mahaffey_MSA1_Step5_4 </td><td> Control of interior and exterior lighting, chassis, air conditioning, horn, switch vehicle off and start by sending CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2006_Thuente_SSA1 </td><td> Denial of service on WLAN communication by jamming attacks</td><td> Wireless Attack </td></tr> 
<tr><td> ID2006_Thuente_SSA2 </td><td> Simple Periodic Jamming Attack to disrupt the network</td><td> Wireless Attack </td></tr> 
<tr><td> ID2006_Thuente_SSA3 </td><td> Execution of Intelligent Jamming Attack to disrupt the network</td><td> Wireless Attack </td></tr> 
<tr><td> ID2002_Gupta_SSA1 </td><td> Denial-of-Service-attack on the MAC-Layer of a WLAN network with 12x12 nodes</td><td> Wireless Attack </td></tr> 
<tr><td> ID2002_Gupta_SSA2 </td><td> Disrupting direct neighbor in WLAN network</td><td> Wireless Attack </td></tr> 
<tr><td> ID2002_Gupta_SSA3 </td><td> Disrupting direct neighbor in WLAN network with several attack sources</td><td> Wireless Attack </td></tr> 
<tr><td> ID2002_Gupta_SSA4 </td><td> Disrupting component groups in WLAN network</td><td> Wireless Attack </td></tr> 
<tr><td> ID2015_Foster_MSA1_Step1</td><td> Fast and vulnerable: A story of Telematic FailuresFoster----  </td><td>  </td></tr> 
<tr><td> ID2015_Foster_MSA1_Step2_1 </td><td> Getting Access via Internet to the Web/telnet console</td><td> Root Shell) and Getting Access via the SMS Administration Interface by establishing a 2G connection  </td></tr> 
<tr><td> ID2015_Foster_MSA1_Step3_2 </td><td> Monitoring IP addresses</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Foster_MSA1_Step4_3 </td><td> Triggering brakes and windscreen wipers by sending malicious CAN messages</td><td> Wireless Attack </td></tr> 
<tr><td> ID2006_Lemke_SSA1 </td><td> Extraction of secret keys by executing side channel attacks</td><td> Hardware Attack </td></tr> 
<tr><td> ID2006_Lemke_SSA2 </td><td> Side Channel Attack through Simple Power Analysis</td><td> Hardware Attack </td></tr> 
<tr><td> ID2006_Lemke_SSA3 </td><td> Side Channel Attack through Differential Power Analysis</td><td> Hardware Attack </td></tr> 
<tr><td> ID2006_Lemke_SSA4 </td><td> Side Channel Attack through Internal Collision Attack</td><td> Hardware Attack </td></tr> 
<tr><td> ID2006_Lemke_SSA5 </td><td> Side Channel Attack through Template Attack</td><td> Hardware Attack </td></tr> 
<tr><td> ID2003_Bellardo_MSA1_Step1 </td><td> Monitoring WLAN communication</td><td> Wireless Attack </td></tr> 
<tr><td> ID2003_Bellardo_MSA1_Step2_1 </td><td> Deauthentication attack to prevent authentication that is necessary when connecting to an access point by spoofing an authentication message by the attacker</td><td> Wireless Attack </td></tr> 
<tr><td> ID2003_Bellardo_MSA1_Step3_1 </td><td> Blocking communication channel with Virtual Carrier Sense Attack for sending messages that contain a high value in the duration field of the message.</td><td> Wireless Attack </td></tr> 
<tr><td> ID2016_Garcia_MSA1_Step1 </td><td> Analysis of ECU and Chip</td><td> Hardware Attack </td></tr> 
<tr><td> ID2016_Garcia_MSA1_Step2_1 </td><td> Firmware Extraction</td><td> Software Attack </td></tr> 
<tr><td> ID2016_Garcia_MSA1_Step3_2 </td><td> Extracting the global master key by Reverse Engineering of the Firmware.</td><td> Software Attack </td></tr> 
<tr><td> ID2016_Garcia_MSA1_Step4_3 </td><td> Unlocking the car.</td><td> Wireless Attack </td></tr> 
<tr><td> ID2015_Rüsberg_SSA1 </td><td> Relay attack on keyless entry system of a vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2005_Alrabady_SSA1 </td><td> Gaining access to vehicle by Scan Attack</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2005_Alrabady_SSA2 </td><td> Gaining access to vehicle by Playback Attack</td><td> Wireless Attack </td></tr> 
<tr><td> ID2005_Alrabady_SSA3 </td><td> Relay attack on keyless entry system of a vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2005_Alrabady_MSA1_Step2_1 </td><td> Gaining access to vehicle by Challenge Forward Prediction Attack</td><td> Wireless Attack </td></tr> 
<tr><td> ID2005_Alrabady_SSA4 </td><td> Gaining access to vehicle by Dictionary Attack</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2015_CanBusHack_SSA1 </td><td> Information Gathering by monitoring the CAN traffic</td><td> Bus Attack </td></tr> 
<tr><td> ID2008_Courtois_SSA1 </td><td> Overcome immobilizer by cryptoanalysis of the Keeloq cipher</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2008_Courtois_SSA2 </td><td> Cryptoanalysis of KeeLoq Cipher</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2008_Courtois_SSA3 </td><td> Cryptoanalysis of KeeLoq Cipher to distinguish rounds</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2008_Courtois_SSA4 </td><td> Cryptoanalysis of KeeLoq Cipher to calculate pair lists</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2007_Kauer_MSA1_Step1 </td><td> Monitoring BIOS measurements</td><td> Hardware Attack </td></tr> 
<tr><td> ID2007_Kauer_MSA1_Step2_1 </td><td> Overcoming TPM protection by execution of side channel attack to get trusted state</td><td> Hardware Attack </td></tr> 
<tr><td> ID2018_Dürrwang_MSA1_Step1 </td><td> Information gathering on the basis of the results of a threat analysis</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Dürrwang_MSA1_Step2_1 </td><td> Brute Forcing Security Access</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2018_Dürrwang_MSA1_Step3_2 </td><td> Executing airbag detonation by exploit a vulnerability of the end-of-life ISO standard</td><td> Bus Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA1_Step1 </td><td> Monitoring Data Traffic</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA1_Step2_1 </td><td> Reverse Engineering Diagnostic Protocols</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA1_Step3_2 </td><td> Getting root privileges and execution of shell by exploiting vulnerability in diagnostic protocol</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA2_Step1 </td><td> Portscan of Services in Head Unit</td><td> Software Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA2_Step2_1 </td><td> Getting root privilege by connecting malicious USB stick</td><td> Hardware Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA2_Step3_2 </td><td> Executing a root shell.</td><td> Software Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA3_Step1 </td><td> Reverse Engineering Bluetooth Stack</td><td> Software Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA3_Step2_1 </td><td> Fuzzing Bluetooth messages</td><td> Wireless Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA3_Step3_2 </td><td> Reboot of Head Unit by setting it in pairing mode and utilizing the stack crash</td><td> without PIN).  </td></tr> 
<tr><td> ID2017_KeenLab_MSA4_Step1 </td><td> Monitoring GSM traffic</td><td> Wireless Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA4_Step2_1 </td><td> Exploting Browser Vulnerability</td><td> Software Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA4_Step3_2 </td><td> Remote Code Execution in the browser of the head unit by exploiting memory bug</td><td> Software Attack </td></tr> 
<tr><td> ID2017_KeenLab_SSA1 </td><td> Compromising the head unit by spoofing of diagnostic CAN messages</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2017_KeenLab_SSA2 </td><td> Compromising the head unit by spoofing of diagnostic CAN messages</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA5_Step1 </td><td> Firmware Extraction of the Telematics ECU</td><td> Software Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA5_Step2_1 </td><td> Reverse Engineering Firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA5_Step3_2 </td><td> Forcing GSM communication with Vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA5_Step4_2 </td><td> Sending malicious messages via GSM</td><td> Wireless Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA5_Step5_4_3 </td><td> Bypassing the signature of the telematics firmware and sending CAN messages by reverse engieering the telematics firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2017_KeenLab_MSA5_Step6_5 </td><td> Activation of different diagnostic services by getting remote control of the telematics</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2005_Poulsen_SSA1 </td><td> Manipulating of traffic light devices by spoofing false messages from a MIRT device</td><td> Environment Attack </td></tr> 
<tr><td> ID2007_Barisani_MSA1_Step1 </td><td> Monitoring Radio Data System</td><td> Wireless Attack </td></tr> 
<tr><td> ID2007_Barisani_MSA1_Step2_1 </td><td> Hijacking of the communication channels.</td><td> Wireless Attack </td></tr> 
<tr><td> ID2007_Barisani_MSA1_Step3_2 </td><td> Sending malicious RDS-TMC messages.</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_ADAC_SSA1 </td><td> Relay attack on keyless entry system of several vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2005_Bono_MSA1_Step1 </td><td> Reverse engineering of the cryptographic cipher of a RFID device</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2005_Bono_MSA1_Step2_1 </td><td> Cracking secret key</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2015_Petit_SSA1 </td><td> Blinding camera and lidar by laser attack</td><td> Environment Attack </td></tr> 
<tr><td> ID2015_Petit_SSA2 </td><td> Confusing Camera Auto Controls</td><td> Environment Attack </td></tr> 
<tr><td> ID2015_Petit_MSA1_Step1 </td><td> Relaying signals captured by a lidar and transmitted to the vehicle to falsify the echo</td><td> Environment Attack </td></tr> 
<tr><td> ID2015_Petit_MSA1_Step2_1 </td><td> Relaying signals captured by a lidar and transmitted to the vehicle to fake echo lidar signals in order to disturb autonomous driving functions</td><td> Environment Attack </td></tr> 
<tr><td> ID2004_Wullems_SSA1 </td><td> Denial of service attack on WLAN communication channel occupying the channel</td><td> Wireless Attack </td></tr> 
<tr><td> ID2013_Baltieri_MSA1_Step1 </td><td> Monitoring CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Baltieri_MSA1_Step2_1 </td><td> Sending malicious CAN messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2018_Computertest_MSA1_Step1 </td><td> Portscan Infotainment</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Computertest_MSA1_Step2_1 </td><td> Brute force on Password key space</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2018_Computertest_MSA1_Step3_2 </td><td> Accessing Radio and car control unit from Infotainment</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Computertest_MSA1_Step4_3 </td><td> Accessing chip for CAN communication</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Computertest_MSA1_Step5_4 </td><td> Flashing malicious Update</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Computertest_MSA1_Step6_5 </td><td> Remote code execution by sending malicious CAN messages</td><td> Software Attack </td></tr> 
<tr><td> ID2016_Klinedinst_SSA5 </td><td> Investigation of vulnerabilities in connected cars</td><td> Software Attack </td></tr> 
<tr><td> ID2007_Spill_MSA1_Step1 </td><td> Monitoring Bluetooth traffic</td><td> Wireless Attack </td></tr> 
<tr><td> ID2007_Spill_MSA1_Step2_1 </td><td> Monitoring MAC</td><td> Wireless Attack </td></tr> 
<tr><td> ID2007_Spill_MSA1_Step3_2 </td><td> Reverse Engineering Bluetooth Hopping Scheme</td><td> Wireless Attack </td></tr> 
<tr><td> ID2014_Costin_MSA1_Step1 </td><td> Large scale analysis of embedded firmwares by crawling firmware files from the internet</td><td> Software Attack </td></tr> 
<tr><td> ID2014_Costin_MSA1_Step2_1 </td><td> Breaking Password Hashes</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2014_Costin_MSA1_Step3_2 </td><td> Fuzzing Firmware files in order to identify vulnerabilities</td><td> Software Attack </td></tr> 
<tr><td> ID2013_Schröder_SSA1 </td><td> Position Forging in order to pretend false single vehicle position</td><td> Wireless Attack </td></tr> 
<tr><td> ID2013_Schröder_SSA2 </td><td> Position Forging in order to pretend false multiple vehicle positions</td><td> Wireless Attack </td></tr> 
<tr><td> ID2013_Schröder_SSA3 </td><td> Position Forging in order to pretend false single vehicle movement paths</td><td> Wireless Attack </td></tr> 
<tr><td> ID2013_Schröder_SSA4 </td><td> Position Forging in order to pretend false multiple vehicle movement paths</td><td> Wireless Attack </td></tr> 
<tr><td> ID2009_Winter_SSA1 </td><td> Eavesdropping attack on the TPM communication</td><td> Bus Attack </td></tr> 
<tr><td> ID2008_Nilsson_MSA1_Step1 </td><td> Monitoring of FlexRay messages by eavesdropping of the channel</td><td> Bus Attack </td></tr> 
<tr><td> ID2008_Nilsson_MSA1_Step2_1 </td><td> Spoofing of FlexRay messages</td><td> Bus Attack </td></tr> 
<tr><td> ID2018_Sitawarin_MSA1_Step1 </td><td> Altering traffic signs to mislead autonomous vehicle functions</td><td> Environment Attack </td></tr> 
<tr><td> ID2018_Sitawarin_MSA1_Step2_1 </td><td> Altering traffic signs with lenticular printing technique</td><td> Environment Attack </td></tr> 
<tr><td> ID2017_Lu_SSA1 </td><td> Misleading detector by using adversarial examples</td><td> Environment Attack </td></tr> 
<tr><td> ID2016_Liu_MSA1_Step1 </td><td> Misleading image classification network with non-targeted attack</td><td> Artificial Intelligence Attack </td></tr> 
<tr><td> ID2016_Liu_MSA1_Step2_1 </td><td> Misleading image classification network with targeted attack</td><td> Artificial Intelligence Attack </td></tr> 
<tr><td> ID2017_Chen_SSA3 </td><td> Attacking Deep Neural Networks with Adversarial Examples</td><td> Artificial Intelligence Attack </td></tr> 
<tr><td> ID2017_Cisse_SSA3 </td><td> Fooling gradient-based algorithms for machine learning by generation of adversarial examples</td><td> Environment Attack </td></tr> 
<tr><td> ID2012_Biggio_SSA1 </td><td> Misleading Support Vector Maschines by data poisoning</td><td> Artificial Intelligence Attack </td></tr> 
<tr><td> ID2016_Papernot_SSA1 </td><td> Attacking a black box deep neural network classifier by using adversarial examples</td><td> Artificial Intelligence Attack </td></tr> 
<tr><td> ID2017_Eykholt_SSA3 </td><td> Triggering misclassification on a deep neural network by generation of physical pertubations</td><td> Environment Attack </td></tr> 
<tr><td> ID2009_Rubinstein_SSA1 </td><td> Investigation of vulnerabilities in static machine learning</td><td> Artificial Intelligence Attack </td></tr> 
<tr><td> ID2017_Chen_MSA1_Step1 </td><td> Misclassification of images via untargeted attack with adversarial examples</td><td> Artificial Intelligence Attack </td></tr> 
<tr><td> ID2017_Chen_MSA1_Step2_1 </td><td> Misclassification of images via targeted attack with adversarial examples</td><td> Artificial Intelligence Attack </td></tr> 
<tr><td> ID2017_Brendel_SSA1 </td><td> Attacking machine learning algorithms by using pertubations of the inputs</td><td> Artificial Intelligence Attack </td></tr> 
<tr><td> ID2017_Xie_SSA1 </td><td> Adversarial Examples with Dense Adversary Generation</td><td> DAG) Algorithm </td></tr> 
<tr><td> ID2017_Xie_SSA2 </td><td> Adversarial Examples with Dense Adversary Generation</td><td> DAG) Algorithm </td></tr> 
<tr><td> ID2017_Xie_SSA3 </td><td> Adversarial Examples with Dense Adversary Generation</td><td> DAG) Algorithm </td></tr> 
<tr><td> ID2017_Xie_SSA4 </td><td> Adversarial Examples with Dense Adversary Generation</td><td> DAG) Algorithm </td></tr> 
<tr><td> ID2017_Xie_SSA5 </td><td> Adversarial Examples with Dense Adversary Generation</td><td> DAG) Algorithm </td></tr> 
<tr><td> ID2018_KeenLab_MSA1_Step1 </td><td> Remote attack on the Tesla Autopilot</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_KeenLab_MSA1_Step2_1 </td><td> Remote attack on the Tesla Autopilot</td><td> Software Attack </td></tr> 
<tr><td> ID2018_KeenLab_MSA1_Step3_2 </td><td> Remote attack on the Tesla Autopilot</td><td> Software Attack </td></tr> 
<tr><td> ID2018_KeenLab_MSA1_Step4_3 </td><td> Remote attack on the Tesla Autopilot</td><td> Software Attack </td></tr> 
<tr><td> ID2018_KeenLab_MSA1_Step5_4 </td><td> Remote attack on the Tesla Autopilot</td><td> Software Attack </td></tr> 
<tr><td> ID2018_KeenLab_MSA1_Step6_5 </td><td> Remote attack on the Tesla Autopilot</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Takahashi_MSA1_Step1 </td><td> Sniffing CAN messages with information</td><td> speed, ) for cruise control  </td></tr> 
<tr><td> ID2018_Takahashi_MSA1_Step2_1 </td><td> Spoofing of CAN messages with false information</td><td> speed, ) to accelerate and decelerate the vehicle  </td></tr> 
<tr><td> ID2018_Takahashi_MSA1_Step3_2 </td><td> Spoofing of CAN messages with false information</td><td> speed, ) to accelerate and decelerate the vehicle  </td></tr> 
<tr><td> ID2018_Takahashi_MSA2_Step1 </td><td> Sniffing CAN messages with information</td><td> speed, ) for cruise control  </td></tr> 
<tr><td> ID2018_Takahashi_MSA2_Step2_1 </td><td> Disabling the park assistance system by spoofing CAN messages with modified data</td><td> Bus Attack </td></tr> 
<tr><td> ID2018_Costantino_SSA1 </td><td> Obtainment of private data and vehicle data by eavesdropping via malicious app which is distributed by social engineering</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Greenberg_MSA1_Step1 </td><td> Stealing the car by overcoming the weak key fob encryption</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Greenberg_MSA1_Step2_1 </td><td> Stealing the car by overcoming the weak key fob encryption</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2018_Greenberg_MSA1_Step3_2 </td><td> Stealing the car by overcoming the weak key fob encryption</td><td> Wireless Attack </td></tr> 
<tr><td> ID2015_Miller_SSA4 </td><td> Manipulation of vehicle functions</td><td> deactivation of engine cylinder, bleeding brakes, steering intervention) by spoofing of diagnostic CAN messages.  </td></tr> 
<tr><td> ID2014_Hoppe_MSA1_Step3_2 </td><td> Flashing of modified firmware by reverse engineering and modification</td><td> including the CRC checksum) of the ECUs firmware  </td></tr> 
<tr><td> ID2016_Klinedinst_SSA1 </td><td> Investigation of vulnerabilities in connected cars</td><td> Bus Attack </td></tr> 
<tr><td> ID2016_Klinedinst_SSA2 </td><td> Investigation of vulnerabilities in connected cars</td><td> Bus Attack </td></tr> 
<tr><td> ID2016_Klinedinst_SSA3 </td><td> Investigation of vulnerabilities in connected cars</td><td> Software Attack </td></tr> 
<tr><td> ID2016_Klinedinst_SSA4 </td><td> Investigation of vulnerabilities in connected cars</td><td> Bus Attack </td></tr> 
<tr><td> ID2017_Chen_SSA1 </td><td> Attacking Deep Neural Networks with Adversarial Examples</td><td> Artificial Intelligence Attack </td></tr> 
<tr><td> ID2017_Chen_SSA2 </td><td> Attacking Deep Neural Networks with Adversarial Examples</td><td> Artificial Intelligence Attack </td></tr> 
<tr><td> ID2017_Cisse_SSA1 </td><td> Fooling gradient-based algorithms for machine learning by generation of adversarial examples</td><td> Environment Attack </td></tr> 
<tr><td> ID2017_Cisse_SSA2 </td><td> Fooling gradient-based algorithms for machine learning by generation of adversarial examples</td><td> Environment Attack </td></tr> 
<tr><td> ID2017_Eykholt_SSA1 </td><td> Triggering misclassification on a deep neural network by generation of physical pertubations</td><td> Environment Attack </td></tr> 
<tr><td> ID2017_Eykholt_SSA2 </td><td> Triggering misclassification on a deep neural network by generation of physical pertubations</td><td> Environment Attack </td></tr> 
<tr><td> ID2006_Aijaz_SSA9</td><td> Attacks on inter vehicle communication systems-an analysisAijaz--Proc. WITThe authors show general attacks, which are described here, as well as more concrete attacks for:1) Car to Car Traffic Applications,2) Car to Infrastructure Applications,3) Car to Home Applications, and4) Routing based Applications.</td><td>   </td></tr> 
<tr><td> ID2006_Aijaz_SSA1</td><td> Attacks on inter vehicle communication systems-an analysisAijaz--Proc. WITThe authors show general attacks, which are described here, as well as more concrete attacks for:1) Car to Car Traffic Applications,2) Car to Infrastructure Applications,3) Car to Home Applications, and4) Routing based Applications.</td><td>   </td></tr> 
<tr><td> ID2006_Aijaz_SSA6</td><td> Attacks on inter vehicle communication systems-an analysisAijaz--Proc. WITThe authors show general attacks, which are described here, as well as more concrete attacks for:1) Car to Car Traffic Applications,2) Car to Infrastructure Applications,3) Car to Home Applications, and4) Routing based Applications.</td><td>   </td></tr> 
<tr><td> ID2006_Aijaz_SSA7</td><td> Attacks on inter vehicle communication systems-an analysisAijaz--Proc. WITThe authors show general attacks, which are described here, as well as more concrete attacks for:1) Car to Car Traffic Applications,2) Car to Infrastructure Applications,3) Car to Home Applications, and4) Routing based Applications.</td><td>   </td></tr> 
<tr><td> ID2006_Aijaz_SSA8</td><td> Attacks on inter vehicle communication systems-an analysisAijaz--Proc. WITThe authors show general attacks, which are described here, as well as more concrete attacks for:1) Car to Car Traffic Applications,2) Car to Infrastructure Applications,3) Car to Home Applications, and4) Routing based Applications.</td><td>   </td></tr> 
<tr><td> ID2006_Aijaz_SSA10</td><td> Attacks on inter vehicle communication systems-an analysisAijaz--Proc. WITThe authors show general attacks, which are described here, as well as more concrete attacks for:1) Car to Car Traffic Applications,2) Car to Infrastructure Applications,3) Car to Home Applications, and4) Routing based Applications.</td><td>   </td></tr> 
<tr><td> ID2006_Aijaz_SSA2</td><td> Attacks on inter vehicle communication systems-an analysisAijaz--Proc. WITThe authors show general attacks, which are described here, as well as more concrete attacks for:1) Car to Car Traffic Applications,2) Car to Infrastructure Applications,3) Car to Home Applications, and4) Routing based Applications.</td><td>   </td></tr> 
<tr><td> ID2006_Aijaz_SSA3</td><td> Attacks on inter vehicle communication systems-an analysisAijaz--Proc. WITThe authors show general attacks, which are described here, as well as more concrete attacks for:1) Car to Car Traffic Applications,2) Car to Infrastructure Applications,3) Car to Home Applications, and4) Routing based Applications.</td><td>   </td></tr> 
<tr><td> ID2006_Aijaz_SSA4</td><td> Attacks on inter vehicle communication systems-an analysisAijaz--Proc. WITThe authors show general attacks, which are described here, as well as more concrete attacks for:1) Car to Car Traffic Applications,2) Car to Infrastructure Applications,3) Car to Home Applications, and4) Routing based Applications.</td><td>   </td></tr> 
<tr><td> ID2006_Aijaz_SSA5</td><td> Attacks on inter vehicle communication systems-an analysisAijaz--Proc. WITThe authors show general attacks, which are described here, as well as more concrete attacks for:1) Car to Car Traffic Applications,2) Car to Infrastructure Applications,3) Car to Home Applications, and4) Routing based Applications.</td><td>   </td></tr> 
<tr><td> ID2018_Gayou_MSA1_Step1 </td><td> Getting full control</td><td> root) on StarLink Head Unit by flashing malicious firmware update via USB port connection. This results in code execution with root privileges.  </td></tr> 
<tr><td> ID2018_Gayou_MSA1_Step2_1 </td><td> Getting full control</td><td> root) on StarLink Head Unit by flashing malicious firmware update via USB port connection. This results in code execution with root privileges.  </td></tr> 
<tr><td> ID2018_Gayou_MSA1_Step3_2 </td><td> Getting full control</td><td> root) on StarLink Head Unit by flashing malicious firmware update via USB port connection. This results in code execution with root privileges.  </td></tr> 
<tr><td> ID2018_Gayou_MSA1_Step4_3 </td><td> Getting full control</td><td> root) on StarLink Head Unit by flashing malicious firmware update via USB port connection. This results in code execution with root privileges.  </td></tr> 
<tr><td> ID2018_Gayou_MSA1_Step5_4 </td><td> Getting full control</td><td> root) on StarLink Head Unit by flashing malicious firmware update via USB port connection. This results in code execution with root privileges.  </td></tr> 
<tr><td> ID2018_Ibrahim_SSA1 </td><td> Relay attack on keyless entry system of a Volvo XC90</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Simmons_SSA1 </td><td> Relay attack on keyless entry system</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Lambert_SSA1 </td><td> Tesla Model 3 manipulalted to host an Ubuntu OS on the Infotainment System and playing Youtube videos.</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Cespedes_SSA1 </td><td> Controlling functions like the brakes, acceleration, windshield wipers, etc.by adding a custom ECU which sends malicious messages to other ECUs</td><td> Hardware Attack </td></tr> 
<tr><td> ID2018_Plkachu_MSA1_Step1 </td><td> Controlling and adapting music to driving behavior by misusing CAN bus traffic</td><td> Hardware Attack </td></tr> 
<tr><td> ID2018_Plkachu_MSA1_Step2_1 </td><td> Controlling and adapting music to driving behavior by misusing CAN bus traffic</td><td> Bus Attack </td></tr> 
<tr><td> ID2018_Plkachu_MSA2_Step1 </td><td> Spoofing malicious speed value messages of a Subaru Impreza by extracting and reverse engineering an ECUs firmware via diagnostic interface</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Plkachu_MSA2_Step2_1 </td><td> Spoofing malicious speed value messages of a Subaru Impreza by extracting and reverse engineering an ECUs firmware via diagnostic interface</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Plkachu_MSA2_Step3_2 </td><td> Spoofing malicious speed value messages of a Subaru Impreza by extracting and reverse engineering an ECUs firmware via diagnostic interface</td><td> Bus Attack </td></tr> 
<tr><td> ID2019_Christensen_SSA1</td><td> Elm-327 clone deviceChristensen--https://www.kth.se/polopoly_fs/1.917488.1600689356!/elm327.pdfhttps://nvd.nist.gov/vuln/detail/CVE-2019-12797  </td><td>  </td></tr> 
<tr><td> ID2019_Munro_SSA1 </td><td> ELM327 OBD2 Bluetooth device misused to send malicious messages via Teslas diagnostic interface to trigger vehicle functions.</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Saunt_SSA1 </td><td> Relay attack on keyless entry system of a Tesla</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Bhatio_SSA1 </td><td> Relay attack on keyless entry system of a Mercedes</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Saunt_SSA2 </td><td> Relay attack on keyless entry system of a Audi RS5</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Hayward_SSA1 </td><td> Relay attack on keyless entry system of several vehicles like vans, taxis, minibuses and others</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Evans_SSA1 </td><td> Relay attack on keyless entry system of seven vehicle models</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Fehely_SSA1 </td><td> Relay attack on keyless entry system of several vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Newsroom_SSA1 </td><td> Relay attack on keyless entry system of a vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Potter_SSA1 </td><td> Relay attack on keyless entry system of a vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_TellerReport_SSA1 </td><td> Relay attack on keyless entry system of at least 65 vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Evans_SSA2 </td><td> Relay attack on keyless entry system of seven vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Evans_SSA3 </td><td> Relay attack on keyless entry system of seven vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2016_Etehad_SSA1 </td><td> Relay attack on keyless entry system of several vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2017_BBC_SSA1 </td><td> Relay attack on keyless entry system of a Mercedes</td><td> Wireless Attack </td></tr> 
<tr><td> ID2017_Smith_SSA1 </td><td> Relay attack on keyless entry system of a BMW</td><td> Wireless Attack </td></tr> 
<tr><td> ID2017_Saltzman_SSA1 </td><td> Relay attack on keyless entry system of several vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Regulus_SSA1 </td><td> Spoofing GPS data to Tesla Model 3 and Tesla Model S to influence the driving behavior of the vehicles.</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Christensen_MSA1_Step1 </td><td> Man-in-the-Middle Attack on AutoPi Wi-Fi network. Communication between AutoPi OBD Dongle and the related Cloud server can be intercepted. Thus, account information, credentials, user data, etc. can be compromised </td><td> Software AttackUsing resources about the system to create a threat model </td></tr> 
<tr><td> ID2019_Christensen_MSA1_Step2_1 </td><td> Man-in-the-Middle Attack on AutoPi Wi-Fi network. Communication between AutoPi OBD Dongle and the related Cloud server can be intercepted. Thus, account information, credentials, user data, etc. can be compromised </td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Christensen_MSA1_Step3_1 </td><td> Man-in-the-Middle Attack on AutoPi Wi-Fi network. Communication between AutoPi OBD Dongle and the related Cloud server can be intercepted. Thus, account information, credentials, user data, etc. can be compromised </td><td> Software Attack </td></tr> 
<tr><td> ID2019_Wouters_MSA1_Step1 </td><td> Tesla key fob contains vulnerability which reduces the complexity for brute forcing the encryption algorithm to finding two 40-bit keys</td><td> Hardware Attack </td></tr> 
<tr><td> ID2019_Wouters_MSA1_Step2_1 </td><td> Tesla key fob contains vulnerability which reduces the complexity for brute forcing the encryption algorithm to finding two 40-bit keys</td><td> Hardware Attack </td></tr> 
<tr><td> ID2019_Wouters_MSA1_Step3_2 </td><td> Tesla key fob contains vulnerability which reduces the complexity for brute forcing the encryption algorithm to finding two 40-bit keys</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Wouters_MSA1_Step4_3 </td><td> Tesla key fob contains vulnerability which reduces the complexity for brute forcing the encryption algorithm to finding two 40-bit keys</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Wouters_MSA1_Step5_4 </td><td> Tesla key fob contains vulnerability which reduces the complexity for brute forcing the encryption algorithm to finding two 40-bit keys</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2019_Bruno_SSA1 </td><td> Monitoring and sending CAN messages by using a custom Arduino tool</td><td> Bus Attack </td></tr> 
<tr><td> ID2019_Rose_MSA1_Step1 </td><td> Different capture-replay attacks of key fob signals enable attackers to unlock and start the vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Rose_MSA1_Step2_1 </td><td> Different capture-replay attacks of key fob signals enable attackers to unlock and start the vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Rose_MSA2_Step1 </td><td> Different capture-replay attacks of key fob signals enable attackers to unlock and start the vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Rose_MSA2_Step2_1 </td><td> Different capture-replay attacks of key fob signals enable attackers to unlock and start the vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Rose_MSA2_Step3_2 </td><td> Different capture-replay attacks of key fob signals enable attackers to unlock and start the vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Cao_SSA1 </td><td> Attacking a LiDAR-based autonomous driving detection system by using adversarial examples</td><td> Environment Attack </td></tr> 
<tr><td> ID2019_Cao_SSA2 </td><td> Attacking a LiDAR-based autonomous driving detection system by using adversarial examples</td><td> Environment Attack </td></tr> 
<tr><td> ID2019_Cao_SSA3 </td><td> Attacking a LiDAR-based autonomous driving detection system by using adversarial examples</td><td> Environment Attack </td></tr> 
<tr><td> ID2019_Cao_SSA4 </td><td> Attacking a LiDAR-based autonomous driving detection system by using adversarial examples</td><td> Environment Attack </td></tr> 
<tr><td> ID2019_Curry_SSA1 </td><td> Cross-Site-Scripting attack to acquire and manipulate a Teslas data, such as speed, temperature, version numbers, etc.</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Kaspersky_MSA1_Step1</td><td> On the IoT road: perks, benefits and security of moving smartlyKaspersky--https://securelist.com/on-the-iot-road/91833/-  </td><td>  </td></tr> 
<tr><td> ID2019_Kaspersky_MSA1_Step2_1</td><td> On the IoT road: perks, benefits and security of moving smartlyKaspersky--https://securelist.com/on-the-iot-road/91833/-  </td><td>  </td></tr> 
<tr><td> ID2019_Kaspersky_MSA3_Step1</td><td> On the IoT road: perks, benefits and security of moving smartlyKaspersky--https://securelist.com/on-the-iot-road/91833/-  </td><td>  </td></tr> 
<tr><td> ID2019_Kaspersky_MSA3_Step2_1</td><td> On the IoT road: perks, benefits and security of moving smartlyKaspersky--https://securelist.com/on-the-iot-road/91833/-  </td><td>  </td></tr> 
<tr><td> ID2019_Kaspersky_SSA1 </td><td> Investigation of security issues on several third party devices uncovers several vulnerabilities</td><td> Hardware Attack </td></tr> 
<tr><td> ID2019_Kaspersky_MSA2_Step1</td><td> On the IoT road: perks, benefits and security of moving smartlyKaspersky--https://securelist.com/on-the-iot-road/91833/-  </td><td>  </td></tr> 
<tr><td> ID2019_Kaspersky_MSA2_Step2_1</td><td> On the IoT road: perks, benefits and security of moving smartlyKaspersky--https://securelist.com/on-the-iot-road/91833/-  </td><td>  </td></tr> 
<tr><td> ID2019_Morgulis_MSA1_Step1 </td><td> Using adversarial examples</td><td> traffic signs) to attack traffic sign recognition system in vehicle  </td></tr> 
<tr><td> ID2019_Morgulis_MSA1_Step2_1 </td><td> Using adversarial examples</td><td> traffic signs) to attack traffic sign recognition system in vehicle  </td></tr> 
<tr><td> ID2019_Morgulis_MSA1_Step3_1 </td><td> Using adversarial examples</td><td> traffic signs) to attack traffic sign recognition system in vehicle  </td></tr> 
<tr><td> ID2019_Murray_SSA1 </td><td> Influencing the driving behavior of an autonomous car by manipulating navigation signals</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Murray_SSA2 </td><td> Influencing the driving behavior of an autonomous car by manipulating navigation signals</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Murray_SSA3 </td><td> Influencing the driving behavior of an autonomous car by manipulating navigation signals</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Google_MSA1_Step1 </td><td> Remote access to Multimedia system of Toyota and Lexus models by brute force attack on the authentication of the Telenav Scout GPS Link app for iOS.</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Google_MSA1_Step2_1 </td><td> Remote access to Multimedia system of Toyota and Lexus models by brute force attack on the authentication of the Telenav Scout GPS Link app for iOS.</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2019_Stykas_MSA1_Step1 </td><td> Security investigation of three vehicle tracking app APIs uncovered several vulnerabilities. Thus, vehicles can be tracked and immobilized by an attacker</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Stykas_MSA1_Step2_1 </td><td> Security investigation of three vehicle tracking app APIs uncovered several vulnerabilities. Thus, vehicles can be tracked and immobilized by an attacker</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Stykas_MSA1_Step3_2 </td><td> Security investigation of three vehicle tracking app APIs uncovered several vulnerabilities. Thus, vehicles can be tracked and immobilized by an attacker</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Stykas_MSA2_Step1 </td><td> Security investigation of three vehicle tracking app APIs uncovered several vulnerabilities. Thus, vehicles can be tracked and immobilized by an attacker</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Stykas_MSA2_Step2_1 </td><td> Security investigation of three vehicle tracking app APIs uncovered several vulnerabilities. Thus, vehicles can be tracked and immobilized by an attacker</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Stykas_MSA2_Step3_2 </td><td> Security investigation of three vehicle tracking app APIs uncovered several vulnerabilities. Thus, vehicles can be tracked and immobilized by an attacker</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Stykas_MSA3_Step1 </td><td> Security investigation of three vehicle tracking app APIs uncovered several vulnerabilities. Thus, vehicles can be tracked and immobilized by an attacker</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Stykas_MSA3_Step2_1 </td><td> Security investigation of three vehicle tracking app APIs uncovered several vulnerabilities. Thus, vehicles can be tracked and immobilized by an attacker</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Neef_SSA1 </td><td> Influencing LiDAR sensors by hiding road objects with black trash bag which absorbs LiDAR signals</td><td> Environment Attack </td></tr> 
<tr><td> ID2019_Neef_SSA2 </td><td> Influencing LiDAR sensors by throwing powder in front of the LiDAR sensor</td><td> Environment Attack </td></tr> 
<tr><td> ID2019_Urquhart_MSA1_Step1</td><td> Cyber-Security Internals of s Skoda Octavia vRS: A Hands on ApproachUrquhart10.1109/ACCESS.2019.2943837-IEEE Access -  </td><td>  </td></tr> 
<tr><td> ID2019_Urquhart_MSA1_Step2_1</td><td> Cyber-Security Internals of s Skoda Octavia vRS: A Hands on ApproachUrquhart10.1109/ACCESS.2019.2943837-IEEE Access -  </td><td>  </td></tr> 
<tr><td> ID2019_Urquhart_MSA1_Step3_2</td><td> Cyber-Security Internals of s Skoda Octavia vRS: A Hands on ApproachUrquhart10.1109/ACCESS.2019.2943837-IEEE Access -  </td><td>  </td></tr> 
<tr><td> ID2019_Urquhart_MSA2_Step1</td><td> Cyber-Security Internals of s Skoda Octavia vRS: A Hands on ApproachUrquhart10.1109/ACCESS.2019.2943837-IEEE Access -  </td><td>  </td></tr> 
<tr><td> ID2019_Urquhart_MSA2_Step2_1</td><td> Cyber-Security Internals of s Skoda Octavia vRS: A Hands on ApproachUrquhart10.1109/ACCESS.2019.2943837-IEEE Access -  </td><td>  </td></tr> 
<tr><td> ID2019_Urquhart_MSA2_Step3_2</td><td> Cyber-Security Internals of s Skoda Octavia vRS: A Hands on ApproachUrquhart10.1109/ACCESS.2019.2943837-IEEE Access -  </td><td>  </td></tr> 
<tr><td> ID2019_Urquhart_MSA3_Step1</td><td> Cyber-Security Internals of s Skoda Octavia vRS: A Hands on ApproachUrquhart10.1109/ACCESS.2019.2943837-IEEE Access -  </td><td>  </td></tr> 
<tr><td> ID2019_Urquhart_MSA3_Step2_1</td><td> Cyber-Security Internals of s Skoda Octavia vRS: A Hands on ApproachUrquhart10.1109/ACCESS.2019.2943837-IEEE Access -  </td><td>  </td></tr> 
<tr><td> ID2019_Urquhart_MSA3_Step3_2</td><td> Cyber-Security Internals of s Skoda Octavia vRS: A Hands on ApproachUrquhart10.1109/ACCESS.2019.2943837-IEEE Access -  </td><td>  </td></tr> 
<tr><td> ID2019_Urquhart_SSA1 </td><td> Activating vehicle functions and configuring/enabling additional functions of a Skoda Octavia vRS 2017.</td><td> Hardware Attack </td></tr> 
<tr><td> ID2019_Urquhart_MSA4_Step1</td><td> Cyber-Security Internals of s Skoda Octavia vRS: A Hands on ApproachUrquhart10.1109/ACCESS.2019.2943837-IEEE Access -  </td><td>  </td></tr> 
<tr><td> ID2019_Urquhart_MSA4_Step2_1</td><td> Cyber-Security Internals of s Skoda Octavia vRS: A Hands on ApproachUrquhart10.1109/ACCESS.2019.2943837-IEEE Access -  </td><td>  </td></tr> 
<tr><td> ID2019_Urquhart_MSA5_Step1</td><td> Cyber-Security Internals of s Skoda Octavia vRS: A Hands on ApproachUrquhart10.1109/ACCESS.2019.2943837-IEEE Access -  </td><td>  </td></tr> 
<tr><td> ID2019_Urquhart_MSA5_Step2_1</td><td> Cyber-Security Internals of s Skoda Octavia vRS: A Hands on ApproachUrquhart10.1109/ACCESS.2019.2943837-IEEE Access -  </td><td>  </td></tr> 
<tr><td> ID2019_Urquhart_MSA5_Step3_2</td><td> Cyber-Security Internals of s Skoda Octavia vRS: A Hands on ApproachUrquhart10.1109/ACCESS.2019.2943837-IEEE Access -  </td><td>  </td></tr> 
<tr><td> ID2013_CBC_SSA1</td><td> New $5 device easily unlocks car doors for thieves in WinnipegCBC--https://www.cbc.ca/news/canada/manitoba/new-5-device-easily-unlocks-car-doors-for-thieves-in-winnipeg-1.2288826?cmp=rss-  </td><td>  </td></tr> 
<tr><td> ID2014_Greenberg_MSA1_Step1 </td><td> Key fob spoofing attack unlocks car in a few minutes</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2014_Greenberg_MSA1_Step2_1 </td><td> Key fob spoofing attack unlocks car in a few minutes</td><td> Wireless Attack </td></tr> 
<tr><td> ID2015_Bilton_SSA1 </td><td> Relay attack on keyless entry system of several vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2015_Paganini_MSA1_Step1</td><td> How to steal Jaguar XFR cars in 60 seconds by hacking themPaganini--https://securityaffairs.co/wordpress/41604/cyber-crime/steal-jaguar-xfr-cars.html-  </td><td>  </td></tr> 
<tr><td> ID2015_Paganini_MSA1_Step2_1</td><td> How to steal Jaguar XFR cars in 60 seconds by hacking themPaganini--https://securityaffairs.co/wordpress/41604/cyber-crime/steal-jaguar-xfr-cars.html-  </td><td>  </td></tr> 
<tr><td> ID2017_Beek_MSA1_Step1 </td><td> Telematic and Infotainment unit of Nissan Leaf compromised to establish a honeypot via its backend server to intercept connection attempts and GPS locations</td><td> Hardware Attack </td></tr> 
<tr><td> ID2017_Beek_MSA1_Step2_1 </td><td> Telematic and Infotainment unit of Nissan Leaf compromised to establish a honeypot via its backend server to intercept connection attempts and GPS locations</td><td> Software Attack </td></tr> 
<tr><td> ID2017_Beek_MSA2_Step1 </td><td> Telematic and Infotainment unit of Nissan Leaf compromised to establish a honeypot via its backend server to intercept connection attempts and GPS locations</td><td> Bus Attack </td></tr> 
<tr><td> ID2017_Beek_MSA2_Step2_1 </td><td> Telematic and Infotainment unit of Nissan Leaf compromised to establish a honeypot via its backend server to intercept connection attempts and GPS locations</td><td> Software Attack </td></tr> 
<tr><td> ID2017_Beek_MSA2_Step3_2 </td><td> Telematic and Infotainment unit of Nissan Leaf compromised to establish a honeypot via its backend server to intercept connection attempts and GPS locations</td><td> Software Attack </td></tr> 
<tr><td> ID2017_Beek_MSA2_Step4_3 </td><td> Telematic and Infotainment unit of Nissan Leaf compromised to establish a honeypot via its backend server to intercept connection attempts and GPS locations</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Leyden_SSA1 </td><td> Improper account management leads to manipulations and information gain by previous vehicle owners.</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Ibrahim_MSA1_Step1</td><td> Key is in the Air: Hacking Remote Keyless Entry SystemsIbrahimhttps://doi.org/10.1007/978-3-030-16874-2_9978-3-030-16873-5 Security and Safety Interplay of Intelligent Software Systems. CSITS 2018, ISSA 2018. Lecture Notes in Computer Science, vol 11552. Springer, Cham-  </td><td>  </td></tr> 
<tr><td> ID2018_Ibrahim_MSA1_Step2_1</td><td> Key is in the Air: Hacking Remote Keyless Entry SystemsIbrahimhttps://doi.org/10.1007/978-3-030-16874-2_9978-3-030-16873-5 Security and Safety Interplay of Intelligent Software Systems. CSITS 2018, ISSA 2018. Lecture Notes in Computer Science, vol 11552. Springer, Cham-  </td><td>  </td></tr> 
<tr><td> ID2018_WMC_SSA1 </td><td> Personal data can be read from vehicle by previously connected Bluetooth devices</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Lambert_MSA1_Step1 </td><td> Compromising Tesla app by reusing authentication key. GPS waqs disabled and the vehicle was stolen</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Lambert_MSA1_Step2_1 </td><td> Compromising Tesla app by reusing authentication key. GPS waqs disabled and the vehicle was stolen</td><td> Software Attack </td></tr> 
<tr><td> ID2018_FleetNews_SSA1 </td><td> Accident replacement hire cars Mercedes S-Class and Range Rover Evoque were stolen by using fake identitied from the dark web</td><td> Hardware Attack </td></tr> 
<tr><td> ID2018_TimesNow_SSA1 </td><td> Relay attack on keyless entry system of a SUV</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_PANews_SSA1 </td><td> Relay attack on keyless entry system of a vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Ruef_SSA1</td><td> Daimler Mercedes Me App 2.11.0-846 on iOS Certificate Pinning information disclosureRuef--https://vuldb.com/?id.125081https://www.cvedetails.com/cve/CVE-2018-18071https://www.scip.ch/en/?labs.20180405  </td><td>  </td></tr> 
<tr><td> ID2016_Geddes_SSA1 </td><td> Blocking door lock signals of several vehicles to steal objects from the vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Ruef_SSA2 </td><td> Daimler Mercedes-Benz COMAND 17/13.0 50.12 of Mercedes-Benz C-Class 2018 vehicles vulnerable for denial of service attacks through the navigation system</td><td> Software Attack </td></tr> 
<tr><td> ID2018_BBC_SSA1 </td><td> Relay attack on keyless entry system of a Ford Mustang</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Dent_MSA1_Step2_1 </td><td> Vehicle theft of Tesla vehicle by capture-replay attack on key fob signals</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Fox_SSA1 </td><td> Relay attack on keyless entry system of several vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Smith_SSA2 </td><td> Relay attack on keyless entry system of a Mercedes</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Rutter_SSA1 </td><td> Relay attack on keyless entry system of a Range Rover</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Smith_SSA1 </td><td> Relay attack on keyless entry system of two Mercedes</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_BoltonNews_SSA1 </td><td> Relay attack on keyless entry system of several vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Rezvani_MSA1_Step1 </td><td> Spoofing control commands to the ethernet channel of the rear camera to start and stop video streams</td><td> Bus Attack </td></tr> 
<tr><td> ID2018_Rezvani_MSA1_Step2_1 </td><td> False video stream can be injected to the ADAS cameras ethernet connection </td><td> Bus Attack </td></tr> 
<tr><td> ID2019_Frodsham_SSA1 </td><td> Relay attack on keyless entry system of a vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_ITV_SSA1 </td><td> Relay attack on keyless entry system of a BMW</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Keay_SSA1 </td><td> Relay attack on keyless entry system of a Land Rover</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Kentonline_SSA1 </td><td> Relay attack on keyless entry system of a Nissan</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Hetherington_SSA1 </td><td> Relay attack on keyless entry system of a Ford</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_BBC_SSA1 </td><td> Relay attack on keyless entry system of a vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Sun_SSA1 </td><td> Relay attack on keyless entry system of several vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Gant_SSA1 </td><td> Relay attack on keyless entry system of a Audi</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Bowe_SSA1 </td><td> Relay attack on keyless entry system of several Ford vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Sleigh_SSA1 </td><td> Relay attack on keyless entry system of a BMW</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Vincent_SSA1 </td><td> Relay attack on keyless entry system of a BMW</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Troughton_SSA1 </td><td> Relay attack on keyless entry system of three Range Rovers</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Stafford_SSA1 </td><td> Controlling several vehicle functions of a Chevrolet Volt using a custom Raspberry Pi and a modem.</td><td> Bus Attack </td></tr> 
<tr><td> ID2019_Lim_SSA1 </td><td> Unlocking and starting a vehicle</td><td> Bus Attack </td></tr> 
<tr><td> ID2019_Bianchini_SSA1 </td><td> A keyless entry car was immobilised remotely in a car park in Australia</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Gerber_SSA1 </td><td> Relay attack on keyless entry system of a vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Morgan_SSA1 </td><td> Relay attack on keyless entry system of six vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_FleetNews_SSA1 </td><td> Relay attack on keyless entry system of a BMW</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Kloeckner_SSA1 </td><td> Relay attack on keyless entry system of a BMW and an Audi</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Pridding_SSA1 </td><td> Relay attack on keyless entry system of two Peugeots</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Adams_SSA1 </td><td> Relay attack on keyless entry system of a Range Rover</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Brookes_SSA1 </td><td> Relay attack on keyless entry system of a Range Rover</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Shmee_SSA1 </td><td> Relay attack on keyless entry system of a vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Ng_SSA1</td><td> Smart alarms left 3 million cars vulnerable to hackers who could turn off motorsNg--https://www.cnet.com/tech/services-and-software/smart-alarms-left-3m-cars-vulnerable-to-hackers-who-could-turn-off-motors/-  </td><td>  </td></tr> 
<tr><td> ID2019_Cimpanu_SSA1 </td><td> Displaying false information in Infotainment unit in Telsa Model 3</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Keen_MSA1_Step1 </td><td> Manipulation of AUTOPILOT ECU Firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Keen_MSA1_Step2_1 </td><td> Remote control of electric steering</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Keen_SSA1 </td><td> Adversarial examples are used to trigger the Autowiper function in a Tesla</td><td> Artificial Intelligence Attack </td></tr> 
<tr><td> ID2019_Keen_SSA2 </td><td> False stickers on the street mislead lane detection mechanism in a Telsa</td><td> Environment Attack </td></tr> 
<tr><td> ID2019_Nespral_MSA1_Step1 </td><td> Key fob spoofing attack unlocks car</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Nespral_MSA1_Step2_1 </td><td> Key fob spoofing attack unlocks car</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Bicchierai_MSA1_Step1 </td><td> Access to GPS tracking app enables attacker to disable a vehicles engine remotely</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Bicchierai_MSA1_Step2_1 </td><td> Access to GPS tracking app enables attacker to disable a vehicles engine remotely</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2019_Bicchierai_MSA1_Step3_2 </td><td> Access to GPS tracking app enables attacker to disable a vehicles engine remotely</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Parallax_SSA1 </td><td> Spoofing of the key fob of a Ford</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Bruno_SSA2 </td><td> Analysing CAN traffic to add functionalities to the vehicle</td><td> Bus Attack </td></tr> 
<tr><td> ID2019_DailyPioneer_MSA1_Step1 </td><td> Vehicle theft by jamming valid GPRS signals and getting access to vehicle with magnetic key</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_DailyPioneer_MSA1_Step2_1 </td><td> Vehicle theft by jamming valid GPRS signals and getting access to vehicle with magnetic key</td><td> Wireless Attack </td></tr> 
<tr><td> ID2012_Kovacs_MSA1_Step1 </td><td> By installing a GPS tracker in vehicles, thieves were able to track the vehicles and copy the keys in order to steal the cars</td><td> Wireless Attack </td></tr> 
<tr><td> ID2012_Kovacs_MSA1_Step2_1 </td><td> By installing a GPS tracker in vehicles, thieves were able to track the vehicles and copy the keys in order to steal the cars</td><td> Software Attack </td></tr> 
<tr><td> ID2012_Kovacs_MSA1_Step3_2 </td><td> By installing a GPS tracker in vehicles, thieves were able to track the vehicles and copy the keys in order to steal the cars</td><td> Hardware Attack </td></tr> 
<tr><td> ID2012_Kovacs_MSA1_Step4_3 </td><td> By installing a GPS tracker in vehicles, thieves were able to track the vehicles and copy the keys in order to steal the cars</td><td> Software Attack </td></tr> 
<tr><td> ID2012_Kovacs_MSA1_Step5_4 </td><td> By installing a GPS tracker in vehicles, thieves were able to track the vehicles and copy the keys in order to steal the cars</td><td> Wireless Attack </td></tr> 
<tr><td> ID2012_CoreSecurity_SSA1 </td><td> Denial of Service on the Wi-Fi communication of Ford Edge vehicles due to a vulnerability in Broadcoms BCM4325 and BCM4329 combo solutions firmware</td><td> Wireless Attack </td></tr> 
<tr><td> ID2013_Pauli_MSA1_Step1 </td><td> Saftey-critical systems can be controlled via the diagnostic ports CAN connection</td><td> Bus Attack </td></tr> 
<tr><td> ID2013_Pauli_MSA1_Step2_1 </td><td> Saftey-critical systems can be controlled via the diagnostic ports CAN connection</td><td> Bus Attack </td></tr> 
<tr><td> ID2014_Dhanjani_MSA1_Step1 </td><td> Brute force attack on Tesla mobile app enables attackers to track vehicles, extract information from the app and even unlock the doors</td><td> Software Attack </td></tr> 
<tr><td> ID2014_Dhanjani_MSA1_Step2_1 </td><td> Brute force attack on Tesla mobile app enables attackers to track vehicles, extract information from the app and even unlock the doors</td><td> Software Attack </td></tr> 
<tr><td> ID2014_Dhanjani_MSA2_Step1 </td><td> Brute force attack on Tesla mobile app enables attackers to track vehicles, extract information from the app and even unlock the doors</td><td> Software Attack </td></tr> 
<tr><td> ID2014_Dhanjani_MSA2_Step2_1 </td><td> Brute force attack on Tesla mobile app enables attackers to track vehicles, extract information from the app and even unlock the doors</td><td> Software Attack </td></tr> 
<tr><td> ID2014_Aaronson_MSA1_Step1 </td><td> Installing cellular device to the telematics ECU leads to remote access to the attached CAN network. Safety-critical systems can be controlled.</td><td> Hardware Attack </td></tr> 
<tr><td> ID2014_Aaronson_MSA2_Step1 </td><td> Installing cellular device to the telematics ECU leads to remote access to the attached CAN network. Safety-critical systems can be controlled.</td><td> Hardware Attack </td></tr> 
<tr><td> ID2014_Aaronson_MSA2_Step2_1 </td><td> Installing cellular device to the telematics ECU leads to remote access to the attached CAN network. Safety-critical systems can be controlled.</td><td> Wireless Attack </td></tr> 
<tr><td> ID2014_Aaronson_MSA1_Step2_1 </td><td> Installing cellular device to the telematics ECU leads to remote access to the attached CAN network. Safety-critical systems can be controlled.</td><td> Wireless Attack </td></tr> 
<tr><td> ID2014_Brewster_MSA1_Step1 </td><td> Security investigation of OBD Dongle uncovered missing encryption of http connection with backend server. </td><td> Software Attack </td></tr> 
<tr><td> ID2014_Brewster_MSA1_Step2_1 </td><td> Security investigation of OBD Dongle uncovered missing encryption of http connection with backend server. </td><td> Wireless Attack </td></tr> 
<tr><td> ID2014_Brewster_MSA1_Step3_1 </td><td> Security investigation of OBD Dongle uncovered missing encryption of http connection with backend server. </td><td> Software Attack </td></tr> 
<tr><td> ID2015_Brook_MSA1_Step1 </td><td> Several vulnerabilities found in OBD dongle during security investigation</td><td> Software Attack </td></tr> 
<tr><td> ID2015_Brook_MSA1_Step2_1 </td><td> Several vulnerabilities found in OBD dongle during security investigation</td><td> Wireless Attack </td></tr> 
<tr><td> ID2015_Bigelow_MSA1_Step1 </td><td> Using a custom device, vehicle functions, such as door locks, lights, etc. can be controlled remotely</td><td> Hardware Attack </td></tr> 
<tr><td> ID2015_Bigelow_MSA1_Step2_1 </td><td> Using a custom device, vehicle functions, such as door locks, lights, etc. can be controlled remotely</td><td> Wireless Attack </td></tr> 
<tr><td> ID2015_Greenberg_MSA1_Step1 </td><td> Man-in-the-Middle attack on GM OnStar RemoteLink App results in remote conttrol over vehicle functions like door locks and ignition</td><td> Hardware Attack </td></tr> 
<tr><td> ID2015_Greenberg_MSA1_Step2_1 </td><td> Man-in-the-Middle attack on GM OnStar RemoteLink App results in remote conttrol over vehicle functions like door locks and ignition</td><td> Wireless Attack </td></tr> 
<tr><td> ID2015_Greenberg_MSA1_Step3_2,Man-in-the-Middle attack on GM OnStar RemoteLink App results in remote conttrol over vehicle functions like door locks and ignition</td><td> Information DisclosureUN-T17: Hosted 3rd party software, e.g. entertainment applications, used as a means to attack vehicle systemsCAPEC-169: FootprintingAAD-16: Location/Trajectory Tracking through Device/Application--  </td><td>  </td></tr> 
<tr><td> ID2015_Greenberg_MSA1_Step4_3 </td><td> Man-in-the-Middle attack on GM OnStar RemoteLink App results in remote conttrol over vehicle functions like door locks and ignition</td><td> Wireless Attack </td></tr> 
<tr><td> ID2015_Smith_SSA1 </td><td> Malware attack on diagnostic tool can lead to a distribution of the malware on attached vehicles</td><td> Diagnostic Attack </td></tr> 
<tr><td> ID2015_Leyden_SSA1 </td><td> Vehicle location tracking by intercepting the communication between vehicles and roadside units</td><td> Wireless Attack </td></tr> 
<tr><td> ID2015_Greenberg_MSA2_Step1 </td><td> SMS messages can be used in insecure OBD Dongle to send malicious CAN commands to the vehicle. Thus, several car components can be controlled </td><td> Software Attack </td></tr> 
<tr><td> ID2015_Greenberg_MSA2_Step2_1 </td><td> SMS messages can be used in insecure OBD Dongle to send malicious CAN commands to the vehicle. Thus, several car components can be controlled </td><td> Wireless Attack </td></tr> 
<tr><td> ID2017_CISA_SSA1</td><td> Continental AG Infineon S-Gold 2 </td><td>  </td></tr> 
<tr><td> ID2017_CISA_SSA2 </td><td> Exploiting vulnerability in Temporary Mobile Subscriber Identity</td><td> TMSI) in telematics control modules  </td></tr> 
<tr><td> ID2015_Ilascu_MSA1_Step1</td><td> Tesla Model S Hacked to Start Without KeyIlascu--https://news.softpedia.com/news/Tesla-Model-S-Hacked-to-Start-Without-Key-470827.shtml-  </td><td>  </td></tr> 
<tr><td> ID2015_Ilascu_MSA1_Step2_1</td><td> Tesla Model S Hacked to Start Without KeyIlascu--https://news.softpedia.com/news/Tesla-Model-S-Hacked-to-Start-Without-Key-470827.shtml-  </td><td>  </td></tr> 
<tr><td> ID2015_NVD_SSA1 </td><td> Bluetooth stack vulnerability on BMW Infotainment ECU leads to crash of CD/Multimedia software</td><td> Software Attack </td></tr> 
<tr><td> ID2017_CISA_SSA3 </td><td> Man-in-the-Middle attack on telematics communication of Hyundai exploits hard-coded keys in Hyundai Motor America Blue Link 3.9.5 and 3.9.4</td><td> Wireless Attack </td></tr> 
<tr><td> ID2017_CISA_SSA4 </td><td> Extracting sensitive information like vehicle location can lead to vehicle theft </td><td> Software Attack </td></tr> 
<tr><td> ID2019_Torchinsky_SSA1 </td><td> Spoofing position signal via GPS leads to display of false positions</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_CBS_SSA1 </td><td> Relay attack on keyless entry system of a Mini Cooper</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_ITV_SSA2 </td><td> Relay attack on keyless entry system of 16 different vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Lisandru_SSA1 </td><td> Modification of functions such as hill-start assistance in Dacia vehciles by misusing the CAN programming tool ddt4all. </td><td> Software Attack </td></tr> 
<tr><td> ID2019_Egan_SSA1 </td><td> Relay attack on keyless entry system of several vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_rhys_MSA1_Step1 </td><td> Manipulating and tuning of vehicle functions using an OBD-CAN device</td><td> Bus Attack </td></tr> 
<tr><td> ID2019_rhys_MSA1_Step2_1 </td><td> Manipulating and tuning of vehicle functions using an OBD-CAN device</td><td> Bus Attack </td></tr> 
<tr><td> ID2019_Goodin_SSA1 </td><td> Tracking and access over vehicle of rental Ford cars even after five months due to improper account management in the FordPass mobile app.</td><td> Software Attack </td></tr> 
<tr><td> ID2019_KeenLab_MSA1_Step1 </td><td> Two security vulnerabilities found in a Tesla’s Model X and Model S Wi-Fi modules resulting in a buffer overflow attack</td><td> Software Attack </td></tr> 
<tr><td> ID2019_KeenLab_MSA1_Step2_1 </td><td> Two security vulnerabilities found in a Tesla’s Model X and Model S Wi-Fi modules resulting in a buffer overflow attack</td><td> Software Attack </td></tr> 
<tr><td> ID2019_KeenLab_MSA1_Step3_2 </td><td> Two security vulnerabilities found in a Tesla’s Model X and Model S Wi-Fi modules resulting in a buffer overflow attack</td><td> Software Attack </td></tr> 
<tr><td> ID2019_KeenLab_MSA1_Step4_3 </td><td> Two security vulnerabilities found in a Tesla’s Model X and Model S Wi-Fi modules resulting in a buffer overflow attack</td><td> Software Attack </td></tr> 
<tr><td> ID2019_KeenLab_MSA1_Step5_4 </td><td> Two security vulnerabilities found in a Tesla’s Model X and Model S Wi-Fi modules resulting in a buffer overflow attack</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Rekawek_SSA1</td><td> How I hacked Volkswagen and Skoda. A story about Volkswagen Group Car Remote Hacking. Rekawek--https://blog.vensis.pl/2019/11/vw-hacking/-  </td><td>  </td></tr> 
<tr><td> ID2019_Rekawek_SSA3 </td><td> During a security investigation of Skoda mobile app API, all VIN numbers registered to the app can be brute forced to acquire health reports for these vehicles from the Volkswagen backend server</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2019_Rekawek_SSA2 </td><td> During a security investigation of Skoda mobile app API, the health report generation function can be attacked by a denial of service attack</td><td> Software Attack </td></tr> 
<tr><td> ID2019_Sugawara_SSA1 </td><td> Injecting voice commands in Tesla and Ford vehicles can unlock the and start the cars </td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Chin_SSA1 </td><td> Tracking, starting, and stopping a vehicle remotely of ex-girlfriends car </td><td> Software Attack </td></tr> 
<tr><td> ID2019_Nxumalo_SSA1 </td><td> Social engineering used to convince vehicle owners to system upgrades which enabled criminals to steal the vehicles </td><td> Software Attackcriminals either hacked into the dealership’s system and stole people’s information, or there were people working within the dealerships who leaked customers’ information.  </td></tr> 
<tr><td> ID2019_Raz_MSA1_Step1 </td><td> Tire Pressure Monitoring System</td><td> TPMS) signals can be intercepted and spoofed  </td></tr> 
<tr><td> ID2019_Raz_MSA1_Step2_1 </td><td> Tire Pressure Monitoring System</td><td> TPMS) signals can be intercepted and spoofed  </td></tr> 
<tr><td> ID2019_Lisandru_SSA2 </td><td> Changing the media skin/theme in a Dacia via USB stick</td><td> Hardware Attack </td></tr> 
<tr><td> ID2019_Lisandru_SSA3 </td><td> Modifying vehicle functions like seatbelt warning on a Dacia Duster by using the CAN programming tool DDT4ALL</td><td> Diagnostic AttackDDT4ALL tool is mainly aimed at CAN ISO_TP network study. </td></tr> 
<tr><td> ID2019_DeClerq_SSA1 </td><td> Key fob spoofing leads to theft of several Lexus and Mercedes vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Dash_MSA1_Step1 </td><td> Automated attacks influence robotic vehicles </td><td> Software AttackCollect time series data of control algortihm </td></tr> 
<tr><td> ID2019_Dash_MSA1_Step2_1 </td><td> Automated attacks influence robotic vehicles </td><td> Software AttackInject malicious libraries </td></tr> 
<tr><td> ID2019_Dash_MSA1_Step3_2 </td><td> Automated attacks influence robotic vehicles </td><td> Software Attack </td></tr> 
<tr><td> ID2019_Dash_MSA1_Step4_2 </td><td> Automated attacks influence robotic vehicles </td><td> Software Attack </td></tr> 
<tr><td> ID2019_Dash_MSA1_Step5_2 </td><td> Automated attacks influence robotic vehicles </td><td> Software Attack </td></tr> 
<tr><td> ID2019_Kelly_SSA1 </td><td> Relay attack on keyless entry system of five Ford Fiestas</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Allen_SSA1 </td><td> Relay attack on keyless entry system of 19 different vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Mills_SSA1 </td><td> Relay attack on keyless entry system of 100 Toyota and Lexus vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Heeds_SSA1 </td><td> Key fob spoofing leads to theft of a Fiat Abarth</td><td> Wireless Attack </td></tr> 
<tr><td> ID2019_Maloney_SSA1 </td><td> Installing a hidden dongle leads to manipulation of the displayed odometer values.</td><td> Hardware Attack </td></tr> 
<tr><td> ID2019_Fowler_SSA1 </td><td> Data, such as call logs, emails, photos, etc. can be extracted from the Infotainment system of a Chevrolet Volt </td><td> Software Attack </td></tr> 
<tr><td> ID2019_Rndash_SSA1 </td><td> Custom Android app and an Arduino is used to send malicious messages over the CAN bus to control vehicle features like ESP or hazard lights</td><td> Software Attack </td></tr> 
<tr><td> ID2010_Koscher_MSA1_Step3_2 </td><td> Firmware Modification</td><td> Software Attack </td></tr> 
<tr><td> ID2016_Miller_MSA2_Step3_2 </td><td> Modifying firmware</td><td> Software Attack </td></tr> 
<tr><td> ID2013_Miller_MSA6_Step3_2</td><td> Adventures in Automotive Networks and Control Units</td><td> Miller----   </td></tr> 
<tr><td> ID2005_Alrabady_MSA1_Step1 </td><td> Gaining access to vehicle by Challenge Forward Prediction Attack</td><td> Cryptographic Attack </td></tr> 
<tr><td> ID2018_ITV_SSA1 </td><td> Relay attack on keyless entry system of a Lexus RX</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Rossignol_SSA1 </td><td> Monitoring CAN traffic of a Cadillac ELR via its OBD port.</td><td> Bus Attack </td></tr> 
<tr><td> ID2018_Lambert_SSA2 </td><td> Setting ECU of Tesla Model 3 into factory mode which reveals information about the powertrain of the vehicle </td><td> Software Attack </td></tr> 
<tr><td> ID2018_Luo_SSA1 </td><td> Volkswagen Customer-Link App and HTC Customer-Link Bridge can be exploitet in order to send malicious messages to the CAN bus of vehicles</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Berta_MSA1_Step1 </td><td> SMS messages sent to an OBD device transmit malicious CAN commands to the vehicle. Thus, several car components can be controlled </td><td> Hardware Attack </td></tr> 
<tr><td> ID2018_Berta_MSA1_Step2_1 </td><td> SMS messages sent to an OBD device transmit malicious CAN commands to the vehicle. Thus, several car components can be controlled </td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Armstrong_SSA1 </td><td> Relay attack on keyless entry system of 45 Ford Fiestas</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Weber_MSA1_Step1 </td><td> Vgate iCar 2 WiFi OBD2 Dongles contain vulnerabilities which enable attackers to control safety-critical functions of a vehicle </td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Weber_MSA1_Step2_1 </td><td> Vgate iCar 2 WiFi OBD2 Dongles contain vulnerabilities which enable attackers to control safety-critical functions of a vehicle </td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Weber_MSA1_Step3_2 </td><td> Vgate iCar 2 WiFi OBD2 Dongles contain vulnerabilities which enable attackers to control safety-critical functions of a vehicle </td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Stykas_SSA1 </td><td> Vehicle tracking and disabling engine via backend server misusing telematic services</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Cheromcha_SSA1 </td><td> Relay attack on keyless entry system of a Mercedes-Benz C-Class</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Brandt_SSA1 </td><td> Relay attack on keyless entry system of a Chevy Suburban</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_CBS_SSA1 </td><td> Relay attack on keyless entry system of a vehicle</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Zeng_MSA1_Step1 </td><td> False GPS signals can be spoofed to GPS navigation of a vehicle by a malicious device which needs to be attached to the vehicle.</td><td> Hardware Attack </td></tr> 
<tr><td> ID2018_Zeng_MSA1_Step2_1 </td><td> False GPS signals can be spoofed to GPS navigation of a vehicle by a malicious device which needs to be attached to the vehicle.</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Innovator_MSA1_Step1 </td><td> USB Malware attack enables attackers to extract private data from the Infotainment system</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Innovator_MSA1_Step2_1 </td><td> USB Malware attack enables attackers to extract private data from the Infotainment system</td><td> Bus Attack </td></tr> 
<tr><td> ID2018_Innovator_MSA1_Step3_2 </td><td> USB Malware attack enables attackers to extract private data from the Infotainment system</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Thomson_SSA1 </td><td> Access and control over components like dash cameras and in-vehicle computers of police cars, ambulances, and other emergency vehicles due to vulnerable wireless gateways</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Cheromcha_SSA2 </td><td> Relay attack on keyless entry system of three Lexus vehicles</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Nigam_MSA1_Step1 </td><td> Vehicle theft by capture-replay attack of valid key fob signals</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Nigam_MSA1_Step2_1 </td><td> Vehicle theft by capture-replay attack of valid key fob signals</td><td> Wireless Attack </td></tr> 
<tr><td> ID2018_Leyden_MSA1_Step1 </td><td> Improper user management leads to access and control of vehicle data by previous owners</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Leyden_MSA1_Step2_1 </td><td> Improper user management leads to access and control of vehicle data by previous owners</td><td> Software Attack </td></tr> 
<tr><td> ID2018_Tan_MSA1_Step1</td><td> Sporean drivers, beware: Keyless cars getting hacked into in MalaysiaTan--https://mothership.sg/2018/02/keyless-car-thefts-malaysia/-  </td><td>  </td></tr> 
<tr><td> ID2018_Tan_MSA1_Step2_1</td><td> Sporean drivers, beware: Keyless cars getting hacked into in MalaysiaTan--https://mothership.sg/2018/02/keyless-car-thefts-malaysia/-  </td><td>  </td></tr> 
<tr><td> ID2018_Childers_MSA1_Step1</td><td> Investigators warn of keyless cars being broken into due to key fob hackingChilders--https://abc13.com/keyless-cars-hack-key-fob-thieves/3785008/-  </td><td>  </td></tr> 
<tr><td> ID2018_Childers_MSA1_Step2_1</td><td> Investigators warn of keyless cars being broken into due to key fob hackingChilders--https://abc13.com/keyless-cars-hack-key-fob-thieves/3785008/-  </td><td>  </td></tr> 
<tr><td> ID2018_Dent_MSA1_Step1 </td><td> Vehicle theft of a Tesla</td><td> by capture-replay attack of valid key fob signals </td></tr> 




</table>
