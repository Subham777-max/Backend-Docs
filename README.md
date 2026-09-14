# Backend Docs

A collection of backend engineering documentation, written as standalone HTML guides.

The goal of this repository is to keep backend concepts, implementation patterns, and reference material easy to read, navigate, and share in a browser. Each topic is maintained as an independent HTML document so it can be opened directly or hosted as a static site.

## Documentation

| Topic | Description |
| --- | --- |
| [Authentication Notes](authentication-notes.html) | Concepts and practical notes for implementing authentication in backend applications. |
| [Access and Refresh Tokens](access-refresh-tokens.html) | How access tokens and refresh tokens work, including token flow, storage, rotation, and implementation guidance. |

## Opening the documentation

Open any `.html` file directly in a browser, or serve the repository with a local static server:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Repository conventions

- Add each backend topic as its own standalone `.html` document.
- Keep navigation, examples, and styling inside the document so it remains portable.
- Add every new document to the **Documentation** table above.
- Prefer clear explanations, practical examples, and diagrams where they improve understanding.

## Scope

Planned documentation may cover authentication, authorization, APIs, databases, caching, queues, observability, security, deployment, and other backend engineering fundamentals.