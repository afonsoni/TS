# Broker
## Requirements
- Mediate the request for attributes between a health unit that requests data from a holder and those that have the respective data in their systems
- Does not maintain attribute values in its database
- Maintaining a map between groups of attributes of a respective holder and the health units that have the respective values
- Guarantee confidentiality, integrity and authenticity of the parties involved
- Entities must use a scheme that supports mutual authentication
- Infrastructure:
	- Server operating system: Ubuntu Server 20.04.6 LTS
	- Web server: Apache Tomcat 10.0.27
	- Data base: PostgreSQL 14.11
	- Secure Communication Library: OpenSSL 3.0.13
	- Management backend: Django 5.0.3
