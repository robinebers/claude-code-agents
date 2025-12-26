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
Next.js 16 frontend development agent that helps you:
- Create pages, layouts, and components
- Build API routes and Server Actions
- Set up data fetching with proper caching
- Refactor code following modern patterns
- Enforce Next.js 16 and React 19 best practices
