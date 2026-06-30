# Documentation project instructions

## About this project

- This is the **Leadey API documentation** site, built on [Mintlify](https://mintlify.com)
- Leadey is a B2B lead-generation / sales-engagement platform: signal-driven, multi-channel outreach across LinkedIn, email, and cold calling
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`; brand styling lives in `style.css`
- Brand foundations (tokens, logos, voice) come from the Leadey Design System — dark-canonical midnight navy (`#0C1122`) with a periwinkle (`#97A4D6`) accent and DM Sans type
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- Use **Cockpit** for the authenticated dashboard (not "app" or "console")
- Use **workspace** (not "project" or "account") for a customer's Leadey environment
- Use **Campaigns** for outreach sequences (internal route is `funnels`); don't expose the internal term
- Use **signals** / **buying signals** for intent detection (hiring surges, funding, tech-stack changes)
- Use **ICP** for Ideal Customer Profile
- Use **credits** for the prepaid usage balance
- Capitalize feature names in Title Case: Cockpit, Campaigns, Inbox, Opportunities, Scrapers, Leads
- Brand name is always **Leadey**

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings; Title Case for feature names and nav labels
- Use em-dashes ( — ) for asides — they're a signature of the brand voice
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, endpoints, and code references
- Confident, systems-oriented, outcome-driven tone — concrete claims, never hype
- **No emoji.** Personality comes from the palette, gradients, and the chevron mark

## Content boundaries

- Document the public API and customer-facing product surfaces only
- Don't document internal admin tooling, internal route names, or backend implementation details
- Keep example credentials obviously fake (e.g. `sk_live_your_key_here`)
