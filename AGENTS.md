# farmingmode

- Purpose: farming application.
- Stack: unspecified.
- Folder map: `readme.md` describes the project. No source directories are present.
- Dev, test, and build: no commands are defined.

## Working rules

- Search with `rg` before reading files. Read only the line ranges you need.
- Skip `node_modules/`, `dist/`, and lockfiles during routine inspection.
- Batch shell commands with `&&`. Pipe long output to `tail -40` and preserve command failures with `set -o pipefail`.
- Keep diffs small. Keep final replies to five lines or fewer, with no recaps.

## Browser tasks

- For any web task, write and run a headless Playwright script using Chromium in `/workspace/scripts`. Save screenshots there.
- Never ask to control the user's PC.
- Use `/workspace/.auth/<site>.json` for saved logins. Never commit those files.
- Stop and ask before handling CAPTCHA or 2FA, making payments, signing up, or posting.
