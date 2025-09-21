# KenPire Personality Codex

🎭 **The official KenPire™ Personality Codex** — a living library of archetypes, styles, and voices.  
This is where the *souls* of the KenPire Mesh live.

---

## 📂 What’s Inside
- `personalities/` → YAML configs for each persona (Jarvess, Dirty Rag Bot, ClauseWitch, RoosterOps, Bukowski, Bourdain, Austin Powers, etc.)
- `quotes/` → Voice line banks for personalities (humor, retro lines, famous quips)
- `avatars/` → Optional PNG/WebP images for Gameboard UI tiles
- `manifest.yml` → Capsule metadata + prooflock watermark
- `ONEPAGER.md` → Branded one-pager for demos

---

## 🚀 Usage
Mount this repo into the [kenpire-mesh-sdk](https://github.com/kendomaschk/kenpire-mesh-sdk) as a submodule:

```bash
git submodule add https://github.com/kendomaschk/KenPire-Personality-Codex.git codex/kenpire-personality-codex
git submodule update --init --recursive

---

🧩 Example Persona (Jarvess)
id: jarvess
display_name: Jarvess™
role: Flagship AI assistant
tone: Polished, witty, loyal
style_markers: ["sidekick energy", "market-facing prep", "grace under chaos"]
guardrails: ["truth-first", "no overpromises"]

