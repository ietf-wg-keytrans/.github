# Overview
Public keys used to provide end-to-end encrypted communication services are 
often authenticated solely by the assertion of the communications service provider 
(e.g., a video conferencing or instant messaging service providers). 
As a result, the underlying encryption protocols are left vulnerable 
to eavesdropping and impersonation by a service provider which distributes 
malicious public keys. To provide confidence to their users and to mitigate 
this attack, end-to-end encrypted communication service providers are increasingly 
looking to an authentication service to provide verifiability for 
identity-to-public-key bindings in the context of their service. 

A scheme for providing this verifiability of key bindings must be:

- Transparent: All end users (applications or devices) receive
  a globally consistent view of the data associated with each identity.

- User-friendly: Little (ideally zero) user action,
  or even awareness of the system, is required to verify a user’s key bindings.

- Private: The authentication service used by the service
  provider only reveals information about specific users,
  such as what keys are associated with an identity,
  or even whether or not a specific identity is registered by the service provider,
  to clients authorized to ask about that user

- Efficient: The computational requirements for the end user
  and the service provider should be practical to deploy
  for internet scale numbers of keys and for typical end-user devices.

Full charter: https://datatracker.ietf.org/wg/keytrans/about/

# Contributing

## Mailing List:
- [Subscribe](https://www.ietf.org/mailman/listinfo/keytrans)
- [View the Archive](https://mailarchive.ietf.org/arch/browse/keytrans/)



 
