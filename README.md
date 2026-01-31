# Web3 Trading Analytics Assignment

## 🎯 Objective
Analyze how trader behavior aligns or diverges from Bitcoin market sentiment (Fear vs Greed).

## 📁 Repository Structure
ds_ayush_bhadouriya/
├── notebook_1.ipynb
├── notebook_2.ipynb
├── csv_files/
├── outputs/
├── ds_report.pdf
└── README.md

## 📊 Dataset Sources
- Bitcoin Fear & Greed Index
- Hyperliquid Historical Trader Data

## 📊 Key Insights from Visualizations
1. **The Fear/Volume Divergence**: As seen in `volume_vs_sentiment.png`, the highest concentration of trade volume occurs during 'Fear' phases, indicating significant "buy the dip" or hedging activity.
2. **Profitability Sweet Spot**: `pnl_dist_sentiment.png` reveals that while 'Greed' has fewer trades, the median PnL is statistically higher, suggesting trend-following strategies outperform contrarian ones on this DEX.
3. **Risk Exposure**: `size_pnl_scatter.png` highlights that 'Extreme Greed' often leads to outliers in position sizing without a proportional increase in PnL, signaling retail exhaustion.

## 🚀 How to Reproduce
1. Upload the two raw CSV files to your Colab environment.
2. Execute `notebook_1.ipynb` to generate the directory structure and cleaned data.
3. Execute `notebook_2.ipynb` to generate the final analytical outputs and clustering.
