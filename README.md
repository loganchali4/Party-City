# Party-City
January 2026 | Estimating Comparable Sales and Evaluating Store Footprint

View interactive web notebook [HERE](https://deepnote.com/workspace/Logans-Python-Workspace-4499e17c-38f8-4e22-9fd9-bb4212d29105/project/Party-City-d9e136f6-61ec-429e-ac19-8696445300f6/notebook/260112partycity-b9992bf07b4943b0b70122a966fd9e9e?utm_source=share-modal&utm_medium=product-shared-content&utm_campaign=notebook&utm_content=d9e136f6-61ec-429e-ac19-8696445300f6)

---

## 1. Q4 2022 Comparable Sales Outlook

Using the transaction sample (~1% panel) and a “comparable store” filter (stores open for the full Q4’21 through Q4’22 comparison window), the sample-derived YoY signal tracks the reported series reasonably well historically.

Based on that relationship, I use the sample signal as a proxy for Q4’22 performance and estimate ~−9.9% YoY for Party City’s Brand Comparable Sales in Q4’22.

<img width="928" height="525" alt="image" src="https://github.com/user-attachments/assets/3561300a-218c-42b6-b949-6e01bef499e3" />

---

## 2. Location Score Rankings

Because the transaction location IDs and web-scraped location IDs don’t always join, I treat store-level sales as a “nice-to-have” input rather than something I force into the web dataset. Where a sales signal exists, I incorporate it cautiously, otherwise, the analysis is driven by web/location attributes.

I rank stores with a simple, interpretable 0-1 score (equal weights across all factors):

- Flagship status  
- Number of services  
- Local redundancy (stores in same city/state)  
- TTM sales where available (with missing sales filled using the average)

The lowest-ranked stores are the most plausible closure candidates under a footprint rationalization plan. One pattern that stood out is that a disproportionate share of the bottom-scoring locations are in Texas, especially around San Antonio (and some Austin), suggesting possible market saturation/overlap there.

---

## 3. Strategic and Secular Considerations

Party City operates in a highly seasonal and discretionary retail category, which creates both opportunity and risk. On the positive side, the company has strong brand recognition and covers a wide range of life events and holidays, which drives recurring demand and makes it a familiar destination for consumers planning celebrations.

At the same time, several structural challenges stand out. Demand is highly cyclical, making the business sensitive to economic slowdowns and inventory missteps. The large brick-and-mortar footprint, which historically supported convenience, has become harder to justify as consumers increasingly shift online and toward big-box or general-merchandise retailers. Party supplies are also largely commoditized, limiting pricing power and making customer loyalty difficult to sustain.

Overall, Party City’s brand and category breadth remain valuable, but long-term success likely depends on a smaller, more productive store footprint, tighter execution around seasonality, and a stronger online presence that better aligns with current consumer behavior.
