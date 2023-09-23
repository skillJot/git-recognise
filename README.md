# git recognise - Open Contribution and Skills Recognition Initiative <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->

- [Introduction](#introduction)
- [Features](#features)
- [How can I, as a project owner, recognise and acknowledge contributions and skills](#how-can-i-as-a-project-owner-recognise-and-acknowledge-contributions-and-skills)
- [How can I, as a project contributor, showcase my contributions and skills?](#how-can-i-as-a-project-contributor-showcase-my-contributions-and-skills)
- [How to Contribute](#how-to-contribute)
- [References](#references)
- [License](#license)

## Introduction

Projects are powered by individuals, and fostering an environment of open and transparent recognition of contributions and skills is crucial for the professional development of these individuals.

The **git recognise** initiative offers a straightforward and transparent mechanism for projects to acknowledge the specific contributions made by individuals and the valuable skills they bring to the project. These acknowledgments and recognitions are not limited to those creating commits within a particular repository; they can extend to anyone contributing to the projects.

While our model may not be as comprehensive as end-to-end verifiable frameworks, we firmly believe that this simplified approach can significantly benefit individuals in their career paths. It achieves this by providing everyone with the opportunity to receive recognition and acknowledgment for their skills, all backed by a verifiable historical record using **git repositories**.

## Features

- **Contribution Templates**: We are presenting a simple contributions template, streamlining the process of acknowledging contributions in a machine-readable format. See the [Contributions Schema](schemas/contributions/README.md) for more details. The template is evolving and we're inviting domain experts to contribute.

- **Verifiable Profile**: Wa are introducing a simple verifiable profile template repository everyone can fork and set up within minutes. The repository contains your profile information and is used to elevate your professional profile by showcasing your contributions via git recognise. See the [Verifiable Profile](https://github.com/alenhorvat/verifiable-profile-template). The template is evolving and we're inviting domain experts to contribute.

- **Portfolio Viewer**: An online viewer that enables to view and check your portfolio and contributions. (coming soon)

## How can I, as a project owner, recognise and acknowledge contributions and skills

Start recognizing project contributions today in three simple steps:

1. Copy the [contributions.yaml](contributions.yaml) to your project's repository (root folder). See the [contributions definition](schemas/contributions/README.md) for more information about the structure and supported claims.

2. Add contributors and their roles/skills to the file according to the template.

3. Notify your users that you're using git-recognise

## How can I, as a project contributor, showcase my contributions and skills?

Begin showcasing your contributions in three simple steps:

- Fork the [Verifiable Profile Repository](https://github.com/alenhorvat/verifiable-profile-template)
  - Visit the repository
  - Click on the "Use this template" button on the top-right
    - Enter a name for your new repository. Repository name MUST be verifiable-profile
    - Click on "Create repository from template".
- Edit the **profile.yaml** by filling in your profile information and adding project repositories where you've contributed.
- Commit and push the changes to your repository.

Every time your project is using git-recognise, add the project to **profile.yaml**.

### View Your Verifiable Portfolio

(Coming Soon)

## How to Contribute

All types of contributions are encouraged and valued. See the [CONTRIBUTING](CONTRIBUTING.md) for different ways to help and details about how this project handles them. Please make sure to read the relevant section before making your contribution. It will make it a lot easier for us maintainers and smooth out the experience for all involved. The community looks forward to your contributions. 🎉

And if you like the project, but just don't have time to contribute, that's fine. There are other easy ways to support the project and show your appreciation, which we would also be very happy about:

- Star the project
- Tweet about it
- Refer this project in your project's readme
- Mention the project at local meetups and tell your friends/colleagues

## References

- [YAML](https://yaml.org/)

## License

Copyright and related rights waived via [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/).
