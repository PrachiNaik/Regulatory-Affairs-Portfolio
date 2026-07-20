# Regulatory Affairs Portfolio — PulseTrack Case Study

I'm a QA analyst transitioning into medical device regulatory affairs. 
This repo is a self-directed case study I built to apply core RA 
concepts — QMSR/ISO 13485, ISO 14971, IEC 62304, FDA 510(k), EU MDR, 
structured labeling, and premarket cybersecurity — to a realistic 
fictional device, end-to-end across its full lifecycle.

**Device**: PulseTrack — a wireless fingertip pulse oximeter with a 
companion mobile app. Class II (US, 510(k) pathway) / Class IIa (EU MDR).

**Note**: PulseTrack is a fictional device created for training 
purposes. All data, comparisons, and predicate references are 
illustrative, not real regulatory filings.

## What's in this repo

| # | Folder | What it demonstrates |
|---|---|---|
| 00 | qms-foundation-qmsr-820 | QMSR / 21 CFR 820 crosswalk to ISO 13485 — the QMS foundation everything else operates inside |
| 01 | intended-use-and-classification | Defining device scope and choosing a regulatory pathway |
| 02 | risk-management-iso14971 | Hazard analysis and risk control methodology |
| 03 | design-controls-dhf | Design History File structure (ISO 13485 Clause 7.3) |
| 04 | fda-submission-510k | Substantial equivalence argument against a predicate device |
| 05 | clinical-evaluation-eu-mdr | Clinical Evaluation Report structure per MDR Annex XIV |
| 06 | labeling-ifu-xml | Instructions for Use, including a structured/electronic (eIFU) XML sample |
| 07 | cybersecurity | Premarket cybersecurity risk assessment and SBOM sample |
| 08 | postmarket-surveillance | Complaint handling and CAPA process |
| 09 | regulatory-strategy-memo | High-level strategy synthesis tying the full lifecycle together |

## Why this structure

The folders are numbered to mirror the actual product lifecycle: 
a device's QMS exists before any single product does (00), which is 
why it comes first — everything from design controls through 
post-market surveillance operates inside that system. From there, 
the folders roughly follow the order a real device moves through: 
scope → risk → design → submission → clinical evidence → labeling → 
security → post-market.

Using one device across every folder — rather than scattered, 
unrelated examples — is intentional. It's meant to show how these 
documents actually connect to each other in a real Design History 
File / Technical File, not just that I can define each term in 
isolation.

## Background
