# my-project

Proyek dengan skill desain [Taste Skill](https://github.com/Leonxlnx/taste-skill) (MIT) terpasang di `.claude/skills/taste-skill`.
Setiap sesi Claude Code (lokal maupun cloud) untuk repo ini otomatis memuat skill `design-taste-frontend`.

Perbarui skill:
```bash
git clone --depth 1 https://github.com/Leonxlnx/taste-skill /tmp/taste-skill
rm -rf .claude/skills/taste-skill && cp -r /tmp/taste-skill/skills/taste-skill .claude/skills/
```
