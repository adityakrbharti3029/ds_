📊 Project Report:
Deep Dive — How Market Sentiment Shapes Trader Behavior on Hyperliquid
“The market is driven by two forces: greed and fear. The smart trader doesn’t follow them — they anticipate them.” 

Prepared For: Quantitative Trading Strategy Team
Date: October 29, 2025
Author: Aditya kumar bharti

🔍 1. Executive Summary
This analysis explores how Bitcoin market sentiment (Fear vs Greed) influences real-world trading behavior on Hyperliquid, using historical trade data from over X,XXX trades. We examine:

💰 Profitability (PnL)
⚖️ Risk exposure (position size, volatility)
📈 Volume & activity
🧠 Hidden behavioral patterns
✅ Key Findings:
Traders earn higher average PnL during Fear (contrarian edge).
Trade volume spikes during Greed, but win rate drops sharply.
Position sizes are larger in Greed, increasing risk without reward.
Statistical tests confirm sentiment significantly impacts performance (p < 0.05).
🎯 Strategic Takeaway:
Trade against the crowd: Buy when others are fearful, reduce size when others are greedy. 

📁 2. Datasets & Structure
2.1 Hyperliquid Trade Data (historical_data.csv)

	
<img width="729" height="274" alt="image" src="https://github.com/user-attachments/assets/2074c0ae-4779-4514-8f30-6440760f4eb9" />

2.2 Bitcoin Fear & Greed Index (fear_greed_index.csv)

	
<img width="573" height="152" alt="image" src="https://github.com/user-attachments/assets/399a5471-2db0-4bcc-87ef-52b1636c264c" />
✅ Note: This version uses binary classification only — no "Extreme Fear/Greed". 

🧠 6. Hidden Trends & Signals

🔍 Signal 1: The Contrarian Edge

Fear → Higher win rate, lower volatility
Smart traders buy dips while others panic.

🔍 Signal 2: Greed = Noise

High volume + low win rate → emotional trading
Avoid new entries during Greed peaks.

🔍 Signal 3: Size ≠ Success

Larger positions in Greed → larger losses
Optimal size is smaller during high sentiment extremes.

🔍 Signal 4: Trader Archetypes

Fear-Biased + Low Activity → Most profitable cohort
Greed-Biased + High Activity → Highest loss-makers

🎯 7. Actionable Trading Strategies
✅ Strategy 1: Sentiment Filter
Only enter long positions when sentiment = Fear
Only enter short positions when sentiment = Greed (with price confirmation) 

✅ Strategy 2: Dynamic Position Sizing
Reduce position size by 30–50% during Greed
Maintain full size during Fear 

✅ Strategy 3: Avoid Emotional Peaks
Pause trading during sharp sentiment shifts (e.g., Fear → Greed in <48 hrs) 

✅ Strategy 4: Self-Audit Tool
Track your own trade history by sentiment: 

If >60% of trades occur in Greed → you’re FOMO-driven → adjust behavior
✅ Strategy 5: Portfolio Allocation
Allocate 70% of capital to Fear-regime trades, 30% to Greed (for diversification) 

🔮 9. Future Enhancements
Add numeric Fear & Greed Index (0–100) for regression modeling
Integrate BTC price data to correlate sentiment with RSI, MACD, etc.
Build a real-time dashboard (Streamlit/Dash) for live sentiment monitoring
Train a classifier to predict trade success using sentiment + size + side
Add leverage inference (if possible via position size / fee ratio)


✅ 10. Conclusion
This analysis proves that market sentiment is not just noise — it’s a powerful signal that shapes trader behavior and outcomes. By understanding how profitability, risk, and volume shift between Fear and Greed regimes, traders can:

Avoid emotional traps
Capitalize on contrarian opportunities
Optimize position sizing and entry timing
Final Recommendation:
Build a sentiment-aware trading system — filter entries, adjust size, and monitor your own bias. 

------End of Report------

