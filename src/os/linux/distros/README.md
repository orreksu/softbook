# linux-distros
Compare Linux distributions

## Distros
### Arch-based
| Name         | Focus         | Base       | Package Format  | Package Manager | Updates | Kernel   | Init System              |
| ------------ | ------------- | ---------- | --------------- | --------------- | ------- | -------- | ------------------------ |
| Arch Linux   | minimal       |            | `bsdtar`        | pacman          | rolling | monolith | systemd                  |
| Manjaro      | friendly      | Arch Linux | `bsdtar`        | pacman          | rolling | monolith | systemd                  |
| EndeavourOS  | friendly      | Arch Linux | `bsdtar`        | pacman          | rolling | monolith | systemd                  |
| Garuda       | gaming        | Arch Linux | `bsdtar`        | pacman          | rolling | monolith | systemd                  |
| SteamOS      | gaming        | Arch Linux | `bsdtar`        | pacman          | rolling | monolith | systemd                  |
| Artix Linux  | not systemd   | Arch Linux | `bsdtar`        | pacman          | rolling | monolith | OpenRC, runit, s6, Dinit |
| BlackArch    | cybersecurity | Arch Linux | `bsdtar`        | pacman          | rolling | monolith | systemd                  |

### Debian-based
| Name          | Focus                | Base       | Package Format  | Package Manager | Updates | Kernel   | Init System              |
| ------------- | -------------------- | ---------- | --------------- | --------------- | ------- | -------- | ------------------------ |
| Debian        | stable               |            | `.deb`          | apt, dpkg       | lts     | monolith | systemd                  |
| Ubuntu        | commercial, friendly | Debian     | `.deb`          | apt, dpkg       | lts     | monolith | systemd                  |
| Linux Mint    | friendly             | Ubuntu     | `.deb`          | apt, dpkg       | lts     | monolith | systemd                  |
| Pop!\_OS      | friendly             | Ubuntu     | `.deb`          | apt, dpkg       | lts     | monolith | systemd                  |
| Zorin OS      | friendly             | Ubuntu     | `.deb`          | apt, dpkg       | lts     | monolith | systemd                  |
| elementary OS | be like macos        | Ubuntu     | `.deb`          | apt, dpkg       | lts     | monolith | systemd                  |
| Kali Linux    | cybersecurity        | Debian     | `.deb`          | apt, dpkg       | rolling | monolith | systemd                  |
| antiX         | lightweight          | Debian     | `.deb`          | apt, dpkg       | lts     | monolith | systemd                  |
| MX Linux      | efficient, friendly  | antiX      | `.deb`          | apt, dpkg       | lts     | monolith | systemd                  |

### RPM-based
| Name                | Focus           | Base          | Package Format  | Package Manager | Updates | Kernel   | Init System              |
| ------------------- | --------------- | ------------- | --------------- | --------------- | ------- | -------- | ------------------------ |
| Fedora Linux        | innovative      |               | `.rpm`          | dnf, rpm        | lts     | monolith | systemd                  |
| Fedora Silverblue   | immutable       | Fedora Linux  | `.rpm`          | rpm-ostree, rpm | lts     | monolith | systemd                  |
| CentOS Stream       | innovative      | Fedora Linux  | `.rpm`          | dnf, yum, rpm   | lts     | monolith | systemd                  |
| RHEL                | commercial      | CentOS Stream | `.rpm`          | dnf, yum, rpm   | lts     | monolith | systemd                  |
| openSUSE Tumbleweed | libre, friendly |               | `.rpm`          | YaST, rpm       | rolling | monolith | systemd                  |
| openSUSE Leap       | libre, stable   |               | `.rpm`          | YaST, rpm       | lts     | monolith | systemd                  |

### Various
| Name          | Focus         | Base       | Package Format  | Package Manager       | Updates | Kernel   | Init System                          |
| ------------- | ------------- | ---------- | --------------- | --------------------- | ------- | -------- | ------------------------------------ |
| Gentoo Linux  | adaptable     |            | source-based    | portage               | rolling | monolith | OpenRc, runit, s6, sysvinit, systemd |
| Slackware     | adaptable     |            |                 | pkgtools, slackpkg    | rolling | monolith | custom                               |
| Void Linux    |               |            |                 |                       |         |          |                                      |
| Solus         | personal      |            |                 | eopkg                 | rolling | monolith | systemd                              |
| Puppy Linux   | lightweight   |            | PET             | Puppy Package Manager | lts     | monolith | Busybox init                         |
| Alpine Linux  | secure        |            |                 | apk-tools             |         |          | OpenRc                               |
| NixOS         | reproducible  |            | source-based    | nix                   |         |          |                                      |
| QubesOS       | secure        |            |                 | yum                   |         | micro    |                                      |
| Bedrock Linux | combine       |            |                 |                       |         |          |                                      |


## Shell
| Name    | ... |
| ------- | --- |
| sh      |     |
| bash    |     |
| zsh     |     |
| ash     |     |
| fish    |     |

## Standard Utilities
| Name    | ... |
| ------- | --- |
| glibc   |     |
| BusyBox |     |


## C standart library (libc)
| Name    | Language |
| ------- | -------- |
| glibc   | C        |
| musl    | C        |
| uClibc  | C        |
| relibc  | Rust     |


## Init Systems
| Name    | ... |
| ------- | --- |
| systemd |     |
| OpenRC  |     |
| runit   |     |
| s6      |     |
| Dinit   |     |


## Version Control System
| Name                        | Language |
| --------------------------- | -------- |
| [git](https://git-scm.com/) | C        |
| [Pijul](https://pijul.org/) | Rust     |


## Compositor
| Name    | ... |
| ------- | --- |
| X11     |     |
| Wayland |     |

## Desktop Envirnemnets (DE)
| Name       | ... |
| ---------- | --- |
| Gnome      |     |
| KDE Plazma |     |
| Budgie     |     |
| MATE       |     |
| i3         |     |
