# StarCraft2-font

[comment]: <> (The following are some information about this project)
[![Last Update](https://img.shields.io/badge/Last%20Update-February%202018-red.svg)]()
[![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen.svg)]()
[![Release](https://img.shields.io/badge/Release-ver.1.0.0-green.svg)]()
[![Tool](https://img.shields.io/badge/Design%20Software-Adobe%20Illustrator-blue.svg)]()

> This is not designed or uploaded by official （Blizzard Entertainment, Inc.）.

> You can see the demo file [here](https://jason40418.github.io/starcraft2-font/icons-reference.html).
If you have any problem please leave issue and I would response ASAP.

## Getting Started

The following is the basic instructions help you to learn how to use this font in your project.

> If you have experience in using [Font Awesome](https://fontawesome.com/) before, you would learn this in a few minutes.

### Prerequisites

1. Download the whole project from [here](https://github.com/jason40418/starcraft2-font/archive/master.zip).
2. Extract file and copy **font** folder and **starcraft2-font.css** file into your project.

> If you want to put .css file into different folder level, please learn how to change the code in *Installing* part.

### Installing

A step by step series of examples that tell you have to get a development env running

**First**, you need to input .css file in your website.

```
<link rel="stylesheet" href="starcraft2-font.css" />
```

**Second**, use it by two way **css mapping** or **character mapping**, the following is the example use character for *grandmaster* icon.

* Use it with ```div``` element  
```
<div class="sc2 sc2-grandmaster"></div>
```
```
<div data-icon="d" class="sc2"></div>
```

* Use it with ```i``` element  
```
<i class="sc2 sc2-grandmaster">
```

**Appendix**, make **starcraft2-font.css** and **font** folder in different folder level.

Open **starcraft2-font.css** file and modify the following file location that you could make files in different localtion.

> **Recommand** With website management you need to put same type of file in same folder.

```
@font-face {
  font-family: "starcraft2-font";
  src:url("../fonts/starcraft2-font.eot");
  src:url("../fonts/starcraft2-font.eot?#iefix") format("embedded-opentype"),
    url("../fonts/starcraft2-font.woff") format("woff"),
    url("../fonts/starcraft2-font.ttf") format("truetype"),
    url("../fonts/starcraft2-font.svg#starcraft2-font") format("svg");
  font-weight: normal;
  font-style: normal;

}
```

## Built With

* [fontastic](http://fontastic.me/) - Used to generate font and css file.
* [Adobe illustrator](https://www.adobe.com/tw/products/illustrator.html) - Used to design icon and export to svg format.

## Versioning

We use [SemVer](http://semver.org/) for versioning.

## Authors

* **Jason Lin** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)