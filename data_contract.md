# Safe Data Contract

## Project

Search Intelligence: Webpage Optimization Recommendation System

## Lane

Machine Learning

## Purpose

This project uses anonymized search and content performance data to identify webpages that may need optimization. The goal is to support prioritization decisions, not to prove search engine ranking behavior.

## Safe Data Allowed

The project may use anonymized or aggregated fields such as:

- Page ID or anonymous page label
- Content age
- Days since last update
- Impressions
- Click-through rate
- Average position
- Word count
- Content type
- Engagement rate
- Trend direction

## Data Not Allowed in Public Repository

The following must not be uploaded or published:

- Client names
- Client domains
- Full URLs
- Private search queries
- Credentials or API keys
- Raw client exports
- Personally identifiable information
- Any confidential business information

## Public Reporting Rule

All public outputs must use anonymous labels such as:

- Page_001
- Page_002
- Client_A
- Content_Type_A

The project should use cautious language such as:

- "The data suggests..."
- "The model estimates..."
- "This may help prioritize..."
- "This should be reviewed by a human before action."

## Leakage Safety

Features that directly reveal the target should not be used for training. For example, if the target is traffic decline, then future traffic change or trend percentage should not be used as an input feature.

## Human Review

Model recommendations are decision-support outputs. Final content decisions should be reviewed by a human SEO or content expert.
