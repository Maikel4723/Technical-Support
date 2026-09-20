# Technical Support Workbench

A Vite + React technical-support workspace based on the Technical Support Assistance concept.

## Current frontend
- Dashboard with active cases, utilities, guides and quick actions
- Cases workspace with two editors side-by-side:
  - Case information / troubleshooting notes
  - Customer email
- Dutch / English workspace language selector
- Word-like customer-mail editor surface
- Utilities library with categories, create/edit/delete and insertion into mail
- Reusable mail templates
- Guide import UI for PDF, DOCX, TXT, Markdown and HTML
- Settings page prepared for secure AI integrations
- Responsive desktop/tablet/mobile layout

## Run locally
```bash
npm install
npm run dev
```

## Next production layer
The UI currently uses browser-local state so it works without exposing credentials. The intended next layer is a secure backend with authentication, PostgreSQL persistence, document parsing, full-text/vector search, server-side language checking, and Microsoft Copilot/Copilot Studio integration.

Never put Microsoft, AI-provider or other private API credentials in frontend source code.

Repository: https://github.com/Maikel4723/Technical-Support