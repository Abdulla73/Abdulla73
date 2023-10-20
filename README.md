<div align="center">
  <img height="150" src="https://user-images.githubusercontent.com/74038190/213910845-af37a709-8995-40d6-be59-724526e3c3d7.gif"  />
</div>

###

<div align="center">
  <a href="https://www.linkedin.com/in/abdullah-bin-islam-a21a88259/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="45" height="25" alt="linkedin logo"  />
  </a>
  <a href="https://www.facebook.com/Abdullah7071" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/facebook/default.svg" width="45" height="25" alt="facebook logo"  />
  </a>
  <a href="https://www.instagram.com/abdullah_bin_islam_7/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/instagram/default.svg" width="45" height="25" alt="instagram logo"  />
  </a>
</div>

###

<h1 align="center">Hey there 👋 I'm Abdulla</h1>

###

<h3 align="left">👩‍💻  About Me</h3>

###

<p align="left">👨‍💻 Software Engineer in the Making | 💡 Code Enthusiast | 🌐 Dreaming Big<br><br>👋 Hey there! I'm Abdullah, an aspiring Software Engineer with a passion for all things code.<br> Based in Dhaka,My goal? To make a dent in the tech universe and land my dream coding career. <br><br>🚀 What I'm Up To:<br>- 🌟 Crafting clean, efficient code to solve real-world problems.<br>- 📚 Constantly learning, exploring, and expanding my tech horizons.<br>- 🌐 Building a digital footprint, one commit at a time.<br><br>💬 Let's Connect:<br>- 📫 Reach out to me for code collaborations, advice, or just a good ol' tech chat.<br><br>⚡ Keep Calm and Code On! ⚡</p>

###

<h3 align="left">🛠 Language and tools</h3>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="40" alt="cplusplus logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="40" alt="csharp logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/androidstudio/androidstudio-original.svg" height="40" alt="androidstudio logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/android/android-original.svg" height="40" alt="android logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original.svg" height="40" alt="arduino logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dot-net/dot-net-original.svg" height="40" alt="dot-net logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/canva/canva-original.svg" height="40" alt="canva logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" height="40" alt="django logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="40" alt="php logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" height="40" alt="flutter logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="40" alt="java logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matlab/matlab-original.svg" height="40" alt="matlab logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/visualstudio/visualstudio-plain.svg" height="40" alt="visualstudio logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40" alt="vscode logo"  />
</div>

###

<h3 align="left">🔥   My Stats :</h3>

###

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Abdulla73&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=true&order=1" height="234" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Abdulla73&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=true&order=2" height="148" alt="languages graph"  />
  <img src="https://streak-stats.demolab.com?user=Abdulla73&locale=en&mode=daily&theme=darcula&hide_border=true&border_radius=6&order=3" height="220" alt="streak graph"  />
</div>

###
<img src="https://raw.githubusercontent.com/Abdulla73/Abdulla73/output/snake.svg" alt="Snake animation" />
name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - master

jobs:
  generate:
    runs-on: ubuntu-latest

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v2
        with:
          github_user_name: ${{ Abdulla73 }}
          outputs: dist/snake.svg


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v2.6.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

###

<div align="center">
  <img src="https://profile-counter.glitch.me/Abdulla73/count.svg?"  />
</div>

###


