<p align="center">
  <a href="https://getleon.ai"><img width="800" src="https://getleon.ai/img/hero-animation.gif" /></a>
</p>

<h1 align="center">
  <a href="https://getleon.ai"><img width="96" src="https://getleon.ai/img/logo.svg" alt="Leon"></a><br>
  Leon
</h1>

_<p align="center">Your open-source personal assistant.</p>_

**Leon** is an **open-source personal assistant** who can live **on your server**.

He **does stuff** when you **ask him to**.

You can **talk to him** and he can **talk to you**.
You can also **text him** and he can also **text you**.
If you want to, Leon can communicate with you by being **offline to protect your privacy**.

### Why?

> 1. If you are a developer (or not), you may want to build many things that could help in your daily life.
>    Instead of building a dedicated project for each of those ideas, Leon can help you with his
>    Skills structure.
> 2. With this generic structure, everyone can create their own skills and share them with others.
>    Therefore there is only one core (to rule them all).
> 3. Leon uses AI concepts, which is cool.
> 4. Privacy matters, you can configure Leon to talk with him offline. You can already text with him without any third party services.
> 5. Open source is great.

> This repository contains the following nodes of Leon:
>
> - The server
> - Skills
> - The web app
> - The hotword node
> - The TCP server (for inter-process communication between Leon and third-party processes such as spaCy)
> - The Python bridge (the connector between Python core and skills)

### What is Leon able to do?

> Today, the most interesting part is about his core and the way he can scale up. He is pretty young but can easily scale to have new features (skills).
> You can find what he is able to do by browsing the [skills list](https://github.com/leon-ai/leon/tree/develop/skills).<br>
> Please do know that after the official release, we will build many skills along with the community. Feel free to [join us on Discord](https://discord.gg/MNQqqKg) to be part of the journey.

Sounds good to you? Then let's get started!

## ☁️ Try with a Single-Click

Gitpod will automatically setup an environment and run an instance for you.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/leon-ai/leon)

### Prerequisites

- [Node.js](https://nodejs.org/) >= 16
- [npm](https://npmjs.com/) >= 8
- Supported OSes: Linux, macOS and Windows

To install these prerequisites, you can follow the [How To section](https://docs.getleon.ai/how-to/) of the documentation.

### Installation

```sh
# Install the Leon CLI
npm install --global @leon-ai/cli

# Install Leon (stable branch)
leon create birth
# OR install from the develop branch: leon create birth --develop
```

### Usage

```sh
# Check the setup went well
leon check

# Run
leon start

# Go to http://localhost:1337
# Hooray! Leon is running
```

### Docker Installation

```sh
# Install Leon
leon create birth --docker

# Run
leon start

# Go to http://localhost:1337
# Hooray! Leon is running
```

[MIT License](https://github.com/leon-ai/leon/blob/develop/LICENSE.md)
