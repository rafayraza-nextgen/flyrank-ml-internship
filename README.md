# FlyRank Capstone: Finding SEO Quick Wins Using Machine Learning

## Overview
This is a machine learning tool built to help content teams and SEO managers. It automatically finds web pages that get high views but low clicks, helping teams know exactly which pages need immediate updates to get more traffic.

## Target Audience
- Content Managers and SEO Teams who manage thousands of web pages.
- AI Engineers looking for simple, honest, and interpretable classification models.

## Architecture Sketch
[Raw Search Data (90 Days)] 
       ↓
[Feature Engineering: Impressions, Clicks, CTR]
       ↓
[Client-Grouped Split (GroupKFold)] 
       ↓
[Interpretable Decision Tree Classifier]
       ↓
[Ranked Action Playbook: Quick Wins / Monitor / No-Go]

## Setup Steps
You can run this project on your own computer by following these simple steps:

1. Clone the repository:
   ```bash
   git clone [https://github.com/rafayraza-nextgen/flyrank-ml-internship.git](https://github.com/rafayraza-nextgen/flyrank-ml-internship.git)
