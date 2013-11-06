Age Gateways
============

Introduction
++++++++++++

In campaigns where alcohol brands are involved, an Age Gateway is required. This document covers the Age Gateway requirements of the Diageo sites (Smirnoff, Guinness, etc)

Types of Age Gateways
+++++++++++++++++++++

- Diageo's "The Perfect Age Gateway", Web - This is a javascript-based age gateway hosted on the Neo platform. It provides an overlay over the current site, allowing visitors a sneek peek which results in more follow-through. This age gateway doesn't work on devices that doesn't have javascript support or have it disabled.

- Jmbo Age Gateway, Web - 

- Jmbo Age Gateway, Mobi - 

- USSD Age Gateway - 

Scope of Work
+++++++++++++

Considerations:

- Which front-ends will the project support? An age gateway needs to be implemented for every required front-end.
- Does the project require a mobi-site frontend? Remember that the Diageo Perfect Age Gateway only supports javascript enabled devices, which doesn't include any low-end devices.

Limitations
+++++++++++

- The current implementations do not support link pass-through, which means that any direct link on the site results in redirection back to the homepage. There are currentl plans to have this implemented.

Code
++++

- Links to the Diageo Perfect Age Gateway documentation can be found on Central (TODO: add link)
- An implementation of a USSD age gateway has been implemented in Figo for the GFM project (TODO: add link, relevant info)
- TODO: information about Jmbo / django implemented age gateways)

Screenshots
+++++++++++
