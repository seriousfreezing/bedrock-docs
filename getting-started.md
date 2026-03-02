---
description: Everything you need to get playing in minutes.
---

# 🚀 Getting Started

## 💻 Client-side

Learn how to install the modpack with your favorite launcher, and enjoy all features.\
For the easiest setup and to support the project, we recommend **Modrinth Launcher** or **CurseForge App**.

* <img src="https://cdn.modrinth.com/modrinth-new.png" alt="Modrinth App" data-size="line"> [**Modrinth Launcher**](https://support.modrinth.com/en/articles/8802250-modpacks-on-modrinth)
* <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/15a10966-3031-4c71-9c5d-0b2aa31b1af2/dfvg2h8-3bf1d4c4-8fef-4606-b6f4-d2fbf4de86f5.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzE1YTEwOTY2LTMwMzEtNGM3MS05YzVkLTBiMmFhMzFiMWFmMlwvZGZ2ZzJoOC0zYmYxZDRjNC04ZmVmLTQ2MDYtYjZmNC1kMmZiZjRkZTg2ZjUucG5nIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.jBbOAg_f1LWPV1s7zEzU-lwy1KBCCjkG5SvfOXIXaus" alt="CurseForge App" data-size="line"> [**CurseForge App**](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/160)
* <img src="https://cdn2.steamgriddb.com/icon_thumb/bb8bf48a4f86fb1a77d0d0953d87958e.png" alt="Prism Launcher" data-size="line"> [**Prism Launcher**](https://prismlauncher.org/wiki/getting-started/download-modpacks/)
* <img src="https://user-images.githubusercontent.com/66513643/112387891-a3063780-8cf2-11eb-8f36-63051dd9d253.png" alt="GDLauncher" data-size="line"> [**GDLauncher**](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/142)

## 🖥️ Server-side

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
  List of versions: `1.21.4/1.21.5/1.21.6/1.21.8/1.21.10`

</details>
