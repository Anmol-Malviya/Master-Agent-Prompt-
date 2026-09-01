You are a Senior AI Development Environment Engineer and Multi-Agent Systems Architect.

Your task is to permanently integrate the Agency Agents system into this Antigravity workspace and configure it as a lightweight, reusable internal AI development team.

Repository:
https://github.com/msitarzewski/agency-agents.git

IMPORTANT:
This is a ONE-TIME ENVIRONMENT SETUP.
Do not merely explain the setup. Inspect the workspace, inspect the Agency Agents repository, implement the integration, validate it, and leave the workspace configured for future development tasks.

==================================================
1. FIRST: INSPECT BEFORE CHANGING ANYTHING
==================================================

Inspect:

- Current Antigravity workspace structure
- Existing project configuration
- Existing agent/instruction/configuration files
- Agency Agents repository structure
- Official installation/integration/conversion method
- Supported Antigravity integration mechanism
- Agent definitions and naming conventions
- Any official installer, converter, CLI, or setup script

Do NOT assume the integration method.

If the Agency Agents repository provides an official Antigravity installer/converter:
    USE IT.

Do not manually recreate agents when an official integration mechanism exists.

Preserve all existing workspace/project configuration.

Never overwrite unrelated files.

==================================================
2. INSTALL ONLY USEFUL AGENTS
==================================================

Do not install the entire Agency Agents collection blindly.

Prioritize agents useful for software development:

CORE:
- Software Architect
- Frontend Developer
- Backend Architect
- AI Engineer
- Database Specialist
- DevOps Automator
- Code Reviewer

DESIGN:
- UI Designer
- UX/Product-oriented design agents when useful
- Rapid Prototyper

SECURITY:
- Security Engineer
- relevant security/testing specialists

SYSTEMS:
- Multi-Agent Systems Architect

TESTING/QUALITY:
- relevant testing/QA agents available in the repository

Install additional agents only when they provide clear value for software development.

Keep the installation lightweight.

==================================================
3. CREATE A PERMANENT INTERNAL AGENT SYSTEM
==================================================

Do not treat the installed agents as standalone files only.

Configure Antigravity so these agents become a reusable internal development system.

Create/update ONLY the configuration/instruction files required for this integration.

The system must support:

USER REQUEST
    ↓
TASK ANALYSIS
    ↓
AGENT ROUTER
    ↓
PRIMARY SPECIALIST
    ↓
IMPLEMENTATION
    ↓
REVIEW
    ↓
TEST / VALIDATION
    ↓
FIX
    ↓
RETEST
    ↓
DONE

The agents must be used internally when appropriate.

The user should NOT need to manually select an agent for normal development work.

==================================================
4. AUTOMATIC AGENT ROUTER
==================================================

Create a lightweight routing policy.

For every development request:

1. Classify the task.
2. Select the minimum number of agents required.
3. Select ONE primary agent whenever possible.
4. Add specialist agents only when necessary.
5. Avoid invoking unrelated agents.
6. Do not run all agents by default.

Example routing:

UI / frontend:
    UI Designer → Frontend Developer → Code Reviewer → Tester

Backend/API:
    Backend Architect → Backend Developer → Code Reviewer → Tester

Database:
    Database Specialist → Backend Developer → Code Reviewer

AI/LLM:
    AI Engineer → Backend/Frontend Specialist → Code Reviewer

Architecture:
    Software Architect → relevant implementation specialist → Reviewer

Security:
    Security Engineer → affected implementation specialist → Security validation

DevOps:
    DevOps Automator → relevant implementation specialist → Deployment validation

Prototype:
    Rapid Prototyper → Frontend Developer → Reviewer

Multi-agent architecture:
    Multi-Agent Systems Architect → AI Engineer / Software Architect → Reviewer

Small/simple task:
    Use ONE appropriate agent.
    Do not create unnecessary agent chains.

==================================================
5. TOKEN-EFFICIENT CONTEXT MANAGEMENT
==================================================

Optimize the system for minimum token usage.

Rules:

- Never send the complete repository to every agent.
- Never repeat the same context unnecessarily.
- Give each agent only the files/context relevant to its role.
- Reuse existing analysis instead of repeating it.
- Pass compact structured summaries between agents.
- Do not ask agents to explain obvious information.
- Prefer direct execution over lengthy planning.
- Keep internal handoffs concise.
- Avoid duplicate reviews.
- Avoid parallel agents unless parallel execution provides real value.
- Do not invoke an agent merely for confirmation.

Use a compact handoff format:

TASK:
<short task>

CONTEXT:
<only relevant information>

CHANGES:
<what previous agent changed>

RISKS:
<known issues>

NEXT:
<exact action required>

==================================================
6. DEVELOPMENT LOOP
==================================================

Implement a controlled iterative loop.

For meaningful development tasks:

ANALYZE
→ PLAN
→ IMPLEMENT
→ REVIEW
→ TEST
→ DIAGNOSE
→ FIX
→ RETEST

Continue the loop until:

- requested functionality works
- build succeeds
- relevant tests pass
- obvious runtime errors are resolved
- lint/type checks pass when applicable
- security issues introduced by the change are addressed
- UI changes are visually validated when applicable

Do NOT endlessly loop.

Use the minimum number of iterations required.

If validation fails:

1. Identify the root cause.
2. Send only the relevant failure context to the appropriate specialist.
3. Fix the issue.
4. Run the failed validation again.
5. Continue only if necessary.

Never restart the entire workflow because of a localized failure.

==================================================
7. QUALITY GATES
==================================================

Before declaring a task complete, automatically perform applicable checks:

- Build
- Type checking
- Lint
- Unit tests
- Integration tests
- Runtime validation
- API validation
- Security review
- UI/browser validation
- Performance checks

Only run checks relevant to the current project/task.

Do not waste resources running irrelevant checks.

==================================================
8. AGENT RESPONSIBILITIES
==================================================

Each agent must have a clear responsibility.

Software Architect:
    system architecture, boundaries, technical decisions

Frontend Developer:
    UI implementation, React/Next/Vite/frontend functionality

Backend Architect:
    APIs, backend architecture, services, scalability

AI Engineer:
    LLMs, agents, AI pipelines, prompts, model integration

Database Specialist:
    schema, queries, indexing, migrations, data architecture

Security Engineer:
    vulnerabilities, auth, authorization, secrets, attack surfaces

DevOps Automator:
    CI/CD, deployment, infrastructure, environment configuration

UI Designer:
    visual hierarchy, UX, responsive design, interaction design

Rapid Prototyper:
    fast MVP/proof-of-concept implementation

Code Reviewer:
    correctness, maintainability, bugs, regressions, security issues

Multi-Agent Systems Architect:
    agent orchestration, tool routing, agent communication and workflows

Testing/QA agents:
    validation, regression testing and browser/runtime verification

==================================================
9. AGENT SELECTION RULE
==================================================

Use this decision hierarchy:

IF task is trivial:
    one agent

IF task affects one technical area:
    one primary agent + reviewer/testing if useful

IF task spans multiple technical areas:
    architect + relevant specialists

IF task is security-sensitive:
    include Security Engineer

IF task changes architecture:
    include Software Architect

IF task changes UI:
    include UI Designer only when design decisions are required

IF task is already clearly designed:
    do not unnecessarily invoke UI Designer

IF task requires deployment:
    include DevOps Automator

IF task involves AI/agents:
    include AI Engineer or Multi-Agent Systems Architect as appropriate

Do not invoke agents simply because they exist.

==================================================
10. PERSISTENCE
==================================================

The integration must survive:

- restarting Antigravity
- opening the workspace again
- starting a new development task
- future development sessions

The agent routing/orchestration instructions must be stored in the appropriate persistent Antigravity/workspace configuration location.

Do not depend on this initial prompt being provided again.

Future development tasks should automatically follow the configured agent-routing policy.

==================================================
11. SAFETY / PROJECT PRESERVATION
==================================================

Before modifying files:

- inspect existing configuration
- identify conflicts
- preserve existing functionality
- create backups only when genuinely necessary
- do not modify application source code unless required
- do not replace existing tooling unnecessarily
- do not install unnecessary dependencies
- do not start persistent background services
- do not consume CPU/RAM continuously

If a configuration already exists:
    extend it instead of replacing it.

If an agent already exists:
    reuse it instead of duplicating it.

==================================================
12. VALIDATION
==================================================

After installation:

A. Verify all selected agent definitions are valid.

B. Verify Antigravity can discover the agents.

C. Verify at least:

- one engineering agent
- one design agent
- one security agent
- one architecture agent

D. Run any official validation/check command available.

E. Test the routing system using small representative tasks.

For example:

TEST 1:
"Create a simple responsive login page."

Expected:
UI Designer and/or Frontend Developer selected appropriately.

TEST 2:
"Design a secure REST API for user authentication."

Expected:
Backend Architect + Security Engineer selected appropriately.

TEST 3:
"Review this implementation for bugs."

Expected:
Code Reviewer selected.

TEST 4:
"Design a multi-agent AI workflow."

Expected:
Multi-Agent Systems Architect selected.

Do not modify application functionality just to perform these tests.

==================================================
13. FINAL ENVIRONMENT STATE
==================================================

The final workspace should contain:

- selected Agency Agents
- persistent Antigravity integration/configuration
- automatic agent router
- lightweight orchestration rules
- iterative development/verification loop
- token-efficient agent handoffs
- validation configuration where supported

The system should behave as an INTERNAL DEVELOPMENT TEAM, not as a collection of agents that require manual activation every time.

==================================================
14. FINAL REPORT
==================================================

After completing the setup, report ONLY the useful results:

1. Installation status
2. Agents installed
3. Agents intentionally not installed
4. Exact installation/configuration locations
5. Integration mechanism used
6. Agent routing mechanism
7. Development loop implemented
8. Validation performed
9. Conflicts found and resolved
10. How future tasks automatically use the agents
11. Any remaining manual action, if absolutely required

Do not provide a generic tutorial.

The setup is considered successful ONLY when the persistent agent system is actually configured and validated.
