# RFC 0000: Open Vision Manifesto

- **Status:** Foundational direction
- **Audience:** Contributors, partners, and the public
- **Scope:** Vision and product principles, not a technical specification

## Vision

OpenVision exists to make first-person experiential media trustworthy, useful, and worthy of human confidence.

We want people to be able to capture meaningful moments from their own point of view, replay them later, share them privately when they choose, and understand where the media came from and how it has changed. The aim is not to reproduce consciousness or claim access to memory. It is to build tools for preserving and communicating experience with honesty about their limits.

Over time, OpenVision should support an open and decentralized ecosystem in which people, devices, applications, and services can participate without surrendering human agency. Open collaboration and proprietary implementation can coexist: shared interfaces, portable records, and public trust principles can form common ground while organizations still compete in products and implementation.

## The problem

Today's media systems are good at recording and distributing images, but they often lose the context that makes a first-person record meaningful and trustworthy. People face several connected problems:

- personal recordings are frequently trapped in devices, applications, or accounts;
- replay rarely preserves the sense of seeing from a particular person's point of view;
- sharing controls are often coarse, permanent, or difficult to understand;
- editing and generative tools make a media item's origin and history harder to assess;
- trust is too often framed as a binary claim that software can determine whether any media is “real” or “fake.”

OpenVision addresses these problems as one product direction: trusted capture, faithful replay, private sharing, and inspectable provenance.

## Product principles

1. **Start with human experience.** Preserve the meaning of a moment for the person who captured it and for the people they intentionally invite to experience it.
2. **Earn trust through clarity.** Explain what is known, what has been declared, and what remains unknown. Do not turn uncertainty into a stronger claim.
3. **Keep people in control.** Capture, retention, access, sharing, and deletion should be understandable choices, not hidden defaults.
4. **Design for private sharing first.** Intimate experiential media should not require public distribution or loss of control in order to be useful.
5. **Preserve portability.** People should be able to retain and move their records without depending forever on one product or provider.
6. **Separate source from transformation.** Enhancements and synthetic additions should not silently replace or obscure the status of source material.
7. **Progress without pretending perfection.** Each release should provide useful, testable improvements while stating its limits plainly.
8. **Make accessibility part of the product.** Capture and replay should respect different bodies, senses, abilities, and comfort needs.

## Trust and provenance

Verified provenance is not universal AI-fake detection. A valid record of origin can support a specific claim about how participating tools handled media; it cannot prove that all media outside that system is false, detect every manipulation, or establish the full truth of the event shown.

OpenVision uses three top-level trust states:

- **Verified capture:** participating systems can verify the media's declared capture origin and the history they attest to.
- **Declared synthetic or enhanced:** synthetic, reconstructed, generated, or materially enhanced content is explicitly identified as such.
- **Unknown provenance:** origin or history cannot be sufficiently verified. Unknown does not mean fake; it means the system should not claim more than it knows.

These states should remain visible through replay, export, and sharing. Trust information should be understandable by people, inspectable by tools, and resilient when media moves between services. No provenance label should be presented as a substitute for context, journalism, consent, or human judgment.

## Privacy and human agency

First-person media can reveal places, relationships, routines, voices, identities, and bystanders. Privacy is therefore a foundation of the product, not a setting added later.

OpenVision will pursue:

- meaningful consent for the recorder and respect for affected people;
- data minimization and purpose-limited collection;
- private-by-default storage and sharing experiences;
- clear, revocable access wherever revocation remains technically possible;
- strong protection for records at rest and in transit;
- understandable retention, export, and deletion controls;
- safeguards against covert recording, abuse, unlawful surveillance, and deceptive use;
- honest disclosure when a privacy or revocation guarantee cannot be maintained after a recipient exports or copies media.

The person represented by a recording is not merely a source of data. Product decisions should preserve dignity, autonomy, and the ability to decline participation.

## An open ecosystem

OpenVision should grow through public discussion, interoperable foundations, and collaboration across research, industry, creators, civil society, and the open-source community.

The project will favor:

- public proposals for shared concepts, interfaces, and trust expectations;
- portable records and compatibility across devices and applications;
- reference implementations and test materials that contributors have the right to share;
- transparent governance and recorded trade-offs;
- independent implementations that can interoperate without requiring one central operator;
- room for commercial and proprietary products, provided they make accurate compatibility and trust claims.

Decentralization is a long-term direction, not a claim that every component must be distributed from the first release. We will prioritize practical interoperability and user control, then reduce unnecessary dependence on centralized services as the ecosystem matures.

## High-level roadmap

### Phase 0: Establish the foundation

Build the public vocabulary, ethical boundaries, governance, contribution process, and initial interoperability direction. Make trust claims and limitations understandable from the beginning.

### Phase 1: Capture and replay

Deliver a useful path for people to create first-person records and replay them across supported experiences, with clear provenance states and user control.

### Phase 2: Private sharing

Make consent-aware, selective sharing a first-class experience. Improve portability, access controls, and transparent handling across participating applications and services.

### Phase 3: Ecosystem interoperability

Enable multiple implementations to exchange and replay records while preserving declared provenance and privacy expectations. Expand public conformance work and community governance.

### Phase 4: Open and decentralized participation

Support broader participation by devices, applications, services, and communities without requiring a single trusted intermediary. Continue evolving the ecosystem through public proposals and independently verifiable compatibility.

This roadmap is directional. Movement between phases depends on demonstrated user value, safety, privacy, and trustworthiness—not only technical capability.
