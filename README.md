# An Explainable Multimodal Framework for Real-Time Bitcoin Forecasting
High-frequency crypto forecasting requires systems that are not only accurate but also explainable and designed for human decision-
making. Bitcoin provides a challenging context for Human-Centred
AI (HCAI) due to its continuous trading, volatility, and sensitivity
to technical signals, blockchain activity, macro events, and retail
sentiment. This paper presents an explainable multimodal frame-
work for Bitcoin forecasting at 15-minute resolution. A leakage-safe
dataset was built by aligning five modalities—market data with tech-
nical indicators, on-chain metrics, the Fear & Greed Index (FGI),
financial and crypto news, and Reddit discussions—onto a unified
15-minute grid. Several model families were evaluated, including
tree-based and sequential learners, hybrid ensembles, and a multi-
modal fusion block (MFB), for next-interval log-return prediction
under chronological splits and rolling evaluation windows. Re-
sults show that while short-horizon Bitcoin movements remain
difficult to predict, multimodal features provide modest, consis-
tent improvements over structured-only baselines, with stronger
effects during event-driven periods. To ensure transparency, the
framework integrates a dual-layer explanation system: SHapley
Additive exPlanations (SHAP)-based feature attributions combined
with large language model (LLM) narratives, ensuring outputs are
both technically faithful and human-accessible. Contributions are
threefold: (i) a reproducible multimodal dataset at 15-minute resolu-
tion; (ii) adaptation of a MFB model for log-return forecasting; and
(iii) a dual-layer explanation system advancing HCAI for decision
support in complex, high-frequency environments.
