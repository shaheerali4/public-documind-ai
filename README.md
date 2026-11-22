# DocuMind AI — Public Showcase

This repository is the public-facing companion for **DocuMind AI**. It provides a safe overview and non-sensitive example configuration while the production source code remains private.

## Repository contents

| File | Purpose |
| --- | --- |
| `README.md` | Explains the scope and safe use of this public repository. |
| `project-links.md` | Records public project and deployment links as they become available. |
| `sample-config.json` | Demonstrates a deliberately restricted, credential-free demo configuration. |

## Demo configuration

`sample-config.json` is illustrative only:

- `mode` is set to `demo`.
- `documentStorage` is disabled.
- `credentialsIncluded` is `false`.
- `note` identifies the file as an example rather than production configuration.

Do not add API keys, tokens, private document URLs, customer data, or production settings to this repository. Keep real secrets in an approved secret manager and production configuration in the private source repository.

## Using this repository

Use this repository to:

- understand what public DocuMind AI material is available;
- review the shape of the safe demo configuration;
- propose corrections or improvements to public documentation;
- track public links without exposing implementation details.

This repository is not a runnable distribution of DocuMind AI and does not contain the production application.

## Contributing

Open an issue or pull request for public documentation corrections, safer examples, or missing public links. Avoid including confidential implementation details, credentials, or sensitive documents.

See [project-links.md](project-links.md) for the current public-link status.
