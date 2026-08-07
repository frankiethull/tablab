# Financial Assistant: Zero-Shot Time Series Forecasting with TabPFN-TS

This lab showcases zero-shot financial time series modeling using the **TabPFN-TS** extension integrated into an interactive Python agent workflow via **Chatlas**.

## Key Concepts
- **Time Series TFMs**: Leverages TabPFN-TS to handle complex financial series, trends, and seasonality without requiring custom model retraining per asset.
- **Python-Native Agentic Framework**: Uses `chatlas` for real-time tool orchestration and dynamic plotting.
- **Financial Metric Engineering**: Computes dynamic rolling statistics and volatility metrics for fast downstream market evaluation.

## Tech Stack
- **Python**: Core engine and model execution
- **`tabpfn-ts`**: Prior-data Fitted Network optimized for time-series forecasting
- **`chatlas`**: Multi-provider chat and tool interface for Python
- **`pandas` / `polars`**: High-performance tabular and temporal data processing