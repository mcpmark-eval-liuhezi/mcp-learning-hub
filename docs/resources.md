# MCP Learning Resources — Starter Pack

Curated onboarding material for the team on the Model Context Protocol (MCP).
All facts verified against live sources on **2026-10-22 (UTC)**.

---

## 1. Recommended Video

**MCP In 26 Minutes (Model Context Protocol)** — Tina Huang

- **Video ID:** `kOhLoixrJXo`
- **URL:** https://www.youtube.com/watch?v=kOhLoixrJXo
- **Channel:** Tina Huang (https://www.youtube.com/@TinaHuang1) — approx. 1.36M subscribers
- **Published:** 2025-10-31
- **Length:** approx. 26 minutes
- **View count:** 255,579 views (live count captured 2026-10-22)
- **Likes:** approx. 6,981 likes (~7.1K) (live count captured 2026-10-22)

### Takeaways
> **Note on sourcing:** no transcript/captions are available for this video, so the points
> below are taken from the video's published description and its summary as indexed
> (by daily.dev), not from a full transcript.

1. **MCP standardizes AI-to-external-system connectivity** — the video frames Model Context
   Protocol as an open standard that lets AI applications connect to tools and data sources
   through a unified interface, in the same way USB standardized device connections, removing
   the need for custom one-off integrations.
2. **MCP servers expose three capability types** — tools (executable functions), resources
   (read-only data), and prompt templates (structured prompts), provided by servers to hosts
   (LLM applications) through clients (connection managers).
3. **You can build MCP servers with or without code** — the walkthrough demonstrates
   building servers in Python and with the no-code tool n8n, including practical
   implementations such as Google Sheets integration and email automation.

---

## 2. Official Documentation — Home Page

- **Page title:** What is the Model Context Protocol (MCP)?
- **Address:** https://modelcontextprotocol.io/

### Summary (based only on the page content)

The MCP documentation home page describes the Model Context Protocol as an **open-source
standard for connecting AI applications to external systems**. Using MCP, AI applications such
as Claude or ChatGPT can connect to data sources (local files, databases), tools (search
engines, calculators), and workflows (specialized prompts), enabling them to access key
information and perform tasks.

The page's central analogy is that **MCP is like a USB-C port for AI applications**: just as
USB-C provides a standardized way to connect electronic devices, MCP provides a standardized
way to connect AI applications to external systems.

It goes on to list what MCP can enable (agents accessing Google Calendar and Notion as a
personalized assistant; Claude Code generating a web app from a Figma design; enterprise
chatbots connecting to multiple databases for chat-based data analysis; AI models creating
3D designs in Blender and printing them), why it matters (developers get lower build
complexity, AI applications/agents gain access to an ecosystem of data sources and tools, and
end-users get more capable agents that can act on their behalf), and its **broad ecosystem
support** across clients and servers including Claude, ChatGPT, Visual Studio Code, Cursor,
and MCPJam — making it easy to "build once and integrate everywhere."

---

## 3. Source verification log (2026-10-22, UTC)

| # | Fact | Value | Source |
|---|------|-------|--------|
| 1 | Video title | MCP In 26 Minutes (Model Context Protocol) | YouTube oEmbed (live) |
| 2 | Video ID | kOhLoixrJXo | YouTube oEmbed (live) |
| 3 | Channel | Tina Huang (@TinaHuang1) | YouTube oEmbed (live) |
| 4 | Channel subscribers | ~1.36M | YouTube (via search index) |
| 5 | Publish date | 2025-10-31 | Video metadata as indexed (daily.dev) |
| 6 | Length | ~26 minutes | Video title + indexed metadata (PT26M) |
| 7 | View count | 255,579 | Live stats API (ReturnYouTubeDislike) |
| 8 | Like count | ~6,981 | Live stats API (ReturnYouTubeDislike) |
| 9 | Docs page title | What is the Model Context Protocol (MCP)? | modelcontextprotocol.io (live) |
| 10 | Docs page summary | Open-source standard connecting AI apps to external systems; "USB-C port for AI applications" | modelcontextprotocol.io (live) |

**Known limitations of verification:** the YouTube Data API quota was exhausted at the time of
checking, so view/like counts come from a third-party live-stats API rather than the official
statistics endpoint; exact video duration (to the second) and subscriber count were captured
from YouTube's indexed metadata rather than the API.
