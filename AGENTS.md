# Working with this skill repository

This repository packages a reusable UI interaction skill. It does not contain an application or the reference video.

- When a user requests a matching UI interaction, read `skills/ui-interaction-patterns/SKILL.md` and only the relevant reference sections before implementation.
- Select skills from the user's goal; users do not need to remember skill names. Briefly state the chosen skill and purpose in Chinese.
- Match existing project conventions. Do not apply all six patterns by default or create a demo when the user only requests installation.
- Keep `agents/openai.yaml` implicit invocation enabled. Validate the skill after edits and check referenced files exist.
- Publish only skill/package files; exclude local account configuration, reference videos, provider downloads and analysis artifacts.
