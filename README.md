<p align="center">
  <img src="logo.png" alt="Grok Bot mark: a white robot head set inside a letter G." width="220">
</p>

# Grok Bot by Fernando Santos

Grok Bot is Fernando Santos's personal GitHub App for admins who install or approve it, and for people who review the changes it opens on his repositories and organizations. It is not an official xAI app.

This repository explains how to grant and remove that access. It does not contain the bot, its credentials, or a service to start.

[Install Grok Bot](https://github.com/apps/grok-bot-by-fernando-santos)

## What it can do

On repositories where it is installed, Grok Bot can:

- Clone the repository and push branches
- Open pull requests and issues, and comment on them
- Read CI results

It runs without webhooks.

## Requirements

| Requirement | What you need |
| --- | --- |
| GitHub permission | Permission to install GitHub Apps on the personal account or organization |
| Repository list | The repositories Grok Bot should use, and no others |
| Organization approval | The owner's approval, when the organization requires it |
| Local setup | None. Cloning this repository does not install the app |

## Install

1. Open [Install Grok Bot](https://github.com/apps/grok-bot-by-fernando-santos) with an account that can manage the target repositories.
2. Read the permissions GitHub shows. An existing installation keeps its current permissions until an owner approves an update. Stop if you do not want to grant what it lists.
3. Select only the repositories Grok Bot should use, and no others.
4. On an organization, wait for the owner's approval when the organization requires it.
5. Read the diff and the CI result before you merge.

## Stop access

Open the personal account or organization at **Settings → GitHub Apps / Installed GitHub Apps**. Suspend Grok Bot to pause access. Uninstall it to remove the installation. While it is suspended or uninstalled, it cannot read or change those repositories.

## Maintainer

[Fernando Santos (@fernando-s97)](https://github.com/fernando-s97)
