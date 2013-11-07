Age Gateways
============

This page is an early work in progress. Please don't rely on it for anything yet.

Introduction
++++++++++++

In campaigns where alcohol brands are involved, an Age Gateway is required. This document covers the Age Gateway requirements of the Diageo sites (Smirnoff, Guinness, etc). An age gateway prompts the visitor for country and date of birth, in order to confirm that the visitor is of legal drinking age in their region. Visitors who are not of drinking age will receive an explanation and will be denied access to the rest of the site.

Types of Age Gateways
+++++++++++++++++++++

- Diageo's "The Perfect Age Gateway", Web - This is a javascript-based age gateway hosted on the Neo platform. It provides an overlay over the current site, allowing visitors a sneek peek which results in more follow-through. This age gateway doesn't work on devices that doesn't have javascript support or have it disabled.

- Jmbo Age Gateway, Web - An age gateway implemented by Praekelt for the Jmbo content management system (TODO: is this Jmbo specific? What about the AG used in GFM?)

- Jmbo Age Gateway, Mobi - An age gatweay implemented by Praekelt for mobi sites built on Jmbo

- USSD Age Gateway - An age gateway developed for the USSD platform.

Scope of Work
+++++++++++++

Considerations:

- Which front-ends will the project support? An age gateway needs to be implemented for every required front-end.
- Does the project require a mobi-site frontend? Remember that the Diageo Perfect Age Gateway only supports javascript enabled devices, which doesn't include any low-end devices.
- The age gateway will be the first page that visitors interact with. It needs to attract users to the rest of the site without violating Diageo content policies. (see links below for more information)

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

- The USSD Age Gateway is accessible on \*120*8864*1139#

Lingo
+++++

- USSD - (TODO: link or description? perhaps sphinx can fetch it)
- AG - Age Gateway
- Mobi - Low-end device web platform
- Web - Modern web platform which utilizes xhtml, css, javascript, html5, css3 or a combination thereof
- Jmbo - A mobile-friendly CMS developed by Praekelt

See Also
++++++++

- Diageo Marketing Code: http://www.diageo.com/en-row/newsmedia/Pages/resource.aspx?resourceid=1287
