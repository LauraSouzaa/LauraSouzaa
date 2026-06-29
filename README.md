[![Typing SVG](https://readme-typing-svg.demolab.com?font=Anton&weight=700&size=35&pause=1000&color=FFFFFF&center=true&vCenter=true&width=1000&lines=Welcome+to+my+profile!;I'm+Laura.;Computer+Science+Student.;Backend+Developer.;Coffee+%2B+Code☕;Learning.+Building.+Growing.)](https://git.io/typing-svg)

#
<p align="left">
Atualmente sou estudante de Ciência da Computação na Atitus Educação. Tenho interesse na área de programação e gosto de aprender coisas novas para desenvolver minhas habilidades. Sou uma pessoa dedicada, responsável e comprometida com tudo o que faço. Busco oportunidades para adquirir experiência, crescer profissionalmente e evoluir também como pessoa.
  
#
---

## 👾 Pacman Contribution Graph
on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

  steps:
      - name: generate pacman-contribution-graph.svg
        uses: abozanona/pacman-contribution-graph@main
        with:
          github_user_name: ${{ github.repository_owner }}


  - name: push pacman-contribution-graph.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
---

## 🌐 Connect with Me

<p align="center">
  <a href="https://www.linkedin.com/in/laura-portella?utm_source=share_via&utm_content=profile&utm_medium=member_android" target="_blank">
    <img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="mailto:laurapdsz20@gmail.com">
    <img src="https://skillicons.dev/icons?i=gmail" alt="Gmail"/>
  </a>
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=LauraSouzaa&color=blueviolet&style=for-the-badge" alt="Profile views"/>
</p>

---

<p align="center">
  <i>"Technology moves the world."</i><br>
  <b>— Steve Jobs</b>
</p>
```
