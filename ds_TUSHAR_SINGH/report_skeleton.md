
# Trader Behavior vs Market Sentiment — Candidate: TUSHAR_SINGH

## Objective
Analyze relationship between trader performance and daily Bitcoin market sentiment (Fear vs Greed).

## Data
- Historical trader data: ./historical_data.csv
- Fear/Greed index: ./fear_greed_index.csv

## Key Steps
1. Clean & normalize columns, parse Timestamp IST -> UTC.
2. Merge trades to daily sentiment by trade_date_utc.
3. Feature engineering: closed_pnl, win_rate, leverage, size, pnl_per_size.
4. Aggregation & visualizations.
5. Optional classifier/clustering.

## Deliverables (in repo)
- notebook_1.ipynb (this notebook)
- csv_files/processed_merged_trades_sentiment.csv
- csv_files/agg_by_sentiment.csv
- csv_files/account_level_summary.csv
- outputs/*.png (figures)
- ds_report.pdf (final 2-4 page summary — create from this markdown + recommended figures)

## Quick insights (fill after running)
- Fill in the top results and attach graphs saved in outputs/

