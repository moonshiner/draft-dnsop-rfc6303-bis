%%%
title = "Revision to Locally Served DNS Zones Registry"
abbrev = "rfc6303-bis"
docName = "@DOCNAME@"
updates = [6603]
ipr = "trust200902"
area = "Internet"
workgroup = "DNSOP"
submissiontype = "IETF"
keyword = ["DNS", "IANA"]

[seriesInfo]
name = "Internet-Draft"
value = "@DOCNAME@"
stream = "IETF"
status = "bcp"

[[author]]
initials = "T."
surname = "Wicinski"
fullname = "Tim Wicinski"
role = "editor"
  [author.address]
  email = "tjw.ietf@gmail.com"
  [author.address.postal]
  city = "Elkins"
  region = "WV"
  code = "26241"
  country = "USA"


%%%

.# Abstract

RFC 6063, "Locally Served DNS Zones", defines an IANA registry called
"Locally-Served DNS Zones". This document changes the registration procedure for
that registry from "IETF Review" to "Expert Review".  This document updates RFC 6063.

{mainmatter}

# Introduction {#introduction}

# Terminology {#terminology}

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this
document are to be interpreted as described in BCP 14 [@!RFC2119] [@RFC8174]
when, and only when, they appear in all capitals, as shown here.
DNS terminology is as described in [@?RFC8499].

## Updates to 6063


OLD:

   This registry can be amended through "IETF Review" as per [RFC5226].
   As part of this review process, it should be noted that once a zone
   is added it is effectively added permanently; once an address range
   starts being configured as a local zone in systems on the Internet,
   it will be impossible to reverse those changes.



NEW:

   This registry can be amended through "Expert Review" policy (Section 4.5 of [RFC8126]).
   As part of this review process, it should be noted that once a zone
   is added it is effectively added permanently; once an address range
   starts being configured as a local zone in systems on the Internet,
   it will be impossible to reverse those changes. More guidance for Designated
   Experts is provided in Section TBD.



{backmatter}

# Appendix


{numbered="false"}

# Acknowledgements {#acknowledgements}

