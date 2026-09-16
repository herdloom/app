# Privacy

Short version: Shepherd runs on your machine, and your code stays on your
machine. There is no telemetry, no analytics, and no account with us.

## What stays local

- Your repositories, branches and worktrees
- Your tickets, plans, reviews and run history
- Your notes and knowledgebases
- Agent output and logs

All of it lives in a folder on your Mac. Nothing is uploaded to us, because
there is no "us" to upload to: Shepherd has no server and no account system.

## What leaves your machine, and only because you asked

| Where | When | What goes |
|---|---|---|
| The coding agent CLIs you connect | When an agent runs | Whatever that agent sends its provider: your prompt and the code it reads. This is the agent's own connection, under your own account. |
| GitHub | When you open a pull request, merge, or watch issues | Your branches and the issue data you asked for, through your own git and GitHub login. |
| Jira | When you turn the Jira watch on | A search for the issues you labelled, through the credentials you entered. |
| GitHub releases | When the app checks for an update | A request for the release list, so the app can tell you a new build exists. |

Turn a connection off and that traffic stops.

## Credentials

Tokens you enter are stored on your machine so the app can use them. They are
not sent anywhere except to the service they belong to. Agent CLIs keep their
own logins; Shepherd does not read them.

## Logs and reports

Agent logs are kept locally and aged out. If you send a problem report, the app
builds a bundle for you, redacts token-shaped strings and secret-looking values,
and shows you the file. Nothing is sent until you attach it yourself.

## Children

Shepherd is a developer tool and is not directed at children.

## Changes

If this ever changes, it changes here first, and the release notes will say so.

Questions: open a [discussion](../../discussions).
