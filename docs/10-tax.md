# Tax: What to Claim, and What It's Worth

Researched 2026-08-20 against CRA, Department of Finance, Supreme Court, and gov.bc.ca primary sources. Assumes a BC general partnership, 50/50, one partner working from her Kelowna home, one partner with full-time salaried employment elsewhere, year-one revenue under $5,000. **This is research, not tax advice**. See the last section for where a CPA genuinely earns their fee.

## The short version

| Question | Answer |
|---|---|
| Does the kitchen/garage qualify for a home-office claim? | **Yes**, and there's no exclusive-use requirement |
| Can home expenses create a loss? | **No.** Capped at income, but carries forward **indefinitely** |
| Can the business loss offset Kevin's Telus salary? | **Yes, in full, the same year** |
| Do we need a T5013 partnership return? | **No.** Nowhere near the thresholds |
| Register for GST voluntarily? | **No.** You can still recover it later |
| Register for BC PST? | **Depends on your market schedule, not revenue** |
| Immediate expensing ($1.5M rule)? | **Expired.** Gone for property available for use after 2024 |
| Accelerated CCA? | **Back, and now law.** Class 8 gets 30% first year instead of 10% |
| CPP on a loss? | **None.** Only applies above $3,500 of net income |
| EI maternity benefits? | **Not on these numbers.** Needs $9,254 prior-year earnings |

---

## 1. The home workspace, bigger than people think

### The kitchen and garage both qualify

You can deduct work-space-in-home expenses if the space is **either** your principal place of business **or** used exclusively for business and regularly for meeting clients. **You qualify on the first branch, and that branch has no exclusivity requirement.** [Folio S4-F2-C2](https://www.canada.ca/en/revenue-agency/services/tax/technical-information/income-tax/income-tax-folios-index/series-4-businesses/series-4-businesses-folio-2-deducting-business-expenses/income-tax-folio-s4-f2-c2-business-use-home-expenses.html) ¶2.11 is explicit:

> "A work space need not be used exclusively for the business in order to meet the principal place of business requirement… In light of the personal use of the space, Mr. A will, however, have to apportion his expenses."

**So a kitchen you also cook dinner in, and a garage you also park in, both count.** No dedicated room needed, no customers visiting. The "exclusive use" rule everyone quotes belongs to the *other* branch of the test.

### The two-step calculation

Square footage first, then a time discount where the space is shared. Worked example on an 1,800 sq ft home:

| Space | Area share | Time factor | Business use |
|---|---|---|---|
| Garage curing area, 200 sq ft | 11.1% | 100% | **11.1%** |
| Kitchen, 150 sq ft, ~6 hrs/day | 8.3% | 25% | **2.1%** |
| | | | **13.2%** |

Against $16,600 of annual home costs (heat, power, insurance, maintenance, mortgage **interest**, property tax, water) that's **$2,191 of eligible expenses**.

Notice how much sits in the garage. **Dedicated, unshared curing space is worth far more per square foot than shared kitchen time**, because it escapes the time discount and is easier to defend. If she can give over a spare room or a partitioned garage bay to curing racks, the claim rises materially.

Deductible: heat, power, water, home insurance, property tax, **mortgage interest** (never principal), maintenance, household cleaning supplies. Renters claim rent instead. Owners **cannot** deduct notional rent for the space.

### 🟢 The trick worth real money in a loss year

Phone and internet are **not** work-space expenses (¶2.32). They go on **line 9220 as ordinary business expenses, above the loss restriction**, so they *can* create or increase a deductible loss. Home heat and mortgage interest sit on line 9945 *below* it and cannot.

Same house, opposite treatment. Push everything legitimately classifiable as a non-work-space expense above the line.

### The cap, and the carry-forward

Home expenses cannot create or increase a business loss. The excess isn't lost: it carries forward **indefinitely**, must be used in the earliest year with income to absorb it, and can only be applied against **the same business**. If the soap partnership winds up and something else starts in the same house, the pool dies with it.

⚠️ **Nobody tracks this for you.** It doesn't appear on a notice of assessment like a non-capital loss does. It exists only on line 7L of next year's T2125. Keep a running note or it's silently lost.

### 🔴 Don't claim CCA on the house

Technically allowed. Almost always a mistake. CRA's practice is not to trigger capital gains on the business portion of a principal residence provided the use is ancillary, there's no structural change, **and no CCA is claimed**. Claiming CCA breaks that third condition and converts part of a tax-free principal residence into taxable property. Leave line 7K at zero.

---

## 2. The partnership mechanics

- **The partnership files nothing and pays no tax.** Each partner files their own T2125 carrying the partnership totals, and takes their share.
- **No T5013 required**: that needs revenue+expenses over $2M or assets over $5M. Complete **Part 8 of T2125** ("Details of other partners") instead.
- **She alone claims the home expenses**, on her own T2125. The Part 7 cap is tested against *her* share of income, not the partnership's.
- **Partner-level costs go in Part 6 → line 9943**: notably her own car's mileage, which is deducted *before* the home-expense cap is tested.
- **One shared CCA schedule**, reproduced identically on both T2125s. Partners can't claim CCA separately on partnership property.
- **Money either of you takes out is a drawing, not an expense.** Salaries to partners are explicitly non-deductible.
- **Deadlines:** balance owing due **April 30, 2027**; filing deadline **June 15, 2027** for self-employed and their spouse.

---

## 3. 🟢 Kevin's salary offset, confirmed

**A current-year business loss is deducted against employment income in the same year**, under ITA s.3(d). It does *not* go through the loss-carryback system. It lands on **line 13500** as a negative amount. No election, no form, no waiting.

At an $85,000 salary, the BC combined marginal rate is **28.2%**, so **every $100 of loss allocated to Kevin is worth about $28 in his pocket**. With a full-time salary absorbing it, the loss is fully consumed in-year, so there'll typically be nothing left to carry back and no T1A to file.

**No at-risk restriction applies.** Those rules only bite limited partners, and BC's Partnership Act s.11 gives general partners unlimited liability, so the restriction isn't engaged.

### The hobby-vs-business test, and how to win it

The old "reasonable expectation of profit" test **was struck down** by the Supreme Court in [*Stewart v. Canada*, 2002 SCC 46](https://decisions.scc-csc.ca/scc-csc/scc-csc/en/item/1986/index.do) as a standalone basis for denying losses. **Losing money is not evidence that you aren't in business.**

But CRA's [Income Tax Audit Manual, Ch. 27](https://www.canada.ca/en/revenue-agency/services/tax/technical-information/income-tax-audit-manual-domestic-compliance-programs-branch-dcpb-27.html) lists personal-element indicators, and a home craft business hits several: a hobby that became a business, customers who are mostly friends and neighbours, no scheduled hours, prices below market, and operating from a personal residence. That's not fatal. The standard is whether *"the personal element so overshadows any element of commerciality as to substantially displace it."* But it means building the file.

**The commerciality file, in rough order of value:**
1. **A separate business bank account.** Cheapest, strongest single rebuttal.
2. **Regulatory compliance**: business licence, Health Canada notification, INCI labelling, product liability insurance. **Nobody does this for a hobby.** The strongest commerciality badge available to a soap maker, and you're doing it anyway.
3. **A written costing and pricing sheet** showing cost-plus-margin, and evidence you raised prices when oil costs rose. **Pricing below market for friends is the single most damaging fact you can create.**
4. Arm's-length customers: markets, Etsy, wholesale. A customer list of relatives is a red flag in CRA's own words.
5. Dated marketing, a business plan with a path to profit, logged production hours, training and courses.
6. **Document why year one lost money**: equipment, the 4-6 week cure forcing an inventory build, booth fees. CRA expressly discounts losses with identifiable startup causes.

The real risk isn't year one. It's year five with flat sub-$5,000 revenue and a fifth straight loss.

---

## 4. Expenses, and three traps

Deductible on the usual lines: raw materials (through cost of goods sold), packaging, advertising, product liability insurance, business licence, accounting fees, market and booth fees, Etsy and payment processing fees, website and domain, postage, office supplies, and the business portion of phone and internet.

### 🔴 Trap 1: inventory is not an expense until sold

Soap cures 4-6 weeks. At December 31 you'll hold finished bars, curing bars, and raw oils. **All of it is inventory.** You must do a **physical count at year end** and value it at the lower of cost and fair market value.

This is the main reason a small soap business can show a *profit* in year one while feeling like it lost money: you spent $1,750 on materials but $650 is sitting on a curing rack, so cost of goods sold is $1,100, not $1,750. Your own labour is never capitalizable.

### 🔴 Trap 2: there is no per-kilometre method

The CRA per-km rates are for **employers reimbursing employees**. A self-employed person deducts **actual costs × business km ÷ total km**, with receipts. Year one needs a **full logbook**, date, destination, purpose, kilometres, plus odometer readings at the start and end of the period. Only from year two can you use a three-month sample.

Parking at a market is separately deductible in full and isn't subject to the business-use ratio.

### 🔴 Trap 3: your own lunch at a market is 0% deductible

Not 50%, zero. Meals become 50% deductible when they're genuinely with a customer, supplier or business contact, or while travelling away on business. Record who was present and why on every receipt. A large meals claim relative to sales also cuts against the commerciality story.

### Startup costs: fix the date

Canada has **no US-style $5,000 startup-cost election**. A cost is currently deductible, capital, or incurred before the business began, in which case it isn't deductible at all. CRA treats **the first purchase of goods for resale or equipment as the start date**; exploratory research beforehand is not deductible.

**Write a one-page memo fixing the start date**, using the earliest of the partnership agreement, BC Registries registration, business bank account, licence, and first supplier invoice.

---

## 5. Equipment write-offs, better than they've been in years

### 🟢 Accelerated CCA is back and is now law

Immediate expensing (the $1.5M rule) **expired** for property available for use after 2024. But the Accelerated Investment Incentive was reinstated by **Bill C-15, royal assent March 26, 2026**. Property acquired after 2024 and available for use before 2034 gets a first-year uplift and **escapes the half-year rule**.

For a $600 Class 8 equipment set bought and used in 2026:
- Base = $600 + ($600 × ½) = $900 → CCA = 20% × $900 = **$180**
- Versus $60 under the old half-year rule. **Three times the deduction.**

A **laptop or POS system gets 100% in year one**, but note the cliff: it must be available for use **before January 1, 2027**.

⚠️ CRA's own Accelerated Investment Incentive web page is **stale** and still shows the superseded phase-out. Cite T4002 Chapter 4 and Bill C-15 instead.

### 🟢 The $500 tool test is per tool, not per invoice

Tools under $500 each fall in **Class 12 at 100%** with no half-year rule, effectively expensed. So:
- A single integrated $600 machine → Class 8 at 20%.
- A $600 order of a $180 stick blender, a $220 mould and a $200 curing rack → **three tools, each under $500, all 100% in year one.**

**Itemize your invoices.** A supplier's bundled "starter kit" line item can cost you the Class 12 treatment that the same goods listed separately would keep.

One quirk: **moulds are a named exception**. Class 12 but still subject to the half-year rule, so 50% in year one. Blenders and pots aren't.

### 🟢 CCA is optional, and it *can* create a loss

The rule that CCA can't create a loss is a **rental-property rule only**. There's no equivalent for ordinary business property. So claiming CCA can deepen the loss that offsets Kevin's salary.

That makes it a genuine planning lever: claim heavily in 2026 to maximize the offset at 28.2% today, or claim zero, preserve the undepreciated balance, and use it in a later, higher-rate year. Nothing is lost by deferring. Worth modelling once.

Note a **short first fiscal period prorates the claim**, starting mid-year shrinks it proportionally.

---

## 6. GST: don't register

The threshold is **$30,000** over four consecutive quarters, measured for **the partnership as a whole**, not per partner. Below it you're a small supplier.

**Voluntary registration is a bad trade for a B2C business.** Your customers can't recover the tax, so you either charge 5% more or absorb it. On ~$4,200 of sales you'd remit ~$210 against maybe $150-180 of input credits, **worse off, plus the compliance burden**, plus a one-year lock-in and a clawback on deregistration.

### 🟢 The fact that removes the urgency

**When you eventually cross $30,000, you can claim input credits on the inventory and capital property you already own at that moment.** CRA's new-registrant rule treats you as having paid GST equal to the "basic tax content" of what's on hand. So waiting costs you nothing on inventory.

**Keep every GST receipt anyway**, unrecovered GST is a deductible expense, and you'll need it for that calculation later.

Registering *does* make sense if you go mostly wholesale, export heavily, or make a large capital outlay.

### Etsy already handles it

Under the marketplace rules, Etsy collects and remits GST on your Canadian Etsy sales **because you're unregistered**. Registering would stop that and make it your job. Sales through your own site are always yours to handle.

---

## 7. PST: the schedule decides, not the revenue

Covered in detail in [01-business-setup.md](01-business-setup.md). The short version:

**Four or more market days in twelve months ends small-seller status even at $2,000 of revenue**, because a rented market stall counts as "established commercial premises." A home workshop with no customers visiting, and online sales, do **not** count.

**The asymmetry with GST is the important part:**

| | GST | BC PST |
|---|---|---|
| Recover tax on inputs later? | **Yes**, new-registrant rule | **Never.** Permanently forfeited |
| Recover tax on equipment? | Yes, if registered | **Never**, registered or not |
| Verdict | **Wait**, costs nothing | **Register if you'll do 4+ markets** |

With GST, waiting is free. With PST, waiting **permanently forfeits** the input tax on every batch of oils, lye, packaging and labels you buy in the meantime. If you're going to be at markets regularly, register early and **start giving suppliers your PST number**. That exemption is the only one BC PST ever offers.

Two things to watch: PST on **equipment** is never recoverable (moulds, scales, blenders, safety gear all cost 7% permanently), and you must **self-assess PST on taxable goods bought outside BC** using form FIN 405 by the last day of the following month.

---

## 8. CPP and EI

**CPP: nothing owed in year one.** Contributions apply only to net self-employment income above $3,500, and a loss produces none. But plan for it: the 2026 self-employed rate is **11.90%** (both halves), so at a $20,000 share that's **$1,963** landing as a lump sum on April 30 with nobody withholding it. Half the base contribution is a deduction, half a credit, and the enhanced portions are fully deductible.

**EI special benefits. She won't qualify, and the lock-in is severe.** Self-employed people can opt into maternity, parental, sickness and caregiving benefits only. But it requires **$9,254 of net self-employed earnings in the prior calendar year** plus an agreement in place **12+ months** before claiming. On a 50% share of sub-$5,000 revenue, that's not close. Realistically it's two-plus years of lead time.

🔴 **And once you receive any benefit, you can never withdraw**, premiums become payable on all future self-employment income for life. You can withdraw penalty-free **within 60 days** of signing, never after receiving a benefit.

⚠️ **If maternity coverage is a real goal, check whether she qualifies through regular employment instead.** If she has or can get an insurable job, that's very likely the better route, and it needs no self-employed agreement at all. Get this checked *before* signing anything.

---

## 9. Records

**Six years** from the end of the last tax year they relate to, so 2026 records until the end of 2032. Must be kept **in Canada**; CRA's position is that books living only in a US-hosted cloud service are **not** kept in Canada, so keep a Canadian backup.

🔴 **Download and archive your Etsy, Square and Stripe reports yourself every year.** CRA holds *you* responsible for platform transaction records, and platforms don't keep them for six years.

Four buckets from day one: **sales by channel** (reconciled monthly to deposits), **purchases** (photograph thermal receipts the day they arrive. They fade), **the mileage log**, and **the home expense file**.

That last one should include a **one-page memo written now**: measured workspace square footage, total finished home area, the hours-per-day basis for shared space, and a floor sketch, dated. Reconstructing that four years later under audit is painful; a contemporaneous memo is close to unimpeachable.

Keep permanently: partnership agreement, registration, licence, business plan, costing sheets, cosmetic notifications, and the CCA schedule with undepreciated balances by class.

---

## 10. Year one, illustrated

On $4,200 of sales with $1,100 cost of goods sold, $2,230 of expenses and $700 of CCA, net income is **$170**, so **$85 each**.

Her home-expense pool of $2,191 is capped at her $85 share. She claims **$85** and **carries $2,106 forward** to 2027.

**If sales had been $3,100 instead**, the partnership loses $900:
- Her whole $2,191 home pool carries forward, untouched.
- **Kevin deducts $450 against his Telus salary, saving about $127 in tax.**
- Neither partner owes CPP or EI.

**The lesson:** the home-expense pool is nearly worthless in year one either way, but it's *preserved*, not lost, and pays off in the first profitable year. The deductions that produce real cash value now are the ones **above** the line. CCA, phone and internet, and everything on line 9270.

---

## 11. Where a CPA genuinely earns their fee

1. 🔴 **How the home-office deduction is claimed in a partnership.** The T2125 wording assumes a partnership-level expense, not one partner's own home. The standard treatment is what's described here, but get it confirmed and papered, and put a clause in the partnership agreement stating she provides the workspace at her own unreimbursed cost.
2. 🔴 **Whether soap equipment is Class 43 manufacturing machinery** (100% first year) rather than Class 8 (30%). Real characterization question, material money.
3. 🔴 **The EI decision**, if maternity coverage matters. Largely irreversible.
4. 🟠 **Whether Etsy's marketplace-facilitated sales count toward your $30,000 GST threshold.** Matters more as revenue grows.
5. 🟠 **Which specific market venues count as "established commercial premises"** for PST. The BC Consumer Taxation Branch answers this free: **1-877-388-4440**.
6. 🟠 **Whether to claim or defer CCA** in 2026. Worth modelling once, properly.

**Free help before you pay anyone:** the [CRA Liaison Officer service](https://www.canada.ca/en/revenue-agency/services/tax/businesses/programs/about-canada-revenue-agency-cra/compliance/liaison-officer-initiative-loi.html) walks through available deductions and bookkeeping setup, is confidential, and is explicitly not an audit. See [08-grants-and-programs.md](08-grants-and-programs.md).
