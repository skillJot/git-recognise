# git-recognise JSON Schemas <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->

- [Contributing](#contributing)
- [JSON schema version](#json-schema-version)
- [Folder structure](#folder-structure)

## Contributing

When you create a new JSON Schema, make sure to follow the folder structure described below.

Create a new branch from the `main` branch, commit your changes, and open a pull request.

## JSON schema version

Currently JSON schema version [2020-12](https://json-schema.org/draft/2020-12/release-notes.html) is used.

## Folder structure

The `schemas/<schema name>` folder is where we store all the [JSON Schemas](https://json-schema.org/).

Each JSON Schema lives in its own folder.

In each schema folder, we can find:

- a `README.md` file, which briefly describes the JSON Schema, and links to relevant documentation pages. More importantly, this README also shows the changes between the different versions of the schema.
- 1 subfolder per version. These folders are named `YYYY-MM(_VV)`. Examples: `2021-11`, `2022-02`, `2022-02_01`, etc. Year (YYYY) and month (MM) of publication are mandatory, while a version number (VV) can be added if multiple versions of the schema are published during a specific month. The date of "publication" corresponds to the date of the merge to the `main` branch. For example, if we merge a pull request in March 2022, we name the folder `2022-03`. If we need to publish a new version of the schema during the same month, we add version number (`_01`, `_02`, etc.).

In a schema version subfolder (e.g. `2021-11`), we store:

- `schema.json`: the actual JSON Schema.
- `examples/` folder (optional): a directory containing JSON examples, which are automatically tested against the JSON Schema defined in `schema.json`
