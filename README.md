# Write Buddy ✍️

An English writing assistant for Korean learners: hints when you get stuck, plus light grammar corrections.

## Features
- **Hint:** press `⌘ ;` (Ctrl + ; on Windows) or the 💡 button next to the cursor, and a faint next-word suggestion appears. Press again for a different word, `Tab` to accept, `Esc` to dismiss.
- **Korean words allowed:** if you don't know a word, write it in Korean, e.g. `I want to 사과하다`. The hint suggests the English word to replace it.
- **Grammar correction:** finish a sentence with `.`, `?` or `!`. Errors get a red wavy underline, and the fix appears right below the sentence. `Tab` applies all fixes.
- **More natural phrasing:** only for sentences that sound clearly awkward, it suggests a more natural version.
- **Correction level:** choose between "꼭 필요한 것만" (only what's necessary) and "조금 더" (a bit more).

## Setup
1. Get an API key from the [Anthropic Console](https://console.anthropic.com/settings/keys).
2. Open the app, click ⚙️ in the top-right corner, enter the key, and save.
3. The key is stored only in that browser's localStorage and is sent only to `api.anthropic.com`.

The default model is Claude Haiku 5.5, which costs well under $1 a month for personal use.

## Deployment
GitHub Pages serves the single `index.html` file. There is no build step.
