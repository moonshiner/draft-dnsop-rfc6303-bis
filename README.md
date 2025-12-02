```




DNSOP                                                   T. Wicinski, Ed.
Internet-Draft                                          30 November 2025
Updates: 6603 (if approved)                                             
Intended status: Best Current Practice                                  
Expires: 3 June 2026


             Revision to Locally Served DNS Zones Registry
                       draft-dnsop-rfc6303-bis-00

Abstract

   RFC 6063, "Locally Served DNS Zones", defines an IANA registry called
   "Locally-Served DNS Zones".  This document changes the registration
   procedure for that registry from "IETF Review" to "Expert Review".
   This document updates RFC 6063.

Status of This Memo

   This Internet-Draft is submitted in full conformance with the
   provisions of BCP 78 and BCP 79.

   Internet-Drafts are working documents of the Internet Engineering
   Task Force (IETF).  Note that other groups may also distribute
   working documents as Internet-Drafts.  The list of current Internet-
   Drafts is at https://datatracker.ietf.org/drafts/current/.

   Internet-Drafts are draft documents valid for a maximum of six months
   and may be updated, replaced, or obsoleted by other documents at any
   time.  It is inappropriate to use Internet-Drafts as reference
   material or to cite them other than as "work in progress."

   This Internet-Draft will expire on 3 June 2026.

Copyright Notice

   Copyright (c) 2025 IETF Trust and the persons identified as the
   document authors.  All rights reserved.

   This document is subject to BCP 78 and the IETF Trust's Legal
   Provisions Relating to IETF Documents (https://trustee.ietf.org/
   license-info) in effect on the date of publication of this document.
   Please review these documents carefully, as they describe your rights
   and restrictions with respect to this document.  Code Components
   extracted from this document must include Revised BSD License text as
   described in Section 4.e of the Trust Legal Provisions and are
   provided without warranty as described in the Revised BSD License.




Wicinski                   Expires 3 June 2026                  [Page 1]

Internet-Draft                 rfc6303-bis                 November 2025


Table of Contents

   1.  Introduction  . . . . . . . . . . . . . . . . . . . . . . . .   2
   2.  Terminology . . . . . . . . . . . . . . . . . . . . . . . . .   2
     2.1.  Updates to 6063 . . . . . . . . . . . . . . . . . . . . .   2
   3.  References  . . . . . . . . . . . . . . . . . . . . . . . . .   2
     3.1.  Normative References  . . . . . . . . . . . . . . . . . .   2
     3.2.  Informative References  . . . . . . . . . . . . . . . . .   3
   Appendix A.  Appendix . . . . . . . . . . . . . . . . . . . . . .   3
   Acknowledgements  . . . . . . . . . . . . . . . . . . . . . . . .   3
   Author's Address  . . . . . . . . . . . . . . . . . . . . . . . .   3

1.  Introduction

2.  Terminology

   The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT",
   "SHOULD", "SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and
   "OPTIONAL" in this document are to be interpreted as described in BCP
   14 [RFC2119] [RFC8174] when, and only when, they appear in all
   capitals, as shown here.  DNS terminology is as described in
   [RFC8499].

2.1.  Updates to 6063

   OLD:

   This registry can be amended through "IETF Review" as per [RFC5226].
   As part of this review process, it should be noted that once a zone
   is added it is effectively added permanently; once an address range
   starts being configured as a local zone in systems on the Internet,
   it will be impossible to reverse those changes.

   NEW:

   This registry can be amended through "Expert Review" policy
   (Section 4.5 of [RFC8126]).  As part of this review process, it
   should be noted that once a zone is added it is effectively added
   permanently; once an address range starts being configured as a local
   zone in systems on the Internet, it will be impossible to reverse
   those changes.  More guidance for Designated Experts is provided in
   Section TBD.

3.  References

3.1.  Normative References





Wicinski                   Expires 3 June 2026                  [Page 2]

Internet-Draft                 rfc6303-bis                 November 2025


   [RFC2119]  Bradner, S., "Key words for use in RFCs to Indicate
              Requirement Levels", BCP 14, RFC 2119,
              DOI 10.17487/RFC2119, March 1997,
              <https://www.rfc-editor.org/info/rfc2119>.

3.2.  Informative References

   [RFC8174]  Leiba, B., "Ambiguity of Uppercase vs Lowercase in RFC
              2119 Key Words", BCP 14, RFC 8174, DOI 10.17487/RFC8174,
              May 2017, <https://www.rfc-editor.org/info/rfc8174>.

   [RFC8499]  Hoffman, P., Sullivan, A., and K. Fujiwara, "DNS
              Terminology", RFC 8499, DOI 10.17487/RFC8499, January
              2019, <https://www.rfc-editor.org/info/rfc8499>.

Appendix A.  Appendix

Acknowledgements

Author's Address

   Tim Wicinski (editor)
   Elkins, WV 26241
   United States of America
   Email: tjw.ietf@gmail.com


























Wicinski                   Expires 3 June 2026                  [Page 3]
```
