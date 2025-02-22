## Hi there 👋

<!--
**duguxiaobai000/duguxiaobai000** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
name: push

on:
  workflow_dispatch:
  push:
    branches:
      - main
  schedule:
    - cron: "* * * * *"

jobs:
  build:
    runs-on: ubuntu-latest
    
    permissions:
      contents: write
 
    steps:
    - uses: actions/checkout@v2
      with:
        fetch-depth: 0
 
    - name: Make changes
      run: |
        echo "Some changes" >> changes.txt
        date > time
        date
        echo 1 > 1
 
    - name: Commit changes
      uses: stefanzweifel/git-auto-commit-action@v5
- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
