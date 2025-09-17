# agents-lead — 12th House AI
![Banner](../BRAND/banner.png)

## Overview
Lead capture & validation system with schema enforcement and webhook delivery.

## Features
- Input schema validation  
- Lead data sanitizer & checker  
- Webhook handler for downstream systems  

## Setup
1. Clone repo  
2. `cp .env.example .env` and fill values  
3. Install dependencies (if needed)  
4. Run tests in `tests/`  

## Structure
- `src/` – Code modules (`schema.py`, `validator.py`, `webhook.py`)  
- `tests/` – Unit tests (`test_schema.py`)  
- `docs/` – Quickstart guide  

## Roadmap
- Next: Expand validators, add database persistence
