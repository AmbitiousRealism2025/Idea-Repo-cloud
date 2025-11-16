# Vibe Coder Tool Gap Research - Orchestrator Agent

## Mission
Orchestrate deep research into tool gaps for vibe coders by coordinating five specialized sub-agents. Each agent will identify opportunities for tools that support developers on their journey from no-code/low-code backgrounds toward full-stack proficiency.

## Target Audience Definition: Vibe Coders
Developers who:
- Started with no-code tools or had minimal/no formal programming training
- Have engaged with coding over time and are actively improving their skills
- Are on a path toward legitimate, marketplace-viable full-stack development
- Often use AI-assisted coding tools and prioritize rapid iteration
- Value practical learning through building over traditional education paths

## Research Objectives
1. **Current State Analysis**: Identify gaps in today's available tools (2025)
2. **Future Gap Identification**: Spot emerging trends and near-future needs (6-12 months)
3. **Opportunity Mapping**: Generate viable app ideas that fill these gaps

## Orchestration Strategy

### Phase 1: Deploy Five Specialized Sub-Agents

Create five parallel research agents, each focused on a distinct domain:

#### Agent 1: Learning & Skill Progression Tools
**Focus Area**: Educational tools, learning paths, skill assessment, progressive complexity
**Research Questions**:
- What gaps exist in helping vibe coders transition from visual/no-code to actual code?
- Where do existing learning platforms fail vibe coders specifically?
- What tools could accelerate the journey from beginner to full-stack competency?
- How can tools better scaffold complexity as skills develop?

#### Agent 2: Development Workflow & Environment Tools
**Focus Area**: IDEs, development environments, debugging, testing, deployment pipelines
**Research Questions**:
- What workflow friction points do vibe coders encounter that experts don't?
- Where are current dev tools too complex or too simplistic for this audience?
- What gaps exist in local development, staging, and production workflows?
- How can tooling better support the transition from simple to complex architectures?

#### Agent 3: Code Quality & Architecture Guidance Tools
**Focus Area**: Code reviews, refactoring, architecture patterns, best practices, technical debt
**Research Questions**:
- How can tools help vibe coders write maintainable, scalable code without overwhelming them?
- What gaps exist in real-time code quality feedback for self-taught developers?
- Where do existing linting/quality tools fall short for this audience?
- How can tools teach architecture patterns through practical application?

#### Agent 4: Collaboration & Community Tools
**Focus Area**: Peer learning, mentorship, code sharing, project collaboration, community engagement
**Research Questions**:
- What collaboration gaps exist specifically for vibe coders learning in public?
- How can tools better connect vibe coders with mentors and peers at similar skill levels?
- Where do current platforms fail at fostering supportive learning communities?
- What opportunities exist for project-based collaborative learning?

#### Agent 5: AI-Assisted Development & Productivity Tools
**Focus Area**: AI code generation, context management, prompt engineering, AI workflow integration
**Research Questions**:
- What gaps exist in helping vibe coders effectively leverage AI coding assistants?
- Where do current AI tools fail to support the learning journey vs. just outputting code?
- How can tools help vibe coders understand, modify, and learn from AI-generated code?
- What's missing in AI-first development workflows for this audience?

### Phase 2: Sub-Agent Research Protocol

Each agent should:

1. **Deep Research Methodology**:
   - Balance web search with targeted sources (dev forums, Product Hunt, GitHub, Reddit, Discord communities, etc.)
   - Investigate current tool landscape to identify genuine gaps
   - Consider both current state (2025) and emerging trends (6-12 months forward)
   - Optionally validate against: existing competitors, user pain points, community feedback

2. **Deliverable Format**:
   - Generate **10 ranked app ideas** (1 = highest viability)
   - For each idea provide:
     - **App Name**: Creative but descriptive
     - **Description**: Brief but complete (2-4 sentences max; prioritize clarity over brevity)
     - **Gap Addressed**: What specific problem this solves
     - **Target User**: Specific vibe coder persona/use case
     - **Key Features**: 3-5 bullet points of core functionality
     - **Tech Stack Fit**: Note if particularly suited to TypeScript/React/Convex or requires different approach
     - **Viability Reasoning**: Why ranked at this position

3. **Research Validation** (Agent's Discretion):
   - Each agent may choose whether to validate ideas against existing tools, competitors, or user communities
   - Agents should note their validation approach in their final report

### Phase 3: Orchestrator Synthesis

After all five agents complete their research:

1. **Individual Agent Reports**:
   - Create separate Markdown files for each agent:
     - `agent-1-learning-tools.md`
     - `agent-2-workflow-tools.md`
     - `agent-3-quality-tools.md`
     - `agent-4-collaboration-tools.md`
     - `agent-5-ai-productivity-tools.md`
   - Each file contains the agent's complete ranked list with full details

2. **Comparative Analysis Document**:
   - Create `orchestrator-synthesis.md` containing:
     - **Executive Summary**: High-level findings across all agents
     - **Overlap Analysis**: Ideas that appeared across multiple agents (indicates strong market need)
     - **Unique Insights**: Novel ideas that only one agent identified
     - **Gap Categories**: Taxonomy of identified gaps across all research
     - **Viability Patterns**: Trends in what makes ideas highly ranked vs. lower ranked
     - **Quick Wins vs. Ambitious Projects**: Categorization by complexity/scope
     - **Tech Stack Alignment**: Which ideas fit well with TypeScript/React/Convex backend
     - **Potential Business Models**: Open source candidates, freemium opportunities, bundled subscriptions
     - **Recommended Next Steps**: Top 10-15 ideas across all agents with rationale

## Technical Constraints & Preferences

**Primary Tech Stack**: TypeScript, React, Convex backend
**Platform Targets**: Web apps (primary), React Native for desktop (Mac/possibly Windows), mobile if compelling
**Complexity Range**: From simple micro-tools to comprehensive platforms - don't self-limit
**Business Models**: Open source, freemium, subscription bundles - tool should dictate model

## Agent Autonomy & Creativity

- **No source restrictions**: Agents may research any relevant communities, forums, or platforms
- **Validation flexibility**: Each agent decides validation rigor based on their domain
- **Creative freedom**: Balance practical/simple ideas with creative/ambitious concepts
- **Market awareness**: Consider both immediate utility and long-term market potential

## Success Criteria

- **50 total ideas** (10 per agent) with comprehensive details
- **Deep research** evidencing thorough investigation of each domain
- **Ranked by viability** with clear reasoning for rankings
- **Overlap identification** showing market validation through convergence
- **Unique innovations** demonstrating creative exploration of gaps
- **Actionable synthesis** providing clear path forward for development decisions

## Execution Instructions

1. Launch five sub-agents in parallel using the Task tool
2. Each agent should use `subagent_type: "general-purpose"` with deep research capability
3. Agents should use web search, web fetch, and any other research tools available
4. Upon completion, synthesize all outputs into the document structure specified above
5. Save all outputs to the current working directory with clear naming conventions

---

**Orchestrator: Begin by launching all five specialized research agents in parallel. Provide each agent with their specific focus area and research questions. Coordinate their research completion and then execute the synthesis phase.**
