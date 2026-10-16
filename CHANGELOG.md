# Changelog

## 1.1.0 (October 2026)

- Focused on three assistants: Claude, ChatGPT and Microsoft Copilot. Gemini and GitHub Copilot (Copilot CLI and VS Code) are no longer covered.
- New `docs/install/microsoft/` folder, with one page for each Microsoft Copilot product: Copilot Cowork, Copilot Studio, Agent Builder, one chat, and admin rollout.
- New Copilot Studio page: upload the seven skills to an agent, step by step.
- New page on the Humantic AI agent from the Microsoft Marketplace, and the two ways to get the skills next to it.
- The single-skill download folder `dist/one-skill/chatgpt-copilot-gemini/` is now `dist/one-skill/chatgpt-microsoft/`. The files in it are the same.
- The ChatGPT desktop route still installs through Codex. Nothing about it changed.

## 1.0.0 (October 2026)

- Seven skills: buyer-read, meeting-prep, pursuit-plan, prospecting, sales-email, buying-committee and expansion-play.
- Installs as one plugin in Claude, ChatGPT, Codex, Microsoft Copilot Cowork and GitHub Copilot.
- One install guide per assistant, in `docs/install/`.
- Ready-made downloads in `dist/`, built from `skills/` by `scripts/build-packages.py`.
- The Copilot Cowork package passes all 59 of Microsoft 365 Agents Toolkit's validation rules.
- The 55-prompt library moved into `prompts/`.

## 0.1.0 (September 2026)

- First release of the seven skills, for Claude.
- The 55-prompt library.
