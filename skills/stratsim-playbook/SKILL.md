---
name: stratsim-playbook
description: Decision coach for StratSim Management (Interpretive Simulations), the multi-round auto-industry business simulation. Use when someone is playing StratSim or StratSimManagement and wants to review last year's results, plan a decision round (product development, ISSQ technology, pricing, marketing, dealers, production and capacity, financing), read Focus Group, Microsegment, Concept Test, Test Market or Pro-Forma reports, check a decision before submitting, plan the final year, or prepare a BoD presentation. Also covers Chinese requests such as StratSim 决策, 排产, 定价, 研发中心, 战略模拟.
---

# StratSim playbook

Coach the user through StratSim Management decisions with a closed loop: every round, compare last year's predictions with the actual results, then decide, stress-test, and write down new predictions to check next round.

The rules of thumb below come from one team's full run: 4 practice years plus 6 competition rounds in a 7-firm industry. That team finished first (weighted score 98.2 vs 82.3 for second, cumulative net income $74.6B, final market value $179.5B). Treat every number here as a reference point from one industry. The user's own reports override it. This is an unofficial student write-up; remind the user to follow their course's rules on outside help.

Reply in the user's language. Mark anything you infer rather than read from a report as [inference].

## Start of every session

Find out where the user is before giving advice:

1. Which round they are deciding, how many rounds are left, and how their course scores the game. The source team's course scored cumulative net income 50% plus final market value 50%.
2. Their firm's vehicles, segments, capacity, cash and debt.
3. Last year's reports. Ask the user to paste or screenshot:
   - Dashboard, Income Statement, Product Contribution
   - Company / Manufacturing results, including the shortage or inventory comment for each vehicle
   - Focus Group and Microsegment reports for every segment they target
   - Economic Outlook and Industry News
   - Competition / Financial Summary
4. What they predicted last round, if they wrote it down.

For a narrow question (one price, one report), answer it directly, then point to the step of the loop it belongs to.

## The loop for one decision round

1. **Review.** Build a table: item, how it was predicted, predicted, actual, why. Cover net income, each vehicle's sales vs schedule, industry size, preference and stock price.
2. **Diagnose.**
   - Shortages: the Manufacturing comment says "shortage <10%", "10-30%" or ">30%".
   - Inventory days above about 30.
   - Focus Group ratings: size "too small" or "too big", price "worst", hot buttons only "avg".
   - Competitors' launches announced in Industry News, which usually reach the market the next year.
   - The economy, interest rates and fuel price.
3. **Research and test.**
   - Buy Microsegment and Focus Group reports for every target segment.
   - Use Concept Tests to screen configurations and launch prices for new or upgraded vehicles.
   - Use Test Market to set price and marketing for vehicles already on sale.
   - Each tool allows about 10 runs per round, so keep one or two for the final combination.
4. **Decide in this order:**
   1. product development
   2. technology
   3. price and marketing
   4. dealers
   5. production and capacity
   6. financing

   Each step depends on the ones before it.
5. **Stress-test.** Read the Pro-Forma at 100%, 90% and 80% of planned sales. Cash must stay positive in the 80% case, or the system forces a short-term loan. Check every decision against the rules below.
6. **Commit and record.** For each decision write the expected result and the number to check next round. Draft the decision rationale from the evidence.

## Rules of thumb (each holds only under its condition)

### Product development
- Fix size first. A vehicle rated "too small" or "too big" will not sell however good its other attributes are. In the source industry, a family car moved from size 28 to 40 and likely-to-buy rose from 14.2% to 24.3%.
- **Major vs minor vs cost reduction.** Pick a major when the vehicle needs a new size or class fit. Pick a minor when hot buttons need to reach "best". Pick a cost reduction when attributes are already best and there is inventory: an upgrade writes off the old inventory, while a cost reduction does not.
- Keep the segment's hot buttons ahead of rivals every year.
- **New vehicles.**
  - Rank them by unit margin, roughly MSRP × 0.88 − base cost, and by overlap with your own high-margin cars. Do not rank them by likely-to-buy: several segments with high likely-to-buy barely made money.
  - Enter segments or classes nobody serves well. In the source industry, a Utility, a 4F family car and a Sports car all led their segments in their first year.
- **Timing and capacity limits.**
  - A vehicle in an existing class takes 2 years; a new class takes 3. Anything started too late never launches before the game ends.
  - You can open only one new development center per year, so start early.
  - Give every center a project every year.

### Technology
- Buy a level only when a specific project in the next year or two needs it. Check the saving against the cost over the rounds left.

### Price
- **Test Market sets prices.** Concept Test exaggerates price sensitivity.
  - Test Market can only move price within ±10% of the baseline.
  - It underestimates demand for vehicles that were short or were just upgraded.
- **A vehicle that is short can take a 5-10% price rise** with almost no loss of share. Repeat while it stays short.
- **A price cut pays only in some cases:** after a downturn, when the price is rated "worst" and rivals are cheaper. In the source industry, a truck cut from $27K to $25K tested +$322M of contribution and sold out. A price cut on a vehicle that is short only loses money.

### Marketing
- Spend about 2-2.5% of revenue.
- Firm preference rises with launches and upgrades. Raising marketing alone to 2.5% of revenue did not lift preference.
- Do not add advertising to vehicles that are short. Advertising does not rescue a vehicle whose price is "worst" and whose hot buttons are only "avg"; fix the product first.

### Dealers
- You can add at most about 10% of established dealers per year, and new dealers open the following year.
- Training raised the dealer rating, which is a market-value driver in the source course.

### Production and capacity
- **Schedule = Test Market share × a realistic industry size.** Realistic was about 75-77% of the system's industry forecast in the source competition. Then adjust:
  - Upgrade year: add about 2.5 share points and leave spare capacity.
  - First year of a new vehicle: schedule 85-90% of estimated demand.
  - A vehicle that was short: Test Market underestimates it, so schedule more.
  - A vehicle that will be upgraded next year: schedule less this year.
  - A price cut: scale the schedule by the Test Market share change.
- Give scarce capacity to the vehicles with the highest unit contribution that were short. Overflow given to low-margin vehicles turned into inventory while the best cars ran short.
- **Expand capacity a year ahead**, at most about +50% per year. Capacity cost about $700 per unit once. Running over capacity cost about $2,000-3,500 per unit every year. Keep utilization at or below about 110%.
- **Flex adds up to about 10% when demand exceeds the schedule. It never cuts production**, which was confirmed twice. Do not rely on it to prevent inventory.

### Financing
- **Early rounds.**
  - If the firm starts with expensive short-term debt, issue stock up to the cap (20% of market value in the source game) to retire it.
  - Avoid large bonds.
  - Debt-free firms get the best rating.
- **When cash is high.** Buy the 1-year CD, which is capped at $10B.
- **Dividends.** They are not on the source course's list of market-value drivers. Dividends of $2 and $5 a share did not hold back the stock, which rose 20.6% and 31.8%.

## Final round

- Skip anything that only pays back after the game: new capacity, new dealers and most technology.
- Give every development center a project that launches this year, such as a minor upgrade or a cost reduction.
- **Schedule production to 100% of capacity with Flex on.**
  - Unsold cars go into inventory at cost, so net income barely moves. The source team confirmed this in the Pro-Forma before submitting.
  - Do not schedule above 100%. The over-capacity charge applies whether or not the cars sell: $401M at 105% and $843M at 110% in the source game. Flex covers real extra demand up to about 110%.
- **Allocate capacity by the midpoint of each vehicle's demand range,** highest unit contribution first. The source team scheduled its Utility at the top of its range and was left with 146K units. Meanwhile three other vehicles, including a price-cut truck, ran short.
- **Test downside cases in the Pro-Forma.** Its Unit Forecasts are the marketing page's projected units, and the Pro-Forma only recalculates after Save. Save lower sales forecasts, read net income, cash and inventory, then restore the forecasts.

## How far to trust system numbers

| Number | Trust | Note |
|---|---|---|
| Industry sales forecast | Low | Actual ran 75-77% of the forecast in competition and 76-85% in practice |
| Test Market share | High | Usually within 0.4 points; actual runs higher when the whole industry is short |
| Concept Test likely-to-buy | Screening only | Overstates price sensitivity |
| Pro-Forma net income | Depends on your forecast | It assumes the forecast units sell |
| Segment preferences | Drift yearly | Re-read Microsegment before every major or minor upgrade |

## Output for a decision round

1. Review table: predicted vs actual and why.
2. Decision table by area, with the evidence for each line, such as a test result, a report rating or a rule above.
3. Risk check: Pro-Forma at 100%, 90% and 80% of planned sales, and the lowest cash.
4. Three to seven predictions to check next round.

## Going deeper

The full guide is in Chinese, but its tables and numbers can be read without it. When this skill is installed as the `stratsim` plugin, the guide is two folders up from this file. Otherwise, read it on GitHub at https://github.com/MrGreyBear/stratsim-playbook.

- [Rules, scoring and hard limits](../../docs/01_规则与评分.md)
- [The closed loop with checklists](../../docs/02_闭环决策流程.md)
- [Playbook by decision area](../../docs/03_各板块打法.md)
- [Lessons with conditions and evidence](../../docs/04_经验清单.md)
- [Year-by-year case of the winning firm](../../docs/05_正式比赛逐年复盘.md)
- [Practice rounds vs the competition](../../docs/06_练习轮vs正式比赛.md)
- [BoD assignment tips](../../docs/07_BoD作业经验.md)
