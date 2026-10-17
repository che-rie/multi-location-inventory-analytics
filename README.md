# multi-location-inventory-analytics
Excel-based inventory allocation, shortage analysis, and purchasing decision-support system

# Multi-Location Inventory Allocation & Purchasing Intelligence System

## Project Overview

Developed an Excel-based inventory allocation and purchasing decision-support prototype to analyze customer orders, monitor inventory availability across multiple locations, evaluate fulfillment options, and identify purchasing requirements.

## Business Objectives

- Determine available-to-promise inventory across locations.
- Recommend stock allocation without exceeding available inventory or customer demand.
- Validate product matching and expected delivery deadlines.
- Identify unfulfilled customer demand.
- Evaluate incoming purchase orders, shipments, and supplier lead times.
- Present inventory and purchasing insights through a dynamic dashboard.

## Tools and Techniques

**Microsoft Excel:** XLOOKUP, SUMIFS, COUNTIFS, IF, MIN, MAX, structured references, Excel Tables, conditional calculations, and charts.

**Analytical techniques:** Inventory availability analysis, order fulfillment planning, reservation tracking, shortage analysis, supplier comparison, and scenario testing.

## Key Results

| Metric | Result |
|---|---:|
| Confirmed customer demand | 150 units |
| New allocation proposals | 108 units |
| Unfulfilled demand | 32 units |
| Provisional coverage | 78.67% |

### Product-Level Analysis

| Product | Proposed supply | Shortage |
|---|---:|---:|
| SKU-A | 60 | 30 |
| SKU-B | 30 | 0 |
| SKU-C | 18 | 2 |

## Key Findings

SKU-A represented 30 of the 32 outstanding units, making it the main product requiring further supply investigation.

The allocation model checked stock availability, customer demand, product compatibility, and estimated delivery deadlines before generating proposed quantities.

Supplier analysis compared replenishment lead times and identified potential alternatives for purchasing review.

## Project Workflow

1. Organized sales, inventory, reservation, and supplier records.
2. Calculated available inventory and flagged records requiring review.
3. Identified confirmed customer orders and outstanding quantities.
4. Generated multi-location allocation proposals.
5. Checked proposed allocations against stock, product, and delivery constraints.
6. Calculated product shortages.
7. Reviewed incoming supply and supplier lead times.
8. Developed a dynamic Excel dashboard for reporting.

## Files

- Excel workbook containing the calculations and dashboard.
- PDF case study explaining the methodology and findings.
- Screenshots showing allocation and purchasing results.

## Scope and Limitations

This independent case study uses constructed business data. Allocation outputs are planning recommendations rather than completed shipments. Delivery calculations rely on simplified transit assumptions, and a historical reservation/allocation discrepancy remains documented for review.
