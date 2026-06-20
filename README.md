<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=6C63FF&height=200&section=header&text=Inbanesan&fontSize=50&fontColor=ffffff&fontAlignY=35&desc=.NET%20Developer%20%7C%20Problem%20Solver%20%7C%20Tech%20Enthusiast&descAlignY=55&descColor=ffffff" width="100%"/>
</div>
<br/>

<img align="right" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="380" />

### 👋 About Me
- 🏢 Working at **Bosco Soft Technologies Pvt Ltd**
- 🌱 Currently leveling up in **React**
- 💡 Expertise in **C#**, **.NET**, and **SQL**
- 🤝 Open to collaborations and interesting projects
- 📫 Reach me at **inbanesanjoshua@gmail.com**
- 📄 [View my Resume](https://drive.google.com/file/d/1FDiyukShlgtZQUxz3QAiCMQ1LdKbcJFA/view?usp=drive_link)

<br clear="right"/>

---

### 🛠️ Tech Stack

<table>
  <tr>
    <td valign="top" width="33%">
      <b>⚙️ Backend</b>
      <br/>
      <img src="https://skillicons.dev/icons?i=cs,dotnet,visualstudio" />
    </td>
    <td valign="top" width="33%">
      <b>🎨 Frontend</b>
      <br/>
      <img src="https://skillicons.dev/icons?i=react,ts,js,html" />
    </td>
    <td valign="top" width="33%">
      <b>🔧 Tools</b>
      <br/>
      <img src="https://skillicons.dev/icons?i=git,github,vscode,postman" />
    </td>
  </tr>
</table>

---

### 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&border_radius=10&count_private=true" height="160"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true&border_radius=10" height="160"/>
</div>
<br/>
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=tokyonight&hide_border=true&border_radius=10" height="160"/>
</div>
<br/>
<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&theme=tokyonight&no-frame=true&row=1&column=6" />
</div>

---

### 🐍 Contribution Graph

<div align="center">
  <img src="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake-dark.svg" />
</div>

---

### 🤝 Connect With Me

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-inbanesanjoshua%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:inbanesanjoshua@gmail.com)
&nbsp;
[![Resume](https://img.shields.io/badge/Resume-View%20Now-6C63FF?style=for-the-badge&logo=google-drive&logoColor=white)](https://drive.google.com/file/d/1FDiyukShlgtZQUxz3QAiCMQ1LdKbcJFA/view?usp=drive_link)

</div>
<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=6C63FF&height=100&section=footer" width="100%"/>

---

### ⚙️ Snake Animation Setup

Create `.github/workflows/snake.yml` in your repo:

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: YOUR_USERNAME
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Replace `YOUR_USERNAME` with your GitHub username.
