# Drill: The investor pitch

**Modules exercised:** [07 Raising money and securities basics](../07-regulatory-compliance/06-raising-money-securities-basics.md), [02 Operating agreements](../02-business-entities/03-operating-agreements.md), [02 Limited liability and veil piercing](../02-business-entities/05-limited-liability-and-veil-piercing.md), [04 Fraud and misrepresentation](../04-torts/03-fraud-and-misrepresentation.md)
**Time:** ~50 min

## Scenario

In early 2025, Nadia and Sam formed Mangrove Roasters LLC to open a coffee roastery and cafe in St. Petersburg. They needed $120,000. Over six weeks they pitched twelve people: college friends, a neighbor, Sam's dentist, Nadia's former teacher, and a few people the teacher introduced. Each put in $10,000 for a "2% member interest" and "a share of profits." None would have any role in running the business. Nadia posted on Instagram: "Looking for a few more investors in Mangrove Roasters, $10k gets you in, targeting 20% annual returns, DM me." The post was public and got 4,000 views.

The investors received a two-page summary and a one-page "Member Subscription" they signed. No one received financial projections, risk disclosures, or an operating agreement. Nadia and Sam never filed anything with the SEC or the Florida Office of Financial Regulation. The dentist earns about $350,000 a year. The retired teacher lives on a pension.

The money went into the buildout and equipment as described. The cafe opened in November 2025 and closed in September 2026. The LLC has no assets left. Three investors have hired a lawyer. Today is October 29, 2026.

## Your task

List every legal issue you can see. For each: who could claim what against whom, what rule governs, what the likely outcome is, and what facts you would want to know that the scenario does not give you.

Write your answer before opening the model answer.

<details>
<summary>Model answer</summary>

**Step 1, parties.** Mangrove Roasters LLC, now an empty shell. Nadia and Sam, founders and the people who actually sold the interests. Twelve investors, including at least one who is likely accredited (the dentist) and several who are not (the teacher, probably the friends). The SEC and the Florida Office of Financial Regulation as regulators. The 4,000 viewers of the post, who matter as proof of general solicitation.

**Step 2, timeline.** Early 2025, pitches, the Instagram post, twelve sales. November 2025, opening. September 2026, closure. October 2026, lawyer hired. The one-year federal clock on an unregistered-sale claim runs from each sale in early 2025 and has likely expired. Florida's clock runs from discovery of the violation and is probably still open.

**Steps 3 and 4.** Issues and the flip.

### Issue 1: Were the member interests securities?
- **Parties and claim:** Threshold question for every claim below.
- **Rule:** An investment contract is a security when there is an investment of money in a common enterprise with an expectation of profits derived from the efforts of others (*SEC v. W.J. Howey Co.*, 328 U.S. 293 (1946)). Florida's definition of "security" includes an investment contract and Florida courts follow *Howey* (§ 517.021, Fla. Stat.). Interests in an LLC are securities when the holders are passive and the managers run the business. See [`cases/sec-v-howey.md`](../cases/sec-v-howey.md).
- **Application:** Twelve passive investors, no management role, profits from Nadia and Sam's work. This is the *Howey* fact pattern.
- **Likely outcome:** Securities. The "member interest" label does not change the analysis.
- **Facts that would change it:** If investors had real management rights under an operating agreement and exercised them, the interests might fall outside *Howey*. Nothing suggests that.

### Issue 2: Unregistered offering and lost exemptions
- **Parties and claim:** Investors against the LLC, Nadia, and Sam for selling unregistered securities; regulators for the same.
- **Rule:** Every offer and sale must be registered or exempt (Securities Act § 5, 15 U.S.C. § 77e; § 517.07, Fla. Stat.). The usual small-company exemptions: Rule 506(b) permits up to 35 non-accredited purchasers but forbids general solicitation and requires specified disclosure to non-accredited purchasers (17 C.F.R. §§ 230.502, 230.506(b)); Rule 506(c) permits general solicitation only if every purchaser is accredited and the issuer verifies it; Florida's limited offering exemption allows up to 35 purchasers in 12 months with no general advertising and access to information (§ 517.061(11), verify current text after recent amendments). Form D is due within 15 days of the first sale.
- **Application:** The public Instagram post is general solicitation. That destroys 506(b), the statutory private offering exemption, and the Florida exemption. 506(c) fails because the teacher and others are not accredited. No disclosure document went to non-accredited purchasers. No Form D.
- **Likely outcome:** An unregistered, non-exempt offering under both federal and Florida law.
- **Facts that would change it:** Whether any of the twelve bought because of the post rather than a pre-existing relationship. Whether Nadia deleted the post before any sale. Neither fully cures it.

### Issue 3: Rescission and who pays it
- **Parties and claim:** Each investor against the LLC and personally against Nadia and Sam for return of $10,000 plus interest and fees.
- **Rule:** Federally, a purchaser from an unregistered sale may rescind for the price plus interest, with no proof of fault or loss required, but must sue within one year of the sale (15 U.S.C. §§ 77l(a)(1), 77m). In Florida, a sale in violation of the registration requirement gives the buyer rescission for the consideration paid plus interest, less income received, and every director, officer, partner, or agent of the seller who personally participated or aided in the sale is jointly and severally liable (§ 517.211(1), (2)). The prevailing party recovers fees (§ 517.211(6)). The Florida claim must be brought within 2 years of discovery, with a 5-year outer limit (verify) (§ 95.11). Waivers of these rights are void (15 U.S.C. § 77n; § 517.241, verify).
- **Application:** The LLC is empty, so the entity claim is worthless. The founders personally participated in every sale, which makes them personally liable under § 517.211(2). Limited liability under § 605.0304 protects members from the LLC's debts, not from their own statutory liability for selling securities.
- **Likely outcome:** Judgments against Nadia and Sam personally for up to $120,000 plus interest and fees, if the investors sue within the Florida period. The federal rescission claim is probably time-barred.
- **Facts that would change it:** When each investor learned the offering was unregistered. Whether any investor received distributions to offset. The founders' personal assets, homestead, and entireties property.

### Issue 4: Fraud and the "20% returns" post
- **Parties and claim:** Investors against the founders for securities fraud and common-law fraud or negligent misrepresentation.
- **Rule:** It is unlawful to make an untrue statement of material fact or omit a fact needed to make statements not misleading in connection with a sale (17 C.F.R. § 240.10b-5; § 517.301, Fla. Stat.). Rule 10b-5 requires scienter; § 517.301 claims under § 517.211 do not require proof of reliance in the same way and shift fees (verify). Common-law fraud requires a knowingly false statement of fact, intent to induce, reliance, and damage; projections are actionable when made without a reasonable basis.
- **Application:** "Targeting 20% annual returns" with no projections behind it and no risk disclosure is the kind of statement that becomes an omission case: what was not said about the risk of a new cafe. The loss itself proves nothing; honest failures are not fraud.
- **Likely outcome:** A credible claim that adds little to rescission in dollars but matters if the registration claim is time-barred.
- **Facts that would change it:** Any spreadsheet behind the 20% figure. What was said orally at each pitch. Whether the summary mentioned risk.

### Issue 5: The operating agreement that does not exist
- **Parties and claim:** Investors against the LLC and founders over their rights as members.
- **Rule:** Without an operating agreement, chapter 605 defaults apply: distributions by agreed contribution value (§ 605.0404), voting by profits interests (§ 605.04073), information rights (§ 605.0410), and the founders' duties of loyalty and care as managing members (§ 605.04091). A member is not liable for LLC debts (§ 605.0304).
- **Application:** The subscription made each investor a 2% member, so each had inspection rights and a claim for an accounting. The founders owed them fiduciary duties in spending the money. The scenario says the money was spent as described, so a fiduciary claim is weak.
- **Likely outcome:** Information and accounting rights, little more. The absence of an agreement hurts the founders most: no waiver of fiduciary duties, no limits on member suits, and no disclosure acknowledgments to point to.
- **Facts that would change it:** Actual spending records. Any founder salary or related-party payments.

**Step 6, what you do not know.** The text of the summary and subscription. Who saw the post and who bought after it. Each investor's income and net worth. Dates each investor learned the facts. Whether the OFR or SEC has received a complaint. Whether the founders have insurance or assets.

### Red herrings
- "There is a friends-and-family exemption." There is not. Pre-existing relationships help prove the absence of general solicitation, but the public post undoes that.
- "They are members, not investors." The label is irrelevant under *Howey*.
- "The LLC protects us." It protects members from the LLC's contract and tort debts. It does not protect a person from liability for his own securities violations.
- "Only twelve people, under 35." Numerical limits only matter once an exemption is otherwise available.
- "We never promised 20%, we said targeting." Softening words do not cure a projection with no basis.

### Procedural and remedial angles
- Forum: Florida circuit court in Pinellas County (Sixth Judicial Circuit) for § 517.211 claims, or federal court for 10b-5 with state claims attached. Twelve investors can join in one action.
- Value: up to $120,000 in rescission plus prejudgment interest, plus fees under § 517.211(6). Personal judgments against the founders.
- Fees: § 517.211(6) shifts fees to the prevailing party, in either direction (verify).
- Limitations: federal unregistered-sale claims, 1 year from sale, likely expired; federal fraud, 2 years from discovery and 5 from the violation (28 U.S.C. § 1658(b)); Florida ch. 517 claims, 2 years from discovery (verify § 95.11 subsection); common-law fraud, 4 years from discovery (verify).
- Pre-suit: none required. Regulators can act independently; willful violations of ch. 517 are felonies (§ 517.302, verify), which is the reason founders in this position talk to counsel before talking to investors.

</details>
