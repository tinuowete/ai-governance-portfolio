# AI Security Control Map

A practitioner reference for AI governance, compliance, and internal audit in regulated financial services.

This control map is designed for enterprise AI systems operating in regulated environments. It provides testable control objectives, required evidence, and practical audit test steps for assessing whether AI systems are governed securely and defensibly in production. It is intended to help organisations translate broad AI governance expectations into concrete, reviewable controls.

## What this is

The AI Security Control Map is a structured control reference for AI systems in regulated financial services. It is built for practitioners who need more than principles, it focuses on what must exist, what evidence should be produced, and how controls should be tested. The document supplements an existing ISMS rather than replacing it, and addresses AI-specific risk areas that are not structurally covered by traditional ISO 27001 Annex A controls.

## Who this is for

This resource is intended for:

- Cybersecurity GRC professionals
- Compliance and regulatory teams
- Internal auditors
- Technology risk teams
- AI governance leads
- Security reviewers supporting AI deployments
- Regulated financial institutions assessing AI system readiness

## What is included

This control map contains:

- **55 control objectives**
- **7 control domains**
- **Evidence requirements for each control**
- **Practical audit test steps**
- **Implementation phase tags**
- **Risk prioritisation guidance**
- **A control attestation template**
- **A regulatory cross-reference table**

The control domains are:

1. **DAT — Data Governance & Training Data Security**
2. **MOD — Model Security & Supply Chain**
3. **PRM — Prompt & Input Security**
4. **OUT — Output Security & Reliability**
5. **ACC — Access Control & Identity**
6. **MON — Monitoring, Logging & Incident Response**
7. **VND — Vendor & Third-Party AI Risk**

## Why this exists

Many organisations are beginning to adopt AI in environments that are already subject to regulatory scrutiny, customer protection obligations, and formal assurance requirements. In practice, AI risk is often discussed at a high level while operational control expectations remain vague. This document closes that gap by turning AI governance concerns into specific, testable control statements.

The map is especially relevant where AI systems influence customer outcomes, process sensitive data, support regulated operations, or depend on third-party models, retrieval layers, or external vendors.

## How to use this document

Each control is written as a **shall statement**, meaning it expresses what the organisation must have in place. For every control, the map provides:

- the **control ID**
- the **control objective**
- the **evidence required**
- the **audit test steps**

Additional implementation guidance includes:

- **Phase tags**: Pre-req, Operational, Periodic
- **Risk if absent**: Critical, High, Medium
- **Priority sequencing** for phased implementation programmes
- **Attestation template** for system-level status tracking
- **Regulatory mapping** to major AI, operational resilience, privacy, and assurance frameworks

## Regulatory and framework coverage

The control map cross-references obligations from:

- **EU AI Act**
- **DORA**
- **GDPR**
- **ISO/IEC 42001**
- **NIST AI RMF**

It is designed to support organisations that need to demonstrate control maturity, regulatory alignment, and audit readiness across overlapping governance expectations.

## Example control themes covered

Examples of issues addressed in the map include:

- training data provenance and lawful basis
- model provenance and integrity verification
- third-party model and vendor assurance
- direct and indirect prompt injection controls
- jailbreak detection
- output guardrails and hallucination thresholds
- document-level access control in RAG systems
- AI-specific KRIs and log completeness
- AI incident classification and reporting readiness
- DORA-aligned third-party oversight
- GDPR-aligned handling of personal data in AI workflows

## Intended use cases

This document can be used in:

- AI risk assessments
- internal audit planning and fieldwork
- control design and implementation programmes
- AI system onboarding reviews
- board and risk committee reporting
- regulatory readiness exercises
- third-party AI due diligence
- control attestation and remediation tracking

## Relationship to ISO 27001

This control map does not replace an organisation’s ISMS. Instead, it extends established security and compliance practices into AI-specific areas such as training data governance, prompt security, output reliability, model supply chain integrity, and AI vendor risk. The intent is to help organisations govern AI systems using a control structure that is operationally usable by GRC, compliance, and audit teams.

## Structure of the artefact

The document is organised into the following major sections:

- control domains and detailed control statements
- control prioritisation matrix
- control attestation template
- regulatory framework cross-reference

This makes it usable both as a reference document and as a working assessment tool.

## Portfolio context

This artefact forms part of a broader AI governance portfolio. The source document references a companion deliverable, the **NIST AI RMF to ISO 27001 Bridge Document**, as part of the same portfolio.

## Author

**Atinuke Victoria Owete, CISM**

## Repository contents

Suggested structure:

```text
.
├── README.md
├── AI_Security_Control_Map.pdf
├── AI_Security_Control_Map.docx
└── supporting-materials/
```

Adjust this structure to match the files you actually upload.

## Disclaimer

This resource is a practitioner reference and not legal advice. Organisations should interpret and implement these controls in line with their jurisdiction, regulatory obligations, business model, AI use cases, and internal risk appetite.

## License

Add your preferred license here, for example:

- All rights reserved
- CC BY-NC 4.0
- MIT License for repository text only

If you do not want reuse without permission, use an explicit rights statement.
