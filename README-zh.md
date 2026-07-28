<!-- 中文版 GitHub 个人主页 README
     用法:如果想让国内招聘方看到中文版,可以把这个文件命名为 README.md 放到
     cirE0205/cirE0205 仓库里。或者保留英文版为主 README,把这个作为 README-zh.md
     并在英文版顶部加一行 [English](README.md) | [中文](README-zh.md) 语言切换。 -->

# Hi ,我是 邓👋

### 资深技术动画师 · 人形机器人 ↔ 数字人

连接 DCC 动画与人形机器人动作。打通动捕 → 仿真 → 硬件 / MetaHuman / Unity 3D 移动端 / UE 运行时,端到端交付。

**约 15 年**在企业级数字人和人形机器人平台上打磨动画与角色技术。目前重点:把打造虚拟人的那套管线,迁移到实体人形机器人上。

---

### 🛠 我正在做的

- **让实体人形机器人跳出动捕动作** — 双通道重定向管线(GMR + 自研 MuJoCo DLS-IK)把 LAFAN1 BVH → 机器人 qpos → **真机执行**,不止仿真播放。跨机器(Win ↔ Linux)Git 工作流。

- **实时 AI 驱动 MetaHuman(UE Pixel Streaming)** — 一个**在线产品**:语音输入 → LLM → Azure Custom Voice TTS → 自研口型脚本 → MetaHuman 面部 → UE Pixel Streaming 视频流输出。**< 1s 往返延迟**。这是直播式交互产品,不是离线资产生成器。

- **NVIDIA Kimodo 文本到动作 → 机器人桥接** — 本地部署 Kimodo;文本指令 → SMPL-X → GMR → 23-DOF 人形机器人 qpos → MuJoCo。为自研人形平台提供文本驱动的动作生成路径。

- **离线语音到动画资产生成器(Python)** — 一个**产出动画文件的工具**:音频输入 → 身体动作 + 面部 + 口型生成 → BVH + UE-JSON + ARKit MTA52 / MetaHuman 曲线,供下游导入 UE MetaHuman 或机器人重定向使用。本地推理(vLLM 长上下文服务, SenseVoice, 2.1 万条动作标注库)。

- **手机遥操作 App** — Unity 3D + Sentis ONNX 端侧推理;驱动实体机器人(RL 训练的运动策略 + 面部表情 + 身体待机动作,机械关节 + 面部混合形变的混合绑定)。

- **医疗 3D 可视化 + 绑定** — 自研 **Three.js 绑定模板驱动所有生成的 3D 心脏模型**(把动画 TA 的绑定能力搬到 Web 环境)。生产级渲染器,可切换 UE Pixel Streaming 后端;Agatston 钙化评分算法在 Stanford COCA 公开数据集上 9/9 完全匹配。

---

### ⚙️ 技术栈

**DCC** — Maya · Blender · 3ds Max · MotionBuilder · HumanIK · Advanced Skeleton

**引擎** — UE 5.2 → 5.8 (Control Rig · MetaHuman · IK Retargeter · Sequencer · LiveLink · Motion Matching · Anim BP) · Unity 3D 2022+ · Three.js

**机器人**(按 RL / sim-to-real 相关度排序) — Isaac Sim · Isaac Lab · IsaacGym (RL + 仿真到实机训练栈) · MuJoCo (物理接触精确的验证仿真) · URDF/MJCF (格式) · DLS-IK 自研实现 · GMR · Kimodo · NVIDIA GEAR (BeyondMimic / mjlab / ProtoMotions) (动作模仿框架) · ROS (中间件)

**编程** — Python (numpy · PyTorch · `bpy` · mujoco · vLLM) · TypeScript / React / Electron · C# · MEL / Maya Python · C++ · Git + Git LFS

**AI 辅助开发(日常使用)** — Claude Code · OpenAI Codex · Google Antigravity · Cursor · UE / Unity 3D / Blender MCP

---

### 📌 精选作品

<!-- 等公开的作品仓库上线后再更新这里 -->

- [`motion-td-portfolio`](https://github.com/cirE0205/motion-td-portfolio) *(即将上线)* — 脱敏公开的展示仓:DLS-IK 人形 IK 脚本, SLERP 时间轴混合工具, Maya → MuJoCo 导出模板, ARKit 52 烘焙工具
- [作品集网站](https://cirE0205.pages.dev) *(即将上线)* — 每个项目带 GIF + 内嵌演示片

---

### 🎬 作品集演示片(Reel)

*即将上线* — 60 秒 Reel。招牌镜头:**三画面同步** — LAFAN1 舞蹈片段在人骨架 BVH 上、在 23-DOF 人形机器人 MuJoCo 仿真里、在实体人形机器人训练台上同时播放。一段动捕,三个阶段:**动捕源 → 仿真 → 硬件**。

---

### 📫 联系方式

- **邮箱:** xg.deng0205@gmail.com
- **LinkedIn:** *(补充链接)*
- **作品集:** *(部署后补充链接)*

---

<details>
<summary>针对不同岗位方向,我会切换头衔</summary>

- **游戏行业 / 国际通用** — Senior Technical Animator, Motion TD, Character TD
- **国内(中文简历)** — 高级动画 TA / 资深动画 TA / 资深技术美术
- **机器人行业** — Senior Humanoid Motion Engineer, Robot Animation Engineer, Design Technologist (Robot Animation)

同一个人,同一套技能,只是根据招聘方阅读语言调整头衔。

</details>
