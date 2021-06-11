

# V8: Data Protection Verification Requirements

## Control Objective
There are three key elements to sound data protection: Confidentiality, Integrity and Availability (CIA). This
standard assumes that data protection is enforced on a trusted system, such as a server, which has been hardened
and has sufficient protections.
Applications have to assume that all user devices are compromised in some way. Where an application transmits
or stores sensitive information on insecure devices, such as shared computers, phones and tablets, the application
is responsible for ensuring data stored on these devices is encrypted and cannot be easily illicitly obtained, altered
or disclosed.
Ensure that a verified application satisfies the following high level data protection requirements:
* Confidentiality: Data should be protected from unauthorized observation or disclosure both in transit and
when stored.
* Integrity: Data should be protected from being maliciously created, altered or deleted by unauthorized
attackers.
* Availability: Data should be available to authorized users as required.

### [V8.1: General Data Protection](v8.1_General_Data_Protection.md)
### [V8.2: Client-Side Data Protection](v8.2_Client-Side_Data_Protection.md)
### [V8.3: Sensitive Private Data](v8.3_Sensitive_Private_Data.md)
### [References](references.md)

[Main page](../README.md) | [<< Previous Chapter](../V7/README.md) |  [Next Chapter >>](../V9/README.md)
| --- | --- | --- |
