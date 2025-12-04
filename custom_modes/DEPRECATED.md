# ⚠️ DEPRECATED - Custom Modes

## This folder is deprecated as of v0.8

**Custom Modes have been removed from Cursor 2.1.** The Memory Bank system now uses **Slash Commands** instead.

## Migration Guide

### Old System (Custom Modes)
1. Configure modes in Cursor Settings UI
2. Switch to mode, then type command (e.g., switch to VAN mode, type "VAN")
3. Mode-specific tool access

### New System (Slash Commands)
1. Copy `.cursor/commands/` folder to project
2. Type `/command` directly (e.g., `/van`)
3. All tools always available

## New Command Files

The command definitions are now in:

```
.cursor/commands/
├── van.md       → /van
├── plan.md      → /plan
├── creative.md  → /creative
├── implement.md → /implement
├── reflect.md   → /reflect
├── archive.md   → /archive
└── qa.md        → /qa
```

## Command Mapping

| Old Custom Mode | New Command |
|-----------------|-------------|
| VAN Mode | `/van` |
| PLAN Mode | `/plan` |
| CREATIVE Mode | `/creative` |
| IMPLEMENT Mode | `/implement` |
| REFLECT Mode | `/reflect` |
| ARCHIVE Mode | `/archive` |
| QA (called from any mode) | `/qa` |

## Files in This Folder

These files are kept for reference only and are no longer used:

- `van_instructions.md` - Original VAN mode instructions
- `plan_instructions.md` - Original PLAN mode instructions
- `creative_instructions.md` - Original CREATIVE mode instructions
- `implement_instructions.md` - Original IMPLEMENT mode instructions
- `reflect_archive_instructions.md` - Original REFLECT+ARCHIVE mode instructions
- `mode_switching_analysis.md` - Analysis of mode switching behavior

## Remove This Folder

You can safely delete the `custom_modes/` folder. The system no longer uses it.

## Questions?

See the main [README.md](../README.md) for updated usage instructions.

