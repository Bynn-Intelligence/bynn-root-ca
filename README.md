# Bynn Intelligence Root Certificate Authority (CA)

## Download

[Download Bynn Root CA (.crt)](https://static.bynn.com/cert/bynn-root-ca.crt)

***

## Certificate Details

### Subject & Issuer

| Field                   | Value                     |
| ----------------------- | ------------------------- |
| **Country**             | US                        |
| **State**               | California                |
| **Locality**            | San Francisco             |
| **Organization**        | Bynn Intelligence, Inc.   |
| **Organizational Unit** | Quantum Security Division |
| **Common Name**         | Bynn Intelligence Root CA |

> **Note:** This is a self-signed root certificate; thus, the Subject and Issuer fields are identical.

### Validity Period

* **Not Before:** Tuesday, 12 November 2024 at 15:05:04 WET
* **Not After:** Saturday, 6 November 2049 at 15:05:04 WET

### Technical Specifications

| Attribute                | Details                                                     |
| ------------------------ | ----------------------------------------------------------- |
| **Serial Number**        | 61 2C 65 4B C4 72 F0 A6 B9 9B D9 72 AC 7E 25 45 F0 F1 12 5E |
| **Version**              | 3                                                           |
| **Signature Algorithm**  | SHA-256 with RSA Encryption (1.2.840.113549.1.1.11)         |
| **Public Key Algorithm** | RSA Encryption (1.2.840.113549.1.1.1)                       |
| **Key Size**             | 4096 bits                                                   |
| **Exponent**             | 65537                                                       |

### Key Usage

* Digital Signature
* Certificate Signing
* Certificate Revocation List (CRL) Signing

> **Critical:** Yes

### Basic Constraints

* Certificate Authority: Yes

> **Critical:** Yes

### Extensions

| Extension                    | Value                                                       |
| ---------------------------- | ----------------------------------------------------------- |
| **Subject Key Identifier**   | 20 ED DF 87 66 BE 57 79 D4 41 76 2F B1 21 07 80 E8 7F 39 51 |
| **Authority Key Identifier** | 20 ED DF 87 66 BE 57 79 D4 41 76 2F B1 21 07 80 E8 7F 39 51 |

### Fingerprints

| Algorithm   | Fingerprint                                                                                     |
| ----------- | ----------------------------------------------------------------------------------------------- |
| **SHA-256** | C8 0D B9 6A 6D A9 39 78 4A DB 14 C4 59 4E 28 75 9E B3 C0 B1 87 11 BF 30 87 93 F4 92 11 98 DF CA |
| **SHA-1**   | 6D 76 62 21 EA 2C 41 BC ED AD 7B 39 37 8F 33 22 6C 40 57 C8                                     |

***

## Deployment Instructions for IT Administrators

To securely deploy the Bynn Root CA certificate within your organization:

1. **Import Certificate:**\
   Add the Bynn Root CA certificate to your domain controller's "Trusted Root Certification Authorities" store.

2. **Distribute via Group Policy (GPO):**\
   Configure Group Policy to automatically deploy the certificate to all managed workstations.

3. **Verify Installation:**\
   Ensure the certificate is installed and trusted on all endpoints.

4. **Maintain Certificate Trust:**\
   Trusting the root certificate enables automatic validation of all subordinate certificates issued by Bynn.

***

## Security and Compliance

Bynn maintains stringent standards for certificate management, including:

* Secure handling of private keys
* Regular security audits
* Comprehensive certificate revocation procedures
* Timestamped digital signatures for traceability

For support or inquiries, contact our team at [support@bynn.com](mailto:support@bynn.com).
