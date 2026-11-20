+++
date = '2026-11-19T22:55:37-06:00'
draft = false
title = 'Artifact 4'
+++

# Introduction and Description

In this assignment, I went through a couple of case studies about data acquisition and preparation for machine learning projects. Each case addressed some of the challenges of getting useful and high quality data for building models. 

# Objective

The ojective of this assignment was for me to get in the shoes of data scientists and come up with solutions when data is not available, or is of low quality, and needed to be processed before model training can begin. 

# Value Proposition

This activity teaches me to be creative when the problem is complex and there is not a single best answer. It also provides me with some common data ppreparation approaches and practices used in the AI/ML industry. 

# Process

## Step 1: Research

Before doing the chat exercise right away, I decided to read through other contents from Workshop 4 of the class as they serve as good resources for learning the workflow of acquiring and preparing data for machine learning projects. 

## Step 2: Interactive Exercise

The exercise was set up so that I could copy a provided prompt into any available AI chat bot, and the chat bot will guide me through the exercise. I followed the instruction and performed the exercise. 

## Step 3: Reflection

After finishing the interactive exercise, I wrote about my experience and the lesson learned as a short reflection. 

# Result

## Concluding Summary

📋 **Data Challenge Scenarios — AI-Generated Practice Summary for User**

**Student:** User

**Scenario 1 — Data Quality and Cleaning:** You proposed dedupe first (script plus diff-score), validating the filter against the best available data, then cleaning, then splitting. You explained that skipping dedupe leaves repeated data in train and test, inflating scores. You also revised “leave emoji-only reviews out” to treating them as meaningful.

**Scenario 2 — Bias, Distribution Shift, and Responsible Scaling:** You identified that the new country’s data may differ from the training data and proposed a trial against human results. Your strongest reasoning was noting that human hiring decisions can be biased and that wrongful rejections prevent the company from learning from different applicants.

**Scenario 3 — Privacy, Security, and Governance:** You proposed de-identification, consent, and cross-site testing, then a trusted third-party environment with audits from both sides. You recognized that updates can leak information and that held-out validation is needed to avoid overfitting.

**Performance highlights:** You were comfortable questioning assumptions and pushing back, such as noting that privacy is not purely a technical problem. You also reached ideas independently, including cross-site testing and oversampling rare groups.

**How the reasoning developed:** After a probing question, you moved from dropping emoji-only reviews to treating them as a separate kind of language. You reached the human-labeled gold standard and the reviewer-capacity issue only after hints.

**Key insights to retain:**

- Near-duplicates can leak across splits, so group related records before splitting.
- Aggregate scores can hide errors for smaller groups.
- Federated learning changes what moves, but does not remove leakage.

**Area to keep developing:** Choosing specific metrics, such as false negative rate per group, and setting pause thresholds before a trial starts.

**Practical next step:** Look up differential privacy and how its noise level trades off against accuracy for small groups.

**Overall takeaway:** Your habit of asking where the “right answer” comes from ties the three scenarios together: clean data needs trustworthy labels, fair scaling needs local evidence, and private collaboration needs validation at every site.

*This AI-generated summary documents User’s practice conversation. It is not an independent instructor grade.*

## Reflection

I found this exercise quite challenging. The main issue was that there were no best answers in a lot of the situations. Some solutions was mentioned for improving the quality of data, but the chat bot agreed that there would still be caveats from the methods proposed. There also seemed to be a mixture of technical, logistical, and social problems. Each type should be addressed from a different angle, likely by a different person when in a professional environment. However, I was not made aware of that, so I had a difficult time coming up with answers. One example was in the recruiting scenario, where I thought I was supposed to fix the issues in the data, but the correct approach was to add more computational and human reviewing capabilities. But in the end, I did learn that getting data for machine learning projects can be a complicated affair on its own.

# Tools and Technologies Used

I used Claude from Anthropic to perform the interactive exercise. 