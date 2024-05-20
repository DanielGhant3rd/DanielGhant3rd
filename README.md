<h1>Hi, I'm Daniel! </h1>

<h2>👨‍💻 Cybersecurity Projects:</h2>

- [Azure Detection Lab](https://github.com/DanielGhant3rd/Active-Directory-Lab/tree/main)

<h2> - Certifications and Certificates</h2>

- Qualys CyberSecurity Asset Management Certificate (CSAM) (https://imgur.com/IBw5L5S)

- Qualys Vulnerability Detection Management and Response Certificate (VDMR) (https://imgur.com/a/sAi5KuR)
  
- FEMA National Incident Management Systems (NIMS) (https://google.com)

- Coursera Microsoft Windows Defender and Firewalls (https://imgur.com/a/BpvTgFp)

<h2>📺 AWS and Azure Cloud Projects</h2>

- [Building A Daily Task Scheduler](https://partyrock.aws/u/DanielG26/7rxMYkNtw/Daily-Inspirations%3A-A-Devotional-Journey)


<h2> 🤳 Connect with me:</h2>

version: 2.1

jobs:
  deploy:
    docker:
      - image: cimg/aws:2023.04.1
    steps:
      - checkout
      - run:
          name: Lets deploy thsi application
          command: |
            ls
            aws s3 sync . s3://$AWS_S3_BUCKET/



workflows:
  Production:
    jobs:
      - deploy:
          filters:
            branches:
              only: main
  

[<img align="left" alt="JoshMadakor | YouTube" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />][youtube]
[<img align="left" alt="JoshMadakor | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="JoshMadakor | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="JoshMadakor | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]

[twitter]: https://twitter.com/joshmadakor
[youtube]: https://www.youtube.com/c/joshmadakor
[instagram]: https://www.instagram.com/joshmadakor/
[linkedin]: https://linkedin.com/in/joshmadakor

<!--
**joshmadakor1/joshmadakor1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
