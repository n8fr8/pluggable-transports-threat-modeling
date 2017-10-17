## Chapter 9: Sample PT Threat Modeling Document

Every Pluggable Transport should provide a threat modeling document with its source code and binary distributions. This document is necessary to inform developers, auditors and ultimatley users, about what a PT can and cannot do.



\*\*\*\*  


Sunflower Protocol Disguise System

Sunflower is a Format Transforming Encryption System that disguises traffic as innocuous traffic

  


Adversary Models:

Threats and Responses:

* Threat: Scan for Encrypted Traffic

* Threat Description: Adversary tries to determine that encrypted traffic is being transmitted over the internet

* Threat Response: System disguises the traffic as other protocol using Format Transforming Encryption

* 
* Threat: Scan of Computer ports for Client or Server Listeners

* Threat Description: Adversary tries to perform scans of ports on either side to determine what type of service the client and destination

*     ports are.

* Threat Response: System, if a proper connection is not made, returns a message appropriate for a scan of some 'typical' service that may leave an open port

* 
* Threat: Deep Packet Inspection performed on Session to search for keywords or signatures in protocols

* Threat Description: System utilizes Regex pattern matching to find bad protocol

* 
* Threat: Advesary uses targeted blocking

* Threat Description: Adversary is performing selective blocking of system.

* Threat Response: System has no specific response, other than encryption, to prevent selective blocking.

* 
* Threat: Adversary requires password.

* Threat

* 
  


Third Party Verification Certification: 

&lt;

link to examplecertificate.pdf

&gt;

 or 

&lt;

  


Example:

ChatSecure iOS Audit Blog Post:

[https://chatsecure.org/blog/chatsecure-security-audit/](https://chatsecure.org/blog/chatsecure-security-audit/)

; Quarks Lab \(3rd party audit\) original post:

[https://blog.quarkslab.com/security-assessment-of-instant-messaging-app-chatsecure-when-privacy-matters.html](https://blog.quarkslab.com/security-assessment-of-instant-messaging-app-chatsecure-when-privacy-matters.html)

  


Example: Adversary Lab Assessment:  

&lt;

[https://Sunflower.org/AdversaryLab.html](https://Sunflower.org/AdversaryLab.html)

&gt;

; Adversary Lab:

[https://github.com/OperatorFoundation/AdversaryLab](https://github.com/OperatorFoundation/AdversaryLab)

Example: Threat Canary Results: 

&lt;

[https://Sunflower.org/TransportCanary.html](https://Sunflower.org/TransportCanary.html)

&gt;

; Transport Canary:

[https://github.com/OperatorFoundation/transport-canary](https://github.com/OperatorFoundation/transport-canary)

