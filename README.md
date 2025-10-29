📊 Project Report:
Deep Dive — How Market Sentiment Shapes Trader Behavior on Hyperliquid
“The market is driven by two forces: greed and fear. The smart trader doesn’t follow them — they anticipate them.” 

Prepared For: Quantitative Trading Strategy Team
Date: October 29, 2025
Author: [Your Name]

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
Column	Description
`Account`	Trader ID
`Execution Price`, `Size USD`	Trade execution details
`Closed PnL`	Profit/Loss per trade
`Side`, `Direction`	Buy/Sell
`Timestamp`	Unix milliseconds (used for merging)
	
<img width="729" height="274" alt="image" src="https://github.com/user-attachments/assets/2074c0ae-4779-4514-8f30-6440760f4eb9" />

2.2 Bitcoin Fear & Greed Index (fear_greed_index.csv)
Column1	Column2
Column	Description
`date`	Calendar date
`classification`	Binary label: **"Fear"** or **"Greed"**
	
<img width="573" height="152" alt="image" src="https://github.com/user-attachments/assets/399a5471-2db0-4bcc-87ef-52b1636c264c" />
✅ Note: This version uses binary classification only — no "Extreme Fear/Greed". 

⚙️ 3. Methodology Overview
Step-by-Step Pipeline:
Load and clean both datasets
Convert timestamps → datetime → merge by date
Engineer features: is_profitable, risk_proxy = Size USD
Segment trades by sentiment
Generate 10+ visualizations across 4 dimensions
Run statistical tests
Derive strategy rules


