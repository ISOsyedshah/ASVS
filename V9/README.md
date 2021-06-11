

# V9: Communications Verification Requirements

## Control Objective
Ensure that a verified application satisfies the following high level requirements:
* TLS or strong encryption is always used, regardless of the sensitivity of the data being transmitted
* The most recent, leading configuration advice is used to enable and order preferred algorithms and ciphers
* Weak or soon to be deprecated algorithms and ciphers are ordered as a last resort
* Deprecated or known insecure algorithms and ciphers are disabled.
Leading industry advice on secure TLS configuration changes frequently, often due to catastrophic breaks in
existing algorithms and ciphers. Always use the most recent versions of TLS configuration review tools (such as
SSLyze or other TLS scanners) to configure the preferred order and algorithm selection. Configuration should be
periodically checked to ensure that secure communications configuration is always present and effective.

### [V9.1: Communications Security Requirements](v9.1_Communications_Security_Requirements.md)
### [V9.2: Server Communications Security Requirements](v9.2_Server_Communications_Security_Requirements.md)
### [References](references.md)

[Main page](../README.md) | [<< Previous Chapter](../V8/README.md) |  [Next Chapter >>](../V10/README.md)
| --- | --- | --- |
