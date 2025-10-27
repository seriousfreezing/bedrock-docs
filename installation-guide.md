---
description: Some tips on how to install the modpack.
---

# 📥 Installation Guide

## Client-side

Recommended: Use **Modrinth Launcher or CurseForge App** — that way you benefit the project monetarily.

* [**Modrinth Launcher**](https://support.modrinth.com/en/articles/8802250-modpacks-on-modrinth)
* [**CurseForge App**](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/160)
* [**ATLauncher**](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/361)
* [**GDLauncher**](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/142)

## Server-side

There are three ways to install the modpack on your server.

* [**Docker Compose**](https://docker-minecraft-server.readthedocs.io/en/latest/)
* [**mcman**](https://github.com/ParadigmMC/mcman)

<details>

<summary><strong>Packwiz</strong></summary>

Download the [packwiz-installer-bootstrap](https://github.com/packwiz/packwiz-installer-bootstrap/releases), move it to the **root folder** of your server, and add the following command to your **pre-launch command**:



* Auto-update or LTS

{% code overflow="wrap" fullWidth="true" %}
```
java -jar packwiz-installer-bootstrap.jar -g -s server https://raw.githubusercontent.com/seriousfreezing/bedrock-reloaded/refs/heads/latest/index.toml
```
{% endcode %}

&#x20;To switch to the latest stable version of the modpack, just change from `latest` to `lts`.



* Deprecated versions

{% code overflow="wrap" fullWidth="true" %}
```
java -jar packwiz-installer-bootstrap.jar -g -s server https://raw.githubusercontent.com/seriousfreezing/bedrock-reloaded/refs/heads/deprecated/1.21.4/index.toml
```
{% endcode %}

These are older versions of the modpack that are no longer supported.

</details>
