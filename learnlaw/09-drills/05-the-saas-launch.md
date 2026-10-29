# Drill: The SaaS launch

**Modules exercised:** [06 IP ownership and contractors](../06-property-ip/06-ip-ownership-work-for-hire-and-contractors.md), [06 Copyright](../06-property-ip/03-copyright.md), [03 Online contracts](../03-contracts/09-online-and-electronic-contracts.md), [07 Marketing and telemarketing](../07-regulatory-compliance/05-marketing-telemarketing-advertising.md), [07 Data privacy and breach](../07-regulatory-compliance/04-data-privacy-and-breach.md), [07 FDUTPA](../07-regulatory-compliance/03-fdutpa.md), [07 Florida taxes](../07-regulatory-compliance/02-florida-taxes-for-business.md), [01 Jurisdiction and venue](../01-foundations/02-jurisdiction-and-venue.md)
**Time:** ~60 min

## Scenario

Habitline LLC, a two-member Florida LLC based in Gainesville, launched a habit-tracking app in May 2026. Subscriptions are $9 a month or $79 a year, charged to a card on file and renewed automatically. By October the app has 6,000 paying users in 40 states.

The code was written by Ravi, a freelance developer in Atlanta, between November 2025 and April 2026. Habitline paid him $30,000 in milestone payments. There was no written contract. Ravi has since posted parts of the codebase on his portfolio site.

The Terms of Service, which choose Florida law, require arbitration in Alachua County, and disclaim warranties, exist only as a link in the website footer. Signup requires an email and a mobile number. Nothing on the signup page mentions terms or marketing. Habitline sends two promotional texts a week to every number collected. Card numbers are stored, unencrypted, in Habitline's own database to "make renewals easy."

An Oregon subscriber complains that she was charged $79 for a second year without any notice, cannot find a cancel button, and has filed a complaint with the Oregon Department of Justice. The members also ask whether they should have been collecting Florida sales tax. Today is October 29, 2026.

## Your task

List every legal issue you can see. For each: who could claim what against whom, what rule governs, what the likely outcome is, and what facts you would want to know that the scenario does not give you.

Write your answer before opening the model answer.

<details>
<summary>Model answer</summary>

**Step 1, parties.** Habitline LLC and its two members. Ravi, a Georgia contractor. 6,000 subscribers in 40 states, each a consumer and a potential class member. The Oregon subscriber. The Oregon DOJ and the Florida Attorney General. The card networks and processor, through the merchant agreement.

**Step 2, timeline.** November 2025 to April 2026, code written and paid for, no writing. May 2026, launch, texts begin, card data stored. October 2026, the Oregon complaint. No limitation period is near; the exposure grows weekly.

**Steps 3 and 4.** Issues and the flip.

### Issue 1: Who owns the code?
- **Parties and claim:** Habitline against Ravi for ownership; Ravi against Habitline for infringement if it modifies or sublicenses beyond the license.
- **Rule:** Copyright vests in the author (17 U.S.C. § 201(a)). A work made for hire belongs to the hiring party only if the author was an employee acting within the scope of employment, or the work falls in one of nine listed categories and the parties signed a written work-for-hire agreement (17 U.S.C. § 101). Software by a contractor is not a listed category. A transfer of copyright requires a signed writing (17 U.S.C. § 204(a)). Contractor status is decided by the common-law agency test (*Community for Creative Non-Violence v. Reid*, 490 U.S. 730 (1989)). A customer who commissioned the work usually holds an implied nonexclusive license (*Effects Associates, Inc. v. Cohen*, 908 F.2d 555 (9th Cir. 1990)).
- **Application:** Ravi is a contractor with no writing. He owns the copyright. Habitline has a license to run the app but cannot stop him from reusing the code and cannot sell the company cleanly.
- **Likely outcome:** Ravi owns it until he signs an assignment. The fix is a written assignment now, for new consideration.
- **Facts that would change it:** Any email where Ravi said "it's your code." Whether Ravi used open-source components with their own licenses.

### Issue 2: Are the Terms of Service binding?
- **Parties and claim:** Habitline against any subscriber, to enforce arbitration, the forum clause, and the warranty disclaimer.
- **Rule:** A browsewrap, a terms link in a footer with no notice at the point of signup, does not bind a user who had no actual or constructive notice (*Nguyen v. Barnes & Noble Inc.*, 763 F.3d 1171 (9th Cir. 2014)). A clickwrap with a conspicuous checkbox at signup generally does. Florida courts apply the same reasonable-notice inquiry (verify). See [`cases/nguyen-v-barnes-and-noble.md`](../cases/nguyen-v-barnes-and-noble.md).
- **Application:** Footer-only, nothing at signup. No assent.
- **Likely outcome:** The arbitration clause, the Alachua County forum clause, the Florida choice of law, and the disclaimers are all probably unenforceable against existing users. A subscriber can sue in her home state and a class action cannot be pushed into arbitration.
- **Facts that would change it:** Whether a later screen, the app store, or the app's first open required acceptance.

### Issue 3: Automatic renewal
- **Parties and claim:** The Oregon subscriber, the Oregon DOJ, and the Florida Attorney General against Habitline.
- **Rule:** Florida's automatic renewal statute requires a seller of a consumer service under a contract with an automatic renewal provision to disclose that provision clearly and conspicuously, and for a term of 12 months or more that renews for more than one month, to send notice 30 to 60 days before the cancellation deadline (§ 501.165, verify current text and remedies). Federally, the Restore Online Shoppers' Confidence Act requires clear disclosure, express informed consent before charging, and a simple cancellation mechanism for online negative-option plans (15 U.S.C. § 8403). Oregon has its own automatic renewal statute enforced as an unlawful trade practice (ORS 646A.295, verify). A choice-of-law clause does not strip a consumer of her home state's consumer statute, and here the clause is not binding anyway.
- **Application:** No disclosure at signup, no pre-renewal notice on an annual plan, no cancel button. Every element is missing, in 40 states.
- **Likely outcome:** Refund of the $79 at minimum, regulatory exposure in Oregon and Florida, and a FDUTPA claim for actual damages and fees (§§ 501.204, 501.2105).
- **Facts that would change it:** What the confirmation email said. Whether the app store handled billing.

### Issue 4: The marketing texts
- **Parties and claim:** Any subscriber, individually or as a class, against Habitline under the TCPA and the Florida Telephone Solicitation Act.
- **Rule:** The TCPA requires prior express written consent for marketing texts sent with an automatic telephone dialing system or prerecorded voice (47 U.S.C. § 227); *Facebook, Inc. v. Duguid*, 592 U.S. 395 (2021), narrowed the autodialer definition. Damages are $500 per message, up to $1,500 if willful. Florida's FTSA requires prior express written consent for telephonic sales calls, including texts, made with an automated system for the selection or dialing of numbers, as narrowed in 2023, with a 15-day stop-request safe harbor (§ 501.059, verify). Damages are $500 per violation, trebled if willful (verify) (§ 501.059(10)).
- **Application:** Signup collected a number with no consent language. Two texts a week to 6,000 numbers is a large number of potential violations. Whether the platform is an "automated system" is the main defense.
- **Likely outcome:** The single largest dollar exposure in the story.
- **Facts that would change it:** How the texts are sent. Whether anyone replied STOP and kept receiving messages. Whether the emails comply with CAN-SPAM (15 U.S.C. § 7704).

### Issue 5: Stored card data
- **Parties and claim:** The card networks and processor against Habitline under the merchant agreement; subscribers and the Attorney General if there is a breach.
- **Rule:** The Payment Card Industry Data Security Standard applies by contract through the merchant agreement; storing full card numbers unencrypted breaches it. Florida's Information Protection Act requires reasonable measures to protect personal information, which includes card numbers, and after a breach requires notice to individuals within 30 days, to the Attorney General for breaches affecting 500 or more Floridians, and to credit agencies above 1,000 (§ 501.171, verify). FIPA has no private cause of action; the Attorney General enforces it as an unfair practice. Every other state has a breach statute that reaches its residents.
- **Application:** Habitline is in breach of its merchant agreement today and one phishing email away from a 40-state notification exercise.
- **Likely outcome:** No lawsuit yet, but processor fines and termination are real. Tokenize through the processor and delete the local numbers.
- **Facts that would change it:** Whether a breach has already occurred.

### Issue 6: Sales tax
- **Parties and claim:** Florida Department of Revenue and other states' revenue departments against Habitline.
- **Rule:** Florida generally does not tax software delivered electronically with no tangible medium, which covers most SaaS (verify with current Department of Revenue guidance). Other states do, and after *South Dakota v. Wayfair, Inc.*, 585 U.S. 162 (2018), a remote seller with enough sales into a state must collect there. Oregon has no sales tax.
- **Application:** Likely no Florida sales tax. Habitline may have crossed nexus thresholds in some taxing states.
- **Likely outcome:** A state-by-state review; Florida is not the problem.
- **Facts that would change it:** Sales by state. Whether the app bundles anything taxable.

**Step 6, what you do not know.** The signup flow. The confirmation and renewal emails. How numbers are dialed. The merchant agreement. Which member directed the texting, since personal participation can mean personal TCPA liability (verify).

### Red herrings
- "We paid him, so we own the code." Payment buys a license, not the copyright, without a signed writing.
- "Our terms say Florida law and arbitration." Only if the user agreed, and here nobody did.
- "Oregon can't touch a Florida company." Selling to Oregon residents is enough contact for an Oregon court (*International Shoe*).
- "Patent the app." The idea is not patentable; the code is a copyright question.

### Procedural and remedial angles
- Forum: a subscriber can sue in her home state or in Florida; a TCPA or FTSA class would likely land in the Northern District of Florida or Alachua County circuit court. Copyright claims are exclusively federal (28 U.S.C. § 1338).
- Value: the texting exposure dwarfs everything else.
- Fees: FDUTPA shifts fees to the prevailing party either way (§ 501.2105); TCPA and FTSA do not, but per-message damages drive settlements; copyright fees need registration before infringement (17 U.S.C. §§ 412, 505).
- Limitations: TCPA 4 years (28 U.S.C. § 1658); FTSA and FDUTPA 4 years (verify) (§ 95.11); copyright 3 years (17 U.S.C. § 507(b)).
- Pre-suit: none required by the consumer statutes. For Habitline, the pre-suit work is the compliance fix: signed assignment from Ravi, clickwrap, renewal disclosures and a cancel button, consent for texts, tokenized card storage.

</details>
