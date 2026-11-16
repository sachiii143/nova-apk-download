# NOVA — Product Vision and Development Roadmap

## Main motive

NOVA aims to become a personal AI companion rather than a simple question-and-answer chatbot.

The product direction is based on five principles:

1. **Memory:** Remember useful information that the user chooses to save.
2. **Context:** Use relevant personal context without forcing the user to repeat everything.
3. **Communication:** Support natural text and voice interactions.
4. **Assistance:** Help users complete everyday digital tasks.
5. **Control:** Keep users informed and require approval for consequential actions.

## Phase 1 — Android companion foundation

- Android Kotlin application.
- Configurable AI providers.
- Local conversation history.
- Editable notes and person profiles.
- Voice interaction foundations.
- Permission-aware device actions.
- Approval queue.
- Public preview and feedback process.

## Phase 2 — Memory intelligence

Planned:
- Better semantic memory retrieval.
- Embedding-based search.
- Memory importance and expiry controls.
- User-controlled memory editing and deletion.
- Reliable export and restore.
- Optional encrypted cloud synchronization.
- Memory source and provenance visibility.

## Phase 3 — Natural voice companion

Planned:
- Lower-latency real-time voice.
- Better interruption handling.
- Configurable voice personalities.
- Better speech recognition and speech output.
- Animated companion interface.
- Lip-sync and expressive avatar.

Voice cloning is not promised and would require appropriate consent, safeguards and technical review.

## Phase 4 — Personal assistant capabilities

Planned:
- More reliable task planning.
- User-defined workflows.
- Expanded device integrations.
- Transparent action history.
- Permission-aware automation.
- Better approval and undo flows.

## Phase 5 — Platform and ecosystem

Planned:
- Optional cloud services.
- Secure account and device synchronization.
- Integrations with supported productivity tools.
- Developer documentation and extension framework.
- Stable release channel.
- Automated testing and release pipelines.

## Security and quality milestones

Before production distribution:
- Replace debug signing with a protected release signing process.
- Review API key handling and provider network security.
- Review Android permissions and accessibility behavior.
- Add automated tests for memory and action approval.
- Test on multiple Android versions and devices.
- Provide a privacy policy and clear data handling disclosures.
- Verify backups, restore and data deletion.
- Add APK integrity verification and release checksums.

## Current stage

NOVA 1.4.0 is a preview build. Roadmap items are development goals, not completed functionality or guaranteed release dates.
