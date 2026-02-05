# Buy-side-project

# M&A Valuation & EPS Accretion/Dilution Merger Model

## Overview

This repository contains a fully integrated **Investment Banking–style M&A analysis** built from scratch, combining standalone valuation with merger consequence modeling.

The objective of the project was to replicate how bankers evaluate an acquisition:

## Files Included

### 1. Valuation Model

A standalone valuation framework was built to assess both the **acquirer (Bajaj Auto)** and the **target (HBL Engineering)** on an intrinsic basis.

**Methodology applied:**

* Discounted Cash Flow (DCF) valuation for both entities

**Work performed:**

* Forecasted operating financials and free cash flows
* Estimated WACC using capital structure and market inputs
* Derived terminal value using perpetuity growth assumptions
* Calculated enterprise value and implied equity value
* Arrived at intrinsic value per share for both acquirer and target


### 2. EPS Accretion / Dilution Merger Model

A full pro-forma merger consequence model evaluating the impact of the acquisition on the acquirer’s earnings per share.

**Key components:**

#### Transaction Assumptions

* Acquirer & Target share prices
* Offer premium
* Shares outstanding
* Net income & EPS base

#### Purchase Price Allocation

* Equity value calculation
* Debt assumed
* Cash acquired
* Enterprise value derivation

#### Financing Structure Scenarios

* 100% Stock
* 100% Cash
* 50% Cash / 50% Stock

#### Ownership & Share Issuance

* Exchange ratio computation
* New shares issued
* Pro-forma share count

#### Pro-Forma Earnings Build

* Combined net income
* Synergy incorporation
* Interest & tax adjustments

#### EPS Impact Analysis

* Pre-deal EPS
* Post-deal EPS
* Accretion / Dilution %

## Key Insights Derived

* Stock-funded acquisitions of higher-P/E targets tend to be dilutive.
* Cash deals are more likely to be accretive, subject to financing cost.
* Synergies play a critical role in offsetting dilution.
* Premium paid directly impacts exchange ratio and share issuance.



---
