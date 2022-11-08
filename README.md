<div id="header" align="center">   <img src="https://media.giphy.com/media/BjvFYeG1WIuoo/giphy.gif"/> </div>
<div id="badges">
  <a href="www.linkedin.com/in/patrick-tricenio">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://www.youtube.com/channel/UCYn7E2DAtTyVFccPdRiHLSQ/channelsL">
    <img src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/>
  </a>
  <a href="https://twitter.com/PTricenio">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>
<img src="https://komarev.com/ghpvc/?username=your-github-username&style=flat-square&color=blue" alt=""/>

<h1>
 Kia Ora
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>


<div align="center">
  <img src="https://media.giphy.com/media/CTX0ivSQbI78A/giphy.gif" width="600" height="300"/>
</div>

---

### 👨‍💻: About Me :

I am aspiring to be a Full Stack Developer/Programmer <img src="https://media.giphy.com/media/OVay6ruYLVNNF8zhxH/giphy.gif" width="30"> from Auckland, New Zealand  <img src="https://media.giphy.com/media/Qa4cAGMr5NfUuINAXd/giphy.gif" width="30">

- :telescope: Aspiring Technologist and Software Programmer contributing to web applications, IOS and Android.

- :seedling: Expanding my knowledge on Programming and Building small projects

- :zap: In my free time, I listen to music and cleaning the house.

- :mailbox:How to reach me: [![Linkedin Badge](https://img.shields.io/badge/Patrick-Linkedin-blue)](www.linkedin.com/in/patrick-tricenio)

---

### :hammer_and_wrench: Languages and Tools :

<div>
  <img scr="https://www.silhouettepng.com/r-letter-silhouette-png/download/858 R Letter PNG" title="R" alt="R" width="40" height="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL"  alt="MySQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/googlecloud/googlecloud-original-wordmark.svg" title="Google Cloud"  alt="Google Cloud" width="40" height="40"/>&nbsp;
</div>


---

### :fire: My Stats :
https://github-readme-streak-stats.herokuapp.com/?user=your-github-username
[![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=your-github-username&theme=dark&background=000000)](https://git.io/streak-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=your-github-username)](https://github.com/anuraghazra/github-readme-stats)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=your-github-username&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)

---

### :writing_hand: Blog Posts :

name: Latest blog post workflow
on:
  schedule:
    # Runs every hour
    - cron: '0 * * * *'
  workflow_dispatch:

jobs:
  update-readme-with-blog:
    name: Update this repos README with latest blog posts
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: gautamkrishnar/blog-post-workflow@master
        with:
          max_post_count: "4"
          feed_list: "https://github.com/Patsy101"
