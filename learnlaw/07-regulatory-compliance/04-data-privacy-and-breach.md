# Data privacy and breach

**Module:** 07 · **Lesson:** 4 · **Time:** ~45 min
**Tags:** `[FL]` `[US]`

## Why this matters to a business owner

Every business holds personal data: card numbers, employee Social Security numbers, patient or client records. Florida requires reasonable security for it and fast notice when it leaks. The United States has no single privacy law, only a patchwork of sector rules, a general ban on unfair practices, and fifty state breach statutes. A breach is also a contract problem, because card networks and large customers impose their own terms. Know which pieces apply before the breach, not after.

## The rule

**Florida Information Protection Act (FIPA), § 501.171.**

- **Who.** A "covered entity" is any business that acquires, maintains, stores, or uses personal information. A "third-party agent" is a vendor that handles it for a covered entity.
- **What.** "Personal information" is a name plus one of: Social Security number, driver license or ID number, financial account or card number with any required code, medical information, or health insurance information. Also a username or email address with a password or security question answer. Encrypted or redacted data is excluded unless the key was also taken.
- **Reasonable measures.** Section 501.171(2) requires reasonable measures to protect and secure data in electronic form.
- **Notice to individuals.** No later than 30 days (verify) after determination of a breach (§ 501.171(4)). Notice is excused if, after consulting law enforcement, the entity reasonably determines the breach will not likely cause identity theft or financial harm, and documents that in writing for five years (verify).
- **Notice to the Attorney General.** Within 30 days (verify) if the breach affects 500 (verify) or more individuals in Florida (§ 501.171(3)).
- **Credit reporting agencies.** Notice at more than 1,000 (verify) individuals (§ 501.171(5)).
- **Vendors.** A third-party agent must notify the covered entity within 10 days (verify) of determining a breach (§ 501.171(6)).
- **Disposal.** Customer records containing personal information must be shredded, erased, or otherwise made unreadable when no longer kept (§ 501.171(8)).
- **Enforcement.** No private right of action (§ 501.171(10)). A violation is an unfair or deceptive practice enforced by the Attorney General under FDUTPA, with civil penalties for late notice of $1,000 (verify) per day for the first 30 days and $50,000 (verify) per 30-day period after, capped at $500,000 (verify) (§ 501.171(9)).

**Florida Digital Bill of Rights, §§ 501.701 to 501.722 (2023).** A consumer privacy law in the mold of California's, but it applies only to controllers with more than $1 billion (verify) in global gross revenue that also meet one of three conditions, such as deriving half their revenue from online advertising or operating a large app store or voice assistant platform (verify). Almost no Florida small business is a controller.

**Federal.**

- **FTC Act § 5**, 15 U.S.C. § 45. Misrepresenting your security or privacy practices is deception. Unreasonable security that causes substantial consumer injury is unfairness. The Third Circuit upheld the theory in *FTC v. Wyndham Worldwide Corp.*, 799 F.3d 236 (3d Cir. 2015).
- **GLBA Safeguards Rule**, 16 C.F.R. part 314. Applies to "financial institutions," which includes non-banks such as auto dealers that finance, tax preparers, and mortgage brokers. Requires a written security program and FTC breach notice at 500 or more consumers (verify).
- **HIPAA.** Covered entities and their business associates. Vendors handling protected health information must sign a business associate agreement.
- **COPPA**, 16 C.F.R. part 312. Verifiable parental consent before collecting personal information from children under 13 online. The rule was amended in 2025 (verify).
- **PCI-DSS.** Not law. A contractual standard imposed through the merchant agreement with the card processor. A card breach triggers fines and assessments under that contract regardless of FIPA.

**Other states.** A Florida business is subject to every state's breach law for that state's residents, and to comprehensive privacy laws such as California's if it crosses their thresholds.

**Burden.** The Attorney General must show a breach and a failure to notify or to take reasonable measures. The entity bears the burden on the no-harm exception and must have documented it.

## How courts reason about it

- **What is "reasonable."** FIPA, the FTC Act, and negligence law all use a reasonableness standard with no checklist. Courts and the FTC look to industry frameworks such as NIST and the CIS controls, to what the business promised in its privacy policy, to the sensitivity of the data, and to known vulnerabilities the business ignored. Unpatched software, shared admin passwords, and unencrypted stored card numbers are the recurring facts in enforcement actions. A small business is held to a smaller program, not to none.
- **Standing and damages in private suits.** FIPA gives no private claim, so plaintiffs sue in negligence, breach of implied contract, and FDUTPA. The fight is over injury. Federal courts after *TransUnion LLC v. Ramirez*, 594 U.S. 413 (2021), require concrete harm, and the Eleventh Circuit has held that risk of future identity theft, without misuse, is often not enough (verify). State courts are more forgiving. Expect a motion to dismiss on injury as the first move.
- **Promises in privacy policies.** A privacy policy is read as a representation to consumers. Saying "we use industry-standard encryption" when you do not is deception under § 5 and FDUTPA. Courts do not treat a privacy policy as a contract unless it was accepted as one (see *Nguyen* on notice).
- **Vendor allocation.** When a vendor is breached, courts enforce the contract's allocation of notice duties, indemnity, and liability caps. The statutory duty to notify stays with the covered entity; the owner can outsource the cost, not the obligation.

## Florida specifics

- Florida follows the majority of states on breach notice design, and is stricter than most on timing: 30 days, with the Attorney General notice at 500 individuals, where many states use 60 days and 1,000.
- No private right of action under FIPA. Florida consumers use FDUTPA and negligence.
- Florida has no general consumer privacy law for small businesses. The Digital Bill of Rights thresholds leave them out.

## Case anchors

- [`cases/pnr-v-beacon-property-management.md`](../cases/pnr-v-beacon-property-management.md): FIPA violations are enforced as FDUTPA violations; this case defines the scope of that act.
- [`cases/nguyen-v-barnes-and-noble.md`](../cases/nguyen-v-barnes-and-noble.md): a privacy policy or terms linked at the bottom of a page binds no one without notice, which cuts both ways for a business relying on its own terms.
- [`cases/burger-king-v-rudzewicz.md`](../cases/burger-king-v-rudzewicz.md): selling into another state is contact enough to be sued there under that state's privacy and breach law.

## Angles checklist

- What personal information does the business hold, where, and in what form? Is any of it encrypted?
- Is the business a covered entity under FIPA, a financial institution under GLBA, a HIPAA covered entity or business associate, or collecting from children?
- Does a written security program exist? Who is responsible for it?
- What does the privacy policy promise, and is it true?
- Vendor contracts: notice within what period, indemnity, insurance, liability caps, data return on termination?
- Card processing: PCI scope, who stores card numbers, what the merchant agreement says about breach.
- Breach response plan: who declares a breach, who calls counsel and the insurer, who notifies whom by when, which forensic firm is pre-engaged, and how the no-harm determination is documented.
- Cyber insurance: notice conditions, panel counsel, sublimits.
- Flip it: in a suit, is there concrete injury? Is there a contract term limiting liability?

## Drill

Gulf Dental, a two-dentist practice organized as a PLLC, uses a cloud scheduling vendor. The vendor emails on a Monday that an attacker accessed its database three weeks earlier and downloaded patient names, dates of birth, and insurance ID numbers for 1,400 Gulf Dental patients. The practice's website says "Your data is protected by bank-level security." Spot the issues.

<details>
<summary>Model answer</summary>

- **FIPA.** Gulf Dental is the covered entity; the vendor is a third-party agent. Name plus health insurance information is personal information. The vendor's three-week delay is its own violation but does not extend Gulf Dental's clock. Gulf Dental must notify 1,400 patients within 30 days of its determination, notify the Attorney General because the count exceeds 500, and notify credit reporting agencies because it exceeds 1,000.
- **HIPAA.** The practice is a covered entity; the vendor is a business associate. HIPAA requires individual notice within 60 days, notice to HHS, and media notice at 500 residents of a state. A missing business associate agreement is a separate violation.
- **Website promise.** "Bank-level security" is a representation. If the practice had no written program and the vendor contract required none, the statement is deceptive under FDUTPA and FTC Act § 5.
- **Vendor contract.** Check notice duties, indemnity, and caps. The delay may support indemnity for notice costs.
- **Private suits.** Patients may sue in negligence and FDUTPA. Injury will be contested; insurance ID numbers support a real identity theft risk.
- **Insurance.** Notify the cyber carrier immediately.
- **Facts that would change it.** If the insurance IDs were encrypted and the key was not taken, the data is not "personal information" and FIPA notice is not required, though HIPAA's own analysis still applies.

</details>

## Check yourself

1. A customer whose data leaked wants to sue under § 501.171. Can she?
2. A vendor contract says the vendor will "handle all breach notifications." The vendor is breached and notifies no one. Who is liable to the Attorney General?
3. Why is PCI-DSS described as contract rather than law, and why does that matter?

<details>
<summary>Answers</summary>

1. No. Section 501.171(10) creates no private right of action. She can sue in negligence, implied contract, or FDUTPA based on the underlying conduct, and must show concrete injury.
2. The covered entity. The statutory duty to notify individuals and the Attorney General belongs to it. The contract gives it an indemnity claim against the vendor, not a defense.
3. Because the card networks impose it through the merchant agreement, not a statute. Its penalties are contractual fines and assessments that apply even when no statute was violated, and that a liability cap in the merchant agreement may or may not limit.

</details>

## Verify and go deeper

- § 501.171, Fla. Stat. (FIPA), all subsections; §§ 501.701 to 501.722 (Florida Digital Bill of Rights, verify thresholds).
- 15 U.S.C. § 45; *FTC v. Wyndham Worldwide Corp.*, 799 F.3d 236 (3d Cir. 2015).
- 16 C.F.R. part 314 (GLBA Safeguards Rule); 45 C.F.R. parts 160 and 164 (HIPAA); 16 C.F.R. part 312 (COPPA).
- *TransUnion LLC v. Ramirez*, 594 U.S. 413 (2021).
- Florida Attorney General breach notice portal: `myfloridalegal.com`.
