# Chapter 3: How to Test and Verify

Any PT implementation should have a documented plan and audit trail of testing, from within the code itself \("unit"\), throughout the development process \("quality assurance"\), all the way to 3rd party security audits before the PT is shipped. As part of this, a PT should, at least, provide a "Our Threat Model" document within its source code repository.

Code Testing, Unit Test, etc

* Tor on Writing Tests:

[https://github.com/torproject/tor/blob/master/doc/HACKING/WritingTests.md](https://github.com/torproject/tor/blob/master/doc/HACKING/WritingTests.md)

* Go Lang Writing Tests:

[https://golang.org/pkg/testing/](https://golang.org/pkg/testing/)

* Network Monitoring

&

Simulation

* Shadow \(

[https://shadow.github.io/\)](https://shadow.github.io/%29)

: "runs real applications like Tor and Bitcoin over a simulated Internet topology"

* Operator Foundation: Adversary Lab:

[https://github.com/OperatorFoundation/AdversaryLab](https://github.com/OperatorFoundation/AdversaryLab)

"Adversary Lab is a service that analyzes captured network traffic to extract statistical properties. Using this analysis, filtering rules can be synthesized to block sampled traffic."

* Transport Canary:

[https://github.com/OperatorFoundation/transport-canary](https://github.com/OperatorFoundation/transport-canary)

Security Audit Options

* OpenTech Fund Red Team Lab \(

[https://www.opentech.fund/lab/red-team-lab\)](https://www.opentech.fund/lab/red-team-lab%29)

: OTF Resource Labs are a general set of mechanisms utilized by the program to offset its current inability to provide long-term funding support. The OTF Red Team Lab: OTF is committed to establishing high-level Internet freedom technology privacy and security standards. One component of this commitment is conducting independent technology audits on all of its projects. OTF contracts with a range of professional information security auditors who assess the privacy and security limitations of each project and suggest remedial strategies or specific changes. These audits mitigate the risk inherent in funding cutting-edge technologies and strengthen the technical capacity of the project as well as the broader human rights and internet freedom technology community.

---

&gt;

Sample security audit: ChatSecure iOS Audit Blog Post:

[https://chatsecure.org/blog/chatsecure-security-audit/](https://chatsecure.org/blog/chatsecure-security-audit/)

; Quarks Lab \(3rd party audit\) original post:

[https://blog.quarkslab.com/security-assessment-of-instant-messaging-app-chatsecure-when-privacy-matters.html](https://blog.quarkslab.com/security-assessment-of-instant-messaging-app-chatsecure-when-privacy-matters.html)

