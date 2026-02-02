<!-- TYPING EFFECT -->
<p align="center">
  <a href="https://github.com/Amanrizvi786110">
    <img src="https://readme-typing-svg.herokuapp.com?size=28&duration=3000&color=36BCF7&center=true&vCenter=true&width=650&lines=Hi+👋+I'm+Aman;Python+Developer+🐍;Django+Backend+Engineer;Learning.+Building.+Scaling.;Code+with+Purpose+⚡" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&height=2"/>
</p>

---

## 🧑‍💻 About Me

- 🐍 Python-focused developer  
- ⚙️ Django & backend engineering  
- 🌐 Exploring full-stack & APIs  
- 🧠 Clean code > clever code  

---

## 🛠 Languages & Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,django,js,html,css,git,github,vscode,linux&perline=6" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=amanrizvi&show_icons=true&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=amanrizvi&theme=tokyonight&hide_border=true" />
</p>


---

## 🐍 Contribution Snake (LIVE)

name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3

      - uses: Platane/snk@v3
        with:
          github_user_name: Amanrizvi786110
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


---

## ✨ Quote I Believe In

> *“Sometimes the elegant implementation is a function.  
> Not a method. Not a class. Just a function.”*  
> — **John Carmack**

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer"/>
</p>
