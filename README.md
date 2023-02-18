![W3C Logo](https://www.w3.org/Icons/w3c_home)

[![Echidna Auto-publish](https://github.com/w3c/vc-spec-directory/actions/workflows/auto-publish.yml/badge.svg)](https://github.com/w3c/vc-spec-directory/actions/workflows/auto-publish.yml)

# Verifiable Credential Specifications Directory

This repository contains a directory created by the
[W3C Verifiable Credentials Working Group](https://www.w3.org/groups/wg/vc)
(VC WG) for the purpose of discovering specifications known to exist in the
Verifiable Credentials Ecosystem.

An Editor's Draft of this repository is available at
https://w3c.github.io/vc-spec-directory/.

## Adding New Entries to the Directory

In order to add a new specification to this directory, you must add a JSON file
to the [./specifications](./specifications) directory and
[open a pull request](https://github.com/w3c/vc-spec-directory/pulls)
to add the file to this repository.

Here is an [example specification entry](https://w3c.github.io/vc-spec-directory/specifications/example.json):

```jsonc
{
  // These fields are required
  "name": "example",
  "specification": "https://example.github.io/example-spec/",
  "contactEmail": "",
  // These fields are optional
  "contactName": "W3C Credentials Community Group",
  "contactWebsite": "",
  "vocabularyDefinition": ""
}
```

Your Pull Request will be automatically validated, please ensure
that all of the automated tests pass (no errors reported) or
your submission will not be reviewed. Common reasons for failed
validation includes invalidly formatted JSON files and missing
mandatory fields. There will be a checklist that you are expected
to complete and attest to its accuracy. Once you submit your request,
your pull request will be reviewed by the directory maintainers. Changes
regarding the required criteria may be requested. If there are no
objections or changes requested, your specification will be
added after a minimum of 7 days and a maximum of 30 days.

## Adding Anything Else to this Registry

Use the standard fork, branch, and pull request workflow to propose changes to
the directory. Please make branch names informative—by including the issue or
bug number for example.

Editorial changes that improve the readability of the directory or correct
spelling or grammatical mistakes are welcome.

Non-editorial changes MUST go through a review and approval process that is
[detailed in the directory](https://w3c.github.io/vc-spec-directory/#the-management-process).

Please read [CONTRIBUTING.md](CONTRIBUTING.md), about licensing contributions.

## Code of Conduct

W3C functions under a [code of conduct](https://www.w3.org/Consortium/cepc/).

## VC Working Group Repositories

- [W3C VC Working Group](https://www.w3.org/groups/wg/vc)
- [W3C VC Use Cases](https://github.com/w3c/vc-use-cases)
- [W3C VC Data Model](https://github.com/w3c/vc-data-model)
