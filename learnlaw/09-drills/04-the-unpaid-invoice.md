# Drill: The unpaid invoice

**Modules exercised:** [03 Contracts](../03-contracts/01-formation.md), [03 Statute of frauds](../03-contracts/03-statute-of-frauds-and-writings.md), [03 Defenses](../03-contracts/06-defenses.md), [08 Small claims and county court](../08-disputes-procedure/02-small-claims-and-county-court.md), [08 Proposals for settlement and fees](../08-disputes-procedure/04-proposals-for-settlement-and-fees.md), [08 Collecting a judgment](../08-disputes-procedure/06-collecting-a-judgment.md)
**Time:** ~50 min

## Scenario

Cutline Marketing LLC runs paid social media campaigns from an office in Miami. In February 2026 its owner, Luis, emailed a four-page proposal to Dr. Ortiz, who owns a Coral Gables dental practice organized as a P.A. The proposal priced a six-month campaign at $18,500, payable $5,000 up front and the balance monthly, and included a clause that "the prevailing party in any dispute shall recover its attorney's fees," a late charge of "1.5% per month on past-due balances," and a line that "results depend on many factors and are not guaranteed." There was no signature block. Dr. Ortiz replied the same day: "Looks good, let's start Monday." The practice paid $5,000 by card.

Cutline ran the campaign from March through August 2026 and sent monthly invoices. Nothing more was paid. In September Dr. Ortiz wrote that "the leads were garbage" and that the practice "won't be paying for work that produced nothing." In October the practice mailed a $4,000 check with "PAID IN FULL, all Cutline invoices" written on the memo line and in the cover letter. The check is sitting on Luis's desk.

Luis wants the balance, the late fees, and his lawyer paid for. Today is October 29, 2026.

## Your task

List every legal issue you can see. For each: who could claim what against whom, what rule governs, what the likely outcome is, and what facts you would want to know that the scenario does not give you.

Write your answer before opening the model answer.

<details>
<summary>Model answer</summary>

**Step 1, parties.** Cutline Marketing LLC (service provider). The dental practice, a professional association, which is the contracting party and debtor. Dr. Ortiz personally is not a party unless he signed as an individual, which he did not. Luis is an agent of Cutline, not a party.

**Step 2, timeline.** February 2026, proposal and "let's start Monday." March to August, performance and invoices. September, repudiation. October, the "paid in full" check. Today, October 29, 2026. Nothing is close to any limitation period.

**Steps 3 and 4.** Issues and the flip on each.

### Issue 1: Was a contract formed, and on what terms?
- **Parties and claim:** Cutline against the practice for breach of contract, $13,500 unpaid.
- **Rule:** A contract forms on offer, acceptance, and consideration, judged objectively by what the parties said and did (*Lucy v. Zehmer*, 196 Va. 493, 84 S.E.2d 516 (1954)). An emailed proposal is an offer; "looks good, let's start Monday" plus a $5,000 payment is acceptance by words and conduct. Under Florida's electronic transactions act, an email with a typed name can satisfy a signature requirement (§ 668.50, Fla. Stat.). See [`cases/lucy-v-zehmer.md`](../cases/lucy-v-zehmer.md).
- **Application:** The reply accepted the proposal as sent, including the fee clause, the late charge, and the no-guarantee line. The missing signature block is not a problem.
- **Likely outcome:** Contract on the proposal's terms.
- **Facts that would change it:** Whether Dr. Ortiz's reply attached conditions. Whether any later email changed the scope or price. Whether the proposal said it was "not binding until signed."

### Issue 2: Statute of frauds and the UCC
- **Parties and claim:** The practice's possible defenses.
- **Rule:** The statute of frauds (§ 725.01) covers agreements not to be performed within one year; a six-month campaign is outside it, and the emails would satisfy it anyway. The UCC's Article 2 governs sales of goods (ch. 672); a marketing campaign is predominantly services, so Article 2 and its $500 writing rule do not apply.
- **Application:** Neither defense is available.
- **Likely outcome:** Both fail.
- **Facts that would change it:** None realistic.

### Issue 3: Did Cutline perform, and does "poor results" excuse payment?
- **Parties and claim:** The practice against Cutline, as a defense of prior breach and as a counterclaim for return of the $5,000.
- **Rule:** The obligation is to perform the services promised with reasonable skill, not to deliver a result, unless a result was promised. The "not guaranteed" clause and the implied duty of good faith frame it. A counterclaim arising from the same contract is compulsory (Fla. R. Civ. P. 1.170(a)). The defending party bears the burden of proving a material breach by the plaintiff.
- **Application:** "Garbage leads" is an argument about results, which the contract disclaimed. It becomes a defense only if the practice shows Cutline did not run the campaign as described, missed deliverables, or misrepresented what it would do.
- **Likely outcome:** Cutline likely prevails on the balance if its deliverables match the proposal. A counterclaim for the $5,000 is weak on these facts.
- **Facts that would change it:** The proposal's deliverables list. Ad account reports. Any pre-contract statements like "you will get 40 new patients a month," which would open a fraud or FDUTPA counterclaim (§ 501.204) that a business can bring (*PNR, Inc. v. Beacon Property Management, Inc.*, 842 So. 2d 773 (Fla. 2003)). See [`cases/pnr-v-beacon-property-management.md`](../cases/pnr-v-beacon-property-management.md).

### Issue 4: The "paid in full" check
- **Parties and claim:** The practice's accord and satisfaction defense if Cutline deposits the check.
- **Rule:** Under § 673.3111, a claim is discharged if the debtor in good faith tenders an instrument as full satisfaction of a claim that is unliquidated or subject to a bona fide dispute, the instrument or an accompanying writing conspicuously states that it is tendered in full satisfaction, and the claimant obtains payment. Exceptions: a claimant organization that has designated a person or office for communications about disputed debts and the check did not go there, or a claimant that repays the amount within 90 days of payment (verify subsections).
- **Application:** The "garbage leads" letter makes the debt disputed, and the memo line and cover letter are conspicuous. Depositing the check discharges the rest of the claim. Cutline can return the check, or deposit it and refund within 90 days, or deposit it only if the designated-office exception applies.
- **Likely outcome:** If deposited and kept, the $9,500 balance is gone. The "under protest" endorsement does not help under the UCC version Florida adopted.
- **Facts that would change it:** Whether Cutline's invoices named an office for disputes. Whether the dispute was raised in good faith.

### Issue 5: The late charge and usury
- **Parties and claim:** Cutline's claim for 1.5% per month; the practice's usury objection.
- **Rule:** Interest over 18% simple per year on obligations of $500,000 or less (verify) is usurious (§ 687.02); over 25% is criminal (§ 687.071). Usury applies to loans and forbearances of money. A late charge on a services invoice is arguably a contractual forbearance; courts have treated interest on past-due accounts as subject to usury limits (verify). Civil usury also requires corrupt intent.
- **Application:** 1.5% per month is 18% simple, at the limit, not over it. If the clause compounds monthly it exceeds 18% effective (verify treatment). Absent the clause, prejudgment interest runs at the statutory rate set quarterly by the Chief Financial Officer (§ 55.03).
- **Likely outcome:** The late charge is probably enforceable at simple interest. Not a reason to litigate.
- **Facts that would change it:** Compounding language. Whether the clause was ever invoked in invoices.

### Issue 6: Attorney's fees
- **Parties and claim:** Either side as prevailing party.
- **Rule:** Florida follows the American rule unless contract or statute shifts fees. A contractual fee clause is enforced; if it ran one way only, § 57.105(7) makes it reciprocal. A proposal for settlement under § 768.79 shifts fees in an action for damages, including breach of contract, if the judgment misses the offer by at least 25% (verify).
- **Application:** The clause here is mutual and was accepted with the proposal. Whoever prevails recovers fees. That makes a $9,500 dispute worth litigating for the winner and dangerous for the loser.
- **Likely outcome:** Fee exposure on both sides, likely exceeding the principal.
- **Facts that would change it:** Whether a court finds the proposal's terms were not part of the deal, which would remove the clause.

**Step 6, what you do not know.** The full proposal. Every email. Whether a dispute office is named on invoices. Whether the practice has assets or a bank account in Florida. Whether Dr. Ortiz made the "won't be paying" statement before or after the last invoice, which matters for anticipatory repudiation and mitigation.

### Red herrings
- "The proposal was never signed." Acceptance by email and payment is enough, and § 668.50 treats the email as signed.
- "It's over $500 so there has to be a writing." That is the UCC goods rule; this is services, and there are writings anyway.
- "1.5% a month is illegal." Eighteen percent simple is the ceiling, not over it.
- Dr. Ortiz personally. The P.A. contracted; he is not personally liable without a guaranty or veil piercing.

### Procedural and remedial angles
- Forum: county court in Miami-Dade (Eleventh Judicial Circuit). $13,500 exceeds the $8,000 (verify) small claims ceiling and is under $50,000 (verify). Cutline, as an LLC, must appear through a lawyer in county civil. Venue is proper where the defendant resides or the cause accrued (§ 47.011).
- Value: $13,500, or $9,500 if the check is accepted with repayment protection, plus interest and fees.
- Fees: contractual, mutual, see Issue 6. A proposal for settlement early can add pressure.
- Limitations: 5 years if the emails and proposal together are a contract "founded on a written instrument," 4 years if not (verify) (§ 95.11).
- Pre-suit: a demand letter that returns the check or states a 90-day repayment position, invokes the fee clause, and offers mediation.
- Collecting: a judgment against a P.A. can be enforced by garnishing the practice's bank account (ch. 77) and by proceedings supplementary (§ 56.29). No head-of-family exemption applies to an entity.

</details>
