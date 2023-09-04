---
description: List of changes to the PowerShell documentation for 2022
ms.date: 07/05/2022
title: What's New in PowerShell-Docs for 2022
---
# What's new in PowerShell Docs for 2022

This article lists some of the major changes to docs during this previous month and celebrates the
contributions from the community.

Help us make the documentation better for you. Read the [Contributor's Guide][contrib] to learn how
to get started.

## 2022-June

New content migrated from GitHub wiki

- [Limitations of PowerShell transcripts](/powershell/scripting/learn/deep-dives/output-missing-from-transcript)
- [Avoid using Invoke-Expression](/powershell/scripting/learn/deep-dives/avoid-using-invoke-expression)
- [Avoid assigning variables in expressions](/powershell/scripting/learn/deep-dives/avoid-assigning-variables-in-expressions)
- [about_Case-Sensitivity]( /powershell/module/microsoft.powershell.core/about/about_case-sensitivity)
- Updated [about_Arrays](/powershell/module/microsoft.powershell.core/about/about_arrays)

New SecretManagement content

- [Understanding the security features of SecretManagement and SecretStore](/powershell/utility-modules/secretmanagement/security-concepts)
- [Using the SecretStore in automation](/powershell/utility-modules/secretmanagement/how-to/using-secrets-in-automation)
- [Using Azure Key Vault in automation](/powershell/utility-modules/secretmanagement/how-to/using-azure-keyvault)

Content updates

- Updated release notes for 7.3-preview.5 and PSReadLine 2.2.6

### Top Community Contributors

GitHub stats

- 44 PRs merged (8 from Community)
- 23 issues opened (14 from Community)
- 23 issues closed (13 Community issues closed)

The following people have contributed to PowerShell docs by submitting pull requests or filing
issues. Thank you!

| GitHub Id  | PRs merged | Issues opened |
| ---------- | :--------: | :-----------: |
| mcdonaldjc |     2      |       1       |
| radrow     |     1      |               |
| yecril71pl |     1      |               |
| muhahaaa   |     1      |               |
| windin7cc  |     1      |               |
| fabiod89   |     1      |               |
| NaridaL    |     1      |               |

## 2022-May

New content

- [Create a Crescendo configuration using the Crescendo cmdlets](/powershell/utility-modules/crescendo/advanced/using-crescendo-cmdlets)
- [Overview of the SecretManagement and SecretStore modules](/powershell/utility-modules/secretmanagement/overview)
- [Get started with the SecretStore module](/powershell/utility-modules/secretmanagement/get-started/using-secretstore)
- [Understanding the SecretManagement module](/powershell/utility-modules/secretmanagement/get-started/understanding-secretmanagement)
- [Managing a SecretStore vault](/powershell/utility-modules/secretmanagement/how-to/manage-secretstore)

Content updates

- Renamed the `staging` branch to `main`
- Updated the Table of Contents for easier discovery
  - Moved Support Lifecycle to the top level
  - Moved Contributor Guide to the top level
- 7.3-preview.4 release notes
- Bulk formatting cleanup for many docs
  - PowerShell-Docs content - 272 files
  - Secrets management - 17 files
- Updated the PSScriptAnalyzer README and deleted docs that were migrated to docs.microsoft.com
- Removed CentOS and Fedora from docs - no longer supported
- Retired 7.1 content - no longer supported
  - Collapse release notes into diff article
  - Delete or move content to archive repo

### Top Community Contributors

GitHub stats

- 53 PRs merged (12 from Community)
- 38 issues opened (21 from Community)
- 39 issues closed (26 Community issues closed)

The following people have contributed to PowerShell docs by submitting pull requests or filing
issues. Thank you!

|    GitHub Id     | PRs merged | Issues opened |
| ---------------- | :--------: | :-----------: |
| tommymaynard     |     5      |               |
| naveensrinivasan |     2      |               |
| rikurauhala      |     1      |               |
| joshua6point0    |     1      |               |
| rhorber          |     1      |               |
| Raton-Laveur     |     1      |               |
| StephenRoille    |     1      |               |
| krlinus          |            |       2       |

## 2022-April

New content

- No new content this month

Content updates

- Rewrote the install instructions for [PowerShellGet](/powershell/scripting/gallery/installing-psget)
- Created separate article for
  [Installing PowerShellGet on older Windows systems](/powershell/scripting/gallery/install-on-older-systems)

Other projects

- PowerShell + DevOps Summit April 25-28
  - Gave presentation about contributing to Docs
  - Lightning demo about argument completers
  - Interview for the [PowerShell Podcast](https://powershellpodcast.podbean.com/e/contributing-to-powershell-made-easy-with-sean-wheeler/)

### Top Community Contributors

GitHub stats

- 24 PRs merged (3 from Community)
- 22 issues opened (17 from Community)
- 21 issues closed (15 Community issues closed)

The following people have contributed to PowerShell docs by submitting pull requests or filing
issues. Thank you!

|   GitHub Id    | PRs merged | Issues opened |
| -------------- | :--------: | :-----------: |
| Hrxn           |     1      |               |
| kevinholtkamp  |     1      |               |
| MikeyBronowski |     1      |               |
| tommymaynard   |            |       4       |

## 2022-March

New Content

- New PowerShell docs
  - [about_Member-Access_Enumeration](/powershell/module/microsoft.powershell.core/about/about_member-access_enumeration)
  - [about_Module_Manifests](/powershell/module/microsoft.powershell.core/about/about_module_manifests)
  - [How to create a command-line predictor](/powershell/scripting/dev-cross-plat/create-cmdline-predictor)
- Utility modules updates
  - New docs for Crescendo release
    - [Install Crescendo](/powershell/utility-modules/crescendo/get-started/install-crescendo)
    - [Choose a command-line tool](/powershell/utility-modules/crescendo/get-started/choose-command-line-tool)
    - [Decide which features to amplify](/powershell/utility-modules/crescendo/get-started/research-tool)
    - [Create a Crescendo cmdlet](/powershell/utility-modules/crescendo/get-started/create-new-cmdlet)
    - [Generate and test a Crescendo module](/powershell/utility-modules/crescendo/get-started/generate-module)
    - We have plans for at least two more documents
  - Moved PlatyPS article from PowerShell docs to the PlatyPS documentation
    - [Moved PlatyPS article](/powershell/utility-modules/platyps/create-help-using-platyps)
  - Migrated more PSScriptAnalyzer documentation from the source code repository
    - [Using PSScriptAnalyzer](/powershell/utility-modules/psscriptanalyzer/using-scriptanalyzer)
    - [Rules and recommendations](/powershell/utility-modules/psscriptanalyzer/rules-recommendations)
    - [Creating custom rules](/powershell/utility-modules/psscriptanalyzer/create-custom-rule)

Content updates

- Bulk cleanup of related links in About_ topics
- Added issue and PR templates to all docs repos
- Updates for 7.3 preview content
  - New tab completions
  - Support for SSH options on remoting cmdlets
  - New experimental feature `PSAMSIMethodInvocationLogging`

Other projects

- Created a prototype cmdlet `Get-WhatsNew` based on the
  [draft RFC](https://github.com/PowerShell/PowerShell-RFC/pull/317)
  - Check out the RFC and provide feedback

New team member

- Welcome [Mikey Lombardi](https://github.com/michaeltlombardi) to the docs team

### Top Community Contributors

GitHub stats

- 49 PRs merged (8 from Community)
- 26 issues opened (14 from Community)
- 33 issues closed (18 Community issues closed)

The following people have contributed to PowerShell docs by submitting pull requests or filing
issues. Thank you!

|   GitHub Id    | PRs merged | Issues opened |
| -------------- | :--------: | :-----------: |
| AspenForester  |     1      |               |
| codaamok       |     1      |               |
| DianaKuzmenko  |     1      |               |
| MikeyBronowski |     1      |               |
| poshdude       |     1      |               |
| robcmo         |     1      |               |
| sertdfyguhi    |     1      |               |
| stampycode     |     1      |               |

## 2022-February

New Content

- [about_Calling_Generic_Methods](/powershell/module/microsoft.powershell.core/about/about_calling_generic_methods&preserve-view=true)

Content updates

- Catching up on issues
- Updates for 7.3 preview content

### Top Community Contributors

GitHub stats

- 22 PRs merged (3 from Community)
- 24 issues opened (19 from Community)
- 18 issues closed (16 Community issues closed)

The following people have contributed to PowerShell docs by submitting pull requests or filing
issues. Thank you!

|    GitHub Id    | PRs merged | Issues opened |
| --------------- | :--------: | :-----------: |
| sethvs          |     2      |               |
| guilhermgonzaga |     1      |               |

## 2022-January

New Content

- No new content. We are down to one writer for PowerShell. I was out of the office for half of
  December for vacation then half of January for COVID.

Content updates

- Catching up on issues
- Updates for 7.3 preview content

### Top Community Contributors

GitHub stats

- 51 PRs merged (10 from Community)
- 29 issues opened (26 from Community)
- 46 issues closed (39 Community issues closed)

The following people have contributed to PowerShell docs by submitting pull requests or filing
issues. Thank you!

|    GitHub Id    | PRs merged | Issues opened |
| --------------- | :--------: | :-----------: |
| sethvs          |     3      |               |
| UberKluger      |     1      |               |
| MiguelDomingues |     1      |               |
| reZach          |     1      |               |
| Hertz-Hu        |     1      |               |
| julian-hansen   |     1      |               |
| Hrxn            |     1      |               |
| peteraritchie   |     1      |               |

<!-- Link references -->
[contrib]: contributing/overview.md