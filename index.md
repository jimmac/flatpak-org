---
layout: default
---
![Pixels](assets/flatpak.gif){:.full.pixels}


[Flatpak](https://github.com/flatpak/flatpak) is a next-generation technology for building and distributing desktop applications on Linux.

Flatpak changes app distribution for the better. Advantages include:

- **Built for every distro.** Create one app and distribute it to the entire Linux desktop market.
- **Stable platforms**. Runtimes provide platforms of common libraries that you can depend on.
- **Consistent environments**. Develop and test your application in an environment that’s identical to the one users have.
- **Full control over dependencies**. Flatpak makes it easy to bundle your own libraries as part of your app.
- **Easy build tools**. Flatpak’s build tools are simple and easy to use, and come with a [full set of documentation](https://docs.flatpak.org).
- **Future-proof builds**. Flatpak apps continue to be compatible with new versions of Linux distributions.

Learn how to [get started in 5 minutes](https://docs.flatpak.org/en/latest/getting-started.html), learn how to [distribute your app as a flatpak](https://docs.flatpak.org/en/latest/).


## Quick Setup

Most Linux distributions come with Flatpak enabled. To get started, all you need to do is enable *Flathub*, which is the best way to get Flatpak apps. Just download and install the [Flathub repository file](https://flathub.org/repo/flathub.flatpakrepo). 

Clicking on the above link should get you going in GNOME and KDE, but you can also enable Flathub manually in the terminal:

```
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```

### Specific Distro Instructions

- [Alpine](setup/alpine)
- [Arch](setup/arch)
- [Ataraxia Linux](setup/ataraxia)
- [CentOS](setup/centos)
- [Chrome OS](setup/chromeos)
- [Clear Linux](setup/clearlinux)
- [Debian](setup/debian)
- [Deepin](setup/deepin)
- [elementary OS](setup/elementary)
- [Endless OS](setup/endless)
- Fedora
- Future OS
- Gentoo
- Kubuntu
- Linux Mint
- Mageia
- Manjaro
- NixOS
- openSUSE
- Pardus
- Pisi GNU/Linux
- Pop!_OS
- PureOS
- Raspberry Pi OS
- Red Hat Enterprise Linux
- Solus
- SulinOS
- [Ubuntu](setup/ubuntu)
- Void Linux
- Zorin OS
{:.distros}

## Looking for Apps?

Regardless of what Linux distro you're using, head over to [Flathub](https://flathub.org) and install the newest apps for Linux!

## About Us

Flatpak is developed by an independent community, made up of contributors, volunteers and supporting organizations. It is a true upstream open source project, dedicated to providing technology and services that can be used by all, with no vendor lock-in. We have strong links to other Free Software projects, including the Freedesktop project.

All our code is freely available, with no contributor agreement required. Volunteers and contributing organizations are welcome, as equal partners. 

## Contact

| | |
--- | --- 
| Mailing list: | `flatpak@lists.freedesktop.org` |
| Private mailing list for security issues: | `flatpak-security@lists.freedesktop.org` |
| Matrix: | `#flatpak` on [Matrix.org](https://matrix.org) |
| GitHub: | [`github.com/flatpak`](https://github.com/flatpak) |
{:.moviecredits}

## See Also
- [Blog posts about Flatpak](blog-posts)
- [Press Information](press)
- [Flatpak History](history)


<!--
Written with love using [Apostrophe](https://flathub.org/apps/details/org.gnome.gitlab.somas.Apostrophe).
-->