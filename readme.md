\# LeetCode Solver



A simple browser-based tool that uses AI models to generate solutions for LeetCode problems. Everything runs client-side with no backend required, and you can choose between multiple AI providers using your own API keys.



\## Features



\- Supports multiple AI providers:

&#x20; - Anthropic Claude

&#x20; - OpenAI GPT

&#x20; - DeepSeek Chat

\- Stores API keys locally in the browser using localStorage

\- Clean dark-themed interface

\- Paste problem description and starter code

\- One-click solution generation

\- Copy generated code to clipboard



\## How It Works



The tool takes your LeetCode problem description and starter code, combines them into a prompt, and sends it directly from your browser to the selected AI provider. The response is displayed as raw code that you can copy and use.



\## Setup



1\. Download or clone this project

2\. Open the HTML file in any modern browser

3\. Click EDIT KEYS

4\. Add your API keys for the providers you want to use

5\. Select a provider from the dropdown

6\. Paste the problem description and starter code

7\. Click SOLVE



\## Notes



\- No server or backend is used

\- API keys are stored only in your browser localStorage

\- Requests are sent directly to the AI provider APIs

\- Requires internet connection for API calls



\## Supported Models



\- Claude: claude-sonnet-4-6

\- OpenAI: gpt-4o

\- DeepSeek: deepseek-chat



\## File Structure



This project is a single file:



index.html



\## Security



API keys never leave your browser except when sent directly to the selected provider API. Nothing is logged or stored remotely by this tool.



\## Limitations



\- Requires valid API keys from supported providers

\- Depends on browser support for fetch and clipboard APIs

\- Performance and token limits depend on the selected model



\## License



MIT License



Copyright (c) 2026 Andrew Platania



Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:



The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.



THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

