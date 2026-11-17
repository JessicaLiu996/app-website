# Structure and visual guidance

Apply these patterns to the current app's verified content and brand. They describe useful layout decisions, not mandatory sections or copied product features.

## Floating navigation

Use a centered, rounded, light capsule with space around it when appropriate. Place the real identity at the left, a few useful entries in the middle, and the main action at the right. A subtle shadow or translucency can separate it from the page while preserving contrast.

Collapse secondary entries on mobile while keeping identity and the primary action visible. The menu needs a close action and keyboard access. Allow for long names, zoom, anchor offsets, and narrow screens.

## Introduction and product visual

Follow the [hero guidance](../SKILL.md#hero): clear title, short explanation, one centered primary action, then a real product visual. Do not invent unsupported platforms or downloads.

Choose recent screenshots or recordings. Keep one main visual, preserve proportions, and use a better source rather than sharpening a low-resolution image to pretend details exist. Follow [framing and scrolling](../SKILL.md#product-framing-and-scrolling) for device displays and long content.

## Feature sections

Use the [feature card guidance](../SKILL.md#feature-cards): one card, two copy levels, real evidence, consistent desktop left/right arrangement, and stacked mobile flow. The frame's default state should expose the feature being discussed.

## Small set of project values

| Value | Basis |
| --- | --- |
| Brand and body fonts | Original assets, verified font identity, usable licensed fonts and fallbacks |
| Text hierarchy | The Skill's desktop/mobile baseline, checked with real wrapping |
| Width and spacing | Readable desktop width, no mobile overflow, aligned content edges |
| Colors | Verified brand values and actual product semantics |
| Containers and motion | Clarify grouping or state without weakening product visibility |
| Download action | Consistent styling and actual destination |

Record values in the existing CSS/configuration. An independent design-system project is not required.

## Visual references

The original workflow drew on the floating navigation of [Doubao](https://www.doubao.com/download/desktop), the introduction-to-product sequence of [WorkBuddy](https://www.workbuddy.cn/), and the concise feature communication of [flomo](https://flomoapp.com/). These sites can change; inspect them if using them for a current decision. They are visual references only, not bundled assets, dependencies, or templates to reproduce.

Judge the result by what a visitor reads first, where attention goes next, and why the next section is useful. Inspect at least a typical desktop and a narrow mobile viewport; repeat only to resolve actual issues.
