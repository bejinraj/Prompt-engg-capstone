# Input Prompt:

Act as a Financial Analyst.

Create a weighted decision matrix comparing Salesforce, HubSpot, and Zoho.

Criteria:

- TCO Cost Model: 30%
- Customization & Scale: 20%
- Setup Speed: 25%
- User Adoption Ease: 25%

Assign each vendor a raw score from 1 to 10.

Calculate:

Weighted Score = Raw Score x Weight

Show the calculation for every criterion and vendor.

Verify that all weights total exactly 100%.

Return the result as a Markdown table.

# Chat-GPT Output 1:

| Criterion                 |   Weight | Salesforce Raw | Salesforce Calculation | Salesforce Weighted | HubSpot Raw | HubSpot Calculation | HubSpot Weighted | Zoho Raw | Zoho Calculation | Zoho Weighted |
| ------------------------- | -------: | -------------: | ---------------------: | ------------------: | ----------: | ------------------: | ---------------: | -------: | ---------------: | ------------: |
| **TCO Cost Model**        |      30% |              5 |               5 × 0.30 |            **1.50** |           7 |            7 × 0.30 |         **2.10** |        9 |         9 × 0.30 |      **2.70** |
| **Customization & Scale** |      20% |              9 |               9 × 0.20 |            **1.80** |           8 |            8 × 0.20 |         **1.60** |        7 |         7 × 0.20 |      **1.40** |
| **Setup Speed**           |      25% |              5 |               5 × 0.25 |            **1.25** |           8 |            8 × 0.25 |         **2.00** |        9 |         9 × 0.25 |      **2.25** |
| **User Adoption Ease**    |      25% |              6 |               6 × 0.25 |            **1.50** |           9 |            9 × 0.25 |         **2.25** |        8 |         8 × 0.25 |      **2.00** |
| **Total**                 | **100%** |                |                        |       **6.05 / 10** |             |                     |    **7.95 / 10** |          |                  | **8.35 / 10** |

**Weight verification:** 30% + 20% + 25% + 25% = **100%** ✓

**Raw-score basis:** These 1–10 scores are analyst assumptions for the requested decision matrix, not independently verified vendor ratings. Current vendor pricing/features can change; for example, Salesforce and HubSpot publish current pricing, while Zoho publishes comparative pricing information. :chatgpt-content-reference{index="0"}

# Chat-GPT Output 2:

| Rank | Vendor         | Total Weighted Score | Score (%) |
| ---: | -------------- | -------------------: | --------: |
|    1 | **Zoho**       |        **8.35 / 10** | **83.5%** |
|    2 | **HubSpot**    |        **7.95 / 10** | **79.5%** |
|    3 | **Salesforce** |        **6.05 / 10** | **60.5%** |

**Weightage total: 100%** ✓

These rankings are based on the raw scores and weights assigned in the decision matrix above.
