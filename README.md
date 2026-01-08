📕 Alpha-Sentinel

Technical Documentation WEEX AI Wars

System Purpose & Design Philosophy
Alpha-Sentinel is a production-grade AI trading system designed to operate autonomously on WEEX using real capital during the AI Wars competition.

The system prioritizes:

Risk-adjusted returns over raw profit

Capital preservation in volatile markets

AI-driven ecision restraint

Full transparency via structured AI logs

Strict compliance with WEEX trading constraints

Unlike high-frequency or gambling-style bots, Alpha-Sentinel trades selectively based on market regime confidence and dynamically adapts exposure using reinforcement learning.

High-Level Architecture
┌──────────────────┐

│ React Dashboard │ (Optional – visualization only)

└─────────┬────────┘

      │ REST / WebSocket
┌─────────▼────────┐

│ FastAPI Server │

│ (Control Layer) │

└─────────┬────────┘

      │
┌─────────▼────────┐

│ AI Trading Core │

│ (Python Engine) │

└─────────┬────────┘

      │
┌─────────▼────────┐

│ WEEX API │

│ (Market + Trade)│

└──────────────────┘

Technology Stack
Backend (Core Execution)

Python 3.10+
