# LeetCode Solver

A browser-based AI tool that generates solutions for LeetCode problems using multiple AI providers. Runs fully client-side with no backend required.

A simple tool for pasting a problem, pasting starter code, and getting a complete solution back instantly.

---

Features:
- Supports multiple AI providers (Claude, OpenAI, DeepSeek)
- Secure API key storage using browser localStorage
- Clean dark themed interface
- One click solution generation
- Copy output to clipboard

---

How it works:
The tool sends your prompt directly from the browser to the selected AI provider.

It combines:
- Problem description
- Starter code

Then requests a full solution and returns only raw code.

---

Setup:
1. Download or clone the project
2. Open `index.html` in a browser
3. Click EDIT KEYS
4. Add API keys for your chosen provider
5. Select a provider
6. Paste a LeetCode problem
7. Click SOLVE

---

Supported Models:
- Claude: claude-sonnet-4-6
- OpenAI: gpt-4o
- DeepSeek: deepseek-chat

---

File Structure:
index.html

Single-file project.

---

Security:
API keys are stored only in browser localStorage.

They are only sent directly to the selected provider API and never stored on any server.

---

Limitations:
- Requires valid API keys
- Depends on browser fetch and clipboard support
- Model limits depend on provider

---

License:
MIT License

Copyright (c) 2026 Andrew Platania

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
