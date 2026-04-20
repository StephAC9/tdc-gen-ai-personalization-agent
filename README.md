TDC Gen‑AI Personalization Agent

This project provides a Netlify Function acting as a secure proxy to a Salesforce Marketing Cloud (SFMC) Landing Page API.

## Purpose
- Avoid SFMC CORS limitations
- Hide SFMC API keys from browsers
- Provide a clean server‑side API layer

## Architecture
Browser → Netlify Function → SFMC Landing Page (SSJS)

## Local Development

```bash
npm install -g netlify-cli
netlify dev
``