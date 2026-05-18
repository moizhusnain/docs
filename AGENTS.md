# Documentation project instructions

## About this project

- This is the **Okara** documentation site built on [Mintlify](https://mintlify.com)
- Okara is an AI CMO platform with specialized marketing agents (SEO, GEO, Reddit, LinkedIn, X, UGC, Coding, Writer, Chat)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mintlify dev` to preview locally
- Run `mintlify broken-links` to check links
- Images live in `/images/`, logos in `/logo/`, videos in `/videos/`

## Terminology

- Use **CMO** (not "AI CMO", "bot", or "assistant") when referring to the main Okara agent
- Use **Feed** (not "dashboard feed" or "task list") for the CMO's task stream
- Use **Terminal** for the CMO's reasoning/digest view
- Use **Company Panel** for the knowledge base panel
- Use **Analytics Window** for the metrics/SEO panel
- Use **agent** (lowercase) for specialized agents (SEO agent, GEO agent, Reddit agent, etc.)
- Use **GEO** (Generative Engine Optimisation) not "AEO" or "AI SEO"
- Product name: **Okara** (not "Okara AI", "Okara CMO", or "okara")

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings (not title case)
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- No Oxford-style over-explanation — readers are founders and marketers, not developers
- Avoid filler phrases: "simply", "just", "easy", "straightforward"

## Content boundaries

- Document user-facing features only — no internal admin or backend details
- Do not document pricing specifics (link to okara.ai instead)
- Do not promise specific AI model names or third-party integrations not yet live

## File structure

```
index.mdx                  — Getting Started (main landing page)
faqs.mdx                   — FAQs
platform/
  seo-agent.mdx            — SEO & GEO agent
  geo-agent.mdx            — GEO agent detail
  reddit.mdx               — Reddit agent
  linkedin-agent.mdx       — LinkedIn agent
  x-agent.mdx              — X (Twitter) agent
  ugc-agent.mdx            — UGC agent
  writer.mdx               — Writer agent
  coding-agent.mdx         — Coding agent
  chat.mdx                 — Chat
  team.mdx                 — Team management
  websites.mdx             — Website connections
  analytics-integrations.mdx — Analytics integrations
```
