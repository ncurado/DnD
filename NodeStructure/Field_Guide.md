# Roleplay Adventure Node System (RANS) – Field Guide

**Version:** 1.1

## Overview

The Roleplay Adventure Node System (RANS) is a practical framework for organizing D&D 5e campaign content. It turns scattered notes into connected, modular units called "nodes." Each node represents a single encounter, event, scene, or piece of lore, written using a consistent format. This makes it easier to prepare sessions, adapt on the fly, and share content with other DMs.

Each node balances two dimensions:

- **Narrative Priority** – How important is this content to the overall story?
- **Schema Depth** – How much structure and prep detail does it contain?

This two-axis system helps you choose the right level of prep for each piece of your campaign.

Whether you're building a homebrew world, running a published module, or collaborating with others, this guide will help you stay organized, prep efficiently, and run more engaging sessions.

**Author:** Nuno Curado  
**Date:** 1 August 2025  
**Updated:** 8 December 2025 (Enhanced Entities field approach)

## License

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. See [http://creativecommons.org/licenses/by-sa/4.0/](http://creativecommons.org/licenses/by-sa/4.0/) for details, or contact Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

*Appendix B contains the full license text for offline use.*

## Table of Contents

1. [What is the Node Structure?](#what-is-the-node-structure)
2. [The Two-Axis System](#the-two-axis-system)
3. [Depth Profiles Explained](#depth-profiles-explained)
   - [Lite Profile](#lite-profile)
   - [Standard Profile](#standard-profile)
4. [Creating Your First Node](#creating-your-first-node)
5. [Sections Guide](#sections-guide)
6. [Implementation for Human DMs](#implementation-for-human-dms)

## Appendices

- [Appendix A: Profile Quick-Start Primers](#appendix-a-profile-quick-start-primers)

---

## What Is the Node Structure?

This section builds on the Overview by introducing the core principles behind RANS and explaining how its structure supports flexible, organized campaign prep.

Each node balances two dimensions:

- **Narrative Priority** – How important is this content to the overall story?
- **Schema Depth** – How much structure and prep detail does it contain?

This guide helps you use this two-axis approach to prep efficiently and run more engaging sessions—whether you're building a homebrew world, running a published module, or collaborating with others.

### Why Use This System?

**Before:** DMs often have messy notes, lost plot threads, and trouble adjusting for time or player needs.

**After:** Every campaign piece uses a consistent format. You can prepare quickly, run sessions flexibly, and make changes easily.

### Key Benefits

- **Organized Content:** Every campaign part has a clear place and purpose.
- **Flexible Prep:** Pick your detail level based on your needs and available time.
- **Easy Changes:** Modular design lets you adjust content fast.
- **Shareable:** Standard format makes it easy to share with others.
- **Optional Analytics:** Optionally track outcomes while maintaining privacy.
- **Modular Automation:** Add automation features as needed, not all at once.

## The Two-Axis System

### What Are the Two Axes?

The RANS uses **two separate axes**:

| **Axis**            | **What It Means**                                      | **Examples**                                |
|---------------------|--------------------------------------------------------|---------------------------------------------|
| Narrative Priority  | How important is this scene to the main story?         | Critical: villain's ritual; Optional: tavern rumor   |
| Schema Depth        | How much detail and structure does the node include?   | Lite: ~6 fields; Standard: full template, validation |

### Understanding the Critical Path

**Critical Path:** The main storyline of your campaign, made up of Critical and Mission nodes. Players must experience these to finish the campaign.

#### Critical Path = Critical Nodes + Mission Nodes

| **Node Type**   | **Role**                                 | **Examples**                                  |
|-----------------|------------------------------------------|-----------------------------------------------|
| Critical        | Key story events, turning points         | Major reveals, character milestones           |
| Mission         | Multi-phase, story-driving challenges    | Main quests, multi-session adventures         |
| Optional        | Extra content, can be skipped            | Side quests, extra character scenes           |
| Informational   | Lore, background, context                | World-building, history, exposition           |

### Why Use Two Axes?

**Clear Choices:** Decide if content is essential (Critical Path) or extra (Optional/Informational).

**Flexible Pacing:** Adjust the amount of optional content depending on your group's time and interests, without breaking the main story.

**No Forced Complexity:** You can make a Critical node simple (Lite) or detailed (Standard), and vice versa for Optional nodes.

### Who Benefits from Each Profile?

Here's how common DM styles align with the RANS Profiles to support your prep and play needs.

| **DM Style**        | **Core Need or Challenge**                                    | **Best Starting Profile**                      |
|---------------------|---------------------------------------------------------------|------------------------------------------------|
| Minimalist          | Prep time is limited; wants fast, clean structure             | **Lite** – fast setup with essential details   |
| Storyteller         | Focuses on narrative flow, not deep mechanics                 | **Lite**, optionally upgrade for session depth |
| Worldbuilder        | Loves lore, factions, and setting detail                      | **Standard** – supports structure and scope    |
| Improviser          | Reacts to players; needs flexible reference points            | **Lite** – modular, easy to adapt              |
| Tactician           | Enjoys crunchy challenges and dynamic encounters              | **Standard** – better for layered obstacles    |
| Tool-Driven         | Uses VTTs, automation, and digital tools                      | **Standard** – includes full metadata          |
| Mentor              | Teaching or guiding others through examples                   | **Lite → Standard** progression recommended    |

## Depth Profiles Explained

### Lite Profile

**Purpose:** Fast content creation with minimal detail  
**Time to Create:** 5–10 minutes  
**Best For:** Quick encounters, last-minute prep, simple content

Includes only the basics:

- Title and identification
- Node type and version
- Summary (key people, places, connections, **structured entities**)
- Main challenge or content
- Basic success and failure outcomes

### Standard Profile

These profiles represent the schema depth axis of RANS, determining how much structure each node includes.

**Purpose:** Full-featured campaign management  
**Time to Create:** 30–45 minutes  
**Best For:** Main campaign content, detailed prep, collaboration

Includes everything from Lite, plus:

- Detailed metadata
- GM intent and focus
- Character integration
- Detailed challenges and options
- **Enhanced entity management with structured format**
- Resource tracking
- Session management
- Full consequences and follow-ups

### Upgrading Nodes

Upgrading a node from Lite to Standard does not require rewriting existing content—only adding additional details, such as character integration, pacing tools, and resource tracking. All Lite fields are preserved and reused within the Standard format.

## Creating Your First Node

### Step 1: Decide on Narrative Priority and Detail

**Narrative Priority:** What is this node's role?

- **Critical:** Key story event (main story)
- **Mission:** Major, multi-step challenge (main story)
- **Optional:** Extra content, not required
- **Informational:** Lore or background

**Schema Depth:** How much detail do you want?

- Lite: Simple, fast setup
- Standard: Full structure

### Step 2: Use the Right Template

**Lite Template (for any node type in RANS):**

```markdown
# [ID] | [Name]
**Version:** 1.0 <!-- Node template version; separate from Guide version -->
**Node Type:** [Critical/Mission/Optional/Informational]
**Profile:** Lite

## Summary
- **Location:** [Where it happens]
- **Trigger:** [How players reach this node]
- **Entities:** [Structured format: NPCs: [list]; Creatures: [list]; Items: [list]]
- **Node Linkages:**
  - **Follows From:** [What comes before]
  - **Connects To:** [What comes next]
  - **Sets Up:** [Future content this leads to]

## Primary Challenge
[Brief description of the main obstacle or content]

## Basic Consequence
**Success:** [What happens if players succeed]
**Failure:** [What happens if they fail]
```

Using the right template ensures each node is consistent and easy to reference during play.

### 4.1 Example: Lite Node in Use

```markdown
# L2-O1 | Goblin Ambush on the Ridge
**Version:** 1.0  
**Node Type:** Optional  
**Profile:** Lite

## Summary
- **Location:** Ridge trail near Phandalin
- **Trigger:** Players take the mountain pass shortcut
- **Entities:** NPCs: Captured merchant (Linene's cousin); Creatures: 3 Goblins (Cragmaw scouts); Items: Stolen supply crate, Redbrand letter
- **Node Linkages:**
  - **Follows From:** CH1-O2 (Wilderness Travel)
  - **Connects To:** CH1-M2 (Cave Hideout)
  - **Sets Up:** Redbrand connections if goblins interrogated

## Primary Challenge
The goblins attack from above with bows while one attempts to flee with stolen supplies.

## Basic Consequence
**Success:** Players recover the crate and find a Redbrand-marked letter.  
**Failure:** Goblins escape with supplies; players suffer a morale setback and lose access to a potion.
```

### Standard Profile Sections

The Standard profile in RANS includes all Lite fields, plus:

#### Enhanced Node Metadata

Tags, estimated session time, difficulty, and pacing tools.

#### GM Focus and Intent

What this node is meant to achieve and how it moves the campaign forward.

#### Character Integration

Ways for each character to shine—class abilities, backgrounds, or personal arcs.

#### Detailed Challenges and Obstacles

All possible challenges, different ways to solve them, scaling, and environment notes.

#### Enhanced Entity Management

For Standard nodes, the Entities field can include more detailed categorization:

```markdown
**Entities:** NPCs: [important characters]; Creatures: [monsters/beasts]; Key Monsters: [boss encounters]; Allies: [friendly NPCs]; Enemies: [hostile characters]; Items: [important objects]
```

#### Resource Management

Track party resources: HP, spells, equipment, and mental and emotional strain.

#### Session Management

Tips for pacing, keeping players engaged, and adapting to surprises.

#### Consequences and Ramifications

Immediate and long-term outcomes for different player choices.

## Sections Guide

This section explains every part of the RANS structure. By using these sections, you can build nodes that are structured, clear, and easy to run.

### Header and Identification (All Profiles)

#### Title Format

**Format:** `[ID] | [Descriptive Name]`  
**Examples:**

- L4-M1 | Temple Showdown with Nezznar
- CH2-C3 | Meeting the Duke
- W-DC-O5 | Hidden Thieves' Guild

#### Node Type

- **Critical:** Main story event
- **Mission:** Large, story-driving challenge
- **Optional:** Extra, skippable content
- **Informational:** Lore or background

#### Profile Declaration

- **Lite:** Minimal, fast setup
- **Standard:** Full detail and structure

#### Version Control

**Format:** Major.Minor.Patch

- **Major:** Big changes or upgrades
- **Minor:** New content added
- **Patch:** Small fixes or clarifications

### Summary Section (All Profiles)

Gives quick context for prep and play. Helps you find and use RANS nodes quickly.

**Include:**

- **Location:** Where it happens (physical or conceptual)
- **Trigger:** How this node starts
- **Entities:** Structured format for all NPCs, creatures, and items in the node
- **Node Linkages:**
  - **Follows From:** What leads to this node
  - **Connects To:** What this node leads to next
  - **Sets Up:** Future content set up by this node

### Enhanced Entities Field

The Entities field is the central place for tracking all characters, creatures, and important objects in a node. Use a structured format for best results:

#### Lite Profile Format:
```
NPCs: [character names]; Creatures: [monster names]; Items: [important objects]
```

#### Standard Profile Format:
```
NPCs: [important characters]; Creatures: [monsters/beasts]; Key Monsters: [boss encounters]; Allies: [friendly NPCs]; Enemies: [hostile characters]; Items: [important objects]
```

#### Examples:

**Lite:**
```
Entities: NPCs: Guard Captain Reese, Merchant Tobias; Creatures: 2 Dire Wolves; Items: Magic sword, Ancient map
```

**Standard:**
```
Entities: NPCs: Guard Captain Reese (quest giver); Creatures: 2 Dire Wolves (patrol); Key Monsters: Alpha Wolf (CR 3, pack leader); Allies: Merchant Tobias (information source); Enemies: Bandit Leader Vex (recurring villain); Items: Magic sword (+1 longsword), Ancient map (leads to treasure)
```

### Lite: Primary Challenge

One clear description of the main obstacle or content. Should be short and ready to run.

**Examples:**

- **Combat:** "Fight 3 goblins (AC 15, HP 7) in a cramped cave"
- **Social:** "Convince the suspicious merchant (DC 15 Persuasion) to reveal the smuggling route"
- **Exploration:** "Navigate a trapped corridor (DC 13 Investigation to spot, DC 15 Thieves' Tools to disarm)"

### Lite: Basic Consequence

Simple outcomes for success or failure, linked to the story.

**Format:**

```markdown
**Success:** [Describe the good outcome]
**Failure:** [Describe the setback or complication]
```

### Standard: Enhanced Node Metadata

- **Tags:** For sorting and filtering
- **Duration:** Estimated prep/play time
- **Difficulty:** How tough is the challenge
- **Pacing Control:** How this node affects session flow

### Standard: GM Focus and Intent

- **Objectives:** What this node should achieve
- **Player Experience:** What you want players to feel or learn
- **Success Indicators:** How you know the node worked

### Standard: Character Integration

- **Spotlights:** Ways for each character to shine
- **Abilities:** How character skills or powers help
- **Backgrounds:** Hooks to character stories
- **Development:** Growth or change opportunities

### Standard: Detailed Challenges and Obstacles

- **Layers:** Main, secondary, and hidden challenges
- **Resolutions:** Combat, social, stealth, creative, environmental
- **Scaling:** Adjust for party size and ability
- **Environment:** Terrain, weather, lighting, etc.

### Standard: Resource Management

- **Costs:** HP, spells, equipment, time, social standing
- **Recovery:** Rest spots, healing, resource refresh
- **Tracking:** How to monitor party resources
- **Depletion:** What happens if resources run out

### Standard: Session Management

- **Prep Checklist:** What to set up before the session
- **Pacing:** Keep things moving and engaging
- **Attention:** Make sure all players are involved
- **Adaptation:** Tips for reacting to surprises

### Standard: Consequences and Ramifications

- **Immediate:** What happens right away
- **Short-term:** Effects in this or next session
- **Long-term:** Impacts on the campaign or world
- **Contingency:** How to keep the story moving after setbacks

## Implementation for Human DMs

### Getting Started

This section helps you start applying RANS, turning scattered ideas into actionable, organized content.

#### Pick Your Starting Profile

- **New to Node-Based Prep:** Start with Lite for a simple introduction.
- **Experienced DMs:** Use Standard for full campaign management.

#### How to Use Nodes

- **Before Sessions:** Use nodes as prep checklists and quick references.
- **During Sessions:** Check the summary for context and adapt as needed.
- **After Sessions:** Update consequences and connections based on what happened.

### Profile Workflows

#### Lite Profile Workflow

1. **Identify Content** (2 min): Decide node type and main idea.
2. **Write Summary** (3 min): Fill in location, trigger, structured entities, connections.
3. **Define Challenge** (3 min): Write the main obstacle and mechanics.
4. **Set Consequences** (2 min): Add clear outcomes for success/failure.  
**Total:** 10 minutes or less.

#### Standard Profile Workflow

1. **Core Structure** (10 min): Fill out Lite sections in more detail.
2. **Character Integration** (10 min): Identify ways each character can contribute.
3. **Challenge Development** (10 min): Include options, scaling, and depth.
4. **Entity Details** (5 min): Expand Entities field with detailed descriptions.
5. **Session Planning** (5 min): Add pacing, resource, and management notes.  
**Total:** About 40 minutes.

### Best Practices

#### Content Creation

- **Start Simple:** Use Lite, then upgrade as needed.
- **Link Nodes:** Make sure each node connects to the story.
- **Think Player-First:** Design with player experience in mind.
- **Use Structured Entities:** Follow the format for better organization and automation.
- **Iterate and Improve:** Use feedback to improve nodes.

#### Organization and Management

- **Consistent Names:** Use clear, searchable IDs.
- **Keep Updated:** Regularly review and update nodes.
- **Back Up:** Use version control or backups.
- **Collaborate:** Share and build with other DMs.

#### Running Sessions

- **Prep Ritual:** Review relevant nodes before playing.
- **Stay Flexible:** Be ready to adapt to player choices.
- **Take Notes:** Update nodes during or after play.
- **Review:** After the session, note what worked and what to improve.

## Appendix A: Profile Quick-Start Primers

This appendix gives you one-page overviews for each RANS profile, so you can get started fast.

### A.1 Lite Profile Primer

**Time Investment:** 5-10 minutes per node  
**Best For:** Quick encounters, last-minute prep, simple content

**Essential Fields:**
- Header (ID, Name, Version, Type, Profile)
- Summary (Location, Trigger, Structured Entities, Node Linkages)
- Primary Challenge
- Basic Consequence

**Entities Format:**
```
NPCs: [character names]; Creatures: [monster names]; Items: [important objects]
```

**Quick Tips:**
- Keep descriptions brief but actionable
- Focus on what players will encounter
- Use structured Entities format for better organization
- Link to other nodes for campaign flow

### A.2 Standard Profile Primer

**Time Investment:** 30-45 minutes per node  
**Best For:** Main campaign content, detailed prep, collaboration

**All Lite Fields Plus:**
- Enhanced Node Metadata
- GM Focus and Intent
- Character Integration
- Detailed Challenges and Obstacles
- Enhanced Entity Management with detailed descriptions
- Resource Management
- Session Management
- Consequences and Ramifications

**Enhanced Entities Format:**
```
NPCs: [detailed characters]; Creatures: [monsters]; Key Monsters: [bosses]; Allies: [friends]; Enemies: [foes]; Items: [objects]
```

**Quick Tips:**
- Build on Lite foundation, don't rewrite
- Use detailed Entities format for comprehensive tracking
- Include scaling options for different party compositions
- Plan for multiple session outcomes

---

**Version 1.1 Changes:**
- Enhanced Entities field with structured format for better organization and automation support
- Added comprehensive examples showing proper Entities usage for both Lite and Standard profiles
- Updated workflow guidance to include structured entity management
- Improved examples throughout to demonstrate the enhanced Entities approach
- Maintained backward compatibility while adding new organizational capabilities

