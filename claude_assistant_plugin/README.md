# Godo4NewbiAI — AI Assistant for Godot 4

**Godo4NewbiAI** is a free AI-powered plugin for Godot 4 that integrates directly into the editor.
Ask questions, fix bugs, generate GDScript — and even create scenes and nodes automatically, without ever leaving Godot.

> Developed by **xStrix**
> Powered by [Claude (Anthropic)](https://www.anthropic.com). Requires your own API Key.

---

## Features

### 💬 AI Chat inside the Editor
Chat with Claude AI directly from the bottom panel of Godot 4.
Ask anything about GDScript, nodes, scenes, physics, shaders, and more.

### ▶ Run EditorScripts with One Click
When you ask Claude to create a scene or add nodes, it generates a ready-to-run **EditorScript**.
Press **Run in Godot** and the scene is built automatically — no copy-paste needed.

**Examples of what Claude can do for you:**
- "Create a Player scene with CharacterBody2D, Sprite2D and CollisionShape2D"
- "Add a PointLight2D to the current scene with orange color"
- "Create a Game Manager autoload script"

### 📖 Share Your Open Script as Context
Click the **📖** button to send your currently open script to Claude.
Then ask: "Is there a bug here?" or "Optimize this function" — Claude already knows your code.

### 🐛 Paste Errors Directly
Click **🐛**, paste the error from the Output panel, and get an immediate fix with explanation.

### 💾 Snippet Library
Save any code block Claude generates with one click.
Find it again in the Snippet tab whenever you need it.

### 🕐 Persistent Chat History
Conversations are saved between sessions.
Reopen Godot and pick up exactly where you left off.

---

## Installation

1. Download and extract the plugin
2. Copy the `addons/claude_assistant` folder into your Godot project root
3. Open Godot: Project > Project Settings > Plugins
4. Find **Godo4NewbiAI** and click **Enable**
5. The Godo4NewbiAI tab appears at the bottom of the editor

---

## Setup API Key

1. Get your API Key at https://console.anthropic.com
2. In the plugin dock, click the gear button
3. Paste your key and click Save

The API Key is saved locally in your project settings and never shared.
Usage costs depend on your Anthropic plan — check https://www.anthropic.com/pricing

---

## Usage Examples

| What you type | What happens |
|---|---|
| "Create a 2D platformer Player scene" | EditorScript builds the scene instantly |
| "Why do I get invalid get index error?" + bug button | Claude explains and fixes it |
| "How do I detect collision with a wall?" | GDScript code with explanation |
| Share script + "Refactor this to use signals" | Claude rewrites your open script |

---

## Requirements

- Godot 4.x (tested on 4.2+)
- An Anthropic API Key (https://console.anthropic.com)
- Internet connection

---

## License

MIT License — Copyright (c) 2026 xStrix

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.

---

## Credits

Created by **xStrix**
Built using the Anthropic Claude API (https://www.anthropic.com).
This plugin is not affiliated with or endorsed by Anthropic or the Godot Foundation.
