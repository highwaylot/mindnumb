# Online and electronic contracts

**Module:** 03 · **Lesson:** 9 · **Time:** ~45 min
**Tags:** `[US]` `[FL]`

## Why this matters to a business owner

Your terms of service, your checkout page, and the vendor agreements you click through all form contracts, or fail to. Whether they bind depends on how the terms were presented and whether the user had to do something to accept them. If your terms are not enforceable, your liability cap, your arbitration clause, and your choice of Florida law all disappear. If your vendor's terms are enforceable, you agreed to things nobody read.

## The rule

Online contracts follow ordinary formation rules. The questions are the same: was there an offer, did the user manifest assent, and did the user have reasonable notice of the terms. Courts sort presentations into rough types.

1. **Clickwrap.** The user must click "I agree" after the terms are displayed or clearly linked next to the button. Almost always enforceable.
2. **Sign-in wrap.** The user clicks a button such as "Create account" or "Place order," with a nearby statement that doing so means agreeing to linked terms. Enforceable if the notice is conspicuous and placed where the user is looking when acting.
3. **Browsewrap.** Terms are available through a link, often in a footer, and the site says that use of the site means acceptance. Usually not enforceable unless the user actually knew of the terms, because mere use does not show assent to terms the user never saw.
4. **Shrinkwrap and terms-in-the-box.** Terms delivered with a product after payment, with a right to return if the buyer objects. Enforceable under *ProCD* if the buyer had an opportunity to review and reject.

**Electronic signatures and records.** Florida's Uniform Electronic Transactions Act, § 668.50, Fla. Stat., and the federal E-SIGN Act, 15 U.S.C. § 7001, give electronic records and signatures the same effect as paper, as long as the parties agreed to transact electronically, which can be shown by conduct. For consumer disclosures required by law, E-SIGN demands affirmative consent and a demonstration that the consumer can access the electronic format.

**Arbitration clauses.** The Federal Arbitration Act, 9 U.S.C. §§ 1 to 16, makes a written arbitration agreement in a contract involving interstate commerce valid and enforceable except on grounds that apply to any contract, such as fraud or unconscionability. States cannot single out arbitration clauses for hostile treatment. Class action waivers inside arbitration clauses are enforceable. *AT&T Mobility LLC v. Concepcion*, 563 U.S. 333 (2011). A delegation clause can send even the question of arbitrability to the arbitrator.

**Modification.** A site that reserves the right to change terms unilaterally must give notice of changes that is reasonably calculated to reach the user. Courts hesitate to bind users to terms changed silently.

The party seeking to enforce online terms bears the burden of proving the user assented, usually with screenshots of the flow as it existed at the time and records of the user's click.

## How courts reason about it

Two cases bracket the field.

*ProCD v. Zeidenberg* enforced a license printed inside a software box and displayed on screen. Judge Easterbrook reasoned that the seller, as master of the offer, could invite acceptance by conduct: using the software after a chance to read the terms and return the product. Airline tickets, insurance policies, and warranty cards all work that way.

*Nguyen v. Barnes & Noble* refused to enforce an arbitration clause in website terms reachable only by a footer link. Without evidence of actual knowledge, enforceability depends on whether the site put a reasonably prudent user on inquiry notice. A footer link, even one on every page, was not enough without some action tying the user's conduct to the terms.

The reasoning between those poles turns on a few variables.

- **Conspicuousness.** Font size, color contrast, placement relative to the action button, and whether the user had to scroll. Courts look at the actual screen, so the evidence is screenshots.
- **Temporal coupling.** A notice that appears at the moment of commitment, next to the button the user clicks, shows assent. A notice encountered at some other time does not.
- **Clarity of the message.** "By clicking Sign Up you agree to our Terms" with a hyperlink works. "Terms" alone in a footer does not.
- **Sophistication.** Courts are more willing to bind businesses than consumers, and more willing to bind repeat users than first-time visitors.
- **Arbitration policy.** Federal courts enforce arbitration clauses readily once assent is shown, and *Concepcion* stripped away most unconscionability attacks on class waivers. The fight has moved upstream to whether a contract formed at all, which is why *Nguyen* matters so much.

## Florida specifics

Florida follows the majority rule on clickwrap, browsewrap, and electronic signatures.

- **UETA** is § 668.50. Florida also has the Electronic Signature Act of 1996 at § 668.001 and following, which largely overlaps.
- Florida courts have enforced clickwrap terms including forum selection and arbitration clauses, and have refused browsewrap-style terms where the link was inconspicuous. *Vitacost.com, Inc. v. McCants*, 210 So. 3d 761 (Fla. 4th DCA 2017) (verify citation), declined to enforce a forum clause where the terms were reachable only by a link the customer was never required to view.
- **Revised Florida Arbitration Code**, ch. 682, governs arbitration agreements not covered by the FAA and supplies procedure where the FAA is silent. Most online contracts involve interstate commerce, so the FAA controls the enforceability question.
- **Forum selection clauses** are presumptively valid in Florida and enforced unless the resisting party shows they are unreasonable or unjust. Mandatory clauses ("shall be brought exclusively in") are distinguished from permissive ones ("may be brought in"), and only mandatory clauses require dismissal elsewhere.
- **Automatic renewal.** Section 501.165 requires clear and conspicuous disclosure of automatic renewal terms in consumer service contracts and, for longer contracts, notice before renewal (verify scope and current text). Federally, the Restore Online Shoppers' Confidence Act, 15 U.S.C. §§ 8401 to 8405, governs negative-option marketing online, and the FTC's 2024 "click-to-cancel" rule was vacated by the Eighth Circuit in 2025 (verify status).
- **FDUTPA** applies to deceptive online practices regardless of what the terms say. A disclaimer buried in terms does not cure a misleading checkout page. See module 07.

## Case anchors

- [`cases/procd-v-zeidenberg.md`](../cases/procd-v-zeidenberg.md): terms delivered with a product and accepted by use are binding when the buyer could review and return.
- [`cases/nguyen-v-barnes-and-noble.md`](../cases/nguyen-v-barnes-and-noble.md): a browsewrap footer link is not notice; without assent there is no arbitration agreement.

## Angles checklist

- How were the terms presented? Get the screenshots of the flow as it existed on the date in question.
- Did the user have to click anything that referenced the terms? Where was the notice relative to the button?
- Can you prove this user clicked? Logs, timestamps, IP, account records.
- Is the counterparty a consumer or a business? First-time or repeat user?
- Is there an arbitration clause, a class waiver, a delegation clause? Does the FAA apply?
- Were the terms changed after the user signed up, and how was notice given?
- Which terms actually matter: limitation of liability, forum, choice of law, fees, auto-renewal?
- Flip it: does a statute such as FDUTPA or ROSCA override the terms regardless of assent?

## Drill

A Boca Raton SaaS company's signup page has a "Start free trial" button. Two lines below it, in gray 9-point type, the page says "By continuing you agree to our Terms," with "Terms" hyperlinked. The Terms include Palm Beach County forum selection, a $500 liability cap, and arbitration with a class waiver. A Texas customer signs up, is charged $4,800 after the trial converts, and sues in Texas for deceptive billing, claiming it never saw the terms. Analyze.

<details>
<summary>Model answer</summary>

- **Type of agreement.** This is a sign-in wrap. The user clicked a button, and a notice near it referenced linked terms. Enforceability turns on whether the notice was conspicuous enough to put a reasonable user on inquiry notice.
- **Conspicuousness.** Gray 9-point type below the button is the weak point. Courts have gone both ways on similar designs. Factors for the company: the notice is adjacent to the button and uses "by continuing you agree." Factors against: small, low contrast, and below rather than above the button. Evidence of what the page actually looked like on that date is essential.
- **Arbitration and forum.** If assent is shown, the FAA requires enforcement of the arbitration clause, the class waiver is valid under *Concepcion*, and the Texas court should compel arbitration. If assent is not shown, under *Nguyen* there is no agreement at all, and everything in the Terms falls, including the cap and the forum clause.
- **Deceptive billing claim.** Regardless of the terms, the trial-to-paid conversion must comply with ROSCA and, if Florida law applies, § 501.165 and FDUTPA. A clear disclosure of the conversion before the user entered payment information is the key fact. The $500 cap does not limit statutory claims that provide their own remedies, and a cap that excused deceptive conduct would face unconscionability and public policy attacks.
- **Likely outcome.** Close on assent. A company that moved the notice above the button in normal-size type with a checkbox would win easily. As designed, it risks losing the arbitration clause and litigating in Texas.
- **Facts that would change it.** A required checkbox makes this clickwrap and ends the formation fight. Evidence the customer visited the Terms page supports actual notice. No pre-trial disclosure of price and date makes the ROSCA claim strong regardless of the contract.

</details>

## Check yourself

1. A vendor emails a PDF contract and the customer replies "Approved, go ahead." No signature line is signed. Is there a signed writing under Florida law?
2. Your terms of service say you may change them at any time by posting the new version. You add an arbitration clause and post it. Is a user who signed up last year bound?
3. Why does the question of whether a contract formed matter so much more for arbitration clauses than it used to?

<details>
<summary>Answers</summary>

1. Likely yes. Under § 668.50 an electronic record satisfies a writing requirement and a typed reply adopted with intent to sign is an electronic signature. The conduct also shows agreement to transact electronically.
2. Probably not, unless you gave notice reasonably calculated to reach the user, such as an email or an in-app prompt, and the user continued using the service afterward. Courts have refused to bind users to silently posted changes.
3. Because *Concepcion* and later cases removed most grounds for refusing to enforce an arbitration clause once it exists. The remaining battleground is whether the user ever assented, so formation doctrine, not unconscionability, now decides most online arbitration disputes.

</details>

## Verify and go deeper

- § 668.50, Fla. Stat. (UETA); §§ 668.001 to 668.006 (Electronic Signature Act of 1996); ch. 682 (Revised Florida Arbitration Code); § 501.165 (automatic renewal, verify).
- 15 U.S.C. § 7001 (E-SIGN); 9 U.S.C. §§ 1 to 16 (FAA); 15 U.S.C. §§ 8401 to 8405 (ROSCA).
- *ProCD, Inc. v. Zeidenberg*, 86 F.3d 1447 (7th Cir. 1996).
- *Nguyen v. Barnes & Noble Inc.*, 763 F.3d 1171 (9th Cir. 2014).
- *AT&T Mobility LLC v. Concepcion*, 563 U.S. 333 (2011).
- *Vitacost.com, Inc. v. McCants*, 210 So. 3d 761 (Fla. 4th DCA 2017) (verify citation).
