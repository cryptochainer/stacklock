# Stacklock — The Stack That Just Works™

> A new way to install *exactly* what you need, without the bloat, breakage, or bullshit.

Stacklock is your bulletproof blueprint for building and running complex tools like Kohya or ComfyUI with zero version mismatch chaos. Whether you’re an advanced AI tinkerer or just trying to get your rig to stop erroring out, Stacklock helps you:

- ✅ Reproduce exact environments across machines
- ⚡️ Launch into training or generation with confidence
- 🚫 Avoid pip hell and dependency drift

## Why Stacklock?

Because installing 47 packages and praying isn't a strategy.

Stacklock is a **complete ecosystem state**: a manifest of versions, scripts, and sanity checks that guarantee everything works together. It's not just a requirements.txt, it's a mindset.

## Example Use Case: Kohya

Coming soon:
- A working Kohya install script
- A validated torch+xformers+transformers+diffusers combo
- Launcher + CLI tools to deploy, validate, and relock

## Project Structure (Planned)

```
stacklock/
├── stacklock.toml          # Core lockfile of all known-good versions
├── setup/                  # Scripts to install and validate environment
│   ├── install_kohya.ps1
│   └── check_cuda.py
├── launchers/              # Scripts to launch tools from the locked state
├── examples/               # Real world installs (Kohya, ComfyUI, etc)
└── README.md
```

## Coming Soon
- `stacklock install kohya`
- Stack snapshots + diffing
- Friendly error handler: tells you *what* broke and *how* to fix it

---

Built by [CryptoChainer](https://github.com/CryptoChainer) — original wallet sync wizard.

_Tagline history: "keeps wallets in sync" → "keeps tools in sync"_

Welcome to the stack that just works.

