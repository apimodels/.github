# APIMODELS

APIMODELS (apimodels.app) is a reliable, affordable multimodal AI API gateway for indie developers, creators, small studios and the AI agents they run. One API key and OpenAI- and Anthropic-compatible endpoints reach 180+ image, video, audio and language models, including Claude Opus 5.5, Claude Sonnet 5.5, GPT Image 2, Seedance 2.5, MiniMax H3, Kling V3, Wan 3.0 and Nano Banana. Major models fail over across providers automatically, failed calls are not charged, and an MCP server connects it to Claude Code, Cursor and Codex. Billing is pay per use.

[Website](https://apimodels.app) · [Models](https://apimodels.app/models) · [API docs](https://apimodels.app/docs)

```bash
curl https://api.apimodels.app/v1/chat/completions \
  -H "Authorization: Bearer $APIMODELS_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model": "claude-opus-5-5", "messages": [{"role": "user", "content": "Hello"}]}'
```

## Open prompt libraries

Each library credits the people who wrote the prompts and links to the original posts. The same collections, with the images and videos playing inline, are on apimodels.app.

| Repository | What's inside |
| --- | --- |
| [claude-opus-5-5-video-prompts](https://github.com/apimodels/claude-opus-5-5-video-prompts) | 60 real videos made with Claude Opus 5.5, six workflows with templates, and our own reproducible run |
| [awesome-seedance2.5-prompts](https://github.com/apimodels/awesome-seedance2.5-prompts) | Seedance 2.5 video prompts, each shown next to the clip it produced |
| [stunning-minimax-h3-prompts](https://github.com/apimodels/stunning-minimax-h3-prompts) | MiniMax H3 (Hailuo 3) video prompts, each with a clip you can watch |
| [gpt-image-2-prompts](https://github.com/apimodels/gpt-image-2-prompts) | Bilingual GPT Image 2 prompts with the images they generated, as CSV and JSON |
| [gpt-image-2-5-prompts](https://github.com/apimodels/gpt-image-2-5-prompts) | GPT Image 2.5 (Flare and Sunburst) prompts, each with the image it produced |

## Use it from code and agents

- [apimodels-api-demo](https://github.com/apimodels/apimodels-api-demo): curl, Node.js and Python examples for image, video, chat and audio models.
- [apimodels-apidocs](https://github.com/apimodels/apimodels-apidocs): base URL per SDK and the native endpoints.
- [apimodels-mcp](https://github.com/apimodels/apimodels-mcp): MCP server (npm `apimodels-mcp`), listed in the official MCP Registry.
- [apimodels-skill](https://github.com/stimQQ/apimodels-skill): Agent Skills for Claude Code and other coding agents.
