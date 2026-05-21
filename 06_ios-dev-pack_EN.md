ARVEN EN
iOS Dev Pack
7 Templates for Swift & SwiftUI Development
$19

Build iOS apps that users love. From architecture to App Store.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

WHAT'S INSIDE

7 production-ready templates for iOS architecture, SwiftUI patterns, performance optimization.
Works with Swift 5.9+, iOS 14+, SwiftUI.
Each template includes best practices and common pitfalls to avoid.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #1 — PROJECT ARCHITECTURE

USE THIS when starting a new iOS app.

PROMPT:
"Design architecture for iOS app: [DESCRIBE APP]

Define:

1) Folder structure (by feature vs layer)
2) MVVM vs MVC vs VIPER (which pattern)
3) Dependency injection (how to pass dependencies)
4) Networking layer (how to fetch data)
5) Local storage (CoreData, UserDefaults, File system)
6) Error handling (how to handle failures)
7) Navigation (how to move between screens)
8) Testing strategy (unit, integration, UI tests)

App type: [SocialApp / ProductivityApp / GameApp / UtilityApp]
Team size: [Solo / Small team / Large team]
Complexity: [Simple / Medium / Complex]

Provide:
- Project folder structure
- Architecture diagram
- Layer responsibilities
- Dependency injection pattern
- Error handling strategy
- Testing pyramid"

ARVEN TIP: Good architecture = easy testing and maintenance.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #2 — SWIFTUI COMPONENTS

USE THIS to build reusable UI components.

PROMPT:
"Design SwiftUI components for: [DESCRIBE FEATURE]

Create:

1) Component hierarchy (parent-child relationships)
2) State management (what state each component owns)
3) View modifiers (spacing, padding, colors)
4) Custom modifiers (create composable modifiers)
5) Previews (for each component)
6) Accessibility (VoiceOver support)
7) Dark mode support
8) Responsive layout (phone, tablet, landscape)

Feature: [E.g., User profile screen]
Design system: [Colors, typography, spacing]

Provide:
- SwiftUI code for each component
- View hierarchy diagram
- State flow
- Preview code
- Accessibility labels
- Dark mode implementation"

ARVEN TIP: Build components once, use everywhere.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #3 — DATA PERSISTENCE

USE THIS to save data locally.

PROMPT:
"Design data persistence for: [DESCRIBE APP]

Choose:

1) User defaults (simple key-value, for settings)
2) Core Data (complex, relational data)
3) File system (documents, images, large files)
4) CloudKit (sync across devices)
5) Realm (alternative to Core Data)

For chosen storage:
- Data model (entities and relationships)
- CRUD operations (create, read, update, delete)
- Migrations (schema changes)
- Sync strategy (online/offline)
- Security (encryption for sensitive data)

Data to persist: [User profiles, Messages, Settings, Files]

Provide:
- Data model (entities)
- Storage layer code
- Migration strategy
- Sync logic
- Security implementation
- Testing helpers"

ARVEN TIP: Plan your data model before coding.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #4 — NETWORKING

USE THIS to fetch data from APIs.

PROMPT:
"Design networking layer for: [DESCRIBE APP]

Build:

1) API client (URLSession wrapper)
2) Request/response models (Codable)
3) Error handling (API errors, network errors)
4) Retry logic (exponential backoff)
5) Caching strategy (memory, disk)
6) Authentication (token storage, refresh)
7) Request interceptors (logging, headers)
8) Mocking for testing

API endpoints: [List main endpoints]
Authentication: [OAuth / JWT / API Key / None]

Provide:
- Networking layer code
- API models (Request/Response)
- Error handling
- Retry strategy
- Cache implementation
- Mock service for testing"

ARVEN TIP: Network requests can be slow. Plan caching and retries upfront.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #5 — PERFORMANCE OPTIMIZATION

USE THIS to make your app fast and smooth.

PROMPT:
"Optimize performance for: [DESCRIBE APP]

Analyze:

1) Memory usage (leaks, excessive allocation)
2) Battery drain (background tasks, networking)
3) Rendering performance (frame rate, scroll smoothness)
4) Startup time (how long to launch)
5) Network efficiency (data sent/received)
6) Storage usage (cache size, database bloat)
7) CPU usage (background processing)

Performance targets:
- Startup: [Under X seconds]
- Scroll: [60 FPS / 120 FPS]
- Memory: [Under X MB]

Provide:
- Performance audit checklist
- Optimization recommendations
- Profiling tools (Instruments)
- Before/after metrics
- Monitoring strategy"

ARVEN TIP: Measure before optimizing. Profile, don't guess.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TEMPLATE #6 — TESTING STRATEGY

USE THIS to ensure quality and prevent bugs.

PROMPT:
"Design testing strategy for: [DESCRIBE APP]

Plan:

1) Unit tests (logic and functions)
2) Integration tests (components working together)
3) UI tests (user flows, screenshots)
4) Snapshot tests (UI consistency)
5) Performance tests (speed benchmarks)
6) Test coverage targets (%) 
7) CI/CD integration (automated testing)
8) Mock and stub strategy

Target coverage: [X%]
Testing tools: [XCTest / Quick/Nimble / Snapshot testing]

Provide:
- Test pyramid (unit/integration/UI ratio)
- Test cases for main features
- Mocking strategy
- CI/CD pipeline config
- Coverage measurement
- Flaky test prevention"

ARVEN TIP:
