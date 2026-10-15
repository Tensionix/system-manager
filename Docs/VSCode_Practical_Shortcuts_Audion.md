# VS Code: practical shortcuts for Audion

**Contents**

- [Markdown / Preview](#markdown--preview)
- [Search / Replace / bulk edits](#search--replace--bulk-edits)
- [Terminal / command flow](#terminal--command-flow)
- [Navigation / layout](#navigation--layout)
- [Commands / settings / keybindings](#commands--settings--keybindings)
- [Files / editing](#files--editing)
- [Git / workspace life](#git--workspace-life)
- [My recommended practical set to memorize first](#my-recommended-practical-set-to-memorize-first)
- [Notes for your setup](#notes-for-your-setup)

Windows-focused cheat sheet for everyday work in Markdown, code, terminal, search, and navigation.

## Markdown / Preview

| Shortcut | What it does | Why it matters |
|---|---|---|
| `Ctrl + Shift + V` | Open Markdown Preview | Quickly view the current `.md` as rendered Markdown |
| `Ctrl + K`, then `V` | Open Markdown Preview to the side | Best mode for writing on the left and reading preview on the right |
| `Ctrl + Alt + V` | Paste image from clipboard *(Paste Image extension)* | Fast screenshot flow into Markdown notes |
| `Ctrl + S` | Save | Useful even with Auto Save enabled |

## Search / Replace / bulk edits

| Shortcut | What it does | Why it matters |
|---|---|---|
| `Ctrl + F` | Find in current file | Basic local search |
| `Ctrl + H` | Replace in current file | Quick local replacement |
| `Ctrl + Shift + F` | Search across files | Search in Hub / project / repo |
| `Ctrl + Shift + H` | Replace across files | Bulk replace across the workspace |
| `Alt + C` | Toggle Match Case | Search only exact letter case |
| `Alt + W` | Toggle Whole Word | Avoid partial matches |
| `Alt + R` | Toggle Regular Expression | Powerful pattern search |
| `Ctrl + Shift + J` | Toggle Search details | Include/exclude files, advanced filters |
| `Alt + Enter` | Open search results in Search Editor | Turns results into an editable/searchable editor view |

## Terminal / command flow

| Shortcut | What it does | Why it matters |
|---|---|---|
| ``Ctrl + ` `` | Toggle integrated terminal | Main terminal shortcut |
| `Ctrl + Shift + \\`` | Create new terminal | Open another terminal tab/session |
| `Ctrl + I` | Inline chat in editor or terminal *(if chat/Copilot features are enabled)* | Optional AI assist; useful only if you actually keep chat features available |
| `Ctrl + Alt + I` | Open Chat view *(if chat/Copilot features are enabled)* | Opens the full chat panel |

## Navigation / layout

| Shortcut | What it does | Why it matters |
|---|---|---|
| `Ctrl + B` | Toggle Sidebar | More screen space / bring Explorer back |
| `Ctrl + Shift + E` | Focus Explorer | Jump straight to files |
| `Ctrl + P` | Quick Open file | Fastest file open in large repos |
| `Ctrl + Tab` | Switch between open editors | Useful with many files open |
| `Ctrl + \\` | Split editor | Open a second editor pane |
| `Ctrl + W` | Close active editor | Fast tab cleanup |

## Commands / settings / keybindings

| Shortcut | What it does | Why it matters |
|---|---|---|
| `Ctrl + Shift + P` | Command Palette | The master shortcut: almost everything starts here |
| `Ctrl + ,` | Open Settings | Fast access to settings UI |
| `Ctrl + K`, then `Ctrl + S` | Open Keyboard Shortcuts | Search, learn, and remap keys |

## Files / editing

| Shortcut | What it does | Why it matters |
|---|---|---|
| `Ctrl + S` | Save file | Still useful for “save now” muscle memory |
| `Ctrl + /` | Toggle line comment | Fast commenting in many languages |
| `Alt + Up / Down` | Move line up/down | Great for text, Markdown, lists, shell commands |
| `Shift + Alt + Up / Down` | Copy line up/down | Duplicate blocks fast |
| `Ctrl + D` | Add next match to selection | Great for repeated word edits |
| `Ctrl + Shift + L` | Select all matches of current selection | Bulk editing in one shot |
| `F2` | Rename symbol | Safer rename in supported languages |
| `Ctrl + Space` | Trigger suggestion | Force IntelliSense/manual completion |

## Git / workspace life

| Shortcut | What it does | Why it matters |
|---|---|---|
| `Ctrl + Shift + G` | Open Source Control | Quick Git panel access |
| `Ctrl + Shift + X` | Open Extensions | Install/update/check extensions |

## My recommended practical set to memorize first

1. `Ctrl + Shift + P` — Command Palette
2. `Ctrl + P` — open file
3. `Ctrl + Shift + V` — Markdown Preview
4. `Ctrl + K`, `V` — Preview to the side
5. ``Ctrl + ` `` — terminal
6. `Ctrl + Shift + F` — global search
7. `Ctrl + Shift + H` — replace in files
8. `Ctrl + B` — sidebar
9. `Ctrl + ,` — settings
10. `Ctrl + K`, `Ctrl + S` — keyboard shortcuts
11. `Ctrl + W` — close editor
12. `Ctrl + Alt + V` — paste image into Markdown

## Notes for your setup

- If you keep Copilot/chat disabled, treat `Ctrl + I` and `Ctrl + Alt + I` as optional and ignore them.
- For Markdown work, the strongest daily pair is:
  - `Ctrl + Shift + V`
  - `Ctrl + K`, `V`
- For large note vaults and code repos, the strongest search pair is:
  - `Ctrl + Shift + F`
  - `Ctrl + Shift + H`
- Your Kit works for both portable and installed VS Code. The main difference is only where `settings.json` lives; the shortcuts and extensions themselves remain the same.
