# NOVA — Feature and Implementation Status

This document distinguishes current implementation foundations from future goals.

## Current implementation foundations

| Area | Current status |
|---|---|
| Android application | Implemented preview |
| Gemini / DeepSeek / custom provider settings | Present in settings; provider compatibility depends on configuration |
| API key storage | Uses Android encrypted preferences |
| Conversation history | Local bounded history |
| Editable memory notes | Implemented |
| Structured person profiles | Implemented |
| Memory context in prompts | Implemented using profile/context matching |
| Tool argument validation | Basic validation implemented |
| Pending action approval queue | Implemented in the inspected ViewModel flow |
| Contact lookup | Implemented for supported workflows |
| Phone call | Opens dialler; does not silently place a call |
| SMS | Opens message composer; user completes sending |
| Flashlight | Supported action |
| Screen assistant | User-triggered screenshot analysis workflow |
| Avatar import | Image/video import settings exist |
| Adult / kids modes | Mode and separate memory foundations exist |
| Manual document-folder backup | Limited JSON backup workflow |

## Important technical limitations

### Memory
Conversation history is bounded. Profile retrieval uses simple keyword matching rather than a full vector database or embedding search.

### Cloud backup
The manual document-folder backup is not automatic Google Drive OAuth synchronization. The current backup payload does not represent every memory category.

### Screen assistant
Screen content is not continuously streamed by default. Analysis is user-triggered. A screenshot sent for analysis may be transmitted to the configured AI provider.

### Device actions
Action validation is basic. Approval is important, but this should not be treated as a complete security boundary or a guarantee that every possible action is safe.

### Voice and avatar
Voice interaction components exist. A fully animated talking face, reliable lip-sync and voice cloning are not established as completed features.

### External integrations
Weather, music and other external services should not be advertised as working unless individually implemented and tested.

## Testing status

This repository contains a preview APK built successfully with Gradle. A successful build does not prove every feature works on every Android device.

Fresh-device installation, provider tests, permission tests, security review and regression testing remain necessary before a production release.
