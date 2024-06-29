The second UNECE regulation, R156, covers providing safe and secure software updates through the implementation of a Software Update Management System. Traditional updates were carried out in approved garages but with todays connected vehicles, updates can be carried out over the air (OTA).
OTA updates can be split into 5 categories:

<b>SOTA</b>

Software over the air updates - focusing on vehicle and incar infotainment applications


<b>FOTA</b>

Firmware over the air updates 

<b>OTAP</b>

Over the air provisioning - automating setup and deployment, making the configuration process more efficient.

<b>OTASP</b>

Over the air service provisioning - procedure to enrol in, activate, manage and update or introduce new services provided to the user

<b>OTAPA</b>

Over the air parameter administration - procedure to update operational parameters used to configure the vehicles functionality from internal networks to driving functions.


The full lifecycle of updating software begins with a cloud native secure software development process where software is developed and tested in separate environments (DTAP). The full suite of security testing (static, dynamic, fuzzing) should be shifted left and continually run during the CI/CD process. Pentesting should also be carried out before deploying to the production environment and then tested in production. The infrastructure on which the development process runs should be built on the principle of zero trust. Software should be verified and signed before deployment through a secure deployment system. The attack paths considered here are over the full creation and deployment flow.
<p></p>
![cloud OTA delivery](/../../img/ota-cloud.png)
