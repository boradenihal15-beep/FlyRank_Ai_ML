# Baseline Plan

## Purpose

The baseline gives a simple rule-based comparison before using machine learning. This helps check whether the model is actually adding value.

## Research Question

Can a machine learning model help identify webpages that are likely to underperform in organic search results so they can be prioritized for optimization?

## Unit of Analysis

Each row represents one webpage.

## Baseline Idea

The baseline will rank pages using simple search-performance rules rather than a trained model.

A page may receive higher priority if it has:

- High impressions
- Low CTR
- Worse average position
- Older content age
- Many days since last update

## Example Baseline Rule

Pages with high impressions and low CTR may be ranked as higher priority because they are visible in search but not receiving many clicks.

## Evaluation

The baseline will be compared with the machine learning model using metrics such as:

- Precision@20
- Precision@50
- Ranking quality
- Interpretability

## Expected Use

The baseline is not expected to be perfect. It provides a simple comparison point to understand whether the model improves prioritization.

## Caution

This baseline does not prove why pages perform differently in search. It only provides a directional way to prioritize pages for review.
