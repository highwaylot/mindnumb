# How to read a case

**Module:** 00 · **Lesson:** 2 · **Time:** ~60 min
**Tags:** `[US]` `[FL]`

## Why this matters to a business owner

A case is the record of a real fight and how a court resolved it. Reading cases is how you learn what a rule means at its edges, which is where your situation will sit. It is also how you stop being fooled by summaries. A headline saying "court rules non-compete unenforceable" tells you nothing until you know the facts that drove it.

## The rule

An appellate opinion has a predictable anatomy. Learn to find each part fast.

1. **Caption and citation.** *Olmstead v. Federal Trade Commission*, 44 So. 3d 76 (Fla. 2010). The first-named party is usually the appellant or petitioner, not necessarily the original plaintiff. "44 So. 3d 76" means volume 44 of the Southern Reporter, Third Series, page 76. "(Fla. 2010)" means the Florida Supreme Court decided it in 2010. "(Fla. 3d DCA 2008)" would mean the Third District Court of Appeal. "(11th Cir. 2009)" is the federal Eleventh Circuit. "(S.D. Fla. 2015)" is the federal district court for the Southern District of Florida. "(U.S. 1985)" or "471 U.S. 462" is the U.S. Supreme Court.
2. **Syllabus or headnotes.** Written by the publisher, not the court. Useful for navigation. Never cite them and never trust them over the opinion.
3. **Procedural posture.** How the case got here. Appeal from a final judgment, from an order granting summary judgment, from a dismissal, from a preliminary injunction, a certified question from a federal court. Posture matters because it sets the **standard of review** (lesson 4) and limits what the court is deciding.
4. **Facts.** The court's statement of what happened. On appeal from a dismissal, the court assumes the complaint's allegations are true. On appeal from a jury verdict, the court takes the facts in the light most favorable to the verdict. So "the facts" are often the facts as one side told them.
5. **Issue.** The question presented. Good opinions state it in one sentence. Many do not, and you have to reconstruct it.
6. **Holding.** The court's answer to the issue, which becomes the rule of the case. Keep it as narrow as the facts require. A holding that "a two-year non-compete against a sales rep with no customer relationships was unenforceable" is not a holding that two-year non-competes are unenforceable.
7. **Reasoning.** How the court got from the issue to the holding. This is where the value is. Look for: the rule the court started from, the cases it followed, the cases it distinguished, the facts it emphasized, the policy concerns it named, and the arguments it rejected.
8. **Dicta.** Statements in the opinion not necessary to the decision. "Had the agreement been limited to one year, we might view it differently" is dicta. Dicta is not binding but tells you how the court is thinking.
9. **Disposition.** Affirmed, reversed, reversed and remanded, quashed, certified question answered. "Remanded" means sent back to the trial court for more proceedings consistent with the opinion.
10. **Concurrences and dissents.** A concurrence agrees with the result but writes separately, often to narrow or broaden the reasoning. A dissent disagrees. Dissents matter because they show the strongest counterargument, and sometimes become the law later.

### Holding versus dicta: the test

Ask: if you removed this statement, would the result change? If not, it is dicta.

### Majority, plurality, per curiam, en banc

- A **majority** opinion speaks for the court.
- A **plurality** opinion has the most votes for a result but no majority on the reasoning. Only the narrowest ground that commanded a majority is binding.
- **Per curiam** means "by the court," unsigned. In Florida, a per curiam affirmance without a written opinion has no precedential value.
- **En banc** means the full appellate court sat, rather than a three-judge panel. En banc decisions override earlier panel decisions.

## How courts reason about it

Courts read earlier cases the same way you are learning to. They extract a holding, decide whether the present facts are materially the same, and either **follow** the case, **distinguish** it (the facts differ in a way that matters), or in rare cases **overrule** it. Lesson 4 covers this.

The skill to build now is **briefing**: condensing an opinion to its working parts in your own words. Use the template in `templates/case-brief.md`. The discipline of writing the holding in one sentence, narrowly, is the whole exercise.

### A worked example

Take *Olmstead v. FTC*, 44 So. 3d 76 (Fla. 2010).

- **Posture:** The Eleventh Circuit certified a question of Florida law to the Florida Supreme Court. The Olmsteads had been ordered by a federal court to turn over their interests in single-member LLCs to a receiver to satisfy an FTC judgment. They argued Florida's charging-order statute was a creditor's only remedy against an LLC interest.
- **Facts that mattered:** The LLCs were single-member. The judgment debtors owned 100%.
- **Issue:** Whether, under Florida's LLC statute as it then stood, a charging order was the exclusive remedy of a judgment creditor against a single-member LLC's membership interest.
- **Holding:** No. The statute did not say the charging order was exclusive, and the general remedy of levying on a debtor's property remained available. A court could order the debtor to surrender all right, title, and interest in a single-member LLC.
- **Reasoning:** Textual (the statute lacked the word "exclusive," while the limited partnership statute had it); structural (the charging order protects *other* members from an outsider being forced on them, and a single-member LLC has no other members to protect); comparison to corporate shares, which can be levied on.
- **Dissent:** Argued the majority rewrote the statute and that the Legislature, not the court, should change it.
- **What happened next:** The Legislature responded in 2011, and the current § 605.0503 makes the charging order the exclusive remedy for multi-member LLCs while allowing foreclosure of a single-member LLC interest when the charging order will not satisfy the judgment in a reasonable time.

That last point is a general lesson: **a case can be superseded by statute**. Always check whether the Legislature answered.

## Florida specifics

- Florida reporters: Florida Supreme Court and DCA opinions appear in the Southern Reporter (So., So. 2d, So. 3d). Since 2020, Florida also uses a public-domain citation form like "2024 WL ..." or the court's own slip opinion numbers. Online Sunshine does not host case law; use the courts' sites, Google Scholar, or CourtListener.
- Florida DCA opinions often decide cases in a few pages. Federal appellate opinions can run fifty. The reading method is the same.
- When a Florida court "certifies conflict" with another DCA or "certifies a question of great public importance," it is inviting the Florida Supreme Court to take the case. Those cases are worth watching because the rule may change.

## Case anchors

- [`cases/olmstead-v-ftc.md`](../cases/olmstead-v-ftc.md): the worked example above.
- [`cases/lucy-v-zehmer.md`](../cases/lucy-v-zehmer.md): a short, clean opinion to practice briefing on.

## Angles checklist

When you pick up any case:

- What was the posture, and what facts did that posture force the court to assume?
- What is the narrowest statement of the holding that still decides the case?
- Which facts did the court repeat? Those are the ones it relied on.
- What did the losing side argue, and why did it fail?
- Is there a dissent? What is its best point?
- Has a statute or later case changed this?
- Was this a Florida court, a federal court predicting Florida law, or another state?

## Drill

Read [`cases/lucy-v-zehmer.md`](../cases/lucy-v-zehmer.md). Before opening the brief's holding section, write your own one-sentence holding. Then compare. Then write one fact change that would flip the result.

<details>
<summary>Model answer</summary>

A holding like: "A contract is formed when a party's words and acts, judged by what a reasonable person would understand, manifest an intent to be bound, regardless of that party's secret intent to joke." A narrower version: "Where a seller negotiates the terms of a land sale for forty minutes, writes and signs a memorandum, and has his wife sign it, his later claim that he was joking does not defeat the contract."

A fact change that flips it: if Zehmer had said "just kidding" and torn up the paper before Lucy left, or if Lucy had known Zehmer was joking, there would be no reasonable manifestation of assent.

</details>

## Check yourself

1. The court says "we need not decide whether a one-year restriction would be enforceable." Is that dicta or holding?
2. On appeal from a motion to dismiss, the court recites that the defendant "fraudulently induced the plaintiff." Has the court found fraud?
3. A Florida Supreme Court opinion from 2010 construes a statute. The statute was amended in 2011. What do you do?

<details>
<summary>Answers</summary>

1. Dicta. It expressly declines to decide it. It does signal the court sees the question as open.
2. No. On a motion to dismiss the court assumes the complaint's allegations are true. It is reciting the allegation, not finding the fact.
3. Read the amended statute. Determine whether the amendment changed the rule the court announced. The case may still be good law for its reasoning on parts of the statute that were not changed, and for events before the amendment's effective date.

</details>

## Verify and go deeper

- *Olmstead v. FTC*, 44 So. 3d 76 (Fla. 2010); § 605.0503, Fla. Stat. (current charging-order rule).
- *Lucy v. Zehmer*, 196 Va. 493, 84 S.E.2d 516 (1954).
- Fla. R. App. P. 9.030 (what each Florida appellate court can review).
