# Web Design: Landing page

## Description
A modular UI design prompt focused on high-contrast aesthetics and specific content layout. This structure is highly effective for ensuring the AI doesn't lose the "vibe" (Theme) while trying to process the "copy" (Content).

## The Prompt
> **[IDEA]** A landing page for a running podcast named “The Pacing Project”.
> 
> **[THEME]** Modern, edgy, and high contrast. Use black and white with hard angles.
> 
> **[CONTENT]** A hero section with the headline “Stories and lessons about racing and proper pacing” and links to podcast platforms.

## Metadata
- **Model:** Stitch by Google / Nano Banana
- **Category:** Web Design / UI
- **Technique:** Modular Tags (Idea/Theme/Content)
- **Tags:** #web-design #ui-ux #high-contrast #minimalist #podcasting
- **Date Created:** 2026-02-12

# [Template] Modular Web Design

## Description
A reusable template for generating landing page concepts. Swap the variables in the brackets to pivot between industries and styles while maintaining a consistent structure.

## The Template
> **[IDEA]** {{Business_Idea}}
> 
> **[THEME]** {{Visual_Style_and_Palette}}
> 
> **[CONTENT]** {{Hero_Copy_and_Requirements}}

## Usage Instructions
1. Copy the prompt above.
2. Replace the `{{tags}}` with your specific project needs.
3. Paste into the AI model.

## Metadata
- **Category:** UI/UX
- **Complexity:** Low
- **Model Recommendation:** Stitch by Google / Image 4

# [Prompt Title] SVG Connection: Data Pipeline Visualization

## Description
A structured blueprint for generating interactive SVG components. This prompt uses a JSON schema to define a "Data Pipeline" UI—specifically a toggle/slider that visualizes the flow of chemical data (Claims, CAS#, SMILES) between a Patent source and a PubChem destination. It includes specific states for "Off" (broken link) and "On" (active flow with animated payloads).

## The Prompt
> Generate an SVG component based on the following structured concept:
> 
> {
>   "svg_concept_design": {
>     "global_settings": {
>       "design_style": "flat design",
>       "layout_orientation": "horizontal",
>       "interaction_type": "toggle switch / slider"
>     },
>     "static_components": {
>       "track": {
>         "element": "pipeline line",
>         "default_appearance": "thin gray dashed line"
>       },
>       "left_node": {
>         "concept": "Source / Origin",
>         "icon_description": "small patent document icon (rectangle with folded corner)",
>         "label": "PAT"
>       },
>       "right_node": {
>         "concept": "Destination / Database",
>         "icon_description": "PubChem-style node (hexagon with simple benzene ring outline)",
>         "label": "PubChem"
>       },
>       "control_knob": {
>         "concept": "Flow control valve",
>         "icon_description": "circular data node with arrowhead pointing right"
>       }
>     },
>     "states_and_animations": {
>       "state_off": {
>         "knob_position": "left, next to origin node",
>         "track_appearance": "broken gray dashed line with no fill",
>         "center_indicator": "small red 'X' or broken chain link symbol in center gap"
>       },
>       "transition_to_on": {
>         "trigger": "slide knob right",
>         "knob_action": "moves to the right node",
>         "track_change": "becomes solid blue line",
>         "background_change": "lightly tints pale blue to indicate active flow",
>         "data_payloads": {
>           "shape": "small rectangular boxes",
>           "labels": [
>             "claim text",
>             "CAS#",
>             "SMILES"
>           ],
>           "animation": "animate steadily rightward along the line at constant speed"
>         },
>         "success_indicator": "green checkmark or 'linked' badge appears briefly next to destination node upon knob arrival"
>       },
>       "transition_to_off_reverse": {
>         "trigger": "slide knob left",
>         "data_payloads_action": "stop and fade",
>         "track_change": "reverts to dashed gray",
>         "success_indicator_action": "checkmark disappears"
>       }
>     }
>   }
> }

## Metadata
- **Model:** Gemini 3.1 Pro
- **Category:** SVG Design / UI/UX
- **Technique:** Structured Object Prompting (JSON)
- **Tags:** #SVG #UI-UX #Data-Flow #JSON-Prompt #Interactive #Animation
- **Date Created:** 2026-02-20
