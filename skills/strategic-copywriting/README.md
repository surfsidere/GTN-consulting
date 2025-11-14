# Strategic Copywriting Skill
## The Alchemist's Codex Methodology for Claude Code

**Version**: 1.0.0
**Created**: January 2025
**Framework**: C.L.E.A.R. (Concise, Logical, Explicit, Adaptive, Reflective)

---

## Overview

This skill enables Claude Code to function as an expert copywriting agent and brand strategist using The Alchemist's Codex methodology. It guides users through a three-phase process to create strategic, persuasive copy grounded in authentic brand identity.

**Core Principle**: Effective communication is the output of a clearly defined core identity. Sell transformation, not products.

---

## What This Skill Does

### Phase 1: Strategic Foundation
Extracts brand DNA (mission, vision, core values), target audience psychographics, and competitive positioning before writing any copy.

### Phase 2: Narrative Engine
Constructs a StoryBrand 7-Part (SB7) BrandScript that positions the customer as hero and the brand as guide.

### Phase 3: Tactical Execution
Generates copy using classical formulas (PAS, BAB, AIDA, 4Ps) with explicit formula declaration, voice alignment to core values, and ethical integration of Cialdini's influence principles.

---

## When to Use This Skill

**Activate when**:
- Creating brand messaging, sales copy, or marketing content
- Translating brand strategy into tactical copy
- User mentions StoryBrand, Donald Miller, or The Alchemist's Codex
- User requests copywriting with strategic foundation

**Do NOT use for**:
- Simple editing or proofreading
- Technical writing or documentation
- Internal communications without brand context
- Quick social posts without strategic foundation

---

## Skill Architecture

```
strategic-copywriting/
├── SKILL.md                           # Main skill instructions
├── README.md                          # This file
├── references/                        # Grounding knowledge base
│   ├── brand-dna-template.md         # Strategic foundation discovery
│   ├── storybrand-sb7-framework.md   # Complete SB7 methodology
│   ├── copywriting-formulas.md       # PAS, BAB, AIDA, 4Ps with examples
│   ├── voice-archetype-matrix.md     # Core values → linguistic rules
│   └── cialdini-principles.md        # Ethical influence integration
└── assets/                            # User-facing templates
    └── brandscript-template.md        # Collaborative BrandScript worksheet
```

---

## Methodological Foundation

### C.L.E.A.R. Framework Compliance

**Concise**: Direct instructions, token-efficient execution
**Logical**: Sequential three-phase workflow with validation gates
**Explicit**: Specific formulas, concrete examples, clear success criteria
**Adaptive**: Iterative refinement loops, responsive to user feedback
**Reflective**: Post-output validation checklists, meta-learning documentation

### Hallucination Mitigation

**Grounding Strategies**:
- All frameworks sourced from authoritative references (Donald Miller, Robert Cialdini)
- Concrete examples in every reference file
- Formula announcement requirement (makes reasoning transparent)
- Post-generation validation checklists
- No invented frameworks or principles

### Three-Phase Workflow (Incremental Prompting)

**Why**: Prevents common copywriting failure (writing without strategy)

**Phase 1** → **Phase 2** → **Phase 3**
- Cannot skip phases
- User approval required between Phase 2 and Phase 3
- Each phase has completion checklist

---

## Key Frameworks Included

### 1. StoryBrand 7-Part Framework (Donald Miller)
- Character (customer desire)
- Problem (external, internal, philosophical)
- Guide (empathy + authority)
- Plan (process or agreement)
- Call to Action (direct + transitional)
- Failure (stakes)
- Success (transformation)

### 2. Classical Copywriting Formulas
- **PAS (Problem-Agitate-Solution)**: Email subject lines, problem sections
- **BAB (Before-After-Bridge)**: Success visions, testimonials
- **AIDA (Attention-Interest-Desire-Action)**: Full sales pages, email sequences
- **4Ps (Promise-Picture-Proof-Push)**: Ad copy, webinar presentations

### 3. Voice Archetypes (12 Types)
- Sage, Jester, Hero, Caregiver, Rebel, Lover
- Ruler, Magician, Innocent, Explorer, Creator, Everyperson
- Each with specific linguistic rules mapping to core values

### 4. Cialdini's 7 Principles of Influence
- Reciprocity, Commitment & Consistency, Social Proof, Authority
- Liking, Scarcity, Unity
- Ethical integration guidance with examples

---

## Usage Examples

### Example 1: Complete Brand Launch

**User Input**:
"I need complete messaging for my new coaching business targeting small business owners."

**Skill Response**:
1. **Phase 1**: Ask sequential questions to extract mission, vision, values, target audience, competitive positioning
2. **Phase 2**: Construct BrandScript using SB7 framework, present for approval
3. **Phase 3**: Generate homepage headline, email sequence, sales page using appropriate formulas

---

### Example 2: Specific Copy Request

**User Input**:
"Write a homepage headline for my SaaS marketing tool. Here's my mission and core values: [provided]"

**Skill Response**:
1. **Phase 2 First**: Build BrandScript from provided foundation
2. **Get Approval**: Present BrandScript for user review
3. **Phase 3 Generation**:
   - Announce formula (4Ps Promise)
   - Draft headline with value annotations
   - Run validation checklist
   - Present final copy

---

### Example 3: Copy Refinement

**User Input**:
"This email isn't converting. Can you improve it? [email provided]"

**Skill Response**:
1. **Audit Against Foundation**: Ask for core values, BrandScript component this addresses
2. **Identify Formula Mismatch**: Diagnose why current copy fails
3. **Regenerate**: Apply correct formula with explicit reasoning
4. **Validate**: Check alignment with brand voice and values

---

## Validation & Quality Gates

### Phase 1 Completion Checklist
- [ ] Mission is aspirational and specific
- [ ] Vision paints measurable future state
- [ ] Core Values are unique and behavioral
- [ ] Target Audience includes psychographic depth
- [ ] Competitor gaps identified
- [ ] Offer transformation is clear

### Phase 2 Completion Checklist
- [ ] User has reviewed and approved BrandScript
- [ ] All 7 SB7 components complete and specific
- [ ] Internal Problem resonates emotionally
- [ ] Success vision is compelling

### Phase 3 Completion Checklist
- [ ] Formula declared with rationale
- [ ] Word choices aligned to core values
- [ ] Strategic analogy used (if complex)
- [ ] Validation checklist completed

---

## Advanced Features

### Multi-Formula Combinations
Sales pages combine PAS (problem) + BAB (success) + 4Ps (CTA)

### Channel-Specific Adaptation
Different execution for email, social media, landing pages, video

### Iterative Refinement Protocol
Systematic debugging when copy doesn't resonate

### Voice Consistency System
Core values → linguistic rules → specific word choices

---

## Grounding Sources

**Primary Authorities**:
- Donald Miller: "Building a StoryBrand" (2017)
- Robert Cialdini: "Influence: The Psychology of Persuasion" (2021, 7th ed)
- Margaret Mark & Carol S. Pearson: "The Hero and the Outlaw" (archetype theory)
- Classical copywriting: Collier, Caples, Schwartz, Ogilvy

**All frameworks**:
- Sourced from published works
- Include attribution
- Provide concrete examples
- Prevent hallucination through grounding

---

## Error Prevention

### Common Copywriting Failures (Avoided)

❌ **Brand-as-hero positioning**: "We are the leader..."
✅ **Customer-as-hero**: "You deserve a partner who..."

❌ **Feature dumping**: "Our platform includes CRM, email..."
✅ **Transformation focus**: "Imagine knowing exactly when to call leads..."

❌ **Skipping strategic foundation**: Writing copy without understanding brand
✅ **Phase 1 → 2 → 3 workflow**: Strategy before tactics

❌ **Manipulative influence tactics**: Fake scarcity, dishonest social proof
✅ **Ethical integration**: Authentic principles woven into narrative

---

## Skill Maintenance

**Update only when**:
- New authoritative frameworks emerge in copywriting literature
- User feedback reveals systematic methodology gaps
- Reference files need expansion based on real-world testing
- Framework sources publish updated editions

**Do NOT update for**:
- Individual client preferences
- Temporary marketing trends
- Unverified "guru" techniques

---

## Integration with SuperClaude Framework

This skill was architected using master-prompter.md methodology:

**C.L.E.A.R. Framework**: Full compliance across all phases
**Hallucination Mitigation**: Grounding, surgical research integration, chain-of-thought, iterative verification
**Incremental Prompting**: Three-phase workflow prevents overwhelm
**Precise Instructions**: Formula announcement, value alignment, validation checklists
**Meta-Prompting**: Built-in reflection on effectiveness and iterative refinement

---

## Version History

**v1.0.0** (2025-01-14)
- Initial release based on The Alchemist's Codex methodology
- Three-phase workflow: Foundation → Narrative → Execution
- Complete StoryBrand SB7 integration
- Four classical formulas (PAS, BAB, AIDA, 4Ps)
- 12 voice archetypes with linguistic rule mappings
- Cialdini's 7 principles ethical integration guide
- Master-prompter C.L.E.A.R. framework compliance
- Comprehensive grounding references (5 files, ~40K words)

---

## Support & Feedback

**Issues**: Report systematic skill failures (not individual client preferences)
**Enhancements**: Suggest grounded framework additions with authoritative sources
**Questions**: Reference specific phase or framework component

---

## License & Attribution

**Skill Framework**: Built for Claude Code using master-prompter methodology
**Content Sources**: All frameworks attributed to original authors
**Usage**: Open for Claude Code users, maintain attribution

---

**Status**: Production-ready for strategic copywriting tasks
**Complexity**: Advanced (requires understanding of brand strategy and copywriting)
**Audience**: Copywriters, marketers, brand strategists, business owners