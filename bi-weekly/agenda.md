# DIF bi-weekly - open call

[![hackmd-github-sync-badge](https://hackmd.io/sdTB8He_TASbNSJOSUdfvQ/badge)](https://hackmd.io/sdTB8He_TASbNSJOSUdfvQ)



[**Website** ](https://identity.foundation ) | [Mailing list](https://lists.identity.foundation/) | [Old minutes](https://docs.google.com/document/d/1vVSGCxZ_YTluSUnwyUNwV74pd6cjLBL-n2ydht_5NyA/edit#) | [Meeting recordings](https://docs.google.com/spreadsheets/d/1wgccmMvIImx30qVE9GhRKWWv3vmL2ZyUauuKx3IfRmA/edit#gid=2039757024)


_For this call, you are encouraged to turn your video on. This is a good way to build rapport given we are a large, disparate group experiencing a lot of churn._

_This document is live-edited DURING each call, and stable/authoritative copies live on our github repo under /agenda.md. Please note that we might not notice a pullrequest in time, but you are free to propose agenda items for future meetings via hackmd._

<details>
<summary> Meeting information </summary>

* To participate - This is an open call, feel free to join and contirubute
* Time: bi-weekly Wednesdays, 11:00-12:00 ET
* [Calendar entry](https://calendar.google.com/event?action=TEMPLATE&tmeid=OWtzNWZuanA4bWRnYmF0ZnVxaDR0MnQ2cGVfMjAyMDA5MjFUMTgwMDAwWiBkZWNlbnRyYWxpemVkLmlkZW50aXR5QG0&tmsrc=decentralized.identity%40gmail.com&scp=ALL)
* [Zoom room](https://us02web.zoom.us/j/313879009?pwd=dHZiSFlFUEYwVk91dEptaTAraTlBZz09), Meeting ID: 313 879 009, Password: 743522 
</details>

## Meeting - 9 December 2020 - (1100 ET) 
 
### Agenda

1. **Welcome and introductions**
2. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/confidential-storage/blob/master/agenda.md)
        *  Introduction to [Spec Map](https://github.com/manicprogrammer/vc-spec-rel/) with researcher Michael Ruminer, talking about how to maintain it going forward
        *  BBS+ in Aries overview with Stephen Curran
        *  eSSIF & eSSIF-Lab interop deep dive
            *  Interop specifications discussion-- how to align with existing API standards?

    * **Identifiers & Discovery** (Markus, Sam) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
        * Method Spec Registry analytics and some possible directions for DIF-based efforts to structure DID Method comparison/review
            * Sam suggested to do analytics of DID method usage through Universal Resolver
            * Sophie suggested that authors/implementers should be asked to supply contact information
        * Discussion around accessibility/usability of DID technology
            * it felt hard to get back to the topic and find the inside knowledge that's required to use DIDs.
            * Sophie agreed that it was hard to find things, there are too many documents and some broken links.
            * Eric suggested it would be good to have third-party journalistic review of DID methods.
        * Key roll-over and recovery
            * repo in IDWG for lists recovery methods we know about.
            * For the Confidential Storage (SDS) WG, key recovery is pretty much out of scope. 
            * There is essentially only a limited set of options (menmonic devices, secret sharing).
            * Biometrics must not be used as a primary private key ("you can't rotate biometrics"). Biometrics can be used to unlock a private key, i.e. as an authorization capability.
            * Universal Wallet Conceptual Clarifications 
            * Universal Registrar problem

    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * Update around [WACI](https://github.com/hellobloom/wallet-credential-interactions/pull/5)
        * Inform about VC Marketplace Workitem: Candidates:
            * In addition to existing: *KILT, Civic*
        * Credential Ontology and Tooling: What should the output to the group be: JSON Schemas, JSON-LD Contexts, Overlab with CCG Vocubulary. Workitem + Affinidi. Getting people at the table.
        * Recovation Workitem TBD (discuss with Gabe.)

    * **DID Auth** (Oliver, Kyle) *half hibernated state*
        * blog article about OIDF collaboration
        * [OIDC workshop on Dec 15th inclusing SIOP/DIF](https://openidentityexchange.org/networks/87/events.html?id=1031)
    * **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://github.com/decentralized-identity/didcomm/blob/main/agenda.md)
        * Current status on 1st complete draft? 
        * DIDComm.org Progress
            * https://github.com/decentralized-identity/didcomm.org
            * https://didcomm.org / https://www.didcomm.org  (works)
        * DID Use Cases
            * [Original]( https://github.com/w3c/did-use-cases/pull/100)
            * [Nader](https://github.com/w3c/did-use-cases/pull/122)
                - [Preview](https://pr-preview.s3.amazonaws.com/creatornader/did-use-cases/pull/122.html#messaging)
            - Needs New PR.
            - Expansion of messaging into protocols?
        * Issues:
            - [128](https://github.com/decentralized-identity/didcomm-messaging/pull/128) - to header semantics
            - [131](https://github.com/decentralized-identity/didcomm-messaging/pull/131) - from/to DID Query Parameters
        * Bluetooth Transport - possible work item?
            - [status/questions](https://hackmd.io/animo/didcomm-bluetooth-transport)
        *  

    * **Sidetree** (Daniel,Troy, Tobias) - [meeting page](https://docs.google.com/document/d/12l4wNkgkDn0tXxTPKB502gRXHa1hd7m0_KyebfRqMAo/edit)
        * SIP 1 status
            * Expected by the end of the month.
        * Canonical and equivalent identifiers status
        * Finalize rules for evaluation of operations and dropping of files
        * Spec / reference implementation inconsistencies
    * **SDS WG** (Kaliya, Dmitry, Tobias) - [meeting page](https://github.com/decentralized-identity/confidential-storage/blob/master/agenda.md)
        * new name: *Confidential Data Store Specification*
        * Discussion: Storage Operations, and Authorization Structure
    * Glossary group 
        * might come back to life with new work item(s)
            * Updates? 

3. **Additional Agenda items**
    * __DIF F2F Virtual meeting - January 19, Tuesday.__
        * [Sign up](https://www.eventbrite.com/e/dif-face-to-face-virtual-2-tickets-131061150429)
    * Track GitHub 
        * Reach out to the Chairs of WGs (where WG charter for IPR has been signed) with your Github handle to be added to the Github teams 
    * [MyData conference](https://online2020.mydata.org/tickets/) next two days!
        * DIF Member Domi Labs aG will be [talking about](https://www.linkedin.com/posts/domi-labs_event-digital-digitaltransformation-activity-6742433961647063040-EpvN) their work in the European Commission's Data Portability Services Incubator (DAPSI)
    * [Thoughtful Biometrics](https://thoughtfulbiometrics.org/) conference, featuring many DIF companies and independent researchers, will be in early February. In addition to the obvious authentication, security, ethics, and government/digital-ID topics, there will also be a technical focus on biometrics for less well-known use-cases, such as [key recovery](https://medium.com/decentralized-identity/dif-id-wg-starting-work-on-cryptographic-secret-recovery-204117b6a2ab?source=friends_link&sk=15e09af545daa6dc86fae39ee9ea632e).
    * Announcement from DID Auth WG: there will be a SIOP/DIF presentation at the Open Identity Exchange December workshop at 1500-1700 GMT.  information [here](https://openidentityexchange.org/networks/87/events.html?id=1031)

## Meeting - 25 Nov 2020 - (1100 ET) 
 
### Agenda

1. **Welcome and introductions**
2. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md)
        * BBS+ presentation by Tobias (Mattr)
            * answering questions about his IIW [presentation](https://www.youtube.com/watch?v=AVnCVzW0rkI)
            * Discussion questions
                * To what degree is this a VC "format", and to what degree is it a VP upgrade?
                * What standards need to change/upgrade for these additional values ("proofValue", "subjectAuthenticationMethod", etc.) to be widespread? Consequences for core VC spec, LD-Proof spec, etc?
                * How are domains and linked secrets related, in the Aries universe? Are systems outside of the Aries world using domain-based indirection?
                * How big is the "lift" (or level of effort) for Aries systems post-[RFC 47](https://github.com/hyperledger/aries-rfcs/blob/master/concepts/0047-json-ld-compatibility/README.md)?  How big for non-Aries systems already using LD-VCs today?  How big for JWT-native systems? 
                * [If time allows] Could we talk more about "Just-in-time Issuance" and "Trusted Witness" solutions?
        * ESSIF-LAB and Odyssey Momentum
            * tbd
    * **Identifiers & Discovery** (Markus, Sam) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
        * Questions around DID deactivation and resolution metadata
            * Can you verify a credential that was signed by a DID that has been deactivated?
            * older versions of a DID document - *version_id* and *version_time* parameters.
            * But support for those parameters is optional.
            * Sidetree's "checkpoint" feature
        * MIME types of DID documents - [issue](https://github.com/w3c/did-core/issues/208
        * Update on issues with [WebID](https://tcwiki.azurewebsites.net/index.php?title=Authentication_UX)
            * Potentially DIF should work on getting WebID into browsers
            * Opportunity for smooth iteration
            * WebAuthn is an option?
    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * Bloom Presentation: [The Wallet Credential Interactions Spec Proposal](https://specs.bloom.co/) by Jace Hensley
        * Next steps: Credential Schemas
        * Workitem Status: Presentation Exchange
            * Go Implementation Workday
            * JSONPath / Ontology Discussion Recap
            * [Open Issues](https://github.com/decentralized-identity/presentation-exchange/issues)
        * Workitem Status: Credentials Manifest calls
    * **DID Auth** (Oliver, Kyle) *half hibernated state*
        * blog article about OIDF collaboration
    * **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](hhttps://github.com/decentralized-identity/didcomm/blob/main/agenda.md)
        * First Complete Draft - reads correctly from beginning to end Nov 30th.
        * DIDComm.org Progress
            * https://github.com/decentralized-identity/didcomm.org
        * DIDcomm usecase to DID Core https://github.com/w3c/did-use-cases/pull/100
        * Issues:
            * [117](https://github.com/decentralized-identity/didcomm-messaging/pull/117) - forward secrecy
            * [124](https://github.com/decentralized-identity/didcomm-messaging/pull/124) - mime types
            * [127](https://github.com/decentralized-identity/didcomm-messaging/pull/127) - structured headers
            * [128](https://github.com/decentralized-identity/didcomm-messaging/pull/128) - to header semantics
            * [129](https://github.com/decentralized-identity/didcomm-messaging/pull/129) - post quantum
            * [126](https://github.com/decentralized-identity/didcomm-messaging/issues/126) - DIDDocs for Peer DIDs
    * **Sidetree** (Daniel,Troy, Tobias) - [meeting page](https://docs.google.com/document/d/12l4wNkgkDn0tXxTPKB502gRXHa1hd7m0_KyebfRqMAo/edit)
        * SIP 1 status [issue](https://github.com/decentralized-identity/sidetree/pull/928)
            * PR for renamed files and properties
        * Canonical and equivalent identifiers status
        * Spec / reference implementation inconsistencies
    * **SDS WG** (Kaliya, Dmitry, Tobias)
        * EDV and Hub Use Cases
            * Demos of what people are using it for now (navigator api, etc)
            * Present/talk about why people are investing in EDVs / being in this group. (Is there overlap between people's use cases?)
            * For example, primary EDV use case: Wallet backup / portability. Is that true for the group?


3. **Additional Agenda items**
    * DIF-wide strategic goals for 2021 (Juan) + [opinion poll](https://forms.gle/jkeC7tTvPr5Ux4vH7)
------------------------


## Meeting - 11 Nov 2020 - (1100 ET) 
 
### Agenda

1. **Welcome and introductions**
3. **Additional Agenda items**
    * DIF F2F Virtual ~mid January 
        * [planning doc v1](https://docs.google.com/document/d/1GcTbLMixs_iaVAJpkNHEZl_c4LH9bH_vrNbe-2cL0GY/edit#)
    * Technical Steering Committee at DIF  (max 10 min)
        * One WG Chair's point: sometimes WGs have difficult decisions about deduplication of efforts or recommendations-- would be good to have "higher authority" with which to consult for tricky judgment calls
        * Frees up Steering Committee for more internal, structural, governance, and business topics
3. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md)
        * [The What and Why of the DIF general-purpose Document-Loader](https://youtu.be/-yUbMDft5O0)  - by Orie Steele
        * [W3C-CCG Edu Creds Task Force & Tooling/Sandbox Intro](https://youtu.be/AEb02JGCArM) (Overview of CCG LD tooling) -  Kim H Duffy 
        * Kaliya book presentation and the Domains of Identity [book](https://g.co/kgs/T6T8LQ)
        * Gold-Button Interop (MyData panel next month by A. Gropper)
        * **Next call about BBS+** agenda and "homework links" [here](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md#agenda---18-nov-2020---useu-time-0600-pst)
    * **Identifiers & Discovery** (Markus, Sam) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
        * [DID WG meeting review during TPAC](https://docs.google.com/presentation/d/1RoE8E4y8S1j65EJaXZ8oihkduNbjTXXvdwtkzw961Xw/)
            * privacy violating properties
            * Abstract Data Model (ADM)
            * language that describes how to add and register new representations
            * Work on "security" and "privacy" in DID Rubric: https://github.com/w3c/did-rubric/pull/10
            * Video Recording of Markus's TPAC resolutions/action items overview [here](https://us02web.zoom.us/rec/share/kupVdGlwe30wjuPFmHBfUG_toosS9Hv-2rl1pReIMWVrODDkJATa7MErNGk0FoQD.J2Ho-Tz_5ZYq3n8D)
        * Fuzzy vault - C++? 
        * Updates on current work items did:peer, KERI, Universal Resolver, .well-known DID configuration, DID parameters, secret recovery mechanisms
        * KERI:
            * "mini conference" on API design in about a month's time
            * additional KERI meeting the hour before the current meeting time for use-cases and spec-authoring discussions to preserve the weekly meeting for #techTalk
    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](hhttps://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * Credential Manifest 
            * Reuse existing Presentation Exchange call time and shift focus towards Credential Manifest.
            * Review Daniel Status
        * IIW recap
        * Affinidi presentation in C&C [Recording](https://us02web.zoom.us/rec/share/3IYGkxbiCJG9acGTsoie_TQYWu8nKacNUcHEZPFx6yyMTjgp4-R_LsrE4SODrlAF.5dwcWpUCRYgI0BAs)
        * Presentation Exchange Status
            * [Multiple Schema identifiers](https://github.com/decentralized-identity/presentation-exchange/pull/149)
            * [Holder Binding between credentials](https://github.com/decentralized-identity/presentation-exchange/pull/123)
    * **DID Auth** (Oliver, Kyle) *half hibernated state*
        * blog article about OIDF collaboration
    * **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://docs.google.com/document/d/1BpTm5SmgfOJcEsXfizO0ZmH1r7imTJDGKudAZtYsm0M/edit?usp=sharing)
        * Spec milestones
            * First Complete Draft reads completely by end of November
            * Next Complete Draft - Eliminate all TODOs
        * https://github.com/w3c/did-use-cases/pull/100
        * Switching to HackMD note taking from next week
        * Mime Types
            * [PR 124](https://github.com/decentralized-identity/didcomm-messaging/pull/124)
            * [Strategy Sheet](https://docs.google.com/spreadsheets/d/1VZz8J2Uz4nab-SY4pvhKd1_eipoEo9kGiqU5iaMYVsY/edit#gid=0)
        * PR/Issues:
            * Pick an issue you think can be closed
            * Pick an issue that shouldn’t be, and comment on what is needed next on the issue.
    * **Sidetree** (Daniel,Troy, Tobias) - [meeting page](https://docs.google.com/document/d/12l4wNkgkDn0tXxTPKB502gRXHa1hd7m0_KyebfRqMAo/edit)
        * Working through issues
    * **SDS WG** (Kaliya, Dmitry, Tobias)
        * GNAP Presentation by Justin Richer
            * [Filling in the GNAP - Justin Richer](https://justinsecurity.medium.com/filling-in-the-gnap-a032453eaf8c)
            * [OAuth 3](https://oauth.net/3/)
        * Spec Rename Update/Announcement (spoiler: Confidential Data Store)
        * Special Topic Discussion: Integrating Hubs & Vaults in the spec


## Meeting - 28 Oct 2020 - (1100 ET) 
 
### Agenda

1. **Welcome and introductions**
2. **Additional Agenda items**
    * Impressions from IIW #31 
        * Sessions
            * OIDC connect propocols - "credential providers"/ Mattr, only for issuance
            * The new SIOP - OIDC way
                * comment: DIDcomm way is also very intersting
                * the two ways are complimentary
            * Scaling using zKP rollups + hiding state info
    * best sessions
3. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md)
        * last call of contributions on Transcommunity map
        * Crowd-sourcing an #IIW31 *Interop-relevant* Reading List
        * working draft [here](https://github.com/decentralized-identity/interoperability/blob/master/assets/iiw31guide.md)
        * host a special meeting focused on 
            * coordinate on JSON-LD/ZKP/BBS+ work(s)
            * cross ledger revocation
    * **Identifiers & Discovery** (Markus, Sam) - [meeting page]
        * From IIW: did:indy https://hackmd.io/@icZC4epNSnqBbYE0hJYseA/S1eUS2BQw
        * From IIW: Opt-in discovery rather than passive discovery by Daniel Hardman
        * Websites and browser interactions 
        * Implementation updates
            * Implementing .well-known 
            * Python implementation of Fuzzy Vault is available now: https://github.com/decentralized-identity/fuzzy-encryption/tree/master/src/python
            * WASM bundle
        * Current topics in DID Core spec
        * Updates on current work items did:peer, KERI, Universal Resolver, .well-known DID configuration, DID parameters, secret recovery mechanisms
    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * No major updates due to IIW
    * **DID Auth** (Oliver, Kyle) *half hibernated state* -
        * DIF - OIDF liaison agreement and collaboration 
    * **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://docs.google.com/document/d/1BpTm5SmgfOJcEsXfizO0ZmH1r7imTJDGKudAZtYsm0M/edit?usp=sharing)
        * Milestones
            * First Complete Draft - reads correctly from beginning to end Oct 30th
            * Next Complete Draft - Eliminate all TODOs
        * DIDComm.org Progress
            * Repo exists
        * IIW Recap
            * DIDComm WG Update
            * DIDComm Mediators
            * Mark Miller talk - https://youtu.be/NAfjEnu6R2g
            * D Web - 
        * MIME Types for DIDComm PR 124 (Daniel Hardman)
        * PR/Issues:
            * Future Encoding
                * [PR 122](https://github.com/decentralized-identity/didcomm-messaging/pull/122)
                * [PR 121](https://github.com/decentralized-identity/didcomm-messaging/pull/121) - Queue Transport to return-route extension
                * [PR 123](https://github.com/decentralized-identity/didcomm-messaging/pull/123) - Outline adjustments
                * [PR 117](https://github.com/decentralized-identity/didcomm-messaging/pull/117) - Perfect Forward Secrecy details (Not updated yet)
    * **Sidetree** (Daniel,Troy, Tobias) - [meeting page](https://docs.google.com/document/d/12l4wNkgkDn0tXxTPKB502gRXHa1hd7m0_KyebfRqMAo/edit)
        * property renaming status 
        * Follow-ups
            * remove `verificationMethod` enum value in public key `purpose`
            * Align remove-public-keys and remove-services on use of `ids` property
            * Question: how do you change the purposes using patches?
        * Controller in patches
        * Compact JWS -> JSON JWS
        * Output the DID document according to the latest did-core spec (rename publicKey to verificationMethod)S
        * SIP 1
        * SIP 2
        * Canonical and equivalent identifiers status
        * Common protocol parameter format 
    * **SDS WG** (Kaliya, Dmitry, Tobias)
        * SDS meeting this week will feature Justin Richer talking about GNAP (formerly OAuth.XYZ) for people researching cutting-edge authorization/authentication 
4. **Discussion topics**
    * on Fridays we host DIF governance calls, feel free to join 


### Proposals
-proposals here-

### Attendees
- 

