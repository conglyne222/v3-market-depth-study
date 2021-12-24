

This project calculates current and historical market depth at all levels from any Uniswap V3 liquidity pools and preform comparison against centralized exchange market depths.


Data requirement:
 - Dune Analytics: to obtain all mint and burn events for each pool (mintburn_dune.sql); this can possibly be replaced with subgraph data (?)
 - Kaiko API: to obtain centralized exchange market depth


Files:
 - depthutil.py  Functions used to construct liquidity distribution retrospectively and generate market depth at each historical date and level
 - MarketDepthStudy.ipynb  Notebook used to construct key results
