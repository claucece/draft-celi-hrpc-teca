---
title: "Technology-Enabled Child Abuse Considerations"
abbrev: "teca"
category: info

docname: draft-celi-hrpc-teca-latest
submissiontype: IRTF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: "IRTF"
workgroup: "Human Rights Protocol Considerations"
keyword:
 - next generation
 - unicorn
 - sparkling distributed ledger
venue:
  group: "Human Rights Protocol Considerations"
  type: "Research Group"
  mail: "hrpc@irtf.org"
  arch: "https://mailarchive.ietf.org/arch/browse/hrpc"
  github: "claucece/draft-celi-hrpc-teca"
  latest: "https://claucece.github.io/draft-celi-hrpc-teca/draft-celi-hrpc-teca.html"

author:
 -
    fullname: Sofia Celi
    organization: Brave
    email: cherenkov@riseup.net

normative:

informative:

...

--- abstract

TODO Abstract


--- middle

# Introduction

Digital technologies shape how children learn, communicate, and play. However, the same technologies can be misused to enable coercion, surveillance, manipulation, or exploitation of minors by adults or peers. This document refers to this as technology-enabled child abuse (TECA). It includes but is not limited to physical, emotional, or sexual abuse facilitated through digital means.

While most discussions of technology and children focus on content exposure or privacy compliance, technology-enabled abuse encompasses broader dynamics of control, dependency, and data exploitation that can occur within families, institutions, or online environments.

# Conventions and Definitions

{::boilerplate bcp14-tagged}


## Definition and Scope

Technology-enabled child abuse refers to any use of digital systems, connected devices, or online services to facilitate or intensify the abuse, control, or exploitation of a minor. This includes acts by:

* Parents, guardians, or relatives, who may misuse technology to monitor or punish.
* Teachers, coaches, or institutional staff, who may use surveillance or communication tools coercively.
* Peers, who may engage in bullying, extortion, or harassment.
* Unknown adults or organized groups, who exploit online platforms for grooming, manipulation, or trafficking.

## Common Tactics

The following categories illustrate—but are not limited to—how technology can be used to perpetrate abuse against children.

1. Surveillance and Monitoring

* Use of “parental control” or monitoring apps beyond protective intent, tracking all communications, locations, and activities.
* Smart home devices (cameras, speakers, TVs) used to overhear conversations or monitor behavior.
* Misuse of educational software or school-issued devices to surveil students beyond pedagogical purposes.
* Exploitation of IoT toys, GPS watches, or “child safety” trackers that upload location or voice data without consent.

2. Coercion and Manipulation

* Forcing children to disclose passwords, messages, or photos under threat or punishment.
* Coercive use of digital punishments (revoking device access, social isolation, public shaming via social media).
* Algorithmic manipulation, such as exploiting content recommendation systems to isolate a child or feed fear/shame narratives.

3. Exposure and Exploitation

* Coerced creation or sharing of intimate images ("self-generated CSAM").
* Non-consensual sharing of private photos or videos to humiliate or blackmail.
* Identity misuse—adults impersonating peers or friends to gain trust.
* Manipulation through "challenge" trends, games, or encrypted messaging for grooming purposes.

4. Peer Abuse and Cyberbullying

* Continuous online harassment via group chats, gaming platforms, or social networks.
* Amplification by algorithms that surface humiliating or harmful content.
* Use of AI tools (e.g., deepfakes) to fabricate compromising images or videos.

5. Institutional or Systemic Abuse

* School or platform data collection without transparency—creating lifelong digital traces exploitable for discrimination.
* Excessive logging and analytics on minors’ browsing or app use.
* Outsourced content moderation or “child safety” systems that process minors’ data at large scale without robust safeguards.

# Threat Model

From a security and privacy standpoint, these attacks differ from classical adversaries:

* The attacker often has legitimate authority or proximity (parent, teacher, platform operator).
* The child has limited agency to modify configurations, consent to data sharing, or understand consequences.
* Asymmetric power defines the relationship; coercion and dependency replace traditional financial or computational asymmetries.
* Attack vectors include shared accounts, school or family networks, IoT ecosystems, and devices nominally "for protection".

# Security Considerations

TODO Security


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
