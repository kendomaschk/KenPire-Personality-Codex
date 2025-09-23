# KenPire Personality Codex 🎭  

The official **KenPire™ Personality Codex** — a living library of bot archetypes, styles, and voices.  
This repo defines the unique *souls* of the KenPire Mesh.  

---

## 🔑 What’s Inside
- `personalities/` → YAML configs for each persona (role, tone, guardrails)  
- `quotes/` → banks of quotes, jokes, retro lines  
- `avatars/` → optional images for Gameboard UI tiles  
- `manifest.yml` → capsule metadata + prooflock watermark  
- `README.md` / `ONEPAGER.md` → docs + marketing one-pager  

---

## ⚡ Usage
Mount this repo as a submodule in `kenpire-mesh-sdk`:  

```bash
git submodule add https://github.com/kendomaschk/KenPire-Personality-Codex.git codex/kenpire-personality-codex
git submodule update --init --recursive
