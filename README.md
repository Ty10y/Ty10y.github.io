# Ty10y's GitHub

This repository contains the source for my personal landing page: https://Ty10y.github.io

## Adding a project

Projects are listed in a JSON array inside `index.html` (`<script id="projects-data">`).
Add one object to the array and the page renders the card, places it in its category
section, adds its tag to the filter chips, and features it in the "Latest" slideshow
if it is one of the 3 most recently added.

```json
{
  "title": "My Project",
  "url": "https://ty10y.github.io/My-Project/",
  "icon": "🌿",
  "desc": "One or two sentences.",
  "tag": "Tool",
  "category": "tools",
  "added": "2026-10-08",
  "updated": "2026-10-20",
  "source": "https://github.com/Ty10y/My-Mod",
  "download": "https://www.curseforge.com/minecraft/mc-mods/my-mod"
}
```

- `category`: `garden`, `tools`, or `mods` (sections are defined in `CATEGORIES` in the page script).
- `added` / `updated`: drive the "New" / "Updated" badges (shown for 30 days).
- `source` / `download`: optional. Projects with `source` get Download + Source buttons.
  Without `download`, Download links to the repo's latest GitHub release.

## Current projects

| **Project**                     | **Link**                                     |
| ------------------------------- | -------------------------------------------- |
| Pocket Plant Weed Almanac       | https://Ty10y.github.io/Pocket-Weed-Almanac/ |
| Garden Bed Planner              | https://Ty10y.github.io/Garden-Bed-Planner/  |
| Poison Ivy ID Quiz              | https://ty10y.github.io/Poison-Ivy-ID/       |
| Gantt Chart                     | https://Ty10y.github.io/Gantt-Chart/         |
| Scrolling Text                  | https://ty10y.github.io/Scrolling-Text/      |
| Icon Cropping Tool              | https://ty10y.github.io/Icon-Cropping-Tool/  |
| Draw SVG                        | https://ty10y.github.io/Draw-SVG/            |
| Arrow Fletching (Minecraft mod) | https://github.com/Ty10y/Arrow-Fletching     |
| Player Maps (Minecraft mod)     | https://github.com/Ty10y/Player-Maps         |
| Torch Slot (Minecraft mod)      | https://github.com/Ty10y/Torch-Slot          |

Languages: HTML (site is built primarily with static HTML/CSS/JS)
