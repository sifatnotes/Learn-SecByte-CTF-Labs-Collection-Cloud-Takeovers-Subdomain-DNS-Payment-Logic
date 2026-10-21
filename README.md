# Learn-SecByte-CTF-Labs-Collection-Cloud-Takeovers-Subdomain-DNS-Payment-Logic
A curated collection of hands-on cybersecurity CTF labs covering Subdomain &amp; Dangling DNS Takeovers, Bucket Takeovers, Currency &amp; Payment Logic Abuse, IDOR Billing, and Cloud Resource Hijacking from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on Cloud Infrastructure and Domain Hijacking (Subdomain Takeovers, Dangling DNS records, Bucket Takeovers, Expired Domain Hijacking, Cloud Resource Hijacking), and Fintech & Business Logic Exploitation (Currency Manipulation, Decimal Precision Abuse, Installment Manipulation, Duplicate Payment Processing, Payment State Desynchronization, Invoice ID Guessing IDOR, Wallet Credit Abuse) labs designed for cybersecurity students, CTF players, cloud security engineers, bug bounty hunters, application security auditors, and financial systems pen testers.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Securing modern web assets and fintech workflows requires an understanding of infrastructure state lifecycle vulnerabilities as well as complex payment business logic flaws. Hosted on [Learn SecByte](https://learn.secbyte.org/), this advanced domain takeover, cloud asset hijacking, and payment logic exploitation collection provides practical, hands-on technical training to audit, exploit, and remediate cloud resource misconfigurations and financial transaction vulnerabilities.

From detecting dangling CNAME records pointing to unclaimed S3/Azure Blob storage containers, claiming orphaned cloud buckets, takeover of expired domain assets, and mitigating cloud identity metadata hijacking to manipulating floating-point decimal precision in payment gateways, exploiting currency conversion logic, desynchronizing payment webhooks, and executing IDOR attacks against billing invoices, these exercises establish critical offensive testing and defensive engineering skills.

---

## Lab Collection & Index

Below is the complete, searchable index of all cloud infrastructure takeover, domain hijacking, and payment business logic challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Subdomain Takeover: From Detection to Defensive Validation** | Cloud Takeover, Dangling DNS & Asset Hijacking | Dangling CNAME record identification, orphaned third-party SaaS routing (GitHub Pages, Heroku, Azure), verification proofs | [Access Lab](https://learn.secbyte.org/ctf/subdomain-takeover-from-detection-to-defensive-validation) |
| 2 | **Dangling DNS Takeover: From Detection to Validation** | Cloud Takeover, Dangling DNS & Asset Hijacking | Stale DNS pointer resolution, orphaned cloud service endpoints, automated DNS recon, defensive validation mechanisms | [Access Lab](https://learn.secbyte.org/ctf/dangling-dns-takeover-from-detection-to-validation) |
| 3 | **Bucket Takeover** | Cloud Takeover, Dangling DNS & Asset Hijacking | Orphaned AWS S3 / Azure Blob storage buckets, namespace registration, public data hosting hijacking, bucket policy takeover | [Access Lab](https://learn.secbyte.org/ctf/bucket-takeover) |
| 4 | **Expired Domain Takeover** | Cloud Takeover, Dangling DNS & Asset Hijacking | Secondary domain expiration monitoring, reverse WHOIS correlation, brand asset hijacking, supply chain email vector abuse | [Access Lab](https://learn.secbyte.org/ctf/expired-domain-takeover) |
| 5 | **Cloud Resource Hijacking: Identity, Metadata, and Misuse** | Cloud Takeover, Dangling DNS & Asset Hijacking | Unattached cloud identities, metadata server credentials, serverless function hijacking, orphaned resource exploitation | [Access Lab](https://learn.secbyte.org/ctf/cloud-resource-hijacking-identity-metadata-and-misuse) |
| 6 | **Currency Manipulation Abuse: Pricing Logic & Payment Controls** | Fintech, Billing & Payment Logic Exploitation | Multi-currency shopping cart tampering, exchange rate rounding exploits, negative currency value inputs, checkout bypass | [Access Lab](https://learn.secbyte.org/ctf/currency-manipulation-abuse-pricing-logic-payment-controls) |
| 7 | **Decimal Precision Abuse** | Fintech, Billing & Payment Logic Exploitation | Floating-point truncation vs. rounding flaws, fractional cent transaction accumulation, balance inflation logic bugs | [Access Lab](https://learn.secbyte.org/ctf/decimal-precision-abuse) |
| 8 | **Installment Manipulation** | Fintech, Billing & Payment Logic Exploitation | Buy Now Pay Later (BNPL) logic flaws, installment calculation parameter tampering, total order price manipulation | [Access Lab](https://learn.secbyte.org/ctf/installment-manipulation) |
| 9 | **Duplicate Payment Processing** | Fintech, Billing & Payment Logic Exploitation | Race conditions in payment execution endpoints, missing transaction idempotency keys, duplicate credit balance updates | [Access Lab](https://learn.secbyte.org/ctf/duplicate-payment-processing) |
| 10 | **Payment State Desync** | Fintech, Billing & Payment Logic Exploitation | Asynchronous webhook status tampering, payment processor state machine mismatch, order status parameter overriding | [Access Lab](https://learn.secbyte.org/ctf/payment-state-desync) |
| 11 | **Invoice ID Guessing: IDOR Billing** | Fintech, Billing & Payment Logic Exploitation | Sequential invoice ID enumeration, broken access control in PDF generation endpoints, private financial record leaks | [Access Lab](https://learn.secbyte.org/ctf/invoice-id-guessing-idor-billing) |
| 12 | **Wallet Credit Abuse: Business Logic Exploitation Lab** | Fintech, Billing & Payment Logic Exploitation | Promotional coupon stacking, wallet balance reload logic bypasses, negative refund request abuse, double spending | [Access Lab](https://learn.secbyte.org/ctf/wallet-credit-abuse-business-logic-exploitation-lab) |

---

## Categories

### 1. Cloud Takeovers, Dangling DNS & Asset Hijacking
Identify dangling CNAME records, reclaim orphaned AWS S3 and Azure Blob buckets, re-register expired domain names linked to enterprise services, and reclaim abandoned cloud identities.
- [Subdomain Takeover: From Detection to Defensive Validation](https://learn.secbyte.org/ctf/subdomain-takeover-from-detection-to-defensive-validation)
- [Dangling DNS Takeover: From Detection to Validation](https://learn.secbyte.org/ctf/dangling-dns-takeover-from-detection-to-validation)
- [Bucket Takeover](https://learn.secbyte.org/ctf/bucket-takeover)
- [Expired Domain Takeover](https://learn.secbyte.org/ctf/expired-domain-takeover)
- [Cloud Resource Hijacking: Identity, Metadata, and Misuse](https://learn.secbyte.org/ctf/cloud-resource-hijacking-identity-metadata-and-misuse)

### 2. Fintech, Billing & Payment Logic Exploitation
Examine payment gateway parameters, exploit currency conversion rounding errors, bypass installment calculations, trigger race conditions for double spending, desynchronize payment webhooks, and exfiltrate billing records via IDOR.
- [Currency Manipulation Abuse: Pricing Logic & Payment Controls](https://learn.secbyte.org/ctf/currency-manipulation-abuse-pricing-logic-payment-controls)
- [Decimal Precision Abuse](https://learn.secbyte.org/ctf/decimal-precision-abuse)
- [Installment Manipulation](https://learn.secbyte.org/ctf/installment-manipulation)
- [Duplicate Payment Processing](https://learn.secbyte.org/ctf/duplicate-payment-processing)
- [Payment State Desync](https://learn.secbyte.org/ctf/payment-state-desync)
- [Invoice ID Guessing: IDOR Billing](https://learn.secbyte.org/ctf/invoice-id-guessing-idor-billing)
- [Wallet Credit Abuse: Business Logic Exploitation Lab](https://learn.secbyte.org/ctf/wallet-credit-abuse-business-logic-exploitation-lab)

---

## Learning Path

Follow this structured progression path to master cloud domain/bucket takeover techniques and complex payment gateway business logic auditing:

1. **Phase 1: Cloud Takeovers & Dangling Infrastructure Recovery** — Scan for stale DNS pointers, take over orphaned S3/Azure buckets, and claim expired domain assets:
   - [Subdomain Takeover: From Detection to Defensive Validation](https://learn.secbyte.org/ctf/subdomain-takeover-from-detection-to-defensive-validation)
   - [Dangling DNS Takeover: From Detection to Validation](https://learn.secbyte.org/ctf/dangling-dns-takeover-from-detection-to-validation)
   - [Bucket Takeover](https://learn.secbyte.org/ctf/bucket-takeover)
   - [Expired Domain Takeover](https://learn.secbyte.org/ctf/expired-domain-takeover)
   - [Cloud Resource Hijacking: Identity, Metadata, and Misuse](https://learn.secbyte.org/ctf/cloud-resource-hijacking-identity-metadata-and-misuse)

2. **Phase 2: Payment Parameters, Currency & Precision Manipulation** — Tamper with currency parameters, test floating-point cent rounding, and exploit installment pricing:
   - [Currency Manipulation Abuse: Pricing Logic & Payment Controls](https://learn.secbyte.org/ctf/currency-manipulation-abuse-pricing-logic-payment-controls)
   - [Decimal Precision Abuse](https://learn.secbyte.org/ctf/decimal-precision-abuse)
   - [Installment Manipulation](https://learn.secbyte.org/ctf/installment-manipulation)

3. **Phase 3: Asynchronous State Desync & Transaction Idempotency** — Send parallel payment requests to trigger double-spending and forge asynchronous webhook states:
   - [Duplicate Payment Processing](https://learn.secbyte.org/ctf/duplicate-payment-processing)
   - [Payment State Desync](https://learn.secbyte.org/ctf/payment-state-desync)

4. **Phase 4: Billing IDORs & Wallet Logic Abuse** — Enumerate billing IDs to access private invoices and exploit wallet refund and credit stacking routines:
   - [Invoice ID Guessing: IDOR Billing](https://learn.secbyte.org/ctf/invoice-id-guessing-idor-billing)
   - [Wallet Credit Abuse: Business Logic Exploitation Lab](https://learn.secbyte.org/ctf/wallet-credit-abuse-business-logic-exploitation-lab)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario directives, infrastructure maps, and financial workflow parameters on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy analysis toolsets (Burp Suite Pro/Community, Turbo Intruder, AWS CLI, Azure CLI, dig, dnsrecon, Python) inside an isolated workstation.
4. Scan for dangling CNAMEs, register orphaned buckets, send concurrent race-condition HTTP requests, tamper with currency and precision fields, and capture target flags.

---

## Disclaimer

This repository and its linked challenge resources are strictly intended for educational, threat research, and authorized technical security training purposes. Never attempt to execute subdomain takeovers, bucket claims, or payment manipulation attacks against unauthorized production web applications, live DNS records, or operational payment gateways.
