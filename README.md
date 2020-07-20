# Plumbing

Collection of common Configs for Project Management and CI/CD.

| probot                                                            | git                                                                         | description                                                   |
|-------------------------------------------------------------------|-----------------------------------------------------------------------------|---------------------------------------------------------------|
| [settings](https://probot.github.io/apps/settings/)               | [probot/settings](https://github.com/probot/settings)                       | Configure Github Projects by Source.                          |
| [stale](https://probot.github.io/apps/stale/)                     | [probot/stale](https://github.com/probot/stale)                             | Handle stale issues.                                          |
| [release-drafter](https://probot.github.io/apps/release-drafter/) | [toolmantim/release-drafter](https://github.com/toolmantim/release-drafter) | Creates a Human Readable Release Change Log.                  |
| [boring-cyborg](https://probot.github.io/apps/boring-cyborg/)     | [kaxil/boring-cyborg](https://github.com/kaxil/boring-cyborg)               | Different util actions like, automatically label Pull Request |

## Usage

For Using in other Github Projects use the Probot Repo Config, more informations at [probot.github.io](https://probot.github.io/docs/best-practices/#configuration).

*example: `.github/stale.yml`*
```ỳaml
_extends: plumbing
```
