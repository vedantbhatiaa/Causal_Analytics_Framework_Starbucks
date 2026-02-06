# Starbucks UK Market Strategy Proposal

## Project Overview

This repository contains a comprehensive business strategy analysis and proposal for Starbucks' UK market operations. The project combines data-driven insights from 10,000 customer reviews with market research to identify strategic opportunities and propose actionable recommendations for improving Starbucks' competitive position in the UK coffee shop market.
 
**Academic Context:** Business Strategy and Analytics

## Executive Summary

Starbucks UK faces increasing competitive pressure from local brands (Costa Coffee, Greggs, Pret A Manger) that offer better value pricing and faster service. Our analysis reveals three critical challenges:

1. **Price Perception:** Negative sentiment (-0.20) on pricing indicates customers view Starbucks as too expensive
2. **Service Inconsistency:** Staff interactions show mixed sentiment (-0.10), with LDA analysis highlighting recurring complaints about rude service
3. **Limited Localization:** The Americanized experience doesn't fully align with UK café culture preferences

![Market Revenue](images/market_revenue.jpg)

### Proposed Strategy

We recommend a three-pillar approach:

1. **Pricing Reform:** Regional pricing, value-tier options, and enhanced loyalty bundles
2. **Localization:** UK-inspired menu items, store redesigns for hybrid work, and partnerships with local cafés
3. **Service Enhancement:** Improved training, staff engagement incentives, and greater store-level autonomy

## Data & Methodology

### Data Collection

- **Source:** Google Maps reviews via exportcomments.com
- **Scope:** 100 Starbucks stores across 10 most populated UK cities
- **Sampling:** Proportional random sampling (e.g., London = 63% of stores, allocated 63 locations)
- **Volume:** 10,000 reviews (100 reviews × 100 stores)
- **Time Period:** 2022-2025
- **Variables:** Star rating, review text, date, city, location, ownership type

  ![Monthly Ratings](images/monthly_ratings.jpg)

### Analytical Techniques

1. **Sentiment Analysis:** 
   - Computed polarity scores (-1 to +1) across five dimensions: price, staff, quality, speed, ambience
   - Used NLP to quantify emotional responses
     
2. **Regression Analysis:**
   - Compared London vs. non-London store performance
   - Key finding: London stores rate 0.26 stars lower (p < 0.001)

3. **Topic Modeling (LDA):**
   - Identified recurring themes in customer feedback
   - Revealed staff behavior as primary complaint driver

4. **Market Analysis:**
   - Competitor pricing comparison (Costa, Pret, Greggs, Black Sheep)
   - Store footprint analysis (2021-2025)
   - Revenue forecasting through 2030
     
![Sentiment Analysis](images/sentiment_analysis.jpg)
## Key Findings

### Customer Sentiment by Dimension

| Dimension | Avg. Sentiment | Interpretation |
|-----------|----------------|----------------|
| **Price** | -0.20 | Most negative - customers find Starbucks too expensive |
| **Staff** | -0.10 | Inconsistent service quality |
| **Quality** | +0.03 | Slightly positive - good but not premium |
| **Speed** | +0.10 | Positive - efficient service during peak hours |
| **Ambience** | +0.12 | Most positive - comfortable "third place" experience |

### Geographic Performance Gap

- **Non-London stores:** 3.96 average rating
- **London stores:** 3.70 average rating (-0.26 stars)
- **Implication:** London is ideal test market for service improvements

### Competitive Position

- **Store Count:** Starbucks (1,356) vs. Costa (2,671) vs. Greggs (2,610)
- **Pricing:** Starbucks £1.95 entry / £4.11 avg vs. Greggs £1.40 entry / £1.80 avg (30% cheaper)
- **Market Growth:** UK coffee market projected to reach £5.56B by 2030

![Stores per Company](images/stores_per_company.jpg)

### LDA Topic Analysis

**Customer Service Complaints**
- Top keywords: staff, rude, manager, attitude, unfriendly, experience, service
- Indicates systematic rather than isolated issues


## Risk Assessment & Mitigation

### Risk 1: Competitor Price Wars
- **Risk:** Competitors lowering prices while maintaining quality
- **Mitigation:** Strengthen loyalty program with tiered rewards, exclusive benefits, and experiential perks

### Risk 2: Global Operational Disruption
- **Risk:** Scaling UK localization strategy to other markets with uncertain acceptance
- **Mitigation:** A/B testing in select markets with limited-time offerings before full rollout

### Risk 3: Staff Turnover
- **Risk:** Trained employees leaving before ROI on training investment
- **Mitigation:** Longer-term contracts, loyalty bonuses, staged pay increases

## Scenario Analysis

### Scenario 1: Service Quality & Personalization Priority
- **Customer Focus:** Premium experience, ambience, personalized interactions
- **Strategy:** Invest in frontline training, employee empowerment, digital personalization through Rewards program
- **Expected Outcome:** Differentiation through emotional engagement

### Scenario 2: Shift Toward Local Brands
- **Customer Focus:** Authentically local, community-oriented brands
- **Strategy:** Acquire successful UK cafés while preserving their independent brand identity
- **Expected Outcome:** Portfolio diversification without forced repositioning

## Strategic Alignment & Feasibility

All proposed initiatives align with Starbucks' core values:
- **Courage:** Willingness to experiment with pricing and regional adaptation
- **Joy:** Enhanced employee development and customer service quality
- **Community:** Localization reflects commitment to neighborhoods

**Implementation Requirements:**
- Pricing strategy analysis with competitor benchmarking
- Menu localization leveraging existing global variation capabilities
- Enhanced employee training programs
- Cross-functional collaboration (HR, product development, operations, marketing)

**Feasibility Assessment:**
- **Pricing Model:** HIGH (regional pricing already used globally)
- **Menu & Store Localization:** HIGH (economies of scale across 1,100+ UK stores)
- **Training & Service Enhancement:** HIGH (expands current systems with minimal capex)


## Use of Generative AI

Generative AI (ChatGPT) was used as an assistive tool for:

1. **Revenue Estimation:** Generated indicative UK revenue table for Starbucks and competitors to scale pricing scenarios
2. **Risk Analysis Support:** Clarified conceptual differences between risks and scenarios, provided structured guidance on risk identification and mitigation

*AI was used for support only; all analytical and decision-making work was performed by the team.*


## Key Recommendations Summary

1. **Immediate Actions (0-3 months):**
   - Pilot regional pricing in London stores
   - Launch value-tier drink options
   - Implement refreshed customer service training

2. **Medium-Term (3-6 months):**
   - Introduce UK-inspired menu items
   - Redesign select stores for hybrid work environment
   - Strengthen loyalty program with tiered benefits

3. **Long-Term (6-12 months):**
   - Explore partnerships with local cafés and suppliers
   - Scale successful initiatives nationwide
   - Develop cultural integration strategy

## References & Data Sources

- **Allegra World Coffee Portal** (2025): UK coffee shop market data
- **Statista**: Market revenue forecasts (2018-2030)
- **Google Maps Reviews**: Primary customer feedback data
- **Starbucks Corporate**: Mission, values, and strategic positioning
- **exportcomments.com**: Review extraction tool

## License

This project was completed as part of an academic course in Business Strategy and Analytics. The analysis and recommendations are for educational purposes.
