# Certificate Authority
## Requirements
- Trusted entity external to the developed system
- Process of issuing and associating certificates with different entities of the system takes into account the possibility of heterogeneous mechanisms (i.e. different API, multiple authentication mechanisms)
- Certificate issuance uses the *Certificate Signing Request* (CSR) method
- Currently, communication with external entities is done via a REST API
- The Certificate Authority makes the list of revoked certificates available through an *Online Certificate Status Protocol* (OCSP) service