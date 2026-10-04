# The Limitation Constraint

**What AI can't change in regulated finance, and where it pays.**

---

## The claim

Three things constrain a lender in Southeast Asia: cost, information, and regulation. But regulation also splits in two, and the halves behave nothing alike.

One part of it burdens you - the compliance load of data residency, model documentation, validation, reporting. A burden yields to money and to technology: spend enough, build well enough, and you proceed. Another part of it limits you - what you may charge, whom you may serve, how you may collect. It yields to nothing you can buy or build, only to a decision made by someone who is not your customer. No individual firm can purchase its way past a limitation, though industry capability collectively does shape what regulators eventually permit.

AI relieves cost, expands information, and grinds down the burden half of regulation. Limitation it does not touch. Limitation moves - mostly against lenders, occasionally in their favour - but never because an underwriting model got better.

So the popular story - that AI will open up credit to people banks do not serve - fails wherever two rules meet: a price ceiling that actually holds prices down, and a limit on how much each borrower may owe, which stops the lender making up in volume what it cannot make in price. Indonesian consumptive online lending is the clearest case. Much of SEA credit has the ceiling without the borrowing limit, and there the story can be partly right; auto, mortgage and corporate lending sit outside the argument entirely.

Where both rules apply, AI pays through the fraud it stops and the manual work it removes from serving small loans - not through pricing risk better. Investors who backed a lender for its superior credit scoring do not lose their money. They earn an ordinary return instead of the premium they were promised: the gains are real, but competition takes them away before the lender can keep them.

**In one line: AI helps with fraud, language and cost, and it helps a lot. It does not help where the pitch says it does - pricing credit risk - because the regulator, not the model, sets those numbers.**

## How the region built its payment systems

In Southeast Asia, governments required banks and wallets to connect to shared payment systems and then pushed the fee merchants pay to near zero - by setting the price directly in Indonesia, and through scheme rules or fee waivers elsewhere. QRIS in Indonesia, PromptPay in Thailand, DuitNow in Malaysia, PayNow in Singapore, InstaPay and QR Ph in the Philippines, VietQR in Vietnam: any app can pay any merchant, merchant fees are at or near zero, several markets ban passing the fee on to consumers, and a growing number of these systems are linked across borders.

Indonesia is the clearest case. Bank Indonesia sets the QRIS merchant discount rate directly and takes none of the proceeds. Since March 2025 the schedule has been 0% for micro merchants on transactions up to IDR 500,000 (about $28), 0.3% above that, 0.7% for small, medium and large merchants, 0.6% for education, 0.4% for fuel, and 0% for public services - and from 1 October 2026 Bank Indonesia extended the 0% rate to every merchant category for transactions up to IDR 100,000 (about $6). The schedule is the same across every bank and wallet, and passing it to the consumer as a surcharge is prohibited. Providers still compete on how many merchants accept them, how fast merchants get paid, reliability and extra services for merchants - but not on the merchant fee, which is not theirs to set.

Three things follow, each from the one before:

1. Processing a domestic payment earns almost nothing, so payment companies use it mainly to gather customer data and to reach customers.
2. The money therefore has to be made elsewhere, and for most consumer-facing players that means lending.
3. Lending is squeezed from the other side - by price ceilings, by limits on how much each borrower may owe, and by collection rules that remove the cheapest ways to make borrowers pay.

The result is a narrow corridor a licensed consumer lender operates inside. Reach every merchant in the country through free public payment systems, then judge creditworthiness from the payments your own customers make on them rather than from collateral or credit bureau records. Charge no more than the ceiling, lend no more than the limit on the borrower's total debt payments allows, and collect under rules that ban the cheapest ways to make borrowers pay.

Almost every strategy in this segment does one of two things: it tries to win more room than the rules allow - a looser licence, a segment the caps do not reach, a case made to the regulator - or it finds an edge others lack inside the same rules: better data, cheaper funding, cheaper collection. AI strategies are no exception, and nearly all of them are the second kind.

## What AI does to each constraint

| Constraint | What it covers | What moves it | What AI does | Trend in SEA |
|---|---|---|---|---|
| Cost | Servicing, documents, support, first-line operations | Technology | Cuts it | Falling: e-KYC, e-signatures, free payment systems, automation |
| Information | Thin-file underwriting, fraud detection, AML | Data access, then technology | Widens it | Improving: more borrowers can be assessed |
| Regulation - burden | Data residency, documentation, validation, reporting | Money and technology | Lowers the cost of meeting it | Rising: new rules every year |
| Limitation - price | What you may charge | Policy decision | Cannot move it | Both ways: Indonesia dropped its planned cut, the Philippines cut its ceiling |
| Limitation - quantity | Whom you may serve, how much, how often | Policy decision | Cannot move it | Tightening |
| Limitation - conduct | How you may collect | Policy decision | Cannot move it | Tightening |

> *Price means the all-in cost to the borrower - interest, margin, platform and administration fees together - not the headline interest rate.*

> *Policy decision means a decision the regulator makes to keep lenders safe or to protect consumers, outside any single firm's control.*

Only the first two limitations are ceilings. Conduct rules ban things rather than set a number: a debt may not be disclosed to the borrower's contacts, collection may not involve threat or intimidation, contact may not fall outside permitted hours. There is no number to stay under.

In Southeast Asia lenders know little about most borrowers, so better data could help a lot - yet the limits are tight enough to block most of that gain. You can underwrite a *warung* owner (a shop or food stall, typically family-run) brilliantly from the QRIS payments she takes through you - and still be unable to charge for the risk that remains, because the ceiling caps the price; unable to lend her the amount your model supports, because her total debt service is capped across every lender she uses; and unable to enforce, because conduct rules forbid that. The underwriting model gets smarter. None of the three rules cares.

Concretely, in Indonesia. Online lending here means the licensed peer-to-peer channel, and its consumptive products are typically unsecured, which is what makes the enforcement problem described later in this piece bite so hard. The all-in economic benefit cap - interest, margin, platform and administration fees together - is set per day by product and tenor. Consumptive funding is capped at 0.3% per day on tenors up to six months and 0.2% beyond. Productive funding up to IDR 50 million (about $2,800) is capped at 0.275% up to six months and 0.1% beyond, and larger productive funding at 0.1%. Late fees carry the same daily caps, and total charges and late fees together may not exceed 100% of principal. The rules sit in SEOJK 19/SEOJK.06/2025, which implements POJK 40/2024 and replaced a 2023 circular that had published a schedule cutting the consumptive cap from 0.3% to 0.2% in 2025 and 0.1% in 2026. OJK replaced that schedule with the current grid from January 2025, and the 2026 step never came.

This is not just an Indonesian quirk. The Philippines runs a comparable instrument on a narrower segment. BSP Circular 1133 covers unsecured general-purpose loans up to PHP 10,000 (about $160) with tenors up to four months, capping nominal interest at 6% per month (about 0.2% per day), the effective rate - interest plus processing, service, handling and verification fees - at a higher all-in ceiling, penalties at 5% per month, and total cost at 100% of the amount borrowed. It moves by policy decision too: SEC Memorandum Circular 14 of 2025 cut the effective-rate ceiling from 15% to 12% per month (about 0.40% per day) for loans written, restructured or renewed from 1 April 2026.

The SEC went further and named the workarounds inside the rule - restructuring, repackaging, splitting the loan amount, recharacterising fees, shifting the tenor, simulated collateral, sham guaranty, disguised charges - each defined as circumvention and each a violation. In effect, it lists every trick a lender might use to get around the ceiling and bans each one in advance.

Two countries, two of the region's largest markets, the same all-in construction, the same 100%-of-principal backstop, the same design applied to segments of different size - and the same proof that the number is a policy choice: Manila cut its ceiling for 2026 while Jakarta held its own above the schedule it had published. No underwriting model prices around a ceiling, and no underwriting model moved either decision.

## The objection this has to answer

There is one good argument against everything above, and it deserves to be put at full strength before it is answered.

A price ceiling does not destroy the value of better information. It changes what that information buys, and it changes it in three directions rather than one.

First, the cap fixes what the borrower pays. It does not fix the lender's actual loss rate, funding cost, servicing cost or fraud rate. Better selection at a capped price means a wider margin on each loan - extra profit from better underwriting, and it exists even under a ceiling that holds prices down. Second, a better model moves the **approval line**: same price, lower losses, more borrowers above break-even, and the value arrives as volume, which is exactly what "AI unlocks credit for the underbanked" means. Third, price is not the only lever left. Loan size, tenor, repayment schedule and how fast repeat borrowers move to bigger loans are not capped, and better information prices risk through all of them.

The prize looks enormous. Indonesian household debt stood at 15.5% of GDP at the end of 2025 - among the lowest ratios in the G20 - against 86.7% in Thailand and 84.8% in Malaysia on Bank Negara's own measure. The national figures are not measured in exactly the same way, so the comparison is rough, but no adjustment comes close to closing the gap, and on that comparison approving more of these borrowers looks like the investment case of the decade.

All three are real, and none is defeated outright. What follows bounds them.

**A cap cuts off the riskiest borrowers; it does not remove the gain on the rest.** Better data raises profit on borrowers you can already serve. What it cannot do is serve a borrower whose true risk needs a price above the ceiling, however precisely that risk is measured. So better data pays only inside a band: the borrowers who are profitable at the capped price. The cap sets how wide that band is. Inside it, the objection wins. Outside it, no model helps. The arithmetic is short: at 0.3% per day a 30-day loan earns at most 9% of principal, so a borrower who defaults more than about one time in twelve loses the lender money at any legal price - before funding and servicing costs, which push that threshold lower. Those borrowers do not disappear when a licensed lender turns them away; they go to informal and illegal lenders.

**And the entity with the model is often not the entity with the risk.** Indonesian platform lending is intermediation, not balance-sheet lending: the licensed operator runs the platform and earns fees, while funders carry the credit exposure - which is why the rules are built around mitigating *their* risk through credit insurance and guarantee institutions. Better selection therefore improves the funder's return, while the operator captures it only through fee levels or through risk positions the licence constrains. When the model sits with one company and the credit loss with another, the operator keeps less of the gain from better selection than the objection assumes.

**The regulator, not competition, sets the width of the band - and Indonesia has moved it both ways.** In 2023 OJK published a schedule cutting the short-tenor consumptive cap by two thirds by 2026. Before the cut was complete it rewrote the rule: from January 2025 the cap held at 0.3% per day for tenors up to six months, fell to 0.2% only for longer ones, and nearly tripled, to 0.275%, for short productive loans up to IDR 50 million (about $2,800). OJK's stated aims were easier access to finance at a rate it called tolerable for the risk, and protecting funders, who carry the credit loss with no deposit insurance behind them. Better models were not the reason; OJK paired the change with an instruction to screen borrowers harder. The width of the band was set, and then reset, without reference to how well anyone underwrites - and quantity limitation did tighten with effect from 2026, when the debt-service limit fell from 40% to 30% of income.

**The debt-service limit caps the whole market, not one channel.** From 2026 an Indonesian consumptive borrower's debt-service payments - principal plus economic benefit falling due - may not exceed 30% of income, down from 40%, and the payments counted are those to every creditor: platforms, banks, financing companies, pawnshops alike. Individual borrowers must also show a minimum monthly income of IDR 3 million (about $170) and may use no more than three platforms. The ratio is economy-wide rather than channel-specific, so a borrower cannot free up platform capacity by moving to a bank loan. None of that stops a better model from finding more borrowers who satisfy the rules - that objection stands. What they do is stop lenders growing by lending more to the borrowers they already have, so volume must come from genuinely new ones, which is slower and more expensive than the underbanked framing implies.

**And the durable part of the advantage is not the model.** It is tempting to argue that underwriting gains diffuse because everyone sees the same data. That is wrong: shared payment systems are not a shared data pool. Transaction histories sit with the banks, wallets and acquirers that hold them, and a lender with proprietary repayment labels, merchant relationships, distribution and feedback loops has something genuinely defensible. But notice what that concession implies. Modelling techniques spread through research papers, vendors and staff who change jobs; the data and the distribution do not. So the moat is the data and the distribution, and the model is what converts an advantage you already had into basis points. That is a real business. It is not evidence that AI unlocked anything.

Which leaves the honest position: under a cap that holds prices down, the value of better underwriting is real, limited to a band whose width the regulator sets, and comes mostly from assets the lender held before any model existed. Wherever the cap does not hold prices down, or nothing stops the lender making up in volume what it cannot make in price, the objection wins outright - and that describes most of SEA outside Indonesian consumptive lending. It is a live business rather than a footnote.

## Why abusive collection keeps coming back

The sharpest version of the claim concerns collection, and it has to be said carefully. Abusive collection is unlawful, it causes real harm, and the conduct rules that ban it are right. What follows is not a defence of it but an explanation of why it keeps returning despite the bans - and the conclusion is that prohibition alone will not end it.

Aggressive collection in SEA lending is not mainly a moral failure. It is what the economics produce. Small loans, price ceilings, no practical way to take repayments from an unsecured borrower's wages, and court judgments that take years to enforce mean that collecting through formal channels costs more than the debt is worth. Indonesia's small-claims track reaches judgment in roughly a month; execution of that judgment is slow and costly enough that, at these ticket sizes, it rarely repays pursuing. Social pressure was the only lever that paid for itself - and that is precisely the lever the conduct rules now ban, for good reason. But the rules removed the last economically viable enforcement tool without putting anything in its place.

That is why the abuse recurs no matter how many agencies are fined: the economics have not changed; only the penalty has. And it is why anything that genuinely fills the hole - deduction at source, restructuring economics that beat default, cheaper legal execution, collateral you already physically hold - is valuable rather than merely compliant.

It also explains an otherwise odd fact. Pegadaian, Indonesia's state pawnbroker, is the size it is because pledged collateral is the one enforcement mechanism that survives every constraint. Possession does not confer a right to simply keep the asset - valuation, notice, sale and accounting for surplus all apply - but it converts enforcement from litigation into a regulated sale process, which is a different and far cheaper thing. The pawnshop is what the market builds when the courts cannot enforce small debts.

## Four things that make AI different in Southeast Asia

**1. Data rules decide how a lender's AI is built.** In Indonesia, ordinary tech companies may keep data abroad, but banks and lenders must keep their data centres in the country under OJK and Bank Indonesia rules. Vietnam requires some kinds of data to be stored locally, and a company must file an assessment before sending personal data abroad. Neither country bans sending customer data to an offshore AI model, but the approvals and local servers cost enough that most lenders don't do it. So their AI ends up built the same way. Names, ID numbers and phone numbers are replaced with codes before anything leaves the country. Small AI models on local servers handle any task that needs to know who the customer is, such as checking an ID card. Powerful offshore models like ChatGPT or Claude see only data with the identity removed. This layer is plumbing, not AI, but every customer-facing AI tool has to pass through it, so a lender that builds it once can launch each later tool cheaply.

**2. A language mistake is a rule breach, not just bad service.** The leading AI models are measurably weaker in the region's languages: least in Bahasa Indonesia, most in Javanese, Sundanese, Cebuano, Khmer and Burmese. They are weaker still when speakers mix two languages in one sentence, as many do, and in scripts such as Thai, Khmer and Burmese that put no spaces between words, so the model can split words wrongly and the errors pile up. This matters because collection rules ban threats. If an AI collection agent's safety checks were tested only in English, and it says something that reads as a threat in Javanese, the lender has broken the conduct rules. The regulator will treat it as a breach, not a software bug.

**3. Scammers already use AI.** Organised scam operations in the region use AI to write their scripts, translate in real time, and fool the selfie and video checks used to open accounts with deepfakes. The losses are large: UNODC put 2025 losses across East Asia, Southeast Asia, Australia and New Zealand at between $88.3 billion and $114.1 billion, and judges losses in East and Southeast Asia alone to be about three times its $18-37 billion estimate for 2023. It expects these groups to adopt AI agents that find victims, run the deception and move the money with less and less human involvement. Lenders are targets, not bystanders. Scammers take out loans with stolen or invented identities and vanish with the money, take over real borrowers' accounts and draw on their credit limits, push victims into borrowing and handing over the cash, and pose as the lender or its collectors to collect repayments. Under Indonesia's cap the arithmetic is harsh: a 30-day loan at the cap earns at most 9%, so one fraudulent loan wipes out what about eleven good loans of the same size can earn. So over the next three years, lenders will spend on AI mainly to defend against fraud, not to cut costs. It is the one area where the other side is also spending more every year.

**4. Regulators write rules they can check.** Supervisors in the region have far fewer specialists than the firms they supervise. So they write rules they can check the same way at every firm, not the rules that would be technically best. That pushes regulation towards records that can be inspected: a list of every AI model in use, documentation, a sign-off that a human reviewed decisions, a stated reason for each decision, and a log of incidents. Expect rules about process, and a gap between following a rule's wording and achieving its purpose. Singapore's MAS, which has the most supervisory expertise in the region, usually writes the first version, and other regulators adapt it to what they can supervise. Where the rule asks for evidence you can hand a supervisor, the tool that produces that evidence becomes the thing worth building and selling.

## Where the value is

If the claim holds, value in SEA financial services lands in this order:

1. **Cost per small ticket.** Making a $150 loan or a $4 insurance policy cheap enough to serve from start to finish. This is where an operator built for small tickets beats incumbents whose cost structures were designed for large ones.
2. **Fraud loss avoided.** Scammers work at industrial scale, fraud losses have no ceiling, and every loss avoided adds straight to profit.
3. **Evidence for the supervisor.** Where the rules demand records a supervisor can inspect, the firm that produces credible evidence most cheaply wins the deals.

And the limited one: charging different prices for different risks on consumer credit. Choosing whom to lend to, how much within the borrowing limits, for how long and how fast to raise limits stays open, as discussed above. Better data widens what lenders know; it does not widen what they may charge. Extra profit from better underwriting under a hard ceiling is real but limited - by the ceiling, by a band that policy sets and resets, and by the fact that most of what makes it defensible is data the lender already owned.

That list says where value can land. It does not say that AI is how to capture it, and in regulated finance frequently it is not.

Cutting the cost of small loans is the largest of the three prizes, and most of it needs no AI model at all. Where a task follows fixed rules - eligibility checks, limit calculations, document routing, reconciliation, permitted contact hours, payment reminder schedules - the right tool is a written rule, not a trained model. The rule is cheaper to run, auditable line by line, does not drift, cannot hallucinate, and needs no monitoring regime.

That last point decides most cases. In a supervised institution the dominant lifetime cost of a model is not compute or licence fees. It is governance: model inventory, documentation, validation, ongoing monitoring, explanations and reason codes, incident logs, and the data-location rules that apply to anything that identifies a customer (the first of the four things above). Rule-based automation carries far less of that load - it still needs ownership, testing, change control and audit trails, but none of the model-risk machinery. And a rule can be examined directly, line by line; a model can mostly only be examined through the documentation around it.

So the second list - where a model specifically is the right instrument - reads differently:

1. **Fraud and financial crime**, because scammers change tactics faster than rules can be rewritten. Of the three, this is the one where a rule is no substitute.
2. **Language, voice and document handling**, because the input is genuinely unstructured and, as the second of the four things above sets out, a mistake in a local language is a conduct breach, not just bad service.
3. **Evidence for the supervisor**, where the required output is a document and the inputs are scattered and messy.

Cost per small ticket sits first on one list and is largely absent from the other. Much of it is a process problem wearing an AI costume, and it will be delivered faster, cheaper and with less supervisory friction by a small piece of rule-based automation than by a model.

The practical sequence follows: fix the process first, automate whatever can be written as a rule, and reach for a model only where the input is genuinely unstructured or the pattern genuinely cannot be written down.

## Does this apply outside Southeast Asia?

The way of thinking travels. The conclusion does not.

Every financial market runs against the same three constraints - cost, information, and regulation - and everywhere regulation splits the same way, into the half that burdens and the half that limits. The question of which half holds you back works anywhere. The answer differs.

Europe compressed payment margins by regulation too, but through the opposite mechanism. Rather than building free public payment systems, it capped the fees on the existing ones - card interchange at 0.2% debit and 0.3% credit - and required that an instant transfer cost no more than a regular one. Price limitation exists there as well: national usury ceilings of long standing, and from 20 November 2026 a consumer-credit regime that extends the obligation to prevent excessive borrowing costs, brings BNPL into scope, and obliges the EBA to report by 2029 on how member states set their caps.

So Europe is extending price limitation, not lacking it. Two things nonetheless break the SEA conclusion:

1. **Enforcement works.** Deductions from wages, fast court payment orders and working enforcement of judgments mean the problem described above - the last affordable way to make borrowers pay removed with nothing in its place - does not arise. A cap on top of working enforcement produces a different market from a cap on top of broken enforcement. That distinction, not the presence of caps, is what travels.
2. **There is little left to learn about borrowers.** Credit bureaus are deep, so borrowers with no credit history are a side problem, not the central one. AI cannot add much to what lenders know when they already know most of it.

Europe's main constraint is therefore neither limitation nor information. It is inherited core systems plus compliance load - the AI Act, DORA, data-protection and model-risk regimes - the burden half of regulation, which does not block AI but makes every use of it cost more.

That is the asymmetry, and the reason the same technology strategy does not travel. Southeast Asia can move AI into its operations faster because it has less to unbuild; Europe pays a migration and governance tax on the same move. Same regulation everywhere - but in Southeast Asia the limiting half holds lenders back, and in Europe the burden half. Opposite implications for where the next dollar of AI spend belongs.

## What would prove this wrong

An argument is only worth publishing if it can lose. This one loses if any of these happens:

1. **A regulator raises a price cap because lenders got better at judging risk.** If any SEA regulator raises or removes a rate cap and says it did so because underwriting improved, the core claim breaks. The nearest case so far is Indonesia holding its short-tenor cap at 0.3% from 2025 instead of cutting it as scheduled. That moved the cap in lenders' favour, but OJK's reasons were access to finance and a price it called tolerable for the risk, not better underwriting.
2. **A regulator loosens borrowing limits because lenders got better at judging risk.** If a regulator relaxes the debt-service limit, the per-borrower cap or the three-platform rule because lenders can now pick out good borrowers near the approval line, the objection wins: better data would be unlocking more lending.
3. **Lenders under a cap keep earning more from better underwriting.** If lenders under a cap that holds prices down make more profit after losses than their peers because they pick borrowers better - lower losses at the same price, or profitable volume their peers cannot match - and keep doing it through good years and bad, not just for one batch of loans, then this essay understates what better data is worth. This is the most important test, and the one this essay cannot run itself: it argues from how the rules are written, not from lenders' actual loan books.
4. **Lenders charge very different prices under the cap.** If lenders charge risky and safe borrowers very different prices well below the ceiling, the ceiling was not holding prices down, and the constraint is weaker than claimed.
5. **A country makes formal collection cheap and effective.** If a country builds a cheap, working way to collect - deductions from wages, fast small-claims enforcement at scale - the argument about abusive collection falls away. Happily.
6. **AI models beat written rules on routine work.** If firms that replaced written rules with AI models do better once the full cost of governing those models is counted, the advice to automate with rules first is wrong.

## The assumption underneath

Those tests all ask whether the argument is wrong inside the world as it is. There is a larger question, which is what happens if the world stops having this shape.

Every rule described in this piece was written for a financial system operated by humans at human speed. Caps are flat because calibrating one per lender, continuously, is not something a supervisor can staff. Supervision is annual because reading a firm's actual behaviour in real time was never possible. Conduct is policed after the fact, by penalty, because there was no way to enforce it at the moment of contact. Enforcement is slow because courts are. Each of these is a design constraint of the era that produced it, not a law of nature - and AI arrived into the finished building rather than the blueprint. Everything in this sector is AI-retrofitted, including the rules.

An **AI-born** financial system cannot be built by firms alone, and that is this argument restated rather than a separate point. If limitation is what holds lenders back, then the thing that has to be AI-born is the limitation layer - the rules, the supervision, the enforcement - not the lenders. An AI lender operating inside a corridor drawn for humans is an AI-shaped firm in a human-shaped box.

So the sequence runs opposite to how it is usually pitched. **AI-born regulation**: rules written as code a computer can run, rather than text a compliance team interprets and a supervisor later audits. **AI-born supervision**: continuous reading of what a firm actually does, which removes the reason caps have to be flat in the first place. **AI-born enforcement**: repayment built into the loan itself, such as deduction at source, rather than chased through courts afterwards - the gap that keeps abusive collection alive, closed by design rather than by conduct rules that only forbid. That is the point at which due process has to be designed in rather than assumed: exempt income, hardship suspension, error correction and a contestable route back to a human. Enforcement that is cheap and automatic is precisely the kind that must be hardest to apply wrongly.

Only on top of that does an AI-born financial industry mean anything: pricing supervised continuously instead of capped in advance, eligibility calibrated per borrower instead of fixed at 30% for everyone, conduct enforced at the moment of contact instead of fined after it. In that system limitation would respond to information - the one thing this essay says it never does.

No jurisdiction has built this. It is a design brief, not a forecast, and probably not one this decade. But it names what transformation in this sector would actually require: not better models operating inside the corridor, but an AI-born corridor, drawn for a different kind of participant. Until then the argument stands, on an assumption worth saying plainly - this holds for as long as the rules are written for humans, by humans, at the speed humans can supervise.

---

## Figures and sources

Figures current as of October 2026. Dollar conversions at about IDR 17,900 and PHP 62.6 per US dollar (early October 2026). Where a rule is on a published schedule, the schedule is given rather than a single number.

- **QRIS merchant discount rate** - Bank Indonesia, effective 15 March 2025: 0% for micro merchants up to IDR 500,000 (about $28), 0.3% above; 0.7% small/medium/large; 0.6% education; 0.4% fuel; 0% public services. From 1 October 2026, 0% for all merchant categories on transactions up to IDR 100,000 (about $6; BI press release 28/159/DKom, 17 August 2026). Uniform across providers; consumer surcharging prohibited.
- **Indonesian online lending economic benefit cap** - SEOJK 19/SEOJK.06/2025 (31 July 2025, replacing SEOJK 19/SEOJK.06/2023), implementing POJK 40/2024. Per calendar day on the funding value: consumptive 0.3% for tenors up to six months, 0.2% above; productive up to IDR 50 million (about $2,800) 0.275% up to six months, 0.1% above; productive above IDR 50 million 0.1%. Late fees capped at the same rates; economic benefit and late fees together capped at 100% of the funding value. The 2023 circular's schedule (consumptive 0.3% in 2024, 0.2% in 2025, 0.1% in 2026) was replaced from 1 January 2025 and never reached its 2026 step. OJK announced the new grid in December 2024, effective 1 January 2025, and codified it in SEOJK 19/SEOJK.06/2025.
- **Indonesian borrower eligibility and exposure** - SEOJK 19/SEOJK.06/2025: debt-service-to-income ratio for consumptive funding (principal plus economic benefit, paid to all creditors including banks, financing companies and pawnshops) at most 40% in 2025 and 30% from 2026; minimum average gross monthly income IDR 3 million (about $170); funding through no more than three platforms; per-borrower cap IDR 2 billion (about $112,000), or IDR 5 billion (about $279,000) for qualifying productive funding. Circular effective 31 July 2025; income and age requirements apply to new and renewed funding from 1 January 2026. Figures read from a certified copy of the signed circular.
- **Household debt to GDP** - end-2025: Indonesia 15.5% (BIS total credit statistics, credit to households, Q4 2025, compiled from Bank Indonesia data; Bank Indonesia does not publish the ratio itself); Malaysia 84.8% (Bank Negara Malaysia, *Financial Stability Review, Second Half 2025*); Thailand 86.7% (Bank of Thailand, *Banking Sector Quarterly Brief Q1 2026*, 19 May 2026). Note that BIS puts Malaysia at 69.8% on a narrower definition than BNM's own, and that the three national series are not measured in exactly the same way.
- **Data localisation** - Indonesia: PP 71/2019 relaxed localisation for private electronic-system operators; financial institutions remain bound by OJK and Bank Indonesia requirements to keep data centres onshore, with supervisory-access and outsourcing conditions. Vietnam: Cybersecurity Law 2025 and Decree 333 (August 2026, replacing Decree 53) require specified entities to store defined data categories domestically; the 2025 Personal Data Protection Law requires a filed impact assessment for cross-border transfers of personal data.
- **Regional scam losses** - UNODC, *An Interconnected Criminal Ecosystem: Transnational Organized Crime Threat Assessment for South-East Asia 2026* (21 July 2026): $88.3-114.1 billion in 2025 across East Asia, Southeast Asia, Australia and New Zealand; for East and Southeast Asia, about three times the $18-37 billion estimated for 2023.
- **Philippine interest ceilings** - BSP Circular 1133 (2021) and SEC Memorandum Circular 3 (2022): nominal 6%/month, effective 15%/month, penalties 5%/month, total cost 100% of principal, on unsecured general-purpose loans up to PHP 10,000 (about $160) and up to 4 months. SEC Memorandum Circular 14 (10 December 2025) recalibrated the effective ceiling to 12%/month for loans written from 1 April 2026, and enumerated circumvention schemes as violations.
- **EU comparators** - Interchange Fee Regulation (EU) 2015/751; Instant Payments Regulation (EU) 2024/886, Article 5b; Consumer Credit Directive II (EU) 2023/2225, applying from 20 November 2026.

---

*Author: Yernar Terlikbayev · [LinkedIn](https://www.linkedin.com/in/yernart) · Part of an open collection on AI in regulated finance.*

*Licence: CC BY 4.0 (prose, not code).*
