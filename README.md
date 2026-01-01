# Mastering TypeScript Skill

Master enterprise-grade TypeScript development with type-safe patterns, modern tooling, and framework integration.

## Overview

This skill provides comprehensive guidance for TypeScript 5.9+ development, covering:

- **Type System Mastery**: Generics, mapped types, conditional types, satisfies operator
- **Enterprise Patterns**: Error handling, validation with Zod, project architecture
- **React Integration**: Type-safe components, hooks, state management (Zustand, Redux Toolkit)
- **NestJS Development**: Scalable APIs, DTOs, authentication, RBAC
- **Modern Toolchain**: Vite 7, pnpm, ESLint 9 flat config, Vitest
- **Cross-Language Insights**: TypeScript compared with Java, Python, C#

## Quick Start

```bash
# Initialize TypeScript project with ESM
pnpm create vite@latest my-app --template vanilla-ts
cd my-app && pnpm install

# Configure strict TypeScript
cat > tsconfig.json << 'EOF'
{
  "compilerOptions": {
    "target": "ES2024",
    "module": "ESNext",
    "moduleResolution": "bundler",
    "strict": true,
    "noUncheckedIndexedAccess": true,
    "exactOptionalPropertyTypes": true
  }
}
EOF
```

## When to Use This Skill

Use when:
- Building type-safe React, NestJS, or Node.js applications
- Migrating JavaScript codebases to TypeScript
- Implementing advanced type patterns (generics, mapped types, conditional types)
- Configuring modern TypeScript toolchains
- Designing type-safe API contracts with Zod validation

## Installing with Skilz (Universal Installer)

The recommended way to install this skill across different AI coding agents is using the **skilz** universal installer.

### Install Skilz

```bash
pip install skilz
```

### Claude Code

Install to user home (available in all projects):
```bash
skilz install -g https://github.com/SpillwaveSolutions/mastering-typescript-skill
```

Install to current project only:
```bash
skilz install -g https://github.com/SpillwaveSolutions/mastering-typescript-skill --project
```

### OpenCode

```bash
skilz install -g https://github.com/SpillwaveSolutions/mastering-typescript-skill --agent opencode
```

### Gemini

```bash
skilz install -g https://github.com/SpillwaveSolutions/mastering-typescript-skill --agent gemini
```

### OpenAI Codex

```bash
skilz install -g https://github.com/SpillwaveSolutions/mastering-typescript-skill --agent codex
```

## Skill Contents

- **SKILL.md** - Main skill documentation with quick reference
- **references/** - Detailed reference documentation
  - `type-system.md` - Complete type system guide
  - `generics.md` - Advanced generics patterns
  - `enterprise-patterns.md` - Error handling, validation, architecture
  - `react-integration.md` - React + TypeScript patterns
  - `nestjs-integration.md` - NestJS API development
  - `toolchain.md` - Modern build tools configuration
- **assets/** - Templates and starter files
  - `tsconfig-template.json` - Strict enterprise config
  - `eslint-template.js` - ESLint 9 flat config
- **scripts/** - Utility scripts
  - `validate-setup.sh` - Verify TypeScript environment

## Version Information (December 2025)

| Tool | Version | Purpose |
|------|---------|---------|
| TypeScript | 5.9+ | Type checking and compilation |
| Node.js | 22 LTS | Runtime environment |
| Vite | 7.x | Build tool and dev server |
| pnpm | 9.x | Package manager |
| NestJS | 11.x | Backend framework |
| React | 19.x | Frontend library |
| ESLint | 9.x | Linting with flat config |
| Vitest | 3.x | Testing framework |

## Key Features Covered

### Type System
- Union and intersection types
- Discriminated unions for type-safe branching
- Type guards and type narrowing
- The `satisfies` operator for safer type checking
- Template literal types

### Generics
- Generic functions, interfaces, and classes
- Generic constraints with `extends`
- Mapped types and key remapping
- Conditional types with `infer`
- Variadic tuple types

### Enterprise Patterns
- Result/Either types for error handling
- Zod schema validation
- Branded types for domain modeling
- Feature-based project organization

### Framework Integration
- React: Typed components, hooks, Context API
- NestJS: Controllers, services, DTOs, guards
- State management: Zustand, Redux Toolkit

## License

MIT

## Author

Richard Hightower - Based on "Mastering Modern TypeScript" book content
