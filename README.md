[![Discord Shield](https://discordapp.com/api/guilds/886961548105515068/widget.png?style=shield)](https://discord.gg/jzuXJxYaHW)

***Have ideas of features you would like to see in Cursr? [Let me know!](#support) Cursr development and priorities are driven by the needs of users!***

<img src="assets/github_banner.jpg" width="100%"/>

# Last update: 2025 Feb 20

> Please note that this repository does not contain source code for the project. Cursr is currently closed sourced and this public repository is simply used to distribute the production build files for users to download as well as provide a place to submit public issues, features and any other requests or discussions. A public repository was also created with plans to open source the free tier part of Cursr but that idea is on indefinite pause right now due to list of reasons and may or may not be resumed in later future.

# Info

Cursr is a cross-platform utility application for optimizing mouse movements between displays and multiple devices by creating custom links/portals between borders in a multiple display and device setups, but can also be useful to some with a single display setup. It was initially created to solve issue of related to using inputs like mouse across multiple displays, but now it also includes keyboard and clipboard sharing for multiple device users. Cursr was created because other existing solutions in the market did not work for me and there had to be more people that were also looking for better solution.

Cursr is created and developed by a single developer without any funding, therefore purchase of Cursr not only gives you access to advanced (Pro) features, but it also greatly supports the project and makes it sustainable for the developer to keep working on it, meaning you'll get updates with new features and any bugs/issues fixed. It's a mix of full and part time work, so your patience when waiting for a reply on any queries is appraciated.

Available on Windows, OSX and Linux*

<small style="opacity:0.5">* Linux tested on Ubuntu (Gnome and KDE), on other distributions or desktop environments it will default to Ubuntu Gnome behavior and will probably not work. If you would like to see support for other distribution or desktop environment please create Github issue. </small>

# Support

For support, feature requests and discussions you can
* [Open an issue](https://github.com/bitgapp/Cursr/issues/new/choose) in this repository
* Leave a message in [Cursr Discord](https://discord.gg/jzuXJxYaHW) server
* Send email to contact@cursr.app

# Features  

## Current

* Create links between borders to allow mouse to move between them to:
  * Move mouse proportionally between different resolution screens
  * Move mouse faster between displays that are further apart by creating a link between their borders, instead of moving mouse across all screens in between
* Split border into smaller segments
  * Allowing you to move from one border to 2 or more displays
  * Allowing to define 'blocking' segments which prevent mouse movement past certain border part
* Save setups for different display layouts and let Cursr auto-select best matching setup when application starts or layout changes
* Customize the UI by
  * Changing colors of linked borders and border segments
  * Changing color of rendered displays belonging to a specific device
* Software KVM - Connect multiple devices with Cursr to:
  * Share mouse, keyboard and clipboard between devices
  * Interchangeably use any connected mouse and keyboard on the go, no restricions for using only mouse/keyboard of 'main/server' device
* Setup keyboard shortcuts to
  * Quickly switch between setups
  * Control mouse

# Roadmap - What's next?

> The Roadmap migh be affected by any exiting or new issues/bugs if they will occur.

<small style="opacity:0.5">Ordered in aproximate priority:</small>

* Bug fixes currently affecting users
* File sharing between devices
* Mouse sensitivity control
* Improvements in user experience with setup editing/creation
* [cursr.app](cursr.app) site update/Potential rebranding
* Wayland support
* Performance improvements
* Improving Cursr discoverability and potentially marketing
* System for sharing and voting for setups to help users find setup/layout ideas

### Other

> Currently there are about 270+ tasks in backlog for Cursr, ranging anywhere from 10min to 100h+ (for more complex new feature ideas that I'm not ready to publish yet) for estimated completion time. The list below contains just a few generic examples that are more likely to be implemented.

* Draw overlay/preview of borders, segments and links over the top of whole screens
* Bug report form in App and in Website
* Make Cursr available on Mac App Store, Windows Store and Snap Store (Linux)
* Cloud sync
* Allow changing display layout from withing the app instead of having to open display settings of the operating system
* Rewrite Cursr from Electron to Tauri (or other alternative using Swift instead of Rust), this should provide a good performance boost and reduce the package size of Cursr
* Allow editing setups without them being active
* Add mouse (and keyboard?) drivers to Cursr
* Translate site and app to more languages


