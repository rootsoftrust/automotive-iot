In the automotive ecosystem, there are various types of data which are transfered between a cloud instantiation and the vehicle itself. Data includes:
<ul>
  <li>payment data</li>
  <li> personally identifiable information</li>
  <li>location data</li>
  <li>data related to the secure operation of the vehicle including firmware updates</li>
  <li>data used for authentication</li>
  <li>telemetrics from the vehicle</li>
  <li>data related to the safe operation of the vehicle</li>
</ul>

<ul>The data above has various security needs, including:
<li>payment data must be confidential, have data origin authenticity which also implies integrity to reduce fraud.</li>
<li>location data must be confidential to ensure privacy.</li>
<li>firmware updates require confidentiality, data origin authenticity, integrity and availability to protect against malware, person-in-the-middle attacks. </li>
<li>authentication data must be confidential, have data origin authenticity and availability.</li>
</ul>



This data is transfered between vehicle and cloud mainly through the use of API's.
<p></p>
This data must be classified based on the risk of a security breach and the impact of the breach on the safe operation of the vehicle. Once a claasificarion scheme has been generated, a NIST CSF profile can be made and CSA matrix controls applied where mitigation is necessary. 
