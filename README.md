<h1 align="left">Surfrider Plastic Origins</h1>

<a href="https://www.plasticorigins.eu/"><img width="80px" src="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/blob/master/assets/PlasticOrigins_logo.png" width="5%" height="5%" align="left" hspace="0" vspace="0"></a>

  <p align="justify">Proudly Powered by <a href="https://surfrider.eu/">SURFRIDER Foundation Europe</a>, the <a href="https://www.plasticorigins.eu/">PLASTIC ORIGINS</a> project is a citizen science project that uses AI to map plastic pollution in European rivers and share its data publicly. Check below to know more about project initiatives and how you can get involved. Please consider starring :star: the project's repositories to show your interest and support. We rely on YOU for making this project a success and thank you in advance for your contributions.</p>

_________________

[Plastic Origins](https://www.plasticorigins.eu/) is a project initiated by the not-for-profit [Surfrider Foundation Europe](https://surfrider.eu/) in search of solutions to address the source of ocean pollution. Supported by [citizens, associations, scientists, and socially responsible companies](https://www.plasticorigins.eu/team), the Plastic Origins project aims to map plastic pollution in European rivers by applying participatory science and Artificial Intelligence technology. This mapping data helps to identify areas of high impact, gain a deeper understanding of the problem on the field, and measure the evolution of pollution over time as well as to raise awareness among political decision-makers on the local, national, and European levels and urge them to act. It's a **hot topic**, here is why:

1. Plastic pollution is the second biggest threat to our Ocean after climate change.
2. Ocean plastic pollution mainly comes from terrestrial sources. Rivers are pathways for litter entering the ocean. For instance, a bottle lost in Paris city might end-up in the Seine River and reach the sea.
3. Investigating river plastic pollution helps to localize plastic inputs and monitor trends, improvements and measures efficiency.
4. There is currently no obligation for European countries to monitor river plastic pollution. The European water framework directive does not include plastic pollution as an indicator for good environmental status.


## All you need to know to get involved

Developments and improvements of Surfrider Plastic Origins tech tools are led by a bunch of amazing volunteers. Surfrider Europe on its own does not have within the organisation technical competencies thus we rely on YOU for making this project a success and welcome any help since there are many ways to contribute, even if you’re not a technical person.

Only with a common effort we can refine the technology, improve and duplicate it, which is why the code is open-source on the [Surfrider Foundation Europe GitHub page](https://github.com/surfriderfoundationeurope), and collected data is available online and publicly accessible on the [Plastic Origins website](https://www.plasticorigins.eu/). 


### How does it work?

* Volunteers film riverbanks via the Plastic Origins mobile application available on [Android](https://play.google.com/store/apps/details?id=com.plasticorigins&hl=fr&gl=US) & [IOS](https://apps.apple.com/fr/app/plastic-origins/id1532710998) (collection of videos and manually labeled images) or by using GoPro (collection of videos uploaded to the [Plastic Origins website](https://www.plasticorigins.eu/)).
* Our [Data Labeling Platform](https://www.trashroulette.com/) allows building a labeled image dataset via crowdsourcing (people tag an existing image dataset and/or contribute to this dataset by uploading images) that helps to improve our AI waste detection and tracking prediction.
* AI recognizes and classifies waste on collected videos to give an open source mapping that feeds and collects data in #OpenData.


### How we work

We use the following tools for project management and dev:

* [Microsoft Teams](https://teams.microsoft.com/l/team/19%3aa3a655a6dce949ed9fe1a6db4e2d6a95%40thread.skype/conversations?groupId=c312e78d-ae29-4ec0-9cd6-1f9999167ebe&tenantId=1fb581f3-43ef-4dfd-b8f7-4ca7bc32ec24) -> for discussions.
* [Azure portal](https://portal.azure.com/#home) -> for building, testing and deploying.
* [GitHub](https://github.com/surfriderfoundationeurope) -> for storing codes, codes' descriptions, documentation, and Architectural Decision Record (ADR).

Our development language is English. All comments and documentation should be written in English so we can share our learnings with developers around the world.

<p align="left">
   <img src="assets/PO project Diagram.png" width="100%" height="100%">
 </p>


### Repo organisation

| ID | Repository | Description | RG-Azure | Maintainers |
| -- | ---------- | ----------- | -------- |------------ |
| GEN | [The-Plastic-Origins-Project](https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project) | You are currently in this repo used for the Plastic Origins project description. |  |[@AntoineBruge](https://github.com/AntoineBruge) |
| APP | [App-Plastic-Origins](https://github.com/surfriderfoundationeurope/App-Plastic-Origins) `Private` | `WIP` - Plastic Origins Mobile app (available on [Android](https://play.google.com/store/apps/details?id=com.plasticorigins&hl=fr&gl=US) & [IOS](https://apps.apple.com/fr/app/plastic-origins/id1532710998)). | |[@AlexisReverte](https://github.com/AlexisReverte) |
| Data LP | [labelcv-web](https://github.com/surfriderfoundationeurope/labelcv-web) | Frontend of our [Data Labeling Platform](https://www.trashroulette.com/). | [Dev](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastic-labellingplatform-dev) [Prod](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-labellingplatform-prod​) |[@cmaneu](https://github.com/cmaneu) / [@bertrandlalo](https://github.com/bertrandlalo)|
| API LP | [LabelCV](https://github.com/surfriderfoundationeurope/LabelCV) | `WIP` - Backend of our [Data Labeling Plateforme](https://www.trashroulette.com/). |  |[@cmaneu](https://github.com/cmaneu)|
| API | [po-mobile-backend](https://github.com/surfriderfoundationeurope/po-mobile-backend) | Plastic Origins 'all in one' Backend - API for data upload from app or website. |[Dev](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastico-mobilebackend-dev​) [Prod](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastico-mobilebackend-prod) |[@cmaneu](https://github.com/cmaneu) / [@benzinamohamedelyes](https://github.com/benzinamohamedelyes)  / [@Vincent-Guiberteau](https://github.com/Vincent-Guiberteau)|
| Data MGT | [etl](https://github.com/surfriderfoundationeurope/etl) | ETL script used to send videos to AI, read results and write in DB | [Dev](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastico-etl-dev​) [Prod](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastico-etl-prod​) |[@cl3m3nt](https://github.com/cl3m3nt)|
| AI | [MOT](https://github.com/surfriderfoundationeurope/mot) | AI model currently used to detect trash on videos | [Dev](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastic-ai-dev) [Prod](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastic-ai-prod)|[@charlesollion](https://github.com/charlesollion) / [@mchagneux](https://github.com/mchagneux)|
| DB MGT | [plasticorigins-ops-db](https://github.com/surfriderfoundationeurope/plasticorigins-ops-db) | All scripts related to our PostGreSQL database. | [Dev](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastico-database-dev​) [Prod](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastico-database-prod​) |[@ChristopheHvd](https://github.com/ChristopheHvd) / [@cmaneu](https://github.com/cmaneu)|
| BI DB | [fillbidatabase](https://github.com/surfriderfoundationeurope/fillbidatabase) | Code for the recurring job that fills Bi database |[Dev](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastico-database-dev​) [Prod](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastico-database-prod​) |[@ChristopheHvd](https://github.com/ChristopheHvd) / [@clembac](https://github.com/clembac) / [@MaxLemarchand](https://github.com/MaxLemarchand) |
| API DB | [api-plastic-origins](https://github.com/surfriderfoundationeurope/api-plastic-origins) `Private` | `WIP` - API that allows access our data to do cartographic visualization. |[Dev](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastico-APIdb-dev​) [Prod](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastico-APIdb-prod​)|[@AntoineGirard](https://github.com/AntoineGirard)|
| Data VIZ | [Plastic-origin](https://github.com/surfriderfoundationeurope/plastic-origin) `Private`| `WIP` - Frontend of our [Plastic Origins website](https://www.plasticorigins.eu/) | [Dev](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastico-publicwebsite-dev) [Prod](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastico-publicwebsite-prod​)|[@YoanDo](https://github.com/YoanDo)|
| CMS | [plastic-origin-web-cms](https://github.com/surfriderfoundationeurope/plastic-origin-web-cms) `Private`| `WIP` - Headless cms for our [Plastic Origins website](https://www.plasticorigins.eu/)  | [Dev](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastico-publicwebsite-dev) [Prod](https://portal.azure.com/#@surfrider.eu/resource/subscriptions/ad31bdcf-3e05-41d4-857b-ae5b767fc8cd/resourceGroups/rg-plastico-publicwebsite-prod​)|[@YoanDo](https://github.com/YoanDo)|


### Ready? Get involved!

Please, get in touch with [@AntoineBruge](https://github.com/AntoineBruge).



## Contributors

Thanks everyone !

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-35-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
                   	                	              	                  	                      	                 
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/Clemsurfrider"><img src="https://avatars3.githubusercontent.com/u/61323067?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Clemsurfrider</b></sub></a><br /><a href="#design-Clemsurfrider" title="Design">🎨</a></td>
    <td align="center"><a href="https://github.com/ChristopheHvd"><img src="https://avatars3.githubusercontent.com/u/1823079?v=4?s=100" width="100px;" alt=""/><br /><sub><b>ChristopheHvd</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=ChristopheHvd" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/clembac"><img src="https://avatars0.githubusercontent.com/u/11059568?v=4?s=100" width="100px;" alt=""/><br /><sub><b>clément baccar</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=clembac" title="Code">💻</a></td>
    <td align="center"><a href="https://www.linkedin.com/in/rapha%C3%ABlle-bertrand-lalo-185679b9/"><img src="https://avatars3.githubusercontent.com/u/22340670?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Raphaëlle Bertrand-Lalo</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=bertrandlalo" title="Code">💻</a></td>
    <td align="center"><a href="http://www.maneu.fr"><img src="https://avatars2.githubusercontent.com/u/790974?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Christopher MANEU</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=cmaneu" title="Code">💻</a></td>
    <td align="center"><a href="http://r.courivaud@gmail.com"><img src="https://avatars1.githubusercontent.com/u/20335094?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Raphaël Courivaud</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=rcourivaud" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/charlesollion"><img src="https://avatars2.githubusercontent.com/u/10595147?v=4?s=100" width="100px;" alt=""/><br /><sub><b>charlesollion</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=charlesollion" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/cl3m3nt"><img src="https://avatars1.githubusercontent.com/u/8882133?v=4?s=100" width="100px;" alt=""/><br /><sub><b>cl3m3nt</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=cl3m3nt" title="Code">💻</a></td>
    <td align="center"><a href="http://felix.voituret.fr"><img src="https://avatars3.githubusercontent.com/u/250322?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Félix Voituret</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=Faylixe" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/lucasrymenants"><img src="https://avatars2.githubusercontent.com/u/15192989?v=4?s=100" width="100px;" alt=""/><br /><sub><b>lucasrymenants</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=lucasrymenants" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/Vincent-Guiberteau"><img src="https://avatars3.githubusercontent.com/u/6638957?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Tekateyy</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=Vincent-Guiberteau" title="Code">💻</a></td>
    <td align="center"><a href="http://www.paul-pidou.name"><img src="https://avatars1.githubusercontent.com/u/4563446?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Paul Pidou</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=PaulPidou" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/AntoninMarchardDev"><img src="https://avatars2.githubusercontent.com/u/29677243?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Antonin Marchard</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=AntoninMarchardDev" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/maximelemarchand"><img src="https://avatars2.githubusercontent.com/u/31620346?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Maxime Lm</b></sub></a><br /><a href="#design-maximelemarchand" title="Design">🎨</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/aaadryyy"><img src="https://avatars3.githubusercontent.com/u/20040637?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Adrien Quillet</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=aaadryyy" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/jules-larue"><img src="https://avatars.githubusercontent.com/u/27008404?s=400&u=600b78901f163dd02219958b045871f3e64afb00&v=4?s=100" width="100px;" alt=""/><br /><sub><b>jules-larue</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=jules-larue" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/EmGarr"><img src="https://avatars1.githubusercontent.com/u/9768541?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Emilien Garreau</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=EmGarr" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/dprslt"><img src="https://avatars1.githubusercontent.com/u/10012070?v=4?s=100" width="100px;" alt=""/><br /><sub><b>dprslt</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=dprslt" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/GuillaumeErhard"><img src="https://avatars0.githubusercontent.com/u/25333848?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Guillaume Erhard</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=GuillaumeErhard" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/morganeheng"><img src="https://avatars2.githubusercontent.com/u/45876652?v=4?s=100" width="100px;" alt=""/><br /><sub><b>morganeheng</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=morganeheng" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/deleva"><img src="https://avatars1.githubusercontent.com/u/48216408?v=4?s=100" width="100px;" alt=""/><br /><sub><b>deleva</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=deleva" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Fred1402"><img src="https://avatars3.githubusercontent.com/u/48215877?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Fred1402</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=Fred1402" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/jpacifico"><img src="https://avatars2.githubusercontent.com/u/6375548?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jonathan</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=jpacifico" title="Code">💻</a></td>
    <td align="center"><a href="http://www.yoan-dorny.com"><img src="https://avatars0.githubusercontent.com/u/23553867?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Yoan</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=YoanDo" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/anth2o"><img src="https://avatars3.githubusercontent.com/u/33425718?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Antoine</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=anth2o" title="Code">💻</a></td>
    <td align="center"><a href="http://www.thomas-robert.fr"><img src="https://avatars0.githubusercontent.com/u/4163601?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Thomas ROBERT</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=ThomasRobertFr" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/lise-deguilhem"><img src="https://avatars3.githubusercontent.com/u/62648003?v=4?s=100" width="100px;" alt=""/><br /><sub><b>lise-deguilhem</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=lise-deguilhem" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/AntoineBruge"><img src="https://avatars1.githubusercontent.com/u/46377579?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Antoine Bruge</b></sub></a><br /><a href="#projectManagement-AntoineBruge" title="Project Management">📆</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/IKozitska"><img src="https://avatars.githubusercontent.com/u/79417358?v=4?s=100" width="100px;" alt=""/><br /><sub><b>iuliia.kozitska</b></sub></a><br /><a href="#projectManagement-IKozitska" title="Project Management">📆</a></td>
    <td align="center"><a href="https://github.com/AlexisReverte"><img src="https://avatars.githubusercontent.com/u/6009041?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Alexis Reverte</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=AlexisReverte" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/AntoineGirard"><img src="https://avatars.githubusercontent.com/u/12141434?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Antoine Girard</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=AntoineGirard" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/benzinamohamedelyes"><img src="https://avatars.githubusercontent.com/u/69303140?v=4?s=100" width="100px;" alt=""/><br /><sub><b>benzinamohamedelyes</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=benzinamohamedelyes" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/francis-valla"><img src="https://avatars.githubusercontent.com/u/42340008?v=4?s=100" width="100px;" alt=""/><br /><sub><b>francis-valla</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=francis-valla" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/mchagneux"><img src="https://avatars.githubusercontent.com/u/28506422?v=4?s=100" width="100px;" alt=""/><br /><sub><b>mchagneux</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=mchagneux" title="Code">💻</a></td>
    <td align="center"><a href="http://www.jeanremypraud.com"><img src="https://avatars.githubusercontent.com/u/3785695?v=4?s=100" width="100px;" alt=""/><br /><sub><b>JR</b></sub></a><br /><a href="https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/commits?author=jeanremy" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->


Thanks also go to people who are not on GitHub but still actively contributing to the project's sucess.


## License

We’re using the `MIT` License. For more details, check [`LICENSE`](https://github.com/surfriderfoundationeurope/The-Plastic-Origins-Project/blob/master/LICENSE) file.
