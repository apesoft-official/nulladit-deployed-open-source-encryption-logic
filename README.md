# NODSEL — NULLADIT Deployed Open Source Encryption Logic

**Deployed cryptography · Public accountability**

Trust in cryptography should rest on inspectable algorithms, implementations and evidence, not on the reputation of their author. NODSEL is the designated public record of the actual encryption logic users of updated NULLADIT releases are trusting.

## Publication standard
For each verified deployed revision, publish the relevant source, algorithm and parameter specifications, test vectors, dependency versions, security assumptions, limitations and a mapping to deployed release identifiers and artifact hashes. Distinguish source inspection from proof that a particular binary corresponds to that source.

## Scope
Hybrid elliptic-curve and lattice-based cryptography belongs here only to the extent actually deployed and verified. Experimental PELAVIUM constructions belong in their separate research repository until adopted and deployed. Never publish production secrets or proprietary node internals.

## Evidence status
This repository's purpose is not itself evidence of source-to-release parity. Until matching source, manifests and verification results are published, that parity remains unverified.

All contributions follow the [engineering constitution](CONSTITUTION.md).

## The architecture of trust
Privacy is not a privilege conferred by an intermediary. NULLADIT seeks to make confidential communication an architectural property rather than a promise of institutional discretion. Independent operation, verifiable cryptography and interoperable clients are complementary goals, not substitutes for security review. No system is invulnerable; claims must follow evidence.

| Project | Responsibility |
| --- | --- |
| NULLADIT Core | Proprietary protocol and node operations; private repository |
| [NOMC](https://github.com/apesoft-official/nulladit-opensource-messenger-client) | Public messenger clients, device installers and independent web/app builds |
| [NODSEL](https://github.com/apesoft-official/nulladit-deployed-open-source-encryption-logic) | Public transparency for actual deployed encryption revisions |
| [PELAVIUM](https://github.com/apesoft-official/nulladit-pelavium) | Experimental privacy research, not deployed |


Aurora graph deployment was reported on November 27, 2026, but does not establish deployed encryption provenance; see [AURORA-COVENANT.md](AURORA-COVENANT.md).

Developed by **Apesoft Canada** · **Inviolable Conversations**


The proposed [VESTIGIUM accountability contract](https://github.com/apesoft-official/nulladit-pelavium/blob/main/VESTIGIUM.md) does not establish encryption source-to-artifact provenance; its child deployment and bytecode remain independently unverified.

## VESTIGIUM — Evidence without surveillance

Read the [Doctrine of Evidentiary Restraint](VESTIGIUM-PHILOSOPHY.md). **Prove the violation, not the conversation.** VESTIGIUM is a proposed accountability doctrine, not a deployed surveillance or access mechanism.

## NULL22 representation and node rewards

See the [NULL22 Representation and Node Service Compensation policy](TOKEN-REPRESENTATION-AND-NODE-REWARDS.md). It records Apesoft's representation limits and the proposed opt-in Proof-of-Service reward standard; it does not determine legal classification or replace applicable valuation and reporting rules.


## NSELCBA boundary

NSELCBA is a separate research-only operator-compensation attestation, not encryption logic or an integrated client release. A standalone contract deployment was reported on November 28, 2026; independent bytecode reconciliation remains outstanding. It is documented in [PELAVIUM](https://github.com/apesoft-official/nulladit-pelavium/tree/main/research) and the private NULLADIT Core. It is not part of NODSEL's deployed-encryption source, release manifest, or source-to-artifact mapping.

See [the consolidated deployment and whitepaper bulletin](WHITEPAPER-DEPLOYMENT-UPDATE-2026-11-28.md) for recorded addresses and evidence limitations. No mining or production activation is implied.
