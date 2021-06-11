

# V7: Error Handling and Logging Verification Requirements

## Control Objective
The primary objective of error handling and logging is to provide useful information for the user, administrators,
and incident response teams. The objective is not to create massive amounts of logs, but high quality logs, with
more signal than discarded noise.
High quality logs will often contain sensitive data, and must be protected as per local data privacy laws or
directives. This should include:
* Not collecting or logging sensitive information unless specifically required.
* Ensuring all logged information is handled securely and protected as per its data classification.
* Ensuring that logs are not stored forever, but have an absolute lifetime that is as short as possible.
If logs contain private or sensitive data, the definition of which varies from country to country, the logs become
some of the most sensitive information held by the application and thus very attractive to attackers in their own
right.
It is also important to ensure that the application fails securely and that errors do not disclose unnecessary
information.

### [V7.1: Log Content Requirements](v7.1_Log_Content_Requirements.md)
### [V7.2: Log Content Requirements](v7.2_Log_Processing_Requirements.md)
### [V7.3: Log Content Requirements](v7.3_Log_Protection_Requirements.md)
### [V7.4: Log Content Requirements](v7.4_Error_Handling.md)
### [References](references.md)

[Main page](../README.md) | [<< Previous Chapter](../V6/README.md) |  [Next Chapter >>](../V8/README.md)
| --- | --- | --- |
