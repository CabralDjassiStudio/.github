# Installation Guide

This package is prepared for:

```text
cabraldjassistudio/.github
```

## Repository requirements

The repository must:

- belong to the `cabraldjassistudio` organization;
- be named exactly `.github`;
- be public to display the organization profile and supply default community files.

## Installation

1. Extract the ZIP.
2. Open the extracted `cabraldjassistudio-dotgithub-*` folder.
3. Copy all its contents to the root of the `.github` repository.
4. Commit and push:

```bash
git add .
git commit -m "docs: establish organization profile and community standards"
git push origin main
```

## Expected structure

```text
.github/
├── README.md
├── LICENSE
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── SUPPORT.md
├── GOVERNANCE.md
├── LICENSING_POLICY.md
├── BRAND_POLICY.md
├── INSTALLATION.md
├── FILE_MANIFEST.md
├── profile/
│   ├── README.md
│   ├── README.pt.md
│   ├── README.fr.md
│   └── README.cv.md
└── .github/
    ├── PULL_REQUEST_TEMPLATE.md
    └── ISSUE_TEMPLATE/
        ├── bug_report.yml
        ├── feature_request.yml
        ├── documentation.yml
        └── config.yml
```

## Verification

Confirm that:

1. `https://github.com/cabraldjassistudio` displays `profile/README.md`.
2. The `.github` repository shows README, code of conduct, contributing, license, and security shortcuts.
3. Issue forms are available.
4. EN/PT/FR/CV profile links work in both directions.
5. The English profile remains the GitHub organization default and the translated profiles remain semantically aligned with it.
6. The Security tab displays the policy.

## License limitation

The included `LICENSE` applies only to this `.github` repository. Every product repository needs its own license according to `LICENSING_POLICY.md`.

## Recommended settings

- protect the default branch;
- require pull requests for policy changes;
- require review for security, licensing, governance, and brand changes;
- block force pushes and branch deletion;
- enable secret scanning and push protection when available;
- restrict repository visibility changes.

## Before publication

Review the website URL, copyright year, future private security contact, organization owner settings, and consistency between all profile language versions.

The legal documents are practical templates and are not jurisdiction-specific legal advice.
