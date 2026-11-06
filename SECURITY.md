# Security Policy

## Supported Versions

The latest version of this repository is supported with security updates.

## Reporting a Vulnerability

If you discover a security vulnerability, please report it privately to the repository maintainer.

Do not disclose API keys, access tokens, customer information, or other sensitive data in public issues.

## Credential Management

- API credentials must be stored in GitHub Actions Secrets.
- Never commit `.env` files or API tokens.
- Rotate credentials immediately if exposure is suspected.
- Use the minimum permissions required for integrations.

## Automated Workflows

Hosting lifecycle workflows interact with Notion and Render APIs. Changes to these workflows should be reviewed before deployment.
