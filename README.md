<div align="center">

# 🎬 voice-design

## 音色库没有？一句话描述现造一个
## No matching voice? Describe one in a sentence

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

当官方音色库找不到合适的声音、需要独特音色身份时，用自然语言描述声音特征来设计并试听自定义音色。输入年龄、性别、情感色彩、语速等描述与试听文本，先改写提示词并确认语种，再产出试听样本和可复用的 voice_id 供 TTS 集成使用。适合在检索现有音色后仍不合适时，做声音方向的对比与收敛。该功能属实验性质，品质通常低于内置音色库，建议优先复用已有音色。

### ✨ 能做什么

- 输入声音特征描述与试听文本 → 输出试听样本与可复用 voice_id
- 改写提示词，收敛年龄、质感、语速与情绪等声音方向
- 生成前先确认语种与发音目标
- 产出试听样本、音色选择建议与 TTS 集成标识
- 适合检索现有音色库后仍找不到合适声音的场景
- 实验性质，品质通常低于内置音色库，建议优先复用现有音色

### 📦 包含的技能

- `voice-design` —— 见 [`voice-design/SKILL.md`](voice-design/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/voice-design.git
cp -r voice-design/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

Designs and previews a custom voice from text when the standard voice library has nothing suitable and a distinct voice identity is required. Input is a natural-language description of the desired traits — age, gender, emotional color, pace — plus a preview text. The prompt is refined, language is confirmed, and the output is preview audio plus a reusable voice_id for TTS integration. This is an experimental feature whose quality is usually below the built-in voice library, so searching existing voices first is recommended.

### ✨ What it does

- Turns a natural-language trait description plus preview text into a custom voice
- Rewrites the prompt to converge age, texture, pace, and emotional character
- Confirms language and pronunciation goals before generating
- Returns preview samples, selection guidance, and a reusable voice_id for TTS
- Best used when searching the existing library found nothing suitable
- Experimental: quality is often below built-in voices, so reuse comes first

### 📦 Skills included

- `voice-design` — [`voice-design/SKILL.md`](voice-design/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/voice-design.git
cp -r voice-design/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
