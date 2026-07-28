# Hi, I'm Eric.Deng 👋

### Senior Technical Animator · Humanoid Robots ↔ Digital Humans

Bridge between DCC animation and humanoid robot motion. Ship mocap → simulation → hardware / MetaHuman / Unity + UE runtime (desktop + mobile) pipelines end-to-end.

**~15 years** shipping animation and character-tech across enterprise, digital-human, and humanoid-robot platforms. Recent focus: porting the same pipelines that ship virtual humans onto physical humanoids.

---

### 🛠 What I'm working on

- **Physical humanoid motion from mocap** — dual retargeting pipeline (GMR + custom MuJoCo DLS-IK) drives LAFAN1 BVH → robot qpos → **real hardware execution**, not just sim playback. Cross-machine (Win ↔ Linux) git workflow.

- **Realtime AI-driven MetaHuman (UE Pixel Streaming)** — a **live product**: audio in → LLM → Azure Custom Voice TTS → own lipsync script → MetaHuman face → UE Pixel Streaming video out. **< 1s roundtrip.**

- **NVIDIA Kimodo text-to-motion → robot bridge** — local Kimodo deployment; text prompt → SMPL-X → GMR → 23-DOF humanoid qpos → MuJoCo. Text-driven authoring for a custom humanoid platform.

- **Offline speech-to-animation asset generator (Python)** — a **tool that produces animation files**: audio in → body motion + face + lipsync generation → BVH + UE-JSON + ARKit MTA52 / MetaHuman curves on disk for downstream import into UE MetaHuman or robot retargeting. Local inference (vLLM long-context server, SenseVoice, 21K-clip motion catalog).

- **Mobile teleoperation app** — Unity 3D + Sentis ONNX on-device inference; drives real robot (RL-trained locomotion policy + face expression + idle body motion, hybrid mechanical joints + face blendshape rig).

- **Medical 3D visualization + rigging** — authored a **Three.js rig template that drives all generated 3D heart meshes** (Motion-TD rigging skillset ported to a web context). Production renderer with swappable UE Pixel Streaming abstraction; Agatston calcium-score algo validated 9/9 vs Stanford COCA.

---

### ⚙️ Stack

- **DCC** — Maya · Blender · 3ds Max · MotionBuilder · HumanIK · Advanced Skeleton
- **3D Engines** — UE 5.2 → 5.8 (Control Rig · MetaHuman · IK Retargeter · Sequencer · LiveLink · Motion Matching · Anim BP) · Unity 2022+ · Three.js
- **Robotics** — MuJoCo · URDF/MJCF · IK (own DLS impl) · GMR · Kimodo · NVIDIA GEAR (BeyondMimic / mjlab / ProtoMotions) · IsaacGym / Isaac Lab · ROS Noetic
- **Programming** — Python (numpy · PyTorch · `bpy` · mujoco · vLLM) · TypeScript / React / Electron · C# · MEL / Maya Python · C++ · Git + Git LFS
- **AI-augmented dev (daily driver)** — Claude Code · OpenAI Codex · Google Antigravity · Cursor · UE / Unity / Blender MCP


---

### 📌 Featured work

<!-- Update these once the public sanitized portfolio repos exist -->

- [`motion-td-portfolio`](https://github.com/cirE0205/motion-td-portfolio) *(coming soon)* — sanitized showcase: DLS-IK, SLERP crossfade stitcher, Maya → MuJoCo export template, ARKit 52 bake tool
- [Portfolio site](https://cirE0205.pages.dev) *(coming soon)* — GIF-embedded project pages + reel

---

### 🎬 Reel

*Coming soon* — 60-second reel. Signature shot: **tri-view** of a LAFAN1 dance clip playing on a human BVH skeleton, on a 23-DOF humanoid in MuJoCo simulation, and on the physical humanoid — synchronized. One clip, three stages: source → simulation → hardware.

---

### 📫 Contact

- **Email:** xg.deng0205@gmail.com
- **LinkedIn:** *(add your URL)*
- **Portfolio:** *(add once deployed)*

---

<details>
<summary>Applying to a specific track? I use two titles.</summary>

- **Game industry / general** — Senior Technical Animator, Motion TD, Character TD
- **China domestic** — 高级技术美术 / 资深技术美术 (Senior TA)
- **Robotics** — Senior Humanoid Motion Engineer, Robot Animation Engineer, Design Technologist (Robot Animation)

Same person, same skills, framed for the reader.

</details>
