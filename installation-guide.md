---
description: Some tips on how to install the modpack.
---

# 📥 Installation Guide

## 💻 Client-side

Recommended: Use **Modrinth Launcher or CurseForge App** — that way you benefit the project monetarily.

* [**Modrinth Launcher**](https://support.modrinth.com/en/articles/8802250-modpacks-on-modrinth)
* [**CurseForge App**](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/160)
* [**ATLauncher**](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/361)
* [**GDLauncher**](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/142)

## 🖥️ Server-side

Currently, only the **Packwiz** method is available. More installation methods will be **added** in the **future.**

1. Download the [packwiz-installer-bootstrap.jar](https://github.com/packwiz/packwiz-installer-bootstrap/releases)
2. Move it to server's root folder.
3. Add this command to your pre-launch command:

{% code overflow="wrap" fullWidth="false" %}
```
java -jar packwiz-installer-bootstrap.jar -g -s server https://raw.githubusercontent.com/seriousfreezing/bedrock-reloaded/refs/heads/latest/index.toml
```
{% endcode %}

* Switch to the Long-Term Support version by replace `latest` with `lts`.

<details>

<summary>Older Versions</summary>

{% code overflow="wrap" fullWidth="false" %}
```
java -jar packwiz-installer-bootstrap.jar -g -s server https://raw.githubusercontent.com/seriousfreezing/bedrock-reloaded/refs/heads/deprecated/1.21.4/index.toml
```
{% endcode %}

* These versions are no longer supported.\
  List of versions: `1.21.4/1.21.5/1.21.6/1.21.8`

</details>
