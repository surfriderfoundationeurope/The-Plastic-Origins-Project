# Surfrider Plastic Origins

Plastic Origins is a project from the not-for-profit [Surfrider Foundation Europe](www.surfrider.eu). We aim to map river plastic pollution. It's a **hot topic**, here is why:

1. Plastic pollution is the second biggest threat to our Ocean after climate change.
2. Ocean plastic pollution mainly comes from terrestrial sources. Rivers are pathways for litter entering the ocean. For instance, a bottle lost in Paris city might end-up in the Seine River and reach the sea.
3. Investigating river plastic pollution helps to localize plastic inputs and monitor trends, improvements and measures efficiency.
4. There is currently no obligation for European countries to monitor river plastic pollution. The European water framework directive does not include plastic pollution as an indicator for good environmental status.


## All you need to know to get involved

Developments and improvements of Surfrider Plastic Origins tech tools are led by a bunch of amazing volunteers. Surfrider Europe in its own does not have within the organisation competencies to make all those developments. We rely on YOU for making this project a success. 


### Project architecture

![Project architecture](/assets/project-architecture.JPG)


### How we work

We use the following tools for project management and dev:
1. Microsoft Teams -> for discussions 
2. [Azure DevOps](https://dev.azure.com/surfrider/PlasticOrigins/) -> to list tasks, organise the work to be done, to make builds and deployments
3. [GitHub](https://github.com/surfriderfoundationeurope) -> to store codes, codes' descriptions, documentation and Architectural Decision Record (ADR). When building an API, please mind of writting a swagger file, think about quotas limits and associated costs & get in touch with @lise-deguilhem who currently deal with the APIm.


### Repo organisation

| Repository                                                   | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [The-Plastic-Origins-Project](https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project) | You are currently in this repo. This is a general repo used to describe the projet. |
| [plasticorigins-ops-db](https://github.com/surfriderfoundationeurope/plasticorigins-ops-db) | All scripts related to our PostGreSQL database. |
| [fillbidatabase](https://github.com/surfriderfoundationeurope/fillbidatabase) | Code for the recurring job that fills Bi database |
| [labelcv-web](https://github.com/surfriderfoundationeurope/labelcv-web) | Frontend of our data labeling plateforme. |
| [LabelCV](https://github.com/surfriderfoundationeurope/LabelCV) | Backend of our data labeling plateforme. |
| [MOT](https://github.com/surfriderfoundationeurope/mot) | AI model currently used to detect trash on videos |
| [Faster-RCNN-waste-detector](https://github.com/surfriderfoundationeurope/Faster-RCNN-waste-detector) | First AI model developed but no in use anymore |
| [Plastic-origin](https://github.com/surfriderfoundationeurope/plastic-origin) | Frontend of [Plastic Origins' website](www.plasticorigins.eu) |
| [etl](https://github.com/surfriderfoundationeurope/etl) | ETL script used to send videos to AI, read results and write in DB |
| [plastic-origins-cloud-ops](https://github.com/surfriderfoundationeurope/plastic-origins-cloud-ops) | ... |
| [po-mobile-backend](https://github.com/surfriderfoundationeurope/po-mobile-backend) | API for data upload from app or website |



### Ready? Get involved!

Please, get in touch with @AntoineBruge.



## Contributors

Thanks everyone !

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-27-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
                   	                	              	                  	                      	                 
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/Clemsurfrider"><img src="https://avatars3.githubusercontent.com/u/61323067?v=4" width="100px;" alt=""/><br /><sub><b>Clemsurfrider</b></sub></a><br /><a href="#design-Clemsurfrider" title="Design">🎨</a></td>
    <td align="center"><a href="https://github.com/ChristopheHvd"><img src="https://avatars3.githubusercontent.com/u/1823079?v=4" width="100px;" alt=""/><br /><sub><b>ChristopheHvd</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=ChristopheHvd" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/clembac"><img src="https://avatars0.githubusercontent.com/u/11059568?v=4" width="100px;" alt=""/><br /><sub><b>clément baccar</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=clembac" title="Code">💻</a></td>
    <td align="center"><a href="https://www.linkedin.com/in/rapha%C3%ABlle-bertrand-lalo-185679b9/"><img src="https://avatars3.githubusercontent.com/u/22340670?v=4" width="100px;" alt=""/><br /><sub><b>Raphaëlle Bertrand-Lalo</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=bertrandlalo" title="Code">💻</a></td>
    <td align="center"><a href="http://www.maneu.fr"><img src="https://avatars2.githubusercontent.com/u/790974?v=4" width="100px;" alt=""/><br /><sub><b>Christopher MANEU</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=cmaneu" title="Code">💻</a></td>
    <td align="center"><a href="http://r.courivaud@gmail.com"><img src="https://avatars1.githubusercontent.com/u/20335094?v=4" width="100px;" alt=""/><br /><sub><b>Raphaël Courivaud</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=rcourivaud" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/charlesollion"><img src="https://avatars2.githubusercontent.com/u/10595147?v=4" width="100px;" alt=""/><br /><sub><b>charlesollion</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=charlesollion" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/cl3m3nt"><img src="https://avatars1.githubusercontent.com/u/8882133?v=4" width="100px;" alt=""/><br /><sub><b>cl3m3nt</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=cl3m3nt" title="Code">💻</a></td>
    <td align="center"><a href="http://felix.voituret.fr"><img src="https://avatars3.githubusercontent.com/u/250322?v=4" width="100px;" alt=""/><br /><sub><b>Félix Voituret</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=Faylixe" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/lucasrymenants"><img src="https://avatars2.githubusercontent.com/u/15192989?v=4" width="100px;" alt=""/><br /><sub><b>lucasrymenants</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=lucasrymenants" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/Vincent-Guiberteau"><img src="https://avatars3.githubusercontent.com/u/6638957?v=4" width="100px;" alt=""/><br /><sub><b>Tekateyy</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=Vincent-Guiberteau" title="Code">💻</a></td>
    <td align="center"><a href="http://www.paul-pidou.name"><img src="https://avatars1.githubusercontent.com/u/4563446?v=4" width="100px;" alt=""/><br /><sub><b>Paul Pidou</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=PaulPidou" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/AntoninMarchardDev"><img src="https://avatars2.githubusercontent.com/u/29677243?v=4" width="100px;" alt=""/><br /><sub><b>Antonin Marchard</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=AntoninMarchardDev" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/maximelemarchand"><img src="https://avatars2.githubusercontent.com/u/31620346?v=4" width="100px;" alt=""/><br /><sub><b>Maxime Lm</b></sub></a><br /><a href="#design-maximelemarchand" title="Design">🎨</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/aaadryyy"><img src="https://avatars3.githubusercontent.com/u/20040637?v=4" width="100px;" alt=""/><br /><sub><b>Adrien Quillet</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=aaadryyy" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/EmGarr"><img src="https://avatars1.githubusercontent.com/u/9768541?v=4" width="100px;" alt=""/><br /><sub><b>Emilien Garreau</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=EmGarr" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/dprslt"><img src="https://avatars1.githubusercontent.com/u/10012070?v=4" width="100px;" alt=""/><br /><sub><b>dprslt</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=dprslt" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/GuillaumeErhard"><img src="https://avatars0.githubusercontent.com/u/25333848?v=4" width="100px;" alt=""/><br /><sub><b>Guillaume Erhard</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=GuillaumeErhard" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/morganeheng"><img src="https://avatars2.githubusercontent.com/u/45876652?v=4" width="100px;" alt=""/><br /><sub><b>morganeheng</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=morganeheng" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/deleva"><img src="https://avatars1.githubusercontent.com/u/48216408?v=4" width="100px;" alt=""/><br /><sub><b>deleva</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=deleva" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/Fred1402"><img src="https://avatars3.githubusercontent.com/u/48215877?v=4" width="100px;" alt=""/><br /><sub><b>Fred1402</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=Fred1402" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/jpacifico"><img src="https://avatars2.githubusercontent.com/u/6375548?v=4" width="100px;" alt=""/><br /><sub><b>Jonathan</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=jpacifico" title="Code">💻</a></td>
    <td align="center"><a href="http://www.yoan-dorny.com"><img src="https://avatars0.githubusercontent.com/u/23553867?v=4" width="100px;" alt=""/><br /><sub><b>Yoan</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=YoanDo" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/anth2o"><img src="https://avatars3.githubusercontent.com/u/33425718?v=4" width="100px;" alt=""/><br /><sub><b>Antoine</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=anth2o" title="Code">💻</a></td>
    <td align="center"><a href="http://www.thomas-robert.fr"><img src="https://avatars0.githubusercontent.com/u/4163601?v=4" width="100px;" alt=""/><br /><sub><b>Thomas ROBERT</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=ThomasRobertFr" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/lise-deguilhem"><img src="https://avatars3.githubusercontent.com/u/62648003?v=4" width="100px;" alt=""/><br /><sub><b>lise-deguilhem</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=lise-deguilhem" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/AntoineBruge"><img src="https://avatars1.githubusercontent.com/u/46377579?v=4" width="100px;" alt=""/><br /><sub><b>Antoine Bruge</b></sub></a><br /><a href="#projectManagement-AntoineBruge" title="Project Management">📆</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->


Thanks also go to people who are not on GitHub but still actively contributing to the project's sucess.


