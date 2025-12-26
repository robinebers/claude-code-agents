# Claude Plugins

A Claude Code plugin marketplace with AI coding plugins built by Robin Ebers.

## Installation

Add the marketplace:
```
/plugin marketplace add robinebers/claude-plugins
```

Install plugins:
```
/plugin install codebase-dedup-analyzer@claude-plugins
/plugin install next-dev@claude-plugins
```

## Available Plugins

### codebase-dedup-analyzer
Deep analysis of codebases to identify:
- Duplicate code and DRY violations
- Unused exports and dead code
- Orphaned files and functions
- Unnecessary dependencies

### next-dev
Next.js 16 frontend development agent with:
- proxy.ts (replacing middleware.ts)
- Cache Components and new caching APIs
- Async request APIs (cookies, headers, params)
- React 19.2 patterns (View Transitions, useEffectEvent, Activity)
