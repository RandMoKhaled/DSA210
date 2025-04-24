#  Huda Beauty Shade Inclusivity: Data Science Project

##  Overview

This project explores the extent to which Huda Beauty’s claims of shade inclusivity in its complexion product lines (such as foundations and concealers) are supported by **objective analysis of product data**. By evaluating the shade ranges using the Fitzpatrick skin tone scale, we assess whether the brand provides equitable options for all skin types, particularly those with deeper skin tones.

---

##  Purpose

To assess the diversity and distribution of Huda Beauty’s complexion product shades and determine whether they provide **balanced coverage across all Fitzpatrick skin tone categories** (Types I–VI). This project excludes customer review data and focuses solely on product-based evidence.

---

##  Motivation

Huda Beauty is recognized for its inclusive marketing, especially in complexion products. However, inclusivity should go beyond branding — this project aims to analyze **real product shade offerings** to verify how inclusive they truly are, using a scientifically grounded classification system (the Fitzpatrick scale).

---

##  Data Sources

### 1. **Product and Shade Data**
- Collected from [Huda Beauty](https://hudabeauty.com) and [Sephora](https://www.sephora.com).
- Includes:
  - Product names and categories
  - Shade names and undertones
  - Swatch images (used for tone classification)

### 2. **Fitzpatrick Mapping**
- Each product shade was categorized into a Fitzpatrick skin type (I–VI).
- Mapping was based on:
  - Swatch visuals
  - Undertone descriptions (warm, cool, neutral)
  - Standardized shade naming conventions

### 3. **Brand Metadata**
- Launch dates and total number of shades per product line
- Breakdown of undertone availability across Fitzpatrick categories

---

##  Data Analysis

###  Preprocessing
- Normalized shade names and undertone labels
- Manually classified each shade into a Fitzpatrick type

###  Exploratory Data Analysis (EDA)
- Plotted distribution of shades across Fitzpatrick skin types
- Compared product lines (e.g., Faux Filter vs. Glowish)
- Analyzed undertone diversity within each Fitzpatrick group

###  Inclusivity Metrics
- Calculated:
  - % of shades per Fitzpatrick category
  - Ratio of warm/cool/neutral undertones within each skin tone type

###  Hypothesis Testing
- **H₀**: Huda Beauty provides an equal distribution of shades across all Fitzpatrick types
- Applied **Chi-Square Goodness of Fit Test** to evaluate distribution balance

### Trend Analysis
- Analyzed shade range evolution over time
- Compared inclusivity of recent launches vs. older ones

---



