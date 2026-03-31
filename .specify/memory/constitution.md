# doit_speckit Constitution

## Core Principles

### I. Clean Code
Write readable, maintainable, and well-structured code. Enforce consistent formatting, naming conventions, and modular organization. Prioritize clarity and simplicity over clever implementations. Code should be self-documenting through clear variable names and logical structure.

### II. Simple UX
Prioritize user experience with intuitive interfaces and minimal cognitive load. Every UI element must serve a clear purpose. Remove unnecessary features or complexity that doesn't directly serve user needs. Follow established design patterns for familiarity.

### III. Responsive Design
Ensure all UI components work seamlessly across desktop, tablet, and mobile devices. Use fluid layouts, flexible typography, and adaptive breakpoints. Mobile-first approach is preferred. All features must be accessible and functional on all screen sizes.

### IV. Minimal Dependencies
Keep the dependency tree lean and well-justified. Only add external packages when they provide significant value and cannot be reasonably implemented in-house. Review and audit dependencies regularly. Prefer built-in platform features over external libraries when practical.

## Technology Stack

**Framework & Runtime**: Next.js 16.2.1, React 19.2.4, React DOM 19.2.4

**Styling**: Tailwind CSS 4.x

**Language**: TypeScript 5.x

**Linting**: ESLint 9.x

All versions must align with the project's `package.json` at the time of development.

## Quality & Development Standards

- **Code Review**: All changes must be reviewed for adherence to Clean Code and Responsive Design principles.
- **No Testing**: Testing is explicitly excluded from this project. No unit tests, integration tests, or end-to-end tests are required or permitted as part of the development process.
- **Linting**: All code must pass ESLint checks before merge.
- **Performance**: Prioritize fast load times and smooth user interactions.

## Governance

This Constitution supersedes all other development guidance and practices. All features and implementations must comply with these four core principles. When principles appear to conflict, prioritize them in order: Clean Code → Simple UX → Responsive Design → Minimal Dependencies.

Amendments to this Constitution require explicit documentation and ratification. The constitution version will follow semantic versioning (MAJOR.MINOR.PATCH).

**Version**: 1.0.0 | **Ratified**: 2026-03-31 | **Last Amended**: 2026-03-31
