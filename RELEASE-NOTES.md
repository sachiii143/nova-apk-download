# NOVA 1.4.0 — Android Preview Release

NOVA is an independent Android personal AI companion project.

Its long-term mission is to move beyond ordinary chatbot interactions toward a context-aware assistant with user-controlled memory, voice communication and permission-aware task assistance.

## Download

Download `NOVA-1.4.0.apk` from the Assets section below.

Direct APK:
https://github.com/sachiii143/nova-apk-download/releases/download/v1.4.0/NOVA-1.4.0.apk

## What is NOVA?

NOVA is being developed around five principles:

- Memory — retain useful information the user chooses to save.
- Context — use relevant personal profiles and conversation context.
- Communication — support text and voice interaction.
- Assistance — help with supported Android tasks.
- Control — keep users in control through permissions and action approvals.

## Current preview capabilities

- Configurable Gemini, DeepSeek and custom provider settings.
- Local conversation history.
- Editable memory notes and structured person profiles.
- Context supplied to AI prompts.
- Voice interaction foundations.
- Approval queue for supported actions.
- Contact lookup and dialler handoff.
- SMS composer handoff.
- Flashlight action.
- User-triggered screen analysis workflow.
- Adult and kids companion mode foundations.

Some capabilities require permissions, provider configuration or compatible devices. See the project documentation for precise implementation status and limitations.

## Install on Android

1. Download the APK.
2. Open it on your Android phone.
3. Allow installation from that source if Android requests it.
4. Tap Install.
5. Open NOVA.

This is a debug/preview APK, not a production Play Store release.

## Configure Gemini

1. Visit https://aistudio.google.com/apikey
2. Sign in with Google.
3. Create or select a project.
4. Create an API key.
5. Open NOVA Settings.
6. Select Gemini under AI Voice Provider / API Keys & Connection Tests.
7. Paste the key, select an available model and save.
8. Run the connection test.

Google offers a limited free tier for eligible models. Usage limits vary, and free-tier data-use terms should be reviewed before sending private information.

Pricing:
https://ai.google.dev/gemini-api/docs/pricing

## Configure DeepSeek

1. Visit https://platform.deepseek.com/
2. Create an account and generate an API key.
3. Check current pricing and account requirements.
4. Select DeepSeek in NOVA Settings.
5. Enter the key, select the configured model, save and test.

## Documentation

- Project overview: README.md
- Installation: INSTALLATION.md
- Feature status: FEATURES.md
- Future roadmap: ROADMAP.md
- Security: SECURITY.md

## Limitations

Advanced semantic memory, automatic Google Drive synchronization, voice cloning, fully animated lip-sync avatars and fully autonomous agents are not claimed as completed features.

The build has been compiled successfully, but this does not guarantee every feature works on every device. Please report reproducible issues without including private API keys or personal data.

## Privacy

Use your own API key. AI prompts may be sent to the selected provider. Review provider terms and do not submit confidential information unless you understand the data-use policy.

NOVA is an independent project and is not an official Google or DeepSeek product.
