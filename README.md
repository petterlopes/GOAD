<div align="center">
  <h1><img alt="GOAD (Game Of Active Directory)" src="./docs/mkdocs/docs/img/logo_GOAD3.png"></h1>
  <br>
</div>

**GOADv3 - BETA VERSION, NOT READY**

:bookmark: GOADv3 Documentation : [https://orange-cyberdefense.github.io/GOAD/](https://orange-cyberdefense.github.io/GOAD/)

## Description
GOAD is a pentest active directory LAB project.
The purpose of this lab is to give pentesters a vulnerable Active directory environment ready to use to practice usual attack techniques.

> **Warning**
> This lab is extremely vulnerable, do not reuse recipe to build your environment and do not deploy this environment on internet without isolation (this is a recommendation, use it as your own risk).<br>
> This repository was build for pentest practice.

## Licenses
This lab use free windows VM only (180 days). After that delay enter a license on each server or rebuild all the lab (may be it's time for an update ;))

## Available labs

- [GOAD](./ad/GOAD/README.md) : 5 vms, 2 forests, 3 domains (full goad lab)
<div align="center">
<img alt="GOAD" width="800" src="./docs/img/GOAD_schema.png">
</div>

- [GOAD-Light](./ad/GOAD-Light/README.md) : 3 vms, 1 forest, 2 domains (smaller goad lab for those with a smaller pc)
<div align="center">
<img alt="GOAD Light" width="600" src="./docs/img/GOAD-Light_schema.png">
</div>

- [MINILAB](./ad/MINILAB/README.md): 2 vms, 1 forst, 1 domain (basic lab with one DC (windows server 2019) and one Workstation (windows 10))

- [SCCM](./ad/SCCM/README.md) : 4 vms, 1 forest, 1 domain, with microsoft configuration manager installed
<div align="center">
<img alt="SCCM" width="600" src="./docs/img/SCCMLAB_overview.png">
</div>

- [NHA](./ad/NHA/README.md) : A challenge with 5 vms and 2 domains. no schema provided, you will have to find out how break it.
