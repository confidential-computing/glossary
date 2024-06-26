## Matrix

| Term                                  | Definition (Summarized)                                                                                                                    | Linked Resources                                                                                                             |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| **Confidential Computing**            | The protection of data in use by performing computation in a hardware-based, attested Trusted Execution Environment.                        | [CCC](https://confidentialcomputing.io)                                                                                      |
| **Confidential Payload**              | A set of code and data specifically designed to be executed within Trusted Execution Environments (TEEs) while maintaining strict confidentiality and integrity.                         |                                                                  |
| **Workload Identity**                 | Unique identity assigned to software workloads for authentication and access management across services and resources.                             | [Microsoft Learn](https://learn.microsoft.com/en-us/entra/workload-id/workload-identities-overview)                         |
| **Remote Attestation**                | A process whereby a system produces information about itself (typically cryptographically-backed) and another party verifies that information, allowing decisions to be made about what types of trust relationships are appropriate to the first system. | [IETF RFC 9334](https://datatracker.ietf.org/doc/html/rfc9334), [CCC Blog](https://confidentialcomputing.io/2023/04/06/why-is-attestation-required-for-confidential-computing/)         |
| **Enclave**                           | A secure area of a processor chip that ensures code and data loaded inside are protected from access or tampering by other software, including the operating system. | [CCC](https://confidentialcomputing.io/wp-content/uploads/sites/10/2023/03/CCC-A-Technical-Analysis-of-Confidential-Computing-v1.3_unlocked.pdf)         |
| **TEE** (Trusted Execution Environment) | An environment that provides a level of assurance of data confidentiality, integrity, and code integrity by preventing unauthorized entities from viewing, altering, or tampering with data and code in use within the TEE. | [CCC](https://confidentialcomputing.io/wp-content/uploads/sites/10/2023/03/CCC-A-Technical-Analysis-of-Confidential-Computing-v1.3_unlocked.pdf)         |
| **TCB** (Trusted Computing Base)      | A set of components that can be known and defined, evaluated and verified by a trusting party or its agents, expected to continue in the same state, and used as the foundation for other services or systems. This represents the critical security components including hardware, firmware, and software. | [Wikipedia](https://en.wikipedia.org/wiki/Trusted_computing_base), [Bursell, Mike (2021) Trust in Computer Systems and the Cloud](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119695158), [NIST](https://csrc.nist.gov/glossary/term/trusted_computing_base), [Microsoft Azure](https://learn.microsoft.com/en-us/azure/confidential-computing/trusted-compute-base) |
| **Memory Isolation**                  | Security feature preventing unauthorized access to data in memory.                                                                         | [Microsoft Azure](https://learn.microsoft.com/en-us/azure/confidential-computing/choose-confidential-containers-offerings)                                                           |
| **Measurements**                      | Process of assessing the state of a system or components to ensure integrity.                                                              | [NIST](https://csrc.nist.gov/glossary/term/roots_of_trust)                                                    |
| **Root of Trust**                     | A static component in a system whereby an endorsing authority allows trustors to assume trust in the system in which the anchor is contained. Trust in the root of trust is assumed, based on the endorsing authority, rather than derived. | [Wikipedia on Trust Anchor](https://en.wikipedia.org/wiki/Trust_anchor), [Bursell, Mike (2021) Trust in Computer Systems and the Cloud](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119695158)                      |
| **Attestation Verification Service**  | Services that verify the integrity and authenticity of attestations in secure computing environments, playing a critical role in establishing trust. | [Azure Attestation](https://learn.microsoft.com/en-us/azure/attestation/overview), [Red Hat on Confidential Computing](https://www.redhat.com), [Veraison Project on GitHub](https://github.com/veraison) |