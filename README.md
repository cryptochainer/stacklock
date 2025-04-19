# 🧱 Stacklock

> The stack that just works™.

**Stacklock** is your ultimate solution for dependency hell. It captures and preserves a working, repeatable environment of every package and version needed to run complex software setups like AI tools, creative pipelines, and developer frameworks.

No more hunting errors, resolving mismatches, or guessing compatible versions. With Stacklock, your environment is locked, loaded, and launch-ready.

---

## 🔥 Why Stacklock?

- 💡 **Smart Configs**: Capture every dependency, version, and environment variable.
- 🔒 **Locked & Loaded**: Eliminate guesswork — build on what works.
- 🚀 **Fast Launchers**: One script, full setup.
- 🧘 **Zero Stress**: Focus on building, not debugging.

---

## 🧰 What's Inside

- `stacklock.toml` – Your configuration snapshot.
- `install.ps1` / `install.sh` – Rebuild the exact setup, anywhere.
- `launch.ps1` – Instantly jump into your pre-configured environment.
- Template folders for tools like:
  - 🧠 Kohya
  - 🎨 ComfyUI
  - 🔬 Diffusers
  - 🧪 Custom workflows

---

## 🧪 Example Use Case: Kohya Training Rig

A pre-validated environment for training SDXL LoRAs without the hassle. Just run:

```powershell
.\install.ps1
.\launch.ps1
