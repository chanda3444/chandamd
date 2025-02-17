<a href="https://github.com/chanda3444/chandamd"><img src="https://readme-typing-svg.demolab.com?font=Black+Ops+One&size=100&pause=1000&color=0013FF&center=true&width=1000&height=200&lines=CHANDA-MD" alt="Typing SVG" /></a>
  </p>
  
<a href="https://whatsapp.com/channel/0029Vb0ux6E5Ui2VPhL49N2e"> <img src="https://raw.githubusercontent.com/shizothetechie/database/main/icon/WhatsApp.png" width="10%"> </a><a href="https://github.com/chanda3444/chandamd"> <img src="https://raw.githubusercontent.com/shizothetechie/database/main/icon/Instagram2.png" width="11%"> </a><a href="https://github.com/chanda3444/chandamd"> <img src="https://raw.githubusercontent.com/shizothetechie/database/main/icon/Facebook.png" width="12%"> </a><a href="https://chat.whatsapp.com/LqwlyO7VyYD8hAXLQ4GAvI"> <img src="https://raw.githubusercontent.com/shizothetechie/database/main/icon/twitter.png" width="10%"> </a>
</p>
</p>

<p align="center"><img src="https://profile-counter.glitch.me/{chandamd}/count.svg" alt="chanda3444 :: Visitor's Count" old_src="https://profile-counter.glitch.me/{chanda3444}/count.svg" /></p>


<p align="center">
<a href="https://github.com/chanda3444/chandamd"><img title="PUBLIC-BOT" src="https://img.shields.io/static/v1?label=Language&message=English&style=square&color=darkpink"></a> &nbsp;
  <img src="https://komarev.com/ghpvc/?username=chanda3444&label=VIEWS&style=square&color=blue" />
</p>
</p> 

<p align="center">
  <a href="https://github.com/chanda3444/chandamd"><img title="Release" src="https://img.shields.io/badge/Release-beta%20v1.0-cyan.svg?style=for-the-badge&logo=appveyor" /></a>
</p>

***

### 1. Fork This Repository

Start by forking this repository to your own GitHub account. Click the button below to fork:

<p align="center">
<a href='https://github.com/chanda3444/chandamd/fork' target="_blank"><img alt='Fork Repo' src='https://img.shields.io/badge/-Fork Repo-grey?style=for-the-badge&logo=github&logoColor=white'/< width=150 height=28/p></a>

### 2. Get Session ID 

You will need a session ID to run the chandamd. Click the button below to obtain your session ID.if any error in loading site try vpn:

> **Get Pair Code (Session ID)**

<p align="center">
<a href='https://malaka-ml-fa86803e6655.herokuapp.com/' target="_blank"><img alt='Pair Code' src='https://img.shields.io/badge/-Pair Code-darkgreen?style=for-the-badge&logo=Whatsapp&logoColor=white'/< width=150 height=28/p></a>


---

## Deployment

You can deploy this bot for free on the following platforms:
     
<p align="center">
<a href='https://railway.app/new' target="_blank"><img alt='Heroku' src='https://img.shields.io/badge/-railway deploy-blue?style=for-the-badge&logo=railway&logoColor=white'/< width=150 height=28/p></a>

<p align="center">
<a href='https://dashboard.heroku.com/new?template=https://github.com/MALAKA-CM/MALAKA-MD-V1' target="_blank"><img alt='Heroku' src='https://img.shields.io/badge/-heroku ‎ deploy-blue?style=for-the-badge&logo=heroku&logoColor=white'/< width=150 height=28/p></a>

<p align="center">
<a href='https://dashboard.render.com/web/new' target="_blank"><img alt='Heroku' src='https://img.shields.io/badge/-Render deploy-blue?style=for-the-badge&logo=render&logoColor=white'/< width=150 height=28/p></a>

<p align="center">
<a href="http://koyeb.com" >
<img alt='Koyeb' src='https://img.shields.io/badge/-koyeb deploy-blue?style=for-the-badge&logo=koyeb&logoColor=white'/< width=150 height=28/p></a>

### GitHub Actions Workflows

#### Node.js CI

You can set up a continuous integration workflow by creating a ```.github/workflows/nodejs.yml``` file with the following content:

```yaml
.github/workflows/nodejs.yml
```

```yaml
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Start application
      run: npm start
```

## 🔗 chanda3444
