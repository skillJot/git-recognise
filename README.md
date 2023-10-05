# git recognise <!-- omit in toc -->

Empowering Skill Endorsement: An initiative for verifiable endorsement of skills and contributions across all projects

## Table of Contents <!-- omit in toc -->

- [Introduction](#introduction)
- [How do I start?](#how-do-i-start)
- [Features](#features)
- [Roadmap](#roadmap)
- [How to Contribute](#how-to-contribute)
- [References](#references)
- [License](#license)

## Introduction

Projects are powered by people, and fostering an environment of transparent and verifiable endorsement of skills and contributions is fundamental for the professional development of all contributors.

The fundamental concept revolves around utilizing Git to acknowledge and endorse contributors' skills, which are showcased through their contributions.

**git recognise** introduces a straightforward and transparent mechanism for projects to acknowledge the specific contributions made by all contributors, not only those who push the code, and the valuable skills contributors bring to the project.

## How do I start?

### Are you a project owner? Recognise and acknowledge contributions and skills

Start recognizing project contributions today in three simple steps:

1. Copy the [contributions.yaml](contributions.yaml) to your project's repository (root folder). See the [contributions definition](schemas/contributions/README.md) for more information about the structure and supported claims.

2. Add contributors and their roles/skills to the file according to the template.

3. Notify your users that you're using git-recognise

### Are you a contributor? Showcase your contributions and skills

Showcase your contributions in three simple steps:

- Fork the [Verifiable Profile Repository](https://github.com/skilljot/verifiable-profile-template)
  - Visit the repository
  - Click on the "Use this template" button on the top-right
    - Enter a name for your new repository. Repository name MUST be verifiable-profile
    - Click on "Create repository from template".
- Edit the **profile.yaml** by filling in your profile information and adding project repositories where you've contributed.
- Commit and push the changes to your repository.

Every time your project is using git-recognise, add the project to **profile.yaml**.

### Are you a contributor or verifier? Check out the Verifiable Portfolio

Visit [SkillJot](https://www.skilljot.com) and enter your or user's GitHub handler. If user's projects are leveraging the power of git-recognise, you'll see it in the profile.

## Features

- **Contribution Templates**: We are presenting a simple contributions template, streamlining the process of acknowledging contributions in a machine-readable format. See the [Contributions Schema](schemas/contributions/README.md) for more details. The template is evolving and we're inviting domain experts to contribute.

- **Verifiable Profile**: Wa are introducing a simple verifiable profile template repository everyone can fork and set up within minutes. The repository contains your profile information and is used to elevate your professional profile by showcasing your contributions via git recognise. See the [Verifiable Profile](https://github.com/alenhorvat/verifiable-profile-template). The template is evolving and we're inviting domain experts to contribute.

- **Portfolio Viewer**: An online viewer that enables to view and check your portfolio and contributions. Visit [SkillJot](https://www.skilljot.com)

## Roadmap

- Align with the [All Contributors](https://github.com/all-contributors/all-contributors) specifications
- Align with the [Open Badges](https://openbadges.org/) and [W3C Verifiable Credentials](https://www.w3.org/TR/vc-data-model-2.0/) data models
- Improve the workflow

## How to Contribute

All types of contributions are encouraged and valued. See the [CONTRIBUTING](CONTRIBUTING.md) for different ways to help and details about how this project handles them. Please make sure to read the relevant section before making your contribution. It will make it a lot easier for us maintainers and smooth out the experience for all involved. The community looks forward to your contributions. 🎉

And if you like the project, but just don't have time to contribute, that's fine. There are other easy ways to support the project and show your appreciation, which we would also be very happy about:

- Star the project
- Tweet about it
- Refer this project in your project's readme
- Mention the project at local meetups and tell your friends/colleagues

## References

- [All Contributors](https://github.com/all-contributors/all-contributors)
- [Open Badges](https://openbadges.org/)
- [W3C Verifiable Credentials](https://www.w3.org/TR/vc-data-model-2.0/)
- [YAML](https://yaml.org/)

## License

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
