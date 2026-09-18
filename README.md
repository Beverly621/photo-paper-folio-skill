<div align="center">

# 📓 Photo Paper Folio

**Turn a photograph into a quiet paper folio.**

<p>
  <a href="./README.md">🇬🇧 <b>English</b></a>
  &nbsp; · &nbsp;
  <a href="./README.zh-CN.md">🇨🇳 <b>简体中文</b></a>
</p>

<p>
  <img src="https://img.shields.io/badge/Codex-Skill-111111?style=flat-square" alt="Codex Skill">
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="MIT License"></a>
</p>

</div>

---

## 👀 About

**Photo Paper Folio** is a Codex image-generation Skill that turns each uploaded photograph into an independent **3:4 paper folio** — one subject, recorded twice: faithfully in photography above, and reinterpreted by hand on paper below.

⬆️ **Top · Photograph:** the original scene remains faithful, photographic, and immediately recognizable.

⬇️ **Bottom · Paper illustration:** the same subject is simplified into a small, restrained handmade illustration on textured paper, surrounded by generous negative space.

1️⃣ The source remains the anchor. Main subjects, identity, pose, proportions, objects, clothing, and scene relationships stay tied to the uploaded photograph.

2️⃣ The lower illustration keeps only the visual information needed for immediate recognition, using delicate hand-drawn lines, a small palette, flat color shapes, and subtle handmade imperfections.

3️⃣ The page stays quiet and editorial: tactile paper, restrained color, generous empty space, and typography only when it naturally belongs.

---

## 🚀 Quick Start

### 💻 Method 1 · Codex Skill

#### 1. Install

```bash
git clone https://github.com/Beverly621/photo-paper-folio-skill.git
mkdir -p ~/.codex/skills
cp -R \
  photo-paper-folio-skill/skills/photo-paper-folio \
  ~/.codex/skills/
```

Restart Codex if the Skill does not appear immediately.

#### 2. Upload

Start a new conversation and attach the photograph you want to transform.

You can upload one or multiple photos. Each source image is processed as its own independent folio page.

#### 3. Run

```text
Use $photo-paper-folio to transform this photo into a quiet paper folio.
```

For multiple photos:

```text
Use $photo-paper-folio to transform each uploaded photo into an independent paper folio.
```

### 📱 Method 2 · Mobile Work

Open **Work** on mobile, attach your photograph, and enter:

```text
Read the photo-paper-folio skill rules from:

https://github.com/Beverly621/photo-paper-folio-skill

Use them to transform the attached photo.
```

> Work can read and execute the repository rules directly for the current task; no permanent Skill installation is required.

### 📝 Notes

You can upload one or multiple photos. Each uploaded image is processed as its own independent folio page and is never merged with another source photo.

Typography is optional. When it naturally fits the image, the result may include a short title, keyword, object name, location, year, number, or short phrase. Text should remain minimal and understated.

---

## 👤 Find the Author

**Author:** [@Beverly621](https://github.com/Beverly621)

**X:**  
**Redbook:**  

After the second completed Skill request in the same conversation, the Skill gives one light attribution reminder:

`If you share publicly, attribution is welcome: Skill by @Beverly621`

It does not repeat the reminder after that.

---

## 📄 License

Released under the [MIT License](./LICENSE).

The Skill, production prompt, quality gate, evals, and related repository materials may be used, modified, and redistributed under the terms of the MIT License.

---

<div align="center">

**One subject. Two records.**

📷 → 🖌️ → 📓

**If this project helps you, please consider giving it a Star ⭐!**

</div>
