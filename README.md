# The Limitation Constraint

**What AI can't change in regulated finance, and where it pays.**

---

## The claim

Three things constrain a lender in Southeast Asia: cost, information, and regulation. But regulation splits in two, and the halves behave nothing alike.

Part of it taxes you - the compliance load of data residency, model documentation, validation, reporting. A tax yields to money and to technology: spend enough, build well enough, and you proceed. Part of it limits you - what you may charge, whom you may serve, how you may collect. It yields to nothing you can buy or build, only to a decision made by someone who is not your customer. No individual firm can purchase its way past a limitation, though industry capability collectively does shape what regulators eventually permit.

AI relieves cost, expands information, and grinds down the taxing half of regulation. Limitation it does not touch. Limitation moves - constantly, and in this region against lenders - but never because an underwriting model got better.

So the underbanked narrative fails wherever a binding ceiling on what a lender may charge meets a rule that stops the lender making up in volume what it cannot make in margin. Indonesian consumptive online lending is the clean case. Much of SEA credit has the ceiling without the volume rule, and there the narrative can be partly right; auto, mortgage and corporate lending sit outside the argument entirely.

Where both bind, AI returns accrue to fraud loss avoided and to the unstructured share of cost per small ticket - not to risk pricing. Capital built on underwriting alpha here is not destroyed. It earns the market return instead of an excess one: the gains are real, and competed away rather than banked.

**In one line: AI helps with fraud, language and cost, and it helps a lot. It does not help where the pitch says it does - pricing credit risk - because the regulator, not the model, sets those numbers.**

## How the region built its rails

Southeast Asia is the region where the state mandated the payment rails and then drove merchant pricing to near zero - by direct price-setting in Indonesia, and by scheme arrangement or commercial waiver elsewhere. QRIS in Indonesia, PromptPay in Thailand, DuitNow in Malaysia, PayNow in Singapore, InstaPay and QR Ph in the Philippines, VietQR in Vietnam: mandated interoperability, merchant fees at or near zero, surcharging to consumers prohibited in several markets, and a growing set of bilateral cross-border links between them.

Indonesia is the clearest case. Bank Indonesia sets the QRIS merchant discount rate directly and takes none of the proceeds. Since March 2025 the schedule has been 0% for micro merchants on transactions up to IDR 500,000, 0.3% above that, 0.7% for small, medium and large merchants, 0.6% for education, 0.4% for fuel, and 0% for public services. The schedule is the same across every bank and wallet, and passing it to the consumer as a surcharge is prohibited. Providers still compete on acceptance, settlement, reliability and merchant services - but not on the headline merchant price, which is not theirs to set.

The consequences follow in strict order:

1. The domestic transaction fee earns almost nothing, so payments functions here mainly as a data-acquisition and distribution business.
2. The margin therefore moves downstream, and for most consumer-facing players it lands in credit.
3. Credit is squeezed from the other side - by price ceilings, by quantity rules, and by conduct rules that strip out collection leverage.

The result is a narrow corridor a licensed consumer lender operates inside. Reach every merchant in the country through free public rails, then underwrite from the flow your own customers generate on them rather than from collateral or bureau history. Price inside a hard ceiling, lend inside a hard limit on the borrower's total debt service, and collect within conduct constraints that remove the cheapest enforcement leverage.

Most strategies in this segment are either an attempt to widen the corridor or an attempt to exploit an asymmetry inside it. That includes the AI strategies.

## What AI does to each constraint

| Constraint | What it covers | What moves it | Direction of travel in SEA |
|---|---|---|---|
| Cost | Servicing, documents, support, first-line operations | Technology | Collapsing fast |
| Information | Thin-file underwriting, fraud detection, AML | Data access, then technology | Frontier genuinely expanding |
| Regulation - compliance load | Data residency, documentation, validation, reporting | Money and technology | Rising, but AI-addressable |
| Limitation - price | What you may charge | Policy decision | Ratcheted down 2024-2026; direction one-way |
| Limitation - quantity | Whom you may serve, how much, how often | Policy decision | Tightening |
| Limitation - conduct | How you may collect | Policy decision | Tightening |

> *Price means the all-in cost to the borrower - interest, margin, platform and administration fees together - not the headline interest rate.*

> *Policy decision means a determination made for prudential or consumer-protection reasons, exogenous to any individual firm.*

Only the first two limitations are ceilings. Conduct rules are prohibitions rather than magnitudes: a debt may not be disclosed to the borrower's contacts, collection may not involve threat or intimidation, contact may not fall outside permitted hours. There is no number to stay under.

SEA's limitations are unusually tight relative to how information-poor it is. You can underwrite a *warung* owner (a shop or food stall, typically family-run) brilliantly from the QRIS flow she generates with you - and still be unable to price the residual risk, because the ceiling caps it; unable to lend her the amount your model supports, because her total debt service is capped across every lender she uses; and unable to enforce, because conduct rules forbid that. The underwriting model gets smarter. None of the three rules cares.

Concretely, in Indonesia. Online lending here means the licensed peer-to-peer channel, and its consumptive products are typically unsecured, which is what makes the enforcement problem described later in this piece bite so hard. The all-in economic benefit cap - interest, margin, platform and administration fees together - has ratcheted down on a schedule set in advance: for short-tenor consumptive funding under one year, 0.3% per day from January 2024, 0.2% from January 2025, and 0.1% from 1 January 2026. Productive funding is capped separately. Total charges and late fees together may not exceed 100% of principal. The rules sit in SEOJK 19/SEOJK.06/2025, which replaced the 2023 circular that first set the ratchet, and complement POJK 40/2024.

This is not an Indonesian idiosyncrasy. The Philippines runs a comparable instrument on a narrower segment. BSP Circular 1133 covers unsecured general-purpose loans up to PHP 10,000 with tenors up to four months, capping nominal interest at 6% per month (about 0.2% per day), the effective rate - interest plus processing, service, handling and verification fees - at a higher all-in ceiling, penalties at 5% per month, and total cost at 100% of the amount borrowed. It ratchets too: SEC Memorandum Circular 14 of 2025 cut the effective-rate ceiling from 15% to 12% per month (about 0.40% per day) for loans written, restructured or renewed from 1 April 2026.

The Philippine regulator went further and named the workarounds inside the rule - restructuring, repackaging, splitting the loan amount, recharacterising fees, shifting the tenor, simulated collateral, sham guaranty - each defined as circumvention and each a violation. It is a catalogue of every clever thing a lender might do instead of pricing risk, closed pre-emptively.

Two regulators, two of the region's largest markets, the same all-in construction, the same 100%-of-principal backstop, the same direction of travel on perimeters that differ in width but not in mechanism. No underwriting model prices around a ceiling, and no underwriting model slows a ratchet.

## The objection this has to answer

There is one good argument against everything above, and it deserves to be put at full strength before it is answered.

A price ceiling does not destroy the value of better information. It changes what that information buys, and it changes it in three directions rather than one.

First, the cap fixes what the borrower pays. It does not fix the lender's realised loss rate, funding cost, servicing cost or fraud rate. Better selection at a capped price is a wider contribution margin - that is underwriting alpha, and it exists inside a binding ceiling. Second, a better model moves the **approval boundary**: same price, lower losses, more borrowers clearing breakeven, and the value arrives as volume, which is exactly what "AI unlocks credit for the underbanked" means. Third, price is not the only lever left. Limit, tenor, repayment schedule and repeat-loan progression are uncapped, and better information prices risk through all of them.

The prize looks enormous. Indonesian household debt stood at 15.0% of GDP at the end of 2025 - among the lowest ratios in the G20 - against 86.7% in Thailand and 84.3% in Malaysia on Bank Negara's own measure. The national series are not built on identical perimeters, so the gap is directional rather than precise, but no plausible reconciliation closes it, and on that comparison extending the approval frontier looks like the thesis of the decade.

All three are real, and none is defeated outright. What follows bounds them.

**A cap truncates the population rather than eliminating the alpha.** Better measurement raises contribution on borrowers you can already serve. What it cannot do is serve a borrower whose true risk requires a price above the ceiling, however precisely that risk is measured. So the value of better information is bounded by the width of the band between borrowers who are profitable at the cap and borrowers who would be profitable at an unconstrained price. Inside that band, the objection wins. Outside it, no model helps.

**And the entity with the model is often not the entity with the risk.** Indonesian platform lending is intermediation, not balance-sheet lending: the licensed operator runs the platform and earns fees, while funders carry the credit exposure - which is why the rules are built around mitigating *their* risk through credit insurance and guarantee institutions. Better selection therefore improves the funder's return, while the operator captures it only through fee levels or through risk positions the licence constrains. Where the model and the credit risk sit in different P&Ls, underwriting alpha is structurally harder to bank than the objection assumes.

**The ratchet showed that the band is a policy variable, not a competitive one.** Price limitation for short-tenor consumptive lending fell by two thirds between 2024 and 2026, on a schedule published in advance and wholly indifferent to underwriting quality. That step is complete; no further reduction is currently scheduled. What the episode demonstrates is not that the band keeps shrinking but that its width is set by policy and can be reset without reference to how well anyone underwrites - and quantity limitation did tighten with effect from 2026, so the direction of travel is intact even though the price step is finished.

**Quantity rules cap the size of the prize, not the channel.** From 2026 an Indonesian consumptive borrower's debt-service payments - principal plus economic benefit falling due - may not exceed 30% of income, down from 40%, and the payments counted are those to every creditor: platforms, banks, financing companies, pawnshops alike. Individual borrowers must also show a minimum monthly income of IDR 3 million and may use no more than three platforms. The ratio is economy-wide rather than channel-specific, so a borrower cannot free up platform capacity by moving to a bank loan. None of that stops a better model from finding more borrowers who satisfy the rules - that objection stands. What they do is close off growth through deeper penetration of existing borrowers, so volume must come from genuinely new ones, which is slower and more expensive than the underbanked framing implies.

**And the durable part of the advantage is not the model.** It is tempting to argue that underwriting gains diffuse because everyone sees the same data. That is wrong: interoperable rails are not a shared data pool. Transaction histories sit with the banks, wallets and acquirers that hold them, and a lender with proprietary repayment labels, merchant relationships, distribution and feedback loops has something genuinely defensible. But notice what that concession implies. The technique diffuses through papers, vendors and staff turnover; the data and the distribution do not. So the moat is the data and the distribution, and the model is what converts an advantage you already had into basis points. That is a real business. It is not evidence that AI unlocked anything.

Which leaves the honest position: under a binding cap the value of better underwriting is real, bounded by a band whose width is a policy variable, and attributable mostly to assets the lender held before any model existed. Wherever the cap does not bind, or nothing stops the lender making up in volume what it cannot make in margin, the objection wins outright - and that describes most of SEA outside Indonesian consumptive lending. It is a live business rather than a footnote.

## The uncomfortable equilibrium

The sharpest version of the claim concerns collection, and it has to be said carefully. Abusive collection is unlawful, it causes real harm, and the conduct rules that ban it are right. What follows is not a defence of it but an explanation of why it keeps returning despite the bans - and the conclusion is that prohibition alone will not end it.

Aggressive collection in SEA lending is not primarily a moral failure. It is an economic equilibrium. Small tickets, price ceilings, no practical wage garnishment against unsecured consumer debt, and enforcement of judgments measured in years mean that formal collection costs more than the debt is worth. Indonesia's small-claims track reaches judgment in roughly a month; execution of that judgment is slow and costly enough that, at these ticket sizes, it rarely repays pursuing. Social pressure was the only lever that paid for itself - and that is precisely the lever the conduct rules now ban, for good reason. But the rules removed the last economically viable enforcement tool without putting anything in its place.

That is why the abuse recurs no matter how many agencies are fined: the equilibrium is intact, and only the penalty for acting on it changed. And it is why anything that genuinely fills the hole - deduction at source, restructuring economics that beat default, cheaper legal execution, collateral you already physically hold - is valuable rather than merely compliant.

It also explains an otherwise odd fact. Pegadaian, Indonesia's state pawnbroker, is the size it is because pledged collateral is the one enforcement mechanism that survives every constraint. Possession does not confer a right to simply keep the asset - valuation, notice, sale and accounting for surplus all apply - but it converts enforcement from litigation into a regulated sale process, which is a different and far cheaper thing. The pawnshop is the equilibrium answer to broken enforcement.

## Four forces that make SEA structurally different for AI

**1. Sovereignty forces the architecture before anyone chooses it.** The constraint is sectoral rather than general. Indonesia's electronic-systems regime actually relaxed localisation for private operators; what binds a financial institution is the OJK and BI requirement to keep data centres onshore, together with supervisory-access and outsourcing conditions. Vietnam's Decree 53 requires specified entities to store defined data categories domestically rather than forbidding an offshore copy outright. The net effect is not a prohibition but a steep price: onshore infrastructure and approval processes raise the cost of routing customer PII to a frontier model offshore far enough that most regulated lenders decline to pay it. The resulting pattern (deterministic tokenisation onshore, small local models for anything identity-bearing, frontier models only over de-identified payloads) is the least glamorous and highest-leverage engineering problem in the whole space.

**2. Language is a compliance surface, not a UX nicety.** Frontier models remain measurably weaker in the region's languages - least so in Bahasa Indonesia, most in Javanese, Sundanese, Cebuano, Khmer and Burmese; weaker still at code-mixing; and weaker at scripts without word spacing, where segmentation errors compound. This has teeth. A collections agent that phrases something as a threat in Javanese, because the guardrail was red-teamed in English, has committed a conduct breach, not a bug.

**3. The adversary is already AI-native.** Industrialised scam operations in the region run LLM-generated scripts, real-time translation, and deepfake injection against liveness checks. The scale is not marginal: UNODC put 2025 losses across East Asia, Southeast Asia, Australia and New Zealand at between $88.3 billion and $114.1 billion, which it characterises as roughly threefold the $18-37 billion it estimated for 2023 - and expects these groups to adopt agentic systems that identify victims, run social engineering and move proceeds with progressively less human involvement. Defensive AI, not cost saving, is what actually pulls AI spend into the sector over the next three years. It is the one part of the stack where the opponent is also increasing its budget.

**4. Supervisory capacity shapes the rules more than ideology does.** Supervisors across the region work with materially smaller specialist benches than the industry they oversee, and rules are shaped by what can be examined consistently across every supervised firm rather than by what is technically ideal. Regulation therefore converges on the auditable: model inventories, documentation, human-in-loop attestation, reason codes, incident logs. Expect process-oriented rules and a gap between letter and substance. MAS, with the deepest supervisory capacity in the region, tends to set the template others adapt to local capacity. Where the binding requirement is evidence you can hand a supervisor, the compliance surface becomes the product.

## Where the value is

If the claim holds, value in SEA financial services accrues in this order:

1. **Cost per small ticket.** Making a $150 loan or a $4 insurance policy economically serviceable end to end. This is where an operator built for small tickets beats incumbents whose cost structures were designed for large ones.
2. **Fraud loss avoided.** The adversary is industrialised, the losses are uncapped, and every point avoided drops straight to the P&L.
3. **The compliance surface itself.** Where the rules demand auditable process, the cheapest credible evidence-production wins deals.

And the constrained one: better *price-based* risk discrimination on consumer credit - selection, limit, tenor and progression remain open, and are discussed above. The information frontier expands; the limitation frontier does not. Underwriting alpha inside a hard ceiling is real but bounded - by the ceiling, by the ratchet, and by the fact that most of what makes it defensible is data the lender already owned.

That list says where value can accrue. It does not say that AI is how to capture it, and in regulated finance frequently it is not.

Cost collapse is the largest of the three prizes, and most of it is available without a model at all. Where a task is deterministic - eligibility checks, limit calculations, document routing, reconciliation, contact-window rules, dunning schedules - the correct implementation is a written rule, not a learned one. The rule is cheaper to run, auditable line by line, does not drift, cannot hallucinate, and needs no monitoring regime.

That last point decides most cases. In a supervised institution the dominant lifetime cost of a model is not compute or licence fees. It is governance: model inventory, documentation, validation, ongoing monitoring, explanations and reason codes, incident logs, and the data-residency constraints that apply to anything identity-bearing (sovereignty, above). Deterministic automation carries far less of that load - it still needs ownership, testing, change control and audit trails, but none of the model-risk apparatus. And a rule can be examined directly, line by line; a model can mostly only be examined through the documentation around it.

So the second list - where a model specifically is the right instrument - reads differently:

1. **Fraud and financial crime**, because the adversary changes faster than rules can be rewritten. Of the three, this is the one where a rule is not a substitute.
2. **Language, voice and document handling**, because the input is genuinely unstructured and, as the language force above sets out, the vernacular gap is a conduct exposure rather than a user-experience one.
3. **Compliance evidence production**, where the required artefact is a document and the input is a mess.

Cost per small ticket sits first on one list and is largely absent from the other. Much of it is a process problem wearing an AI costume, and it will be delivered faster, cheaper and with less supervisory friction by a small piece of deterministic automation than by a model.

The practical sequence follows: fix the process first, automate whatever is specifiable, and reach for a model only where the input is genuinely unstructured or the pattern genuinely cannot be written down.

## Does this apply outside Southeast Asia?

The frame generalises. The conclusion does not.

Every financial market runs against the same three constraints - cost, information, and regulation - and everywhere regulation splits the same way, into the half that taxes and the half that limits. Asking which half binds is portable. The answer is not.

Europe compressed payment margins by regulation too, but through the opposite mechanism. Rather than building free public rails, it capped the incumbent ones - card interchange at 0.2% debit and 0.3% credit - and required that an instant transfer cost no more than a regular one. Price limitation exists there as well: national usury ceilings of long standing, and from 20 November 2026 a consumer-credit regime that extends the obligation to prevent excessive borrowing costs, brings BNPL into scope, and obliges the EBA to report on how member states set their caps.

So Europe is extending price limitation, not lacking it. Two things nonetheless break the SEA conclusion:

1. **Enforcement works.** Wage garnishment, payment-order procedures and functioning execution mean the equilibrium described above - the last economically viable enforcement tool removed with nothing put in its place - simply does not arise. A cap on top of working enforcement produces a different market from a cap on top of broken enforcement. That distinction, not the presence of caps, is what travels.
2. **The information frontier is narrow.** Credit bureaus are deep, so thin-file is a marginal problem rather than the central one. AI cannot expand a frontier that already sits close to its limit.

Europe's binding constraint is therefore neither limitation nor information. It is inherited core systems plus compliance load - the AI Act, DORA, data-protection and model-risk regimes - the taxing half of regulation, which does not block AI adoption but prices it per unit of value delivered.

That is the asymmetry, and the reason the same technology strategy does not travel. Southeast Asia can leapfrog into AI-native operations because it has less to unbuild; Europe pays a migration and governance tax on the identical move. Same regulation everywhere - but in Southeast Asia the limiting half binds, and in Europe the taxing half. Opposite implications for where the next dollar of AI spend belongs.

## What would prove this wrong

An argument is only worth publishing if it can lose. This one loses if:

1. **A price ceiling moves because models got better.** If any SEA regulator raises or removes a rate cap explicitly because underwriting quality improved, limitation responded to information and the core claim breaks.
2. **Quantity limitation loosens as underwriting improves.** If a regulator relaxes a debt-service ratio, funding limit or platform cap on the grounds that lenders can now identify good marginal borrowers, the approval-frontier objection wins on its own terms.
3. **Capped lenders show persistent underwriting alpha.** If lenders operating under a binding ceiling demonstrate durable risk-adjusted contribution attributable to better selection - lower losses at the same price, or profitable approval volumes their peers cannot match, sustained across cycles rather than one vintage - then the bound described above is too tight and the corollary fails. This is the central empirical test, and the one this essay is least able to run: it argues from the construction of the rules, not from observed portfolios.
4. **Risk-based pricing spreads inside the caps.** If lenders demonstrably price wide spreads inside the ceilings, the ceilings were not binding and the constraint is weaker than claimed.
5. **Enforcement gets replaced.** If a jurisdiction builds a cheap, working formal enforcement channel - wage-deduction regimes, fast small-claims execution at scale - the equilibrium argument dissolves. Happily.
6. **Models beat automation on deterministic work.** If institutions that replaced specifiable rules with models show better economics after governance costs are counted honestly, the automation-first sequence above is wrong.

## The assumption underneath

Those tests all ask whether the argument is wrong inside the world as it is. There is a larger question, which is what happens if the world stops having this shape.

Every rule described in this piece was written for a financial system operated by humans at human speed. Caps are flat because calibrating one per lender, continuously, is not something a supervisor can staff. Supervision is annual because reading a firm's actual behaviour in real time was never possible. Conduct is policed after the fact, by penalty, because there was no way to enforce it at the moment of contact. Enforcement is slow because courts are. Each of these is a design constraint of the era that produced it, not a law of nature - and AI arrived into the finished building rather than the blueprint. Everything in this sector is AI-retrofitted, including the rules.

An **AI-born** financial system cannot be built by firms alone, and that is this argument restated rather than a separate point. If limitation is what binds, then the thing that has to be AI-born is the limitation layer - the rules, the supervision, the enforcement - not the lenders. An AI lender operating inside a corridor drawn for humans is an AI-shaped firm in a human-shaped box.

So the sequence runs opposite to how it is usually pitched. **AI-born regulation**: rules written as executable specifications rather than prose a compliance function interprets and a supervisor later audits. **AI-born supervision**: continuous reading of what a firm actually does, which removes the reason caps have to be flat in the first place. **AI-born enforcement**: recovery designed into the instrument rather than pursued through courts afterwards - the hole that broke the equilibrium, closed by construction rather than by conduct rules that only forbid. That is the point at which due process has to be designed in rather than assumed: exempt income, hardship suspension, error correction and a contestable route back to a human. Enforcement that is cheap and automatic is precisely the kind that must be hardest to apply wrongly.

Only on top of that does an AI-born financial industry mean anything: pricing supervised continuously instead of capped in advance, eligibility calibrated per borrower instead of fixed at 30% for everyone, conduct enforced at the moment of contact instead of fined after it. In that system limitation would respond to information - the one thing this essay says it never does.

No jurisdiction has built this. It is a design brief, not a forecast, and probably not one this decade. But it names what transformation in this sector would actually require: not better models operating inside the corridor, but an AI-born corridor, drawn for a different kind of participant. Until then the argument stands, on an assumption worth saying plainly - this holds for as long as the rules are written for humans, by humans, at the speed humans can supervise.

---

## Figures and sources

Figures current as of August 2026. Where a rule is on a published schedule, the schedule is given rather than a single number.

- **QRIS merchant discount rate** - Bank Indonesia, effective 15 March 2025: 0% for micro merchants up to IDR 500,000, 0.3% above; 0.7% small/medium/large; 0.6% education; 0.4% fuel; 0% public services. Uniform across providers; consumer surcharging prohibited.
- **Indonesian online lending economic benefit cap** - SEOJK 19/SEOJK.06/2025 (replacing SEOJK 19/SEOJK.06/2023), with POJK 40/2024. Short-tenor consumptive funding under one year: 0.3% per day 2024, 0.2% 2025, 0.1% from 2026. Productive funding is capped separately; figures not reproduced here pending verification against the signed circular. Total charges and penalties capped at 100% of principal.
- **Indonesian borrower eligibility and exposure** - SEOJK 19/SEOJK.06/2025: debt-service-to-income ratio for consumptive funding 40% (2025) tightening to 30% (2026), counting payments to all creditors; minimum monthly borrower income IDR 3 million; maximum three platforms per borrower. Circular issued 31 July 2025; full compliance from 1 January 2026. The signed circular is not accessible outside Indonesia; the borrower-eligibility figures here are as reported in law-firm summaries of it, not checked against the primary text.
- **Household debt to GDP** - Indonesia 15.0% (Bank Indonesia / BPS, Dec 2025); Malaysia 84.3% (Bank Negara Malaysia, Mar 2025); Thailand 86.7% (end-2025, from 87.4% in Q1 2025). Note that third-party estimates for Malaysia around 69-70% use a narrower definition than BNM's own, and that the three national series are not built on identical perimeters.
- **Regional scam losses** - UNODC, *Transnational Organized Crime Threat Assessment for South-East Asia 2026* (21 July 2026): $88.3-114.1 billion in 2025 across East Asia, Southeast Asia, Australia and New Zealand, against $18-37 billion estimated for 2023.
- **Philippine interest ceilings** - BSP Circular 1133 (2021) and SEC Memorandum Circular 3 (2022): nominal 6%/month, effective 15%/month, penalties 5%/month, total cost 100% of principal, on unsecured general-purpose loans up to PHP 10,000 and up to 4 months. SEC Memorandum Circular 14 (10 December 2025) recalibrated the effective ceiling to 12%/month for loans written from 1 April 2026, and enumerated circumvention schemes as violations.
- **EU comparators** - Interchange Fee Regulation (EU) 2015/751; Instant Payments Regulation (EU) 2024/886, Article 5b; Consumer Credit Directive II (EU) 2023/2225, applying from 20 November 2026.

---

*Author: Yernar Terlikbayev · [LinkedIn](https://www.linkedin.com/in/yernart) · Part of an open collection on AI in regulated finance.*

*Licence: CC BY 4.0 (prose, not code).*
