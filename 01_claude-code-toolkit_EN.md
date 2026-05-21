ARVEN EN
Claude Code Toolkit
11 Battle-Tested Prompt Templates · Full Development Lifecycle
$29

From architecture to deployment — zero context switching.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

WHAT'S INSIDE

11 production-tested prompt templates covering the complete development lifecycle.
Each template is designed to work with Claude Code, Cursor, Copilot, or Windsurf.
Works with any programming language or framework.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #1 — PROJECT BOOTSTRAP

USE THIS FIRST in every new project.

PROMPT:
"You are a senior software architect. Analyze the following project requirements and create: 1) folder structure, 2) tech stack recommendation with reasoning, 3) CLAUDE.md memory file, 4) first 3 implementation tasks.

Requirements: [DESCRIBE YOUR PROJECT]

Constraints: [BUDGET/TIME/TEAM/PERFORMANCE REQUIREMENTS IF ANY]"

ARVEN TIP: The CLAUDE.md file is critical. It persists context across Chat sessions, eliminating context switching.

EXAMPLE OUTPUT:
- Folder structure with rationale
- Next.js 14 + Fastify backend + PostgreSQL (why each)
- CLAUDE.md with project context, decisions, team roles
- Task 1: Setup database schema, Task 2: API endpoints, Task 3: Auth system

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #2 — CODE REVIEW & REFACTOR

USE THIS when code quality matters (production readiness, performance, security).

PROMPT:
"Review this code for:

1) Bugs and edge cases (null handling, boundary conditions, error scenarios)
2) Performance issues (O(n) complexity, unnecessary loops, memory leaks)
3) Security vulnerabilities (SQL injection, XSS, CSRF, hardcoded secrets, input validation)
4) Readability and maintainability (variable naming, function length, comments)

Provide:
- List of issues with severity (Critical/High/Medium/Low)
- Refactored version with inline comments explaining each change
- Reasoning for each change

Code: [PASTE CODE]"

ARVEN TIP: Use this before every commit to production. Catches 80% of bugs.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #3 — TEST GENERATOR

USE THIS to avoid shipping untested code.

PROMPT:
"Write comprehensive tests for this function. Include:

1) Unit tests for happy path (normal inputs, expected outputs)
2) Edge cases (null, undefined, empty, boundary values, extreme inputs)
3) Error scenarios (invalid types, exceptions, timeouts)
4) Mocks for external dependencies (API calls, database queries)

Framework: [Jest/Pytest/Vitest/etc]
Coverage target: 90%+

Function: [PASTE CODE]"

ARVEN TIP: 90% test coverage = sleep well at night.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #4 — API DESIGN

USE THIS before building backends.

PROMPT:
"Design a RESTful API for the following feature. Provide:

1) Endpoint list with HTTP methods (GET/POST/PUT/DELETE/PATCH)
2) Request/response schemas in JSON (with required/optional fields, types)
3) Error codes and messages (400, 401, 403, 404, 500, etc.)
4) Authentication approach (JWT, OAuth, API keys)
5) Rate limiting strategy (per user, per IP, time window)
6) Pagination strategy (if applicable)

Feature: [DESCRIBE FEATURE]

Example: POST /api/users/create should take {name, email, password} and return {id, token, user}"

ARVEN TIP: Good API design = easy integration. Bad design = client hell.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #5 — DEBUG ASSISTANT

USE THIS when things break (and they will).

PROMPT:
"I have a bug. Help me find the root cause and fix it.

Error: [PASTE ERROR MESSAGE]

Relevant code: [PASTE CODE SNIPPET]

What I expect to happen: [DESCRIBE EXPECTED BEHAVIOR]

What actually happens: [DESCRIBE ACTUAL BEHAVIOR]

Steps to reproduce: [LIST STEPS]

Please:
1) Explain the root cause
2) Provide a fix with explanation
3) Suggest prevention for future"

ARVEN TIP: Good error messages save hours. Copy-paste the full stack trace.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #6 — DATABASE SCHEMA

USE THIS before writing queries.

PROMPT:
"Design a database schema for: [DESCRIBE APP]

Provide:

1) Table definitions (name, columns, data types)
2) Primary keys and foreign keys
3) Indexes for performance (search fields, frequently joined tables)
4) Relationships diagram in text format
5) Migration SQL (CREATE TABLE statements)
6) Example queries (SELECT, INSERT, UPDATE patterns)

Database: [PostgreSQL/MySQL/MongoDB/etc]"

ARVEN TIP: Good schema = queries that run in milliseconds. Bad schema = timeouts.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #7 — DOCUMENTATION WRITER

USE THIS for every code you want others to use.

PROMPT:
"Write complete documentation for this code:

1) README with setup instructions (install, config, usage)
2) JSDoc/docstring comments for each function (parameters, returns, examples)
3) Usage examples with real data
4) CHANGELOG entry (what's new, what changed, what's deprecated)
5) Troubleshooting guide (common errors, solutions)

Code: [PASTE CODE]

Audience: [Junior devs / DevOps / End users]"

ARVEN TIP: Code without docs is legacy code on day 1.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #8 — PERFORMANCE AUDIT

USE THIS before launch.

PROMPT:
"Analyze this code for performance bottlenecks:

1) Time complexity (O(n), O(n²), O(log n) — identify slow parts)
2) Space complexity (memory usage, garbage collection)
3) Unnecessary re-renders (React/Vue) or database queries (N+1 problem)
4) Memory leaks (event listeners not removed, closures holding references)
5) Caching opportunities (what can be cached, TTL strategy)

Provide:
- Bottleneck analysis with impact (CPU/Memory/Network)
- Optimized version with explanations
- Expected improvement (% faster, % less memory)

Code: [PASTE CODE]

Current performance: [200ms load time / 50MB memory / etc]"

ARVEN TIP: Optimize the 20% of code that uses 80% of resources.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #9 — SECURITY CHECKLIST

USE THIS on anything that touches user data.

PROMPT:
"Perform a security audit of this code. Check for:

1) SQL injection (parameterized queries used?)
2) XSS (Cross-Site Scripting — input sanitization?)
3) CSRF (Cross-Site Request Forgery — tokens present?)
4) Insecure direct object references (IDOR — authorization checks?)
5) Hardcoded credentials (secrets in code?)
6) Missing input validation (type checking, length limits?)
7) Improper error handling (sensitive info in error messages?)
8) Authentication/Authorization gaps (who can do what?)

Code: [PASTE CODE]

Provide:
- Vulnerabilities list with severity (Critical/High/Medium)
- Fixed version
- Security best practices for this domain"

ARVEN TIP: One vulnerability = one hacked account. One hacked account = PR nightmare.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #10 — DEPLOYMENT CONFIG

USE THIS when you're ready for production.

PROMPT:
"Create production deployment configuration for this app: [DESCRIBE APP]

Provide:

1) Dockerfile (multi-stage build, optimized layers)
2) docker-compose.yml (services: app, database, cache, etc.)
3) GitHub Actions CI/CD pipeline (test → build → deploy)
4) Environment variables template (.env.example)
5) Health check endpoint
6) Monitoring/logging setup (what to track)

Tech stack: [Node.js/Python/Go/etc]

Deployment target: [Heroku/AWS/DigitalOcean/Hetzner/etc]"

ARVEN TIP: Good deployment = sleep through the night. Bad deployment = 3am phone calls.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #11 — CODE MIGRATION

USE THIS when upgrading frameworks or languages.

PROMPT:
"Migrate this codebase from [OLD TECH] to [NEW TECH].

Provide:

1) Migration strategy (big bang vs incremental)
2) File-by-file conversion plan (what changes, what stays)
3) Compatibility shims needed (temporary code to support both versions)
4) Testing approach (what to test, how to verify)
5) Rollback plan (what if something breaks)
6) Timeline estimate (days/weeks)

Old code: [PASTE CODE]

ARVEN TIP: Incremental migration = safer than big bang rewrite."

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

SUMMARY: WHEN TO USE EACH TEMPLATE

Project starts           → Template #1 (Bootstrap)
Code review before PR   → Template #2 (Review)
Need test coverage      → Template #3 (Tests)
Building backend        → Template #4 (API)
Something broke         → Template #5 (Debug)
New feature needs data  → Template #6 (Schema)
Need documentation     → Template #7 (Docs)
App is slow            → Template #8 (Performance)
Touching user data     → Template #9 (Security)
Ready for production   → Template #10 (Deployment)
Upgrading framework    → Template #11 (Migration)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

KEY PRINCIPLES

✓ Each template is production-tested (used on real projects)
✓ No context switching — all 11 in one toolkit
✓ Works with any tech stack
✓ Copy-paste ready
✓ Saves 50+ hours per project
✓ Reduces bugs by 80%

ARVEN AI Agency • arvend.io • Good Just Happens
