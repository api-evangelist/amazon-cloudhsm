# Amazon CloudHSM (amazon-cloudhsm)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AWS CloudHSM is a cloud-based hardware security module (HSM) that enables you to manage cryptographic keys on dedicated FIPS 140-2 Level 3 validated, single-tenant HSM instances running within your own VPC for regulatory compliance and data security.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-cloudhsm/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, CloudHSM, Security, Cryptography, HSM, Compliance

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon CloudHSM API
API for creating and managing CloudHSM clusters and HSM instances for dedicated hardware-based cryptographic key management.

**Human URL:** [https://aws.amazon.com/cloudhsm/](https://aws.amazon.com/cloudhsm/)

#### Tags:

 - AWS, CloudHSM, Security, Cryptography

#### Properties

- [Documentation](https://docs.aws.amazon.com/cloudhsm/latest/APIReference/)

- [APIReference](https://docs.aws.amazon.com/cloudhsm/latest/APIReference/)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/cloudhsm/)
- [SpectralRules](rules/amazon-cloudhsm-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-cloudhsm-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| FIPS 140-2 Level 3 Validated | Dedicated single-tenant HSM instances meeting the highest FIPS validation levels. |
| Full Key Control | Complete control over cryptographic keys with no AWS access to key material. |
| Elastic Capacity | Add or remove HSMs from clusters as needed, paying only for active resources hourly. |
| High Availability | Multi-AZ HSM clusters provide redundancy and automatic failover. |
| Industry-Standard APIs | Supports PKCS#11, Java JCE, and Microsoft CNG APIs for application integration. |

## Use Cases

| Name | Description |
|------|-------------|
| Data Encryption | Protect sensitive data with hardware-backed encryption keys. |
| SSL/TLS Offloading | Manage SSL/TLS certificates and private keys in dedicated HSMs. |
| Certificate Authority | Secure private CA keys for organizations issuing their own certificates. |
| Database Encryption | Support transparent data encryption (TDE) for Oracle and SQL Server databases. |
| Regulatory Compliance | Meet PCI DSS, HIPAA, and other regulatory requirements for key management. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon RDS | Use CloudHSM keys for Oracle TDE and SQL Server TDE in RDS. |
| AWS KMS | Use CloudHSM as a custom key store for AWS KMS operations. |
| Amazon VPC | HSM instances run inside your VPC for network isolation. |
| AWS IAM | Control access to HSM cluster management operations. |
| AWS CloudTrail | Audit HSM management API calls via CloudTrail. |

## Artifacts

### JSON Schema

- No schemas generated

### JSON-LD

- [Amazon CloudHSM Context](json-ld/amazon-cloudhsm-context.jsonld)

## Vocabulary

- [Amazon CloudHSM Vocabulary](vocabulary/amazon-cloudhsm-vocabulary.yaml) — Unified taxonomy covering operations, workflows, and personas

## Rules

- [Amazon CloudHSM Spectral Rules](rules/amazon-cloudhsm-spectral-rules.yml) — 19 rules enforcing Amazon CloudHSM API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
