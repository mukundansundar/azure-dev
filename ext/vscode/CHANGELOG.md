# Release History

## 0.5.0 (2023-04-05)

### Features Added

- [[#1849]](https://github.com/Azure/azure-dev/pull/1849) Support for the `azd package` command has been added for both the entire application and individual services.

### Breaking Changes

- [[#1798]](https://github.com/Azure/azure-dev/pull/1798) Version 0.8.0 or higher of the Azure Developer CLI is now required. If an older version is installed, you will be prompted to update.
- [[#1658]](https://github.com/Azure/azure-dev/pull/1658) Version 1.76.0 or higher of VS Code is now required.

## 0.4.2 (2023-03-15)

### Bugs Fixed

- [[#1735]](https://github.com/Azure/azure-dev/pull/1735) Fixed an issue with the login command not working immediately after install.

## 0.4.1 (2023-03-14)

### Bugs Fixed

- [[#1724]](https://github.com/Azure/azure-dev/pull/1724) Refine conditions for displaying the prompt to install the CLI.

## 0.4.0 (2023-03-08)

### Added

- [[#853]](https://github.com/Azure/azure-dev/pull/853) Integration with the Azure Resources extension's workspace view. Requires version 0.6.1 of the [Azure Resources](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azureresourcegroups) extension.
- [[#1644]](https://github.com/Azure/azure-dev/pull/1644) Added a walkthrough experience for using the extension.

## 0.3.0 (2022-09-14)

### Added

- [[#493]](https://github.com/Azure/azure-dev/pull/493) Show README file after successful init/up.

### Fixed

- [[#498]](https://github.com/Azure/azure-dev/pull/498) Use `azd template list` to populate template list in VS Code (now always consistent with the CLI).
- [[#556]](https://github.com/Azure/azure-dev/pull/556) Improve error message when no environments are found.

## 0.2.0 (2022-08-02)

### Changed

- [[#189]](https://github.com/Azure/azure-dev/pull/189) Bump bicep minimum version to v0.8.9

### Added

- [[#151]](https://github.com/Azure/azure-dev/pull/151) Detect and warn the user if `azd` CLI is not installed.

### Fixed

- [[#159]](https://github.com/Azure/azure-dev/pull/159) Enable user feedback via surveys.
- [[#170]](https://github.com/Azure/azure-dev/pull/170) Enable gradual rollout of new features.

## 0.1.0 (2022-07-11)

- Initial release.
