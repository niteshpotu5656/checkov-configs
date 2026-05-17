# Checkov Account Configs

One JSON file per AWS account.
The MCP server checks for this file before running any pipeline.
If it does not exist the MCP creates it automatically.

## File naming
`{account_id}.json`

## Required fields
- account_id
- account_name
- environment
- app_id
- manager
- enabled
