---
layout: fr
title: Code Signing Certificate
author: vertion
date: November 29, 2021
amount: 450
milestones:
  - name: Assumed Name filed
    funds: 140 VTC
    done:
    status: unfinished
  - name: Certificate issued
    funds: 310 VTC
    done:
    status: unfinished
payouts:
  - date:
    amount:
  - date:
    amount:
---
The code signing certificate currently being used for OCM is issued by Comodo, EV (requires hardware based 2FA in possession of Gertjaap), expires September 2022 and is registered to Vertcoin Foundation, Inc. which isn't incorporated anymore.  This current process requiring hardware based 2FA in order to sign makes it difficult for others to sign software such as Vertcoin-Core and after September 2022, a whole new certificate will have to be issued under a new organization.  

Signing Windows and MacOS binaries with a certificate helps to bypass the blue Windows Defender Smart Screen and displays the name of the organization who signed the software which you are allowing to be run.  This helps to build trust and credibility when running the software.  

Windows and MacOS builds for Vertcoin-Core have never been code signed.  To ensure that Vertcoin-Core as well as OCM (after September 2022) and future software developed within the Vertcoin Project can be code signed, I propose the creation of the Vertcoin Project Code Signing Association.  This will be filed by my registered agent as an assumed name and meets the organization requirements for a code signing certificate issued by Comodo. The certificate and registered agent will be renewed yearly.

___________

**Comodo Code Signing Certificate - 1 Year $179**

**Certificate of Assumed Name and Registered Agent - $79**

___________

**Total - $258 (450 VTC as of November 29, 2021)**
