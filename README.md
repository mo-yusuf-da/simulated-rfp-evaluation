# Simulated RFP Evaluation: Off-Road Haul Truck Tires

> **This is a simulated exercise.** The suppliers, prices, and performance figures are invented for portfolio demonstration. They are not real companies or market data, and they are not connected to any employer.

A sourcing-evaluation exercise that walks through a competitive RFP from criteria to award recommendation, built in Excel with live formulas.

## What is in this repo
| File | Contents |
| --- | --- |
| `Simulated_RFP_Evaluation_HaulTruckTires.xlsx` | Workbook: assumptions, weighted criteria, bidder pricing template, invented bids, 5-year TCO model, scoring, sensitivity analysis, recommendation |
| `Simulated_RFP_Evaluation_HaulTruckTires.pdf` | Print of every workbook tab, for viewing in the browser (GitHub does not preview Excel files) |
| `RFP_Simulated_HaulTruckTires.md` | The RFP document issued to the three fictional bidders |

## Scenario
A fictional aggregates producer is sourcing tires for a 40-truck haul fleet under a 5-year agreement. Three fictional suppliers bid: Northfield Tire, Summit Tread, and Prairie Rubber.

## Method
1. **Criteria and weights:** total cost of ownership 40%, technical performance 20%, delivery and service 15%, supplier risk and compliance 10%, commercial terms 10%, sustainability and safety 5%.
2. **Pricing template:** a standard format so bids are comparable.
3. **TCO model:** purchase cost with price escalation, freight, support fees, downtime cost from premature failures, warranty credits, and the working-capital benefit of payment terms, discounted to NPV.
4. **Scoring:** TCO score is formula-driven (5 x lowest NPV / bidder NPV). Other criteria are evaluator scores from 1 to 5 with written rationale.
5. **Sensitivity:** the award decision is re-tested under four weighting scenarios.

## Result (on the invented inputs)
- The lowest unit-price bidder (Prairie Rubber) has the highest 5-year NPV cost, about $427K (15.2%) more than the lowest-cost bidder, because shorter tire life and more early failures drive replacement and downtime costs.
- The highest unit-price bidder (Summit Tread) has the lowest 5-year NPV cost and the top weighted score, and wins in all four sensitivity scenarios.
- Recommended negotiation levers: longer payment terms, a written escalation cap, a lead-time service level, faster warranty-credit payment, and a freight rate at or below the competing bids.

The outcome follows from the inputs I chose. The point of the exercise is the method: comparing bids on TCO rather than unit price, and testing whether the decision is robust.

## Limitations
Tire life and failure rates are treated as supplier-reported and unverified. Annual tire demand is modeled as a steady average. A real evaluation would verify claims through references, site trials, and warranty-claim history.

## How to use
Open the workbook. Blue cells are inputs, black cells are formulas, and green cells link to other sheets. Change any blue input (for example a bid price or a criterion weight) and all results recalculate.
