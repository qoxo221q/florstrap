Download the [latest release of Florstrap](https://github.com/florstraplabs/florstrap/releases/latest), and run it. Configure your preferences if needed, and install. That's about it!

Alternatively, you can install Florstrap via [Winget](https://winstall.app/apps/pizzaboxer.Florstrap) by running this in a Command Prompt window:



You will also need the [.NET 6 Desktop Runtime](https://aka.ms/dotnet-core-applaunch?missing_runtime=true&arch=x64&rid=win11-x64&apphost_version=6.0.16&gui=true). If you don't already have it installed, you'll be prompted to install it anyway. Be sure to install Florstrap after you've installed this.

It's not unlikely that Windows Smartscreen will show a popup when you run Florstrap for the first time. This happens because it's an unknown program, not because it's actually detected as being malicious. To dismiss it, just click on "More info" and then "Run anyway".

Once installed, Florstrap is added to your Start Menu, where you can access the menu and reconfigure your preferences if needed.

## Code

Florstrap uses the [WPF UI](https://github.com/lepoco/wpfui) library for the user interface design. We currently use and maintain our own fork of WPF UI at [florstraplabs/wpfui](https://github.com/florstraplabs/wpfui).

[shield-repo-license]:  https://img.shields.io/github/license/florstraplabs/florstrap
[shield-repo-workflow]: https://img.shields.io/github/actions/workflow/status/florstraplabs/florstrap/ci-release.yml?branch=main&label=builds
[shield-repo-releases]: https://img.shields.io/github/downloads/florstraplabs/florstrap/latest/total?color=981bfe
[shield-repo-latest]:   https://img.shields.io/github/v/release/florstraplabs/florstrap?color=7a39fb

[shield-crowdin-status]: https://badges.crowdin.net/florstrap/localized.svg
