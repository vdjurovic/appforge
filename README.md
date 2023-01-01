# AppForge

AppForge is a complete solution for automated deployment and updating of multi-platform applications. It provides easy-to-use
tools which enable developers to rapidly deploy applications without having to worry about details such as installers, platform integration,
user experience and so on.

AppForge automatically generates native installers for all supported operating systems and CPU architectures. User experience is the 
same as for any native application. 

In addition to installers, AppForge enables auto-update of installed applications without any user intervention. Your applications will
always run latest version. All  that users need is internet connection.

AppForge consists of te following components:

* [Backstage](https://github.com/bitshifted/backstage) - server-side application which generates installers and serves updates. 
* [Ignite Maven plugin](https://github.com/bitshifted/ignite-maven-plugin) - a Maven plugin used in development stage to generate deployment packages
* [Ignite](https://github.com/bitshifted/ignite) - GUI tool for generating deployment configuration files
* [Launchcode](https://github.com/bitshifted/launchcode) - native launcher for applications
* [Syncro](https://github.com/bitshifted/syncro) - library which performs updates of applications

For more detailed information about specific components, please visit component repositories.

# License

AppForge is open source software released under Mozilla Public License 2.0. Please see the [License](./LICENSE) file for details. 
All components are also released under this license.

# Supported platforms and languages

AppForge currently supports Java desktop applications, including Swing and JavaFX. Applications can be deployed to:

* Windows x64, as .exe installers
* Mac OS X, both x64 and aarch64, as .dmg packaged application bundles
* Linux, both x64 and aarch64, as .deb, .rpm and .tar.gz packages

# Contributing

## Reporting issues

All issues related to any component should be reported [in this repository](https://github.com/bitshifted/appforge/issues), not in 
component repositories. This allows for easier tracking of issues.

Please make sure to correctly label the issue, so it is easier to filter.
