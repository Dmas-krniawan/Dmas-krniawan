<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Hi%2C%20I'm%20NAMA_LO&fontSize=45&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Web%20Developer%20%7C%20Frontend%20%26%20Backend&descAlignY=55&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2500&pause=800&color=00F7FF&center=true&vCenter=true&width=600&lines=Building+cool+things+for+the+web+%F0%9F%9A%80;JavaScript+%7C+React+%7C+Node.js;Always+learning%2C+always+shipping" />

<br/>

<img src="https://komarev.com/ghpvc/?username=USERNAME_GITHUB&label=Profile%20Views&color=0e75b6&style=for-the-badge" />
<img src="https://img.shields.io/github/followers/USERNAME_GITHUB?label=Followers&style=for-the-badge&color=0e75b6" />
<img src="https://img.shields.io/badge/dynamic/json?color=blue&style=for-the-badge&label=GitHub%20Stars&query=%24.length&url=https://api.github.com/search/repositories?q=user:USERNAME_GITHUB" />

</div>

---

## 🧑‍💻 Tentang Saya

```javascript
const nama_lo = {
  role: "Web Developer",
  lokasi: "Indonesia",
  fokus: ["Frontend", "Backend", "UI/UX"],
  sedangBelajar: "sesuatu yang baru tiap minggu",
  motto: "Ship fast, iterate faster"
};
```

<img align="right" width="380" src="https://raw.githubusercontent.com/mikechambers/mikechambers/main/coding.gif">

- 🔭 Lagi ngerjain: **[ai studdy]**
- 🌱 Lagi belajar: **[maching learning]**
- 👯 Terbuka buat kolaborasi di: **[website]**
- 💬 Ajak diskusi soal: **JavaScript, React, Node.js**
- ⚡ Fun fact: **[gatau]**

<br clear="both"/>

---

## 🛠️ Tech Arsenal

<div align="center">
<img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,nodejs,express,mongodb,postgres,tailwind,figma,git,docker,vscode&theme=dark&perline=8" />
</div>

---

## 📊 Statistik Ngoding

<div align="center">
<img width="49%" src="https://github-readme-stats.vercel.app/api?username=USERNAME_GITHUB&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&icon_color=00F7FF&title_color=00F7FF" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME_GITHUB&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00F7FF" />
</div>

<div align="center">
<img width="65%" src="https://github-readme-streak-stats.herokuapp.com/?user=USERNAME_GITHUB&theme=highcontrast&hide_border=true&background=0d1117&ring=00F7FF&fire=00F7FF&currStreakLabel=00F7FF" />
</div>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=USERNAME_GITHUB&theme=react-dark&hide_border=true&bg_color=0d1117&color=00F7FF&line=00F7FF&point=ffffff" width="90%"/>
</div>

---

## 🐍 Contribution Snake (animasi makan kotak kontribusi)

name: Generate Snake Animation

on:
  schedule:
    # Jalan otomatis tiap hari jam 00:00 UTC (jam 7 pagi WIB)
    - cron: "0 0 * * *"
  workflow_dispatch: {}   # biar bisa dijalanin manual dari tab Actions
  push:
    branches:
      - main               # ganti ke "master" kalau branch utama lo namanya itu

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake animation SVG
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push ke branch output
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
</div>

> ⚠️ Butuh setup GitHub Action — instruksi ada di bawah.

---

## 🏆 GitHub Trophy

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=USERNAME_GITHUB&theme=darkhub&no-frame=true&row=1&column=7" />
</div>

---

## 🌐 Let's Connect

<div align="center">
<a href="https://linkedin.com/in/USERNAME_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://instagram.com/USERNAME_IG"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
<a href="https://twitter.com/USERNAME_TWITTER"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" /></a>
<a href="mailto:email@kamu.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer"/>
</div>


