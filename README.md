<!-- Header: animated waving banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:00d4aa&height=220&section=header&text=Ravindra%20M%20O&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Aspiring%20Cloud%20%26%20DevOps%20Engineer&descAlignY=60&descSize=20" alt="Ravindra M O banner" />
</p>

<!-- Typing animation -->
<p align="center">
  <a href="https://github.com/ravindram0">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=00D4AA&center=true&vCenter=true&width=700&lines=Open+to+work+in+Cloud+%26+DevOps;Building+CI%2FCD+pipelines+%F0%9F%9A%80;Containers+%C2%B7+Kubernetes+%C2%B7+Monitoring;Learning+in+public%2C+shipping+every+day" alt="Typing animation" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to%20Work-Cloud%20%26%20DevOps-00d4aa?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Location-Remote-1f6feb?style=for-the-badge&logo=googlemaps&logoColor=white" />
  <img src="https://komarev.com/ghpvc/?username=ravindram0&label=Profile%20Views&color=0d1117&style=for-the-badge" />
</p>

---

## ⚙️ Operating principles

```yaml
engineer:
  name: Ravindra M O
  role: Aspiring Cloud & DevOps Engineer
  status: open_to_work
  work_mode: remote
  focus:
    - CI/CD automation
    - Containers & Kubernetes
    - Monitoring & observability
    - Infrastructure as Code
  motto: "Build useful things. Learn in public."
```

---

## 🧊 3D contribution graph

<p align="center">
  <img src="./profile-3d-contrib/profile-night-view.svg" alt="3D contribution graph" width="100%" />
</p>

> Generated automatically by the workflow at the bottom of this file.

---

## 🔄 Delivery pipeline

```mermaid
flowchart LR
    A[💻 Code] --> B[🔀 Git Push]
    B --> C[🧪 Build & Test]
    C --> D[🐳 Docker Image]
    D --> E[☸️ Kubernetes]
    E --> F[📊 Prometheus + Grafana]
    F -.feedback.-> A
```

---

## 🚀 Infrastructure shipped

| Project | Description |
|---|---|
| [End-to-End CI/CD Pipeline with Kubernetes Monitoring](https://github.com/RavindraM0/End-to-End-CI-CD-Pipeline-with-Kubernetes-Monitoring) | CI/CD pipeline deploying to Kubernetes with monitoring |
| [DevOps](https://github.com/RavindraM0/DevOps) | DevOps practice and experiments |
| [ecommerce](https://github.com/RavindraM0/ecommerce) | E-commerce project |
| [-my-portfolio-](https://github.com/RavindraM0/-my-portfolio-) | Personal portfolio site |
| [Python](https://github.com/RavindraM0/Python) | Python practice and scripts |
| [LeetCode](https://github.com/RavindraM0/LeetCode) | Problem-solving solutions |

---

## 🛠️ Platform toolkit

```bash
ravindram0@github:~$ toolbox --list
```

<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,bash,git,github,githubactions,jenkins,docker,kubernetes,terraform,ansible,aws,azure,prometheus,grafana,python,nginx&perline=8" alt="Tech stack" />
</p>

---

## 📈 Service signals

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=ravindram0&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00d4aa&icon_color=1f6feb" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ravindram0&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00d4aa" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ravindram0&theme=github-dark-blue&hide_border=true&background=0d1117" alt="Streak stats" />
</p>

---

## 🐍 Uptime in motion

<p align="center">
  <img src="https://raw.githubusercontent.com/ravindram0/ravindram0/output/github-snake-dark.svg" alt="Contribution snake" />
</p>

---

## 🤝 Keep it moving

<p align="center">
  <a href="https://github.com/ravindram0"><img src="https://img.shields.io/badge/GitHub-ravindram0-181717?style=for-the-badge&logo=github" /></a>
  <!-- Add your links:
  <a href="https://www.linkedin.com/in/YOUR-ID"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" /></a>
  <a href="mailto:you@example.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  -->
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d4aa,50:1f6feb,100:0d1117&height=120&section=footer" alt="footer" />
</p>

<!--
=====================================================================
SETUP (delete this block after setup)

Your profile repo must be named exactly: ravindram0/ravindram0
Add this file at .github/workflows/profile-animations.yml

name: Profile animations
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
permissions:
  contents: write
jobs:
  contrib-3d:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: yoshi389111/github-profile-3d-contrib@0.7.1
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          USERNAME: ravindram0
      - name: Commit
        run: |
          git config user.name "github-actions"
          git config user.email "actions@github.com"
          git add -A profile-3d-contrib
          git commit -m "Update 3D contrib graph" || echo "no changes"
          git push
  snake:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ravindram0
          outputs: |
            dist/github-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
=====================================================================
-->
