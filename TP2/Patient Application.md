# Patient Application
## Requirements
- Mobile application for Android and iOS operating systems
- Storage of personal identification data and the data subject’s digital certificate
- TCP/IP communication with certificate authority
- Periodic authentication (robust authentication mechanisms, confidentiality and integrity of data transferred to the holder's device)
- Data is transferred in JSON format - JavaScript Object Notation
- Guarantee of the integrity and authenticity of data stored on the holder's device
- Communication between the Patient Application and the Medical Application initiated via a QR Code by the bearer, always.
- Connection via:
	- BLE - Bluetooth Low Energy;
	- NFC - Near Field Communication;
	- WiFi-Aware.
- Communication supported through messages encoded in JSON format
- Guarantee of confidentiality and integrity of data transmitted between patient and doctor
- Allow auditing of interactions occurring with medical applications, for example, indicating the authorized attributes for a particular healthcare facility and when it occurred