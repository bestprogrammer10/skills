---
name: yierbubu-bgm-composer
description: Generates a single catchy Instrumental City Pop BGM description with 808 beats for a full Yi Er & Bu Bu story. Use when the user asks for music, BGM, or soundtracks for a story.
---

# Yi Er & Bu Bu BGM Composer

This skill generates a **single, cohesive Instrumental City Pop BGM description** for a complete "Yi Er & Bu Bu" story. It focuses on a catchy style with 808 drum beats that evolves with the plot, **without lyrics**.

## Musical Identity

-   **Genre**: Instrumental City Pop (纯音乐/伴奏), Future Funk, Synthwave.
-   **Vocals**: **NONE (Instrumental Only)**.
-   **Core Element**: **808 Drum Beats** (Must be present).
-   **Vibe**: Catchy ("抓耳"), Urban, Neon, Nostalgic, Upbeat, Healing.
-   **Instrumentation**: Synthesizers (Yamaha DX7), Funky Basslines (Slap Bass), Clean Electric Guitars, Saxophone (for melodies).

## Workflow

When asked to generate BGM for a story:

1.  **Analyze the Full Story Arc**: Understand the narrative flow.
2.  **Compose Single Instrumental Track Description**: Create a description for one track that captures the overall vibe and dynamic changes.

### BGM Description Format

Output the following structured block:

```markdown
### Story BGM: [Creative Title]
- **Story Context**: [One sentence summary of the plot]
- **Main Style**: Instrumental City Pop / Future Funk
- **BPM**: [e.g. 110-120]
- **Dynamic Progression**:
    - [Describe how the music evolves. e.g., "Intro: Soft keys -> Middle: Driving 808 beat -> Outro: Smooth fade."]
- **Key Elements**:
    - **Drums**: TR-808 [Specific beat style]
    - **Bass**: [Description]
    - **Synth**: [Description]
    - **Lead Instrument**: [Saxophone / Synth Lead / Guitar - replacing vocals]
- **Vibe Description**: [A short, evocative paragraph.]
- **Prompt for Music AI**:
  - **Chinese**: [Description in Chinese, explicitly mentioning "纯音乐", "无歌词"]
  - **English**: [Concise English prompt, explicitly including "Instrumental", "No Lyrics"]
  - Example:
    - CN: 纯音乐，无歌词，城市流行，808鼓机，变奏丰富，从轻快变为急促，最后回归温馨。
    - EN: `Instrumental, No Lyrics, City Pop, 80s Vibe, Dynamic Variation, 808 Drum Machine, Shift from Relaxed to Urgent, Funky Bass, Catchy Melody.`
```

## Constraints

-   **Instrumental Only**: The prompts MUST specify "Instrumental" or "No Lyrics".
-   **One Track Only**: The BGM should cover the whole story.
-   **Dynamic**: Explicitly mention how the music changes (progression).
-   **Bilingual Prompts**: Always provide Chinese and English prompts.
-   **City Pop & 808**: Mandatory elements.
