<p align="center"><img width="300" src="./docs/readme.jpg"/></p>

<h1 align="center">Solzhenitsyn</h1>

<p align="center">Botnet codebases for various tasks. In memory of <a href="https://en.wikipedia.org/wiki/Aleksandr_Solzhenitsyn">Aleksandr Isayevich Solzhenitsyn</a></p>

# Docker - Usage and Importance
      - Pull the docker image (In Information), do not use this repository on your
      own computer or clone the repository and build the dockerfile on your down computer

      - To run the image use ie:
      ---docker run --name <name_of_given_container> -it ghcr.io/ronaldsonbellande/malware-exhibit:main bash---

      or if it build your own image from the Dockerfile replace ie:
      --- docker run --name <name_of_given_container> -it <docker_image> bash ---

      - To bash into the docker container after exiting it use ie:
      --- docker start -ia <name_of_given_container> ---
      - Small introduction for usage as there will be more complex introduction in https://github.com/Algorithm-Model-Research for useabilities


Introduction
------------
- For more instroctions into docker usage, check out the organization to get a betterunderstanding on how to use the image
=======
      - For more instroctions into docker usage, check out the organization to get a betterunderstanding on how to use the image
      - docker pull ghcr.io/ronaldsonbellande/malware-exhibit:main
      - docker pull ghcr.io/algorithm-model-research/malware-exhibit:main

Few things to NOTE
1. Dont deploy on your personal machine. These stuff can go on to infect other devices in your network.
2. If there is a password on the ZIP(coz VX-UNDERGROUND)....the password is 'infected'.....without the quotes....offcourse
3. Some are .ex_ intead of .exe to avoid accidental deployment by double clicking

```
The malware in this repo is either:
1. FEW: Built by me
2. SOME: Analysed by me ⚡
3. A FEW: Acquired and retrieved during threat hunting and threat intelligence ☄
4. MOST: Shared/Sourced from other malware researchers VX-UNDERGROUND, KASPERSKY, LIFKA, JOHN HAMMOND, CTFs...and a few others
```

- There are over a thousand malware samples in this repository from simple fireworks to weapons-of-mass-destruction.
- To reverse Engineer these samples, you can use Ghidra, Responder, IDApro.
- Ensure you have the necessary support environment installed i.e JDK, Python3, Ruby etc
- All source code which is packaged may or may not be set with the password 'infected' (without the '). Individual files are likely not packaged.
- To get even more malware check out VX-UNDERGROUND, MALWARETECH, ANY.RUN, VT, LIFKA...etc

## Liability Disclaimer:

To the maximum extent permitted by applicable law, I and/or affiliates whom this repo is sourced and or submitted content to this repo, shall not be liable for any indirect, incidental, special, consequential or punitive damages, or any loss of profits or revenue, whether incurred directly or indirectly, or any loss of data, use, goodwill, or other intangible losses, resulting from:

- (i) your access to this resource and/or inability to access this resource;
- (ii) any conduct or content of any third party referenced by this resource, including, any offensive or illegal conduct or other users or third parties;
- (iii) any content obtained from this resource or any of its resources
