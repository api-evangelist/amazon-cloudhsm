# Amazon CloudHSM (amazon-cloudhsm)
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
- [NaftikoCapability](capabilities/cryptographic-key-management.yaml)

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

## Capabilities

### Shared Per-API Definitions

- [Amazon CloudHSM](capabilities/shared/cloudhsm.yaml) — 6 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Cryptographic Key Management](capabilities/cryptographic-key-management.yaml) | Amazon CloudHSM | 6 | Security Engineer |

## Vocabulary

- [Amazon CloudHSM Vocabulary](vocabulary/amazon-cloudhsm-vocabulary.yaml) — Unified taxonomy covering operations, workflows, and personas

## Rules

- [Amazon CloudHSM Spectral Rules](rules/amazon-cloudhsm-spectral-rules.yml) — 19 rules enforcing Amazon CloudHSM API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
