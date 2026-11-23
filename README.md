# PromptHub

A quick prompt builder for coding with Claude across many chats. One offline HTML file: no install, no server, no libraries.

Open `PromptHub.html` in any browser (phone or desktop) and follow the 1-2-3 steps:

1. **Where are you?** New project · New chat · Same chat · Ending chat
2. **What do you want?** Pick a task type and type one line
3. **Copy prompt** and paste it into Claude

## Why

Long chats use a lot of tokens, so it's common to start a fresh chat and carry on. PromptHub keeps each project's rules, decisions, rejected ideas and the last handoff note, and puts them into every new-chat prompt, so Claude builds on top of existing code instead of breaking it.

## Features

- **Consistent / Open mode:** change only what's asked, or allow Claude to propose improvements first
- **Task types:** Feature, Bug fix, Plan only, Review, Tidy up, Question
- **Same prompt structure every time** (XML tags, context first, task last) for predictable results
- **Handoff:** ask Claude for a handoff note, paste it back, and it fills the next new-chat prompt
- **Fill from Claude:** fill a project's details from an existing chat or from the code file alone
- **History, backup export/import**, works offline; data stays on your device

## Privacy

Everything is stored in your browser's local storage on your device. Nothing is sent anywhere. Use **Export backup** to keep a copy or move to another device.
