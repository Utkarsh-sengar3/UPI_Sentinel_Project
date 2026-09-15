# UPI Sentinel — Fraud Ring & Merchant Analytics

## Run in VS Code

1. Open this folder in VS Code.
2. Open the terminal.
3. Create/activate a Python virtual environment.
4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Run the dashboard:

```bash
python dashboard/app.py
```

6. Open the local address shown in the terminal, normally:
`http://127.0.0.1:8050`

## Dashboard pages

- Executive Overview
- Fraud & Risk
- Merchant Intelligence
- Disputes & Chargebacks
- KYC Intelligence
- Fraud Ring / Network
- Data Quality
- AgentIQ

The dashboard uses the cleaned transaction dataset and cleaned complaint/chargeback dataset. Risk signals are investigative indicators, not proof of fraud.
