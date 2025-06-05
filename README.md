## Credit Score Cutoffs and Profit Maximization

This project presents a data-driven plan for banks to evaluate and **optimize credit score thresholds** used in credit limit assignment, ultimately aiming to **maximize profitability** through more informed risk–reward trade-offs.

We implement a **Regression Discontinuity Design (RDD)** to test whether existing credit score cutoffs are set optimally. By estimating changes in customer behavior (default, spending, profit) around these thresholds, we provide actionable insights to fine-tune credit policies.

---

### Overview

#### Motivation

Many banks use a **Markov Decision Process (MDP)** framework with bucketing algorithms to assign credit limits based on credit scores. These buckets impose thresholds that may not capture true behavioral responses near the cutoff.

RDD offers a quasi-experimental design that helps banks validate whether a threshold jump meaningfully impacts outcomes, and more importantly, whether that jump reflects **optimal business value**.

While academic literature often emphasizes the magnitude of the jump at the cutoff, the comparison of slopes on either side is frequently overlooked. In this project, we deliberately highlight this slope contrast as a key decision lever for firms to refine thresholds and unlock greater profit potential.

#### Objectives

This project lays out a step-by-step framework to:
- Quantify the **causal effect** of higher credit limits on default, spending, and profit
- Evaluate if current thresholds align with **maximum expected profit**
- Recommend **scenario-based adjustments** (e.g., shifting cutoffs, adjusting the offer structure) based on observed discontinuities to **capture unrealized profit**

---

### Using This Repo

Refer to **`Credit Score Cutoffs and Profit Maximization.pdf`** for:
- A structured walkthrough of the RDD setup
- Scenario-specific guidance for interpreting slope differences around cutoffs
- Execution steps for deploying this approach within a banking context

---

## Credit

Developed by:
- Xueshan (Kevin) Peng  
- Mengyang (Elena) Liu  
- Yuanhang (Charles) Zhang  
- Haoyu (Howell) Su  

Referenced [Moody’s "Determining the Optimal Dynamic Credit Card Limit"](https://www.moodys.com/web/en/us/insights/resources/Determining-the-Optimal-Dynamic-Credit-Card-Limit.pdf).  
Simulated data used for demonstration purposes only.
