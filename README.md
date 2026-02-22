# Telonex Research

Prediction market research by [Telonex](https://telonex.io). Data, notebooks, and methodology.

## Setup

Requires Python 3.9+ (tested on 3.11).

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Copy `.env.example` to `.env` and add your API key:

```bash
cp .env.example .env
```

Get a free API key at [telonex.io](https://telonex.io).

## Notebooks

| Notebook | Description |
|----------|-------------|
| [liquidity_rewards_jesus](research/liquidity_rewards_jesus/liquidity_rewards_jesus.ipynb) | How $70K in sponsored rewards reshaped depth, execution, and maker behavior on the Jesus market - [read the article](https://telonex.io/research/sponsored-liquidity-rewards-jesus-market) |
| [top_15m_crypto_traders](research/top_15m_crypto_traders/top_15m_crypto_traders.ipynb) | Analysis of 46,945 wallets across 2,688 Polymarket 15-minute crypto markets - [read the article](https://telonex.io/research/top-crypto-traders-polymarket-15m) |

## License

MIT
