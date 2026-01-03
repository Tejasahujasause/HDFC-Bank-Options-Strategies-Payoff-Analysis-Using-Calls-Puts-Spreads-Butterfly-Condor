# HDFC-Bank-Options-Strategies-Payoff-Analysis-Using-Calls-Puts-Spreads-Butterfly-Condor

This project analyzes HDFC Bank equity options by constructing multiple option positions and spreads to study how payoff, risk, and return profiles change with strategy structure, while keeping the same underlying and expiry.

The focus is on payoff engineering, not price prediction.

**Underlying Setup**
Underlying asset: HDFC Bank equity
Spot price reference: ₹1659.9 (as of 9 July 2023)
Instruments used: Call and Put options with same expiry
Tool used: Excel-based payoff modeling

**Sheet 1: Spread Strategy**

This sheet constructs a vertical call spread by combining a long call and a short call at different strikes.

**Purpose:**
Express a moderately bullish view
Reduce premium cost compared to a naked call
Cap both maximum profit and maximum loss

**Insight:**
Directional exposure can be achieved with defined risk and improved capital efficiency by sacrificing unlimited upside.

**Sheet 2: Butterfly Strategy – 1**

This sheet constructs a long call butterfly using three strikes.

**Purpose:**

Profit from low volatility or price stability
Concentrate payoff near a specific strike
Keep losses limited on both sides

**Insight:**
Butterfly spreads are volatility and precision strategies, not directional bets. They reward price stability rather than movement.

**Sheet 3: Condor Strategy**

This sheet builds a condor spread using four option legs.

**Purpose:**

Profit if price remains within a wider range
Trade lower maximum profit for higher probability of success
Maintain defined downside risk

**Insight:**
Condors prioritize consistency over payoff sharpness, making them suitable for range-bound market expectations.

**Sheet 4: Butterfly Strategy – 2**

This sheet modifies the butterfly structure using different strike spacing.

**Purpose:**

Show how strike selection changes payoff shape
Compare sensitivity of profit, loss, and break-even points

**Insight:**
Even with the same strategy type, payoff profiles vary significantly based on strike placement, highlighting true payoff engineering.

**Key Takeaway**

Using the same underlying and expiry, different option structures produce completely different outcomes. This project demonstrates how traders use options to design risk-controlled payoff structures for directional, neutral, and volatility-based market views.
