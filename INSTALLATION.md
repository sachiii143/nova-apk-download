# NOVA 1.4.0 — Complete Installation and Setup Guide

## Before you start

You need:
- An Android phone.
- Internet access.
- The NOVA APK.
- Your own Gemini or DeepSeek API key.

Download:
https://github.com/sachiii143/nova-apk-download/releases/latest

## Part 1 — Install the APK

1. Open the download link on your phone.
2. Download `NOVA-1.4.0.apk`.
3. Open Downloads or your file manager.
4. Tap the APK.
5. If Android blocks the installation, open the option to allow installation from this source for your browser or file manager.
6. Return to the installer and tap Install.
7. Open NOVA.

Only install APKs from a source you trust. Android may display a warning because this preview APK is not distributed through Google Play.

## Part 2 — Create a free Gemini API key

Official page:
https://aistudio.google.com/apikey

1. Sign in with your Google account.
2. Open API Keys.
3. Create or select a project.
4. Create an API key.
5. Copy the key.

Google's Gemini API free tier has model-specific limits and eligibility. It is not unlimited. Some models require billing.

Pricing and free-tier information:
https://ai.google.dev/gemini-api/docs/pricing

Privacy note: Google states that content submitted through the free tier may be used to improve its products. Do not send confidential information without reviewing the terms.

## Part 3 — Add the Gemini key to NOVA

1. Open NOVA.
2. Open Settings.
3. Find AI Voice Provider / API Keys & Connection Tests.
4. Select Gemini.
5. Paste your Gemini API key.
6. Select an available model.
7. Save.
8. Run the connection test.
9. Return to chat and send a test message.

If the connection fails:
- Check the key for missing characters or spaces.
- Check your internet connection.
- Confirm the selected model is available to your account.
- Check the current Google AI Studio quota and service status.
- Review the error shown by NOVA.

## Part 4 — Configure DeepSeek (optional)

Official platform:
https://platform.deepseek.com/

1. Create or sign in to your account.
2. Generate an API key.
3. Check current API pricing and account requirements.
4. Open NOVA Settings.
5. Select DeepSeek.
6. Enter the key.
7. Select the configured model.
8. Save and test.

DeepSeek API usage may be chargeable. Check its official pricing before using it.

## Part 5 — Permissions

NOVA may request Android permissions when you use particular features.

- Microphone: voice interaction.
- Contacts: contact lookup for supported actions.
- Notifications: reminders and notifications.
- Accessibility: supported screen-assistant actions, if enabled.

Grant permissions only when you understand why they are needed. You can manage them later through Android Settings.

## Part 6 — Memory

Use NOVA's memory and profile settings to add information you want the assistant to use in future conversations.

Review saved notes and profiles for accuracy. Do not assume every conversation is permanently stored or that all memory categories are backed up to Google Drive.

## Part 7 — Test NOVA

Try these checks:

1. Send a normal text message.
2. Confirm the selected provider responds.
3. Test voice interaction if microphone permission is enabled.
4. Add a memory note and check whether relevant context is used later.
5. Try a supported device action and inspect its approval prompt.
6. Test the connection again if you change providers.

## Troubleshooting

**APK will not install**
- Confirm the download completed.
- Check that Android allows installation from the app used to download it.
- Remove an older conflicting debug build if Android reports a signature conflict. Uninstalling may remove local app data, so back up anything important first.

**API key rejected**
- Generate a fresh key from the provider's official dashboard.
- Check that the correct provider is selected.
- Check model availability and account quota.
- Never send your key to support or publish it in an issue.

**NOVA connects but does not respond**
- Check internet access.
- Check provider status and quota.
- Confirm the selected model and endpoint are correct.

**A feature is unavailable**
- Some features are previews, permission-dependent or still under development. See FEATURES.md.

## Important

This is a debug/preview build. It is not a final production release. Use it for testing and feedback, not for safety-critical tasks.

The user is responsible for API usage and any charges from third-party providers.
