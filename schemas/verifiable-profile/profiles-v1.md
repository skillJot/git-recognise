# Profiles

## Description

git is a distributed version control system, however, most git repositories are published via public platforms, such as GitLab, GitHub, BitBucket, and others. However, repositories can also be self-hosted or hosted in private environments.

The central nature of platforms introduces platform specific user identifiers or handlers. These handlers are understood in the context of the platform and are used to identify users.

Since users can have accounts on different platforms, we need to have a way to express the ownership of different accounts. In this version, we introduce a simple account cross-referencing. Account cross-referencing means that user simply creates her verifiable profile repository at all providers and references all the handlers she owns in all profile files. Whenever a profile member is present, SkillJot will check whether the referenced repository references the given user handler.

This represents the simplest way of self-attesting account ownership.

Currently only pre-defined platforms are supported

- GitLab
- GitHub
- BitBucket
