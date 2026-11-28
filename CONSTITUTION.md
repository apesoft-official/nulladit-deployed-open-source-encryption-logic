# NODSEL — NULLADIT Deployed Open Source Encryption Logic — Engineering constitution

Publish only reviewed encryption source corresponding to verified deployed releases, plus clearly labeled tests and explanatory material. Record release identifiers, source revisions, hashes, algorithm parameters, dependencies, test vectors and known limitations. Do not silently substitute experimental code or claim quantum safety or formal proof without evidence. Verify source-to-artifact correspondence where possible; explicitly mark gaps. Never export secrets, real user data, private node internals or confidential operational configuration. Use allowlisted exports, provenance review and secret scanning. Every relevant production encryption sweep must assess and synchronize NODSEL, or report blockers.

All changes must preserve the repository's trust boundary and distinguish design intent from verified results.

## Aurora Covenant boundary
The original eight NULLADIT contracts remain the constitutional base. Aurora Covenant is a proposed subordinate release registry only; it does not itself verify source-to-binary correspondence or establish cryptographic safety. NODSEL continues to document actual deployed encryption logic only after independent provenance and release verification. No repository publication constitutes governance approval or deployment.


## Wallet authentication and pool-observation boundary

Proof of control of a wallet establishes control of a cryptographic account only. It does not establish human identity, benign intent, verified-node status, governance eligibility, or authority to inspect NULLADIT network state.

An ordinary messaging account shall never receive unrestricted ability to enumerate, observe, or query the message or envelope pool. It may request only recipient-scoped results through short-lived, purpose-bound capabilities or equivalent privacy-preserving selectors. A response must not reveal whether an unrelated recipient, message, or relationship exists. Padding, batching, cover traffic, and blinded lookup mechanisms should be used where compatible with the approved protocol.

Pool-wide or operational observation shall be limited to verified nodes and only to the minimum scope required for routing, storage, delivery, or independently authorized security work. Every protected-data request must be authenticated, purpose-scoped, rate-limited, replay-resistant, and capable of producing independently verifiable audit evidence. Creating or rotating to a new wallet does not exempt a requester from these controls.

VESTIGIUM may anchor an opaque commitment to evidence of a signed request, including its network domain, requesting wallet or authorized node key, request nonce, request class, bounded time reference, and policy or result code. It shall not place message content, recipient identity, communication relationships, legal identity, IP address, browser fingerprint, device identifier, location, raw challenge response, or raw evidence on a public ledger. A commitment proves that evidence was submitted under a cryptographic key; it does not prove the human identity or malicious intent of the key's controller. Adverse action requires independent review and must account for ordinary activity, compromise, error, and innocent participation.

Sybil resistance may use transparent, governance-approved registration rules, uniform privacy-preserving rate limits, or capability probation. It shall not convert a legitimate recipient claim into a node-imposed payment gate, identity-disclosure requirement, or surveillance mechanism. A verified node remains subject to least privilege because legitimate access to some traffic does not authorize observation of unrelated traffic.

This article interprets and supplements the existing Presumption of Digital Inviolability and equal-access requirements. It grants no decryption power, administrative privilege, mining authority, governance vote, contract authority, or deployment approval, and it does not modify or override the original eight founding contracts. Documentation alone does not implement these controls; enforceable claims require compatible protocol, node, and client behavior supported by reviewable evidence.
