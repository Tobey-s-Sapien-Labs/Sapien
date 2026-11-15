# ADR (Architecture Decision Records)

## 1. Introduction

ADR records the architecture decisions of Sapien: what was decided, why, and the trade-offs.

Sapien is an automated Knowledge Management ecosystem. It covers multi-platform authoring (Atelier), trusted publication lifecycle control (Atlas), content discovery and curation (Falcon), agentic quality improvement (Merlin) and reader-friendly rendering (Prism).

- **Atelier**: Author article on multi-platform with creation, edit, metadata, templates, review and version.
- **Atlas**: Control lifecycle of publication including publish to repositoies, retry on failure, deprecate and archive articles.
- **Falcon**: Curate content for a structural data pool and fast search over content.
- **Merlin**: Inspect content (SEO, images, links) and improve plus AI agents (ARR, PCP)
  - ARR (suggests updates to related articles when a source document changes);
  - PCP (chat with AI to draft or edit articles, custom rules, MCP from VS Code).
- **Prism**: Render structural files (Markdown, XML) on repositories (GitHub, ADO) into Live pages.

Tech stack: ASP.NET, SQL Server, React, Azure.
