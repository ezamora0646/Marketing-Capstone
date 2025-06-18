# Marketing-Capstone

## Table of Contents

- [Scope & Goals of Analysis](#scope-&-goalsof-analysis)
- [Dataset & Overview of Data Structure](#dataset--overview-of-data-structure)
- [Executive Summary](#executive-summary)
- [Insights Deep Dive](#insights-deep-dive)
- [Recommendations](#recommendations)
  

## Scope & Goals of Analysis

COOP Careers is a non-profit organization dedicated to helping recent graduates overcome underemployment. The 16-week fellowship culminates in a Data Analytics Capstone, in which fellows deliver data-driven business recommendations to stakeholders and representatives from marketing agencies such as RPA. The dataset analyzed contains synthetic data from 700+ ad campaigns across the US that were launced in 2024. Various branding and performance metrics were calculated using the available data on expenses, impressions, clicks, etc. This report focuses on insights I generated as an Audience Analyst responsible for identifying top performing segments and generating audience personas. Additionally, these insights are presented alongside findings from the Creative Analyst I collaborated with. 


The **main objectives** of this analysis are to:
1. Benchmark Top Performing Audience Segments
2. Generate Audience Personas to inform marketing strategies
3. Optimize creative sizing and messaging for future campaigns

## Dataset & Overview of Data Structure

The dataset used for this analysis comprised over 20 fields capturing both categorical audience attributes and quantitative performance metrics across digital ad campaigns. Each row represents a unique media delivery instance tied to an audience segment and creative variation. Audience segmentation was defined across multiple hierarchical levels, from broad interest categories (e.g., Finance, Arts & Entertainment) to specific subcategories (e.g., Credit & Lending, Events & Listings), allowing for granular analysis of behavioral and contextual targeting.

The dataset was cleaned and standardized using Power Query to ensure reliable aggregations and accurate comparisons across segment types, devices, and creative strategies. This structured foundation enabled advanced filtering, pivot analysis, and dashboard visualizations to surface insights on high-performing audience groups and media strategies. Below is the data field summary:

<div align="center">
 <img width="631" alt="Image 1" src="https://github.com/user-attachments/assets/e4f686f2-70ee-4967-a576-3be8bacc701c" />
</div>


## Executive Summary

**Audience Insights:**
Segments such as Brand Propensities, Finance, and Intent consistently outperformed others across both cost-efficiency and engagement KPIs. For example, Brand Propensities achieved the **lowest CPA ($166.14) and CPC ($4.84)**, while Intent audiences led in **CTR (31.93%)** and remained competitive in **CVR (5.16%)**, suggesting a dual role in both branding and performance campaigns.

Creative Performance:
Among creative sizes, 300x250 and 320x50 emerged as **cost-effective and reliable** across the cost and rate-based KPIs of all campaigns. On average, 320x50 offered the **lowest CPA ($682) and highest CVR (11.80%)**, while 300x250 maintained the **lowest average vCPM ($536.80)**, suggesting that both formats warrant continued use and A/B testing to optimize performance across cost and conversion objectives. While median performance across creative sizes was relatively stable, 320x50 carried more upside potential, albeit with outlier risk.

**Key Takeaway:**
Top-performing audience segments frequently coincided with high-performing creative formats (e.g., 300x250, 320x50), suggesting alignment between media strategy and audience targeting. Given their complementary strengths, 320x50 and 300x250 should be prioritized in A/B testing to determine which creative format best aligns with specific campaign goals—whether focused on acquisition (CPA, CVR) or efficiency (vCPM).

## Insights Deep Dive

### Creative Sizing Efficiency 

#### 320x50 is the most cost-effective creative size
<p align="center">
  <a href="https://public.tableau.com/app/profile/edwin.zamora/viz/AudienceAnalystCapstone/Dashboard2?publish=yes">
    <img src="https://github.com/user-attachments/assets/36dcd61e-5b8a-4bfb-8091-c74f72d486a7" alt="View Creative Sizing Insights" />
</p>
Across all campaigns, the creative sizes 300x250 and 320x50 emerged as the **most cost-efficient formats**. Both consistently posted the **lowest CPM ($0.03)**, with 320x250 also offering the **lowest vCPM ($61.67).** Notably, 320x50 edged ahead on conversion metrics, generating the **highest CVR of 3.90%.**

While 300x250 performed reliably across metrics, 320x50's strong benchmarks—particularly on CPA ($310.59) and CTR (25.67%)—suggest that this format has higher upside when paired with the right segment. In contrast, **300x50 consistently underperformed,** recording the highest CPC ($17.16) and CPA ($456.41). These findings highlight the **strategic value** of selecting creative formats not just based on cost, but on their potential for conversion lift and audience match.





### Top Performing Audience Segments


#### Campaign Efficiency Isn’t One-Dimensional  

<p>
  <a href="https://public.tableau.com/app/profile/edwin.zamora/viz/AudienceAnalystCapstone/Dashboard1?publish=yes">
  <img src="https://github.com/user-attachments/assets/366919dc-671e-47d4-bb6c-c46651da85f2" alt = "Audience Performance Metrics">
</p>
Audience performance varied widely across metrics, revealing a clear decoupling between cost and outcome. For example, the Finance segment reported one of the highest CPCs ($7.24) but still ranked among the top 3 segments with the lowest CPA ($174.30) and second-lowest CPM ($13.84). This suggests that higher CPCs can still yield cost-effective conversions when the audience is well-aligned with campaign objectives.

In contrast, segments like Life Event and Interest Propensities appeared cost-efficient by CPC ($5.77 and $6.61, respectively) but fared worse on CPA and CPM. Ultimately, these results show that no single metric captures campaign value. A balanced view is required to contextualize trade-offs between click volume, cost per acquisition, and impression quality. 

<p>
  
</p>

#### Volume ≠ Engagement

<p>
  <a href="https://public.tableau.com/app/profile/edwin.zamora/viz/AudienceAnalystCapstone/Dashboard3?publish=yes">
  <img src="https://github.com/user-attachments/assets/1eed7665-b304-4cb1-bea0-c3277a7dd693" alt = "Audience Branding Metrics">
</p>
Media & Entertainment stood out on engagement metrics, with a CTR of 32.56%—the highest among all audience segments—despite only ranking mid-tier in CPA and CVR. However, this did not translate to aduience engagement especially when comparin results to smaller markets. 

An added layer of complexity emerged when comparing impression volume to performance outcomes. Beauty & Fitness recorded more than 2 million viewable impressions across 21 campaigns but failed to capture top performance metrics. In contrast, Lotame had just 18 campaigns and far fewer impressions but nearly matched top performers on CTR (29.95%) and CVR (6.58%).

This reinforces the importance of impression quality over quantity. Segments with fewer but more targeted impressions and well-matched creative formats often converted at higher rates. Future testing might benefit from reallocating spend to smaller segments that, while niche, may offer stronger return on investment when paired with the right creative strategy.


<p align="center">
  <img src="">
  <img src="">
</p>



#### Cross-Cutting Synergies

<p align="center">
  <img src= "">
</p>

<p align="center">
  <img src="">
  <img src="">
</p>


#### 




## Recommendations
**Strategic takeaway:** 

** **
**Implication:** 

**Recommendations** for :
1. 
2. 

** **
**Implication:** 

**Recommendations** for :
1. 
2. 

** **
**Implication:** 

**Recommendations** for :
1. 
2. 


