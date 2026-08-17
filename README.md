# 👋 Olá, eu sou Luis Felipe

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00E5FF&center=true&vCenter=true&width=700&lines=Luis+Felipe+Morais+Almeida;Full+Stack+Developer;JavaScript+%7C+Node.js+%7C+TypeScript;Criando+projetos+e+solu%C3%A7%C3%B5es+digitais" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://github.com/luisfpdev">
    <img src="https://img.shields.io/github/followers/luisfpdev?label=Seguidores&style=for-the-badge&logo=github&color=00E5FF" />
  </a>
  <a href="https://github.com/luisfpdev?tab=repositories">
    <img src="https://img.shields.io/github/stars/luisfpdev?label=Stars&style=for-the-badge&logo=github&color=00E5FF" />
  </a>
</p>

---

## `> ABOUT_ME`

```js
const LuisFelipe = {
    name: "Luis Felipe Morais Almeida",
    username: "luisfpdev",
    role: "Developer",
    company: "CNX Code",
    focus: [
        "Web Development",
        "Discord Bots",
        "Backend",
        "Automation",
        "Performance Optimization"
    ],
    technologies: [
        "JavaScript",
        "TypeScript",
        "Node.js",
        "HTML",
        "CSS",
        "Git",
        "GitHub"
    ],
    currentlyLearning: [
        "Advanced JavaScript",
        "TypeScript",
        "Backend Development",
        "Software Engineering"
    ],
    goal: "Transformar ideias em projetos reais."
};

> TECHNOLOGIES
<p align="center"> <img src="https://skillicons.dev/icons?i=js,ts,nodejs,html,css,git,github,vscode,mysql&perline=9" /> </p>
> WHAT_I_DO
Desenvolvimento de aplicações web
Desenvolvimento de bots para Discord
Sistemas e automações
Backend com Node.js
Integrações com APIs
Desenvolvimento de ferramentas
Otimização e melhoria de desempenho
Criação de projetos para comunidades e empresas
> GITHUB_STATS
<p align="center"> <img height="180em" src="https://github-readme-stats.vercel.app/api?username=luisfpdev&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" /> <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=luisfpdev&layout=compact&theme=github_dark&hide_border=true&langs_count=8" /> </p>
> CONTRIBUTION_ACTIVITY
<p align="center"> <img src="https://github-readme-activity-graph.vercel.app/graph?username=luisfpdev&bg_color=0D1117&color=00E5FF&line=00E5FF&point=FFFFFF&area=true&hide_border=true" width="100%" /> </p>
> TROPHIES
<p align="center"> <img src="https://github-profile-trophy.vercel.app/?username=luisfpdev&theme=algolia&no-frame=true&no-bg=true&margin-w=10&row=1&column=6" width="100%" /> </p>
> CONTRIBUTION_MATRIX
<p align="center"> <img src="https://raw.githubusercontent.com/luisfpdev/luisfpdev/output/github-contribution-grid-snake-dark.svg" alt="GitHub Contribution Snake" width="100%" /> </p>
> PROJECTS
CNX Code

Projeto focado em desenvolvimento de soluções digitais, automações, otimização e ferramentas para comunidades e servidores.

Discord Systems

Desenvolvimento de sistemas personalizados para Discord, incluindo:

Sistema de tickets
Logs
Atendimento
Automação
Integrações
Painéis
Sistemas administrativos
> CURRENTLY_WORKING_ON
[+] Desenvolvimento de novos projetos
[+] Aprimorando JavaScript
[+] Estudando TypeScript
[+] Desenvolvendo sistemas com Node.js
[+] Criando soluções para CNX Code
[+] Aprimorando conhecimentos em desenvolvimento
> CONTACT
<p align="center"> <a href="https://github.com/luisfpdev"> <img src="https://img.shields.io/badge/GitHub-luisfpdev-0D1117?style=for-the-badge&logo=github&logoColor=00E5FF" /> </a> </p>
> CONTRIBUTION_SNAKE
<p align="center"> <img src="https://raw.githubusercontent.com/luisfpdev/luisfpdev/output/github-contribution-grid-snake.svg" alt="Contribution Snake" /> </p>
<p align="center"> <b>“Transformando ideias em código.”</b> </p> <p align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=00E5FF&height=100&section=footer" /> </p> ```
Importante para a CONTRIBUTION_MATRIX

Essa parte:

https://raw.githubusercontent.com/luisfpdev/luisfpdev/output/github-contribution-grid-snake-dark.svg

precisa de uma GitHub Action para gerar automaticamente a animação da cobra. Crie exatamente este arquivo:

.github/workflows/snake.yml

name: Generate Snake


on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:


jobs:
  generate:
    runs-on: ubuntu-latest


    steps:
      - name: Generate Snake
        uses: Platane/snk@v3
        with:
          github_user_name: luisfpdev
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark


      - name: Deploy Snake
        uses: crazy-max/ghaction-github-pages@v4
        with:
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
