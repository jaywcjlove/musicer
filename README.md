<!--idoc:ignore:start-->
> [!TIP]
> Declaration: This project is not an open-source project. The repository serves as the official website, used to collect issues and user demands. This is done to save costs, because without an official website, the application cannot pass the review.
<!--idoc:ignore:end-->

<div align="center">
  <br />
  <br />
  <img src="./assets/logo.png" width="160" height="160">
  <h1>
    Musicer
  </h1>
  <!--rehype:style=border: 0;-->
  <p>
    <a href="./README.zh.md">简体中文</a> • 
    <a target="_blank" href="https://github.com/jaywcjlove/musicer/issues/new?template=bug_report.yml">Contact & Support</a> • 
    <a href="./CHANGELOG.md">Changelog</a>
  </p>
  <p>
    <a target="_blank" href="https://jaywcjlove.github.io/maslink/?id=6745227444" title="Musicer for macOS">
      <img alt="Musicer AppStore" src="https://jaywcjlove.github.io/sb/download/macos.svg" height="51">
    </a>
  </p>
</div>

![Musicer 1](./assets/screenshots-1.png)

![Musicer 2](./assets/screenshots-2.png)

![Musicer 3](./assets/screenshots-3.png)

![Musicer 3](./assets/musicer.gif)

![Musicer 4](./assets/musicer-2.gif)

Mini and convenient local music player, lightweight and practical, specially designed for playing local audio, supports a variety of common audio formats, enjoy your music anytime, anywhere!

### Features

- Support local audio file playback
- Waveform progress bar to display playback progress
- Customize player theme color
- One-click switch to mini mode
- Display and control player in the status bar

Supported formats: MP3, AIFF, AMR, WAV, CAF, AAC, AC3, FLAC, M4R, M4A, etc.

### Musicer, Ready for AI

Musicer supports the **[Model Context Protocol (MCP)](https://modelcontextprotocol.io)**. Connect it to an AI client such as Claude, Cursor, or Grok, then use natural language to search for music, play, pause, skip tracks, and read the currently playing track and its lyrics.

#### Configure in Grok

```bash
# Add the Musicer MCP server
$ grok mcp add Musicer \
  --transport stdio \
  --scope user \
  -- "/System/Applications/Musicer.app/Contents/MacOS/Musicer" --mcp
# Remove the Musicer MCP server
$ grok mcp remove musicer
# List configured MCP servers
$ grok mcp list
# Diagnose the Musicer MCP server connection
$ grok mcp doctor Musicer
```

Alternatively, configure it directly in `~/.grok/config.toml`:

```ini
[mcp_servers.musicer]
command = "/Applications/Musicer.app/Contents/MacOS/Musicer"
args = ["--mcp"]
enabled = true
```

You can also add the following to an MCP client configuration, such as Claude Desktop or Cursor:

```json
{
  "mcpServers": {
    "musicer": {
      "command": "/Applications/Musicer.app/Contents/MacOS/Musicer",
      "args": ["--mcp"]
    }
  }
}
```

<!--idoc:config:
title: Musicer - Mini and convenient local music player
-->