# Connected Experience — Vision Prototype

UX vision prototype screens for **UIESTRAT-84**: a unified Search → Downloads → Support → Case journey inside the Hybrid Cloud Console.

## 🔗 Live Prototype

**[View the prototype →](https://yichen1yu.github.io/connected-experience-vision/)**

## Screens

| # | Screen | Beat | Description |
|---|--------|------|-------------|
| 1 | Masthead AI Search | Beat 1 | Expanded search bar with AI "Ask Red Hat" summary, CVE results, advisories, KB articles |
| 2 | Search Results | Beat 1–2 | Full results page with filter chips, AI summary banner, Downloads service card |
| 3 | Downloads | Beat 2 | Downloads page with entitlement banner, architecture pre-filled from Insights |
| 4 | Support Agent | Beat 3 | Conversational side-panel agent with session context and KB citation cards |
| 5 | Case Creation | Beat 4 | Pre-filled support case with ~22 min saved from auto-populated context |

## Related Artifacts

- [Vision Narrative (Google Doc)](https://docs.google.com/document/d/1bxTTfsmfx9pWfXyNJMKTcmANb8ZqbSoK0dN6GW8vcOk/edit?tab=t.8k73tggmb8me)
- [UIESTRAT-84 (Jira)](https://redhat.atlassian.net/browse/UIESTRAT-84)

## Tech

- Standalone HTML — no build step required
- [PatternFly 6](https://www.patternfly.org/) CDN for design tokens and typography
- Red Hat Text / Display / Mono fonts via Google Fonts
- Custom `hcc-` prefixed classes for HCC console chrome (masthead, sidebar)
