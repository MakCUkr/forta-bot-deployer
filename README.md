# Forta bot deployement bot

## Description

This bot detects transactions with deployments of Forta bots

## Supported Chains
- Polygon
## Alerts

- FAD-1
  - Fired when a transaction contains the Nethermind deployer deploys a Forta bot
  - Severity is always set to "low" 
  - Type is always set to "info"
  - Metadata :
      `agentId`: returns agentId for the bot
      `owner`: returns owner for the bot
      `metadata`: returns metadata for the bot

## Test Data

Txn:
- 0x7b3a2acef6aa72c80eaf036357e11f2ee5931f2eea8b546421e5ea18b299b4ee