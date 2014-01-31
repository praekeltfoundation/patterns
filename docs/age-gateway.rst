Age Gateways
============

This page is an early work in progress. Please don't rely on it for anything yet.

Introduction
++++++++++++

In campaigns where alcohol brands are involved, an Age Gateway is required.
This document covers the Age Gateway requirements of the Diageo sites 
(Smirnoff, Guinness, etc). An age gateway prompts the visitor for country 
and date of birth, in order to confirm that the visitor is of legal drinking 
age in their region. Visitors who are not of drinking age will receive an 
explanation and will be denied access to the rest of the site.

Types of Age Gateways
+++++++++++++++++++++

- Diageo's "The Perfect Age Gateway", Web - This is a javascript-based age 
  gateway hosted on the Neo platform. It provides an overlay over the current 
  site, allowing visitors a sneek peek which results in more follow-through. 
  This age gateway doesn't work on devices that don't have javascript support
  or have it disabled - so it is not suitable for feature phone mobi sites.

- Jmbo Age Gateway - An age gateway implemented by Praekelt for the Jmbo 
  CMS. This works for both web and mobi. While it is integrated with Jmbo,
  it can be used as inspiration for a Django age gateway for sites not
  using Jmbo. See the GFM project for an example of this used outside of
  Jmbo.

- USSD Age Gateway - An age gateway developed for the USSD platform.

Scope of Work
+++++++++++++

Considerations:

- Which front-ends will the project support? An age gateway needs to be 
  implemented for every required front-end.
- Does the project require a mobi-site frontend? Remember that the 
  Diageo Perfect Age Gateway only supports javascript enabled devices, 
  which doesn't include any low-end devices.
- The age gateway will be the first page that visitors interact with. 
  It needs to attract users to the rest of the site without violating 
  Diageo content policies. (see links below for more information)

Limitations
+++++++++++

- Passing links through the gateway was a limitation for the Jmbo
  age gateway but this has been implemented in December 2013.

Code
++++

- Documentation and code for the Diageo Perfect Age Gateway documentation 
  should be obtained from the client's Basecamp to ensure the project uses
  the latest version.
- An implementation of a USSD age gateway has been implemented in Figo for 
  the GFM project, somewhere in `https://github.com/praekelt/gfm-ussd-service/tree/develop/figo`
- Jmbo age gateway: `https://github.com/praekelt/jmbo-foundry/blob/develop/foundry/middleware.py#L42`

Screenshots
+++++++++++

- The USSD Age Gateway is accessible on \*120*8864*1139#

Lingo
+++++

- USSD - Unstructured Service Supplementary Data - see 
  `http://www.truteq.co.za/tips_ussd/`
- AG - Age Gateway
- Mobi - Low-end device web platform
- Web - Modern web platform which utilizes xhtml, css, javascript, 
  html5, css3 or a combination thereof
- Jmbo - A mobile-friendly CMS developed by Praekelt

See Also
++++++++

- Diageo Marketing Code: http://www.diageo.com/en-row/newsmedia/Pages/resource.aspx?resourceid=1287
