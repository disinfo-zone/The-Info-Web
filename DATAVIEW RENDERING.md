# Dataview Static Rendering

This vault uses Dataview queries to auto-generate index tables for people, events, organizations, programs, concepts, and places. Since Obsidian Publish cannot execute Dataview queries, they must be pre-rendered to static Markdown tables before publishing.

## How It Works

- **`DATAVIEW - *.md`** files contain live Dataview queries (local only, excluded from publishing)
- **`MOC - *.md`** and **`KEY INDIVIDUALS.md`** / **`KEY EVENTS.md`** / **`KEY ORGANIZATIONS.md`** / **`KEY PROGRAMS AND PROJECTS.md`** / **`KEY CONCEPTS AND TECH.md`** / **`KEY PLACES.md`** are the static rendered versions (published to web)
- The render script (`C:/temp/render_dataview.py`) reads the DATAVIEW files and generates the static versions

## Workflow

1. Edit pages' frontmatter (`category`, `summary`) in Obsidian as needed
2. Run the render script:
   ```
   py -3 C:/temp/render_dataview.py
   ```
3. Publish changes via Obsidian Publish — the static tables will appear on the website

## Adding a New Category

1. Create `DATAVIEW - MOC - [Category].md` following the existing pattern
2. Run the render script to generate the static `MOC - [Category].md`
3. Add the DATAVIEW file to the publish exclusion list in `.obsidian/publish.json`

## Files

| File | Location | Purpose |
|------|----------|---------|
| Render script | `C:/temp/render_dataview.py` | Reads DATAVIEW files, writes static tables |
| Source templates | `10 - PEOPLE/DATAVIEW - *.md` (20 files) | Live Dataview queries for people |
| Published people tables | `10 - PEOPLE/MOC - *.md`, `KEY INDIVIDUALS.md` (20 files) | Static Markdown tables |
| Source templates | `40 - EVENTS/DATAVIEW - KEY EVENTS.md` | Live Dataview queries for events |
| Published events table | `40 - EVENTS/KEY EVENTS.md` | Static Markdown tables |
| Source template | `20 - ORGANIZATIONS/DATAVIEW - KEY ORGANIZATIONS.md` | Live Dataview queries for organizations |
| Published orgs table | `20 - ORGANIZATIONS/KEY ORGANIZATIONS.md` | Static Markdown tables |
| Source template | `30 - PROGRAMS & PROJECTS/DATAVIEW - KEY PROGRAMS AND PROJECTS.md` | Live Dataview queries for programs |
| Published programs table | `30 - PROGRAMS & PROJECTS/KEY PROGRAMS AND PROJECTS.md` | Static Markdown tables |
| Source template | `50 - CONCEPTS & TECHNOLOGY/DATAVIEW - KEY CONCEPTS AND TECH.md` | Live Dataview queries for concepts |
| Published concepts table | `50 - CONCEPTS & TECHNOLOGY/KEY CONCEPTS AND TECH.md` | Static Markdown tables |
| Source template | `60 - PLACES/DATAVIEW - KEY PLACES.md` | Live Dataview queries for places |
| Published places table | `60 - PLACES/KEY PLACES.md` | Static Markdown tables |
| Publish config | `.obsidian/publish.json` | Excludes DATAVIEW files from web |

## Dry Run

Preview changes without writing files:
```
py -3 C:/temp/render_dataview.py --dry-run
```
