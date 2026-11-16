<!-- NOVA-PRODUCT-VISION-START -->

# NOVA — One AI Platform, Two Personal Experiences

NOVA is an Android AI companion platform built around two experiences:

- **NOVA Kids:** A friendly learning companion for after-school conversations, homework guidance, everyday knowledge and new skills, with child safety and parental supervision as core requirements.
- **NOVA Personal:** A memory-inspired AI companion for adults, using user-provided personality profiles and authorized memories to create personalized conversations, with an on-screen avatar experience as a long-term goal.

**Main motive:** Make AI more personal and useful — helping children learn and grow, while helping adults preserve and revisit meaningful memories through transparent, user-controlled AI experiences.

NOVA is an AI simulation, not the actual person represented by a personality profile. Advanced avatar, voice and learning capabilities remain under development.

[Read the complete project vision](PROJECT-VISION.md)

<!-- NOVA-PRODUCT-VISION-END -->
# NOVA — Your Personal AI Companion for Android

<p align="center">
  <strong>A personal AI companion designed to understand context, remember information, communicate naturally and assist with everyday digital tasks.</strong>
</p>

<p align="center">
  <a href="https://github.com/sachiii143/nova-apk-download/releases/latest">Download NOVA for Android</a>
</p>

---

## 1. What is NOVA?

NOVA is an Android-based personal AI companion project built around a simple idea:

**An AI assistant should be more than a chatbot. It should become a useful, context-aware companion that can remember relevant information, communicate naturally and help users perform tasks with their permission.**

Traditional chatbots often treat every conversation as separate. NOVA is being developed to provide a more continuous experience through persistent personal information, conversation history, configurable AI providers, voice interaction and controlled device assistance.

NOVA is an independent project. It is not an official Google, Gemini or DeepSeek application.

## 2. Why was NOVA built?

The main motivation behind NOVA was to explore a more personal and practical form of AI.

The project aims to address several limitations of ordinary chatbot experiences:

- Repeating personal information in every conversation.
- Losing useful context between sessions.
- Having no convenient bridge between AI conversations and everyday phone tasks.
- Limited control over which AI provider powers the assistant.
- Lack of a clear approval step before consequential actions.
- The gap between a conversational AI and a genuinely useful personal assistant.

The long-term goal is to develop an assistant that understands the user's preferences, remembers information the user chooses to save, communicates through text and voice, and helps with tasks while keeping the user in control.

## 3. Main mission

**Build a personal AI companion that remembers, understands, communicates and assists — with privacy, transparency and user approval at its core.**

NOVA is intended to evolve step by step from an Android AI chat application into a more complete personal assistant platform.

## 4. What NOVA includes

The current project includes the following capabilities or implementation foundations. Actual availability can depend on the selected provider, permissions, device and build.

- AI chat with configurable provider settings.
- Gemini, DeepSeek and custom provider configuration in the settings interface.
- Local conversation history.
- Editable memory notes and structured person profiles.
- Personal context supplied to AI prompts.
- Voice interaction components.
- A tool/action approval queue.
- Contact lookup and phone dialler handoff.
- SMS composer handoff, with the user completing the send.
- Flashlight control.
- Screen-assistant workflow with user-triggered analysis.
- Avatar media import settings.
- Separate adult and kids companion modes.
- Local memory storage and a manual document-folder backup workflow.

See [FEATURES.md](FEATURES.md) for implementation details and limitations.

## 5. Download NOVA

**Latest Android download:**

https://github.com/sachiii143/nova-apk-download/releases/latest

Current preview release: **NOVA 1.4.0**

APK file: `NOVA-1.4.0.apk`

This is currently a debug/preview build. It is intended for testing, not represented as a final production release.

## 6. Installation and first-time setup

1. Open the download link on your Android phone.
2. Download `NOVA-1.4.0.apk`.
3. Open the downloaded file.
4. If Android asks, allow your browser or file manager to install unknown apps.
5. Tap Install.
6. Open NOVA.
7. Open Settings.
8. Find the AI Voice Provider / API Keys & Connection Tests section.
9. Select Gemini or DeepSeek.
10. Enter your own API key and select an available model.
11. Save the settings.
12. Run the connection test.
13. Return to the chat screen and test NOVA.

Full instructions: [INSTALLATION.md](INSTALLATION.md)

## 7. Get a Gemini API key

Google AI Studio provides a Gemini API key management page:

https://aistudio.google.com/apikey

General steps:

1. Sign in with your Google account.
2. Open the API Keys section.
3. Create or select a Google AI Studio project.
4. Create an API key.
5. Copy the key.
6. Open NOVA Settings.
7. Select Gemini.
8. Paste your key into the Gemini API key field.
9. Save and test the connection.

### Is Gemini API free?

Google offers a free Gemini API tier for eligible models, subject to model-specific usage limits and availability.

Free access is not unlimited. Limits can change. Some models and features require paid billing.

Important: Google's published pricing information states that content submitted through the free tier may be used to improve its products. Do not submit sensitive or confidential information unless you understand the applicable terms.

Check current pricing and limits:
https://ai.google.dev/gemini-api/docs/pricing

## 8. Use DeepSeek instead

Official DeepSeek platform:

https://platform.deepseek.com/

General steps:

1. Create or sign in to your DeepSeek account.
2. Open its API/platform section.
3. Generate an API key.
4. Check the current pricing and account requirements.
5. Open NOVA Settings.
6. Select DeepSeek.
7. Enter your key.
8. Save and test the connection.

DeepSeek API access and pricing are subject to DeepSeek's current terms. Do not assume it is free.

## 9. Memory and personalization

NOVA is designed to use more than the current message.

Its memory architecture includes:

- Recent conversation history.
- Editable memory notes.
- Structured person profiles.
- Personal details such as background, preferences, relationships and stories.
- Relevant context included in AI prompts.

The user should be able to review and edit information saved in the app.

Memory is currently based on local storage and structured context retrieval. It should not be confused with a fully implemented cloud-based semantic memory system.

Google Drive automatic synchronization is not currently claimed as a completed feature. The existing manual backup workflow has limitations and should not be treated as a complete backup of every memory category.

## 10. User approval and safety

NOVA is being developed around the principle that the user should remain in control.

Some device actions use an approval queue. Contact and messaging workflows can open the phone's dialler or message composer rather than silently completing the action.

Users should review permissions and approve only actions they understand.

## 11. Privacy and API keys

- Each user should use their own API key.
- Never share API keys publicly.
- Do not paste API keys into GitHub issues or public discussions.
- Configure keys inside the app's settings.
- The project uses Android encrypted local preferences for configured provider credentials.
- AI requests may send conversation content to the selected AI provider.
- Screen analysis can send the selected screenshot to the configured AI service.
- Review provider privacy policies before using the app with sensitive information.

Read [SECURITY.md](SECURITY.md).

## 12. Current limitations

NOVA is an evolving preview project.

The following should not be considered completed merely because they are part of the vision:

- Fully animated face-to-face avatar with reliable lip synchronization.
- Voice cloning or imitation.
- Automatic Google Drive OAuth synchronization.
- Complete semantic/vector memory retrieval.
- Fully autonomous background agents.
- Production-grade device automation across all Android applications.
- Fully integrated weather, music and external service execution.
- Google Play production distribution.

See [ROADMAP.md](ROADMAP.md).

## 13. Future vision

The long-term roadmap explores:

**A. Advanced memory**
- Better long-term personal memory.
- Semantic search and contextual retrieval.
- Memory editing, deletion and export controls.
- Optional encrypted cloud backup and synchronization.

**B. Natural communication**
- Improved real-time voice conversation.
- More natural interruption handling.
- Configurable voice and speaking style.
- Animated companion with lip synchronization.

**C. Personal AI intelligence**
- Better planning and reasoning.
- Context-aware proactive assistance.
- User-defined personas and profiles.
- Multiple AI provider support.

**D. Device assistance**
- Safer Android action execution.
- Expanded task queue and approval workflows.
- Integrations with supported apps and services.
- Transparent activity and action history.

**E. Platform development**
- Production signing and release automation.
- Better onboarding and diagnostics.
- Automated tests and security reviews.
- Optional services and integrations.

These are development goals, not promises that the features already exist.

## 14. Project architecture

NOVA is an Android application built using Kotlin.

The project is organized around:
- Android UI and settings.
- AI provider configuration and chat clients.
- Conversation and personal memory components.
- ViewModel-based application state.
- Tool/action validation and approval.
- Android services and permission-controlled capabilities.

The complete development source is maintained separately in the private repository:

https://github.com/sachiii143/nova-personal-ai-companion

## 15. Who is NOVA for?

NOVA is intended for people interested in:

- Personal AI assistants.
- Android development.
- AI-powered productivity.
- Persistent memory and personalization.
- Voice-first interactions.
- Responsible AI tool execution.
- Experimenting with multiple AI providers.

## 16. Feedback and contributions

Feedback is welcome.

Please use the Issues section of this public repository for download problems, installation problems and documentation feedback.

Do not post API keys, passwords, personal data or private screenshots containing sensitive information.

## 17. Disclaimer

NOVA is an independent experimental software project. It is provided as a preview and without a guarantee of uninterrupted operation or suitability for a particular purpose.

Users are responsible for their own API keys, provider charges, permissions and device security.

Google Gemini and DeepSeek are third-party services. Their names and trademarks belong to their respective owners.

---

**NOVA — More than a chatbot. A step toward a personal AI companion.**
