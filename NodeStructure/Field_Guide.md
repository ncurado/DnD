# Enhanced Standardized Node Structure – Field Guide

**Version**: 7.0

## Overview

This documentation covers the Enhanced Standardized Node Structure system for D&D 5e campaign management. Version 6.0 introduces major improvements including privacy-respectful analytics, modular automation features, and visual reference guides. The system provides complete guidance for understanding, implementing, and creating node-based campaign content using a flexible two-axis approach that separates narrative priority from schema complexity.

**Author**: Nuno Curado
**Documentation**: with the help of Manus AI
**Date**: 8th of June, 2025

## License

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit [http://creativecommons.org/licenses/by-sa/4.0/](http://creativecommons.org/licenses/by-sa/4.0/) or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

## Table of Contentss

1. [What is the Node Structure?](#1-what-is-the-node-structure)
2. [The Two-Axis System](#2-the-two-axis-system)
3. [Depth Profiles Explained](#3-depth-profiles-explained)
4. [Creating Your First Node](#4-creating-your-first-node)
5. [Section-by-Section Guide](#5-section-by-section-guide)
6. [Implementation for Human DMs](#6-implementation-for-human-dms)

## Appendices

- [Appendix A: Complete Section Reference](#appendix-a-profile-quick-start-primers)

---

## 1. What is the Node Structure?

The Enhanced Standardized Node Structure transforms D&D campaign management from scattered notes into organized, interconnected content modules. Each "node" represents a discrete piece of campaign content—an encounter, scene, location, or story moment—with standardized formatting that enables systematic preparation, execution, and sharing.

### The Problem It Solves

**Before**: DMs struggle with inconsistent notes, forgotten plot threads, and difficulty adapting content for different time constraints or player preferences.

**After**: Every piece of campaign content follows a consistent structure that supports quick preparation, flexible execution, and easy modification.

### Core Benefits

- **Systematic Organization**: Every campaign element has a defined place and purpose
- **Flexible Preparation**: Choose detail level based on available time and needs
- **Easy Adaptation**: Modular design allows quick adjustments
- **Collaborative Sharing**: Standard format enables community resource sharing
- **Privacy-Respectful Analytics**: Optional tracking with user-controlled privacy levels
- **Modular Automation**: Choose automation features without all-or-nothing complexity

## 2. The Two-Axis System

### Understanding the Separation

The Enhanced Node Structure operates on **two independent axes** that address different concerns:

| **Axis** | **What it Measures** | **Examples** |
|----------|---------------------|--------------|
| **Narrative Priority** | Does the table absolutely need this scene? | Critical → villain's ritual; Optional → tavern rumor |
| **Schema Depth** | How many fields, tags, automations ride on the node? | Lite → ~6 fields; Comprehensive → full template with JSON validation |

### The Critical Path Concept

**Critical Path**: The essential narrative backbone of your campaign, composed of Critical and Mission nodes that players must experience for campaign completion.

#### Critical Path = Critical Nodes + Mission Nodes

| **Node Type** | **Role in Critical Path** | **Examples** |
|---------------|---------------------------|--------------|
| **Critical** | Key story moments, turning points, revelations (Critical Path) | Major plot reveals, character milestones, campaign-changing decisions |
| **Mission** | Complex, multi-phase challenges that drive narrative (Critical Path) | Multi-session adventures, major quest lines, extended problem-solving |
| **Optional** | Enrichment that can be skipped without breaking story | Side quests, exploration, additional character development |
| **Informational** | Context and exposition delivery | Lore, world-building, background information |

### Campaign Planning Benefits

**Clear Decision Making**: "Is this essential to the main story?" → Critical Path. "Does this add depth but isn't required?" → Supporting Structure.

**Flexible Pacing**: Adjust Optional/Informational density based on available time and player interest while maintaining story integrity through the Critical Path.

**Story Integrity**: The Critical Path ensures campaign completion even if time constraints force skipping Optional content.

### Why This Matters

**The Problem with Single-Axis Thinking**: Previous systems conflated story importance with metadata complexity. This forced users into inappropriate complexity levels based on story needs.

**The Two-Axis Solution**: A Critical node can live in a Lite template (quick one-pager) or a Comprehensive template (full automation). Conversely, you might draft an Optional node in Comprehensive depth if you plan to datamine interactions later.

### Stakeholder Benefits

| **User Type** | **Challenge** | **Solution** |
|---------------|---------------|--------------|
| **Minimalist DM** | Hates populating 10+ metadata slots | Create Critical-Lite nodes in 5 minutes |
| **Tool-Focused DM** | Needs consistent validation for automation | Use Comprehensive profile for full schema compliance |
| **Mentor DM** | Wants progressive complexity for newcomers | Clear upgrade path: Lite → Standard → Comprehensive |

## 3. Depth Profiles Explained

### Lite Profile

**Purpose**: Rapid content creation with minimal overhead
**Creation Time**: 5-10 minutes
**Use Cases**: Quick encounters, time-constrained preparation, simple content

Essential fields only:

- Title and basic identification
- Node type and version
- Summary with key entities and connections
- Primary challenge or content
- Basic success/failure consequences

### Standard Profile

**Purpose**: Comprehensive campaign management with full structure
**Creation Time**: 30-45 minutes
**Use Cases**: Main campaign content, detailed preparation, collaborative development

**All sections from the complete Standard profile structure**, including:

- Enhanced Node Metadata
- GM Focus and Intent
- Character Integration
- Detailed Challenges and Obstacles
- Resource Management
- Session Management
- Consequences and Ramifications

### Upgrade Paths

**Lossless Expansion**: Any profile can be upgraded to a higher complexity level without losing existing content.

1. **Start with Lite** for rapid content creation
2. **Expand to Standard** when you need detailed preparation
3. **Move to Comprehensive** for automation and advanced analytics

## 4. Creating Your First Node

### Step 1: Choose Your Axes

**Narrative Priority**: What type of content is this?

- **Critical**: Key story moments, turning points, revelations (Critical Path)
- **Mission**: Complex, multi-phase challenges that drive narrative (Critical Path)
- **Optional**: Enrichment that can be skipped without breaking story
- **Informational**: Context and exposition delivery

**Schema Depth**: How much detail do you need?

- Lite: Quick creation, minimal fields
- Standard: Full structure and guidance
- Comprehensive: Maximum automation and validation

### Step 2: Select Template

Based on your choices, use the appropriate template:

**Lite Template** (any node type):

``` markdown
# [ID] | [Name]
**Version**: 1.0
**Node Type**: [Critical/Mission/Optional/Informational]
**Profile**: Lite

## Summary
- **Location**: [Where this takes place]
- **Trigger**: [How players encounter this]
- **Entities**: [Key NPCs, creatures, objects]
- **Node Linkages**:
  - **Follows From**: [Previous nodes that can lead to this one]
  - **Connects To**: [Immediate next nodes this can lead to]
  - **Sets Up**: [Future nodes this foreshadows or enables]


## Primary Challenge
[Single, focused description of main obstacle or content]

## Basic Consequence
**Success**: [Positive outcome]
**Failure**: [Negative outcome]
```

### Standard Profile Sections

All Lite sections plus the complete Standard profile structure:

#### Enhanced Node Metadata

Categorization and session planning information including tags, duration, difficulty, and pacing control.

#### GM Focus and Intent

Clear statement of what this node should accomplish, what players should experience, and how it advances the campaign.

#### Character Integration

Specific opportunities for each party member to contribute meaningfully, including class abilities, backgrounds, and personal story connections.

#### Detailed Challenges and Obstacles

Comprehensive breakdown of all potential challenges with multiple resolution approaches, difficulty scaling, and environmental factors.

#### Resource Management

Tracking of party resources including HP, spell slots, equipment durability, and mental/emotional costs.

#### Session Management

Pacing guidance, attention management techniques, and adaptation strategies for different table dynamics.

#### Consequences and Ramifications

Detailed outcomes for different resolution approaches, including immediate effects and long-term campaign implications.

## 5. Section-by-Section Guide

This section provides detailed guidance for each component of the node structure, organized by profile level and complexity.

### Header and Identification (All Profiles)

#### Title Format

**Structure**: `[ID] | [Descriptive Name]`
**Examples**:

- L4-M1 | Temple Showdown with Nezznar
- CH2-C3 | Meeting the Duke
- W-DC-O5 | Hidden Thieves' Guild

#### Node Type Classification

**Critical**: Key story moments, turning points, revelations (Critical Path)
**Mission**: Complex, multi-phase challenges that drive narrative (Critical Path)
**Optional**: Enrichment that can be skipped without breaking story
**Informational**: Context and exposition delivery

#### Profile Declaration

**Lite**: Minimal fields, rapid creation
**Standard**: Full structure and guidance
**Comprehensive**: Maximum automation and validation with modular features

#### Version Control

**Format**: Major.Minor.Patch

- **Major** (1.0 → 2.0): Structural changes or profile upgrades
- **Minor** (1.1 → 1.2): Content additions
- **Patch** (1.1.1 → 1.1.2): Corrections and clarifications

### Summary Section (All Profiles)

Provides immediate context for preparation and execution. Essential for quick reference and campaign navigation.

**Required Components**:

- **Location**: Physical or conceptual space where content occurs
- **Trigger**: Conditions that activate or lead to this node
- **Entities**: All significant NPCs, creatures, objects, or forces involved
- **Node Linkages**: Relationships to other campaign content
  - **Follows From**: [Previous nodes that can lead to this one]
  - **Connects To**: [Immediate next nodes this can lead to]
  - **Sets Up**: [Future nodes this foreshadows or enables]

### Lite Profile Sections (Tutorial) {: #lite-profile-sections-tutorial }

#### Primary Challenge

Single, focused description of the main obstacle or content. Should be specific enough to run immediately but concise enough for quick creation.

**Examples**:

- **Combat**: "Fight 3 goblins (AC 15, HP 7 each) in cramped cave tunnel"
- **Social**: "Convince suspicious merchant (DC 15 Persuasion) to reveal smuggling route"
- **Exploration**: "Navigate trapped corridor (DC 13 Investigation to detect, DC 15 Thieves' Tools to disarm)"

#### Basic Consequence

Simple success/failure outcomes that connect to campaign narrative.

**Format**:

``` markdown
**Success**: [Positive outcome with specific benefits]
**Failure**: [Negative outcome with specific complications]
```

### Standard Profile Additional Sections (Tutorial) {: #standard-profile-additional-sections-tutorial }

#### Enhanced Node Metadata (Standard Profile)

**Tags**: Multi-select categorization for filtering and organization
**Duration**: Estimated time investment for preparation and execution
**Difficulty**: Challenge level appropriate for party capabilities
**Pacing Control**: How this node affects campaign rhythm and momentum

#### GM Focus and Intent (Standard Profile)

**Primary Objectives**: What this node must accomplish for campaign progression
**Player Experience Goals**: Intended emotional and narrative impact
**Success Indicators**: How to recognize when the node has achieved its purpose

#### Character Integration (Standard Profile)

**Individual Spotlight Moments**: Specific opportunities for each party member
**Class Ability Applications**: How different character abilities can contribute
**Background Connections**: Links to character histories and motivations
**Character Development**: Growth opportunities and story advancement

#### Detailed Challenges and Obstacles (Standard Profile)

**Multi-Layered Challenges**: Primary, secondary, and hidden obstacles
**Resolution Approaches**: Combat, social, stealth, environmental, and creative solutions
**Scaling Guidelines**: Adaptation for different party sizes and capabilities
**Environmental Factors**: Terrain, weather, lighting, and atmospheric elements

#### Resource Management (Standard Profile)

**Expected Resource Costs**: HP, spell slots, equipment, time, and social capital
**Recovery Opportunities**: Rest points, healing, and resource restoration
**Resource Tracking**: Systematic monitoring of party capabilities
**Depletion Consequences**: What happens when resources run low

#### Session Management (Standard Profile)

**Preparation Checklist**: Pre-session setup and material organization
**Pacing Techniques**: Managing time and maintaining engagement
**Attention Management**: Keeping all players involved and interested
**Adaptation Strategies**: Responding to unexpected player choices

#### Consequences and Ramifications (Standard Profile)

**Immediate Outcomes**: Direct results of player actions and choices
**Short-term Effects**: Consequences that manifest within the current session or next
**Long-term Ramifications**: Campaign-wide implications and future plot development
**Contingency Planning**: How to maintain narrative momentum after misses or setbacks

## 6. Implementation for Human DMs

### Getting Started

#### Choose Your Starting Profile

**New to Node-Based Campaigns**: Start with Lite profile to learn the system without overwhelming complexity.
**Experienced DMs**: Begin with Standard profile for comprehensive campaign management.
**Tool-Heavy Campaigns**: Use Comprehensive profile with selective automation features.

#### Workflow Integration

**Session Preparation**: Use nodes as preparation checklists and reference materials.
**During Play**: Reference summary sections for quick context and adaptation guidance.
**Post-Session**: Update consequences and connections based on player choices.

### Profile-Specific Workflows

#### Lite Profile Workflow

1. **Identify Content** (2 minutes): Determine node type and basic concept
2. **Write Summary** (2 minutes): Location, trigger, entities, connections
3. **Define Challenge** (3 minutes): Single primary obstacle with specific mechanics
4. **Set Consequences** (3 minutes): Clear success/failure outcomes

**Total Time**: 10 minutes maximum

#### Standard Profile Workflow

1. **Core Structure** (10 minutes): Complete Lite sections with enhanced detail
2. **Character Integration** (10 minutes): Specific opportunities for each party member
3. **Challenge Development** (10 minutes): Multiple approaches and scaling options
4. **Session Planning** (10 minutes): Pacing, resources, and management guidance

**Total Time**: 40 minutes average

#### Comprehensive Profile Workflow

1. **Standard Foundation** (40 minutes): Complete all Standard profile sections
2. **Analytics Configuration** (5 minutes): Set privacy and tracking preferences
3. **Automation Setup** (10 minutes): Enable desired automation features
4. **Integration Testing** (5 minutes): Verify tool connections and validation

**Total Time**: 60 minutes maximum

### Best Practices

#### Content Creation

**Start Simple**: Begin with Lite profiles and upgrade as needed
**Focus on Connections**: Ensure nodes link logically to campaign narrative
**Player-Centric Design**: Always consider how content serves player experience
**Iterative Improvement**: Use feedback and analytics to refine content

#### Organization and Management

**Consistent Naming**: Use clear, searchable node identifiers
**Regular Updates**: Maintain current connections and consequences
**Backup Systems**: Preserve content with version control
**Collaborative Tools**: Share and develop content with other DMs

#### Session Execution

**Preparation Rituals**: Review relevant nodes before each session
**Flexible Adaptation**: Use guidance to respond to unexpected player choices
**Real-time Notes**: Update consequences and connections during play
**Post-Session Review**: Analyze what worked and what needs improvement

## Appendix A: Profile Quick-Start Primers

This appendix provides comprehensive one-page primers for each profile level, enabling immediate implementation without requiring full documentation review.

### A.1 Lite Profile Primer

The Lite Profile primer provides everything needed to create functional campaign content in 5-10 minutes. Perfect for time-constrained preparation, learning the system, or creating simple encounters that maintain campaign connectivity.

**Key Features**: 6 essential fields, 5-minute workflow, immediate usability
**Best For**: Quick encounters, last-minute prep, system learning, backup content

*For complete Lite Profile guidance, see standalone primer document.*

### A.2 Standard Profile Primer

The Standard Profile primer covers the complete Enhanced Node Structure system with 15-20 fields and comprehensive preparation guidance. Ideal for main campaign content requiring detailed preparation and professional presentation.

**Key Features**: Complete structure, 30-45 minute creation, professional quality
**Best For**: Main story content, collaborative development, detailed encounters

*For complete Standard Profile guidance, see standalone primer document.*

### A.3 Comprehensive Profile Primer

The Comprehensive Profile primer provides enterprise-level features including advanced analytics, automation capabilities, and extensive tool integration. Designed for professional campaign management and data-driven optimization.

**Key Features**: 25+ fields, advanced analytics, automation, API integration
**Best For**: Professional campaigns, tool integration, research applications

*For complete Comprehensive Profile guidance, see standalone primer document.*

### Profile Selection Guide

``` markdown
Choose Your Profile Based on Your Needs
═══════════════════════════════════════════════════════════════════════════════

Time Available    │ Content Type      │ Technical Needs   │ Recommended Profile
─────────────────┼──────────────────┼──────────────────┼────────────────────
5-10 minutes     │ Any               │ Basic             │ Lite
30-45 minutes    │ Main campaign     │ Standard          │ Standard
45-60 minutes    │ Professional      │ Advanced          │ Comprehensive
─────────────────┼──────────────────┼──────────────────┼────────────────────
Learning system  │ Any               │ Any               │ Start with Lite
Time pressure    │ Any               │ Any               │ Lite
Collaboration    │ Detailed content  │ Standard+         │ Standard/Comprehensive
Tool integration │ Any               │ API required      │ Comprehensive
Analytics needs  │ Any               │ Data collection   │ Comprehensive
```

### Upgrade Path Visualization

``` markdown
Profile Progression and Feature Evolution
═══════════════════════════════════════════════════════════════════════════════

Lite Profile (5-10 min)
┌─────────────────────────────────────────────────────────────────────────────┐
│ • Header & Summary     • Primary Challenge     • Basic Consequences         │
│ • Resolution Options   • Quick Notes           • Essential Connections      │
└─────────────────────────────────────────────────────────────────────────────┘
                                    ↓ Add Detail
Standard Profile (30-45 min)
┌─────────────────────────────────────────────────────────────────────────────┐
│ All Lite Features Plus:                                                    │
│ • Character Integration    • Detailed Mechanics    • Resource Management   │
│ • Session Planning        • Extended Consequences  • Quality Assurance     │
└─────────────────────────────────────────────────────────────────────────────┘
                                    ↓ Add Technology
Comprehensive Profile (45-60 min)
┌─────────────────────────────────────────────────────────────────────────────┐
│ All Standard Features Plus:                                                │
│ • Analytics Config        • Automation Features    • API Integration       │
│ • Collaboration Tools     • Advanced Validation    • Enterprise Features   │
└─────────────────────────────────────────────────────────────────────────────┘

All upgrades are lossless - content from lower profiles becomes foundation for higher profiles
```

### Quick Decision Matrix

Use this matrix to quickly determine which profile best fits your immediate needs:

| Question | Lite | Standard | Comprehensive |
|----------|------|----------|---------------|
| Do I have less than 15 minutes? | ✅ Yes | ❌ No | ❌ No |
| Is this a simple encounter? | ✅ Yes | ⚠️ Maybe | ❌ No |
| Do I need detailed character integration? | ❌ No | ✅ Yes | ✅ Yes |
| Will I share this with other DMs? | ⚠️ Maybe | ✅ Yes | ✅ Yes |
| Do I need analytics or automation? | ❌ No | ❌ No | ✅ Yes |
| Is this for professional use? | ❌ No | ⚠️ Maybe | ✅ Yes |

**Legend**: ✅ Ideal fit, ⚠️ Possible but consider alternatives, ❌ Not recommended

### Implementation Recommendations

**For New Users**:

1. Start with Lite Profile to learn the system fundamentals
2. Create 3-5 Lite nodes to understand connections and workflow
3. Upgrade one Lite node to Standard to experience the full structure
4. Consider Comprehensive only after mastering Standard Profile

**For Experienced DMs**:

1. Assess your typical preparation time and content complexity needs
2. Choose Standard for most main campaign content
3. Use Lite for quick encounters and backup content
4. Implement Comprehensive for professional or collaborative projects

**For Tool Developers**:

1. Support all three profiles with appropriate user interfaces
2. Provide clear upgrade paths between profiles
3. Implement analytics and automation features gradually
4. Ensure privacy and security compliance for Comprehensive features

The profile primers provide immediate, actionable guidance for implementing the Enhanced Node Structure system at any complexity level, ensuring that users can begin creating professional-quality campaign content immediately while having clear paths for growth and enhancement.
