# Mapping Africa's Conflict Relationships (1997-2014)

## Example Scenario: Ground-Level Relevance

> **Fatima**, a field coordinator for an international NGO in the Sahel, is tasked with preparing a conflict-risk report for an upcoming health deployment in **northern Mali**.  
> Her concern isn’t just *whether* violence is happening—it’s **who’s behind it**, **who’s being targeted**, and **whether this pattern is intensifying**.  

> By analyzing dyadic conflict data, she learns that:
> - **Actor1**: *Jama’at Nasr al-Islam wal Muslimin (JNIM)*  
> - **Actor2**: *Malian Military Forces*  
> - Have been in repeated confrontations in the region  
> - With a **recent surge in frequency and fatalities**

> This insight allows Fatima to:
> - Reroute medical supply chains  
> - Brief her team on security vulnerabilities  
> - Advocate for localized ceasefire diplomacy  
> - And avoid deploying staff into a rapidly escalating zone

> **The result?** A faster, smarter humanitarian response—**before** the next flashpoint ignites.

### Project Summary

In Africa’s conflict zones, it’s not just about what happened - it’s about **who keeps fighting whom**. This project explores over a decade of conflict data from the **ACLED Dyadic dataset**, focusing on recurring conflict relationships (dyads), escalation trends, and high-risk actors.

We turn raw conflict data into actionable insights for **NGOs, peacebuilders, analysts, and policy teams**.

## Deliverables

- Cleaned + enriched dataset (dyad IDs, actor normalizations, regional splits)
- Escalation curves by dyad
- Hotspot heatmaps (regional volatility maps)
- Network graphs of actor relationships
- Dyadic Risk Score (composite index: frequency × intensity × recency)
- Interactive visualizations + summary notebooks

## Key Insights

- A small number of actor dyads account for most repeated violence.
- Conflict intensity is highly skewed; most events cluster in a few regions.
- Certain actors (e.g. state forces, rebel coalitions) act as **conflict hubs**.
- Risk scores help forecast **where and with whom** future violence is likely.

## Technologies Used

- Python (Pandas, Plotly, Seaborn, NetworkX)
- Jupyter Notebooks
- ACLED Dyadic Conflict Dataset
- Geopandas + Shapefiles for heatmapping

## How to Use

Clone the repo and open the 'conflict.ipynb' notebook:

```bash
git clone https://github.com/YOUR_USERNAME/conflict-dyads-africa.git
cd conflict-dyads-africa
jupyter notebook conflict.ipynb