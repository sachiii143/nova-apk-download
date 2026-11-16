# NOVA — Security and Privacy Notes

## API keys

- Each user should provide their own provider API key.
- Never commit API keys, passwords, signing keys or tokens.
- Do not share API keys in screenshots, issues or public chats.
- Revoke and replace any key that may have been exposed.
- NOVA's inspected settings implementation uses Android encrypted preferences for provider credentials.

## AI provider data

When using an external AI provider, prompts and relevant conversation context may be sent to that provider.

Review the privacy terms of the selected provider before sending sensitive information.

Google's Gemini API free tier has separate data-use terms from its paid tier. Review current terms and pricing before use.

## Screen assistant

A screenshot selected for analysis can contain personal information. Review it before sending it to an AI provider.

## Device actions

NOVA uses an approval-oriented workflow for supported actions. Review every approval request. Basic argument validation is not a complete security guarantee.

## Network configuration

The source project has included local home-network gateway configuration. It must be reviewed and made configurable before broad distribution.

Do not send API keys over untrusted cleartext HTTP connections.

## Preview status

This is not a formal security certification or independent security audit.

Do not use this preview build for safety-critical, financial, medical or emergency operations.

Report security issues privately to the project maintainer rather than publishing credentials or exploit details in public issues.
