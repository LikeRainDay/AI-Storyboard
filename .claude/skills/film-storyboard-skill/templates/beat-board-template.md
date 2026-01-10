# Beat Board Template - 9-Panel Grid Layout

---

**Episode**: ep{XX}
**Title**: [Episode Title]
**Generated**: [Date/Time]
**Language**: [Output language - zh-CN, en-US, ja-JP, ko-KR]
**Visual Style**: [Style keywords]
**Aspect Ratio**: [e.g., 16:9, 9:16, 1:1]
**Target Model**: [e.g., Gemini Imagen 3, Midjourney v6]

---

## Purpose

This beat board represents the **visual baseline** for the episode using a **3x3 grid layout** (9 panels total).

These 9 images establish:

- Character canonical appearance
- Key settings and environments
- Lighting and color palette approach
- Overall visual style

**Grid Layout**: 3 rows × 3 columns (total 9 panels)

```
Row 1: [Panel 1] [Panel 2] [Panel 3]
Row 2: [Panel 4] [Panel 5] [Panel 6]
Row 3: [Panel 7] [Panel 8] [Panel 9]
```

---

## Character Style Guide

**IMPORTANT**: Use identical character descriptions across all 9 panels for consistency.

**[Character Name 1]**:

- Age: [age]
- Hair: [color, style, length]
- Eyes: [color]
- Clothing: [detailed description]
- Distinctive Features: [any unique markers]

**[Character Name 2]**:

- [Same structure]

---

## Panel 1: [Beat Name/Title]

**Grid Position**: Row 1, Column 1 (Top Left)
**Beat Reference**: Beat 1 from beat-breakdown-ep{XX}.md
**Narrative Context**: [What's happening in this moment]

**Image Prompt**:

```
[Shot type], [camera angle]. [Subject description] [action/pose] [setting]. [Lighting]. [Style keywords].

[Full narrative descriptive prompt, 80-150 words]

--ar 16:9
```

**Key Visual Elements**:

- [Element 1]
- [Element 2]
- [Element 3]

---

## Panel 2: [Beat Name/Title]

**Grid Position**: Row 1, Column 2 (Top Center)
**Beat Reference**: Beat 2
**Narrative Context**: [What's happening]

**Image Prompt**:

```
[Full prompt, 80-150 words, maintaining character consistency]

--ar 16:9
```

**Key Visual Elements**:

- [List]

---

## Panel 3: [Beat Name/Title]

**Grid Position**: Row 1, Column 3 (Top Right)
**Beat Reference**: Beat 3
**Narrative Context**:

**Image Prompt**:

```
[Full prompt, 80-150 words]

--ar 16:9
```

**Key Visual Elements**:

- [List]

---

## Panel 4: [Beat Name/Title]

**Grid Position**: Row 2, Column 1 (Middle Left)
**Beat Reference**: Beat 4
**Narrative Context**:

**Image Prompt**:

```
[Full prompt, 80-150 words]

--ar 16:9
```

**Key Visual Elements**:

- [List]

---

## Panel 5: [Beat Name/Title]

**Grid Position**: Row 2, Column 2 (Middle Center)
**Beat Reference**: Beat 5
**Narrative Context**:

**Image Prompt**:

```
[Full prompt, 80-150 words]

--ar 16:9
```

**Key Visual Elements**:

- [List]

---

## Panel 6: [Beat Name/Title]

**Grid Position**: Row 2, Column 3 (Middle Right)
**Beat Reference**: Beat 6
**Narrative Context**:

**Image Prompt**:

```
[Full prompt, 80-150 words]

--ar 16:9
```

**Key Visual Elements**:

- [List]

---

## Panel 7: [Beat Name/Title]

**Grid Position**: Row 3, Column 1 (Bottom Left)
**Beat Reference**: Beat 7
**Narrative Context**:

**Image Prompt**:

```
[Full prompt, 80-150 words]

--ar 16:9
```

**Key Visual Elements**:

- [List]

---

## Panel 8: [Beat Name/Title]

**Grid Position**: Row 3, Column 2 (Bottom Center)
**Beat Reference**: Beat 8
**Narrative Context**:

**Image Prompt**:

```
[Full prompt, 80-150 words]

--ar 16:9
```

**Key Visual Elements**:

- [List]

---

## Panel 9: [Beat Name/Title]

**Grid Position**: Row 3, Column 3 (Bottom Right)
**Beat Reference**: Beat 9
**Narrative Context**:

**Image Prompt**:

```
[Full prompt, 80-150 words]

--ar 16:9
```

**Key Visual Elements**:

- [List]

---

## 3x3 Grid Generation Instructions

**IMPORTANT for AI Image Generation**:

To generate the complete 3x3 panel grid:

### Option 1: Generate Individual Panels, Then Assemble

1. Generate each panel separately using the prompts above
2. Assemble the 9 images into a 3x3 grid layout using image editing software
3. Maintain consistent spacing and alignment

### Option 2: Use Grid-Aware Generation (if supported)

Some AI tools (like Midjourney, ComfyUI workflows) support grid layouts:

- Specify `--tile 3x3` or equivalent grid parameter
- Or use custom ComfyUI node for multi-panel generation

### Option 3: Prompt-Based Grid (Advanced)

Include in each prompt: "Part of a 3x3 storyboard grid, position [X]"

- Example for Panel 1: "...Part of a 3x3 storyboard grid, top-left panel..."

---

## Character Consistency Check

**[Character Name 1]**:

- Canonical Description: [From style guide above]
- Appears in Panels: [List panel numbers]
- Consistency Verification: ✓/✗
  - [ ] All instances use identical hair description
  - [ ] All instances use identical clothing
  - [ ] All instances use identical physical features

**[Character Name 2]**:

- Canonical Description:
- Appears in Panels:
- Consistency Verification: ✓/✗

---

## Style Consistency Check

- [ ] All prompts use narrative descriptive style (not keyword lists)
- [ ] Style keywords applied uniformly across all 9 prompts
- [ ] Shot types and camera angles specified for each
- [ ] Lighting approach consistent with project style
- [ ] Each prompt is 80-150 words
- [ ] All prompts written in target language: [Language]

---

## Generation Metadata

- **Model**: [e.g., Gemini Imagen 3]
- **Settings**: [e.g., Guidance scale, temperature]
- **Grid Layout**: 3×3 (9 panels total)
- **Individual Panel Size**: [e.g., 1024×576 for 16:9]
- **Final Grid Size**: [e.g., 3072×1728 for assembled grid]

---

## Notes

[Any creative decisions, variations, or considerations for generation]

---

**Status**: ✓ Ready for Image Generation
**Next Steps**:

1. Generate 9 individual images using prompts above
2. Assemble into 3x3 grid layout
3. Review complete grid for visual consistency
4. Use `/sequence ep{XX}` to expand select beats into 4-panel sequences
