# RICE Prioritization Framework Template

## Overview
RICE is a prioritization framework that helps product teams make data-driven decisions about which features to build. It stands for:
- **Reach:** How many users will this impact?
- **Impact:** How much will this impact each user?
- **Confidence:** How confident are we in our estimates?
- **Effort:** How much work will this require?

## Formula
**RICE Score = (Reach × Impact × Confidence) ÷ Effort**

## Template

### Feature: [Feature Name]

| Component | Value | Rationale |
|-----------|-------|-----------|
| **Reach** | [Number of users per time period] | [How you calculated this number] |
| **Impact** | [1-3 scale] | [Why this impact level] |
| **Confidence** | [0-1 scale] | [Basis for confidence level] |
| **Effort** | [Person-weeks] | [Breakdown of work required] |
| **RICE Score** | [Calculated score] | [Final prioritization] |

### Impact Scale
- **3:** Massive impact (solves critical user problem)
- **2:** High impact (significant improvement)
- **1:** Medium impact (moderate improvement)

### Confidence Scale
- **1.0:** Very high confidence (strong data)
- **0.8:** High confidence (good data)
- **0.5:** Medium confidence (some data)
- **0.2:** Low confidence (limited data)

### Effort Guidelines
- **1-2 weeks:** Small features, bug fixes
- **3-6 weeks:** Medium features, integrations
- **7-12 weeks:** Large features, new products
- **13+ weeks:** Major initiatives, platform changes

## Example: Mobile-Only Plan

| Component | Value | Rationale |
|-----------|-------|-----------|
| **Reach** | 12M users/month | Based on mobile-only user segment analysis |
| **Impact** | 4 | Critical for market penetration in price-sensitive markets |
| **Confidence** | 0.8 | Strong market research data available |
| **Effort** | 4 weeks | Backend pricing logic + frontend changes |
| **RICE Score** | 9.6 | High priority for next quarter |

## Best Practices

### 1. Use Consistent Time Periods
- Standardize on monthly or quarterly reach
- Ensure effort estimates are comparable
- Use same confidence criteria across features

### 2. Validate Assumptions
- Cross-check reach estimates with analytics
- Validate impact assumptions with user research
- Review effort estimates with engineering team

### 3. Regular Updates
- Recalculate scores as new data becomes available
- Adjust confidence based on validation results
- Update effort estimates as scope changes

### 4. Context Matters
- Consider strategic alignment beyond RICE score
- Factor in technical debt and dependencies
- Account for market timing and competitive pressure

## Common Pitfalls

### 1. Overestimating Reach
- **Problem:** Assuming all users will use new feature
- **Solution:** Use historical adoption rates as baseline

### 2. Underestimating Effort
- **Problem:** Not accounting for testing, deployment, monitoring
- **Solution:** Include full development lifecycle in estimates

### 3. Inconsistent Confidence Scoring
- **Problem:** Different team members use different criteria
- **Solution:** Establish clear confidence guidelines

### 4. Ignoring Dependencies
- **Problem:** High RICE score but blocked by other work
- **Solution:** Factor in prerequisite work and technical debt

## Advanced Techniques

### 1. Sensitivity Analysis
Test how RICE scores change with different assumptions:
- What if reach is 50% lower?
- What if effort is 2x higher?
- What if confidence drops to 0.5?

### 2. Portfolio Balancing
Use RICE alongside other factors:
- Strategic alignment
- Technical risk
- User feedback urgency
- Competitive pressure

### 3. Dynamic Scoring
Adjust scores based on:
- Market conditions
- User behavior changes
- Competitive landscape shifts
- Technical constraints

## Template Usage

1. **Copy this template** for each feature evaluation
2. **Fill in the values** based on your research and estimates
3. **Calculate the RICE score** using the formula
4. **Review and validate** assumptions with stakeholders
5. **Update regularly** as new information becomes available

## Related Frameworks

- **MoSCoW:** Must have, Should have, Could have, Won't have
- **Value vs Effort Matrix:** Simple 2x2 prioritization
- **Kano Model:** Basic, Performance, Excitement features
- **Weighted Scoring:** Custom criteria with weights

---

## Legal and Compliance Notice

**COMPREHENSIVE DISCLAIMER:**

This template is an educational case study created by Vikas Sahani for learning product management methodologies. It is not affiliated with, endorsed by, or sponsored by Netflix, Inc. or any other company mentioned herein.

**EDUCATIONAL USE ONLY:**
- This template is created solely for educational and learning purposes
- All data, insights, and recommendations are hypothetical and simulated
- No confidential, proprietary, or insider information has been used
- This content is not suitable for commercial decision-making or investment purposes

**Contact Information:**
- **Author:** Vikas Sahani
- **Email:** vikassahani17@gmail.com
- **LinkedIn:** [www.linkedin.com/in/vikas-sahani-727420358](https://www.linkedin.com/in/vikas-sahani-727420358)
- **Purpose:** Educational demonstration of PM research methodology

*This template is for educational purposes. Adapt based on your team's specific needs and context.*
