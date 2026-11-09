# Agent instructions

## Skills: Razgon 2D Studio (v0.3.0)

Project skills live in `.claude/skills/`. Before starting a matching task, read the relevant `SKILL.md` and follow it.

| Skill | When to use |
|---|---|
| `.claude/skills/make-2d-video/SKILL.md` | Full pipeline: voiceover → animated stick-figure video (MP4) |
| `.claude/skills/new-video/SKILL.md` | `/new-video`: intake, studio install, timestamps, shot list |
| `.claude/skills/video-styles/SKILL.md` | `/video-styles`: style comparison and custom looks |
| `.claude/skills/render-video/SKILL.md` | `/render-video`: build scenes, QC, preview, final render |
| `.claude/skills/video-sound/SKILL.md` | `/video-sound`: music, SFX, mix |

Notes:
- Relative paths inside skills (`../make-2d-video/...`) resolve from each skill's own folder.
- The studio kit is copied to `razgon-2d-studio/` at the repo root on first use (see `make-2d-video/references/install.md`).
- Overview: `.claude/skills/RAZGON-README.md`.
