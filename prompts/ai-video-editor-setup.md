# Setup prompt – Local AI Video Editor

Transcribed from a screenshot. Copy everything inside the box below and paste it into
Claude Code (or Codex) while it is running **inside an empty `AI Video Editor` folder on your computer**.

```text
Help me build a local AI video editor on my computer, inside this AI Video Editor folder. Start by checking my operating system and what's already installed.

Create four folders:
• Raw - my unedited recordings.
• Projects - one folder for each video, with its work and exports together.
• Signature Style - my branding, examples and saved styles.
• Setup - the editor's tools, instructions and setup notes.

Use these official sources:
• FFmpeg: https://ffmpeg.org/download.html
• Python: https://www.python.org/downloads/
• Node.js: https://nodejs.org/en/download
• HyperFrames: https://github.com/heygen-com/hyperframes
• WhisperX: https://github.com/m-bain/whisperX
• yt-dlp: https://github.com/yt-dlp/yt-dlp
• Playwright, if needed for browser checks: https://github.com/microsoft/playwright

Read their current install instructions. Use versions that work together on my computer. Install the published tools where available; only clone a repository if the setup needs its source. Keep project tools here where practical, and explain any computer-wide installation.

Install FFmpeg and ffprobe, a compatible Python, Node.js, HyperFrames and its core skills, WhisperX, yt-dlp and the browser needed for previews. Use a WhisperX setup that works with my operating system and hardware, with CPU mode available. Keep its Python environment separate from my other apps.

For HyperFrames, check the current instructions for "npx hyperframes skills update." Make sure the installed skills can be found by the app I'm using. If I use both Codex and Claude Code, connect the same project setup to both and check each separately.

Set up the available local HyperFrames sound effects. Check that the actual sound files are there, keep any required credits and test them. Use local tools for this workflow; don't add paid voice, avatar or media services unless I ask.

Check the tools actually run. Save the working versions and steps in Setup. Tell me what passed, what failed and any clicks you need from me. Explain it in plain English. Don't call setup finished just because the downloads finished.
```

## How to use it

1. Create a folder on your computer called `AI Video Editor`.
2. Open a terminal in that folder and start Claude Code (`claude`).
3. Paste the prompt above and approve the installs it asks about.
4. When it finishes, check the `Setup` folder for the notes on what was installed and what passed.
