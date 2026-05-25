# x12-claims-interoperability
 X12 EDI Claims Pipeline — 270/271/837P/835 transactions with revenue cycle analytics
 
 # X12 EDI Claims Interoperability Pipeline
End-to-end X12 EDI transaction pipeline covering the complete
US healthcare revenue cycle — from eligibility verification
through claim submission and payment reconciliation.

## EDI Transactions Built

| Transaction | Purpose | Direction |
|---|---|---|
| X12 270 | Eligibility Inquiry | Provider → Payer |
| X12 271 | Eligibility Response | Payer → Provider |
| X12 837P | Professional Claim | Provider → Payer |
| X12 835 | Remittance Advice (ERA) | Payer → Provider |

## X12 Segments Covered
ISA · IEA · GS · GE · ST · SE · BPR · TRN · NM1 · CLM
CLP · SV1 · SVC · DTP · HI · CAS · EB · EQ · DTM

## Revenue Cycle Analytics
- Billed vs paid analysis by payer
- Collection rate benchmarking  
- Claim denial patterns (CARC codes)
- CPT category distribution
- Eligibility verification workflow

## Data Source
Synthea FHIR R4 synthetic patients — no PHI, fully HIPAA-safe

## Stack
Python · pandas · numpy · matplotlib · json

## Related Projects
- [FHIR Healthcare Analytics](https://github.com/nipa-analytics/fhir-healthcare-analytics)
- [ICD-10 Medical Coding Analytics](https://github.com/nipa-analytics/icd10-medical-coding-analytics)
- [HL7 v2 ADT Message Pipeline](https://github.com/nipa-analytics/hl7v2-adt-message-pipeline)

## Author
**Nipa Shah** — Data Scientist | Healthcare Analytics | AI/ML  
📍 Jersey City, NJ  
🔗 [LinkedIn](https://www.linkedin.com/in/nipa-s-486287382)  
🐙 [GitHub](https://github.com/nipa-analytics)
