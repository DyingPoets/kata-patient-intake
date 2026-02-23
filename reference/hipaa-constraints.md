# HIPAA Constraints Relevant to Patient Intake UX
*For training purposes — simplified, not legal advice*

---

## Data Minimization
Collect only data that is necessary for the purpose. Do not ask for information "just in case."
**UX implication:** Every field on the form must have a documented clinical or operational purpose.

## Consent and Authorization
Patients must consent to how their data is used before providing it.
**UX implication:** HIPAA acknowledgement cannot be at the end — patients should understand it before filling out the form.

## Minimum Necessary Rule
When sharing data with staff, only share what's needed for their role.
**UX implication:** Intake nurses and billing staff should see different views of the same intake data.

## Audit Trail
All access to patient health information must be logged.
**UX implication:** Build audit logging into the architecture from the start, not as an afterthought.

## Breach Notification
If PHI (Protected Health Information) is exposed, the clinic must notify patients within 60 days.
**UX implication:** SSN, medical history, and insurance data require additional access controls.

## Right of Access
Patients have the right to access their own health records.
**UX implication:** There must be a way for a patient to view or export their intake data.
