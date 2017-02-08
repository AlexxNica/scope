<p align="center">
  <img width="800" height="352" src="https://cloud.githubusercontent.com/assets/532272/22727205/6f4d658a-ed8c-11e6-8921-8baf70f011e0.jpg">
</p>

# Scope - Serverless Open Source Status Board</h1>

Scope is a customizable birdeye's view of your open source project.

Built using event driven serverless tech, the application can be cloned down & deployed for your open source project in minutes.

Deploy it as a stand-alone application or embed it directly into your project's site.

Run it for **[free](https://aws.amazon.com/free/)** under AWS's generous free tier.

## Table of Contents
<!-- ⛔️ AUTO-GENERATED-CONTENT:START (TOC:collapse=true&collapseText=Click to expand) -->
<details>
<summary>Click to expand</summary>
- [Features](#features)
- [Why we built it](#why-we-built-it)
- [Contributing](#contributing)
- [Setup](#setup)
- [FAQ](#faq)
</details>
<!-- AUTO-GENERATED-CONTENT:END -->

## Features

<img align="right" width="391" height="218" src="https://cloud.githubusercontent.com/assets/532272/22727459/cad63336-ed8d-11e6-8924-fce36f239a84.gif">

- Look mom! No servers!
- Avoid github rate limiting via event driven webhooks
- Customizable styles 💁
- Map your projects tags into the columns you want

Map your projects github labels to columns of your choosing and have them automatically update.

## Why we built it

We built this tool for our community to help keep people up to speed with what is happening with the serverless project & to highlight places where we actively want feedback + collaboration.

- Quickly sort and see high priority issues & Pull requests
- Call out which issues need attention from your community
- Zoom into important aspect of your open source project

[Front-end Documentation & setup](./backend/README.md)

[Backend Documentation & setup](./backend/README.md)

# Contributing

Want to contribute back to the project? Drop an issue or open up a PR.

## Setup

**First things first** 👉 [Setup your AWS account](https://youtu.be/HSd9uYj2LJA) and `npm i serverless -g` to be able to deploy your status board

1. Deploy the serverless Backend. [Follow these instructions](./backend/README.md)

2. Grab your API endpoints & plug them into the front-end in `/frontend/src/custom.config.js`

3. Configure the front-end columns with your projects labels, build and deploy it. [Follow these instructions](./frontend/README.md)

## FAQ

**Do I need an AWS account for this to work?**

Yes, but this will fall into the free tier of an AWS account. [Free tier Signup](https://aws.amazon.com/free/)

**Does it need to show all my issues?**

Nope. You choose what labels show up in each column

**Do I have to show recently completed items?**

Nope. You can toggle off that column in the front-end config.

**I just setup the front-end, where are the recently completed items?**

They will start flowing in once you start closing issues/PRs in your repo
