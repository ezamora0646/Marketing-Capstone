# Optimizing National Marketing Campaigns

## Table of Contents

- [Scope & Goals of Analysis](#scope-&-goalsof-analysis)
- [Dataset & Overview of Data Structure](#dataset--overview-of-data-structure)
- [Executive Summary](#executive-summary)
- [Insights Deep Dive](#insights-deep-dive)
- [Recommendations](#recommendations)
  

## Scope & Goals of Analysis

COOP Careers is a non-profit organization dedicated to helping recent graduates overcome underemployment. The 16-week fellowship culminates in a Data Analytics Capstone, in which fellows deliver data-driven business recommendations to stakeholders and representatives from marketing agencies such as RPA. The dataset analyzed contains synthetic data from 700+ ad campaigns across the US that were launced in 2024. Various branding and performance metrics were calculated using the available data on expenses, impressions, clicks, etc. This report focuses on insights I generated as an Audience Analyst responsible for identifying top performing segments and generating audience personas. Additionally, these insights are presented alongside findings from the analysis of data on creative sizing. 


The **main objectives** of this analysis are to:
1. Optimize creative sizing for future campaigns 
2. Benchmark Top Performing Audience Segments
3. Determine Optimal Creative Sizing and Audience Strategies

## Dataset & Overview of Data Structure

The dataset used for this analysis comprised over 20 fields capturing both categorical audience attributes and quantitative performance metrics across digital ad campaigns. Each row represents a unique media delivery instance tied to an audience segment and creative variation. Audience segmentation was defined across multiple hierarchical levels, from broad interest categories (e.g., Finance, Arts & Entertainment) to specific subcategories (e.g., Credit & Lending, Events & Listings), allowing for granular analysis of behavioral and contextual targeting.

The dataset was cleaned and standardized using Power Query to ensure reliable aggregations and accurate comparisons across segment types, devices, and creative strategies. This structured foundation enabled advanced filtering, pivot analysis, and dashboard visualizations to surface insights on high-performing audience groups and media strategies. Below is the data field summary:

<div align="center">
 <img width="631" alt="Image 1" src="https://github.com/user-attachments/assets/e4f686f2-70ee-4967-a576-3be8bacc701c" />
</div>


## Executive Summary

**Audience Insights:**
Segments such as Brand Propensities, Finance, and Intent consistently outperformed others across both cost-efficiency and engagement KPIs. For example, Brand Propensities achieved the **lowest CPA ($166.14) and CPC ($4.84)**, while Intent audiences led in **CTR (31.93%)** and remained competitive in **CVR (5.16%)**, highlighting its effectiveness across both branding and performance-focused objectives.

**Creative Performance:**
Among creative sizes, 300x250 and 320x50 emerged as **cost-effective and reliable** across the cost and conversion KPIs of all campaigns. 320x50 consistently offered the **lowest CPA ($310.59) and the highest CVR (3.9%)**, while 300x250 maintained the **lowest vCPM ($65.78)**, suggesting that both formats warrant continued use and A/B testing to optimize performance across cost and conversion objectives. While median performance across creative sizes was relatively stable, 320x50 carried more upside potential, albeit with outlier risk.

**Cross-Cutting Analysis:**
The most effective campaign outcomes occurred where **high-performing audience segments were paired with optimal creative sizes**. For example, *Intent audiences paired with 320x50* achieved elevated CTR (32.99%) and CVR (6.12%), while *Brand Propensities with 320x50* yielded the **lowest CPA ($132.20)**. Conversely, creative formats like *300x50 often inflated CPC and CPA* without clear performance gains, highlighting inefficiencies in certain segment–format combinations.

**Key Takeaway:**
Campaign efficiency and engagement are maximized not through isolated optimization, but through **targeted pairing of audience segments and creative formats**. Strategic use of combinations such as *Intent + 320x50* or *Brand Propensities + 300x250* allows advertisers to tailor their creative strategy by audience intent and cost sensitivity. These insights support a recommendation to prioritize **creative-audience alignment** in future media planning, using A/B testing to refine performance benchmarks across cost and conversion goals.

## Insights Deep Dive

### Creative Sizing Efficiency 

#### 320x50 is the most cost-effective creative size
<p align="center">
  <a href="https://public.tableau.com/app/profile/edwin.zamora/viz/AudienceAnalystCapstone/Dashboard2?publish=yes">
    <img src="https://github.com/user-attachments/assets/36dcd61e-5b8a-4bfb-8091-c74f72d486a7" alt="View Creative Sizing Insights" />    

Across all campaigns, the creative sizes 300x250 and 320x50 emerged as the **most cost-efficient formats**. Both consistently posted the **lowest CPM ($0.03)**, with 320x250 also offering the **lowest vCPM ($61.67).** Notably, 320x50 edged ahead on conversion metrics, generating the **highest CVR of 3.90%.**

While 300x250 performed reliably across metrics, 320x50's strong benchmarks—particularly on CPA ($310.59) and CTR (25.67%)—suggest that this format has higher upside when paired with the right segment. In contrast, **300x50 consistently underperformed,** recording the highest CPC ($17.16) and CPA ($456.41). These findings highlight the **strategic value** of selecting creative formats not just based on cost, but on their potential for conversion lift and audience match.
</p>

<p>
  <br>
</p>

### Top Performing Audience Segments


#### Campaign Efficiency Isn’t One-Dimensional  

<p>
  <a href="https://public.tableau.com/app/profile/edwin.zamora/viz/AudienceAnalystCapstone/Dashboard1?publish=yes">
  <img src="https://github.com/user-attachments/assets/366919dc-671e-47d4-bb6c-c46651da85f2" alt = "Audience Performance Metrics">
    
Audience performance varied widely across metrics, revealing a clear decoupling between cost and outcome. For example, the Finance segment reported one of the **highest CPCs ($7.24)** but still ranked among the top 3 segments with the **lowest CPA ($174.30)** and secondlowest CPM ($13.84). This suggests that higher CPCs can still yield cost-effective conversions when the audience is well-aligned with campaign objectives. <br>

In contrast, segments like Life Event and Interest Propensities *appeared* cost-efficient by CPC ($5.77 and $6.61, respectively) but *fared worse* on CPA and CPM. Ultimately, these results show that **no single metric captures campaign value**. A balanced view is required to contextualize trade-offs between click volume, cost per acquisition, and impression quality. 
</p>

<p>
  <br>
</p>


#### Volume ≠ Engagement

<p>
  <a href="https://public.tableau.com/app/profile/edwin.zamora/viz/AudienceAnalystCapstone/Dashboard3?publish=yes">
  <img src="https://github.com/user-attachments/assets/2f367983-1260-4e7f-9daf-2e57fc467e07" alt = "Audience Branding Metrics">

Media & Entertainment stood out on engagement metrics, with a CTR of 32.56%—the highest among all audience segments—despite only ranking *mid-tier in CPA and CVR*. However, this did not translate to audience engagement especially when comparing results to smaller markets. 

An added layer of complexity emerged when comparing impression volume to performance outcomes. Beauty & Fitness recorded **more than 2 million viewable impressions** across 21 campaigns but **failed to capture top performance metrics**. In contrast, Lotame had just 18 campaigns and far fewer impressions but nearly matched top performers on CTR (29.95%) and CVR (6.58%).

This reinforces the importance of impression quality over quantity. Segments with fewer but more targeted impressions and well-matched creative formats often converted at higher rates. Future testing might benefit from reallocating spend to smaller segments that, while niche, may offer stronger return on investment when paired with the right creative strategy.
</p>

<p>
  <br>
</p>

#### Performance Peaks When Audience & Format Align

<p align="center">
  <img src= "https://github.com/user-attachments/assets/6c0823bb-96e3-4ab2-bac6-c69dc89f4cf1">
<img src="https://github.com/user-attachments/assets/137fac86-51cb-4881-b323-9d7356ad7ee8">
</p>

Key patterns emerged from analyzing the creative size utilized in campaigns among the audience segments with the best performance (first table) and engagement (second table) metrics. For instance, Brand Propensities + 320x50 delivered **strong results across all the performance metrics**, with a CPC of just $3.75, the lowest among all creative formats, and the lowest CPA of $132.20.

However, not all audience segments perform equally across formats, nor do high-performing formats yield the same results for all audiences. For example, Finance + 300x50 reported a CPA of $1,479.79, vastly underperforming Finance + 320x50 ($159.57), despite targeting the *same behavioral group.*

As for engagement metrics, 320x50 consistently yielded the best CVR and CTR for top performing audience segments and top branded segements alike. Further testing is suggested to create strategies that capitalize on high branding visibility of audience segments like Media & Entertainment.

Altogether, data suggests that optimal performance is achieved not through blanket assumptions about creative or audience, but through targeted pairings that align format strengths with audience behavior and intent.

<p>
  <br>
</p>

## Recommendations
**Strategic takeaway:** 
Optimizing audience engagement and campaign efficiency requires more than selecting high-performing segments or cost-effective creatives in isolation. The strongest results occur when **audience behavior, creative format, and campaign objectives are strategically aligned**. 
<br>

**Recommendations** for optimizing efficiency:
1. Prioritize high-performing pairings & allocate budget toward audience–creative combinations that consistently outperform on both cost and conversion metrics.
2. Limit or reassess spend on underperforming creative sizes like 300x50, which showed inflated CPC and CPA metrics with minimal conversion upside.


**Recommendations** for strategy building:
1. Test creative alignment & run A/B tests to validate whether improved performance in specific segments is driven by format, messaging, or their synergy.
2.  Audience segmentation should inform creative format selection upfront, enabling more strategic campaign design and forecasting.


