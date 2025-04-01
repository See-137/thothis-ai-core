# Thothis AI Core 🧠

An intelligent, modular, serverless-ready assistant built for cloud-native deployment and daily operations.

## 🌐 Modules Included

- `telegram_bot.py` — Handles Telegram webhook + GPT replies
- `daily_brief.py` — Morning summary drop logic
- `xrp_strategy.py` — Price zone checker + GPT insight + journaling
- `gpt_engine.py` — Shared GPT handler with retries + temperature support

## ☁️ Infra Scaffold

Inside `infrastructure/terraform/`:
- ✅ Lambda function stubs
- ✅ API Gateway base
- ✅ Secrets Manager (OpenAI, Telegram)
- ✅ DynamoDB (journaling, memory)
- ✅ IAM roles + basic policy templates

## 📦 Deployment

To deploy serverless AI stack:
1. Configure `.env` or use AWS Secrets Manager
2. Use Terraform to provision infra
3. Connect Telegram to bot via webhook
4. Automate daily drops, XRP zone alerts, journaling

## 📜 License

MIT — built to be hacked, extended, and scaled.
