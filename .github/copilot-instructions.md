# Copilot Instructions for "Children of Ash"

## Project Overview
"Children of Ash" is a narrative-driven campaign set in the Lancer system. It explores themes of war aftermath, fractured loyalties, and rogue AI dangers in the colony world of Virelia. The project is structured as a collection of markdown files organized by categories such as factions, locations, NPCs, and events.

## Key Directories
- **Events/**: Contains markdown files detailing significant incidents in the campaign.
- **Factions/**: Documents the major groups and organizations, including subfolders for specific factions like PMC and Warband.
- **Locations/**: Describes key places in the setting, such as Virelia and its surrounding areas.
- **NPCs/**: Profiles important characters in the campaign.

## Conventions and Patterns
- **File Naming**: Use descriptive names for markdown files, reflecting their content (e.g., `Noble Rook Confederacy.md` for faction details).
- **Content Structure**: Each markdown file should follow a clear structure with optional entries depending on the subject:
  - **Title**: At the top, generally matching the filename. (Header 1)
  - **Type**: (Optional: Events, Locations) Identifier of specific content type.
  - **Callsign**: (Optional: Lancer Pilots) Unique identifier for pilots.
  - **Affiliation**: (Optional: NPCs, Characters) Groups the subject is associated with.
  - **Abbreviation**: (Optional: Factions) Shortened form of the faction name.
  - **Summary**: A brief overview of the subject. (No header)
  - **Details**: In-depth information, organized into sections. (Header 3, bullet points for content subcategories)
- **Cross-Referencing**: Use relative links to connect related files (e.g., linking NPC profiles to faction descriptions).

## Contributor Workflows
- **Adding New Content**:
  1. Create a new markdown file in the appropriate directory.
  2. Follow the content structure conventions.
  3. Update related files with links to the new content.
- **Editing Existing Content**:
  1. Ensure consistency in formatting and structure.
  2. Maintain cross-references when updating details.
- **Suggestions**:
  - Propose new content ideas or improvements to existing files.
  - Discuss potential changes with the team before implementation.

## Integration Points
- **External Resources**: The project references external tools and documents for the Lancer system, such as the [Lancer System Reference Document](https://compcon.app/) and [Lancer Cheat Sheets](https://lancer-rules.carrd.co/).
- **Narrative Cohesion**: Ensure all content aligns with the campaign's themes and setting.

## Examples
- **Faction File Example**:
  ```markdown
  # Noble Rook Confederacy

  A militaristic faction with a strong history of nobility and high-houses.

  ## Details
  - **Leadership**: Rotating cast of noble houses who control industry and trade.
  - **Goals**: Reclaim lost territories, resist Union oversight, and quell growing AI dangers.
  ```

- **NPC File Example**:
  ```markdown
  # Peeny Weeny

  **Callsign:** `PEENY`  
  **Affiliation:** [Example](/Factions/PMC/Example.md)  

  <img src="link-to-peeny-weeny-image" width=200>  

  A rogue AI specialist with ties to the [Union](/Factions/The%20Union.md) and a grudge against the [Echo Reliquary](/Factions/Warband/Echo%20Reliquary.md).

  ## Details
  - **Background**: Former Union scientist.
  ```

- **Session File Example**:
  ```markdown
  # "Session Name"
  ## Act #, Session #

  **Key Characters**: [Character A](/NPCs/CharacterA.md), [Character B](/NPCs/CharacterB.md)

  Session summary text goes here.

  ## Details
  - **Chronological Subheader 1**:
    - Info about the session's events relevant to the subheading
  - **Chronological Subheader 2**:
    - Info about the session's events relevant to the subheading
  ```

## Notes for AI Agents
- Focus on maintaining narrative consistency and thematic alignment.
- Prioritize clarity and organization in markdown files.
- Use examples as templates for new content.
- Always consult the future-plans.md file for guidance on upcoming content.

---
