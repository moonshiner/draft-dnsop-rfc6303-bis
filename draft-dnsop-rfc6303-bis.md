%%%
title = "Updates to Locally Served DNS Zones and IP Special-Purpose Address Space Registries"
abbrev = "Updates to RFCs 6303 and 6890"
docName = "@DOCNAME@"
updates = [6603, 6890]
ipr = "trust200902"
area = "OPS"
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

RFC 6063, "Locally Served DNS Zones", defines two IANA registries called
"IPv4 Locally-Served DNS Zone" and "IPv6 Locally-Served DNS Zone" registries.
This document changes the registration policy for
that registry from "IETF Review" to "Expert Review".

Also, this document updates IP Special-Purpose Address Space registries to indicate whether
an IP address block is eligible to be in Locally-Served DNS Zones.

This document updates RFC 6063 and RFC 6890.

{mainmatter}

# Introduction {#introduction}

In [@!RFC6303]  "Locally Served DNS Zones", it defines two IANA registries called
"IPv4 Locally-Served DNS Zone" and "IPv6 Locally-Served DNS Zone" registries.
This document changes the registration policy for
that registry from "IETF Review" to "Expert Review".

Also, this document updates IP Special-Purpose Address Space registries {{!RFC6890}} to indicate whether
an IP address block is eligible to be in Locally-Served DNS Zones.

PLEASE REMOVE THE FOLLOWING PARAGRAPH BEFORE PUBLISHING:
The source for this draft is maintained on GitHub at:
https://github.com/moonshiner/draft-dnsop-rfc6303-bis

# Terminology {#terminology}

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this
document are to be interpreted as described in BCP 14 [@!RFC2119] [@RFC8174]
when, and only when, they appear in all capitals, as shown here.
DNS terminology is as described in [@?RFC8499].

# Updates to RFC 6063 {#6063-updates}

Please update {{Section 8 of @!RFC6303}} "IANA Considerations" as follows:

OLD:

{:quote}
>   This registry can be amended through "IETF Review" as per {{?RFC5226}}.
>   As part of this review process, it should be noted that once a zone
>   is added it is effectively added permanently; once an address range
>   starts being configured as a local zone in systems on the Internet,
>   it will be impossible to reverse those changes.


NEW:

{:quote}
>  This registry can be amended through "Expert Review" policy ({{Section 4.5 of !RFC8126}}).
>  As part of this review process, it should be noted that once a zone
>  is added it is effectively added permanently; once an address range
>  starts being configured as a local zone in systems on the Internet,
>  it will be impossible to reverse those changes. More guidance for Designated
>  Experts is provided in {{guidance}} of THIS_DOCUMENT.

## Guidance for Designated Experts {#guidance}

In changing the approval to "Expert Review", there should be some additional guidance.
Here are some examples (not all mandatory) on what the Reviewer should look for:

1. Should have at least an internet-draft written which can explain the usage.

2. The various Working Groups in the IETF should have

3. Must be approved by someone named Tim.

## Changes to the IPv6 Locally-Served DNS Zones Registry

IANA is request to add the zones listed below to the "IPv6 Locally-Served DNS Zone" registry:

TBC with {{!RFC9637}} entries.

#  Changes to the IP Special-Purpose Space Registries {#6890-updates}

## Eligible to Locally-Served DNS Zones New Column

IANA is requested to add a new column, Eligible to Locally-Served DNS Zones, to the "IPv6 Special-Purpose Address Space" and "IPv4 Special-Purpose Address Space" registries.

## Eligible to Locally-Served DNS Zones Note

IANA is requested to add the following note to the "IPv6 Special-Purpose Address Space" and "IPv4 Special-Purpose Address Space" registries:

Eligible to Locally-Served DNS Zones:
: A boolean value indicating whether the IP address block is to be added to the Locally-Served DNS Zones IANA
  registry.

## IPv6 Locally-Served DNS Zone Registry Note

IANA is requested to add the following note to the "IPv6 Special-Purpose Address Space" registry:

Note:
: IANA has to add relevant entries for "Eligible to Locally-Served DNS Zones"
set to "True" in the IPv6 Locally-Served DNS Zone Registry.

## IPv4 Locally-Served DNS Zone Registry Note

IANA is requested to add the following note to the "IPv4 Special-Purpose Address Space" registry:

Note:
: IANA has to add relevant entries for "Eligible to Locally-Served DNS Zones"
set to "True" in the IPv4 Locally-Served DNS Zone Registry.

## Initial IPv6 Locally-Served DNS Zone Registry

TBC.

## Initial IPv4 Locally-Served DNS Zone Registry 

TBC.

# Operational Considerations

TBC.

# Security Considerations

This document does not add new security risks other than those already discussed in {{RFC6303}}, {{!RFC6890}}, and {{!RFC9637}}.

# IANA Considerations

Sections {{<6063-updates}} and {{<6890-updates}} include actions for IANA. These actions are not repeated here.

{backmatter}

{numbered="false"}

# Acknowledgements {#acknowledgements}

