# Claude Plugins

A Claude Code plugin marketplace with AI coding plugins built by Robin Ebers.

## Installation

Add the marketplace:
```
/plugin marketplace add robinebers/claude-plugins
```

Install plugins:
```
/plugin install dedup-code-agent@claude-plugins
/plugin install nextjs-dev-agent@claude-plugins
```

## Available Plugins

### dedup-code-agent
Deep analysis of the codebase to identify sloppy AI code, like:
- Duplicate code and copy-pasted functions
- Unused exports and dead code branches
- Orphaned files with no imports
- Unnecessary dependencies in package.json

### nextjs-dev-agent
Next.js 16 frontend development with up-to-date patterns:
- proxy.ts instead of middleware.ts
- Cache Components with `"use cache"` directive
- Async request APIs (await cookies/headers/params)
- React 19.2 features (View Transitions, Activity, useEffectEvent)
- Tailwind CSS v4 configuration
