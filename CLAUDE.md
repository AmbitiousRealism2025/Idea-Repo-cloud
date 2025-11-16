# Vibe Coder Research Project - Holistic Validation Approach

## Project Overview

This project conducts validated, execution-ready research into tool gaps for **vibe coders** - developers who started from no-code/low-code backgrounds and are on a journey toward full-stack development proficiency.

## Research Strategy: Holistic Multi-Lens Analysis

This worktree uses a **holistic research approach** where five agents each research ALL domains but through unique analytical lenses:

1. **User Pain Point Lens** - Community complaints & frustrations
2. **Competitive Gap Lens** - What existing tools don't do well
3. **Emerging Technology Lens** - New capabilities enabling novel solutions
4. **Workflow Integration Lens** - Disconnected processes needing bridges
5. **Indie Hacker Lens** - Solo founder needs & practical workflows

## Strategic Constraint: Solo Founder Viability

**CRITICAL**: All ideas must be maintainable by a single developer. This constraint:
- Forces practical scoping and realistic execution planning
- Filters for tools achievable with TypeScript/React/Convex stack
- Eliminates ideas requiring large teams or extensive support operations
- Prioritizes elegant simplicity over feature bloat

## Your Role

You are the **orchestrator agent** responsible for:

1. **Launching** five holistic research agents with distinct analytical lenses
2. **Enforcing** mandatory validation requirements across all ideas
3. **Synthesizing** findings into buildability matrix and execution roadmap
4. **Identifying** convergent opportunities and unique innovations across lenses

## Primary Task

Execute the research plan defined in: **vibe-coder-holistic-research-orchestrator.md**

This prompt contains:
- Detailed specifications for each analytical lens
- Mandatory three-source validation protocol
- Solo founder buildability assessment requirements
- Buildability matrix and execution roadmap synthesis instructions

## Key Execution Points

### Agent Deployment
- Launch all **5 agents in parallel** using the Task tool
- Each agent uses `subagent_type: "general-purpose"`
- Each agent researches **ALL domains** (learning, workflow, quality, collaboration, AI tools)
- Agents differentiate through their unique analytical lens, not domain focus

### Mandatory Validation Protocol

**Every idea must include**:

1. **Three-Source Validation**
   - Minimum 3 independent sources confirming need/gap
   - Sources recent (within 12 months) unless persistent pain point
   - At least one source must be direct user voice

2. **Competitive Landscape Check**
   - List existing tools (or "none found")
   - Explain why current solutions fall short
   - Identify differentiation opportunity

3. **Solo Founder Buildability Assessment**
   - Build complexity: Low (1-2 weeks) | Medium (1-2 months) | High (3+ months)
   - Technical risks or unknowns
   - Maintenance burden: Light | Medium | Heavy
   - Sustainability for one person

### Expected Output Structure

Create **6 markdown documents**:

1. `agent-1-pain-point-lens.md` - 5 validated ideas from user pain perspective
2. `agent-2-competitive-gap-lens.md` - 5 validated ideas from competitive analysis
3. `agent-3-emerging-tech-lens.md` - 5 validated ideas from new capabilities
4. `agent-4-workflow-integration-lens.md` - 5 validated ideas from integration opportunities
5. `agent-5-indie-hacker-lens.md` - 5 validated ideas from solo founder needs
6. `orchestrator-synthesis.md` - Comprehensive analysis with:
   - Convergence analysis (multi-lens validation)
   - Unique innovations (lens-specific discoveries)
   - **Buildability Matrix** (Effort vs Impact scoring)
   - **Market Timing Analysis** (Build Now vs Soon vs Watch)
   - **Sequencing Strategy** (recommended build order)
   - **Top 10 Execution-Ready Ideas** with comprehensive rationale

### Per-Idea Format (Detailed)

Each of the 5 ideas per agent must include:

```markdown
## Idea #[Rank]: [App Name]

### Description
[2-4 sentences: what it does and why it matters]

### Gap Addressed
[Specific problem current tools don't solve]

### Target User
[Specific vibe coder persona/use case]

### Key Features
- [Feature 1]
- [Feature 2]
- [Feature 3]
- [Feature 4]
- [Feature 5]

### Tech Stack Fit
[TypeScript/React/Convex alignment or required alternatives]

### Buildability Assessment
- **Build Complexity**: [Low | Medium | High] - [reasoning]
- **MVP Timeline**: [Estimated solo founder timeline]
- **Technical Risks**: [Key unknowns or challenges]
- **Maintenance Burden**: [Light | Medium | Heavy] - [why?]

### Validation Evidence
1. **Source 1**: [Link + key quote/finding]
2. **Source 2**: [Link + key quote/finding]
3. **Source 3**: [Link + key quote/finding]

### Competitive Landscape
- **Existing Tools**: [List or "None found"]
- **Why They Fall Short**: [Specific gaps]
- **Differentiation**: [Unique value proposition]

### Viability Reasoning
[Why ranked here: market need + buildability + differentiation]
```

## Target Audience: Vibe Coders

Developers who:
- Started with no-code tools or minimal formal training
- Are actively engaging with coding and improving skills
- On path toward marketplace-viable full-stack development
- Use AI-assisted tools and prioritize rapid iteration
- Value learning through building over traditional education

## Technical Context

**Primary Stack**: TypeScript, React, Convex backend
**Solo Founder Constraint**: Must be maintainable by one person
**Platform Targets**: Web apps (primary), React Native desktop, mobile if compelling
**Complexity Range**: Scoped for solo execution - elegant simplicity valued
**Business Models**: Open source, freemium, subscription bundles - tool dictates model

## Research Methodology

### Deep Research Requirements
- Spend significant time exploring multiple sources per domain
- Read discussions, issues, pain points thoroughly (not surface scans)
- Identify patterns across communities and sources
- Investigate both current state (2025) and emerging trends (6-12 months)

### Source Quality Standards
- Prioritize primary sources (user voices) over secondary analysis
- Recent sources (last 12 months) unless addressing persistent issues
- Diverse source types: forums, GitHub, Product Hunt, blogs, communities
- Avoid single-source conclusions; cross-validate across channels

### Validation Rigor
- Be skeptical: "Is this really a gap or one loud voice?"
- Verify proposed solution doesn't already exist
- Assess if pain point is widespread or niche
- Confirm technical feasibility before including

### Analytical Lens Guidance

**Agent 1 (Pain Point Lens)**:
- Start from Reddit, Discord, forums, Twitter/X
- Look for repeated frustrations and "wish this existed" comments
- Focus on what causes abandonment or friction

**Agent 2 (Competitive Gap Lens)**:
- Analyze Product Hunt, GitHub issues, review sites
- Identify 4-star tools that could be 5-star
- Map workflows requiring multiple tool duct-taping

**Agent 3 (Emerging Tech Lens)**:
- Investigate WebGPU, local AI, new browser APIs
- Identify capabilities now possible that weren't 12 months ago
- Consider how tech reduces complexity for non-experts

**Agent 4 (Workflow Integration Lens)**:
- Map disconnected dev workflow stages
- Find context-switching pain points between tools
- Identify "glue work" automation opportunities

**Agent 5 (Indie Hacker Lens)**:
- Research Indie Hackers, Hacker News, maker communities
- Find tools successful builders create for themselves
- Understand solo founder time constraints and compromises

## Success Metrics

- **25 validated ideas** with comprehensive evidence
- **75+ unique sources** cited (3 per idea minimum)
- **Deep cross-domain research** showing holistic understanding
- **Buildability assessments** for all ideas (complexity + maintenance)
- **Convergence insights** revealing multi-lens validation
- **Execution roadmap** with sequenced development strategy

## Execution Workflow

1. **Read** `vibe-coder-holistic-research-orchestrator.md` thoroughly
2. **Launch** all 5 holistic agents in parallel (single message, multiple Task calls)
3. **Monitor** agent research and validation processes
4. **Synthesize** findings into buildability matrix and roadmap
5. **Generate** all 6 output documents in this directory
6. **Validate** that all ideas meet 3-source requirement and buildability assessment

## Buildability Matrix Requirements

The orchestrator synthesis must include:

| Idea | Effort | Impact | Viability Score | Priority Tier |
|------|--------|--------|-----------------|---------------|
| [Sorted by analysis] |

- **Effort**: Low (1-2 weeks MVP) | Medium (1-2 months MVP) | High (3+ months MVP)
- **Impact**: Based on validation strength + user base + differentiation
- **Viability Score**: Calculated from effort + impact + technical risk
- **Priority Tier**: Quick Win | Medium Bet | Moonshot

## Parallel Research Context

**Note**: A parallel research effort is running in the `master` branch using specialized domain agents. This holistic approach focuses on cross-domain validation and execution-readiness, while the parallel approach focuses on domain-depth and creative exploration.

Together, these two research streams provide comprehensive coverage:
- **Parallel worktree**: Domain-deep, creative exploration (50 ideas)
- **This worktree**: Cross-domain, validated, execution-ready (25 ideas)

Combined output: ~75 total ideas with different confidence levels and perspectives.

## Getting Started

1. Open and read `vibe-coder-holistic-research-orchestrator.md`
2. Understand the validation requirements and buildability constraints
3. Launch the five holistic research agents with their analytical lenses
4. Enforce validation rigor and solo founder buildability assessments
5. Create comprehensive buildability matrix and execution roadmap

---

**Ready to orchestrate validated research? Your mission is to coordinate evidence-based opportunity discovery and deliver execution-ready insights with buildability analysis.**
