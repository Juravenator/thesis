This is the source tree of my Master thesis. The compiled version can be
found here, as well as on [CDS](https://cds.cern.ch/record/2265916).

The Compact Muon Solenoid (CMS) Trigger Supervisor (TS) is a software framework that has been designed to
handle the CMS Level-1 trigger setup, configuration and monitoring during data
taking as well as all communications with the main run control of CMS.

The interface consists of a web-based GUI rendered by a back-end C++ framework
(AjaXell) and a front-end JavaScript framework (Dojo).  
These provide developers with the tools they need to to write their own custom
control panels.

However, currently there is much frustration with this framework given the age
of the Dojo library and the various hacks needed to implement modern use cases.

The task at hand is to renew this library and its developer tools, updating it
to use the newest standards and technologies, while maintaining full
compatibility with legacy code.

This document describes the requirements, development process, and changes to
this framework that were included in the upgrade from v2.x to v3.x.
