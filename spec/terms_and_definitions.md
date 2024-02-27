
[//]: # (Pandoc Formatting Macros)

[//]: # (Portable Document Format)

[//]: # (blank)

[//]: # (: file format defined by ISO 32000-2)


## Terms & Definitions

# AAL

See: [[ref: authenticator assurance level]].



# ABAC<a id="abac"></a>

See: [[ref: attribute-based access control]].

# access control<a id="access-control"></a>

The process of granting or denying specific requests for obtaining and using information and related information processing services.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/access_control).

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Access_control): In [physical security](https://en.wikipedia.org/wiki/Physical_security) and [information security](https://en.wikipedia.org/wiki/Information_security), access control (AC) is the selective restriction of access to a place or other resource, while access management describes the process. The act of accessing may mean consuming, entering, or using. Permission to access a resource is called [authorization](#authorization).

# ACDC

See: [Authentic Chained Data Container](#authentic-chained-data-container).

# action

Something that is actually done (a 'unit of work' that is executed) by a single [actor](#actor) (on behalf of a given [party](#party)), as a single operation, in a specific context.Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#action).

# actor

An [entity](#entity) that can act (do things/execute [actions](#action)), e.g. people, machines, but not [organizations](#organization). A [digital agent](#digital-agent) can serve as an actor acting on behalf of its [principal](#principal).Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/terms/actor).

# address

See: [network address](#network-address).

# administering authority<a id="administering-authority"></a>

See: [administering body](#administering-body).

# administering body<a id="administering-body"></a>

A [legal entity](#legal-entity) [delegated](#delegation) by a [governing body](#governing-body) to administer the operation of a [governance framework](#governance-framework) and governed infrastructure for a [digital trust ecosystem](#digital-trust-ecosystem), such as one or more [trust registries](#trust-registries).

Also known as: [administering authority](#administering-authority).

# agency<a id="agency"></a>

In the context of decentralized digital trust infrastructure, the empowering of a [party](#party) to act independently of its own accord, and in particular to empower the party to employ an [agent](#agent) to act on the [party’s](#party) behalf.

# agent<a id="agent"></a>

An [actor](#actor) that is executing an [action](#action) on behalf of a [party](#party) (called the [principal](#principal) of that [actor](#actor)). In the context of decentralized digital trust infrastructure, the term “agent” is most frequently used to mean a [digital agent](#digital-agent).

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#agent).

See also: [wallet](#wallet).

Note: In a ToIP context, an agent is frequently assumed to have privileged access to the [wallet](#wallet)(s) of its principal. In market parlance, a mobile app performing the [actions](#action) of an agent is often simply called a [wallet](#wallet) or a [digital wallet](#digital-wallet).

# AID<a id="aid"></a>

See [autonomic identifier](#autonomic-identifier).

# anonymous<a id="anonymous"></a>

An adjective describing when the [identity](#identity) of a [natural person](#natural person) or other [actor](#actor) is unknown.

See also: [pseudonym](#pseudonym).

# anycast<a id="anycast"></a>

Anycast is a network [addressing](#address) and [routing](#routing) methodology in which a single [IP-address](#IP-address) is shared by devices (generally servers) in multiple locations. [Routers](#router) direct packets addressed to this destination to the location nearest the sender, using their normal decision-making algorithms, typically the lowest number of BGP network hops. Anycast [routing](#routing) is widely used by [content deliv](https://en.wikipedia.org/wiki/Content_delivery_network)e[ry networks](https://en.wikipedia.org/wiki/Content_delivery_network) such as web and name servers, to bring their content closer to end users.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Anycast).

See also: [broadcast](#broadcast), [multicast](#multicast), [unicast](#unicast).

# anycast address<a id="anycast-address"></a>

A [network address](network-address) (especially an [IP address](IP-address)) used for [anycast](#anycast) routing of network transmissions.

# appraisability (of a communications endpoint)<a id="appraisability-of-a-communications-endpoint"></a>

The ability for a [communication endpoint](#communication-endpoint) identified with a [verifiable identifier](verifiable-identifier) to be appraised for the set of its [properties](#property) that enable a [relying party](#relying-party) or a [verifier](#verifier-of-a-claim-or-credential) to make a [trust decision](#trust-decision) about communicating with that [endpoint](#endpoint).

See also: [trust basis](#trust-basis), [verifiability](#verifiability-of-a-digital-object-claim-or-assertion).

# appropriate friction<a id="appropriate-friction"></a>

A user-experience design principle for information systems (such as digital wallets) specifying that the level of attention required of the [holder](#holder) for a particular transaction should provide a reasonable opportunity for an informed choice by the [holder](#holder).

Source: [PEMC IGR](https://kantarainitiative.org/download/pemc-implementors-guidance-report/).

# attestation<a id="attestation"></a>

The issue of a statement, based on a decision, that fulfillment of specified [requirements](#requirement) has been demonstrated. In the context of decentralized digital trust infrastructure, an attestation usually has a [digital signature](#digital-signature) so that it is [cryptographically verifiable](#cryptographically-verifiable).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/attestation).

# attribute<a id="attribute"></a>

An identifiable set of data that describes an [entity](#entity), which is the [subject](#subject) of the attribute. 

See also: [property](#property).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#attribute): [Data](https://essif-lab.github.io/framework/docs/terms/data) that represents a characteristic that a [party](https://essif-lab.github.io/framework/docs/terms/party) (the [owner](https://essif-lab.github.io/framework/docs/terms/owner) of the [attribute](https://essif-lab.github.io/framework/docs/terms/attribute)) has attributed to an [entity](https://essif-lab.github.io/framework/docs/terms/entity) (which is the [subject](https://essif-lab.github.io/framework/docs/terms/subject) of that attribute).

Note: An [identifier](#identifier) is an attribute that uniquely identifies an [entity](#entity) within some context.

# attribute-based access control<a id="attribute-based-access-control"></a>

An [access control](#access-control) approach in which access is mediated based on [attributes](#attribute) associated with [subjects](#subject) (requesters) and the objects to be accessed. Each object and [subject](#subject) has a set of associated [attributes](#attribute), such as location, time of creation, access rights, etc. Access to an object is [authorized](#authorization) or denied depending upon whether the required (e.g., policy-defined) correlation can be made between the [attributes](#attribute) of that object and of the requesting [subject](#subject).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/attribute_based_access_control).

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Attribute-based_access_control): Attribute-based access control (ABAC), also known as policy-based access control for [IAM](https://en.wikipedia.org/wiki/Identity_management), defines an access control paradigm whereby a subject's authorization to perform a set of operations is determined by evaluating attributes associated with the subject, object, requested operations, and, in some cases, environment attributes.

# audit (of system controls)<a id="audit-of-system-controls"></a>

Independent review and examination of records and activities to assess the adequacy of system controls, to ensure compliance with established [policies](#policy) and operational procedures.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/audit).

# audit log<a id="audit-log"></a>

An audit log is a security-relevant chronological [record](#record), set of [records](#record), and/or destination and source of [records](#record) that provide documentary evidence of the sequence of activities that have affected at any time a specific operation, procedure, event, or device.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Audit_trail).

Also known as: audit trail.

See also: [key event log](#key-event-log).

# auditor (of an entity)<a id="auditor-of-an-entity"></a>

The [party](#party) responsible for performing an [audit](#audit-of-system-controls). Typically an auditor must be [accredited](#accreditation-of-an-entity).

See also: [human auditable](#human-auditable).

# assurance level<a id="assurance-level"></a>

A level of confidence in a [claim](#claim) that may be relied on by others. Different types of assurance levels are defined for different types of trust assurance mechanisms. Examples include [authenticator assurance level](#authenticator-assurance-level), [federation assurance level](federation-assurance-level), and [identity assurance level](identity-assurance-level).

# authentication (of a user, process, or device)<a id="authentication-of-a-user-process-or-device"></a>

Verifying the [identity](#identity) of a user, process, or device, often as a prerequisite to allowing access to resources in an information system.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/authentication).

See also: [authenticator](#authenticator-of-an-entity), [verifiable message](#verifiable-message).

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Authentication): The act of proving an [assertion](https://en.wikipedia.org/wiki/Logical_assertion), such as the [identity](https://en.wikipedia.org/wiki/Digital_identity) of a computer system user.

# [[def: authenticator]]

Something the claimant possesses and controls (typically a cryptographic module or password) that is used to [[ref: authenticate]] the claimant’s [[ref: identity]].

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/authenticator).

# [[def: authenticator assurance level, AAL]]
~ A measure of the strength of an [authentication](#authentication-of-a-user-process-or-device) mechanism and, therefore, the confidence in it. 

Also known as: [[ref: AAL]]

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/authenticator_assurance_level).

See also: [federation assurance level](#federation-assurance-level), [identity assurance level](#identity-assurance-level), [identity binding](#identity-binding).

Note: In [NIST SP 800-63-3](https://pages.nist.gov/800-63-3/sp800-63-3.html), AAL is defined in terms of three levels: AAL1 (Some confidence), AAL2 (High confidence), AAL3 (Very high confidence).

# Authentic Chained Data Container<a id="authentic-chained-data-container"></a>

A digital [data](#data) structure designed for both cryptographic [verification](#verification) and [chaining](#chaining) of data containers. ACDC may be used for [digital credentials](#digital-credential).

For more information, see: [ToIP ACDC Task Force](https://wiki.trustoverip.org/display/HOME/ACDC+%28Authentic+Chained+Data+Container%29+Task+Force).

# authenticity<a id="authenticity"></a>

The [property](#property) of being genuine and being able to be [verified](#verifiable) and trusted; confidence in the [validity](#validation) of a transmission, a [message](#message), or message originator.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/authenticity).

See also: [confidentiality](#confidentiality), [correlation privacy](#correlation-privacy), [cryptographic verifiability](#cryptographic-verifiability).


# authorization<a id="authorization"></a>

The process of [verifying](#verifier-of-a-claim-or-credential) that a requested [action](#action) or service is approved for a specific [entity](#entity).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/authorization).

See also: [permission](#permission).

authorized organizational representative

A [person](#natural-person) who has the authority to make [claims](#claim), sign documents or otherwise commit resources on behalf of an [organization](#organization).

Source: [Law Insider](https://www.lawinsider.com/dictionary/authorized-organizational-representative#:~:text=Authorized%20Organizational%20Representative%20means%20the,the%20resources%20of%20the%20organization.)

# authorization graph<a id="authorization-graph"></a>

A graph of the [authorization](#authorization) relationships between different entities in a [trust-community](#trust-community). In a [digital trust ecosystem](#digital-trust-ecosystem), the [governing body](#governing-body) is typically the [trust root](#trust-root) of an authorization graph. In some cases, an authorization graph can be traversed by making queries to one or more [trust registries](#trust-registries).

See also: [governance graph](#governance-graph), [reputation graph](#reputation-graph), [trust graph](#trust-graph).

# authoritative source<a id="authoritative-source"></a>

A source of information that a [relying party](#relying-party) considers to be [authoritative](#authority) for that information. In ToIP architecture, the [trust registry](#trust-registry) authorized by the [governance framework (#governance-framework) for a [trust community](#trust-community) is typically considered an authoritative source by the members of that [trust community](#trust-community). A [system of record](#system-of-record) is an authoritative source for the data records it holds. A [trust root](#trust-root) is an authoritative source for the beginning of a [trust chain](#trust-chain).

# authority<a id="authority"></a>

A [party](#party) of which certain decisions, ideas, [rules](#rule) etc. are followed by other [parties](https://essif-lab.github.io/framework/docs/terms/party).

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/terms/authority).

# autonomic identifier<a id="autonomic-identifier"></a>

The specific type of [self-certifying identifier](self-certifying-identifier) specified by the [KERI](#KERI) specifications.

Also known as: [AID](#AID).

# biometric<a id="biometric"></a>

A measurable physical characteristic or personal behavioral trait used to recognize the [AID](#AID), or verify the [claimed](#claim) [identity](#identity), of an applicant. Facial images, fingerprints, and iris scan samples are all examples of biometrics.

Source: [NIST](https://csrc.nist.gov/glossary/term/biometric)

# blockchain<a id="blockchain"></a>

A [distributed digital ledger](#distributed-ledger) of cryptographically-signed transactions that are grouped into blocks. Each block is cryptographically linked to the previous one (making it tamper evident) after [validation](#validation) and undergoing a consensus decision. As new blocks are added, older blocks become more difficult to modify (creating [tamper resistance](#tamper-resistant)). New blocks are replicated across copies of the ledger within the network, and any conflicts are resolved automatically using established rules.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/blockchain)

Supporting definitions:

[Wikipedia:](https://en.wikipedia.org/wiki/Blockchain) A [distributed ledger](https://en.wikipedia.org/wiki/Distributed_ledger) with growing lists of [records](https://en.wikipedia.org/wiki/Record_\(computer_science\)) (blocks) that are securely linked together via [cryptographic hashes](https://en.wikipedia.org/wiki/Cryptographic_hash_function). Each block contains a cryptographic hash of the previous block, a [timestamp](https://en.wikipedia.org/wiki/Trusted_timestamping), and transaction data (generally represented as a [Merkle tree](https://en.wikipedia.org/wiki/Merkle_tree), where [data nodes](https://en.wikipedia.org/wiki/Node_\(computer_science\)) are represented by leaves). Since each block contains information about the previous block, they effectively form a chain (compare [linked list](https://en.wikipedia.org/wiki/Linked_list) data structure), with each additional block linking to the ones before it. Consequently, blockchain transactions are irreversible in that, once they are recorded, the data in any given block cannot be altered retroactively without altering all subsequent blocks.

# broadcast<a id="broadcast"></a>

In computer networking, telecommunication and information theory, broadcasting is a method of transferring a [message](#message) to all recipients simultaneously. Broadcast delivers a message to all [nodes](#node) in the network using a one-to-all association; a single [datagram](#datagram) (or [packet](#data-packet)) from one sender is routed to all of the possibly multiple endpoints associated with the [broadcast address](#broadcast-address). The network automatically replicates [datagrams](#datagram) as needed to reach all the recipients within the scope of the broadcast, which is generally an entire network subnet.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Broadcasting_\(networking\)).

See also: [anycast](#anycast), [multicast](#multicast), [unicast](#unicast).

Supporting definitions:

[NIST-CSRC](https://csrc.nist.gov/glossary/term/broadcast): Transmission to all devices in a network without any acknowledgment by the receivers.

# broadcast address<a id="broadcast-address"></a>

A broadcast address is a [network address](#network-address) used to transmit to all devices connected to a multiple-access [communications](#communication) network. A [message](#message) sent to a broadcast address may be received by all network-attached [hosts](#host). In contrast, a [multicast address](#multicast-address) is used to address a specific group of devices, and a [unicast address](#unicast-address) is used to address a single device. For network layer communications, a broadcast address may be a specific [IP address](#IP-address).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Network_address).

# C2PA<a id="c2pa"></a>

See: [Coalition for Content Provenance and Authenticity](#coalition-for-content-provenance-and-authenticity).


# CA<a id="ca"></a>

See: [certificate authority](#certificate-authority).


# CAI<a id="cai"></a>

See: [Content Authenticity Initiative](#content-authenticity-initiative).


# certification authority<a id="certification-authority"></a>

See: [certificate authority](#certificate-authority).


# certificate authority<a id="certificate-authority"></a>

The entity in a [public key infrastructure](#public-key-infrastructure) (PKI) that is responsible for issuing [public key certificates](#public-key-certificate) and exacting compliance to a PKI policy.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/certificate_authority).

Also known as: [certification authority](#certification-authority).

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Certificate_authority): In [cryptography](https://en.wikipedia.org/wiki/Cryptography), a certificate authority or certification authority (CA) is an entity that stores, signs, and issues [digital certificates](https://en.wikipedia.org/wiki/Public_key_certificate). A digital certificate certifies the ownership of a public key by the named subject of the certificate. This allows others (relying parties) to rely upon signatures or on assertions made about the private key that corresponds to the certified public key. A CA acts as a trusted third party—trusted both by the subject (owner) of the certificate and by the party relying upon the certificate.[<sup>\[1\]</sup>](https://en.wikipedia.org/wiki/Certificate_authority#cite_note-1) The format of these certificates is specified by the [X.509](https://en.wikipedia.org/wiki/X.509) or [EMV](https://en.wikipedia.org/wiki/EMV) standard.


# certification (of a party)<a id="certification-of-a-party"></a>

A comprehensive assessment of the management, operational, and technical security controls in an information system, made in support of security [accreditation](#accreditation-of-an-entity), to determine the extent to which the controls are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting the security [requirements](#requirement) for the system.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/certification).


# certification body<a id="certification-body"></a>

A [legal entity](#legal-entity) that performs [certification](#certification-of-a-party).

For more information: <https://en.wikipedia.org/wiki/Professional_certification> 


# chain of trust<a id="chain-of-trust"></a>

See: [trust chain](#trust-chain).


# chained credentials<a id="chained-credentials"></a>

Two or more [credentials](#credential) linked together to create a [trust chain](#trust-chain) between the credentials that is [cryptographically verifiable](#cryptographically-verifiable). 

Note: [ACDCs](#ACDC) are a type of [digital credential](#digital-credential) that explicitly supports [chaining](#chaining).


# chaining<a id="chaining"></a>

See: [trust chain](#trust-chain).


# channel<a id="channel"></a>

See: [communication channel](#communication-channel).


# ciphertext<a id="ciphertext"></a>

[Encrypted](#encryption) (enciphered) [data](#data). The [confidential](#confidentiality) form of the [plaintext](#plaintext) that is the output of the [encryption](#encryption) function.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/ciphertext).


# claim<a id="claim"></a>

An assertion about a [subject](#subject), typically expressed as an [attribute](#attribute) or [property](#property) of the [subject](#subject). It is called a “claim” because the assertion is always made by some [party](#party), called the [issuer](#issuer-of-a-claim-or-credential) of the claim, and the [validity](#validation) of the claim must be judged by the [verifier](#verifier-of-a-claim-or-credential). 

Supporting definitions:

[W3C VC](https://www.w3.org/TR/vc-data-model/#terminology): An assertion made about a [subject](https://www.w3.org/TR/vc-data-model/#dfn-subjects).

[Wikipedia](https://en.wikipedia.org/wiki/Claims-based_identity): A claim is a statement that one subject, such as a person or organization, makes about itself or another subject. For example, the statement can be about a name, group, buying preference, ethnicity, privilege, association or capability.

Note: If the [issuer](#issuer-of-a-claim-or-credential) of the claim is also the [subject](#subject) of the claim, the claim is [self-asserted](#self-asserted).


# Coalition for Content Provenance and Authenticity<a id="coalition-for-content-provenance-and-authenticity"></a>

C2PA is a Joint Development Foundation project of the Linux Foundation that addresses the prevalence of misleading information online through the development of technical standards for certifying the source and history (or provenance) of media content.

Also known as: [C2PA](#c2pa).

See also: [Content Authenticity Initiative](#content-authenticity-initiative).


# communication<a id="communication"></a>

The transmission of information.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Communication).

See also: [ToIP communication](#toip-communication).


# communication endpoint<a id="communication-endpoint"></a>

A type of communication network node. It is an interface exposed by a communicating party or by a [communication channel](#communication-channel). An example of the latter type of a communication endpoint is a publish-subscribe topic or a group in group communication systems.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Communication_endpoint).

See also: [ToIP endpoint](#ToIP-endpoint).

# communication channel<a id="communication-channel"></a>

A communication channel refers either to a physical transmission medium such as a wire, or to a logical [connection](#connection) over a multiplexed medium such as a radio channel in telecommunications and computer networking. A channel is used for information transfer of, for example, a digital bit stream, from one or several senders to one or several receivers.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Communication_channel).

See also: [ToIP channel](#toip-channel).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/terms/communication-channel): a (digital or non-digital) means by which two [actors](https://essif-lab.github.io/framework/docs/terms/actor) can exchange messages with one another.

# communication metadata<a id="communication-metadata"></a>

[Metadata](#metadata) that describes the sender, receiver, [routing](#routing), handling, or contents of a [communication](#communication). Communication metadata is often observable even if the contents of the [communication](#communication) are encrypted.

See also: [correlation privacy](#correlation-privacy).


# communication session<a id="communication-session"></a>

A finite period for which a [communication channel](#communication-channel) is instantiated and maintained, during which certain [properties](#property) of that channel, such as authentication of the participants, are in effect. A session has a beginning, called the session initiation, and an ending, called the session termination.

Supporting definitions:

[NIST-CSRC](https://csrc.nist.gov/glossary/term/session): A persistent interaction between a subscriber and an end point, either a relying party or a Credential Service Provider. A session begins with an authentication event and ends with a session termination event. A session is bound by use of a session secret that the subscriber’s software (a browser, application, or operating system) can present to the relying party or the Credential Service Provider in lieu of the subscriber’s authentication credentials.

[Wikipedia](https://en.wikipedia.org/wiki/Session_\(computer_science\)): In [computer science](https://en.wikipedia.org/wiki/Computer_science) and [networking](https://en.wikipedia.org/wiki/Computer_network) in particular, a session is a time-delimited two-way link, a practical (relatively high) layer in the [TCP/IP protocol](https://en.wikipedia.org/wiki/Internet_protocol_suite) enabling interactive expression and information exchange between two or more communication devices or ends – be they computers, [automated systems](https://en.wikipedia.org/wiki/Automation), or live active users (see [login session](https://en.wikipedia.org/wiki/Login_session)). A session is established at a certain point in time, and then ‘torn down’ - brought to an end - at some later point. An established communication session may involve more than one message in each direction. A session is typically [stateful](https://en.wikipedia.org/wiki/Stateful), meaning that at least one of the communicating parties needs to hold current state information and save information about the session history to be able to communicate, as opposed to [stateless](https://en.wikipedia.org/wiki/Stateless_server) communication, where the communication consists of independent [requests](https://en.wikipedia.org/wiki/Request-response) with responses. An established session is the basic requirement to perform a [connection-oriented communication](https://en.wikipedia.org/wiki/Connection-oriented_communication). A session also is the basic step to transmit in [connectionless communication](https://en.wikipedia.org/wiki/Connectionless_communication) modes. However, any unidirectional transmission does not define a session.


# complex password<a id="complex-password"></a>

A [password](#password) that meets certain security requirements, such as minimum length, inclusion of different character types, non-repetition of characters, and so on.

Supporting definitions:

[Science Direct](https://www.sciencedirect.com/topics/computer-science/complex-password): According to Microsoft, complex passwords consist of at least seven characters, including three of the following four character types: uppercase letters, lowercase letters, numeric digits, and non-alphanumeric characters such as & $ \* and !


# compliance<a id="compliance"></a>

In the context of decentralized digital trust infrastructure, the extent to which a system, [actor](#actor), or [party](#party) conforms to the requirements of a [governance framework](#governance-framework) or [trust framework](#trust-framework) that pertains to that particular [entity](#entity).

See also: [Governance, Risk Management, and Compliance](#governance-risk-management-and-compliance).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#compliance): The state of realization of a set of conformance criteria or normative framework of a [party](https://essif-lab.github.io/framework/docs/terms/party).


# concept<a id="concept"></a>

An abstract idea that enables the classification of [entities](#entity), i.e., a mental construct that enables an instance of a class of [entities](#entity) to be distinguished from [entities](#entity) that are not an instance of that class. A concept can be [identified](#identifier) with a [term](#term).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#concept): the ideas/thoughts behind a classification of [entities](https://essif-lab.github.io/framework/docs/terms/entity) (what makes [entities](https://essif-lab.github.io/framework/docs/terms/entity) in that class 'the same').

[Wikipedia](https://en.wikipedia.org/wiki/Concept): A concept is defined as an [abstract](https://en.wikipedia.org/wiki/Abstraction) [idea](https://en.wikipedia.org/wiki/Idea). It is understood to be a fundamental building block underlying principles, [thoughts](https://en.wikipedia.org/wiki/Thought) and [beliefs](https://en.wikipedia.org/wiki/Belief). Concepts play an important role in all aspects of [cognition](https://en.wikipedia.org/wiki/Cognition).


# confidential computing<a id="confidential-computing"></a>

Hardware-enabled features that isolate and process [encrypted](#encryption) [data](#data) in memory so that the [data](#data) is at less risk of exposure and compromise from concurrent workloads or the underlying system and platform.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/confidential_computing).

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Confidential_computing): Confidential computing is a security and [privacy-enhancing computational technique](https://en.wikipedia.org/wiki/Privacy-enhancing_technologies) focused on protecting [data in use](https://en.wikipedia.org/wiki/Data_in_use). Confidential computing can be used in conjunction with storage and network encryption, which protect [data at rest](https://en.wikipedia.org/wiki/Data_at_rest) and [data in transit](https://en.wikipedia.org/wiki/Data_in_transit) respectively. It is designed to address software, protocol, cryptographic, and basic physical and supply-chain attacks, although some critics have demonstrated architectural and [side-channel attacks](https://en.wikipedia.org/wiki/Side-channel_attack) effective against the technology.


# confidentiality<a id="confidentiality"></a>

In a [communications](#communication) context, a type of privacy protection in which [messages](#message) use [encryption](#encryption) or other privacy-preserving technologies so that only [authorized](#authorization) [parties](#party) have access.

See also: [authenticity](#authenticity), [correlation privacy](#correlation-privacy).

Supporting definitions:

[NIST-CSRC](https://csrc.nist.gov/glossary/term/confidentiality): Preserving authorized restrictions on information access and disclosure, including means for protecting personal privacy and proprietary information.

[Wikipedia](https://en.wikipedia.org/wiki/Confidentiality): Confidentiality involves a set of rules or a promise usually executed through [confidentiality agreements](https://en.wikipedia.org/wiki/Confidentiality_agreements) that limits the access or places restrictions on certain types of [information](https://en.wikipedia.org/wiki/Information).


# connection<a id="connection"></a>

A [communication channel](#communication-channel) established between two [communication endpoints](#communication-endpoint). A connection may be [ephemeral](#ephemeral-connection) or [persistent](#persistent-connection).

See also: [ToIP connection](#toip-connection).


# Content Authenticity Initiative<a id="content-authenticity-initiative"></a>

The Content Authenticity Initiative (CAI) is an association founded in November 2019 by Adobe, the New York Times and [Tw](https://en.wikipedia.org/wiki/Twitter)i[tter](https://en.wikipedia.org/wiki/Twitter). The CAI promotes an industry standard for provenance [metadata](#metadata) defined by the [C2PA](#c2pa). The CAI cites curbing disinformation as one motivation for its activities.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Content_Authenticity_Initiative).

Also known as: [CAI](#cai).


# controller (of a key, vault, wallet, agent, or device)<a id="controller-of-a-key-vault-wallet-agent-or-device"></a>

In the context of digital [communications](#communication), the [entity](#entity) in control of sending and receiving digital [communications](#communication). In the context of decentralized digital trust infrastructure, the [entity](#entity) in control of the [cryptographic keys](#cryptographic-key) necessary to perform [cryptographically verifiable](#cryptographically-verifiable) [actions](#action) using a [digital agent](#digital-agent) and [digital wallet](#digital-wallet). In a ToIP context, the [entity](#entity) in control of a [ToIP endpoint](#ToIP-endpoint).

See also: [device controller](#device-controller), [DID controller](#did-controller), [ToIP controller](#toip-controller).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#controller): the role that an [actor](https://essif-lab.github.io/framework/docs/terms/actor) performs as it is executing actions on that [entity](https://essif-lab.github.io/framework/docs/terms/entity) for the purpose of ensuring that the [entity](https://essif-lab.github.io/framework/docs/terms/entity) will act/behave, or be used, in a particular way.


# consent management<a id="consent-management"></a>

A system, process or set of policies under which a [person](#natural-person) agrees to share [personal data](#personal-data) for specific usages. A consent management system will typically create a [record](#record) of such consent.

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Consent_management): Consent management is a system, process or set of policies for allowing consumers and patients to determine what health information they are willing to permit their various care providers to access. It enables patients and consumers to affirm their participation in e-health initiatives and to establish consent directives to determine who will have access to their protected health information (PHI), for what purpose and under what circumstances. Consent management supports the dynamic creation, management and enforcement of consumer, organizational and jurisdictional privacy policies.


# controlled document<a id="controlled-document"></a>

A [governance document](#governance-document) whose authority is derived from a primary document.


# correlation privacy<a id="correlation-privacy"></a>

In a [communications](#communication) context, a type of privacy protection in which [messages](#message) use [encryption](#encryption), [hashes](#hash), or other privacy-preserving technologies to avoid the use of [identifiers](#identifier) or other content that [unauthorized](#authorization) [parties](#party) may use to correlate the sender and/or receiver(s).

See also: [authenticity](#authenticity), [confidentiality](#confidentiality).


# counterparty<a id="counterparty"></a>

From the perspective of one [party](#party), the other [party](#party) in a [transaction](#transaction), such as a financial transaction.

See also: [first party](#first-party), [second party](#second-party), [third party](#third-party).

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Counterparty): A counterparty (sometimes contraparty) is a [legal entity](https://en.wikipedia.org/wiki/Juristic_person), [unincorporated entity](https://en.wikipedia.org/wiki/Unincorporated_entity), or collection of entities to which an exposure of [financial risk](https://en.wikipedia.org/wiki/Financial_risk) may exist.


# credential<a id="credential"></a>

A container of [claims](#claim) describing one or more [subjects](#subject). A credential is generated by the [issuer](#issuer-of-a-claim-or-credential) of the credential and given to the [holder](#holder-of-a-claim-or-credential) of the credential. A credential typically includes a signature or some other means of proving its [authenticity](#authenticity). A credential may be either a [physical credential](#physical-credential) or a [digital credential](#digital-credential).

See also: [verifiable credential](#verifiable-credential).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/terms/credential): data, representing a set of [assertions](https://essif-lab.github.io/framework/docs/terms/assertion) (claims, statements), authored and signed by, or on behalf of, a specific [party](https://essif-lab.github.io/framework/docs/terms/party).

[W3C VC](https://www.w3.org/TR/vc-data-model/#terminology): A set of one or more [claims](https://www.w3.org/TR/vc-data-model/#dfn-claims) made by an [issuer](https://www.w3.org/TR/vc-data-model/#dfn-issuers).


# credential family<a id="credential-family"></a>

A set of related [digital credentials](#digital-credential) defined by a [governing body](#governing-body) (typically in a [governance framework](#governance-framework)) to empower [transitive trust decisions](#transitive-trust-decision) among the participants in a [digital trust ecosystem](#digital-trust-ecosystem).


# credential governance framework<a id="credential-governance-framework"></a>

A [governance framework](#governance-framework) for a [credential family](#credential-family). A credential governance framework may be included within or referenced by an [ecosystem governance framework](#ecosystem-governance-framework).


# credential offer<a id="credential-offer"></a>

A protocol request invoked by an [issuer](#issuer-of-a-claim-or-credential) to offer to [issue](#issuance) a [digital credential](#digital-credential) to the  [holder](#holder-of-a-claim-or-credential) of a [digital wallet](#digital-wallet). If the request is invoked by the [holder](#holder-of-a-claim-or-credential), it is called an [issuance request](#issuance-request).


# credential request<a id="credential-request"></a>

See: [issuance request](#issuance-request).


# credential schema<a id="credential-schema"></a>

A [data schema](#data-schema) describing the structure of a [digital credential](#digital-credential). The [W3C Verifiable Credentials Data Model Specification](#w3c-verifiable-credentials-data-model-specification) defines a set of requirements for credential schemas.


# criterion<a id="criterion"></a>

In the context of [terminology](#terminology), a written description of a [concept](#concept) that anyone can evaluate to determine whether or not an [entity](#entity) is an instance or example of that [concept](#concept). Evaluation leads to a yes/no result.


# cryptographic binding<a id="cryptographic-binding"></a>

Associating two or more related elements of information using cryptographic techniques.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/cryptographic_binding).


# cryptographic key<a id="cryptographic-key"></a>

A key in cryptography is a piece of information, usually a string of numbers or letters that are stored in a file, which, when processed through a cryptographic algorithm, can encode or decode cryptographic [data](#data). Symmetric cryptography refers to the practice of the same [key](#cryptographic-key) being used for both [encryption](#encryption) and [decryption](#decryption). Asymmetric cryptography has separate [keys](#cryptographic-key) for [encrypting](#encryption) and [decrypting](#decryption). These keys are known as the [public keys](#public-key) and [private keys](#private-key), respectively.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Key_\(cryptography\)).

See also: [controller](#controller-of-a-key-vault-wallet-agent-or-device).


# cryptographic trust<a id="cryptographic-trust"></a>

A specialized type of [technical trust](#technical-trust) that is achieved using cryptographic algorithms.

Contrast with: [human trust](#human-trust).


# cryptographic verifiability<a id="cryptographic-verifiability"></a>

The [property](#property) of being [cryptographically verifiable](#cryptographically-verifiable).

Contrast with: [human auditability](#human-auditability).


# cryptographically verifiable<a id="cryptographically-verifiable"></a>

A property of a data structure that has been digitally signed using a [private key](#private-key) such that the [digital signature](#digital-signature) can be verified using the [public key](#public-key). [Verifiable data](#verifiable-data), [verifiable messages](#verifiable-message), [verifiable credentials](#verifiable-credential), and [verifiable data registries](#verifiable-data-registry) are all cryptographically verifiable. Cryptographic verifiability is a primary goal of the [ToIP Technology Stack](#toip-technology-stack).

Contrast with: [human auditable](#human-auditable).


# cryptographically bound<a id="cryptographically-bound"></a>

A state in which two or more elements of information have a [cryptographic binding](#cryptographic-binding).


# custodial wallet<a id="custodial-wallet"></a>

A [digital wallet](#digital-wallet) that is directly in the custody of a [principal](#principal), i.e., under the principal’s direct personal or organizational control. A [digital wallet](#digital-wallet) that is in the custody of a [third party](#third-party) is called a [non-custodial wallet](#non-custodial-wallet).


# custodian<a id="custodian"></a>

A [third party](#third-party) that has been assigned rights and duties in a [custodianship arrangement](#custodianship-arrangement) for the purpose of hosting and safeguarding a [principal’s](#principal) [private keys](#private-key), [digital wallet](#digital-wallet) and [digital assets](#digital-asset) on the [principal’s](#principal) behalf. Depending on the [custodianship arrangement](#custodianship-arrangement), the custodian may act as an exchange and provide additional services, such as staking, lending, account recovery, or security features.

Contrast with: [guardian](#guardian), [zero-knowledge service provider](#zero-knowledge-service-provider).

See also: [custodial wallet](#custodial-wallet).

Supporting definitions:

[NIST-CSRC](https://csrc.nist.gov/glossary/term/custodian): A third-party [entity](#entity) that holds and safeguards a user’s [private keys](#private-key) or digital assets on their behalf. Depending on the system, a custodian may act as an exchange and provide additional services, such as staking, lending, account recovery, or security features.

Note: While a custodian technically has the necessary access to in theory [impersonate](#impersonation) the [principal](#principal), in most cases a custodian is expressly prohibited from taking any action on the [principal’s](#principal) account unless explicitly [authorized](#authorization) by the [principal](#principal). This is what distinguishes custodianship from [guardianship](#guardian).


# custodianship arrangement<a id="custodianship-arrangement"></a>

The informal terms or formal legal agreement under which a [custodian](#custodian) agrees to provide service to a [principal](#principal).


# dark pattern<a id="dark-pattern"></a>

A design pattern, mainly in user interfaces, that has the effect of deceiving individuals into making choices that are advantageous to the designer.

Source: Kantara PEMC Implementors Guidance Report

Also known as: [deceptive pattern](#deceptive-pattern).


# data<a id="data"></a>

In the pursuit of [knowledge](#knowledge), data is a collection of discrete values that convey information, describing quantity, quality, fact, statistics, other basic units of meaning, or simply sequences of symbols that may be further interpreted. A datum is an individual value in a collection of data.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Data).

See also: [verifiable data](#verifiable-data).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#data): something (tangible) that can be used to communicate a meaning (which is intangible/information).


# datagram<a id="datagram"></a>

See: [data packet](#data-packet).


# data packet<a id="data-packet"></a>

In telecommunications and computer networking, a network packet is a formatted unit of [data](#data) carried by a packet-switched network such as the Internet. A packet consists of control information and user [data](#data); the latter is also known as the payload. Control information provides data for delivering the payload (e.g., source and destination network addresses, error detection codes, or sequencing information). Typically, control information is found in packet headers and trailers.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Network_packet).


# data schema<a id="data-schema"></a>

A description of the structure of a digital document or object, typically expressed in a [machine-readable](#machine-readable) language in terms of constraints on the structure and content of documents or objects of that type. A credential schema is a particular type of data schema.

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/XML_schema): An XML schema is a description of a type of [XML](https://en.wikipedia.org/wiki/Extensible_Markup_Language) document, typically expressed in terms of constraints on the structure and content of documents of that type, above and beyond the basic syntactical constraints imposed by XML itself. These constraints are generally expressed using some combination of grammatical rules governing the order of elements, [Boolean predicates](https://en.wikipedia.org/wiki/Boolean_predicates) that the content must satisfy, data types governing the content of elements and attributes, and more specialized rules such as [uniqueness](https://en.wikipedia.org/wiki/Uniqueness_quantification) and [referential integrity](https://en.wikipedia.org/wiki/Referential_integrity) constraints.


# data subject<a id="data-subject"></a>

The [natural person](#natural-person) that is described by [personal data](#personal-data). Data subject is the term used by the EU [General Data Protection Regulation](#general-data-protection-regulation).


# data vault<a id="data-vault"></a>

See: [digital vault](#digital-vault).


# decentralized identifier<a id="decentralized-identifier"></a>

A globally unique persistent [identifier](#identifier) that does not require a centralized [registration](#registration) [authority](#authority) and is often generated and/or registered cryptographically. The generic format of a DID is defined in section [3.1 DID Syntax](https://www.w3.org/TR/did-core/#did-syntax) of the [W3C Decentralized Identifiers (DIDs) 1.0](https://www.w3.org/TR/did-core/) specification. A specific DID scheme is defined in a [DID method](#did-method) specification.

Source: [W3C DID](https://www.w3.org/TR/did-core/#terminology).

Also known as: [DID](#did).

See also: [DID method](#did-method), [DID URL](#did-url).


# decentralized identity<a id="decentralized-identity"></a>

A [digital identity](#digital-identity) architecture in which a [digital identity](#digital-identity) is established via the control of a set of [cryptographic keys](#cryptographic-key) in a [digital wallet](#digital-wallet) so that the [controller](#controller-of-a-key-vault-wallet-agent-or-device) is not dependent on any external [identity provider](#identity-provider) or other [third party](#third-party).

See also: [federated identity](#federated-identity), [self-sovereign identity](#self-sovereign-identity).


# Decentralized Identity Foundation<a id="decentralized-identity-foundation"></a>

A non-profit project of the [Linux Foundation](https://www.linuxfoundation.org/) chartered to develop the foundational components of an open, standards-based, [decentralized identity](#decentralized-identity) [ecosystem](#digital-ecosystem) for people, [organizations](#organization), apps, and devices.

See also: [OpenWallet Foundation](#openwallet-foundation), [ToIP Foundation](#toip-foundation).

For more information, see: <http://identity.foundation/> 


# Decentralized Web Node<a id="decentralized-web-node"></a>

A decentralized personal and application data storage and message relay node, as defined in the DIF Decentralized Web Node specification. Users may have multiple nodes that replicate their data between them.

Source: [DIF DWN Specification](https://identity.foundation/decentralized-web-node/spec/).

Also known as: DWN.

For more information, see: <https://identity.foundation/decentralized-web-node/spec/> 


# deceptive pattern<a id="deceptive-pattern"></a>

See: [dark pattern](#dark-pattern).


# decryption<a id="decryption"></a>

The process of changing [ciphertext](#ciphertext) into [plaintext](#plaintext) using a cryptographic algorithm and [key](#cryptographic-key). The opposite of [encryption](#encryption).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/decryption).


# deep link<a id="deep-link"></a>

In the context of the World Wide Web, deep linking is the use of a hyperlink that links to a specific, generally searchable or indexed, piece of web content on a website (e.g. "https\://example.com/path/page"), rather than the website's home page (e.g., "https\://example.com"). The URL contains all the information needed to point to a particular item. Deep linking is different from [mobile deep linking](#mobile-deep-link), which refers to directly linking to in-app content using a non-HTTP URI.

See also: [out-of-band introduction](#out-of-band-introduction).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Deep_linking).


# definition<a id="definition"></a>

A textual statement defining the meaning of a [term](#term) by specifying [criterion](#criterion) that enable the [concept](#concept) identified by the [term](#term) to be distinguished from all other [concepts](#concept) within the intended [scope](#scope).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#definition): a text that helps [parties](https://essif-lab.github.io/framework/docs/@) to have the same understanding about the meaning of (and [concept](https://essif-lab.github.io/framework/docs/@) behind) a [term](https://essif-lab.github.io/framework/docs/@), ideally in such a way that these [parties](https://essif-lab.github.io/framework/docs/@) can determine whether or not they make the same distinction.

Wikipedia: A definition is a statement of the meaning of a term (a [word](https://en.wikipedia.org/wiki/Word), [phrase](https://en.wikipedia.org/wiki/Phrase), or other set of [symbols](https://en.wikipedia.org/wiki/Symbol)). Definitions can be classified into two large categories: [intensional definitions](https://en.wikipedia.org/wiki/Intensional_definition) (which try to give the sense of a term), and [extensional definitions](https://en.wikipedia.org/wiki/Extensional_definition) (which try to list the objects that a term describes). Another important category of definitions is the class of [ostensive definitions](https://en.wikipedia.org/wiki/Ostensive_definition), which convey the meaning of a term by pointing out examples. A term may have many different senses and multiple meanings, and thus require multiple definitions.


# delegation<a id="delegation"></a>

TODO


# delegation credential<a id="delegation-credential"></a>

TODO


# dependent<a id="dependent"></a>

An [entity](#entity) for the caring for and/or protecting/guarding/defending of which a [guardianship arrangement](#guardianship-arrangement) has been established with a [guardian](#guardian).

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#dependent)

See also: [custodian](#custodian).

Mental Model: [eSSIF-Lab Guardianship](https://essif-lab.github.io/framework/docs/terms/pattern-guardianship)


# device controller<a id="device-controller"></a>

The [controller](#controller-of-a-key-vault-wallet-agent-or-device) of a device capable of digital [communications](#communication), e.g., a smartphone, tablet, laptop, IoT device, etc.


# dictionary<a id="dictionary"></a>

A dictionary is a listing of lexemes (words or [terms](#term)) from the lexicon of one or more specific languages, often arranged alphabetically, which may include information on [definitions](#definition), usage, etymologies, pronunciations, translation, etc. It is a lexicographical reference that shows inter-relationships among the [data](#data). Unlike a [glossary](#glossary), a dictionary may provide multiple [definitions](#definition) of a [term](#term) depending on its [scope](#scope) or context.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Dictionary).


# DID<a id="did"></a>

See: [decentralized identifier](#decentralized-identifier).


# DID controller<a id="did-controller"></a>

An [entity](#entity) that has the capability to make changes to a [DID document](#did-document). A [DID](#did) might have more than one DID controller. The DID controller(s) can be denoted by the optional `controller` property at the top level of the [DID document](#did-document). Note that a DID controller might be the [DID subject](#did-subject).

Source: [W3C DID](https://www.w3.org/TR/did-core/#terminology).

See also: [controller](#controller-of-a-key-vault-wallet-agent-or-device).


# DID document<a id="did-document"></a>

A set of data describing the [DID subject](#did-subject), including mechanisms, such as cryptographic public keys, that the [DID subject](#did-subject) or a DID delegate can use to [authenticate](#authentication-of-a-user-process-or-device) itself and prove its association with the [DID](#did). A DID document might have one or more different representations as defined in section 6 of the [W3C Decentralized Identifiers (DIDs) 1.0](https://www.w3.org/TR/did-core/) specification.

Source: [W3C DID](https://www.w3.org/TR/did-core/#terminology).


# DID method<a id="did-method"></a>

A definition of how a specific DID method scheme is implemented. A DID method is defined by a DID method specification, which specifies the precise operations by which [DIDs](#did) and [DID documents](#did-document) are created, resolved, updated, and deactivated.

Source: [W3C DID](https://www.w3.org/TR/did-core/#dfn-did-methods).

For more information: <https://www.w3.org/TR/did-core/#methods> 


# DID subject<a id="did-subject"></a>

The [entity](#entity) identified by a [DID](#did) and described by a [DID document](#did-document). Anything can be a DID subject: person, group, organization, physical thing, digital thing, logical thing, etc.

Source: [W3C DID](https://www.w3.org/TR/did-core/#dfn-did-subjects).

See also: [subject](#subject).


# DID URL<a id="did-url"></a>

A [DID](#did) plus any additional syntactic component that conforms to the definition in section 3.2 of the [W3C Decentralized Identifiers (DIDs) 1.0](https://www.w3.org/TR/did-core/) specification. This includes an optional DID path (with its leading / character), optional DID query (with its leading ? character), and optional DID fragment (with its leading # character).

Source: [W3C DID](https://www.w3.org/TR/did-core/#dfn-did-urls).


# digital agent<a id="digital-agent"></a>

In the context of ​​decentralized digital trust infrastructure, an [agent](#agent) (specifically a type of [software agent](#software-agent)) that operates in conjunction with a [digital wallet](#digital-wallet).

Note: In a ToIP context, a digital agent is frequently assumed to have privileged access to the [digital wallet](#digital-wallet)(s) of its principal. In market parlance, a mobile app that performs the [actions](#action) of a digital agent is often simply called a [wallet](#wallet) or a [digital wallet](#digital-wallet).

# digital asset<a id="digital-asset"></a>

A digital asset is anything that exists only in digital form and comes with a distinct usage right. [Data](#data) that do not possess that right are not considered assets.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Digital_asset).

See also: [digital credential](#digital-credential).


# digital certificate<a id="digital-certificate"></a>

See: [public key certificate](#public-key-certificate).


# digital credential<a id="digital-credential"></a>

A [credential](#credential) in digital form that is signed with a [digital signature](#digital-signature) and held in a [digital wallet](#digital-wallet). A digital credential is issued to a [holder](#holder-of-a-claim-or-credential) by an [issuer](#issuer-of-a-claim-or-credential); a [proof](#proof) of the credential is [presented](#presentation) by the [holder](#holder-of-a-claim-or-credential) to a [verifier](#verifier-of-a-claim-or-credential).

See also: [issuance request](#issuance-request), [presentation request](#presentation-request), [verifiable credential](#verifiable-credential).

Contrast with: [physical credential](#physical-credential).

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Digital_credential): Digital credentials are the digital equivalent of paper-based [credentials](https://en.wikipedia.org/wiki/Credentials). Just as a paper-based credential could be a [passport](https://en.wikipedia.org/wiki/Passport), a [driver's license](https://en.wikipedia.org/wiki/Driver%27s_license), a membership certificate or some kind of ticket to obtain some service, such as a cinema ticket or a public transport ticket, a digital credential is a proof of qualification, competence, or clearance that is attached to a person.


# digital ecosystem<a id="digital-ecosystem"></a>

A digital ecosystem is a distributed, adaptive, open socio-technical system with properties of self-organization, scalability and sustainability inspired from natural ecosystems. Digital ecosystem models are informed by knowledge of natural ecosystems, especially for aspects related to competition and collaboration among diverse [entities](#entity).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Digital_ecosystem).

See also: [digital trust ecosystem](#digital-trust-ecosystem), [trust community](#trust-community).


# digital identity<a id="digital-identity"></a>

An [identity](#identity) expressed in a digital form for the purpose representing the identified [entity](#entity) within a computer system or digital network.

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary): [Digital data](https://essif-lab.github.io/framework/docs/essifLab-glossary#data) that enables a specific [entity](https://essif-lab.github.io/framework/docs/essifLab-glossary#entity) to be distinguished from all others in a specific context.

[Wikipedia](https://en.wikipedia.org/wiki/Digital_identity): Digital identity refers to the information utilized by [computer systems](https://en.wikipedia.org/wiki/Computer_systems) to represent external entities, including a person, organization, application, or device. When used to describe an individual, it encompasses a person's compiled information and plays a crucial role in automating access to computer-based services, verifying identity online, and enabling computers to mediate relationships between entities.


# digital rights management<a id="digital-rights-management"></a>

Digital rights management (DRM) is the management of legal access to digital content. Various tools or technological protection measures (TPM) like [access control](#access-control) technologies, can restrict the use of proprietary hardware and copyrighted works. DRM technologies govern the use, modification and distribution of copyrighted works (e.g. software, multimedia content) and of systems that enforce these policies within devices.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Digital_rights_management).

Also known as: [DRM](#drm).


# digital trust ecosystem<a id="digital-trust-ecosystem"></a>

A [digital ecosystem](#digital-ecosystem) in which the participants are one or more interoperating [trust communities](#trust-community). Governance of the various [roles](#role) of [governed parties](#governed-party) within a digital trust ecosystem (e.g., [issuers](#issuer-of-a-claim-or-credential), [holders](#holder-of-a-claim-or-credential), [verifiers](#verifier-of-a-claim-or-credential), [certification bodies](#certification-body), [auditors](#auditor-of-an-entity)) is typically managed by a [governing body](#governing-body) using a [governance framework](#governance-framework) as recommended in the [ToIP Governance Stack](#toip-governance-stack). Many digital trust ecosystems will also maintain one or more [trust lists](#trust-list) and/or [trust registries](#trust-registry).


# digital trust utility<a id="digital-trust-utility"></a>

An information system, network, distributed database, or [blockchain](#blockchain) designed to provide one or more supporting services to higher level components of decentralized digital trust infrastructure. In the [ToIP stack](#toip-stack), digital trust utilities are at [Layer 1](#layer-1). A [verifiable data registry](#verifiable-data-registry) is one type of digital trust utility.


# digital signature<a id="digital-signature"></a>

A digital signature is a mathematical scheme for verifying the authenticity of digital [messages](#message) or documents. A valid digital signature, where the prerequisites are satisfied, gives a recipient very high confidence that the [message](#message) was created by a known sender ([authenticity](https://en.wikipedia.org/wiki/Authentication)), and that the message was not altered in transit ([integrity](https://en.wikipedia.org/wiki/Data_integrity)).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Digital_signature).

Supporting definitions:

[NIST-CSRC](https://csrc.nist.gov/glossary/term/digital_signature): The result of a cryptographic transformation of data which, when properly implemented, provides the services of: 1. origin authentication, 2. data integrity, and 3. signer non-repudiation.


# digital vault<a id="digital-vault"></a>

A secure container for [data](#data) whose [controller](#controller-of-a-key-vault-wallet-agent-or-device) is the [principal](#principal). A digital vault is most commonly used in conjunction with a [digital wallet](#digital-wallet) and a [digital agent](#digital-agent). A digital vault may be implemented on a local device or in the cloud; multiple digital vaults may be used by the same [principal](#principal) across different devices and/or the cloud; if so they may use some type of synchronization. If the capability is supported, [data](#data) may flow into or out of the digital vault automatically based on [subscriptions](#subscription) approved by the [controller](#controller-of-a-key-vault-wallet-agent-or-device).

Also known as: [data vault](#data-vault), [encrypted data vault](#encrypted-data-vault).

See also: [enterprise data vault](#enterprise-data-vault), [personal data vault](#personal-data-vault), [virtual vault](#virtual-vault).

For more information, see: <https://en.wikipedia.org/wiki/Personal_data_service>, <https://digitalbazaar.github.io/encrypted-data-vaults/>


# digital wallet<a id="digital-wallet"></a>

A [user agent](#user-agent), optionally including a hardware component, capable of securely storing and processing [cryptographic keys](#cryptographic-key), [digital credentials](#digital-credential), [digital assets](#digital-asset) and other sensitive private [data](#data) that enables the [controller](#controller-of-a-key-vault-wallet-agent-or-device) to perform [cryptographically verifiable](#cryptographically-verifiable) operations. A [non-custodial wallet](#non-custodial-wallet) is directly in the custody of a [principal](#principal). A [custodial wallet](#custodial-wallet) is in the [custody](#custodian) of a [third party](#third-party). [Personal wallets](#personal-wallet) are held by individual persons; [enterprise wallets](#enterprise-wallet) are held by [organizations](#organization) or other [legal entities](#legal-entity).

See also: [digital agent](#digital-agent), [key management system](#key-management-system), [wallet engine](#wallet-engine).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#wallet): a component that implements the [capability](https://essif-lab.github.io/framework/docs/terms/capability) to securely store data as requested by [colleague agents](https://essif-lab.github.io/framework/docs/terms/colleague), and to provide stored data to [colleague agents](https://essif-lab.github.io/framework/docs/terms/colleague) or [peer agents](https://essif-lab.github.io/framework/docs/terms/peer-agent), all in [compliance](https://essif-lab.github.io/framework/docs/terms/compliance) with the rules of its [principal](https://essif-lab.github.io/framework/docs/terms/principal)'s [wallet policy](https://essif-lab.github.io/framework/docs/terms/wallet-policy). 

[Wikipedia](https://en.wikipedia.org/wiki/Digital_wallet): A digital wallet, also known as an e-wallet, is an [electronic device](https://en.wikipedia.org/wiki/Consumer_electronics), [online service](https://en.wikipedia.org/wiki/Online_service_provider), or [software program](https://en.wikipedia.org/wiki/Computer_program) that allows one party to make [electronic transactions](https://en.wikipedia.org/wiki/Electronic_transaction) with another party bartering [digital currency](https://en.wikipedia.org/wiki/Digital_currency) units for [goods and services](https://en.wikipedia.org/wiki/Goods_and_services). This can include purchasing items either [online](https://en.wikipedia.org/wiki/Online_and_offline) or at the [point of sale](https://en.wikipedia.org/wiki/Point_of_sale) in a [brick and mortar](https://en.wikipedia.org/wiki/Brick_and_mortar) store, using either [mobile payment](https://en.wikipedia.org/wiki/Mobile_payment) (on a [smartphone](https://en.wikipedia.org/wiki/Smartphone) or other [mobile device](https://en.wikipedia.org/wiki/Mobile_device)) or (for online buying only) using a [laptop](https://en.wikipedia.org/wiki/Laptop) or other [personal computer](https://en.wikipedia.org/wiki/Personal_computer). Money can be deposited in the digital wallet prior to any transactions or, in other cases, an individual's bank account can be linked to the digital wallet. Users might also have their [driver's license](https://en.wikipedia.org/wiki/Driver%27s_license), [health card](https://en.wikipedia.org/wiki/Health_Care_Card), loyalty card(s) and other ID documents stored within the wallet. The credentials can be passed to a merchant's terminal wirelessly via [near field communication](https://en.wikipedia.org/wiki/Near_field_communication) (NFC).

Note: In market parlance, a mobile app that performs the [actions](#action) of a [digital agent](#digital-agent) and has access to a set of [cryptographic keys](#cryptographic-key) is often simply called a [wallet](#wallet) or a digital wallet.


# distributed ledger<a id="distributed-ledger"></a>

A distributed ledger (also called a shared ledger or distributed ledger technology or DLT) is the consensus of replicated, shared, and synchronized digital [data](#data) that is geographically spread (distributed) across many sites, countries, or institutions. In contrast to a centralized database, a distributed ledger does not require a central administrator, and consequently does not have a single (central) point-of-failure. In general, a distributed ledger requires a [peer-to-peer](#peer-to-peer) (P2P) computer network and consensus algorithms so that the ledger is reliably replicated across distributed computer [nodes](#node) (servers, clients, etc.). The most common form of distributed ledger technology is the [blockchain](#blockchain), which can either be on a public or private network.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Distributed_ledger).


# domain<a id="domain"></a>

See: [security domain](#security-domain).

See also: [trust domain](#trust-domain).


# DRM<a id="drm"></a>

See: [digital rights management](#digital-rights-management).


# DWN<a id="dwn"></a>

See: [Decentralized Web Node](#decentralized-web-node).


# ecosystem<a id="ecosystem"></a>

See: [digital ecosystem](#digital-ecosystem).


# ecosystem governance framework<a id="ecosystem-governance-framework"></a>

A [governance framework](#governance-framework) for a [digital trust ecosystem](#digital-trust-ecosystem). An ecosystem governance framework may incorporate, aggregate, or reference other types of governance frameworks such as a [credential governance framework](#credential-governance-framework) or a [utility governance framework](#utility-governance-framework).


# eIDAS<a id="eidas"></a>

eIDAS (electronic IDentification, Authentication and trust Services) is an EU regulation with the stated purpose of governing "electronic identification and [trust services](#trust-service-provider) for electronic transactions". It passed in 2014 and its provisions came into effect between 2016-2018.

Source: [Wikipedia](https://en.wikipedia.org/wiki/EIDAS).


# encrypted data vault<a id="encrypted-data-vault"></a>

See: [digital vault](#digital-vault).


# encryption<a id="encryption"></a>

Cryptographic transformation of [data](#data) (called [plaintext](#plaintext)) into a form (called [ciphertext](#ciphertext)) that conceals the [data’s](#data) original meaning to prevent it from being known or used. If the transformation is reversible, the corresponding reversal process is called [decryption](#decryption), which is a transformation that restores encrypted [data](#data) to its original state.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/encryption).


# end-to-end encryption<a id="end-to-end-encryption"></a>

[Encryption](#encryption) that is applied to a [communication](#communication) before it is transmitted from the sender’s [communication endpoint](#communication-endpoint) and cannot be [decrypted](#decryption) until after it is received at the receiver’s [communication endpoint](#communication-endpoint). When end-to-end encryption is used, the [communication](#communication) cannot be [decrypted](#decryption) in transit no matter how many [intermediaries](#intermediary-system) are involved in the [routing](#routing) process.

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/End-to-end_encryption): End-to-end encryption (E2EE) is a private communication system in which only communicating users can participate. As such, no one, including the communication system provider, [telecom providers](https://en.wikipedia.org/wiki/Telecommunications_service_providers), [Internet providers](https://en.wikipedia.org/wiki/Internet_providers) or malicious actors, can access the [cryptographic keys](https://en.wikipedia.org/wiki/Key_\(cryptography\)) needed to converse. End-to-end [encryption](https://en.wikipedia.org/wiki/Encryption) is intended to prevent data being read or secretly modified, other than by the true sender and recipient(s). The messages are encrypted by the sender but the third party does not have a means to decrypt them, and stores them encrypted. The recipients retrieve the encrypted data and decrypt it themselves.


# End-to-End Principle<a id="end-to-end-principle"></a>

The end-to-end principle is a design framework in computer networking. In networks designed according to this principle, guaranteeing certain application-specific features, such as reliability and security, requires that they reside in the communicating end [nodes](#node) of the network. [Intermediary](#intermediary-system) nodes, such as [gateways](#gateway) and [routers](#router), that exist to establish the network, may implement these to improve efficiency but cannot guarantee end-to-end correctness.

Source: [Wikipedia](https://en.wikipedia.org/wiki/End-to-end_principle).

For more information, see: <https://trustoverip.org/permalink/Design-Principles-for-the-ToIP-Stack-V1.0-2022-11-17.pdf> 


# endpoint<a id="endpoint"></a>

See: [communication endpoint](#communication-endpoint).

See also: [ToIP endpoint](#ToIP-endpoint).


# endpoint system<a id="endpoint-system"></a>

The system that operates a [communications](#communication) [endpoint](#endpoint). In the context of the [ToIP stack](#toip-stack), an endpoint system is one of three types of systems defined in the [ToIP Technology Architecture Specification](#toip-technology-architecture-specification).

See also: [intermediary system](#intermediary-system), [supporting system](#supporting-system).


# enterprise data vault<a id="enterprise-data-vault"></a>

A [digital vault](#digital-vault) whose [controller](#controller-of-a-key-vault-wallet-agent-or-device) is an [organization](#organization).


# enterprise wallet<a id="enterprise-wallet"></a>

A [digital wallet](#digital-wallet) whose [holder](#holder-of-a-claim-or-credential) is an [organization](#organization).

Contrast with: [personal wallet](#personal-wallet).


# entity<a id="entity"></a>

Someone or something that is known to exist.

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary).


# ephemeral connection<a id="ephemeral-connection"></a>

A [connection](#connection) that only exists for the duration of a single [communication session](#communication-session) or [transaction](#transaction).

Contrast with: [persistent connection](#persistent-connection).


# expression language<a id="expression-language"></a>

A language for creating a computer-interpretable ([machine-readable](#machine-readable)) representation of specific [knowledge](#knowledge).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Expression_language).


# FAL<a id="fal"></a>

See: [federation assurance level](#federation-assurance-level).


# federated identity<a id="federated-identity"></a>

A [digital identity](#digital-identity) architecture in which a [digital identity](#digital-identity) established on one computer system, network, or [trust domain](#trust-domain) is linked to other computer systems, networks, or [trust domains](#trust-domain) for the purpose of identifying the same [entity](#entity) across those domains.

See also: [decentralized identity](#decentralized-identity), [self-sovereign identity](#self-sovereign-identity).

Supporting definitions:

[NIST-CSRC](https://csrc.nist.gov/glossary/term/federated_identity_management); A process that allows for the conveyance of identity and authentication information across a set of networked systems.

[Wikipedia](https://en.wikipedia.org/wiki/Federated_identity): A **federated identity** in [information technology](https://en.wikipedia.org/wiki/Information_technology) is the means of linking a person's [electronic identity](https://en.wikipedia.org/wiki/Digital_identity) and attributes, stored across multiple distinct [identity management](https://en.wikipedia.org/wiki/Identity_management) systems.

# federation<a id="federation"></a>

A group of [organizations](#organization) that collaborate to establish a common [trust framework](#trust-framework) or [governance framework](#governance-framework) for the exchange of [identity data](#identity-data) in a [federated identity](#federated-identity) system.

See also: [trust community](#trust-community)

Supporting definitions:

[NIST-CSRC](https://csrc.nist.gov/glossary/term/federation): A collection of realms (domains) that have established trust among themselves. The level of trust may vary, but typically includes authentication and may include authorization.


# federation assurance level<a id="federation-assurance-level"></a>

A category that describes the [federation](#federation) protocol used to communicate an assertion containing [authentication](#authenticator-of-an-entity)) and [attribute](#attribute) information (if applicable) to a [relying party](#relying-party), as defined in [NIST SP 800-63-3](https://pages.nist.gov/800-63-3/) in terms of three levels: FAL 1 (Some confidence), FAL 2 (High confidence), FAL 3 (Very high confidence).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/federation_assurance_level).

See also: [authenticator assurance level](#authenticator-assurance-level), [identity assurance level](#identity-assurance-level).


# fiduciary<a id="fiduciary"></a>

A fiduciary is a person who holds a legal or ethical relationship of trust with one or more other [parties](#party) (person or group of persons). Typically, a fiduciary prudently takes care of money or other [assets](#digital-asset) for another person. One [party](#party), for example, a corporate trust company or the trust department of a bank, acts in a fiduciary capacity to another [party](#party), who, for example, has entrusted funds to the fiduciary for safekeeping or investment. In a fiduciary relationship, one person, in a position of vulnerability, justifiably vests confidence, good faith, reliance, and trust in another whose aid, advice, or protection is sought in some matter.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Fiduciary).


# first party<a id="first-party"></a>

The [party](#party) who initiates a [trust relationship](#trust-relationship), [connection](#connection), or [transaction](#transaction) with a [second party](#second-party).

See also: [third party](#third-party), [fourth party](#fourth-party).


# foundational identity<a id="foundational-identity"></a>

A set of [identity data](#identity-data), such as a [credential](#credential), [issued](#issuer-of-a-claim-or-credential) by an [authoritative source](#authoritative-source) for the [legal identity](#legal-identity) of the [subject](#subject). Birth certificates, passports, driving licenses, and other forms of government ID documents are considered foundational [identity documents](#identity-document). Foundational identities are often used to provide [identity binding](#identity-binding) for [functional identities](#functional-identity).

Contrast with: [functional identity](#functional-identity).


# fourth party<a id="fourth-party"></a>

A [party](#party) that is not directly involved in the trust relationship between a [first party](#first-party) and a [second party](#second-party), but provides supporting services exclusively to the [first party](#first-party) (in contrast with a [third party](#third-party), who in most cases provides supporting services to the [second party](#second-party)). In its strongest form, a [fourth party](#fourth-party) has a [fiduciary](#fiduciary) relationship with the [first party](#first-party).


# functional identity<a id="functional-identity"></a>

A set of [identity data](#identity-data), such as a [credential](#credential), that is [issued](#issuer-of-a-claim-or-credential) not for the purpose of establishing a [foundational identity](#foundational-identity) for the subject, but for the purpose of establishing other attributes, qualifications, or capabilities of the subject. Loyalty cards, library cards, and employee IDs are all examples of functional identities. [Foundational identities](#foundational-identity) are often used to provide [identity binding](#identity-binding) for functional identities.


# gateway<a id="gateway"></a>

A gateway is a piece of networking hardware or software used in telecommunications networks that allows [data](#data) to flow from one discrete network to another. Gateways are distinct from [routers](#router) or switches in that they communicate using more than one protocol to connect multiple networks[<sup>\[1\]\[2\]</sup>](https://en.wikipedia.org/wiki/Gateway_\(telecommunications\)#cite_note-1) and can operate at any of the seven layers of the open systems interconnection model (OSI).

See also: [intermediary](#intermediary-system).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Gateway_\(telecommunications\)).


# GDPR<a id="gdpr"></a>

See: [General Data Protection Regulation](#general-data-protection-regulation).


# General Data Protection Regulation<a id="general-data-protection-regulation"></a>

The General Data Protection Regulation (Regulation (EU) 2016/679, abbreviated GDPR) is a European Union regulation on information privacy in the European Union (EU) and the European Economic Area (EEA). The GDPR is an important component of EU privacy law and human rights law, in particular Article 8(1) of the Charter of Fundamental Rights of the European Union. It also governs the transfer of [personal data](#personal-data) outside the EU and EEA. The GDPR's goals are to enhance individuals' control and rights over their personal information and to simplify the regulations for international business.

Source: [Wikipedia](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation).

Also known as: [GDPR](#gdpr).


# glossary<a id="glossary"></a>

A glossary (from Ancient Greek: γλῶσσα, glossa; language, speech, wording), also known as a _vocabulary_ or _clavis_, is an alphabetical list of [terms](#term) in a particular domain of [knowledge](#knowledge) ([scope](#scope)) together with the [definitions](#definition) for those terms. Unlike a [dictionary](#dictionary), a glossary has only one [definition](#definition) for each term.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Glossary).


# governance<a id="governance"></a>

The [act](#actor) or process of governing or overseeing the realization of (the results associated with) a set of [objectives](#objective) by the [owner](#owner-of-an-entity) of these [objectives](#objective), in order to ensure they will be fit for the purposes that this [owner](#owner-of-an-entity) intends to use them for.

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#governance).


# Governance, Risk Management, and Compliance<a id="governance-risk-management-and-compliance"></a>

[Governance](#governance), [risk management](#risk-management), and [compliance](#compliance) (GRC) are three related facets that aim to assure an [organization](#organization) reliably achieves [objectives](#objective), addresses uncertainty and acts with integrity. [Governance](#governance) is the combination of processes established and executed by the directors (or the board of directors) that are reflected in the [organization's](#organization) structure and how it is managed and led toward achieving goals. [Risk management](#risk-management) is predicting and managing risks that could hinder the [organization](#organization) from reliably achieving its [objectives](#objective) under uncertainty. [Compliance](#compliance) refers to adhering with the mandated boundaries (laws and regulations) and voluntary boundaries (company's policies, procedures, etc.)

Source: [Wikipedia](https://en.wikipedia.org/wiki/Governance,_risk_management,_and_compliance).

Also known as: [GRC](#grc).


# governance diamond<a id="governance-diamond"></a>

A term that refers to the addition of a [governing body](#governing-body) to the standard [trust triangle](#trust-triangle) of [issuers](#issuer-of-a-claim-or-credential), [holders](#holder-of-a-claim-or-credential), and [verifiers](#verifier-of-a-claim-or-credential) of [credentials](#credential). The resulting combination of four [parties](#party) represents the basic structure of a [digital trust ecosystem](#digital-trust-ecosystem).


# governance document<a id="governance-document"></a>

A document with at least one [identifier](#identifier) that specifies [governance requirements](#governance-requirement) for a [trust community](#trust-community). 

Note: A governance document is a component of a [governance framework](#governance-framework).

# governance framework<a id="governance-framework"></a>

A collection of one or more [governance documents](#governance-document) published by the [governing body](#governing-body) of a [trust community](#trust-community). 

Also known as: [trust framework](#trust-framework).

Note: In the [digital identity](#digital-identity) industry specifically, a governance framework is better known as a [trust framework](#trust-framework). ToIP-conformant governance frameworks conform to the [ToIP Governance Architecture Specification](#toip-governance-architecture-specification) and follow the [ToIP Governance Metamodel](#toip-governance-metamodel).

# governance graph<a id="governance-graph"></a>

A graph of the [governance](#governance) relationships between [entities](#entity) with a [trust community](#trust-community). A governance graph shows which [nodes](#node) are the [governing bodies](#governing-body) and which are the [governed parties](#governed-party). In some cases, a governance graph can be traversed by making queries to one or more [trust registries](#trust-registry).Note: a [party](#party) can play both [roles](#role) and also be a participant in multiple [governance frameworks](#governance-framework).

See also: [authorization graph](#authorization-graph), [reputation graph](#reputation-graph), [trust graph](#trust-graph).

# governance requirement<a id="governance-requirement"></a>

A [requirement](#requirement) such as a [policy](#policy), [rule](#rule), or [technical specification](#technical-specification) specified in a [governance document](#governance-document).

See also: [technical requirement](#technical-requirement).

# governed use case<a id="governed-use-case"></a>

A use case specified in a [governance document](#governance-document) that results in specific [governance requirements](#governance-requirement) within that [governance framework](#governance-framework). Governed use cases may optionally be discovered via a [trust registry](#trust-registry) authorized by the relevant [governance framework](#governance-framework).


# governed party<a id="governed-party"></a>

A [party](#party) whose [role(s)](#role) in a [trust community](#trust-community) is governed by the [governance requirements](#governance-requirement) in a [governance framework](#governance-framework).


# governed information<a id="governed-information"></a>

Any information published under the authority of a [governing body](#governing-body) for the purpose of governing a [trust community](#trust-community). This includes its [governance framework](#governance-framework) and any information available via an authorized [trust registry](#trust-registry).


# governing authority<a id="governing-authority"></a>

See: [governing body](#governing-body).


# governing body<a id="governing-body"></a>

The [party](#party) (or set of [parties](#party)) authoritative for governing a [trust community](#trust-community), usually (but not always) by developing, publishing, maintaining, and enforcing a [governance framework](#governance-framework). A governing body may be a government, a formal legal entity of any kind, an informal group of any kind, or an individual. A governing body may also delegate operational responsibilities to an [administering body](#administering-body).

Also known as: [governing authority](#governing-authority).


# GRC<a id="grc"></a>

See: [Governance, Risk Management, and Compliance](#governance-risk-management-and-compliance).


# guardian<a id="guardian"></a>

A [party](https://essif-lab.github.io/framework/docs/terms/party) that has been assigned rights and duties in a [guardianship arrangement](#guardianship-arrangement) for the purpose of caring for, protecting, guarding, and defending the [entity](https://essif-lab.github.io/framework/docs/terms/entity) that is the [dependent](https://essif-lab.github.io/framework/docs/terms/dependent) in that [guardianship arrangement](#guardianship-arrangement). In the context of decentralized digital trust infrastructure, a guardian is issued [guardianship credentials](#guardianship-credential) into their own [digital wallet](#digital-wallet) in order to perform such [actions](#action) on behalf of the [dependent](#dependent) as are required by this [role](#role).

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#guardian)

See also: [custodian](#custodian), [zero-knowledge service provider](#zero-knowledge-service-provider).

Mental Model: [eSSIF-Lab Guardianship](https://essif-lab.github.io/framework/docs/terms/pattern-guardianship)

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Legal_guardian): A legal guardian is a person who has been appointed by a court or otherwise has the legal authority (and the corresponding [duty](https://en.wikipedia.org/wiki/Duty)) to make decisions relevant to the personal and [property](https://en.wikipedia.org/wiki/Property) interests of another person who is deemed incompetent, called a [ward](https://en.wikipedia.org/wiki/Ward_\(law\)).

For more information, see: [On Guardianship in Self-Sovereign Identity V2.0](https://sovrin.org/wp-content/uploads/Guardianship-Whitepaper-V2.0.pdf) (April, 2023).

Note: A guardian is a very different role than a [custodian](#custodian), who does not take any [actions](#action) on behalf of a [principal](#principal) unless explicitly [authorized](#authorization).


# guardianship arrangement<a id="guardianship-arrangement"></a>

A guardianship arrangement (in a [jurisdiction](#jurisdiction)) is the specification of a set of rights and duties between [legal entities](https://essif-lab.github.io/framework/docs/terms/legal-entity) of the [jurisdiction](https://essif-lab.github.io/framework/docs/terms/jurisdiction) that enforces these rights and duties, for the purpose of caring for, protecting, guarding, and defending one or more of these [entities](https://essif-lab.github.io/framework/docs/terms/legal-entity). At a minimum, the entities participating in a guardianship arrangement are the [guardian](#guardian) and the [dependent](#dependent).

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#guardian)

See also: [custodianship arrangement](#custodianship-arrangement).

Mental Model: [eSSIF-Lab Guardianship](https://essif-lab.github.io/framework/docs/terms/pattern-guardianship)

For more information, see: [On Guardianship in Self-Sovereign Identity V2.0](https://sovrin.org/wp-content/uploads/Guardianship-Whitepaper-V2.0.pdf) (April, 2023).


# guardianship credential<a id="guardianship-credential"></a>

A [digital credential](#digital-credential) [issued](#issuer-of-a-claim-or-credential) by a [governing body](#governing-body) to a [guardian](#guardian) to empower the [guardian](#guardian) to undertake the rights and duties of a [guardianship arrangement](#guardianship-arrangement) on behalf of a [dependent](#dependent).


# hardware security module<a id="hardware-security-module"></a>

A physical computing device that provides tamper-evident and intrusion-resistant safeguarding and management of digital [keys](#cryptographic-key) and other secrets, as well as crypto-processing.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/hardware_security_module_hsm).

Also known as: [HSM](#hsm).

Supporting definitions:

[NIST-CSRC](https://csrc.nist.gov/glossary/term/hardware_security_module_hsm): A physical computing device that provides tamper-evident and intrusion-resistant safeguarding and management of digital keys and other secrets, as well as crypto-processing. FIPS 140-2 specifies requirements for HSMs.

[Wikipedia](https://en.wikipedia.org/wiki/Hardware_security_module): A physical computing device that safeguards and manages secrets (most importantly [digital keys](https://en.wikipedia.org/wiki/Digital_keys)), performs [encryption](https://en.wikipedia.org/wiki/Encryption) and decryption functions for [digital signatures](https://en.wikipedia.org/wiki/Digital_signature), [strong authentication](https://en.wikipedia.org/wiki/Strong_authentication) and other cryptographic functions. These modules traditionally come in the form of a plug-in card or an external device that attaches directly to a [computer](https://en.wikipedia.org/wiki/Computer) or [network server](https://en.wikipedia.org/wiki/Server_\(computing\)). A hardware security module contains one or more [secure cryptoprocessor](https://en.wikipedia.org/wiki/Secure_cryptoprocessor) [chips](https://en.wikipedia.org/wiki/Integrated_circuit).


# hash<a id="hash"></a>

The result of applying a [hash function](#hash-function) to a [message](#message).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/hash_value).

Also known as: hash output, hash result, hash value.


# hash function<a id="hash-function"></a>

An algorithm that computes a numerical value (called the [hash value](#hash)) on a [data](#data) file or electronic [message](#message) that is used to represent that file or message, and depends on the entire contents of the file or message. A hash function can be considered to be a fingerprint of the file or message. Approved hash functions satisfy the following properties: _one-way_ (it is computationally infeasible to find any input that maps to any pre-specified output); and _collision resistant_ (it is computationally infeasible to find any two distinct inputs that map to the same output).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/hash_function).


# holder (of a claim or credential)<a id="holder-of-a-claim-or-credential"></a>

A [role](#role) an [agent](#agent) performs by serving as the [controller](#controller-of-a-key-vault-wallet-agent-or-device) of the [cryptographic keys](#cryptographic-key) and [digital credentials](#digital-credential) in a [digital wallet](#digital-wallet). The holder makes [issuance requests](#issuance-request) for [credentials](#credential) and responds to [presentation requests](#presentation-request) for [credentials](#credential). A holder is usually, but not always, a [subject](#subject) of the [credentials](#credential) they are holding.

See also: [issuer](#issuer-of-a-claim-or-credential), [verifier](#verifier-of-a-claim-or-credential).

Mental model: [W3C Verifiable Credentials Data Model Roles & Information Flows](https://www.w3.org/TR/vc-data-model/#roles)

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/terms/holder): a component that implements the [capability](https://essif-lab.github.io/framework/docs/terms/capability) to handle [presentation requests](https://essif-lab.github.io/framework/docs/terms/presentation-request) from a [peer agent](https://essif-lab.github.io/framework/docs/terms/peer-agent), produce the requested data (a presentation) according to its [principal](https://essif-lab.github.io/framework/docs/terms/principal)'s [holder-policy](https://essif-lab.github.io/framework/docs/terms/holder-policy), and send that in response to the request.

[W3C VC](https://www.w3.org/TR/vc-data-model/#dfn-holders): A role an [entity](https://www.w3.org/TR/vc-data-model/#dfn-entities) might perform by possessing one or more [verifiable credentials](https://www.w3.org/TR/vc-data-model/#dfn-verifiable-credentials) and generating [presentations](https://www.w3.org/TR/vc-data-model/#dfn-presentations) from them. A holder is usually, but not always, a [subject](https://www.w3.org/TR/vc-data-model/#dfn-subjects) of the [verifiable credentials](https://www.w3.org/TR/vc-data-model/#dfn-verifiable-credentials) they are holding. Holders store their [credentials](https://www.w3.org/TR/vc-data-model/#dfn-credential) in [credential repositories](https://www.w3.org/TR/vc-data-model/#dfn-credential-repository).


# holder binding<a id="holder-binding"></a>

The process of creating and verifying a relationship between the [holder](#holder-of-a-claim-or-credential) of a [digital wallet](#digital-wallet) and the wallet itself. Holder binding is related to but NOT the same as subject binding.


# host<a id="host"></a>

A host is any hardware device that has the capability of permitting access to a network via a user interface, specialized software, [network address](#network-address), [protocol stack](#protocol-stack), or any other means. Some examples include, but are not limited to, computers, personal electronic devices, thin clients, and multi-functional devices.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/host).

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Host_\(network\)): A network host is a [computer](https://en.wikipedia.org/wiki/Computer) or other device connected to a [computer network](https://en.wikipedia.org/wiki/Computer_network). A host may work as a [server](https://en.wikipedia.org/wiki/Server_\(computing\)) offering information resources, services, and applications to users or other hosts on the network. Hosts are assigned at least one [network address](https://en.wikipedia.org/wiki/Network_address). A computer participating in networks that use the [Internet protocol suite](https://en.wikipedia.org/wiki/Internet_protocol_suite) may also be called an IP host. Specifically, computers participating in the [Internet](https://en.wikipedia.org/wiki/Internet) are called Internet hosts. Internet hosts and other IP hosts have one or more [IP addresses](https://en.wikipedia.org/wiki/IP_address) assigned to their network interfaces.


# hourglass model<a id="hourglass-model"></a>

An architectural model for layered systems—and specifically for the [protocol layers](#protocol-layer) in a [protocol stack](#protocol-stack)—in which a diversity of supporting protocols and services at the lower layers are able to support a great diversity of protocols and applications at the higher layers through the use of a single protocol in the [spanning layer](#spanning-layer) in the middle—the “neck” of the hourglass. 

See also: [trust spanning protocol](#trust-spanning-protocol).

For more information, see: <https://trustoverip.org/permalink/Design-Principles-for-the-ToIP-Stack-V1.0-2022-11-17.pdf> and <https://cacm.acm.org/magazines/2019/7/237714-on-the-hourglass-model/abstract> 

Note: The Internet’s [TCP/IP stack](#tcpip) follows the hourglass model, and it is the design model for the [ToIP stack](#toip-stack).


# HSM<a id="hsm"></a>

See: [hardware security module](#hardware-security-module).


# human auditability<a id="human-auditability"></a>

See: [human auditable](#human-auditable).

Contrast with: [cryptographic verifiability](#cryptographic-verifiability).


# human auditable<a id="human-auditable"></a>

A process or procedure whose [compliance](#compliance) with the [policies](#policy) in a [trust framework](#trust-framework) or [governance framework](#governance-framework) can only be [verified](#verifiable) by a human performing an [audit](#audit-of-system-controls). Human auditability is a primary goal of the [ToIP Governance Stack](#toip-governance-stack).

Contrast with: [cryptographically verifiable](#cryptographically-verifiable).


# human experience<a id="human-experience"></a>

The processes, patterns and rituals of acquiring [knowledge](#knowledge) or skill from doing, seeing, or feeling things as a [natural person.](#natural-person) In the context of decentralized digital trust infrastructure, the direct experience of a [natural person](#natural-person) using [trust applications](#trust-application) to make [trust decisions](#trust-decision) within one or more [digital trust ecosystems](#digital-trust-ecosystem).

Note: Human experience includes social experiences (e.g., rituals, behaviors, ceremonies and rites of passage), as well as customer experience, worker or employee experience, and user experience.


# human-readable<a id="human-readable"></a>

Information that can be processed by a human but that is not intended to be [machine-readable](#machine-readable).


# human trust<a id="human-trust"></a>

A [level of assurance](#level-of-assurance) in a [trust relationship](#trust-relationship) that can be achieved only via human evaluation of applicable [trust](#trust) factors.

Contrast with: [technical trust](#technical-trust).


# IAL<a id="ial"></a>

See: [identity assurance level](#identity-assurance-level).


# identification<a id="identification"></a>

The [action](#action) of a [party](#party) obtaining the set of [identity data](#identity-data) necessary to serve as that [party’s](#party) [identity](#identity) for a specific [entity](#entity).

Note: The act of identification of a specific [entity](#entity) is relational to each [party](#party) that needs to perform that action. Therefore each party may end up with their own set of [identity data](#identity-data) that meets their specific [requirements](#requirement) for their specific [scope](#scope).


# identifier<a id="identifier"></a>

A single [attribute](#attribute)—typically a character string—that uniquely identifies an [entity](#entity) within a specific context (which may be a global context). Examples include the name of a [party,](#party) the URL of an [organization](#organization), or a serial number for a [man-made thing](#man-made-thing).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#identifier): a character string that is being used for the identification of some [entity](https://essif-lab.github.io/framework/docs/terms/entity) (yet may refer to 0, 1, or more [entities](https://essif-lab.github.io/framework/docs/terms/entity), depending on the context within which it is being used).


# identity<a id="identity"></a>

A collection of [attributes](#attribute) or other [identity data](#identity-data) that describe an [entity](#entity) and enable it to be distinguished from all other [entities](#entity) within a specific [scope](#scope) of [identification](#identification). Identity attributes may include one or more [identifiers](#identifier) for an [entity](#entity), however it is possible to establish an identity without using [identifiers](#identifier).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#identity): the combined [knowledge](https://essif-lab.github.io/framework/docs/terms/knowledge) about that [entity](https://essif-lab.github.io/framework/docs/terms/entity) of all [parties](https://essif-lab.github.io/framework/docs/terms/party), i.e. the union of all [partial identities](https://essif-lab.github.io/framework/docs/terms/partial-identity) of which that [entity](https://essif-lab.github.io/framework/docs/terms/entity) is the [subject](https://essif-lab.github.io/framework/docs/terms/subject).

Note: Identity is relational to the [party](#party) performing the identification. For example, if 100 different [parties](#party) have an identity for the same [entity](#entity), each of them may hold a different set of [identity data](#identity-data) enabling identification of that [entity](#entity).

# identity assurance level<a id="identity-assurance-level"></a>

A category that conveys the degree of confidence that a person’s claimed [identity](#identity) is their real [identity](#identity), for example as defined in [NIST SP 800-63-3](https://pages.nist.gov/800-63-3/sp800-63-3.html) in terms of three levels: IAL 1 (Some confidence), IAL 2 (High confidence), IAL 3 (Very high confidence).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/identity_assurance_level).

See also: [authenticator assurance level](#authenticator-assurance-level), [federation assurance level](#federation-assurance-level).

# identity binding<a id="identity-binding"></a>

The process of associating a set of [identity data](#identity-data), such as a [credential](#credential), with its [subject](#subject), such as a [natural person](#natural-person). The strength of an identity binding is one factor in determining an [authenticator assurance level](#authenticator-assurance-level).

See also: [identity assurance level](#identity-assurance-level), [identity proofing](#identity-proofing).


# identity data<a id="identity-data"></a>

The set of [data](#data) held by a [party](#party) in order to provide an [identity](#identity) for a specific [entity](#entity).


# identity document<a id="identity-document"></a>

A physical or digital document containing [identity data](#identity-data). A [credential](#credential) is a specialized form of identity document. Birth certificates, bank statements, and utility bills can all be considered identity documents.


# identity proofing<a id="identity-proofing"></a>

The process of a [party](#party) gathering sufficient [identity data](#identity-data) to establish an [identity](#identity) for a particular [subject](#subject) at a particular [identity assurance level](#identity-assurance-level).

See also: [identity binding](#identity-binding).

Supporting definitions:

[NIST-CSRC](https://csrc.nist.gov/glossary/term/identity_proofing): The process of providing sufficient information (e.g., identity history, credentials, documents) to establish an identity.


# identity provider<a id="identity-provider"></a>

An identity provider (abbreviated IdP or IDP) is a system [entity](#entity) that creates, maintains, and manages [identity](#identity) information for [principals](#principal) and also provides [authentication](#authenticator-of-an-entity) services to relying applications within a [federation](#federation) or distributed network.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Identity_provider).

Note: The term “identity provider” is used in [federated identity](#federated-identity) systems because it is a required component of their architecture. By contrast, [decentralized identity](#decentralized-identity) and [self-sovereign identity](#self-sovereign-identity) systems do not use the term because they are architected to enable [entities](#entity) to create and control their own [digital identities](#digital-identity) without the need to depend on an external provider.


# IDP<a id="idp"></a>

See: [identity provider](#identity-provider).


# impersonation<a id="impersonation"></a>

In the context of cybersecurity, impersonation is when an attacker pretends to be another person in order to commit fraud or some other digital crime.

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Impersonator): An impersonator is someone who imitates or copies the behavior or actions of another. As part of a [criminal act](https://en.wikipedia.org/wiki/Crime) such as [identity theft](https://en.wikipedia.org/wiki/Identity_theft), the criminal is trying to assume the identity of another, in order to commit [fraud](https://en.wikipedia.org/wiki/Fraud), such as accessing confidential information, or to gain property not belonging to them. Also known as [social engineering](https://en.wikipedia.org/wiki/Social_engineering_\(security\)) and [impostors](https://en.wikipedia.org/wiki/Impostor).


# integrity (of a data structure)<a id="integrity-of-a-data-structure"></a>

In IT security, data integrity means maintaining and assuring the accuracy and completeness of [data](#data) over its entire lifecycle. This means that [data](#data) cannot be modified in an [unauthorized](#authorization) or undetected manner.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Information_security#Integrity).


# intermediary system<a id="intermediary-system"></a>

A system that operates at [ToIP Layer 2](#toip-layer-2), the [trust spanning layer](#trust-spanning-layer) of the [ToIP stack](#toip-stack), in order to route [ToIP messages](#toip-message) between [endpoint systems](#endpoint-system). A supporting system is one of three types of systems defined in the [ToIP Technology Architecture Specification](#toip-technology-architecture-specification).

See also: [endpoint system](#endpoint-system), [supporting system](#supporting-system).


# Internet Protocol<a id="internet-protocol"></a>

The Internet Protocol (IP) is the network layer [communications](#communication) protocol in the Internet protocol suite (also known as the [TCP/IP](#tcpip) suite) for relaying [datagrams](#datagram) across network boundaries. Its [routing](#routing) function enables internetworking, and essentially establishes the Internet. IP has the task of delivering [packets](#data-packet) from the source host to the destination host solely based on the [IP addresses](#ip-address) in the packet headers. For this purpose, IP defines [packet](#data-packet) structures that encapsulate the data to be delivered. It also defines addressing methods that are used to label the datagram with source and destination information.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Internet_Protocol).

Also known as: [IP](#ip).

See also: [Transmission Control Protocol](#transmission-control-protocol), [User Datagram Protocol](#user-datagram-protocol).


# Internet protocol suite<a id="internet-protocol-suite"></a>

The Internet protocol suite, commonly known as [TCP/IP](#tcpip), is a framework for organizing the set of [communication](#communication) protocols used in the Internet and similar computer networks according to functional criteria. The foundational protocols in the suite are the [Transmission Control Protocol](#transmission-control-protocol) (TCP), the [User Datagram Protocol](#user-datagram-protocol) (UDP), and the [Internet Protocol](#internet-protocol) (IP).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Internet_protocol_suite)

Also known as: [TCP/IP](#tcpip).

See also: [protocol stack](#protocol-stack).


# IP<a id="ip"></a>

See: [Internet Protocol](#internet-protocol).


# IP address<a id="ip-address"></a>

An [Internet Protocol](#internet-protocol) address (IP address) is a numerical label such as 192.0.2.1 that is connected to a computer network that uses the [Internet Protocol](#internet-protocol) for [communication](#communication). An IP address serves two main functions: network interface [identification](#identification), and location [addressing](#address).

Source: [Wikipedia](https://en.wikipedia.org/wiki/IP_address).


# issuance<a id="issuance"></a>

The [action](#action) of an [issuer](#issuer-of-a-claim-or-credential) producing and transmitting a [digital credential](#digital-credential) to a [holder](#holder-of-a-claim-or-credential). A [holder](#holder-of-a-claim-or-credential) may request issuance by submitting an [issuance request](#issuance-request).

See also: [presentation](#presentation), [revocation](#revocation).


# issuance request<a id="issuance-request"></a>

A protocol request invoked by the [holder](#holder-of-a-claim-or-credential) of a [digital wallet](#digital-wallet) to obtain a [digital credential](#digital-credential) from an [issuer](#issuer-of-a-claim-or-credential).

See also: [presentation request](#presentation-request).


# issuer (of a claim or credential)<a id="issuer-of-a-claim-or-credential"></a>

A [role](#role) an [agent](#agent) performs to package and [digitally sign](#digital-signature) a set of [claims](#claim), typically in the form of a [digital credential](#digital-credential), and transmit them to a [holder](#holder-of-a-claim-or-credential).

See also: [verifier](#verifier-of-a-claim-or-credential), [holder](#holder-of-a-claim-or-credential).

Mental model: [W3C Verifiable Credentials Data Model Roles & Information Flows](https://www.w3.org/TR/vc-data-model/#roles)

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#issuer): a component that implements the [capability](https://essif-lab.github.io/framework/docs/terms/capability) to construct [credentials](https://essif-lab.github.io/framework/docs/terms/credential) from data objects, according to the content of its [principal](https://essif-lab.github.io/framework/docs/terms/principal)'s [issuer](https://essif-lab.github.io/framework/docs/terms/issuer)-Policy (specifically regarding the way in which the [credential](https://essif-lab.github.io/framework/docs/terms/credential) is to be digitally signed), and pass it to the [wallet](https://essif-lab.github.io/framework/docs/terms/wallet)-component of its [principal](https://essif-lab.github.io/framework/docs/terms/principal) allowing it to be issued.

[W3C VC](https://www.w3.org/TR/vc-data-model/#terminology): A role an [entity](https://www.w3.org/TR/vc-data-model/#dfn-entities) can perform by asserting [claims](https://www.w3.org/TR/vc-data-model/#dfn-claims) about one or more [subjects](https://www.w3.org/TR/vc-data-model/#dfn-subjects), creating a [verifiable credential](https://www.w3.org/TR/vc-data-model/#dfn-verifiable-credentials) from these [claims](https://www.w3.org/TR/vc-data-model/#dfn-claims), and transmitting the [verifiable credential](https://www.w3.org/TR/vc-data-model/#dfn-verifiable-credentials) to a [holder](https://www.w3.org/TR/vc-data-model/#dfn-holders).


# jurisdiction<a id="jurisdiction"></a>

The composition of: a) a [legal system](#legal-system) (legislation, enforcement thereof, and conflict resolution), b) a [party](#party) that governs that [legal system](#legal-system), c) a scope within which that [legal system](#legal-system) is operational, and d) one or more [objectives](#objective) for the purpose of which the [legal system](#legal-system) is operated.

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#jurisdiction)

Mental model: [eSSIF-Lab Jurisdictions ](https://essif-lab.github.io/framework/docs/terms/pattern-jurisdiction)


# KATE<a id="kate"></a>

See: [keys-at-the-edge](#keys-at-the-edge).


# KERI<a id="keri"></a>

See: [Key Event Receipt Infrastructure](#key-event-receipt-infrastructure).


# key<a id="key"></a>

See: [cryptographic key](#cryptographic-key).


# key establishment<a id="key-establishment"></a>

A process that results in the sharing of a key between two or more entities, either by transporting a key from one entity to another (key transport) or generating a key from information shared by the entities (key agreement).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/key_establishment).


# key event<a id="key-event"></a>

An event in the history of the usage of a [cryptographic key pair](#cryptographic-key). There are multiple types of key events. The inception event is when the key pair is first generated. A rotation event is when the key pair is changed to a new key pair. In some [key management systems](#key-management-system) (such as [KERI](#keri)), key events are tracked in a [key event log](#key-event-log).


# key event log<a id="key-event-log"></a>

An ordered sequence of [records](#record) of [key events](#key-event).

Note: Key event logs are a fundamental data structure in [KERI](#keri).


# Key Event Receipt Infrastructure<a id="key-event-receipt-infrastructure"></a>

A decentralized permissionless [key management](#key-management-system) architecture.

Also known as: KERI.

For more information, see: <https://keri.one/>, [ToIP ACDC Task Force](https://wiki.trustoverip.org/display/HOME/ACDC+%28Authentic+Chained+Data+Container%29+Task+Force)


# key management system<a id="key-management-system"></a>

A system for the management of [cryptographic keys](#cryptographic-key) and their [metadata](#metadata) (e.g., generation, distribution, storage, backup, archive, recovery, use, [revocation](#revocation), and destruction). An automated key management system may be used to oversee, automate, and secure the key management process. A key management is often protected by implementing it within the [trusted execution environment](#trusted-execution-environment) (TEE) of a device. An example is the [Secure Enclave](#secure-enclave) on Apple iOS devices.

Also known as: [KMS](#kms).

Source: [NIST-CRSC](https://csrc.nist.gov/glossary/term/key_management_system).


# keys-at-the-edge<a id="keys-at-the-edge"></a>

A [key management](#key-management-system) architecture in which [keys](#key) are stored on a user’s local edge devices, such as a smartphone, tablet, or laptop, and then used in conjunction with a secure protocol to unlock a [key management system](#key-management-system) (KMS) and/or a [digital vault](#digital-vault) in the cloud. This approach can enable the storage and sharing of large [data](#data) structures that are not feasible on edge devices. This architecture can also be used in conjunction with [confidential computing](#confidential-computing) to enable cloud-based [digital agents](#digital-agent) to safely carry out “user not present” operations.

Also known as: [KATE](#kate).


# KMS<a id="kms"></a>

See: [key management system](#key-management-system).


# knowledge<a id="knowledge"></a>

The (intangible) sum of what is known by a specific [party](https://essif-lab.github.io/framework/docs/terms/party), as well as the familiarity, awareness or understanding of someone or something by that [party](https://essif-lab.github.io/framework/docs/terms/party).

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#knowledge).


# Laws of Identity<a id="laws-of-identity"></a>

A set of seven “laws” written by Kim Cameron, former Chief Identity Architect of Microsoft (1941-2021), to describe the dynamics that cause digital identity systems to succeed or fail in various contexts. His goal was to define the requirements for a unifying identity metasystem that can offer the Internet the identity layer it needs.

For more information, see: <https://www.identityblog.com/?p=352>.


# Layer 1<a id="layer-1"></a>

See: [ToIP Layer 1](#toip-layer-1).


# Layer 2<a id="layer-2"></a>

See: [ToIP Layer 2](#toip-layer-2).


# Layer 3<a id="layer-3"></a>

See: [ToIP Layer 3](#toip-layer-3).


# Layer 4<a id="layer-4"></a>

See: [ToIP Layer 4](#toip-layer-4).


# legal entity<a id="legal-entity"></a>

An [entity](#entity) that is not a [natural person](#natural-person) but is recognized as having legal rights and responsibilities. Examples include corporations, partnerships, sole proprietorships, non-profit [organizations](#organization), associations, and governments. (In some cases even natural systems such as rivers are treated as legal entities.)

See also: [Legal Entity Identifier](#legal-entity-identifier), [legal person](#legal-person), [organization](#organization).


# Legal Entity Identifier<a id="legal-entity-identifier"></a>

The Legal Entity Identifier (LEI) is a unique global [identifier](#identifier) for [legal entities](#legal-entity) participating in financial transactions. Also known as an LEI code or LEI number, its purpose is to help identify [legal entities](#legal-entity) on a globally accessible database. Legal entities are [organisations](#organization) such as companies or government entities that participate in financial transactions.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Legal_Entity_Identifier).

Note: LEIs are administered by the [Global Legal Entity Identifier Foundation](https://www.gleif.org/) (GLEIF).


# legal identity<a id="legal-identity"></a>

A set of [identity data](#identity-data) considered [authoritative](#authority) to identify a [party](#party) for purposes of legal accountability under one or more [jurisdictions](#jurisdiction).

See also: [foundational identity](#foundational-identity), [functional identity](#functional-identity).


# legal person<a id="legal-person"></a>

In law, a legal person is any person or 'thing' that can do the things a human person is usually able to do in law – such as enter into contracts, sue and be sued, own property, and so on.[<sup>\[3\]\[4\]\[5\]</sup>](https://en.wikipedia.org/wiki/Legal_person#cite_note-3) The reason for the term "legal person" is that some legal persons are not people: companies and corporations are "persons" legally speaking (they can legally do most of the things an ordinary person can do), but they are not people in a literal sense (human beings).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Legal_person).

Contrast with: [natural person](#natural-person).

See also: [legal entity](#legal-entity), [organization](#organization).


# legal system<a id="legal-system"></a>

A system in which [policies](#policy) and [rules](#rule) are defined, and mechanisms for their enforcement and conflict resolution are (implicitly or explicitly) specified. Legal systems are not just defined by governments; they can also be defined by a [governance framework](#governance-framework).

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#legal-system)


# LEI<a id="lei"></a>

See: [Legal Entity Identifier](#legal-entity-identifier).


# level of assurance<a id="level-of-assurance"></a>

See: [assurance level](#assurance-level).


# liveness detection<a id="liveness-detection"></a>

Any technique used to detect a [presentation attack](#presentation-attack) by determining whether the source of a biometric sample is a live human being or a fake representation. This is typically accomplished using algorithms that analyze biometric sensor data to detect whether the source is live or reproduced.

Also known as: [proof of presence](#proof-of-presence).


# locus of control<a id="locus-of-control"></a>

The set of computing systems under a [party’s](#party) direct control, where [messages](#message) and [data](#data) do not cross [trust boundaries](#trust-boundary).


# machine-readable<a id="machine-readable"></a>

Information written in a computer language or [expression language](#expression-language) so that it can be read and processed by a computing device.

Contrast with: [human-readable](#human-readable).


# man-made thing<a id="man-made-thing"></a>

A[ thing](#thing) generated by human activity of some kind. Man-made things include both active things, such as cars or drones, and passive things, such as chairs or trousers.

Source: [Sovrin Foundation Glossary V3](https://docs.google.com/document/d/1gfIz5TT0cNp2kxGMLFXr19x1uoZsruUe_0glHst2fZ8/edit)

Contrast with: [natural thing](#natural-thing).

Note: Active things are the equivalent of non-human [actors ](#actor)in the eSSIF-Lab mental model [Parties, Actors, Actions](https://essif-lab.pages.grnet.gr/framework/docs/terms/pattern-party-actor-action). Also see[ Appendix B](https://docs.google.com/document/d/1gfIz5TT0cNp2kxGMLFXr19x1uoZsruUe_0glHst2fZ8/edit#heading=h.mq7pzglc1j96) and[ Appendix C](https://docs.google.com/document/d/1gfIz5TT0cNp2kxGMLFXr19x1uoZsruUe_0glHst2fZ8/edit#heading=h.uiq9py7xnmxd) of the Sovrin Glossary.


# mandatory<a id="mandatory"></a>

A [requirement](#requirement) that must be implemented in order for an implementer to be in [compliance](#compliance). In [ToIP governance frameworks](#toip-governance-framework), a mandatory [requirement](#requirement) is expressed using a MUST or REQUIRED keyword as defined in IETF RFC 2119.

See also: [recommended](#recommended), [optional](#optional).

For more information, see: <https://www.rfc-editor.org/rfc/rfc2119>.


# metadata<a id="metadata"></a>

Information describing the characteristics of [data](#data) including, for example, structural metadata describing data structures (e.g., data format, syntax, and semantics) and descriptive metadata describing data contents (e.g., information security labels).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/metadata).

See also: [communication metadata](#communication-metadata).

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Metadata): Metadata (or metainformation) is "[data](https://en.wikipedia.org/wiki/Data) that provides information about other data", but not the content of the data itself, such as the text of a message or the image itself.


# message<a id="message"></a>

A discrete unit of [communication](#communication) intended by the source for consumption by some recipient or group of recipients.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Message).

See also: [ToIP message](#toip-message), [verifiable message](#verifiable-message).


# mobile deep link<a id="mobile-deep-link"></a>

In the context of mobile apps, [deep linking](#deep-link) consists of using a uniform resource identifier (URI) that links to a specific location within a mobile app rather than simply launching the app. Deferred deep linking allows users to deep link to content even if the app is not already installed. Depending on the mobile device platform, the URI required to trigger the app may be different.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Mobile_deep_linking).


# MPC<a id="mpc"></a>

See: [multi-party computation](#multi-party-computation).


# multicast<a id="multicast"></a>

In computer networking, multicast is group [communication](#communication) where [data](#data) transmission is addressed (using a [multicast address](#multicast-address)) to a group of destination computers simultaneously. Multicast can be one-to-many or many-to-many distribution. Multicast should not be confused with physical layer point-to-multipoint communication.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Multicast).

See also: [anycast](#anycast), [broadcast](#broadcast), [unicast](#unicast).


# multicast address<a id="multicast-address"></a>

A multicast address is a logical [identifier](#identifier) for a group of [hosts](#host) in a computer network that are available to process [datagrams](#datagram) or frames intended to be [multicast](#multicast) for a designated network service.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Multicast_address).

See also: [broadcast address](#broadcast-address), [unicast address](#unicast-address).


# multi-party computation<a id="multi-party-computation"></a>

Secure multi-party computation (also known as secure computation, multi-party computation (MPC) or privacy-preserving computation) is a subfield of cryptography with the goal of creating methods for [parties](#party) to jointly compute a function over their inputs while keeping those inputs private. Unlike traditional cryptographic tasks, where cryptography assures security and [integrity](#integrity-of-a-data-structure) of [communication](#communication) or storage and the adversary is outside the system of participants (an eavesdropper on the sender and receiver), the cryptography in this model protects participants' privacy from each other.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Secure_multi-party_computation).

Also known as: [MPC](#mpc), [secure multi-party computation](#secure-multi-party-computation).


# multi-party control<a id="multi-party-control"></a>

A variant of [multi-party computation](#multi-party-computation) where multiple parties must act in concert to meet a control requirement without revealing each other’s data. All parties are privy to the output of the control, but no party learns anything about the others.


# multi-signature<a id="multi-signature"></a>

A cryptographic [signature](#digital-signature) scheme where the process of signing information (e.g., a transaction) is distributed among multiple [private keys](#private-key).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/multi_signature).


# natural person<a id="natural-person"></a>

A person (in legal meaning, i.e., one who has its own legal personality) that is an individual human being, distinguished from the broader category of a [legal person](#legal-person), which may be a private (i.e., business entity or non-governmental [organization](#organization)) or public (i.e., government) [organization](#organization).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Natural_person).

See also: [legal entity](#legal-entity), [party](#party).

Contrast with: [legal person](#legal-person)


# natural thing<a id="natural-thing"></a>

A [thing](#thing) that exists in the natural world independently of humans. Although natural things may form part of a [man-made thing](https://trustoverip.github.io/hxwg/glossary.html#man-made-thing), natural things are mutually exclusive with [man-made things](https://trustoverip.github.io/hxwg/glossary.html#man-made-thing). 

Source: [Sovrin Foundation Glossary V3](https://docs.google.com/document/d/1gfIz5TT0cNp2kxGMLFXr19x1uoZsruUe_0glHst2fZ8/edit). 

Contrast with: [man-made thing](#man-made-thing).

For more information see: [Appendix B](https://docs.google.com/document/d/1gfIz5TT0cNp2kxGMLFXr19x1uoZsruUe_0glHst2fZ8/edit#heading=h.mq7pzglc1j96) and[ Appendix C](https://docs.google.com/document/d/1gfIz5TT0cNp2kxGMLFXr19x1uoZsruUe_0glHst2fZ8/edit#heading=h.uiq9py7xnmxd) of the Sovrin Glossary

Note: Natural things (those recognized to have legal rights) can be [parties](#party) but never [actors](#actor) in the eSSIF-Lab mental model [Parties, Actors, Actions](https://essif-lab.pages.grnet.gr/framework/docs/terms/pattern-party-actor-action). 


# network address<a id="network-address"></a>

A network address is an [identifier](#identifier) for a [node](#node) or [host](#host) on a telecommunications network. Network addresses are designed to be unique [identifiers](#identifier) across the network, although some networks allow for local, private addresses, or locally administered addresses that may not be unique. Special network addresses are allocated as [broadcast](#broadcast) or [multicast](#multicast) addresses. A network address designed to address a single device is called a [unicast address](#unicast-address).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Network_address).


# node<a id="node"></a>

In telecommunications networks, a node (Latin: nodus, ‘knot’) is either a redistribution point or a [communication endpoint](#communication-endpoint). The definition of a node depends on the network and [protocol layer](#protocol-layer) referred to. A physical network node is an electronic device that is attached to a network, and is capable of creating, receiving, or transmitting information over a [communication channel](#communication-channel).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Node_\(networking\)).


# non-custodial wallet<a id="non-custodial-wallet"></a>

A [digital wallet](#digital-wallet) that is directly in the control of the [holder](#holder-of-a-claim-or-credential), usually because the holder is the [device controller](#device-controller) of the device hosting the [digital wallet](#digital-wallet) (smartcard, smartphone, tablet, laptop, desktop, car, etc.) A [digital wallet](#digital-wallet) that is in the custody of a [third party](#third-party) is called a [custodial wallet](#custodial-wallet).


# objective<a id="objective"></a>

Something toward which a [party](#party) (its [owner](#owner-of-an-entity)) directs effort (an aim, goal, or end of [action](#action)).

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/terms/objective).


# OOBI<a id="oobi"></a>

See: [out-of-band introduction](#out-of-band-introduction).


# OpenWallet Foundation<a id="openwallet-foundation"></a>

A non-profit project of the [Linux Foundation](https://www.linuxfoundation.org/) chartered to build a world-class open source [wallet engine](#wallet-engine).

See also: [Decentralized Identity Foundation](#decentralized-identity-foundation), [ToIP Foundation](#toip-foundation).

For more information, see: <https://openwallet.foundation/> 


# operational circumstances<a id="operational-circumstances"></a>

In the context of privacy protection, this term denotes the context in which privacy trade-off decisions are made. It includes the regulatory environment and other non-technical factors that bear on what reasonable privacy expectations might be.

Source: [PEMC IGR](https://kantarainitiative.org/download/pemc-implementors-guidance-report/)


# optional<a id="optional"></a>

A [requirement](#requirement) that is not [mandatory](#mandatory) or [recommended](#recommended) to implement in order for an implementer to be in [compliance](#compliance), but which is left to the implementer’s choice. In [ToIP governance frameworks](#toip-governance-framework), an optional [requirement](#requirement) is expressed using a MAY or OPTIONAL keyword as defined in IETF RFC 2119.

See also: [mandatory](#mandatory), [recommended](#recommended).

For more information, see: <https://www.rfc-editor.org/rfc/rfc2119>.


# organization<a id="organization"></a>

A [party](#party) that consists of a group of [parties](#party) who agree to be organized into a specific form in order to better achieve a common set of [objectives](#objective). Examples include corporations, partnerships, sole proprietorships, non-profit organizations, associations, and governments.

See also: [legal entity](#legal-entity), [legal person](#legal-person).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#organization): a [party](https://essif-lab.github.io/framework/docs/terms/party) that is capable of setting [objectives](https://essif-lab.github.io/framework/docs/terms/objective) and making sure these are realized by [actors](https://essif-lab.github.io/framework/docs/terms/actor) that it has [onboarded](https://essif-lab.github.io/framework/docs/terms/onboarding) and/or by (vetted) [parties](https://essif-lab.github.io/framework/docs/terms/party) that are committed to contribute to these [objectives](https://essif-lab.github.io/framework/docs/terms/objective).


# organizational authority<a id="organizational-authority"></a>

A type of [authority](#authority) where the [party](https://essif-lab.github.io/framework/docs/terms/party) asserting its right is an [organization](#organization).


# out-of-band introduction<a id="out-of-band-introduction"></a>

A process by which two or more [entities](#entity) exchange [VIDs](#vid) in order to form a [cryptographically verifiable](#cryptographically-verifiable) [connection](#connection) (e.g., a [ToIP connection](#toip-connection)), such as by scanning a [QR code](#qr-code) (in person or remotely) or clicking a [deep link](#deep-link).

Also known as: [OOBI](#oobi).


# owner (of an entity)<a id="owner-of-an-entity"></a>

The [role](#role) that a [party](#party) performs when it is exercising its legal, rightful or natural title to control a specific [entity](#entity).

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#owner).

See also: [controller](#controller-of-a-key-vault-wallet-agent-or-device).


# P2P<a id="p2p"></a>

See: [peer-to-peer](#peer-to-peer).


# party<a id="party"></a>

An [entity](#entity) that sets its [objectives](#objective), maintains its [knowledge](#knowledge), and uses that [knowledge](#knowledge) to pursue its [objectives](#objective) in an autonomous (sovereign) manner. Humans and [organizations](#organization) are the typical examples.

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary).

See also: [first party](#first-party), [second party](#second-party), [third party](#third-party), [natural person](#natural-person)


# password<a id="password"></a>

A string of characters (letters, numbers and other symbols) that are used to authenticate an identity, verify access authorization or derive cryptographic keys.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/password).

See also: [complex password](#complex-password).


# peer<a id="peer"></a>

In the context of digital networks, an [actor](#actor) on the network that has the same status, privileges, and communications options as the other actors on the network.

See also: [peer-to-peer](#peer-to-peer).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#peer-actor): the [actor](https://essif-lab.github.io/framework/docs/terms/actor) with whom/which this other [actor](https://essif-lab.github.io/framework/docs/terms/actor) is communicating in that [communication session](https://essif-lab.github.io/framework/docs/terms/communication-session).


# peer-to-peer<a id="peer-to-peer"></a>

Peer-to-peer (P2P) computing or networking is a distributed application architecture that partitions tasks or workloads between [peers](#peer). [Peers](#peer) are equally privileged, equipotent participants in the network. This forms a peer-to-peer network of [nodes](#node).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Peer-to-peer).


# permission<a id="permission"></a>

[Authorization](#authorization) to perform some [action](#action) on a system.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/permission).


# persistent connection<a id="persistent-connection"></a>

A [connection](#connection) that is able to persist across multiple [communication sessions](#communication-session). In a ToIP context, a persistent connection is established when two [ToIP endpoints](#ToIP-endpoint) exchange [verifiable identifiers](#verifiable-identifier) that they can use to re-establish the [connection](#connection) with each other whenever it is needed.

Contrast with: [ephemeral connection](#ephemeral-connection).


# personal data<a id="personal-data"></a>

Any information relating to an identified or identifiable [natural person](#natural-person) (called a [data subject](#data-subject) under [GDPR](#gdpr)).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/personal_data).


# personal data store<a id="personal-data-store"></a>

See: [personal data vault](#personal-data-vault).

Note: In the market, the term “personal data store” has also been used to generally mean a combination of the functions of a personal [digital agent](#digital-agent), [personal wallet](#personal-wallet), and [personal data vault](#personal-data-vault).


# personal data vault<a id="personal-data-vault"></a>

A [digital vault](#digital-vault) whose [controller](#controller-of-a-key-vault-wallet-agent-or-device) is a [natural person](#natural-person).


# personal wallet<a id="personal-wallet"></a>

A [digital wallet](#digital-wallet) whose [holder](#holder-of-a-claim-or-credential) is a [natural person](#natural-person).

Contrast with: [enterprise wallet](#enterprise-wallet).


# personally identifiable information<a id="personally-identifiable-information"></a>

Information (any form of [data](#data)) that can be used to directly or indirectly [identify](#identity) or re-identify an individual person either singly or in combination within a single [record](#record) or in correlation with other [records](#record). This information can be one or more [attributes](#attribute)/fields/[properties](#property) in a [record](#record) (e.g., date-of-birth) or one or more [records](#record) (e.g., medical records).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/personally_identifiable_information)

Also known as: [PII](#pii).

See also: [personal data](#personal-data), [sensitive data](#sensitive-data).


# physical credential<a id="physical-credential"></a>

A [credential](#credential) in a physical form such as paper, plastic, or metal.

Contrast with: [digital credential](#digital-credential).


# PII<a id="pii"></a>

See: [personally identifiable information](#personally-identifiable-information).


# PKI<a id="pki"></a>

See: [public key infrastructure](#public-key-infrastructure).


# plaintext<a id="plaintext"></a>

Unencrypted information that may be input to an [encryption](#encryption) operation. Once encrypted, it becomes [ciphertext](#ciphertext).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/plaintext).


# policy<a id="policy"></a>

Statements, rules or assertions that specify the correct or expected behavior of an entity. For example, an [authorization](#authorization) policy might specify the correct [access control](#access-control) rules for a software component. Policies may be [human-readable](#human-readable) or [machine-readable](#machine-readable) or both.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/policy)

See also: [governance framework](#governance-framework), [governance requirement](#governance-requirement), [rule](#rule).


# PoP<a id="pop"></a>

See: [proof of personhood](#proof-of-personhood).


# presentation<a id="presentation"></a>

A [verifiable](#verifiable) [message](#message) that a [holder](#holder-of-a-claim-or-credential) may send to a [verifier](#verifier-of-a-claim-or-credential) containing [proofs](#proof) of one or more [claims](#claim) derived from one or more [digital credentials](#digital-credential) from one or more [issuers](#issuer-of-a-claim-or-credential) as a response to a specific [presentation request](#presentation-request) from a  [verifier](#verifier-of-a-claim-or-credential).

Supporting definitions: 

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/terms/presentation): A (signed) digital [message](#message) that a [holder](#holder-of-a-claim-or-credential) component may send to a [verifier](#verifier-of-a-claim-or-credential) component that contains [data](#data) derived from one or more [verifiable credentials](#verifiable-credential) (that (a [colleague](https://essif-lab.github.io/framework/docs/terms/colleague) component of) the [holder](https://essif-lab.github.io/framework/docs/terms/holder) component has received from [issuer](https://essif-lab.github.io/framework/docs/terms/issuer) components of one or more [parties](https://essif-lab.github.io/framework/docs/terms/party)), as a response to a specific [presentation request](#presentation-request) of a  [verifier ](#verifier-of-a-claim-or-credential)component.


# presentation attack<a id="presentation-attack"></a>

A type of cybersecurity attack in which the attacker attempts to defeat a [biometric](#biometric) [liveness detection](#liveness-detection) system by providing false inputs.

Supporting definitions:

[NIST-CSRC](https://csrc.nist.gov/glossary/term/presentation_attack): Presentation to the biometric data capture subsystem with the goal of interfering with the operation of the biometric system.


# presentation request<a id="presentation-request"></a>

A protocol request sent by the [verifier](#verifier-of-a-claim-or-credential) to the [holder](#holder-of-a-claim-or-credential) of a [digital wallet](#digital-wallet) to request a [presentation](#presentation).

See also: [issuance request](#issuance-request).


# primary document<a id="primary-document"></a>

The [governance document](#governance-document) at the root of a [governance framework](#governance-framework). The primary document specifies the other [controlled documents](#controlled-document) in the governance framework.


# principal<a id="principal"></a>

The [party](https://essif-lab.github.io/framework/docs/terms/party) for whom, or on behalf of whom, an [actor](https://essif-lab.github.io/framework/docs/terms/actor) is executing an [action](https://essif-lab.github.io/framework/docs/terms/action) (this [actor](https://essif-lab.github.io/framework/docs/terms/actor) is then called an [agent](https://essif-lab.github.io/framework/docs/terms/agent) of that [party](https://essif-lab.github.io/framework/docs/terms/party)).

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#principal)


# Principles of SSI<a id="principles-of-ssi"></a>

A set of principles for [self-sovereign identity](#self-sovereign-identity) systems originally defined by the Sovrin Foundation and republished by the [ToIP Foundation](#toip-foundation).

For more information, see: <https://sovrin.org/principles-of-ssi/> and <https://trustoverip.org/wp-content/uploads/2021/10/ToIP-Principles-of-SSI.pdf> 


# privacy policy<a id="privacy-policy"></a>

A statement or legal document (in privacy law) that discloses some or all of the ways a [party](#party) gathers, uses, discloses, and manages a customer or client's [data.](#data)

Source: [Wikipedia](https://en.wikipedia.org/wiki/Privacy_policy)

See also: [security policy](#security-policy).


# private key<a id="private-key"></a>

In [public key cryptography](#public-key-cryptography), the [cryptographic key](#cryptographic-key) which must be kept secret by the [controller](#controller-of-a-key-vault-wallet-agent-or-device) in order to maintain security.

Supporting definitions:

[NIST-CSRC](https://csrc.nist.gov/glossary/term/private_key): The secret part of an asymmetric key pair that is typically used to digitally sign or decrypt data.


# proof<a id="proof"></a>

A digital object that enables [cryptographic verification](#cryptographic-verifiability) of either: a) the [claims](#claim) from one or more [digital credentials](#digital-credential), or b) facts about [claims](#claim) that do not reveal the [data ](#data) itself (e.g., proof of the [subject](#subject) being over/under a specific age without revealing a birthdate).

See also: [zero-knowledge proof](#zero-knowledge-proof).


# proof of control<a id="proof-of-control"></a>

See: [proof of possession](#proof-of-possession).


# proof of personhood<a id="proof-of-personhood"></a>

Proof of personhood (PoP) is a means of resisting malicious attacks on [peer-to-peer](#peer-to-peer) networks, particularly, attacks that utilize multiple fake [identities](#identity), otherwise known as a [Sybil attack](#sybil-attack). Decentralized online platforms are particularly vulnerable to such attacks by their very nature, as notionally democratic and responsive to large voting blocks. In PoP, each unique human participant obtains one equal unit of voting power, and any associated rewards.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Proof_of_personhood).

Also known as: [PoP](#pop).


# proof of possession<a id="proof-of-possession"></a>

A [verification](#verification) process whereby a [level of assurance](#level-of-assurance) is obtained that the owner of a [key pair](#cryptographic-key) actually controls the [private key](#private-key) associated with the [public key](#public-key).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/proof_of_possession).


# proof of presence<a id="proof-of-presence"></a>

See: [liveness detection](#liveness-detection).


# property<a id="property"></a>

In the context of digital communication, an [attribute](#attribute) of a digital object or [data](#data) structure, such as a [DID document](#did-document) or a [schema](#schema).

See also: [attribute](#attribute), [claim](#claim).


# protected data<a id="protected-data"></a>

[Data](#data) that is not publicly available but requires some type of [access control](#access-control) to gain access.


# protocol layer<a id="protocol-layer"></a>

In modern protocol design, protocols are layered to form a [protocol stack](#protocol-stack). Layering is a design principle that divides the protocol design task into smaller steps, each of which accomplishes a specific part, interacting with the other parts of the protocol only in a small number of well-defined ways. Layering allows the parts of a protocol to be designed and tested without a combinatorial explosion of cases, keeping each design relatively simple.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Communication_protocol#Layering).

See also: [hourglass model](#hourglass-model), [ToIP stack](#toip-stack).


# protocol stack<a id="protocol-stack"></a>

The protocol stack or network stack is an implementation of a computer networking protocol suite or protocol family. Some of these terms are used interchangeably but strictly speaking, the _suite_ is the definition of the communication protocols, and the _stack_ is the software implementation of them.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Protocol_stack)

See also: [protocol layer](#protocol-layer).


# pseudonym<a id="pseudonym"></a>

A pseudonym is a fictitious name that a [person](#natural-person) assumes for a particular purpose, which differs from their original or true name (orthonym). This also differs from a new name that entirely or legally replaces an individual's own. Many pseudonym [holders](#holder-of-a-claim-or-credential) use pseudonyms because they wish to remain [anonymous](#anonymous), but anonymity is difficult to achieve and often fraught with legal issues.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Pseudonym).


# public key<a id="public-key"></a>

[Drummond Reed](mailto:drummond.reed@avast.com): In [public key cryptography](#public-key-cryptography), the [cryptographic key](#cryptographic-key) that can be freely shared with anyone by the [controller](#controller-of-a-key-vault-wallet-agent-or-device) without compromising security. A [party’s](#party) public key must be verified as [authoritative](#authority) in order to verify their [digital signature](#digital-signature).

Supporting definitions:

[NIST-CSRC](https://csrc.nist.gov/glossary/term/public_key): The public part of an asymmetric key pair that is typically used to verify signatures or encrypt data.


# public key certificate<a id="public-key-certificate"></a>

A set of [data](#data) that uniquely identifies a [public key](#public-key) (which has a corresponding [private key](#private-key)) and an [owner](#owner-of-an-entity) that is authorized to use the [key pair](#cryptographic-key). The certificate contains the owner’s [public key](#public-key) and possibly other information and is [digitally signed](#digital-signature) by a [certification authority](#certification-authority) (i.e., a trusted [party](#party)), thereby binding the [public key](#public-key) to the [owner](#owner-of-an-entity).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/public_key_certificate).

See also: [public key infrastructure](#public-key-infrastructure).

Supporting definitions:

Wikipedia : In [cryptography](https://en.wikipedia.org/wiki/Cryptography), a public key certificate, also known as a digital certificate or identity certificate, is an [electronic document](https://en.wikipedia.org/wiki/Electronic_document) used to prove the validity of a [public key](https://en.wikipedia.org/wiki/Key_authentication). The certificate includes information about the key, information about the identity of its owner (called the subject), and the [digital signature](https://en.wikipedia.org/wiki/Digital_signature) of an entity that has verified the certificate's contents (called the issuer). If the signature is valid, and the software examining the certificate trusts the issuer, then it can use that key to communicate securely with the certificate's subject. In [email encryption](https://en.wikipedia.org/wiki/Email_encryption), [code signing](https://en.wikipedia.org/wiki/Code_signing), and [e-signature](https://en.wikipedia.org/wiki/Electronic_signature) systems, a certificate's subject is typically a person or organization. However, in [Transport Layer Security](https://en.wikipedia.org/wiki/Transport_Layer_Security) (TLS) a certificate's subject is typically a computer or other device, though TLS certificates may identify organizations or individuals in addition to their core role in identifying devices.


# public key cryptography<a id="public-key-cryptography"></a>

Public key cryptography, or asymmetric cryptography, is the field of cryptographic systems that use pairs of related [keys](#cryptographic-key). Each key pair consists of a [public key](#public-key) and a corresponding [private key](#private-key). [Key pairs](#cryptographic-key) are generated with cryptographic algorithms based on mathematical problems termed one-way functions. Security of public key cryptography depends on keeping the [private key](#private-key) secret; the [public key](#public-key) can be openly distributed without compromising security.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Public-key_cryptography).

See also: [public key infrastructure](#public-key-infrastructure).


# public key infrastructure<a id="public-key-infrastructure"></a>

A set of policies, processes, server platforms, software and workstations used for the purpose of administering [certificates](#public-key-certificate) and [public-private key pairs](#public-key-cryptography), including the ability to [issue](#issuer-of-a-claim-or-credential), maintain, and [revoke](#revocation) [public key certificates](#public-key-certificate). The PKI includes the hierarchy of [certificate authorities](#certificate-authority) that allow for the deployment of [digital certificates](#digital-certificate) that support [encryption](#encryption), [digital signature](#digital-signature) and [authentication](#authenticator-of-an-entity) to meet business and security requirements.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/public_key_infrastructure).

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Public_key_infrastructure): A public key infrastructure (PKI) is a set of roles, policies, hardware, software and procedures needed to create, manage, distribute, use, store and revoke [digital certificates](https://en.wikipedia.org/wiki/Public_key_certificate) and manage [public-key encryption](https://en.wikipedia.org/wiki/Public-key_cryptography). The purpose of a PKI is to facilitate the secure electronic transfer of information for a range of network activities such as e-commerce, internet banking and confidential email.


# QR code<a id="qr-code"></a>

A QR code (short for "quick-response code") is a type of two-dimensional matrix barcode—a [machine-readable](#machine-readable) optical image that contains information specific to the identified item. In practice, QR codes contain data for a locator, an identifier, and web tracking.

Source: [Wikipedia](https://en.wikipedia.org/wiki/QR_code).

See also: [out-of-band introduction](#out-of-band-introduction).


# RBAC<a id="rbac"></a>

See: [role-based access control](#role-based-access-control).


# real world identity<a id="real-world-identity"></a>

A term used to describe the opposite of [digital identity](#digital-identity), i.e., an identity (typically for a person) in the physical instead of the digital world.

Also known as: [RWI](#rwi).

See also: [legal identity](#legal-identity).


# recommended<a id="recommended"></a>

A [requirement](#requirement) that is not [mandatory](#mandatory) to implement in order for an implementer to be in [compliance](#compliance), but which should be implemented unless the implementer has a good reason. In [ToIP governance frameworks](#toip-governance-framework), a recommendation is expressed using a SHOULD or RECOMMENDED keyword as defined in IETF RFC 2119.

See also: [mandatory](#mandatory), [optional](#optional).

For more information, see: <https://www.rfc-editor.org/rfc/rfc2119>.


# record<a id="record"></a>

A uniquely identifiable entry or listing in a database or [registry](#registry).


# registrant<a id="registrant"></a>

The [party](#party) submitting a [registration](#registration) [record](#record) to a [registry](#registry).


# registrar<a id="registrar"></a>

The [party](#party) who performs [registration](#registration) on behalf of a [registrant](#registrant).


# registration<a id="registration"></a>

The process by which a [registrant](#registrant) submits a [record](#record) to a [registry](#registry).

registration agent

A [party](#party) responsible for accepting [registration](#registration) requests and [authenticating](authentication-of-a-user-process-or-device) the [entity](#entity) making the request. The term may also apply to a [party](#party) accepting [issuance](#issuance) requests for [digital credentials](#digital-credential).


# registry<a id="registry"></a>

A specialized database of [records](#record) that serves as an [authoritative source](#authoritative-source) of information about [entities](#entity).

See also: [trust registry](#trust-registry).


# relationship context<a id="relationship-context"></a>

A context established within the boundary of a [trust relationship](#trust-relationship).


# relying party<a id="relying-party"></a>

A [party](#party) who consumes [claims](#claim) or [trust graphs](#trust-graph) from other [parties](#party) (such as [issuers](#issuer-of-a-claim-or-credential), [holders](#holder-of-a-claim-or-credential), and [trust registries](#trust-registry)) in order to make a [trust decision](#trust-decision).

See also: [verifier](#verifier-of-a-claim-or-credential).

Note: The term “relying party” is more commonly used in [federated identity](#federated-identity) architecture; the term “verifier” is more commonly used with [decentralized identity](#decentralized-identity) architecture and [verifiable credentials](#verifiable-credential).


# reputation<a id="reputation"></a>

The reputation or prestige of a social entity (a [person](#natural-person), a social group, an [organization](#organization), or a place) is an opinion about that entity – typically developed as a result of social evaluation on a set of criteria, such as behavior or performance.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Reputation).


# reputation graph<a id="reputation-graph"></a>

A graph of the [reputation](#reputation) relationships between different entities in a [trust community](#trust-community). In a [digital trust ecosystem](#digital-trust-ecosystem), the [governing body](#governing-body) may be one [trust root](#trust-root) of a reputation graph. In some cases, a reputation graph can be traversed by making queries to one or more [trust registries](#trust-registry).

See also: [authorization graph](#authorization-graph), [governance graph](#governance-graph), [trust graph](#trust-graph).


# reputation system<a id="reputation-system"></a>

Reputation systems are programs or algorithms that allow users to rate each other in online communities in order to build [trust](#trust) through [reputation](#reputation). Some common uses of these systems can be found on e-commerce websites such as eBay, Amazon.com, and Etsy as well as online advice communities such as Stack Exchange.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Reputation_system).


# requirement<a id="requirement"></a>

A specified condition or behavior to which a system needs to [comply](#compliance). [Technical requirements](#technical-requirement) are defined in [technical specifications](#technical-specification) and implemented in computer systems to be executed by software [actors](#actor). [Governance requirements](#governance-requirement) are defined in [governance documents](#governance-document) that specify [policies](#policy) and procedures to be executed by human [actors](#actor). In ToIP architecture, requirements are expressed using the keywords defined in Internet RFC 2119.

See also: [mandatory](#mandatory), [recommended](#recommended), [optional](#optional).

For more information, see: <https://www.rfc-editor.org/rfc/rfc2119>.


# revocation<a id="revocation"></a>

In the context of [digital credentials](#digital-credential), revocation is an event signifying that the [issuer](#issuer-of-a-claim-or-credential) no longer attests to the [validity](#validation) of a [credential](#digital-credential) they have [issued](#issuer-of-a-claim-or-credential). In the context of cryptographic keys, revocation is an event signifying that the [controller](#controller-of-a-key-vault-wallet-agent-or-device) no longer attests to the [validity](#validation) of a public/private key pair for which the [controller](#controller-of-a-key-vault-wallet-agent-or-device) is [authoritative](#authority).

See also: [issuance](#issuance), [presentation](#presentation).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#revokerevocation): the act, by or on behalf of the [party](https://essif-lab.github.io/framework/docs/terms/party) that has issued the [credential](https://essif-lab.github.io/framework/docs/terms/credential), of no longer vouching for the correctness or any other qualification of (arbitrary parts of) that [credential](https://essif-lab.github.io/framework/docs/terms/credential).

[NIST-CSRC](https://csrc.nist.gov/glossary/term/revocation): **​​For digital certificates**: The process of permanently ending the binding between a certificate and the identity asserted in the certificate from a specified time forward. **For cryptographic keys**: A process whereby a notice is made available to affected entities that keys should be removed from operational use prior to the end of the established cryptoperiod of those keys.


# risk<a id="risk"></a>

The effects that uncertainty (i.e. a lack of information, understanding or [knowledge](#knowledge) of events, their consequences or likelihoods) can have on the intended realization of an [objective ](#objective)of a [party](#party).

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary)

Supporting definitions: 

[NIST-CSRC](https://csrc.nist.gov/glossary/term/risk): A measure of the extent to which an entity is threatened by a potential circumstance or event, and typically a function of: (i) the adverse impacts that would arise if the circumstance or event occurs; and (ii) the likelihood of occurrence.


# risk assessment<a id="risk-assessment"></a>

The process of identifying [risks](#risk) to organizational operations (including mission, functions, image, reputation), organizational assets, individuals, other [organizations](#organization), and the overall [ecosystem](#digital-trust-ecosystem), resulting from the operation of an information system. Risk assessment is part of [risk management](#risk-management), incorporates threat and vulnerability analyses, and considers [risk mitigations](#risk-mitigation) provided by security controls planned or in place.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/risk_assessment).

Also known as: risk analysis.

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Risk_assessment): Risk assessment determines possible mishaps, their likelihood and consequences, and the [tolerances](https://en.wikipedia.org/wiki/Engineering_tolerance) for such events.[<sup>\[1\]</sup>](https://en.wikipedia.org/wiki/Risk_assessment#cite_note-RausandRisk13-1) The results of this process may be expressed in a [quantitative](https://en.wikipedia.org/wiki/Quantitative_property) or [qualitative](https://en.wikipedia.org/wiki/Qualitative_data) fashion. Risk assessment is an inherent part of a broader [risk management](https://en.wikipedia.org/wiki/Risk_management) strategy to help reduce any potential risk-related consequences. More precisely, risk assessment identifies and analyses potential (future) events that may negatively impact individuals, assets, and/or the environment (i.e. [hazard analysis](https://en.wikipedia.org/wiki/Hazard_analysis)). It also makes judgments "on the [tolerability](https://en.wikipedia.org/wiki/Tolerability) of the risk on the basis of a risk analysis" while considering influencing factors (i.e. risk evaluation).


# risk decision<a id="risk-decision"></a>

See: [trust decision](#trust-decision).


# risk management<a id="risk-management"></a>

The process of managing [risks](#risk) to organizational operations (including mission, functions, image, or reputation), organizational assets, or individuals resulting from the operation of an information system, and includes: (i) the conduct of a [risk assessment](#risk-assessment); (ii) the implementation of a [risk mitigation](#risk-mitigation) strategy; and (iii) employment of techniques and procedures for the continuous monitoring of the security state of the information system.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/risk_management).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#risk-management): a process that is run by (or on behalf of) a specific [party](https://essif-lab.github.io/framework/docs/terms/party) for the purpose of [managing](https://essif-lab.github.io/framework/docs/terms/management) the [risks](https://essif-lab.github.io/framework/docs/terms/risk) that it [owns](https://essif-lab.github.io/framework/docs/terms/owner) (thereby realizing specific [risk objectives](https://essif-lab.github.io/framework/docs/terms/risk-objective)).

[Wikipedia](https://en.wikipedia.org/wiki/Risk_management): Risk management is the identification, evaluation, and prioritization of [risks](https://en.wikipedia.org/wiki/Risk) (defined in [ISO 31000](https://en.wikipedia.org/wiki/ISO_31000) as the effect of uncertainty on objectives) followed by coordinated and economical application of resources to minimize, monitor, and control the probability or impact of unfortunate events or to maximize the realization of opportunities.


# risk mitigation<a id="risk-mitigation"></a>

Prioritizing, evaluating, and implementing the appropriate [risk](#risk)-reducing controls/countermeasures recommended from the [risk management](#risk-management) process.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/risk_mitigation).


# role<a id="role"></a>

A defined set of characteristics that an [entity](#entity) has in some context, such as responsibilities it may have, [actions](#action) (behaviors) it may execute, or pieces of [knowledge](#knowledge) that it is expected to have in that context, which are referenced by a specific role name.

Source: [eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#role).

See also: [role credential](#role-credential).


# role-based access control<a id="role-based-access-control"></a>

[Access control](#access-control) based on user [roles](#role) (i.e., a collection of access [authorizations](#authorization) a user receives based on an explicit or implicit assumption of a given [role](#role)). [Role](#role) [permissions](#permission) may be inherited through a [role](#role) hierarchy and typically reflect the [permissions](#permission) needed to perform defined functions within an [organization](#organization). A given [role](#role) may apply to a single individual or to several individuals.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/role_based_access_control).

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/Role-based_access_control): In computer systems security, role-based access control (RBAC) or role-based security is an approach to restricting system access to authorized users, and to implementing [mandatory access control](https://en.wikipedia.org/wiki/Mandatory_access_control) (MAC) or [discretionary access control](https://en.wikipedia.org/wiki/Discretionary_access_control) (DAC).


# role credential<a id="role-credential"></a>

A [credential](#credential) [claiming](#claim) that the [subject](#subject) has a specific [role](#role).


# router<a id="router"></a>

A router is a networking device that forwards [data packets](#data-packet) between computer networks. Routers perform the traffic directing functions between networks and on the global Internet. Data sent through a network, such as a web page or email, is in the form of [data packets](#data-packet). A packet is typically forwarded from one router to another router through the networks that constitute an internetwork (e.g. the Internet) until it reaches its destination [node](#node). This process is called [routing](#routing).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Router_\(computing\)).


# routing<a id="routing"></a>

Routing is the process of selecting a path for traffic in a network or between or across multiple networks. Broadly, routing is performed in many types of networks, including circuit-switched networks, such as the public switched telephone network (PSTN), and computer networks, such as the Internet. A [router](#router) is a computing device that specializes in performing routing.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Routing).


# rule<a id="rule"></a>

A prescribed guide for conduct, process or [action](#action) to achieve a defined result or [objective](#objective). Rules may be [human-readable](#human-readable) or [machine-readable](#machine-readable) or both.

See also: [governance framework](#governance-framework), [policy](#policy).


# RWI<a id="rwi"></a>

See: [real world identity](#real-world-identity).


# schema<a id="schema"></a>

A framework, pattern, or set of [rules](#rule) for enforcing a specific structure on a digital object or a set of digital [data](#data). There are many types of schemas, e.g., data schema, credential verification schema, database schema.

For more information, see: W3C [Data Schemas](https://www.w3.org/TR/vc-data-model/#data-schemas).

Note: `credentialSchema `is a Property Definition in the [W3C VC Data Model, see 3.2.1](https://www.w3.org/2018/credentials/#credentialSchema)


# scope<a id="scope"></a>

In the context of [terminology](#terminology), scope refers to the set of possible [concepts](#concept) within which: a) a specific [term](#term) is intended to uniquely identify a [concept](#concept), or b) a specific [glossary](#glossary) is intended to identify a set of [concepts](#concept). In the context of [identification](#identification), scope refers to the set of possible entities within which a specific entity must be uniquely identified. In the context of [specifications](#specification), scope refers to the set of problems (the problem space) within which the specification is intended to specify solutions.

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#scope): the extent of the area or subject matter (which we use, e.g., to define [pattern](https://essif-lab.github.io/framework/docs/@), [concept](https://essif-lab.github.io/framework/docs/@), [term](https://essif-lab.github.io/framework/docs/@) and [glossaries](https://essif-lab.github.io/framework/docs/@) in, but it serves other purposes as well).


# SCID<a id="scid"></a>

See: [self-certifying identifier](#self-certifying-identifier).

# second party<a id="second-party"></a>

The [party](#party) with whom a [first party](#first-party) engages to form a [trust relationship](#trust-relationship), establish a [connection](#connection), or execute a [transaction](#transaction).

See also: [third party](#third-party).


# Secure Enclave<a id="secure-enclave"></a>

A coprocessor on Apple iOS devices that serves as a [trusted execution environment](#trusted-execution-environment).


# secure multi-party computation<a id="secure-multi-party-computation"></a>

See: [multi-party computation](#multi-party-computation).


# Secure Sockets Layer<a id="secure-sockets-layer"></a>

The original transport layer security protocol developed by Netscape and partners. Now deprecated in favor of [Transport Layer Security](#transport-layer-security) (TLS).

Also known as: [SSL](#ssl).


# security domain<a id="security-domain"></a>

An environment or context that includes a set of system resources and a set of system entities that have the right to access the resources as defined by a common [security policy](#security-policy), security model, or security architecture.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/domain)

See also: [trust domain](#trust-domain).


# security policy<a id="security-policy"></a>

A set of [policies](#policy) and [rules](#rule) that governs all aspects of security-relevant system and system element behavior.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/security_policy)

See also: [privacy policy](#privacy-policy).


# self-asserted<a id="self-asserted"></a>

A term used to describe a [claim](#claim) or a [credential](#credential) whose [subject](#subject) is also the [issuer](#issuer-of-a-claim-or-credential).


# self-certified<a id="self-certified"></a>

When a [party](#party) provides its own [certification](#certification-of-a-party) that it is [compliant](#compliance) with a set of [requirements](#requirement), such as a [governance framework](#governance-framework).


# self-certifying identifier<a id="self-certifying-identifier"></a>

A subclass of [verifiable identifier](#verifiable-identifier) that is [cryptographically verifiable](#cryptographically-verifiable) without the need to rely on any [third party](#third-party) for [verification](#verification) because the [identifier](#identifier) is cryptographically bound to the [cryptographic keys](#cryptographic-key) from which it was generated.

See also: [autonomic identifier](#autonomic-identifier).

Also known as: [SCID](#scid).

# self-sovereign identity<a id="self-sovereign-identity"></a>

A [decentralized identity](#decentralized-identity) architecture that implements the [Principles of SSI](#principles-of-ssi).

See also: [federated identity](#federated-identity).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#ssi-self-sovereign-identity): SSI (Self-Sovereign Identity) is a term that has many different interpretations, and that we use to refer to concepts/ideas, architectures, processes and technologies that aim to support (autonomous) [parties](https://essif-lab.github.io/framework/docs/terms/party) as they negotiate and execute electronic [transactions](https://essif-lab.github.io/framework/docs/terms/transaction) with one another.

[Wikipedia](https://en.wikipedia.org/wiki/Self-sovereign_identity): Self-sovereign identity (SSI) is an approach to [digital identity](https://en.wikipedia.org/wiki/Digital_identity) that gives individuals control over the information they use to prove who they are to [websites](https://en.wikipedia.org/wiki/Website), services, and [applications](https://en.wikipedia.org/wiki/Application_software) across the web. Without SSI, individuals with persistent accounts (identities) across the [internet](https://en.wikipedia.org/wiki/Internet) must rely on a number of large identity providers, such as [Facebook](https://en.wikipedia.org/wiki/Facebook) (Facebook Connect) and [Google](https://en.wikipedia.org/wiki/Google) (Google Sign-In), that have control of the information associated with their identity.


# sensitive data<a id="sensitive-data"></a>

[Personal data](#personal-data) that a reasonable [person](#natural-person) would view from a privacy protection standpoint as requiring special care above and beyond other [personal data](#personal-data).

Supporting definitions:

[PEMC IGR](https://kantarainitiative.org/download/pemc-implementors-guidance-report/): While all Personal Information may be regarded as sensitive in that an unauthorized processing of an individual’s data may be offensive to that person, we use the term here to denote information that a reasonable person would view as requiring special care above and beyond other personal data. For reference see [GDPR Recital #51](https://www.privacy-regulation.eu/en/recital-51-GDPR.htm) or [Sensitive Personal Data](https://w3c.github.io/dpv/dpv/#SensitivePersonalData) in the W3C [Data Privacy Vocabulary](https://w3id.org/dpv).


# session<a id="session"></a>

See: [communication session](#communication-session).


# sociotechnical system<a id="sociotechnical-system"></a>

An approach to complex organizational work design that recognizes the interaction between people and technology in workplaces. The term also refers to coherent systems of human relations, technical objects, and cybernetic processes that inhere to large, complex infrastructures. Social society, and its constituent substructures, qualify as complex sociotechnical systems.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Sociotechnical_system)


# software agent<a id="software-agent"></a>

In computer science, a software agent is a computer program that acts for a user or other program in a relationship of [agency](#agency), which derives from the Latin agere (to do): an agreement to act on one's behalf. A [user agent](#user-agent) is a specific type of software agent that is used directly by an end-user as the [principal](#principal).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Software_agent).

See also: [digital agent](#digital-agent).


# Sovrin Foundation<a id="sovrin-foundation"></a>

A 501 (c)(4) nonprofit organization established to administer the [governance framework](#governance-framework) governing the Sovrin Network, a public service utility enabling [self-sovereign identity](#self-sovereign-identity) on the internet. The Sovrin Foundation is an independent [organization](#organization) that is responsible for ensuring the Sovrin [identity](#identity) system is public and globally accessible.

For more information, see: <https://sovrin.org/> 


# spanning layer<a id="spanning-layer"></a>

A specific layer within a [protocol stack](#protocol-stack) that consists of a single protocol explicitly designed to provide interoperability between the [protocols layers](#protocol-layer) above it and below it.

See also: [hourglass model](#hourglass-model), [trust spanning layer](#trust-spanning-layer).

For more information, see: <https://www.isi.edu/newarch/iDOCS/final.finalreport.pdf>, National Academies of Sciences, Engineering, and Medicine. 1997. The Unpredictable Certainty: White Papers. Washington, DC: The National Academies Press. <https://doi.org/10.17226/6062>.


# specification<a id="specification"></a>

See: [technical specification](#technical-specification).


# SSI<a id="ssi"></a>

See: [self-sovereign identity](#self-sovereign-identity).

Note: In some contexts, such as academic papers or industry conferences, this acronym has started to replace the term it represents.


# SSL<a id="ssl"></a>

See: [Secure Sockets Layer](#secure-sockets-layer).


# stream<a id="stream"></a>

In the context of digital [communications](#communication), and in particular [streaming media](#streaming-media), a flow of [data](#data) delivered in a continuous manner from a server to a client rather than in discrete [messages](#message).


# streaming media<a id="streaming-media"></a>

Streaming media is multimedia for playback using an offline or online media player. Technically, the stream is delivered and consumed in a continuous manner from a client, with little or no intermediate storage in network elements. Streaming refers to the delivery method of content, rather than the content itself.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Streaming_media). 


# subject<a id="subject"></a>

The [entity](#entity) described by one or more [claims](#claim), particularly in the context of [digital credentials](#digital-credential).

Supporting definitions:

[W3C VC](https://www.w3.org/TR/vc-data-model/#terminology): A thing about which [claims](https://www.w3.org/TR/vc-data-model/#dfn-claims) are made.

[eSSIF-Lab:](https://essif-lab.github.io/framework/docs/essifLab-glossary#subject) the (single) [entity](#entity) to which a given set of coherent [data](#data) relates/pertains. Examples of such sets include attributes, [Claims](#claim)/Assertions, files/dossiers, [(verifiable) credentials](#verifiable-credential), [(partial) identities](https://essif-lab.github.io/framework/docs/terms/partial-identity), [employment contracts](https://essif-lab.github.io/framework/docs/terms/employment-contract), etc.


# subscription<a id="subscription"></a>

In the context of decentralized digital trust infrastructure, a subscription is an agreement between a first [digital agent](#digital-agent)—the publisher—to automatically send a second [digital agent](#digital-agent)—the subscriber—a [message](#message) when a specific type of event happens in the [wallet](#wallet) or [vault](#digital-vault) managed by the first [digital agent](#digital-agent).


# supporting system<a id="supporting-system"></a>

A system that operates at [ToIP Layer 1](#toip-layer-1), the [trust support layer](#trust-support-layer) of the [ToIP stack](#toip-stack). A supporting system is one of three types of systems defined in the [ToIP Technology Architecture Specification](#toip-technology-architecture-specification).

See also: [endpoint system](#endpoint-system), [intermediary system](#intermediary-system).

# Sybil attack<a id="sybil-attack"></a>

A Sybil attack is a type of attack on a computer network service in which an attacker subverts the service's [reputation system](#reputation-system) by creating a large number of [pseudonymous](#pseudonym) [identities](#identity) and uses them to gain a disproportionately large influence. It is named after the subject of the book _Sybil_, a case study of a woman diagnosed with dissociative identity disorder.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Sybil_attack).


# system of record<a id="system-of-record"></a>

A system of record (SOR) or source system of record (SSoR) is a data management term for an information storage system (commonly implemented on a computer system running a database management system) that is the [authoritative data source](#authoritative-source) for a given data element or piece of information. 

Source: [Wikipedia](https://en.wikipedia.org/wiki/System_of_record)

See also: [authoritative source](#authoritative-source), [trust registry](#trust-registry), [verifiable data registry](#verifiable-data-registry).


# tamper resistant<a id="tamper-resistant"></a>

A process which makes alterations to the [data](#data) difficult (hard to perform), costly (expensive to perform), or both.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/tamper_resistant).


# TCP<a id="tcp"></a>

See: [Transmission Control Protocol](#transmission-control-protocol).


# TCP/IP<a id="tcpip"></a>

See: [Internet Protocol Suite](#internet-protocol-suite).


# TCP/IP stack<a id="tcpip-stack"></a>

The [protocol stack](#protocol-stack) implementing the [TCP/IP](#tcpip) suite.


# technical requirement<a id="technical-requirement"></a>

A [requirement](#requirement) for a hardware or software component or system. In the context of decentralized digital trust infrastructure, technical requirements are a subset of [governance requirements](#governance-requirement). Technical requirements are often specified in a [technical specification](#technical-specification).

For more information, see: <https://datatracker.ietf.org/doc/html/rfc2119> 

Note: In ToIP architecture, both technical requirements and [governance requirements](#governance-requirement) are expressed using the keywords defined in IETF RFC 2119.


# technical specification<a id="technical-specification"></a>

A document that specifies, in a complete, precise, verifiable manner, the [requirements](#requirement), design, behavior, or other characteristics of a system or component and often the procedures for determining whether these provisions have been satisfied.

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/specification)

See also: [governance framework](#governance-framework), [governance requirement](#governance-requirement), [policy](#policy), [rule](#rule).


# technical trust<a id="technical-trust"></a>

A [level of assurance](#level-of-assurance) in a [trust relationship](#trust-relationship) that can be achieved only via technical means such as hardware, software, network [protocols](#protocol-layer), and cryptography. Cryptographic trust is a specialized type of technical trust.

Contrast with: [human trust](#human-trust).


# TEE<a id="tee"></a>

See: [trusted execution environment](#trusted-execution-environment).


# term<a id="term"></a>

A unit of text (i.e., a word or phrase) that is used in a particular context or scope to refer to a [concept](#concept) (or a relation between [concepts](#concept), or a [property](#property) of a [concept](#concept)).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#term): a word or phrase (i.e.: text) that is used in at least one [scope](https://essif-lab.github.io/framework/docs/terms/scope)/context to represent a specific [concept](https://essif-lab.github.io/framework/docs/terms/concept).

[Merriam Webster:](https://www.merriam-webster.com/dictionary/term) a word or expression that has a precise meaning in some uses or is peculiar to a science, art, profession, or subject.

Note: A term MUST NOT be confused with the concept it refers to.


# terminology<a id="terminology"></a>

Terminology is a group of specialized words and respective meanings in a particular field, and also the study of such [terms](#term) and their use; the latter meaning is also known as terminology science. A term is a word, compound word, or multi-word expressions that in specific contexts is given specific meanings—these may deviate from the meanings the same words have in other contexts and in everyday language.[<sup>\[2\]</sup>](https://en.wikipedia.org/wiki/Terminology#cite_note-2) Terminology is a discipline that studies, among other things, the development of such [terms](#term) and their interrelationships within a specialized domain. Terminology differs from lexicography, as it involves the study of [concepts](#concept), conceptual systems and their labels (terms), whereas lexicography studies words and their meanings.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Terminology).


# terms community<a id="terms-community"></a>

A group of [parties](#party) who share the need for a common [terminology](#terminology).

See also: [trust community](#trust-community).


# terms wiki<a id="terms-wiki"></a>

A wiki website used by a [terms community](#terms-community) to input, maintain, and publish its [terminology](#terminology). The ToIP Foundation Concepts and Terminology Working Group has established a simple template for GitHub-based terms wikis.


# thing<a id="thing"></a>

An [entity](#entity) that is neither a [natural person](#natural-person) nor an [organization](#organization) and thus cannot be a [party](#party). A thing may be a [natural thing](#natural-thing) or a [man-made thing](#man-made-thing).


# third party<a id="third-party"></a>

A [party](#party) that is not directly involved in the trust relationship between a [first party](#first-party) and a [second party](#second-party), but provides supporting services to either or both of them.


# three party model<a id="three-party-model"></a>

The issuer—holder—verifier model used by all types of [physical credentials](#physical-credential) and [digital credentials](#digital-credential) to enable [transitive trust decisions](#transitive-trust-decision).

Also known as: [trust triangle](#trust-triangle).


# timestamp<a id="timestamp"></a>

A token or packet of information that is used to provide assurance of timeliness; the timestamp contains timestamped data, including a time, and a signature generated by a [trusted timestamp authority](#trusted-timestamp-authority) (TTA).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/timestamp).

Supporting definitions:

[TechTarget](https://www.techtarget.com/whatis/definition/timestamp#:~:text=A%20timestamp%20is%20the%20current,minute%20fractions%20of%20a%20second.): A timestamp is the current time of an event that a computer records. Through mechanisms, such as the [Network Time Protocol](https://www.techtarget.com/searchnetworking/definition/Network-Time-Protocol), a computer maintains accurate current time, calibrated to minute fractions of a second. Such precision makes it possible for networked computers and applications to communicate effectively.


# TLS<a id="tls"></a>

See: [Transport Layer Security](#transport-layer-security).


# ToIP<a id="toip"></a>

See: Trust Over IP


# ToIP application<a id="toip-application"></a>

A [trust application](#trust-application) that runs at [ToIP Layer 4](#toip-layer-4), the [trust application layer](#trust-application-layer).


# ToIP channel<a id="toip-channel"></a>

See: VID relationship.


# ToIP communication<a id="toip-communication"></a>

[Communication](#communication) that uses the [ToIP stack](#toip-stack) to deliver [ToIP messages](#toip-message) between [ToIP endpoints](#ToIP-endpoint), optionally using [ToIP intermediaries](https://docs.google.com/document/d/1fZByfuSOwszDRkE7ARQLeElSYmVznoOyJK4sxRvJpyM/edit#heading=h.hcobm4uk16ff), to provide [authenticity](#authenticity), [confidentiality](#confidentiality), and [correlation privacy](#correlation-privacy).


# ToIP connection<a id="toip-connection"></a>

A [connection](#connection) formed using the [ToIP Trust Spanning Protocol](#toip-trust-spanning-protocol) between two [ToIP endpoints](#ToIP-endpoint) identified with [verifiable identifiers](#verifiable-identifier). A ToIP connection is instantiated as one or more [VID relationships](#vid-relationship).


# ToIP controller<a id="toip-controller"></a>

The [controller](#controller-of-a-key-vault-wallet-agent-or-device) of a [ToIP identifier](#toip-identifier).


# ToIP Foundation<a id="toip-foundation"></a>

A non-profit project of the [Linux Foundation](https://www.linuxfoundation.org/) chartered to define an overall architecture for decentralized digital trust infrastructure known as the [ToIP stack](#toip-stack). 

See also: [Decentralized Identity Foundation](#decentralized-identity-foundation), [OpenWallet Foundation](#openwallet-foundation).

For more information, see: <https://trustoverip.org/>.


# ToIP endpoint<a id="toip-endpoint"></a>

An [endpoint](#endpoint) that communicates via the [ToIP Trust Spanning Protocol](#toip-trust-spanning-protocol) as described in the [ToIP Technology Architecture Specification](#toip-technology-architecture-specification).


# ToIP Governance Architecture Specification<a id="toip-governance-architecture-specification"></a>

The specification defining the [requirements](#requirement) for the [ToIP Governance Stack](#toip-governance-stack) published by the [ToIP Foundation](#toip-foundation).

For more information, see: <https://trustoverip.org/our-work/deliverables/>.


# ToIP governance framework<a id="toip-governance-framework"></a>

A [governance framework](#governance-framework) that conforms to the requirements of the [ToIP Governance Architecture Specification](#toip-governance-architecture-specification).


# ToIP Governance Metamodel<a id="toip-governance-metamodel"></a>

A structural model for [ToIP governance frameworks](#toip-governance-framework) that specifies the recommended [governance documents](#governance-document) that should be included depending on the [objectives](#objective) of the [trust community](#trust-community).


# ToIP Governance Stack<a id="toip-governance-stack"></a>

The governance half of the four layer [ToIP stack](#toip-stack) as defined by the [ToIP Governance Architecture Specification](#toip-governance-architecture-specification).

See also: [ToIP Technology Stack](#toip-technology-stack).


# ToIP identifier<a id="toip-identifier"></a>

A [verifiable identifier](#verifiable-identifier) for an [entity](https://essif-lab.github.io/framework/docs/terms/entity) that is addressable using the [ToIP stack](#toip-stack).

See also: [autonomous identifier](#autonomic-identifier), [decentralized identifier](#decentralized-identifier).

For more information, see: [Section 6.4](https://github.com/trustoverip/TechArch/blob/main/spec.md#64-toip-identifiers) of the [ToIP Technology Architecture Specification](#toip-technology-architecture-specification).


# ToIP intermediary<a id="toip-intermediary"></a>

See: [intermediary system](#intermediary-system).


# ToIP layer<a id="toip-layer"></a>

One of four [protocol layers](#protocol-layer) in the [ToIP stack](#toip-stack). The four layers are [ToIP Layer 1](#toip-layer-1), [ToIP Layer 2](#toip-layer-2), [ToIP Layer 3](#toip-layer-3), and [ToIP Layer 4](#toip-layer-4).

For more information, see: [ToIP Technology Architecture Specification](#toip-technology-architecture-specification), [ToIP Governance Architecture Specification](#toip-governance-architecture-specification).


# ToIP Layer 1<a id="toip-layer-1"></a>

The [trust support](#trust-support) layer of the [ToIP stack](#toip-stack), responsible for supporting the [trust spanning protocol](#trust-spanning-protocol) at [ToIP Layer 2](#toip-layer-2).


# ToIP Layer 2<a id="toip-layer-2"></a>

The [trust spanning layer](#trust-spanning-layer) of the [ToIP stack](#toip-stack), responsible for enabling the [trust task protocols](#trust-task-protocol) at [ToIP Layer 3](#toip-layer-3).


# ToIP Layer 3<a id="toip-layer-3"></a>

The [trust task](#trust-task) layer of the [ToIP stack](#toip-stack), responsible for enabling [trust applications](#trust-application) at [ToIP Layer 4](#toip-layer-4).


# ToIP Layer 4<a id="toip-layer-4"></a>

The [trust application](#trust-application) layer of the [ToIP stack](#toip-stack), where end users have the direct [human experience](#human-experience) of using applications that call [trust task protocols](#trust-task-protocol) to engage in [trust relationships](#trust-relationship) and make [trust decisions](#trust-decision) using ToIP decentralized digital trust infrastructure.


# ToIP message<a id="toip-message"></a>

A [message](#message) communicated between [ToIP endpoints](#ToIP-endpoint) using the [ToIP stack](#toip-stack).


# ToIP stack<a id="toip-stack"></a>

The layered architecture for decentralized digital trust infrastructure defined by the [ToIP Foundation](#toip-foundation). The ToIP stack is a dual stack consisting of two halves: the [ToIP Technology Stack](#toip-technology-stack) and the [ToIP Governance Stack](#toip-governance-stack). The four layers in the ToIP stack are [ToIP Layer 1](#toip-layer-1), [ToIP Layer 2](#toip-layer-2), [ToIP Layer 3](#toip-layer-3), and [ToIP Layer 4](#toip-layer-4).

For more information, see: [ToIP Technology Architecture Specification](#toip-technology-architecture-specification), [ToIP Governance Architecture Specification](#toip-governance-architecture-specification).


# ToIP system<a id="toip-system"></a>

A computing system that participates in the [ToIP Technology Stack](#toip-technology-stack). There are three types of ToIP systems: [endpoint systems](#endpoint-system), [intermediary systems](#intermediary-system), and [supporting systems](#supporting-system).

For more information, see: [Section 6.3](https://github.com/trustoverip/TechArch/blob/main/spec.md#63-high-level-system-architecture) of the [ToIP Technology Architecture Specification](#toip-technology-architecture-specification).


# ToIP trust network<a id="toip-trust-network"></a>

A [trust network](#trust-network) implemented using the [ToIP stack](#toip-stack).


# ToIP Technology Architecture Specification<a id="toip-technology-architecture-specification"></a>

The [technical specification](#technical-specification) defining the [requirements](#requirement) for the [ToIP Technology Stack](#toip-technology-stack) published by the [ToIP Foundation](#toip-foundation). 

For more information: [ToIP Technology Architecture Specification](#toip-technology-architecture-specification). 


# ToIP Technology Stack<a id="toip-technology-stack"></a>

The technology half of the four layer [ToIP stack](#toip-stack) as defined by the [ToIP Technology Architecture Specification](#toip-technology-architecture-specification).

See also: [ToIP Governance Stack](#toip-governance-stack), [ToIP layer](#toip-layer).


# ToIP trust community<a id="toip-trust-community"></a>

A [trust community](#trust-community) governed by a [ToIP governance framework](#toip-governance-framework).


# ToIP Trust Registry Protocol<a id="toip-trust-registry-protocol"></a>

The open standard [trust task protocol](#trust-task-protocol) defined by the [ToIP Foundation](#toip-foundation) to perform the [trust task](#trust-task) of querying a [trust registry](#trust-registry). The ToIP Trust Registry Protocol operates at [Layer 3](#layer-3) of the [ToIP stack](#toip-stack).


# ToIP Trust Spanning Protocol<a id="toip-trust-spanning-protocol"></a>

The ToIP Layer 2 protocol for [verifiable messaging](#verifiable-message) that implements the [trust spanning layer](#trust-spanning-layer) of the [ToIP stack](#toip-stack).  The ToIP Trust Spanning Protocol enables [actors](#actor) in different digital [trust domains](#trust-domain) to interact in a similar way to how the Internet Protocol (IP) enables devices on different local area networks to exchange data.

Mental model: [hourglass model,](#hourglass-model) see the [Design Principles for the ToIP Stack](https://trustoverip.org/permalink/Design-Principles-for-the-ToIP-Stack-V1.0-2022-11-17.pdf).

For more information, see: [Section 7.3](https://github.com/trustoverip/TechArch/blob/main/spec.md#73-layer-2-trust-spanning) of the [ToIP Technology Architecture Specification](#toip-technology-architecture-specification) and the [Trust Spanning Protocol Task Force](https://wiki.trustoverip.org/display/HOME/ToIP+Trust+Spanning+Protocol+Specification).


# transaction<a id="transaction"></a>

A discrete event between a user and a system that supports a business or programmatic purpose. A digital system may have multiple categories or types of transactions, which may require separate analysis within the overall digital identity [risk assessment](#risk-assessment).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/transaction).

See also: [connection](#connection).

Supporting definitions:

eSSIF-Lab: the exchange of goods, services, funds, or data between some [parties](https://essif-lab.github.io/framework/docs/terms/party) (called [participants](https://essif-lab.github.io/framework/docs/terms/participant) of the [transaction](https://essif-lab.github.io/framework/docs/terms/transaction)).


# transitive trust decision<a id="transitive-trust-decision"></a>

A [trust decision](#trust-decision) made by a [first party](#first-party) about a [second party](#second-party) or another [entity](#entity) based on information about the [second party](#second-party) or the other [entity](#entity) that is obtained from one or more [third parties](#third-party). 

Note: A primary purpose of [digital credentials](#digital-credential), [chained credentials](#chained-credentials), and [trust registries](#trust-registry) is to facilitate transitive trust decisions.

For more information, see: [Design Principles for the ToIP Stack](https://trustoverip.org/our-work/design-principles/).


# Transmission Control Protocol<a id="transmission-control-protocol"></a>

The Transmission Control Protocol (TCP) is one of the main protocols of the [Internet protocol suite](#internet-protocol-suite). It originated in the initial network implementation in which it complemented the [Internet Protocol](#internet-protocol) (IP). Therefore, the entire suite is commonly referred to as [TCP/IP](#tcpip). TCP provides reliable, ordered, and error-checked delivery of a stream of octets (bytes) between applications running on hosts communicating via an IP network. Major internet applications such as the World Wide Web, email, remote administration, and file transfer rely on TCP, which is part of the Transport Layer of the TCP/IP suite. [SSL/TLS](#transport-layer-security) often runs on top of TCP.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Transmission_Control_Protocol).

Also known as: [TCP](#tcp).

See also: [User Datagram Protocol](#user-datagram-protocol).


# Transport Layer Security<a id="transport-layer-security"></a>

Transport Layer Security (TLS) is a cryptographic protocol designed to provide [communications](#communication) security over a computer network. The protocol is widely used in applications such as email, instant messaging, and [Voice over IP](#voice-over-ip), but its use in securing HTTPS remains the most publicly visible. The TLS protocol aims primarily to provide security, including privacy ([confidentiality](#confidentiality)), integrity, and [authenticity](#authenticity) through the use of cryptography, such as the use of [certificates](#digital-certificate), between two or more communicating computer applications.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Transport_Layer_Security).

Also known as: [TLS](#tls).

Note: TLS replaced the deprecated [Secure Sockets Layer](#secure-sockets-layer) (SSL) protocol.


# tribal knowledge<a id="tribal-knowledge"></a>

[Knowledge](#knowledge) that is known within an “in-group” of people but unknown outside of it. A [tribe](https://en.wikipedia.org/wiki/Tribe), in this sense, is a group of people that share such a common [knowledge](#knowledge).

Source: [Wikipedia](https://en.wikipedia.org/wiki/Tribal_knowledge)


# trust<a id="trust"></a>

A belief that an [entity](#entity) will behave in a predictable manner in specified circumstances. The entity may be a person, process, object or any combination of such components. The entity can be of any size from a single hardware component or software module, to a piece of equipment identified by make and model, to a site or location, to an organization, to a nation-state. Trust, while inherently a subjective determination, can be based on objective evidence and subjective elements. The objective grounds for trust can include for example, the results of information technology product testing and evaluation. Subjective belief, level of comfort, and experience may supplement (or even replace) objective evidence, or substitute for such evidence when it is unavailable. Trust is usually relative to a specific circumstance or situation (e.g., the amount of money involved in a transaction, the sensitivity or criticality of information, or whether safety is an issue with human lives at stake). Trust is generally not transitive (e.g., you trust a friend but not necessarily a friend of a friend). Finally, trust is generally earned, based on experience or measurement.

Source: [NIST Special Publication 800-39](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-39.pdf) p.24

See also: [transitive trust decision](#transitive-trust-decision).

For more information, see: [Design Principles for the ToIP Stack](https://trustoverip.org/our-work/design-principles/).


# trust anchor<a id="trust-anchor"></a>

See: [trust root](#trust-root).

Note: The term “trust anchor” is most commonly used in cryptography and [public key infrastructure](#public-key-infrastructure). 


# trust application<a id="trust-application"></a>

An application that runs at [ToIP Layer 4](#toip-layer-4) in order to perform [trust tasks](#trust-task) or engage in other [verifiable messaging](#verifiable-message) using the [ToIP stack](#toip-stack).


# trust application layer<a id="trust-application-layer"></a>

In the context of the [ToIP stack](#toip-stack), the [trust application](#trust-application) layer is [ToIP Layer 4](#toip-layer-4). Applications running at this layer call [trust task protocols](#trust-task-protocol) at [ToIP Layer 3](#toip-layer-3).


# trust assurance<a id="trust-assurance"></a>

A process that provides a [level of assurance](#level-of-assurance) sufficient to make a particular [trust decision](#trust-decision).


# trust basis<a id="trust-basis"></a>

The [properties](#property) of a [verifiable identifier](#verifiable-identifier) or a [ToIP system](#toip-system) that enable a [party](#party) to [appraise](#appraisability-of-a-communications-endpoint) it to determine a [trust limit](#trust-limit).

See also: [appraisability](#appraisability-of-a-communications-endpoint). 

# trust boundary<a id="trust-boundary"></a>

The border of a [trust domain](#trust-domain).

# trust chain<a id="trust-chain"></a>

A set of [cryptographically verifiable](#cryptographically-verifiable) links between [digital credentials](#digital-credential) or other [data](#data) containers that enable [transitive trust decisions](#transitive-trust-decision).

See also: [chained credentials](#chained-credentials), [trust graph](#trust-graph).

For more information, see: [Design Principles for the ToIP Stack](https://trustoverip.org/our-work/design-principles/).

# trust community<a id="trust-community"></a>

A set of [parties](#party) who collaborate to achieve a mutual set of [trust objectives](#trust-objective). 

See also: [digital trust ecosystem](#digital-trust-ecosystem), [ToIP trust community](#toip-trust-community).

Note: A trust community may be large or small, formal or informal. In a formal trust community, the set of [policies](#policy) and [rules ](#rule)governing behavior of members are usually published in a [governance framework](#governance-framework) or [trust framework](#trust-framework). In an informal trust community, the policies or rules governing the behavior of members may be [tribal knowledge](#tribal-knowledge).


# trust context<a id="trust-context"></a>

The context in which a specific [party](#party) makes a specific [trust decision](#trust-decision). Many different factors may be involved in establishing a trust context, such as: the relevant interaction or transaction; the presence or absence of existing [trust relationships](#trust-relationship); the applicability of one or more [governance frameworks](#governance-framework); and the location, time, network, and/or devices involved. A trust context may be implicit or explicit; if explicit, it may be identified using an [identifier](#identifier). A [ToIP governance framework](#toip-governance-framework) an example of an explicit trust context identified by a [ToIP identifier](#toip-identifier).

See also: [trust domain](#trust-domain).

For more information, see: [Design Principles for the ToIP Stack](https://trustoverip.org/our-work/design-principles/).


# trust decision<a id="trust-decision"></a>

A decision that a [party](#party) needs to make about whether to engage in a specific interaction or [transaction](#transaction) with another [entity](#entity) that involves real or perceived [risks](#risk).

See also: [transitive trust decision](#transitive-trust-decision).

For more information, see: [Design Principles for the ToIP Stack](https://trustoverip.org/our-work/design-principles/).


# trust domain<a id="trust-domain"></a>

A [security domain](#security-domain) defined by a computer hardware or software architecture, a [security policy](#security-policy), or a [trust community](#trust-community), typically via a [trust framework](#trust-framework) or [governance framework](#governance-framework).

See also: [trust context](#trust-context), [digital trust ecosystem](#digital-trust-ecosystem).


# trust ecosystem<a id="trust-ecosystem"></a>

See [digital trust ecosystem](#digital-trust-ecosystem).


# trust establishment<a id="trust-establishment"></a>

The process two or more [parties](#party) go through to establish a [trust relationship](#trust-relationship). In the context of decentralized digital trust infrastructure, trust establishment takes place at two levels. At the technical trust level, it includes some form of [key establishment](#key-establishment). At the human trust level, it may be accomplished via an [out-of-band introduction](#out-of-band-introduction), the exchange of [digital credentials](#digital-credential), queries to one or more [trust registries](#trust-registry), or evaluation of some combination of [human-readable](#human-readable) and [machine-readable](#machine-readable) [governance frameworks](#governance-framework).


# trust framework<a id="trust-framework"></a>

A term (most frequently used in the [digital identity](#digital-identity) industry) to describe a [governance framework](#governance-framework) for a [digital identity](#digital-identity) system, especially a [federation](#federation).


# trust graph<a id="trust-graph"></a>

A [data](#data) structure describing the [trust relationship](#trust-relationship) between two or more [entities](#entity). A simple trust graph may be expressed as a [trust list](#trust-list). More complex trust graphs can be recorded or registered in and queried from a [trust registry](#trust-registry). Trust graphs can also be expressed via [trust chains](#trust-chain) and [chained credentials](#chained-credentials). Trust graphs can enable [verifiers](#verifier-of-a-claim-or-credential) to make [transitive trust decisions](#transitive-trust-decision).

See also: [authorization graph](authorization-graph), [governance graph](#governance-graph), [reputation graph](#reputation-graph).


# trust limit<a id="trust-limit"></a>

A limit to the degree a [party](#party) is willing to trust an [entity](#entity) in a specific [trust relationship](#trust-relationship) within a specific [trust context](#trust-context).

For more information, see: [Design Principles for the ToIP Stack](https://trustoverip.org/our-work/design-principles/).


# trust list<a id="trust-list"></a>

A one-dimensional [trust graph](#trust-graph) in which an [authoritative source](#authoritative-source) publishes a list of [entities](#entity) that are trusted in a specific [trust context](#trust-context). A trust list can be considered a simplified form of a [trust registry](#trust-registry).


# trust network<a id="trust-network"></a>

A network of parties who are connected via [trust relationships](#trust-relationship) conforming to [requirements](#requirement) defined in a legal regulation, [trust framework](#trust-framework) or [governance framework](#governance-framework). A trust network is more formal than a [digital trust ecosystem](#digital-trust-ecosystem); the latter may connect parties more loosely via transitive trust relationships and/or across multiple trust networks.

See also: [ToIP trust network](#toip-trust-network).


# trust objective<a id="trust-objective"></a>

An [objective](#objective) shared by the [parties](#party) in a [trust community](#trust-community) to establish and maintain [trust relationships](#trust-relationship).


# Trust over IP<a id="trust-over-ip"></a>

A term coined by John Jordan to describe the decentralized digital trust infrastructure made possible by the [ToIP stack](#toip-stack). A play on the term Voice over IP (abbreviated VoIP).

Also known as: [ToIP](#toip).


# trust registry<a id="trust-registry"></a>

A [registry](#registry) that serves as an [authoritative source](#authoritative-source) for [trust graphs](#trust-graph) or other [governed information](#governed-information) describing one or more [trust communities](#trust-community). A trust registry is typically [authorized](#authorization) by a [governance framework](#governance-framework).

See also: [trust list](#trust-list), [verifiable data registry](#verifiable-data-registry).


# trust registry protocol<a id="trust-registry-protocol"></a>

See: [ToIP Trust Registry Protocol](#toip-trust-registry-protocol).


# trust relationship<a id="trust-relationship"></a>

A relationship between a [party](#party) and an [entity](#entity) in which the [party](#party) has decided to trust the [entity](#entity) in one or more [trust contexts](#trust-context) up to a [trust limit](#trust-limit).

Supporting definitions:

[NIST](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-160v1r1.pdf): An agreed upon relationship between two or more system elements that is governed by criteria for secure interaction, behavior, and outcomes relative to the protection of assets.

For more information, see: [Design Principles for the ToIP Stack](https://trustoverip.org/our-work/design-principles/).


# trust root<a id="trust-root"></a>

The [authoritative source](#authoritative-source) that serves as the origin of a [trust chain](#trust-chain).

For more information, see: [Design Principles for the ToIP Stack](https://trustoverip.org/our-work/design-principles/).


# trust service provider<a id="trust-service-provider"></a>

In the context of specific [digital trust ecosystems](#digital-trust-ecosystem), such as the European Union’s eIDAS regulations, a trust service provider (TSP) is a legal entity that provides specific [trust support](#trust-support) services as required by legal regulations, [trust frameworks](#trust-framework), or [governance frameworks](#governance-framework). In the larger context of [ToIP](#trust-over-ip) infrastructure, a TSP is a provider of services based on the [ToIP stack](#toip-stack). Most generally, a TSP is to the trust layer for the Internet what an Internet service provider (ISP) is to the Internet layer.

Also known as: [TSP](#tsp).

Supporting definitions:

Wikipedia: A trust service provider (TSP) is a person or legal entity providing and preserving [digital certificates](https://en.wikipedia.org/wiki/Digital_certificate) to create and validate [electronic signatures](https://en.wikipedia.org/wiki/Electronic_signature) and to authenticate their signatories as well as websites in general. Trust service providers are qualified [certificate authorities](https://en.wikipedia.org/wiki/Certificate_authority) required in the [European Union](https://en.wikipedia.org/wiki/European_Union) and in Switzerland in the context of regulated [electronic signing](https://en.wikipedia.org/wiki/Electronic_signature) procedures.


# trust support<a id="trust-support"></a>

A system, protocol, or other infrastructure whose function is to facilitate the establishment and maintenance of [trust relationships](#trust-relationship) at higher [protocol layers](#protocol-layer). In the [ToIP stack](#toip-stack), the [trust support layer](#trust-support-layer) is [Layer 1](#layer-1).


# trust support layer<a id="trust-support-layer"></a>

In the context of the [ToIP stack](#toip-stack), the [trust support](#trust-support) layer is [ToIP Layer 1](#toip-layer-1). It supports the operations of the ToIP Trust Spanning Protocol at [ToIP Layer 2](#toip-layer-2).


# trust spanning layer<a id="trust-spanning-layer"></a>

A [spanning layer](#spanning-layer) designed to span between different digital [trust domains](#trust-domain). In the [ToIP stack](#toip-stack), [ToIP Layer 2](#toip-layer-2) is the trust spanning layer.

See also: [ToIP layer](#toip-layer).

Mental model: [hourglass model,](#hourglass-model) see [ToIP Technology Architecture Specification](#toip-technology-architecture-specification)

For more information, see: [Section 7.3](https://github.com/trustoverip/TechArch/blob/main/spec.md#73-layer-2-trust-spanning) of the [ToIP Technology Architecture Specification](#toip-technology-architecture-specification).


# trust spanning protocol<a id="trust-spanning-protocol"></a>

See: [ToIP Trust Spanning Protocol](#toip-trust-spanning-protocol).


# trust task<a id="trust-task"></a>

A specific task that involves establishing, verifying, or maintaining [trust relationships](#trust-relationship) or exchanging [verifiable messages](#verifiable-message) or [verifiable data](#verifiable-data) that can be performed on behalf of a [trust application](#trust-application) by a [trust task protocol](#trust-task-protocol) at [Layer 3](#toip-layer-3) of the [ToIP stack](#toip-stack).

For more information, see [Section 7.4](https://github.com/trustoverip/TechArch/blob/main/spec.md#74-layer-3-trust-tasks) of the [ToIP Technology Architecture Specification](#toip-technology-architecture-specification).


# trust task layer<a id="trust-task-layer"></a>

In the context of the [ToIP stack](#toip-stack), the [trust task](#trust-task) layer is [ToIP Layer 3](#toip-layer-3). It supports [trust applications](#trust-application) operating at [ToIP Layer 4](#toip-layer-4).


# trust task protocol<a id="trust-task-protocol"></a>

A [ToIP Layer 3](#toip-layer-3) protocol that implements a specific [trust task](#trust-task) on behalf of a [ToIP Layer 4](#toip-layer-4) [trust application](#trust-application).


# trust triangle<a id="trust-triangle"></a>

See: [three-party model](#three-party-model).


# trusted execution environment<a id="trusted-execution-environment"></a>

A trusted execution environment (TEE) is a secure area of a main processor. It helps code and data loaded inside it to be protected with respect to [confidentiality](#confidentiality) and [integrity](#integrity-of-a-data-structure). Data [integrity](#integrity-of-a-data-structure) prevents [unauthorized](#authorization) [entities](#entity) from outside the TEE from altering [data](#data), while code integrity prevents code in the TEE from being replaced or modified by [unauthorized](#authorization) [entities](#entity), which may also be the computer [owner](#owner-of-an-entity) itself as in certain [DRM](#drm) schemes.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Trusted_execution_environment).

Also known as: [TEE](#tee).

See also: [Secure Enclave](#secure-enclave).


# trusted role<a id="trusted-role"></a>

A [role](http://role) that performs restricted activities for an [organization](#organization) after meeting competence, security and background [verification](#verification) [requirements](#requirement) for that [role](#role).


# trusted third party<a id="trusted-third-party"></a>

In [cryptography](#public-key-cryptography), a trusted [third party](#third-party) (TTP) is an entity which facilitates interactions between two [parties](#party) who both trust the third party; the third party reviews all critical transaction communications between the parties, based on the ease of creating fraudulent digital content. In TTP models, the [relying parties](#relying-party) use this trust to secure their own interactions. TTPs are common in any number of commercial transactions and in cryptographic digital transactions as well as cryptographic protocols, for example, a [certificate authority](#certificate-authority) (CA) would issue a [digital certificate](#digital-certificate) to one of the two parties in the next example. The CA then becomes the TTP to that certificate's issuance. Likewise transactions that need a third party recordation would also need a third-party repository service of some kind.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Trusted_third_party).

Also known as: [TTP](#ttp).

Supporting definitions:

[NIST-CSRC](https://csrc.nist.gov/glossary/term/trusted_third_party): A third party, such as a CA, that is trusted by its clients to perform certain services. (By contrast, the two participants in a key-establishment transaction are considered to be the first and second parties.)


# trusted timestamp authority<a id="trusted-timestamp-authority"></a>

An [authority](#authority) that is trusted to provide accurate time information in the form of a [timestamp](#timestamp).

Source: [NIST-CSRC](https://csrc.nist.gov/glossary/term/trusted_timestamp_authority).

Also known as: [TTA](#tta).


# trustworthy<a id="trustworthy"></a>

A [property](#property) of an [entity](#entity) that has the [attribute](#attribute) of [trustworthiness](#trustworthiness).


# trustworthiness<a id="trustworthiness"></a>

An [attribute](#attribute) of a [person](#natural-person) or [organization](#organization) that provides confidence to others of the qualifications, capabilities, and reliability of that [entity](#entity) to perform specific tasks and fulfill assigned responsibilities. Trustworthiness is also a characteristic of information technology products and systems. The attribute of trustworthiness, whether applied to people, processes, or technologies, can be measured, at least in relative terms if not quantitatively. The determination of trustworthiness plays a key role in establishing [trust relationships](#trust-relationship) among [persons](#natural-person) and [organizations](#organization). The [trust relationships](#trust-relationship) are key factors in [risk decisions](#risk-decision) made by senior leaders/executives.

Source: [NIST Special Publication 800-39](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-39.pdf) p.24


# TSP<a id="tsp"></a>

See: [trust service provider](#trust-service-provider), [trust spanning protocol](#trust-spanning-protocol).


# TTA<a id="tta"></a>

See: [trusted timestamp authority](#trusted-timestamp-authority).


# TTP<a id="ttp"></a>

See: [trusted third party](#trusted-third-party).


# UDP<a id="udp"></a>

See: [User Datagram Protocol](#user-datagram-protocol).


# unicast<a id="unicast"></a>

In computer networking, unicast is a one-to-one transmission from one point in the network to another point; that is, one sender and one receiver, each identified by a [network address](#network-address) (a [unicast address](#unicast-address)). Unicast is in contrast to [multicast](#multicast) and [broadcast](#broadcast) which are one-to-many transmissions. [Internet Protocol](#internet-protocol) unicast delivery methods such as [Transmission Control Protocol](#transmission-control-protocol) (TCP) and [User Datagram Protocol](#user-datagram-protocol) (UDP) are typically used.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Unicast).

See also: [anycast](#anycast).


# unicast address<a id="unicast-address"></a>

A [network address](#network-address) used for a [unicast](#unicast).


# user agent<a id="user-agent"></a>

A [software agent](#software-agent) that is used directly by the end-user as the [principal](#principal). Browsers, email clients, and [digital wallets](#digital-wallet) are all examples of user agents.

Supporting definitions:

[Wikipedia](https://en.wikipedia.org/wiki/User_agent): On the [Web](https://en.wikipedia.org/wiki/World_Wide_Web), a user agent is a [software agent](https://en.wikipedia.org/wiki/Software_agent) capable of and responsible for retrieving and facilitating [end user](https://en.wikipedia.org/wiki/End_user) interaction with Web content.[<sup>\[1\]</sup>](https://en.wikipedia.org/wiki/User_agent#cite_note-1) This includes all common [web browsers](https://en.wikipedia.org/wiki/Web_browser), such as [Google Chrome](https://en.wikipedia.org/wiki/Google_Chrome), [Mozilla Firefox](https://en.wikipedia.org/wiki/Mozilla_Firefox), and [Safari](https://en.wikipedia.org/wiki/Safari_\(web_browser\)), some [email clients](https://en.wikipedia.org/wiki/Email_client), standalone [download managers](https://en.wikipedia.org/wiki/Download_manager) like [youtube-dl](https://en.wikipedia.org/wiki/Youtube-dl), other [command-line](https://en.wikipedia.org/wiki/Command-line) utilities like [cURL](https://en.wikipedia.org/wiki/CURL), and arguably [headless](https://en.wikipedia.org/wiki/Headless_software) [services](https://en.wikipedia.org/wiki/Service_\(systems_architecture\)) that power part of a larger application, such as a [web crawler](https://en.wikipedia.org/wiki/Web_crawler).

The user agent plays the role of the [client](https://en.wikipedia.org/wiki/Client_\(computing\)) in a [client–server system](https://en.wikipedia.org/wiki/Client%E2%80%93server_model). The [HTTP](https://en.wikipedia.org/wiki/HTTP) [User-Agent header](https://en.wikipedia.org/wiki/User-Agent_header) is intended to clearly identify the agent to the server. However, this header can be omitted or [spoofed](https://en.wikipedia.org/wiki/User_agent_spoofing), so some websites use [other agent detection methods](https://en.wikipedia.org/wiki/Browser_sniffing).


# User Datagram Protocol<a id="user-datagram-protocol"></a>

In computer networking, the User Datagram Protocol (UDP) is one of the core [communication](#communication) protocols of the [Internet protocol suite](#internet-protocol-suite) used to send [messages](#message) (transported as [datagrams](#datagram) in [packets](#data-packet)) to other hosts on an [Internet Protocol](#internet-protocol) (IP) network. Within an IP network, UDP does not require prior communication to set up [communication channels](#communication-channel) or data paths.

Source: [Wikipedia](https://en.wikipedia.org/wiki/User_Datagram_Protocol).

Also known as: [UDP](#udp).


# utility governance framework<a id="utility-governance-framework"></a>

A [governance framework](#governance-framework) for a [digital trust utility](#digital-trust-utility). A utility governance framework may be a component of or referenced by an [ecosystem governance framework](#ecosystem-governance-framework) or a [credential governance framework](#credential-governance-framework).


# validation<a id="validation"></a>

An [action](#action) an [agent](#agent) (of a [principal](#principal)) performs to determine whether a digital object or set of [data](#data) meets the [requirements](#requirement) of a specific [party](#party).

See also: [verification](#verification).

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#validate): The act, by or on behalf of a [party](https://essif-lab.github.io/framework/docs/terms/party), of determining whether or not that data is valid to be used for some specific purpose(s) of that [party](https://essif-lab.github.io/framework/docs/terms/party).

[NIST: ](https://csrc.nist.gov/glossary/term/validation)Confirmation, through the provision of objective evidence, that the requirements for a specific intended use or application have been fulfilled.


# vault<a id="vault"></a>

See: [digital vault](#digital-vault).


# VC<a id="vc"></a>

See: [verifiable credential](#verifiable-credential).


# verifiability (of a digital object, claim, or assertion)<a id="verifiability-of-a-digital-object-claim-or-assertion"></a>

The [property](#property) of a digital object, assertion, [claim](#claim), or [communication](#communication), being [verifiable](#verifiable).

See also: [ appraisability](#appraisability-of-a-communications-endpoint).


# verifiable<a id="verifiable"></a>

In the context of digital [communications](#communication) infrastructure, the ability to determine the [authenticity](#authenticity) of a [communication](#communication) (e.g., sender, contents, [claims](#claim), [metadata](#metadata), provenance), or the underlying [sociotechnical](#sociotechnical-system) infrastructure (e.g., [governance](#governance-framework), [roles](#role), [policies](#policy), [authorizations](#authorization), [certifications](#certification-of-a-party)).

See also:[ appraisability (of a communications end-point)](#appraisability-of-a-communications-endpoint); [digital signature](#digital-signature).


# verifiable credential<a id="verifiable-credential"></a>

A standard data model and representation format for [cryptographically-verifiable](#cryptographically-verifiable) [digital credentials](#digital-credential) as defined by the [W3C Verifiable Credentials Data Model specification](#w3c-verifiable-credentials-data-model-specification).

Source: [W3C DID](https://www.w3.org/TR/did-core/#terminology)

See also: [digital credential](#digital-credential).

Mental model: [W3C Verifiable Credentials Data Model Roles & Information Flows](https://www.w3.org/TR/vc-data-model/#roles)

Supporting definitions:

[W3C VC](https://www.w3.org/TR/vc-data-model/#terminology): A verifiable credential is a tamper-evident credential that has authorship that can be cryptographically verified. Verifiable credentials can be used to build [verifiable presentations](https://www.w3.org/TR/vc-data-model/#dfn-verifiable-presentations), which can also be cryptographically verified. The [claims](https://www.w3.org/TR/vc-data-model/#dfn-claims) in a credential can be about different [subjects](https://www.w3.org/TR/vc-data-model/#dfn-subjects).


# verifiable data<a id="verifiable-data"></a>

Any digital [data](#data) or object that is [digitally signed](#digital-signature) in such a manner that it can be [cryptographically verified](#cryptographically-verifiable). 

Note: In the context of ToIP architecture, verifiable data is signed with the [cryptographic keys ](#cryptographic-key)associated with the [ToIP identifier](#toip-identifier) of the data [controller](#controller-of-a-key-vault-wallet-agent-or-device).


# verifiable data registry<a id="verifiable-data-registry"></a>

A [registry](#registry) that facilitates the creation, [verification](#verification), updating, and/or deactivation of [decentralized identifiers](#decentralized-identifier) and [DID documents](#did-document). A verifiable data registry may also be used for other [cryptographically-verifiable](#cryptographically-verifiable) data structures such as [verifiable credentials](#verifiable-credential). 

Source: [W3C DID](https://www.w3.org/TR/did-core/#terminology)

Mental model: [W3C Verifiable Credentials Data Model Roles & Information Flows](https://www.w3.org/TR/vc-data-model/#roles)

See also: [authoritative source](#authoritative-source), [trust registry](#trust-registry), [system of record](#system-of-record).

For more information, see: the W3C Verifiable Credentials specification \[[VC-DATA-MODEL](https://www.w3.org/TR/did-core/#bib-vc-data-model)].

Note: There is an [earlier definition in the W3C VC 1.1. glossary](https://www.w3.org/TR/vc-data-model/#terminology) that is not as mature (it is not clear about the use of cryptographically verifiable data structures). We do not recommend that definition.


# verifiable identifier<a id="verifiable-identifier"></a>

An [identifier](#identifier) over which the [controller](#controller-of-a-key-vault-wallet-agent-or-device) can provide cryptographic [proof of control](#proof-of-control).

See also: [decentralized identifier](#decentralized-identifier), [autonomous identifier](#autonomic-identifier).


# verifiable message<a id="verifiable-message"></a>

A [message](#message) communicated as [verifiable data](#verifiable-data).

See also: [ToIP messages](#toip-message) 


# verification<a id="verification"></a>

An [action](#action) an [agent](#agent) (of a [principal](#principal)) performs to determine the [authenticity](#authenticity) of a [claim](#claim) or other digital object using a [cryptographic key](#cryptographic-key).

See also: [validation](#validation).

Mental model: [W3C Verifiable Credentials Data Model Roles & Information Flows](https://www.w3.org/TR/vc-data-model/#roles)

Supporting definitions:

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#verify): The act, by or on behalf of a [party](https://essif-lab.github.io/framework/docs/terms/party), of determining whether that data is authentic (i.e. originates from the [party](https://essif-lab.github.io/framework/docs/terms/party) that authored it), timely (i.e. has not expired), and conforms to other specifications that apply to its structure.


# verifier (of a claim or credential)<a id="verifier-of-a-claim-or-credential"></a>

A [role](#role) an [agent](#agent) performs to perform [verification](#verification) of one or more [proofs](#proof) of the [claims](#claim) in a [digital credential](#digital-credential).

See also: [relying party](#relying-party); [issuer](#issuer-of-a-claim-or-credential), [holder](#holder-of-a-claim-or-credential).

Mental model: [W3C Verifiable Credentials Data Model Roles & Information Flows](https://www.w3.org/TR/vc-data-model/#roles)

Supporting definitions:

[W3C VC](https://www.w3.org/TR/vc-data-model/#terminology): A role an [entity](https://www.w3.org/TR/vc-data-model/#dfn-entities) performs by receiving one or more [verifiable credentials](https://www.w3.org/TR/vc-data-model/#dfn-verifiable-credentials), optionally inside a [verifiable presentation](https://www.w3.org/TR/vc-data-model/#dfn-verifiable-presentations) for processing. Other specifications might refer to this concept as a [relying party](#relying-party).

[eSSIF-Lab](https://essif-lab.github.io/framework/docs/essifLab-glossary#verifier): a component that implements the [capability](https://essif-lab.github.io/framework/docs/terms/capability) to request [peer agents](https://essif-lab.github.io/framework/docs/terms/peer-agent) to present (provide) data from credentials (of a specified kind, issued by specified [parties](https://essif-lab.github.io/framework/docs/terms/party)), and to verify such responses (check structure, signatures, dates), according to its [principal](https://essif-lab.github.io/framework/docs/terms/principal)'s [verifier policy](https://essif-lab.github.io/framework/docs/terms/verifier-policy). 

[NIST:](https://csrc.nist.gov/glossary/term/verifier) The entity that verifies the authenticity of a digital signature using the public key.


# VID<a id="vid"></a>

See [​​verifiable identifier](#verifiable-identifier).


# VID relationship<a id="vid-relationship"></a>

The [communications](#communication) relationship formed between two [VIDs](#vid) using the [ToIP Trust Spanning Protocol](#toip-trust-spanning-protocol). A particular feature of this protocol is its ability to establish as many VID relationships as needed to establish different [relationship contexts](#relationship-context) between the communicating [entities](#entity).


# VID-to-VID<a id="vid-to-vid"></a>

The specialized type of [peer-to-peer](#peer-to-peer) [communications](#communication) enabled by the [ToIP Trust Spanning Protocol](#toip-trust-spanning-protocol). Each pair of VIDs creates a unique [VID relationship](#vid-relationship).


# virtual vault<a id="virtual-vault"></a>

A [digital vault](#digital-vault) enclosed inside another [digital vault](#digital-vault) by virtue of having its own [verifiable identifier](#verifiable-identifier) (VID) and its own set of [encryption](#encryption) [keys](#key) that are separate from those used to unlock the enclosing vault.


# Voice over IP<a id="voice-over-ip"></a>

Voice over Internet Protocol (VoIP), also called IP telephony, is a method and group of technologies for voice calls for the delivery of voice [communication](#communication) sessions over [Internet Protocol](#internet-protocol) (IP) networks, such as the Internet.

Also known as: [VoIP](#voip).


# VoIP<a id="voip"></a>

See: [Voice over IP](#voice-over-ip).


# W3C Verifiable Credentials Data Model Specification<a id="w3c-verifiable-credentials-data-model-specification"></a>

A W3C Recommendation defining a standard data model and representation format for [cryptographically-verifiable](#cryptographically-verifiable) [digital credentials](#digital-credential). Version 1.1 was published on 03 March 2022.

For more information, see: <https://www.w3.org/TR/vc-data-model/> 


# wallet<a id="wallet"></a>

See: [digital wallet](#digital-wallet).


# wallet engine<a id="wallet-engine"></a>

The set of software components that form the core of a [digital wallet](#digital-wallet), but which by themselves are not sufficient to deliver a fully functional wallet for use by a [digital agent](#digital-agent) (of a [principal](#principal)). A wallet engine is to a [digital wallet](#digital-wallet) what a [browser engine](https://en.wikipedia.org/wiki/Browser_engine) is to a web browser.

For more information: The charter of the [OpenWallet Foundation](#openwallet-foundation) is to produce an open source [digital wallet](#digital-wallet) engine.


# witness<a id="witness"></a>

A computer system that receives, [verifies](#verifier-of-a-claim-or-credential), and stores [proofs](#proof) of [key events](#key-event) for a [verifiable identifier](#verifiable-identifier) (especially an [autonomous identifier](#autonomic-identifier)). Each witness controls its own [verifiable identifier](#verifiable-identifier) used to sign [key event](#key-event) messages stored by the witness. A witness may use any suitable computer system or database architecture, including a file, centralized database, distributed database, [distributed ledger](#distributed-ledger), or [blockchain](#blockchain).

Note: [KERI](#keri) is an example of a [key management system](#key-management-system) that uses witnesses.


# zero-knowledge proof<a id="zero-knowledge-proof"></a>

A specific kind of cryptographic [proof](#proof) that proves facts about [data](#data) to a [verifier](#verifier-of-a-claim-or-credential) without revealing the underlying [data](#data) itself. A common example is proving that a person is over or under a specific age without revealing the person’s exact birthdate.

Also known as: zero-knowledge protocol.

Supporting definitions:

[Ethereum:](https://ethereum.org/en/zero-knowledge-proofs/) A zero-knowledge proof is a way of proving the validity of a statement without revealing the statement itself.

[Wikipedia](https://en.wikipedia.org/wiki/Zero-knowledge_proof): a method by which one [party](#party) (the prover) can prove to another party (the verifier) that a given statement is true, while avoiding conveying to the [verifier](#verifier-of-a-claim-or-credential) any information beyond the mere fact of the statement's truth.


# zero-knowledge service<a id="zero-knowledge-service"></a>

In cloud computing, the term “zero-knowledge” refers to an online service that stores, transfers or manipulates [data](#data) in a way that maintains a high level of [confidentiality](#confidentiality), where the data is only accessible to the [data's](#data) [owner](#owner-of-an-entity) (the client), and not to the service provider. This is achieved by [encrypting](#encryption) the raw data at the client's side or [end-to-end](#end-to-end-encryption) (in case there is more than one client), without disclosing the password to the service provider. This means that neither the service provider, nor any [third party](#third-party) that might intercept the [data](#data), can [decrypt](#decryption) and access the [data](#data) without prior permission, allowing the client a higher degree of privacy than would otherwise be possible. In addition, zero-knowledge services often strive to hold as little [metadata](#metadata) as possible, holding only that [data](#data) that is functionally needed by the service.

Source: [Wikipedia](https://en.wikipedia.org/wiki/Zero-knowledge_service).

Also known as: no knowledge, zero access.

# zero-knowledge service provider<a id="zero-knowledge-service-provider"></a>

The provider of a [zero-knowledge service](#zero-knowledge-service) that hosts [encrypted](#encryption) [data](#data) on behalf of the [principal](#principal) but does not have access to the [private keys](#private-key) in order to be able to [decrypt](#decryption) it.

# zero-trust architecture<a id="zero-trust-architecture"></a>

A network security architecture based on the core design principle “never trust, always verify”, so that all [actors](#actor) are denied access to resources pending [verification.](#verification)

Also known as: zero-trust security, perimeterless security.

Contrast with: [attribute-based access control](#attribute-based-access-control), [role-based access control](#role-based-access-control).

Supporting definitions:

[NIST-CSRC](https://csrc.nist.gov/glossary/term/zero_trust_architecture): A security model, a set of system design principles, and a coordinated cybersecurity and system management strategy based on an acknowledgement that threats exist both inside and outside traditional network boundaries. The zero trust security model eliminates implicit trust in any one element, component, node, or service and instead requires continuous verification of the operational picture via real-time information from multiple sources to determine access and other system responses.

[Wikipedia](https://en.wikipedia.org/wiki/Zero_trust_security_model): The zero trust security model, also known as zero trust architecture (ZTA), and sometimes known as perimeterless security, describes an approach to the strategy, design and implementation of [IT systems](https://en.wikipedia.org/wiki/IT_system). The main concept behind the zero trust security model is "never trust, always verify," which means that users and devices should not be trusted by default, even if they are connected to a permissioned network such as a corporate [LAN](https://en.wikipedia.org/wiki/Local_area_network) and even if they were previously verified.

# ZKP<a id="zkp"></a>

See: [zero-knowledge proof](#zero-knowledge-proof).

[[def: anonymous]]
~ An adjective describing when the identity of a natural person or other actor is unknown.
See also: pseudonym.

[[def: assurance level]]
~ A level of confidence that may be relied on by others. Different types of assurance levels are defined for different types of trust assurance mechanisms. Examples include authenticator assurance level, federation assurance level, and identity assurance level.

[[def: authorization]]
~ The process of verifying that a requested action or service is approved for a specific entity.
Source: NIST-CSRC.
* See also: [[ref: permission]].

[[def: out-of-band introduction, OOBI]]
~ A process by which two or more entities exchange VIDs in order to form a cryptographically verifiable connection (e.g., a ToIP connection), such as by scanning a QR code (in person or remotely) or clicking a deep link.
* Also known as: [[ref:OOBI]].

[[def: permission]]
~ Authorization to perform some action on a system.
* Source: [[ref: NIST-CSRC]].

[[def: policy]]
~ Statements, rules or assertions that specify the correct or expected behavior of an entity. 
* Example: An authorization policy might specify the correct access control rules for a software component.
* Source: [[ref: NIST-CSRC]]
* See also: governance requirement, machine-readable policy.

[[def: real world identity]]
A term used to describe the opposite of digital identity, i.e., an identity (typically for a person) in the physical instead of the digital world.
Also known as: RWI.
See also: legal identity.

[[def: self-certifying identifier, SCID]]
* A subclass of verifiable identifier that is cryptographically verifiable without the need to rely on any third party for verification because the identifier is cryptographically bound to the cryptographic keys from which it was generated.
* Also known as: autonomous identifier.

## Sources for Terms & Definitions

::: todo: Really Important
  Add list (table?) of sources
:::


[[def: NIST-CSRC]] 
~ [NIST Computer Security Resource Center Glossary](https://csrc.nist.gov/glossary/)
