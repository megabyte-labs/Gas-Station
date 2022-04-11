<!-- ⚠️ This README has been generated from the file(s) ".config/docs/blueprint-readme-playbook.md" ⚠️--><div align="center">
  <center>
    <a href="https://github.com/megabyte-labs/Gas-Station">
      <img width="148" height="148" alt="Gas Station logo" src="https://gitlab.com/megabyte-labs/gas-station/-/raw/master/logo.png" />
    </a>
  </center>
</div>
<div align="center">
  <center><h1 align="center">Ansible Playbook: Gas Station ⛽<i></i></h1></center>
  <center><h4 style="color: #18c3d1;">Brought to you by <a href="https://megabyte.space" target="_blank">Megabyte Labs</a></h4><i></i></center>
</div>

<div align="center">
  <a href="https://megabyte.space" title="Megabyte Labs homepage" target="_blank">
    <img alt="Homepage" src="https://img.shields.io/website?down_color=%23FF4136&down_message=Down&label=Homepage&logo=home-assistant&logoColor=white&up_color=%232ECC40&up_message=Up&url=https%3A%2F%2Fmegabyte.space&style=for-the-badge" />
  </a>
  <a href="https://github.com/megabyte-labs/Gas-Station/blob/master/docs/CONTRIBUTING.md" title="Learn about contributing" target="_blank">
    <img alt="Contributing" src="https://img.shields.io/badge/Contributing-Guide-0074D9?logo=github-sponsors&logoColor=white&style=for-the-badge" />
  </a>
  <a href="https://app.slack.com/client/T01ABCG4NK1/C01NN74H0LW/details/" title="Chat with us on Slack" target="_blank">
    <img alt="Slack" src="https://img.shields.io/badge/Slack-Chat-e01e5a?logo=slack&logoColor=white&style=for-the-badge" />
  </a>
  <a href="link.gitter" title="Chat with the community on Gitter" target="_blank">
    <img alt="Gitter" src="https://img.shields.io/gitter/room/megabyte-labs/community?logo=gitter&logoColor=white&style=for-the-badge" />
  </a>
  <a href="https://github.com/megabyte-labs/Gas-Station" title="GitHub mirror" target="_blank">
    <img alt="GitHub" src="https://img.shields.io/badge/Mirror-GitHub-333333?logo=github&style=for-the-badge" />
  </a>
  <a href="https://gitlab.com/megabyte-labs/gas-station" title="GitLab repository" target="_blank">
    <img alt="GitLab" src="https://img.shields.io/badge/Repo-GitLab-fc6d26?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgAQMAAABJtOi3AAAABlBMVEUAAAD///+l2Z/dAAAAAXRSTlMAQObYZgAAAHJJREFUCNdNxKENwzAQQNEfWU1ZPUF1cxR5lYxQqQMkLEsUdIxCM7PMkMgLGB6wopxkYvAeI0xdHkqXgCLL0Beiqy2CmUIdeYs+WioqVF9C6/RlZvblRNZD8etRuKe843KKkBPw2azX13r+rdvPctEaFi4NVzAN2FhJMQAAAABJRU5ErkJggg==&style=for-the-badge" />
  </a>
</div>
<br/>
<div align="center">
  <a title="Version: 2.1.0" href="https://github.com/megabyte-labs/Gas-Station" target="_blank">
    <img alt="Version: 2.1.0" src="https://img.shields.io/badge/version-2.1.0-blue.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgAQMAAABJtOi3AAAABlBMVEUAAAD///+l2Z/dAAAAAXRSTlMAQObYZgAAACNJREFUCNdjIACY//+BEp9hhM3hAzYQwoBIAqEDYQrCZLwAAGlFKxU1nF9cAAAAAElFTkSuQmCC&cacheSeconds=2592000&style=flat-square" />
  </a>
  <a title="Build status" href="https://gitlab.com/megabyte-labs/gas-station/-/commits/master" target="_blank">
    <img alt="Build status" src="https://img.shields.io/gitlab/pipeline-status/megabyte-labs/gas-station?branch=master&label=build&logo=gitlab&style=flat-square">
  </a>
  <a title="E2E test status for all operating systems" href="https://gitlab.com/megabyte-labs/gas-station/-/commits/e2e" target="_blank">
    <img alt="E2E test status" src="https://img.shields.io/gitlab/pipeline-status/megabyte-labs/gas-station?branch=e2e&label=e2e%20test&logo=virtualbox&style=flat-square">
  </a>
  <a title="Documentation" href="https://megabyte.space/docs/ansible" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg?logo=readthedocs&style=flat-square" />
  </a>
  <a title="License: MIT" href="https://github.com/megabyte-labs/Gas-Station/blob/master/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-yellow.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgAQMAAABJtOi3AAAABlBMVEUAAAD///+l2Z/dAAAAAXRSTlMAQObYZgAAAHpJREFUCNdjYOD/wMDAUP+PgYHxhzwDA/MB5gMM7AwMDxj4GBgKGGQYGCyAEEgbMDDwAAWAwmk8958xpIOI5zKH2RmOyhxmZjguAiKmgIgtQOIYmFgCIp4AlaQ9OczGkJYCJEAGgI0CGwo2HmwR2Eqw5SBnNIAdBHYaAJb6KLM15W/CAAAAAElFTkSuQmCC&style=flat-square" />
  </a>
</div>

> <br/><h4 align="center">**A no-stone-unturned Ansible playbook you can use to set up the ultimate home lab or on-premise addition to your cloud!**</h4><br/><br/>

<a href="#table-of-contents" style="width:100%"><img style="width:100%" src="https://gitlab.com/megabyte-labs/assets/-/raw/master/png/aqua-divider.png" /></a>

## Table of Contents

- [Introduction](#introduction)
- [Quick Start](#quick-start)
  - [Vagrant (Recommended)](#vagrant-recommended)
  - [macOS/Linux](#macoslinux)
  - [Windows](#windows)
- [Supported Operating Systems](#supported-operating-systems)
- [Requirements](#requirements)
  - [Host Requirements](#host-requirements)
    - [Easier Method of Installing the Host Requirements](#easier-method-of-installing-the-host-requirements)
  - [Operating System](#operating-system)
  - [Connection](#connection)
  - [MAS on Mac OS X](#mas-on-mac-os-x)
- [Software](#software)
  - [Binaries](#binaries)
  - [NPM Packages](#npm-packages)
  - [Python Packages](#python-packages)
  - [Ruby Gems](#ruby-gems)
  - [Visual Studio Code Extensions](#visual-studio-code-extensions)
  - [Chrome Extensions](#chrome-extensions)
  - [Homebrew Formulae (macOS and Linux only)](#homebrew-formulae-macos-and-linux-only)
  - [Homebrew Casks (macOS only)](#homebrew-casks-macos-only)
  - [Go, Rust, and System-Specific Packages](#go-rust-and-system-specific-packages)
- [Web Applications](#web-applications)
  - [Helm Charts](#helm-charts)
  - [Host Applications](#host-applications)
    - [HTPC](#htpc)
- [Philosophy](#philosophy)
- [Architecture](#architecture)
- [Managing Environments](#managing-environments)
  - [Switching Between Environments](#switching-between-environments)
- [Contributing](#contributing)
- [License](#license)

<a href="#introduction" style="width:100%"><img style="width:100%" src="https://gitlab.com/megabyte-labs/assets/-/raw/master/png/aqua-divider.png" /></a>

## Introduction

Welcome to a new way of doing things. Born out of complete paranoia and a relentless pursuit of the best of GitHub Awesome lists, Gas Station aims to add the capability of being able to completely wipe whole networks and restore them on a regular basis. It takes a unique approach to network provisioning because it supports desktop provisioning as a first-class citizen. By default, without much configuration, it is meant to provision and maintain the state of a network that includes development workstations and servers. One type of user that might benefit from this project is a web developer who wants to start saving the state of their desktop as code. Another type of user is one who wants to start hosting RAM-intensive web applications in their home-lab environment to save huge amounts on cloud costs. This project is also meant to be maintainable by a single person. Granted, if you look through our eco-system you will see we are well-equipped for supporting entire teams as well.

Gas Station a collection of Ansible playbooks, configurations, scripts, and roles meant to provision computers and networks with the "best of GitHub". By leveraging Ansible, you can provision your whole network relatively fast in the event of a disaster or scheduled network reset. This project is also intended to increase the security of your network by allowing you to frequently wipe, reinstall, and re-provision your network, bringing it back to its original state. This is done by backing up container storage volumes (like database files and Docker volumes) to encrypted S3 buckets, storing configurations in encrypted git repositories, and leveraging GitHub-sourced power tools to make the job easy-peasy.

This project started when a certain somebody changed their desktop wallpaper to an _cute_ picture of a cat 🐱 when, all of a sudden, their computer meowed. Well, it actually started before that but no one believes someone who claims that time travelers hacked them on a regular basis. _Tip: If you are stuck in spiritual darkness involving time travelers, save yourself some headaches by adopting an other-people first mentality that may include volunteering, tithing, and surrendering to Jesus Christ._ Anyway, enough preaching!

Gas Station is:

- Highly configurable - most roles come with optional variables that you can configure to change the behavior of the role
- Highly configured - in-depth research is done to ensure each software component is configured with bash completions, plugins that are well-received by the community, and integrated with other software used in the playbook
- Compatible with all major operating systems (i.e. Windows, Mac OS X, Ubuntu, Fedora, CentOS, Debian, and even Archlinux)
- The product of a team of experts
- An amazing way to learn about developer tools that many would consider to be "the best of GitHub"
- Open to new ideas - feel free to [open an issue](https://gitlab.com/megabyte-labs/gas-station/-/issues) or [contribute](https://github.com/megabyte-labs/Gas-Station/blob/master/docs/CONTRIBUTING.md) with a [pull request](https://github.com/megabyte-labs/Gas-Station/issues)!

<a href="#quick-start" style="width:100%"><img style="width:100%" src="https://gitlab.com/megabyte-labs/assets/-/raw/master/png/aqua-divider.png" /></a>

## Quick Start

The easiest way to run the entire playbook, outlined in the `main.yml` file, is to run the appropriate command listed below. These commands will run the playbook on the machine you run the command on. This is probably the best way to get your feet wet before you decide to give us a ⭐ and customize the playbook for your own needs. Ideally, this command should be run on the machine that you plan on running Ansible with to provision the other computers on your network. It is only guaranteed to work on fresh installs so testing it out with [Vagrant](https://www.vagrantup.com/) is highly encouraged.

### Vagrant (Recommended)

To test it out with Vagrant, you can run the following commands which will open up an interactive dialog where you can pick which operating system and virtualization provider you wish to test the installation with:

```shell
bash start.sh # Only required if you do not have the dependencies (i.e. Task) already installed
task ansible:test:vagrant
```

### macOS/Linux

```shell
curl -sSL https://gitlab.com/megabyte-labs/gas-station/-/raw/master/scripts/quickstart.sh | bash
```

### Windows

In an administrative PowerShell session, run:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://gitlab.com/megabyte-labs/gas-station/-/raw/master/files/quickstart.ps1'))
```

<a href="#supported-operating-systems" style="width:100%"><img style="width:100%" src="https://gitlab.com/megabyte-labs/assets/-/raw/master/png/aqua-divider.png" /></a>

## Supported Operating Systems

The following chart shows the operating systems that have been tested for compatibility using the `environments/dev/` environment. This chart is automatically generated using the Ansible Molecule tests you can view in the `molecule/default/` folder. We currently have logic in place to automatically handle the testing of Windows, Mac OS X, Ubuntu, Fedora, CentOS, Debian, and Archlinux. If your operating system is not listed but is a variant of one of the systems we test (i.e. a Debian-flavored system or a RedHat-flavored system) then it might still work.

compatibility_matrix

<a href="#requirements" style="width:100%"><img style="width:100%" src="https://gitlab.com/megabyte-labs/assets/-/raw/master/png/aqua-divider.png" /></a>

## Requirements

- **[Python >=3.7](https://www.python.org/)**
- **[Ansible >=2.9](https://www.ansible.com/)**
- Ansible controller should be a macOS/Linux environment (WSL/Docker can be used on Windows)

### Host Requirements

There are Python and Ansible package requirements need to be installed by running the following command (or equivalent) in the root of this repository:

```
if type poetry &> /dev/null; then poetry install --no-root; else pip3 install -r .config/requirements.txt; fi
ansible-galaxy install requirements.yml
```

#### Easier Method of Installing the Host Requirements

You can also run `bash .config/scripts/start.sh` if you do not mind development dependencies being installed as well. This method will even handle installing Python 3 and Ansible.

### Operating System

**This playbook is built and tested to run on fresh installs of Windows, Mac OS X, Ubuntu, Fedora, Debian, CentOS, and Archlinux**. It may still be possible to run the playbook on your current machine. However, installing the playbook on a fresh install is the only thing we actively support. That said, if you come across an issue with an environment that already has configurations and software present, please do not hesitate to [open an issue](https://gitlab.com/megabyte-labs/gas-stationrepository.location.issue.gitlab).

### Connection

SSH (or WinRM in the case of Windows) and Python should be available on the target systems you would like to provision. If you are attempting to provision a Windows machine, you can ensure that WinRM is enabled and configured so that you can remotely provision the Windows target by running the following command with PowerShell:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://gitlab.com/megabyte-labs/gas-station/-/raw/master/files/client.ps1'))
```

### MAS on Mac OS X

We use [mas](https://github.com/mas-cli/mas) to install apps from the App Store in some of our roles. Sadly, automatically signing into the App Store is not possible on OS X 10.13+ via mas. This is because [mas no longer supports login functionality on OS X 10.13+](https://github.com/mas-cli/mas/issues/164).

There is another caveat with mas. In order to install an application using mas, the application has to have already been added via the App Store GUI. This means that the first time around you will have to install the apps via the App Store GUI so they are associated with your App Store account.

<a href="#software" style="width:100%"><img style="width:100%" src="https://gitlab.com/megabyte-labs/assets/-/raw/master/png/aqua-divider.png" /></a>

## Software

This project breaks down software into a role (found in the subdirectories of the `roles/` folder) if the software requires anything other than being added to the `PATH` variable. Below is a quick description of what each role does. Browsing through this list, along with the conditions laid out in `main.yml`, you will be able to get a better picture of what software will be installed by the default `main.yml` playbook.

role_descriptions

We encourage you to browse through the repositories that are linked to in the table above to learn about the configuration options they support.

### Binaries

A lot of nifty software does not require any configuration other than being added to the `PATH` or being installed with an installer like `brew`. For this kind of software that requires no configuration, we list the software we would like installed by the playbook as a variable in `group_vars/` or `host_vars/` as an array of keys assigned to the `software` variable ([example here](environments/prod/group_vars/desktop/vars.yml)). With those keys, we install the software using the `[professormanhattan.genericinstaller](https://galaxy.ansible.com/professormanhattan/genericinstaller)` role which determines how to install the binaries by looking up the keys against the `software_package` object ([example here](environments/prod/group_vars/all/software.yml)). For your convienience, the software we recommend and install by default is listed below:

| Package                                                                                      | Description                                                                                                                                       |
| -------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[act](https://github.com/nektos/act)**                                                     | To run Github Actions locally                                                                                                                     |
| **[altair](https://github.com/altair-graphql/altair)**                                       | A beautiful feature-rich GraphQL Client for all platforms                                                                                         |
| **[askgit](https://github.com/askgitdev/askgit)**                                            | Query git repositories with SQL. Generate reports, perform status checks, analyze codebases                                                       |
| **[bandwhich](https://github.com/imsnif/bandwhich)**                                         | Terminal bandwidth utilization tool                                                                                                               |
| **[bane](https://github.com/genuinetools/bane)**                                             | Custom & better AppArmor profile generator for Docker containers                                                                                  |
| **[bat](https://github.com/sharkdp/bat)**                                                    | Clone of cat(1) with syntax highlighting and Git integration                                                                                      |
| **[betwixt](https://github.com/kdzwinel/betwixt)**                                           | Web Debugging Proxy based on Chrome DevTools Network panel                                                                                        |
| **[bin](https://github.com/marcosnils/bin)**                                                 | Effortless binary manager                                                                                                                         |
| **[bitwarden](https://github.com/bitwarden/desktop)**                                        | The desktop vault (Windows, macOS, & Linux)                                                                                                       |
| **[bivac](https://github.com/camptocamp/bivac)**                                             | Backup Interface for Volumes Attached to Containers                                                                                               |
| **[boilr](https://github.com/tmrts/boilr)**                                                  | boilerplate template manager that generates files or directories from template repositories                                                       |
| **[captain](https://github.com/jenssegers/captain)**                                         | Helps manage docker-compose.yml files from anywhere in the file system                                                                            |
| **[cerebro](https://github.com/cerebroapp/cerebro)**                                         | Open-source productivity booster with a brain                                                                                                     |
| **[clair](https://github.com/quay/clair)**                                                   | Vulnerability Static Analysis for Containers                                                                                                      |
| **[consul-cli](https://github.com/mantl/consul-cli)**                                        | Command line interface to Consul HTTP API                                                                                                         |
| **[croc](https://github.com/schollz/croc)**                                                  | Easily and securely send things from one computer to another                                                                                      |
| **[ctop](https://github.com/bcicen/ctop)**                                                   | Top-like interface for container metrics                                                                                                          |
| **[cumulus](https://github.com/gillesdemey/Cumulus)**                                        | A SoundCloud player that lives in the menubar                                                                                                     |
| **[dasel](https://github.com/TomWright/dasel)**                                              | Select, put and delete data from JSON, TOML, YAML, XML and CSV files with a single tool                                                           |
| **[dat](https://github.com/datproject/dat)**                                                 | peer-to-peer sharing & live syncronization of files via command line                                                                              |
| **[dat-desktop](https://github.com/datproject/dat-desktop)**                                 | Peer to peer data syncronization                                                                                                                  |
| **[delta](https://github.com/dandavison/delta)**                                             | A syntax-highlighting pager for git and diff output                                                                                               |
| **[dive](https://github.com/wagoodman/dive)**                                                | A tool for exploring each layer in a docker image                                                                                                 |
| **[desed](https://github.com/SoptikHa2/desed)**                                              | Debugger for Sed: demystify and debug the sed scripts, from comfort of terminal                                                                   |
| **[deta](https://github.com/deta/deta-cli)**                                                 | Command line interface for managing Deta micros and deployments                                                                                   |
| **[direnv](https://github.com/direnv/direnv)**                                               | Extension to load and unload environment variables depending on the current directory                                                             |
| **[docker-slim](https://github.com/docker-slim/docker-slim)**                                | Extension to minify and secure Docker images                                                                                                      |
| **[dockle](https://github.com/goodwithtech/dockle)**                                         | Container Image Linter for Security, Helping build the Best-Practice Docker Image, Easy to start                                                  |
| **[doctl](https://github.com/digitalocean/doctl)**                                           | The official command line interface for the DigitalOcean API                                                                                      |
| **[dog](https://github.com/ogham/dog)**                                                      | A command-line DNS client                                                                                                                         |
| **[duf](https://github.com/muesli/duf)**                                                     | a better 'df' alternative                                                                                                                         |
| **[dust](https://github.com/bootandy/dust)**                                                 | A more intuitive version of du in rust                                                                                                            |
| **[envconsul](https://github.com/hashicorp/envconsul)**                                      | Launch a subprocess with environment variables using data from @hashicorp Consul and Vault                                                        |
| **[fd](https://github.com/sharkdp/fd)**                                                      | A simple, fast and user-friendly alternative to 'find'                                                                                            |
| **[felony](https://github.com/henryboldi/felony)**                                           | An open-source pgp keychain built on the modern web with Electron, React, and Redux                                                               |
| **[ffsend](https://github.com/timvisee/ffsend)**                                             | Easily and securely share files from the command line, a fully featured Firefox Send client                                                       |
| **[filebrowser](https://github.com/filebrowser/filebrowser)**                                | Web file browser                                                                                                                                  |
| **[fm](https://github.com/knipferrc/fm)**                                                    | Terminal file manager                                                                                                                             |
| **[fselect](https://github.com/jhspetersson/fselect)**                                       | Extension to find files with SQL-like queries                                                                                                     |
| **[fq](https://github.com/wader/fq)**                                                        | jq for binary formats                                                                                                                             |
| **[fuego](https://github.com/sgarciac/fuego)**                                               | Fuego is a command line client for the firestore database                                                                                         |
| **[g-assist](https://github.com/Melvin-Abraham/Google-Assistant-Unofficial-Desktop-Client)** | A cross-platform unofficial Google Assistant Client for Desktop                                                                                   |
| **[ganache](https://github.com/trufflesuite/ganache-ui)**                                    | Personal blockchain for Ethereum development                                                                                                      |
| **[gitify](https://github.com/manosim/gitify)**                                              | GitHub notifications on the menu bar                                                                                                              |
| **[gitleaks](https://github.com/zricethezav/gitleaks)**                                      | Extension to scan git repos (or files) for secrets using regex and entropy                                                                        |
| **[gitomatic](https://github.com/muesli/gitomatic)**                                         | A tool to monitor git repositories and automatically pull & push changes                                                                          |
| **[glab](https://github.com/profclems/glab)**                                                | An open-source GitLab command line tool bringing GitLab's cool features to your command line                                                      |
| **[glow](https://github.com/charmbracelet/glow)**                                            | Glow is a terminal based markdown reader designed from the ground up to bring out the beauty—and power—of the CLI                                 |
| **[gojq](https://github.com/itchyny/gojq)**                                                  | gojq is a pure Go implementation of jq that is mostly backwards compatible (but not completely)                                                   |
| **[go-chromecast](https://github.com/vishen/go-chromecast)**                                 | cli for Google Chromecast, Home devices and Cast Groups                                                                                           |
| **[gping](https://github.com/orf/gping)**                                                    | Ping, but with a graph                                                                                                                            |
| **[grex](https://github.com/pemistahl/grex)**                                                | A command-line tool and library for generating regular expressions from user-provided test cases                                                  |
| **[gron](https://github.com/tomnomnom/gron)**                                                | Extension to make JSON greppable                                                                                                                  |
| **[hclq](https://github.com/mattolenik/hclq)**                                               | Command-line processor for HashiCorp config files, like sed for HCL — Terraform, Consul, Nomad, Vault                                             |
| **[hexyl](https://github.com/sharkdp/hexyl)**                                                | A command-line hex viewer                                                                                                                         |
| **[hey](https://github.com/rakyll/hey)**                                                     | HTTP load generator, ApacheBench (ab) replacement, formerly known as rakyll/boom                                                                  |
| **[hostctl](https://github.com/guumaster/hostctl)**                                          | This tool gives more control over the use of hosts file                                                                                           |
| **[htmlq](https://github.com/mgdm/htmlq)**                                                   | A lightweight and flexible command-line JSON processor for HTML                                                                                   |
| **[hyperfine](https://github.com/sharkdp/hyperfine)**                                        | A command-line benchmarking tool                                                                                                                  |
| **[jiq](https://github.com/fiatjaf/jiq)**                                                    | Create jq queries interactively by leveraging a live reload feature in the terminal                                                               |
| **[jitsi-meet-electron](https://github.com/jitsi/jitsi-meet-electron)**                      | Desktop application for Jitsi Meet built with Electron                                                                                            |
| **[jo](https://github.com/jpmens/jo)**                                                       | JSON output from a shell                                                                                                                          |
| **[jq](https://github.com/stedolan/jq)**                                                     | Command-line JSON processor                                                                                                                       |
| **[kdash](https://github.com/kdash-rs/kdash)**                                               | A simple and fast dashboard for Kubernetes                                                                                                        |
| **[kubenav](https://github.com/kubenav/kubenav)**                                            | kubenav is the navigator for your Kubernetes clusters right in your pocket                                                                        |
| **[license](https://github.com/nishanths/license)**                                          | Command-line license text generator                                                                                                               |
| **[linuxkit](https://github.com/linuxkit/linuxkit)**                                         | A toolkit for building secure, portable and lean operating systems for containers                                                                 |
| **[manta](https://github.com/hql287/Manta)**                                                 | Flexible invoicing desktop app with beautiful & customizable templates                                                                            |
| **[mark-text](https://github.com/marktext/marktext)**                                        | A simple and elegant markdown editor, available for Linux, macOS and Windows                                                                      |
| **[masscode](https://github.com/antonreshetov/massCode)**                                    | A free and open source code snippets manager for developers                                                                                       |
| **[mc](https://github.com/minio/mc)**                                                        | MinIO Client is a replacement for ls, cp, mkdir, diff and rsync commands for filesystems and object storage                                       |
| **[mjml-app](https://github.com/mjmlio/mjml-app)**                                           | The desktop app for MJML                                                                                                                          |
| **[mkcert](https://github.com/FiloSottile/mkcert)**                                          | A simple zero-config tool to make locally trusted development certificates with any names                                                         |
| **[mockoon](https://github.com/mockoon/mockoon)**                                            | Mockoon is the easiest and quickest way to run mock APIs locally. No remote deployment, no account required, open source                          |
| **[motrix](https://github.com/agalwood/Motrix)**                                             | A full-featured download manager                                                                                                                  |
| **[mqttx](https://github.com/emqx/MQTTX)**                                                   | Elegant Cross-platform MQTT 5.0 Desktop Client                                                                                                    |
| **[muffet](https://github.com/raviqqe/muffet)**                                              | Fast website link checker in Go                                                                                                                   |
| **[mullvad-vpn](https://github.com/mullvad/mullvadvpn-app)**                                 | The Mullvad VPN client app for desktop and mobile                                                                                                 |
| **[nebula](https://github.com/slackhq/nebula)**                                              | A scalable overlay networking tool                                                                                                                |
| **[nnn](https://github.com/jarun/nnn)**                                                      | A full-featured terminal file manager                                                                                                             |
| **[node-prune](https://github.com/tj/node-prune)**                                           | Extension to remove unnecessary files from node_modules                                                                                           |
| **[nomino](https://github.com/yaa110/nomino)**                                               | Batch rename utility for developers                                                                                                               |
| **[nuclear](https://github.com/nukeop/nuclear)**                                             | Streaming music player that finds free music                                                                                                      |
| **[osquery](https://github.com/osquery/osquery)**                                            | SQL powered operating system instrumentation, monitoring, and analytics                                                                           |
| **[ots](https://github.com/sniptt-official/ots)**                                            | Share end-to-end encrypted secrets with others via a one-time URL                                                                                 |
| **[oq](https://github.com/Blacksmoke16/oq)**                                                 | A performant, and portable jq wrapper to facilitate the consumption and output of formats other than JSON; using jq filters to transform the data |
| **[page-fetch](https://github.com/detectify/page-fetch)**                                    | Fetch web pages using headless Chrome, storing all fetched resources including JavaScript files                                                   |
| **[pass](https://www.passwordstore.org/)**                                                   | Password manager                                                                                                                                  |
| **[pastel](https://github.com/sharkdp/pastel)**                                              | A command-line tool to generate, analyze, convert and manipulate colors                                                                           |
| **[peco](https://github.com/peco/peco)**                                                     | Simplistic interactive filtering tool                                                                                                             |
| **[pony](https://github.com/jessfraz/pony)**                                                 | Local file-based password, API key, secret, recovery code store backed by GPG                                                                     |
| **[pretzel](https://github.com/amiechen/pretzel)**                                           | Pretzel is Mac desktop app that shows and find keyboard shortcuts based on your current app                                                       |
| **[procs](https://github.com/dalance/procs)**                                                | A modern replacement for ps written in Rust                                                                                                       |
| **[psu](https://github.com/greenled/portainer-stack-utils)**                                 | CLI client for Portainer                                                                                                                          |
| **[pup](https://github.com/ericchiang/pup)**                                                 | Parsing HTML at the command line                                                                                                                  |
| **[q](https://github.com/harelba/q)**                                                        | Run SQL directly on CSV or TSV files                                                                                                              |
| **[responsively](https://github.com/responsively-org/responsively-app)**                     | A modified web browser that helps in responsive web development                                                                                   |
| **[rip](https://github.com/nivekuil/rip)**                                                   | A safe and ergonomic alternative to rm                                                                                                            |
| **[runjs](https://github.com/lukehaas/RunJS)**                                               | A JavaScript playground that auto-evaluates as you type                                                                                           |
| **[s5cmd](https://github.com/peak/s5cmd)**                                                   | Parallel S3 and local filesystem execution tool                                                                                                   |
| **[schema](https://github.com/Confbase/schema)**                                             | A tool to infer and instantiate schemas and translate between data formats                                                                        |
| **[scrcpy](https://github.com/Tomotoes/scrcpy-gui)**                                         | A simple & beautiful GUI application for scrcpy                                                                                                   |
| **[sd](https://github.com/chmln/sd)**                                                        | Intuitive find & replace CLI (sed alternative)                                                                                                    |
| **[shfmt](https://github.com/mvdan/sh/)**                                                    | A shell parser, formatter, and interpreter with bash support; includes shfmt                                                                      |
| **[skm](https://github.com/TimothyYe/skm)**                                                  | A simple and powerful SSH keys manager                                                                                                            |
| **[sqlectron](https://github.com/sqlectron/sqlectron-gui)**                                  | A simple and lightweight SQL client desktop with cross database and platform support                                                              |
| **[ssh-vault](https://github.com/ssh-vault/ssh-vault)**                                      | Encrypt/decrypt using ssh keys                                                                                                                    |
| **[ssl-proxy](https://github.com/suyashkumar/ssl-proxy)**                                    | Simple zero-config SSL reverse proxy with real autogenerated certificates                                                                         |
| **[switchhosts](https://github.com/oldj/SwitchHosts)**                                       | Extension to switch hosts                                                                                                                         |
| **[sysbench](https://github.com/akopytov/sysbench)**                                         | System performance benchmark tool                                                                                                                 |
| **[tabby](https://github.com/Eugeny/tabby)**                                                 | A terminal for a more modern age                                                                                                                  |
| **[task](https://github.com/go-task/task)**                                                  | A task runner / simpler Make alternative written in Go                                                                                            |
| **[teleport](https://github.com/gravitational/teleport)**                                    | Modern SSH server for teams managing distributed infrastructure                                                                                   |
| **[tflint](https://github.com/terraform-linters/tflint)**                                    | A Pluggable Terraform Linter                                                                                                                      |
| **[temps](https://github.com/jackd248/temps)**                                               | Simple menubar application based on Electron with actual weather information and forecast                                                         |
| **[tokei](https://github.com/XAMPPRocky/tokei)**                                             | Tokei is a program that displays statistics about the code                                                                                        |
| **[transfer](https://github.com/rinetd/transfer)**                                           | Converts from one encoding to another                                                                                                             |
| **[trivy](https://github.com/aquasecurity/trivy)**                                           | Scanner for vulnerabilities in container images, file systems, and Git repositories, as well as for configuration issues                          |
| **[up](https://github.com/akavel/up)**                                                       | Ultimate Plumber is a tool for writing Linux pipes with instant live preview                                                                      |
| **[udemy-downloader-gui](https://github.com/FaisalUmair/udemy-downloader-gui)**              | A desktop application for downloading Udemy Courses                                                                                               |
| **[waypoint](https://github.com/hashicorp/waypoint)**                                        | A tool to build, deploy, and release any application on any platform                                                                              |
| **[websocat](https://github.com/vi/websocat)**                                               | CLI for interacting with web sockets                                                                                                              |
| **[webtorrent](https://github.com/webtorrent/webtorrent-desktop)**                           | Streaming torrent app for Mac, Windows, and Linux                                                                                                 |
| **[Whaler](https://github.com/P3GLEG/Whaler)**                                               | Whaler takes a Docker image and attempts to reverse engineer the Dockerfile that created it                                                       |
| **[wkhtmltopdf](https://github.com/wkhtmltopdf/wkhtmltopdf)**                                | Convert HTML to PDF using Webkit (QtWebKit)                                                                                                       |
| **[xurls](https://github.com/mvdan/xurls)**                                                  | Extract urls from text                                                                                                                            |
| **[yq](https://github.com/mikefarah/yq/v4)**                                                 | Process YAML documents from the CLI                                                                                                               |

### NPM Packages

NPM provides a huge catalog of useful CLIs and libraries so we also include a useful and interesting default set of NPM-hosted CLIs for hosts in the `desktop` group ([defined here](environments/prod/group_vars/desktop/npm-packages.yml), for example):

| Package                                                                      | Description                                                                                                                                                                                                                     |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[@angular/cli](https://npmjs.com/package/@angular/cli)**                   | Official CLI for [Angular](https://angular.io/) capable of generating new projects, generating boilerplate files, and testing apps with LiveReload                                                                              |
| **[@cloudflare/wrangler](https://npmjs.com/package/@cloudflare/wrangler)**   | A CLI tool designed for folks who are interested in using Cloudflare Workers                                                                                                                                                    |
| **[@ionic/cli](https://npmjs.com/package/@ionic/cli)**                       | A command line interface (CLI) is go-to tool for developing Ionic apps                                                                                                                                                          |
| **[@nestjs/cli](https://npmjs.com/package/@nestjs/cli)**                     | A command-line interface tool that helps you to initialize, develop, and maintain your Nest applications                                                                                                                        |
| **[@sentry/cli](https://npmjs.com/package/@sentry/cli)**                     | A Sentry command line client for some generic tasks                                                                                                                                                                             |
| **[@vercel/ncc](https://npmjs.com/package/@vercel/ncc)**                     | CLI for compiling a Node.js module into a single file, together with all its dependencies, gcc-style                                                                                                                            |
| **[auto-install](https://npmjs.com/package/auto-install)**                   | Auto installs dependencies as you code                                                                                                                                                                                          |
| **[bitly-cli-client](https://npmjs.com/package/bitly-cli-client)**           | Shorten links with Bitly in the terminal                                                                                                                                                                                        |
| **[browser-sync](https://browsersync.io/)**                                  | test desktop and mobile versions of a website at the same time                                                                                                                                                                  |
| **[caniuse-cmd](https://npmjs.com/package/caniuse-cmd)**                     | Caniuse command line tool                                                                                                                                                                                                       |
| **[carbon-now-cli](https://npmjs.com/package/carbon-now-cli)**               | Tool that generates beautiful images of source code through an intuitive UI, while customizing aspects like fonts, themes, window controls and much mor                                                                         |
| **[commitizen](https://npmjs.com/package/commitizen)**                       | The commitizen command line utility                                                                                                                                                                                             |
| **[cordova](https://npmjs.com/package/cordova)**                             | The command line tool to build, deploy and manage Cordova-based applications                                                                                                                                                    |
| **[deviceframe](https://npmjs.com/package/deviceframe)**                     | Put device frames around mobile/web/progressive app screenshots                                                                                                                                                                 |
| **[editly](https://npmjs.com/package/editly)**                               | A tool and framework for declarative NLE (non-linear video editing) using Node.js and ffmpeg                                                                                                                                    |
| **[electron](https://npmjs.com/package/electron)**                           | A tool that enables to write cross-platform desktop applications using JavaScript, HTML and CSS                                                                                                                                 |
| **[emma-cli](https://npmjs.com/package/emma-cli)**                           | Install the package you are looking for                                                                                                                                                                                         |
| **[emoj](https://npmjs.com/package/emoj)**                                   | Find relevant emoji from text on the command-line                                                                                                                                                                               |
| **[empty-trash-cli](https://npmjs.com/package/empty-trash-cli)**             | A CLI to empty the trash                                                                                                                                                                                                        |
| **[eslint](https://npmjs.com/package/eslint)**                               | A tool for identifying and reporting on patterns found in ECMAScript/JavaScript code                                                                                                                                            |
| **[fastify-cli](https://npmjs.com/package/fastify-cli)**                     | Command line tools for Fastify. Generate, write, and run an application with one single command                                                                                                                                 |
| **[firebase-tools](https://npmjs.com/package/firebase-tools)**               | The Firebase Command Line Interface (CLI) Tools can be used to test, manage, and deploy Firebase project from the command line                                                                                                  |
| **[fkill-cli](https://npmjs.com/package/fkill-cli)**                         | Fabulously kill processes. Cross-platform.                                                                                                                                                                                      |
| **[fx](https://npmjs.com/package/fx)**                                       | Command-line JSON processing tool                                                                                                                                                                                               |
| **[git-open](https://npmjs.com/package/git-open)**                           | Type git open to open the repo website (GitHub, GitLab, Bitbucket) in browser                                                                                                                                                   |
| **[google-font-installer](https://npmjs.com/package/google-font-installer)** | Google Font Installer is a NodeJS module/CLI that lets you Search, Download and Install fonts offered by Google Web Fonts                                                                                                       |
| **[gtop](https://npmjs.com/package/gtop)**                                   | System monitoring dashboard for terminal                                                                                                                                                                                        |
| **[gulp](https://npmjs.com/package/gulp)**                                   | A toolkit that helps you automate painful or time-consuming tasks in your development workflow                                                                                                                                  |
| **[imgur-uploader-cli](https://npmjs.com/package/imgur-uploader-cli)**       | CLI to upload images to imgur                                                                                                                                                                                                   |
| **[ios-deploy](https://npmjs.com/package/ios-deploy)**                       | Command line tool to install aand debug iOS apps                                                                                                                                                                                |
| **[ipfs-deploy](https://npmjs.com/package/ipfs-deploy)**                     | Upload static website to IPFS pinning services and optionally update DNS                                                                                                                                                        |
| **[is-up-cli](https://npmjs.com/package/is-up-cli)**                         | Check whether a website is up or down using the isitup.org API                                                                                                                                                                  |
| **[localtunnel](https://npmjs.com/package/localtunnel)**                     | localtunnel exposes localhost to the world for easy testing and sharing                                                                                                                                                         |
| **[mjml](https://npmjs.com/package/mjml)**                                   | A markup language created by Mailjet and designed to reduce the pain of coding a responsive email                                                                                                                               |
| **[nativefier](https://npmjs.com/package/nativefier)**                       | Tool to make any web page a desktop application                                                                                                                                                                                 |
| **[nectarjs](https://npmjs.com/package/nectarjs)**                           | A JavaScript native compiler                                                                                                                                                                                                    |
| **[newman](https://npmjs.com/package/newman)**                               | A command-line collection runner for Postman                                                                                                                                                                                    |
| **[np](https://npmjs.com/package/np)**                                       | A better npm publish                                                                                                                                                                                                            |
| **[npm-check](https://npmjs.com/package/npm-check)**                         | Check for outdated, incorrect, and unused dependencies                                                                                                                                                                          |
| **[nrm](https://npmjs.com/package/nrm)**                                     | nrm can help you easy and fast switch between different npm registries                                                                                                                                                          |
| **[oclif](https://npmjs.com/package/oclif)**                                 | A framework for building CLIs in Node.js                                                                                                                                                                                        |
| **[package-size](https://npmjs.com/package/package-size)**                   | Tool to get the bundle size of an npm package                                                                                                                                                                                   |
| **[pageres-cli](https://npmjs.com/package/pageres-cli)**                     | A CLI to capture screenshots of websites in various resolutions                                                                                                                                                                 |
| **[playwright](https://npmjs.com/package/playwright)**                       | Single API to automate Chromium, WebKit, and Firefox (available as a CLI and library)                                                                                                                                           |
| **[pm2](https://npmjs.com/package/pm2)**                                     | PM2 is a production process manager for Node.js applications with a built-in load balancer                                                                                                                                      |
| **[pkg](https://npmjs.com/package/pkg)**                                     | This command line interface enables you to package your Node.js project into an executable that can be run even on devices without Node.js installed                                                                            |
| **[prettier](https://npmjs.com/package/prettier)**                           | A code formatter                                                                                                                                                                                                                |
| **[psi](https://npmjs.com/package/psi)**                                     | PageSpeed Insights with reporting                                                                                                                                                                                               |
| **[ramda-cli](https://npmjs.com/package/ramda-cli)**                         | A tool for processing data with functional pipelines in the command-line or interactively in browser                                                                                                                            |
| **[semantic-release](https://npmjs.com/package/semantic-release)**           | A tool that automates the process of releasing software, featuring integrations with GitHub / GitLab releases                                                                                                                   |
| **[serve](https://npmjs.com/package/serve)**                                 | Static file serving and directory listing                                                                                                                                                                                       |
| **[serverless](https://npmjs.com/package/serverless)**                       | Serverless Framework – Build web, mobile and IoT applications with serverless architectures using AWS Lambda, Azure Functions, Google CloudFunctions & more                                                                     |
| **[share-cli](https://npmjs.com/package/share-cli)**                         | Quickly share files from your command line                                                                                                                                                                                      |
| **[sharp-cli](https://npmjs.com/package/sharp-cli)**                         | CLI for sharp, a high performance Node.js image processing module                                                                                                                                                               |
| **[speed-test](https://npmjs.com/package/speed-test)**                       | Test your internet connection speed and ping using speedtest.net from the CLI                                                                                                                                                   |
| **[stegcloak](https://npmjs.com/package/stegcloak)**                         | StegCloak is a pure JavaScript steganography module designed in functional programming style, to hide secrets inside text by compressing and encrypting the secret before cloaking it with special unicode invisible characters |
| **[supdock](https://npmjs.com/package/supdock)**                             | A CLI for running commands like "docker logs" in an easier, more interactive way                                                                                                                                                |
| **[surge](https://npmjs.com/package/surge)**                                 | Publish web apps to a CDN with a single command and no setup required                                                                                                                                                           |
| **[svgo](https://npmjs.com/package/svgo)**                                   | SVG Optimizer is a Node.js-based tool for optimizing SVG vector graphics files                                                                                                                                                  |
| **[terminalizer](https://npmjs.com/package/terminalizer)**                   | Record your terminal and generate animated gif images or share a web player link terminalizer.com                                                                                                                               |
| **[tinypng-cli](https://npmjs.com/package/tinypng-cli)**                     | Handy command line tool for shrinking PNG images using the TinyPNG API                                                                                                                                                          |
| **[tldr](https://npmjs.com/package/tldr)**                                   | A Node.js based command-line client for tldr                                                                                                                                                                                    |
| **[ts2c](https://npmjs.com/package/ts2c)**                                   | A JavaScript/TypeScript to C compiler                                                                                                                                                                                           |
| **[typescript](https://npmjs.com/package/typescript)**                       | A language for application-scale JavaScript                                                                                                                                                                                     |
| **[wifi-password-cli](https://npmjs.com/package/wifi-password-cli)**         | CLI to get current wifi password                                                                                                                                                                                                |
| **[wordpressify](https://npmjs.com/package/wordpressify)**                   | Automate your WordPress development workflow                                                                                                                                                                                    |
| **[zx](https://npmjs.com/package/zx)**                                       | A tool for writing better scripts                                                                                                                                                                                               |

### Python Packages

In a similar fashion to the NPM packages, we include a great set of default Python packages that are included by default for the `desktop` group ([defined here](environments/prod/group_vars/desktop/pip-packages.yml)):

| Package                                                          | Description                                                                                                                                                                                                                                              |
| ---------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[ansibleconnect](https://pypi.org/project/ansibleconnect/)**   | Parses Ansible inventory and opens up a tmux session for each host                                                                                                                                                                                       |
| **[ansible-lint](https://pypi.org/project/ansible-lint/)**       | Lint tool that checks [Ansible](https://www.ansible.com/) projects for best practices and problematic code                                                                                                                                               |
| **[asciinema](https://pypi.org/project/asciinema/)**             | Tool that records terminal session and replay them in a terminal as well as in a web browser                                                                                                                                                             |
| **[aws-shell](https://pypi.org/project/aws-shell/)**             | AWS shell is the interactive productivity booster for the AWS CLI                                                                                                                                                                                        |
| **[cookiecutter](https://pypi.org/project/cookiecutter/)**       | A command-line utility that creates projects from cookiecutters (project templates)                                                                                                                                                                      |
| **[gdown](https://pypi.org/project/gdown)**                      | An alternative to wget and curl that can handle downloading large files from Google Drive                                                                                                                                                                |
| **[git-filter-repo](https://pypi.org/project/git-filter-repo)**  | Tool that aids in wiping particular sections of a repository                                                                                                                                                                                             |
| **[gixy](https://pypi.org/project/gixy/)**                       | A tool to analyze Nginx configuration                                                                                                                                                                                                                    |
| **[httpstat](https://pypi.org/project/httpstat/)**               | A script that reflects curl statistics in a fascinating and well-defined way, it is a single file which is compatible with Python 3 and requires no additional software (dependencies) to be installed on a users system                                 |
| **[http-prompt](https://pypi.org/project/http-prompt/)**         | An interactive command-line HTTP client featuring autocomplete and syntax highlighting, built on HTTPie and prompt_toolkit                                                                                                                               |
| **[iredis](https://pypi.org/project/iredis/)**                   | A terminal client for redis with auto-completion and syntax highlighting                                                                                                                                                                                 |
| **[kube-shell](https://pypi.org/project/kube-shell/)**           | An integrated shell for working with the Kubernetes CLI                                                                                                                                                                                                  |
| **[litecli](https://pypi.org/project/litecli/)**                 | A command-line client for SQLite databases that has auto-completion and syntax highlighting                                                                                                                                                              |
| **[netaddr](https://pypi.org/project/netaddr/)**                 | A system-independent network address manipulation library for Python 2.7 and 3.5+                                                                                                                                                                        |
| **[ngxtop](https://pypi.org/project/ngxtop/)**                   | ngxtop parses your nginx access log and outputs useful, top-like, metrics of your nginx server                                                                                                                                                           |
| **[molecule](https://pypi.org/project/molecule/)**               | Molecule project is designed to aid in the development and testing of Ansible roles. Molecule provides support for testing with multiple instances, operating systems and distributions, virtualization providers, test frameworks and testing scenarios |
| **[mycli](https://pypi.org/project/mycli/)**                     | Command line interface for MySQL database with auto-completion and syntax highlighting                                                                                                                                                                   |
| **[pre-commit](https://pypi.org/project/pre-commit/)**           | A framework for managing and maintaining multi-language pre-commit hooks                                                                                                                                                                                 |
| **[pywhat](https://pypi.org/project/pywhat/)**                   | what is recursive                                                                                                                                                                                                                                        |
| **[social-analyzer](https://pypi.org/project/social-analyzer/)** | API, CLI & Web App for analyzing & finding a person’s profile across social media websites                                                                                                                                                               |
| **[spotdl](https://pypi.org/project/spotdl/)**                   | A tool to download Spotify playlists and songs along with album art and metadata                                                                                                                                                                         |
| **[starred](https://pypi.org/project/starred/)**                 | Generate a GitHub Awesome list directly from your starred repositories                                                                                                                                                                                   |
| **[statcode](https://pypi.org/project/statcode/)**               | `man` pages for HTTP status codes (used by running `statcode 418`, for instance)                                                                                                                                                                         |
| **[truffleHog](https://pypi.org/project/truffleHog/)**           | A tool which makes it easier to search through the history of a git repository to discover passwords and other secrets                                                                                                                                   |
| **[virtualenv](https://pypi.org/project/virtualenv/)**           | A tool for creating isolated virtual python environments                                                                                                                                                                                                 |
| **[yamllint](https://pypi.org/project/yamllint/)**               | A linter for YAML files                                                                                                                                                                                                                                  |

### Ruby Gems

A handful of Ruby gems are also installed on targets in the `desktop` group ([defined here](environments/prod/group_vars/desktop/ruby-gems.yml)):

| Package                                              | Description                                                                                                                          |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **[bropages](https://rubygems.org/gems/bropages)**   | Informative CLI tool that provides community-curated examples for most CLI programs                                                  |
| **[bundler](https://rubygems.org/gems/bundler)**     | A tool that manages ruby application's gem dependencies through its entire life, across many machines, systematically and repeatably |
| **[chef](https://rubygems.org/gems/chef)**           | A systems integration framework, built to bring the benefits of configuration management to the entire infrastructure                |
| **[cocoapods](https://rubygems.org/gems/cocoapods)** | A tool that manages library dependencies for Xcode project                                                                           |
| **[fpm](https://rubygems.org/gems/fpm)**             | A tool that converts directories, rpms, python eggs, rubygems, and more to rpms, debs, solaris packages and more                     |
| **[gist](https://rubygems.org/gems/gist)**           | A tool that provides a single function (Gist.gist) that uploads a gist                                                               |
| **[mdl](https://rubygems.org/gems/mdl)**             | A style checker/lint tool for markdown files                                                                                         |
| **[t](https://rubygems.org/gems/t)**                 | A command-line power tool for Twitter                                                                                                |

### Visual Studio Code Extensions

A considerable amount of effort has gone into researching and finding the "best" VS Code extensions. They are [defined here](environments/prod/group_vars/desktop/vscode-extensions.yml) and Gas Station also installs a good baseline configuration which includes settings for these extensions:

| Package                                                                                                                                            | Description                                                                                                                                                                                                                     |
| -------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[Angular.ng-template](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)**                                                 | Editor services for Angular template files                                                                                                                                                                                      |
| **[attilabuti.vscode-mjml](https://marketplace.visualstudio.com/items?itemName=attilabuti.vscode-mjml)**                                           | MJML preview, lint, and compile                                                                                                                                                                                                 |
| **[bierner.markdown-emoji](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-emoji)**                                           | Adds emoji syntax support to VS Code's built-in Markdown preview                                                                                                                                                                |
| **[ChakrounAnas.turbo-console-log](https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log)**                           | This extension make debugging much easier by automating the operation of writing meaningful log message                                                                                                                         |
| **[ChFlick.firecode](https://marketplace.visualstudio.com/items?itemName=ChFlick.firecode)**                                                       | Firestore security rule support for Visual Studio Code                                                                                                                                                                          |
| **[chrmarti.regex](https://marketplace.visualstudio.com/items?itemName=chrmarti.regex)**                                                           | Shows the current regular expression's matches in a side-by-side document                                                                                                                                                       |
| **[cweijan.vscode-mysql-client2](https://marketplace.visualstudio.com/items?itemName=cweijan.vscode-mysql-client2)**                               | A database GUI for SQL, SQLite, MongoDB, Redis, and ElasticSearch                                                                                                                                                               |
| **[DavidAnson.vscode-markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)**                           | Markdown/CommonMark linting and style checking for Visual Studio Code                                                                                                                                                           |
| **[dbaeumer.vscode-eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)**                                           | Integrates ESLint into VS Code                                                                                                                                                                                                  |
| **[denoland.vscode-deno](https://marketplace.visualstudio.com/items?itemName=denoland.vscode-deno)**                                               | Adds support for Deno (powered by the Deno language server)                                                                                                                                                                     |
| **[eamodio.gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)**                                                         | GitLens is a popular extension that supercharges the Git capabilities built into VS Code                                                                                                                                        |
| **[EditorConfig.EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)**                                     | This plugin attempts to override user/workspace settings with setting found in .editorconfig files                                                                                                                              |
| **[esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)**                                           | Prettier is an opinionated code formatter                                                                                                                                                                                       |
| **[ericadamski.carbon-now-sh](https://marketplace.visualstudio.com/items?itemName=ericadamski.carbon-now-sh)**                                     | A VS Code extension to open the current editor content in carbon.now.sh                                                                                                                                                         |
| **[firsttris.vscode-jest-runner](https://marketplace.visualstudio.com/items?itemName=firsttris.vscode-jest-runner)**                               | Manage, run, and debug individual Jest tests                                                                                                                                                                                    |
| **[formulahendry.auto-rename-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)**                             | Automatically rename paired HTML/XML tag, same as Visual Studio IDE does                                                                                                                                                        |
| **[formulahendry.code-runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)**                                     | Run code snippet or code file                                                                                                                                                                                                   |
| **[GitHub.vscode-pull-request-github](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)**                     | Review and manage your GitHub pull requests and issues directly in VS Code                                                                                                                                                      |
| **[GitLab.gitlab-workflow](https://marketplace.visualstudio.com/items?itemName=GitLab.gitlab-workflow)**                                           | This extension integrates GitLab to VS Code                                                                                                                                                                                     |
| **[GoogleCloudTools.cloudcode](https://marketplace.visualstudio.com/items?itemName=GoogleCloudTools.cloudcode)**                                   | This extension brings the power and convenience of IDEs to cloud-native application development                                                                                                                                 |
| **[golang.Go](https://marketplace.visualstudio.com/items?itemName=golang.Go)**                                                                     | This extension provides rich language support for the Go programming language, integrates with Google Cloud services like Google Kubernetes Engine, Cloud Run, Cloud APIs, and Secret Manager                                   |
| **[HashiCorp.terraform](https://marketplace.visualstudio.com/items?itemName=HashiCorp.terraform)**                                                 | This extension adds syntax highlighting and other editing features for Terraform files using the Terraform Language Server                                                                                                      |
| **[hediet.vscode-drawio](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio)**                                               | Allows editing draw.io images in VS Code by adding files ending with .drawio.png                                                                                                                                                |
| **[IBM.output-colorizer](https://marketplace.visualstudio.com/items?itemName=IBM.output-colorizer)**                                               | This extension adds syntax colorization for both the output/debug/extensions panel and \*.log files, other extension that colorize the output panel will disable this extension                                                 |
| **[Kelvin.vscode-sshfs](https://marketplace.visualstudio.com/items?itemName=Kelvin.vscode-sshfs)**                                                 | Allows mounting SSH destinations as file system mounts inside VS Code                                                                                                                                                           |
| **[mads-hartmann.bash-ide-vscode](https://marketplace.visualstudio.com/items?itemName=mads-hartmann.bash-ide-vscode)**                             | This extension utilizes the bash language server, that is based on Tree Sitter and its grammar for Bash and supports explainshell integration                                                                                   |
| **[ms-azuretools.vscode-docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)**                                 | This extension makes it easy to build, manage, and deploy containerized applications from Visual Studio Code                                                                                                                    |
| **[ms-kubernetes-tools.vscode-kubernetes-tools](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools)** | The extension for developers building applications to run in Kubernetes clusters and for DevOps staff troubleshooting Kubernetes applications                                                                                   |
| **[ms-vscode-remote.remote-containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)**                   | Containers extension enables the use a Docker container as a full-featured development environment                                                                                                                              |
| **[ms-vscode-remote.remote-ssh](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)**                                 | SSH enables the use of any remote machine with a SSH server as the development environment                                                                                                                                      |
| **[ms-vscode-remote.remote-wsl](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl)**                                 | WSL extension enables the use VS Code on Windows to build Linux applications that run on the Windows Subsystem for Linux(WSL)                                                                                                   |
| **[ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)**                                                       | A VS Code extension with rich support for the Python language, including features such as IntelliSense (Pylance), linting, debugging, code navigation, code formatting, refactoring, variable explorer, test explorer, and more |
| **[ms-vscode.PowerShell](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell)**                                               | This extension provides rich PowerShell language support for Visual Studio Code                                                                                                                                                 |
| **[MS-vsliveshare.vsliveshare](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)**                                   | This extension enables to collaboratively edit and debug with others in real time, regardless what programming languages are used                                                                                               |
| **[MS-vsliveshare.vsliveshare-audio](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-audio)**                       | This extension enhances the existing Visual Studio Live Share experience, by enabling to quickly spin up an audio call directly from within Visual Studio Code, without needing to use a separate tool or service               |
| **[njpwerner.autodocstring](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)**                                         | Aids in writing Python doc strings via templates                                                                                                                                                                                |
| **[nrwl.angular-console](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console)**                                               | A UI to accompany the Nx CLI                                                                                                                                                                                                    |
| **[paulvarache.vscode-taskfile](https://marketplace.visualstudio.com/items?itemName=paulvarache.vscode-taskfile)**                                 | This extension provides Intellisense, Tasks, a Tree View and Hover actions for your Taskfiles                                                                                                                                   |
| **[philnash.ngrok-for-vscode](https://marketplace.visualstudio.com/items?itemName=philnash.ngrok-for-vscode)**                                     | A VSCode extension for controlling ngrok from the command palette                                                                                                                                                               |
| **[PKief.material-icon-theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)**                                     | Material design icons                                                                                                                                                                                                           |
| **[pranaygp.vscode-css-peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)**                                       | A VSCode extension for peeking at CSS definitions from a class or id taq in HTML                                                                                                                                                |
| **[quicktype.quicktype](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)**                                                 | An extension that generates types and helper code for reading JSON                                                                                                                                                              |
| **[rbbit.typescript-hero](https://marketplace.visualstudio.com/items?itemName=rbbit.typescript-hero)**                                             | A VSCode extension to organize and sort all the TS imports                                                                                                                                                                      |
| **[redhat.ansible](https://marketplace.visualstudio.com/items?itemName=redhat.ansible)**                                                           | This extension adds language support for Ansible to Visual Studio Code and OpenVSX compatible editors by leveraging ansible-language-server                                                                                     |
| **[redhat.vscode-yaml](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)**                                                   | Provides comprehensive YAML Language support to Visual Studio Code, via the yaml-language-server, with built-in Kubernetes syntax support                                                                                       |
| **[richie5um2.vscode-sort-json](https://marketplace.visualstudio.com/items?itemName=richie5um2.vscode-sort-json)**                                 | Alphabetically sorts the keys in selected JSON objects                                                                                                                                                                          |
| **[Rubymaniac.vscode-paste-and-indent](https://marketplace.visualstudio.com/items?itemName=Rubymaniac.vscode-paste-and-indent)**                   | This extension adds limited support for pasting and indenting code                                                                                                                                                              |
| **[salbert.comment-ts](https://marketplace.visualstudio.com/items?itemName=salbert.comment-ts)**                                                   | Adds automatic templating of TypeScript-flavored JSDoc comments                                                                                                                                                                 |
| **[shd101wyy.markdown-preview-enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)**                 | An extension that provides with many useful functionalities such as automatic scroll sync, math typesetting, mermaid, PlantUML, pandoc, PDF export, code chunk, presentation writer, etc                                        |
| **[softwaredotcom.swdc-vscode](https://marketplace.visualstudio.com/items?itemName=softwaredotcom.swdc-vscode)**                                   | A plugin for automatic programming metrics and time tracking Visual Studio Code                                                                                                                                                 |
| **[steoates.autoimport](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)**                                                 | An extension that automatically finds, parses and provides code actions and code completion for all available imports                                                                                                           |
| **[stylelint.vscode-stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)**                                   | A mighty, modern CSS linter that helps to enforce consistent conventions and avoid errors in stylesheets                                                                                                                        |
| **[timonwong.shellcheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck)**                                               | Integrates Shellcheck linting (linting for shell scripts)                                                                                                                                                                       |
| **[toba.vsfire](https://marketplace.visualstudio.com/items?itemName=toba.vsfire)**                                                                 | A VSCode extension for syntax highlighting, hover help and code completions with Firestore security rules and index definition files                                                                                            |
| **[tyriar.sort-lines](https://marketplace.visualstudio.com/items?itemName=tyriar.sort-lines)**                                                     | An extension that sorts lines of text in Visual Studio Code                                                                                                                                                                     |
| **[usernamehw.errorlens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)**                                               | An extension that charges language diagnostic features by making diagnostics stand out more prominently, highlighting the entire line wherever a diagnostic is generated by the language and also prints the message inline     |
| **[valentjn.vscode-ltex](https://marketplace.visualstudio.com/items?itemName=valentjn.vscode-ltex)**                                               | Adds LanguageTool functionality including grammar and spell-checking                                                                                                                                                            |
| **[VisualStudioExptTeam.vscodeintellicode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)**           | The IntelliCode extension for Visual Studio Code provides artificial intelligence-assisted IntelliSense for Python, Java, TypeScript, and JavaScript                                                                            |
| **[vsciot-vscode.vscode-arduino](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino)**                               | The Arduino extension makes it easy to develop, build, deploy and debug your Arduino sketches in Visual Studio Code, with a rich set of functionalities                                                                         |
| **[vsls-contrib.codetour](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.codetour)**                                             | Allows running, creating, and editting code tours which are a unique way of guiding contributors through the code base of a project                                                                                             |
| **[vsls-contrib.gistfs](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gistfs)**                                                 | A Visual Studio Code extension that allows you to edit GitHub Gists and repositories from the comfort of your favorite editor                                                                                                   |
| **[wayou.vscode-todo-highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)**                                 | An extension that highlights TODO, FIXME, and other annotations within the code                                                                                                                                                 |
| **[wix.vscode-import-cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)**                                           | This extension will display inline in the editor the size of the imported package                                                                                                                                               |
| **[yatki.vscode-surround](https://marketplace.visualstudio.com/items?itemName=yatki.vscode-surround)**                                             | Easily add code that surrounds other code like try/catches                                                                                                                                                                      |

### Chrome Extensions

To reduce the amount of time it takes to configure Chromium-based browsers like Brave, Chromium, and Chrome, we also include the capability of automatically installing Chromium-based browser extensions (via a variable [defined here](environments/prod/group_vars/desktop/chrome-extensions.yml)):

| Package                                                                                                                                   | Description                                                                                                                       |
| ----------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| **[AdGuard AdBlocker](https://chrome.google.com/webstore/detail/adguard-adblocker/bgnkhhnnamicmpeenaelnjfhikgbkllg)**                     | Blocks all types of ads on all web pages, even on Facebook, YouTube and all other websites                                        |
| **[Bitly](https://chrome.google.com/webstore/detail/bitly-powerful-short-link/iabeihobmhlgpkcgjiloemdbofjbdcic)**                         | Creates short, customized, powerful links from any page and share them with the world                                             |
| **[Bitwarden](https://chrome.google.com/webstore/detail/bitwarden-free-password-m/nngceckbapebfimnlniiiahkandclblb)**                     | A secure and free password manager for all of the devices                                                                         |
| **[Buffer](https://chrome.google.com/webstore/detail/buffer/noojglkidnpfjbincgijbaiedldjfbhh)**                                           | Shares contents to Instagram, Twitter, Facebook, Pinterest and LinkedIn from anywhere on the web                                  |
| **[Checkbot](https://chrome.google.com/webstore/detail/checkbot-seo-web-speed-se/dagohlmlhagincbfilmkadjgmdnkjinl)**                      | SEO, web speed, and security tester/crawler                                                                                       |
| **[Falcon](https://chrome.google.com/webstore/detail/falcon/mmifbbohghecjloeklpbinkjpbplfalb)**                                           | Chrome extension for full text history search                                                                                     |
| **[Floccus](https://chrome.google.com/webstore/detail/floccus-bookmarks-sync/fnaicdffflnofjppbagibeoednhnbjhg)**                          | Syncs bookmarks across browsers via Nextcloud, WebDAV or Google Drive                                                             |
| **[Git History Browser Extension](https://chrome.google.com/webstore/detail/git-history-browser-exten/laghnmifffncfonaoffcndocllegejnf)** | Adds a button to github to see the file history                                                                                   |
| **[Google Dictionary](https://chrome.google.com/webstore/detail/google-dictionary-by-goog/mgijmajocgfcbeboacabfgobmjgjcoja)**             | View definitions easily as you browse the web                                                                                     |
| **[Grammarly](https://chrome.google.com/webstore/detail/grammarly-for-chrome/kbfnbcaeplbcioakkpcpgfkobkghlhen)**                          | A Chrome extension for grammar and spelling to style and tone, and eliminate writing errors and find the perfect words to express |
| **[Headless Recorder](https://chrome.google.com/webstore/detail/headless-recorder/djeegiggegleadkkbgopoonhjimgehda)**                     | A Chrome extension for recording browser interaction and generating Puppeteer & Playwright scripts                                |
| **[HTTPS Everywhere](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp)**                       | A Chrome extension to encrypt the Web! Automatically use HTTPS security on many sites                                             |
| **[JSON Viewer Pro](https://chrome.google.com/webstore/detail/json-viewer-pro/eifflpmocdbdmepbjaopkkhbfmdgijcc)**                         | A completely free extension to visualise JSON response in awesome Tree and Chart view with great user experience and options      |
| **[LastPass](https://chrome.google.com/webstore/detail/lastpass-free-password-ma/hdokiejnpimakedhajhdlcegeplioahd)**                      | A password manager that saves passwords and gives secure access from every computer and mobile device                             |
| **[LanguageTool](https://chrome.google.com/webstore/detail/grammar-spell-checker-%E2%80%94-l/oldceeleldhonbafppcapldpdifcinji)**          | Grammar and spelling checker with Google Docs integration                                                                         |
| **[Markdown Here](https://chrome.google.com/webstore/detail/markdown-here/elifhakcjgalahccnjkneoccemfahfoa)**                             | A Chrome extension to write email in Markdown and render it (make it pretty!) before sending                                      |
| **[MetaMask](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn)**                                       | An extension for accessing Ethereum enabled distributed applications, or "Dapps" in browser                                       |
| **[Octohint](https://chrome.google.com/webstore/detail/octohint/hbkpjkfdheainjkkebeoofkpgddnnbpk)**                                       | The missing IntelliSense hint for GitHub and GitLab                                                                               |
| **[Rakuten](https://chrome.google.com/webstore/detail/rakuten-get-cash-back-for/chhjbpecpncaggjpdakmflnfcopglcmi)**                       | A Chrome extension to find best shopping deals and coupons and just save them                                                     |
| **[Screenity](https://chrome.google.com/webstore/detail/screenity-screen-recorder/kbbdabhdfibnancpjfhlkhafgdilcnji)**                     | The most powerful screen recorder for Chrome                                                                                      |
| **[SingleFile](https://chrome.google.com/webstore/detail/singlefile/mpiodijhokgodhhofbcjdecpffjipkle)**                                   | A Chrome extension to save a complete page into a single HTML file                                                                |
| **[SponsorBlock](https://chrome.google.com/webstore/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone)**                   | A Chrome extension to skip sponsorships, subscription begging and more on YouTube videos                                          |
| **[Vimeo Record](https://chrome.google.com/webstore/detail/vimeo-record-screen-webca/ejfmffkmeigkphomnpabpdabfddeadcb)**                  | A Chrome extension to record and share unlimited free video messages from your browser                                            |
| **[Web Vitals](https://chrome.google.com/webstore/detail/web-vitals/ahfhijdlegdabablpippeagghigmibma?hl=en)**                             | A Chrome extension to measure metrics for a healthy site                                                                          |

### Homebrew Formulae (macOS and Linux only)

Although most of the `brew` installs are handled by the [Binaries](#binaries) installer, some `brew` packages are also installed using [this configuration](environments/prod/group_vars/desktop/homebrew.yml). The default Homebrew formulae include:

| Package                                                                   | Description                                           |
| ------------------------------------------------------------------------- | ----------------------------------------------------- |
| **[automake](https://formulae.brew.sh/formula/automake)**                 | Tool for generating GNU Standards-compliant Makefiles |
| **[carthage](https://formulae.brew.sh/formula/carthage)**                 | A simple, decentralized dependency manager for Cocoa  |
| **[chrome-cli](https://formulae.brew.sh/formula/chrome-cli)**             | Control Google Chrome from the command-line           |
| **[findutils](https://formulae.brew.sh/formula/findutils)**               | Collection of GNU find, xargs, and locate             |
| **[ideviceinstaller](https://formulae.brew.sh/formula/ideviceinstaller)** | Tool for managing apps on iOS devices                 |
| **[libimobiledevice](https://formulae.brew.sh/formula/libimobiledevice)** | Library to communicate with iOS devices natively      |

### Homebrew Casks (macOS only)

On macOS, some software is installed using Homebrew casks. These include:

| Package                                                  | Description                                                                                                                     |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| **[clocker](https://formulae.brew.sh/cask/clocker)**     | macOS program that shows the time in multiple timezones in the top menu bar                                                     |
| **[secretive](https://github.com/maxgoedjen/secretive)** | there is no importing/exporting keys so you only have access to the public key                                                  |
| **[sloth](https://github.com/sveinbjornt/Sloth)**        | macOS program that shows all open files, directories, sockets, pipes, and devices in use by all running processes on the system |
| **[stats](https://formulae.brew.sh/cask/stats)**         | macOS program that shows the system monitor in the top menu bar                                                                 |

### Go, Rust, and System-Specific Packages

Go packages, Rust crates, and system-specific packages like `.deb` and `.rpm` bundles are all handled by the `[professormanhattan.genericinstaller](https://galaxy.ansible.com/professormanhattan/genericinstaller)` role described above in the [Binaries](#binaries) section. There are also ways of installing Go and Rust packages directly by using configuration options provided by their corresponding roles outlined in the [Roles](#roles) section.

<a href="#web-applications" style="width:100%"><img style="width:100%" src="https://gitlab.com/megabyte-labs/assets/-/raw/master/png/aqua-divider.png" /></a>

## Web Applications

This playbook does a bit more than just install software. It also optionally sets up web applications too. If you choose to deploy the default Gas Station web applications on your network, you should probably do it on a computer/server that has a lot of RAM (e.g. 64GB+).

Although a production environment will always be more stable and performant if it is hosted with a major cloud provider, sometimes it makes more sense to locally host web applications. Some applications have abnormally large RAM requirements that could potentially cost thousands per month to host with a legit cloud provider.

We use Kubernetes as the provider for the majority of the applications. It is a production-grade system and although there is a steeper learning curve it is well worth it. Each application we install is packaged as a Helm chart. All of the data is backed up regularly to an encrypted cloud S3 bucket of your choice.

### Helm Charts

The available Helm charts that this playbook completely handles the set up for are listed below.

| Package                                                                                                                 | Description                                                                                                                                                                                                                                                                                                                                                                                         |
| ----------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[Budibase](https://docs.budibase.com/self-hosting/hosting-methods/kubernetes)**                                       | [Budibase](https://docs.budibase.com/self-hosting/hosting-methods/kubernetes)                                                                                                                                                                                                                                                                                                                       |
| **[Argo](https://artifacthub.io/packages/helm/argo/argo-cd)**                                                           | Helm NEED (I thnink?)                                                                                                                                                                                                                                                                                                                                                                               |
| **[cert-manager](https://cert-manager.io/docs/installation/helm/)**                                                     | Helm NEED                                                                                                                                                                                                                                                                                                                                                                                           |
| **[Falco](https://github.com/falcosecurity/charts/tree/master/falco#introduction) NEED**                                | [Falco](https://github.com/falcosecurity/charts/tree/master/falco#introduction) NEED                                                                                                                                                                                                                                                                                                                |
| **[GitLab Runner](https://artifacthub.io/packages/helm/gitlab/gitlab-runner)**                                          | Deploys an instance of GitLab runner to a Kubernetes cluster. GitLab runner allows you to attach computers to GitLab CI workflows.                                                                                                                                                                                                                                                                  |
| **[kubequery](https://github.com/Uptycs/kubequery/)**                                                                   | [kubequery](https://github.com/Uptycs/kubequery/)                                                                                                                                                                                                                                                                                                                                                   |
| **[vaultwarden](https://artifacthub.io/packages/helm/k8s-at-home/vaultwarden)**                                         | [vaultwarden](https://artifacthub.io/packages/helm/k8s-at-home/vaultwarden)                                                                                                                                                                                                                                                                                                                         |
| **[Drone](https://github.com/drone/charts)**                                                                            | [Drone](https://github.com/drone/charts)                                                                                                                                                                                                                                                                                                                                                            |
| **[Kibana](https://artifacthub.io/packages/helm/elastic/kibana) NEED**                                                  | [Kibana](https://artifacthub.io/packages/helm/elastic/kibana) NEED                                                                                                                                                                                                                                                                                                                                  |
| **[HashiCorp Consul](https://artifacthub.io/packages/helm/hashicorp/consul)**                                           | Helm NEED                                                                                                                                                                                                                                                                                                                                                                                           |
| **[HashiCorp Vault](https://artifacthub.io/packages/helm/hashicorp/vault)**                                             | Helm NEED                                                                                                                                                                                                                                                                                                                                                                                           |
| **[HashiCorp Waypoint](https://artifacthub.io/packages/helm/hashicorp/waypoint)**                                       | Helm                                                                                                                                                                                                                                                                                                                                                                                                |
| **[Kubernetes Dashboard](https://artifacthub.io/packages/helm/k8s-dashboard/kubernetes-dashboard)**                     | Helm NEED                                                                                                                                                                                                                                                                                                                                                                                           |
| **[kube-prometheus-stack](https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack)** | Installs a collection of Kubernetes manifests, Grafana dashboards, and Prometheus rules combined with documentation and scripts to provide easy to operate end-to-end Kubernetes cluster monitoring with Prometheus using the Prometheus Operator. This Helm includes the [official Grafana Helm chart](https://artifacthub.io/packages/helm/grafana/grafana). NEED                                 |
| **[Thanos](https://artifacthub.io/packages/helm/bitnami/thanos)**                                                       | [Thanos](https://artifacthub.io/packages/helm/bitnami/thanos)                                                                                                                                                                                                                                                                                                                                       |
| **[Minio](https://artifacthub.io/packages/helm/bitnami/minio)**                                                         | Helm                                                                                                                                                                                                                                                                                                                                                                                                |
| **[Loki](https://artifacthub.io/packages/helm/grafana/loki)**                                                           | [Loki](https://artifacthub.io/packages/helm/grafana/loki)                                                                                                                                                                                                                                                                                                                                           |
| **[Kubeapps](https://kubeapps.com/) NEED**                                                                              | [Kubeapps](https://kubeapps.com/) NEED                                                                                                                                                                                                                                                                                                                                                              |
| **[Logstash](https://artifacthub.io/packages/helm/elastic/logstash)**                                                   | [Logstash](https://artifacthub.io/packages/helm/elastic/logstash)                                                                                                                                                                                                                                                                                                                                   |
| **[ElasticSearch](https://artifacthub.io/packages/helm/elastic/elasticsearch)**                                         | [ElasticSearch](https://artifacthub.io/packages/helm/elastic/elasticsearch)                                                                                                                                                                                                                                                                                                                         |
| **[n8n](https://artifacthub.io/packages/helm/open-8gears/n8n)**                                                         | [n8n](https://artifacthub.io/packages/helm/open-8gears/n8n)                                                                                                                                                                                                                                                                                                                                         |
| **[graylog](https://artifacthub.io/packages/helm/kong-z/graylog) NEED**                                                 | [graylog](https://artifacthub.io/packages/helm/kong-z/graylog) NEED                                                                                                                                                                                                                                                                                                                                 |
| **[Knative](https://artifacthub.io/packages/olm/community-operators/knative-operator) NEED**                            | [Knative](https://artifacthub.io/packages/olm/community-operators/knative-operator) NEED                                                                                                                                                                                                                                                                                                            |
| **[Fission](https://artifacthub.io/packages/helm/fission-charts/fission-all) 8**                                        | [Fission](https://artifacthub.io/packages/helm/fission-charts/fission-all) 8                                                                                                                                                                                                                                                                                                                        |
| **[Concourse](https://artifacthub.io/packages/helm/concourse/concourse) NEED**                                          | [Concourse](https://artifacthub.io/packages/helm/concourse/concourse) NEED                                                                                                                                                                                                                                                                                                                          |
| **[Nexus Repository Manager](https://artifacthub.io/packages/helm/sonatype/nexus-repository-manager)**                  | Helm                                                                                                                                                                                                                                                                                                                                                                                                |
| **[Rancher](https://artifacthub.io/packages/helm/rancher-stable/rancher)**                                              | Helm                                                                                                                                                                                                                                                                                                                                                                                                |
| **[Sentry](https://artifacthub.io/packages/helm/sentry/sentry) NEED**                                                   | [Sentry](https://artifacthub.io/packages/helm/sentry/sentry) NEED                                                                                                                                                                                                                                                                                                                                   |
| **[UniFi](https://artifacthub.io/packages/helm/k8s-at-home/unifi)**                                                     | Helm                                                                                                                                                                                                                                                                                                                                                                                                |
| **[Celium](https://docs.gitlab.com/ee/topics/autodevops/stages.html#network-policy)**                                   | NEED REQUIRED for GitLab -- see: https://docs.gitlab.com/ee/topics/autodevops/stages.html#network-policy                                                                                                                                                                                                                                                                                            |
| **[Vector](https://vector.dev/docs/setup/installation/package-managers/helm/)**                                         | [Vector](https://vector.dev/docs/setup/installation/package-managers/helm/)                                                                                                                                                                                                                                                                                                                         |
| **[Velero](https://artifacthub.io/packages/helm/vmware-tanzu/velero)**                                                  | Helm NEED                                                                                                                                                                                                                                                                                                                                                                                           |
| **[DKron](https://github.com/distribworks/dkron-helm)**                                                                 | Helm                                                                                                                                                                                                                                                                                                                                                                                                |
| **[Space Cloud](https://space-cloud.io/)**                                                                              | Waiting on someone to make a Helm                                                                                                                                                                                                                                                                                                                                                                   |
| **[Cool tools]()**                                                                                                      | https://github.com/auto-ssl/lua-resty-auto-ssl https://github.com/weaveworks/weave https://adminbro.com/ https://www.vultr.com/products/bare-metal/ https://github.com/containrrr/watchtower https://www.boundaryproject.io/ https://artifacthub.io/packages/helm/cluster-autoscaler/cluster-autoscaler https://github.com/linkerd/linkerd2 https://cilium.io/ https://github.com/porter-dev/porter |

### Host Applications

By default, on each computer provisioned using the default settings of Gas Station, several apps are installed on each host. Docker Compose is used to manage the deployment. The default apps include:

| App                                                | Description                                                                                                                                           |
| -------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[Authelia](https://www.authelia.com/)**          | An authentication portal that supports SSO and 2FA                                                                                                    |
| **[Homer](https://github.com/bastienwirtz/homer)** | A very simple homepage which is customized by the playbook to automatically include links to the Docker containers you choose to host on the computer |
| **[Portainer](https://www.portainer.io/)**         | A Docker management tool                                                                                                                              |
| **[Serve](https://github.com/vercel/serve)**       | Simple interface for viewing files located or symlinked to in the `/var/www/` folder of the machine                                                   |

You can, of course, disable deploying these apps. However, we include them because they have a small footprint and include useful features. You can also customize the list of apps you wish to include on each host.

#### HTPC

We do not maintain any of the host applications except the ones listed above. However, we do provide the capability of marking a computer being provisioned as an HTPC. Doing this will include a suite of web applications with powerful auto-downloading, organizing, tagging, and media-serving capabilities. Since most people will probably be stepping outside the confines of the law for this, it is not recommended. If you still want to experiment then you can find descriptions of the applications below. The applications are intended to be hosted on a single computer via Docker Compose. The backend for Kodi is included but you should still use the regular installation method for Plex and the front-end of Kodi to view your media collection.

| App                                                                        | Description                                                                      |
| -------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| **[WireGuard](https://docs.linuxserver.io/images/docker-wireguard)**       | Dedicated VPN for the HTPC applications                                          |
| **[Bazarr](https://docs.linuxserver.io/images/docker-bazarr)**             | Manages and automatically downloads subtitles                                    |
| **[Heimdall](https://docs.linuxserver.io/images/docker-heimdall)**         | Start page for all the HTPC apps                                                 |
| **[Jackett](https://docs.linuxserver.io/images/docker-jackett)**           | Request proxy server for Radarr and Sonarr                                       |
| **[Kodi Headless](https://hub.docker.com/r/linuxserver/kodi-headless)**    | Backend for Kodi                                                                 |
| **[Lidarr](https://docs.linuxserver.io/images/docker-lidarr)**             | Music collection manager that automatically downloads from BitTorrent and Usenet |
| **[NZBGet](https://docs.linuxserver.io/images/docker-nzbget)**             | Usenet downloader                                                                |
| **[Ombi](https://docs.linuxserver.io/images/docker-ombi)**                 | Plex request and user management system                                          |
| **[Organizr](https://docs.linuxserver.io/images/docker-htpcmanager)**      | Front end for HTPC web applications                                              |
| **[Radarr](https://docs.linuxserver.io/images/docker-radarr)**             | Automatic movie downloader                                                       |
| **[Sonarr](https://docs.linuxserver.io/images/docker-sonarr)**             | Automatic TV show downloader                                                     |
| **[Tautulli](https://docs.linuxserver.io/images/docker-tautulli)**         | Metrics and monitoring for Plex                                                  |
| **[Transmission](https://docs.linuxserver.io/images/docker-transmission)** | BitTorrent client                                                                |

<a href="#philosophy" style="width:100%"><img style="width:100%" src="https://gitlab.com/megabyte-labs/assets/-/raw/master/png/aqua-divider.png" /></a>

## Philosophy

The philosophy of this project basically boils down to "**_automate everything_**" and include the best development tools that might be useful without over-bloating the machine with services. Automating everything should include tasks like automatically accepting software terms in advance or pre-populating Portainer with certificates of all the Docker hosts you would like to control. One problem we face is that there are so many great tools offered on GitHub. A lot of research has to go into what to include and what to pass on. The decision of whether or not to include a piece of software in the default playbook basically boils down to:

- **Project popularity** - If one project has 10k stars and a similar alternative has 500 stars then 9 times of out 10 the more popular project is selected.
- **Last commit date** - We prefer software that is being actively maintained, for obvious reasons.
- **Cross platform** - Our playbook supports the majority of popular operating systems so we opt for cross-platform software. However, in some cases, we will include software that has limited cross-platform support like Xcode (which is only available on Mac OS X). If a piece of software is too good to pass up, it is added and only installed on the system(s) that support it.
- **Usefulness** - If a tool could potentially improve developer effectiveness then we are more likely to include it.
- **System Impact** - Software that can be run with a small RAM footprint and software that does not need a service to load on boot is much more likely to be included.

One of the goals of this project is to be able to re-provision a network with the click of a button. This might not be feasible since consumer-grade hardware usually does not include features like IPMI (which is a feature included in high-end motherboards that lets you control the power state remotely). However, we aim to reduce the amount of interaction required when re-provisioning an entire network down to the bare minimum. In the worst case scenario, you will have to reformat, reinstall the operating system, and ensure that OpenSSH is running (or WinRM in the case of Windows) on each of the computers in your network. However, the long term goal is to allow the user to reformat and reinstall the operating system used as your Ansible host using an automated USB installer and then automatically re-provision everything else on the network by utilizing IPMI.

You might ask, "But how can I retain application-level configurations?" We currently handle this by:

- Pre-defining dotfiles in a customizable Git repository
- Backing up to encrypted S3 buckets
- Syncing files to private git repositories
- Utilizing tools that synchronize settings like [mackup](https://github.com/lra/mackup) or [macprefs](https://github.com/clintmod/macprefs) in the case of macOS

However, we intentionally keep this synchronization to a minimum (i.e. only back up what is necessary). After all, one of the goals of this project is to be able to regularly flush the bad stuff off a system. By keeping what we back up to a minimum, we reduce the attack surface.

<a href="#architecture" style="width:100%"><img style="width:100%" src="https://gitlab.com/megabyte-labs/assets/-/raw/master/png/aqua-divider.png" /></a>

## Architecture

You can find a high-level overview of what each folder and file does in the [ARCHITECTURE.md](docs/ARCHITECTURE.md) file.

<a href="#managing-environments" style="width:100%"><img style="width:100%" src="https://gitlab.com/megabyte-labs/assets/-/raw/master/png/aqua-divider.png" /></a>

## Managing Environments

We accomplish managing different environments by symlinking all the folders that should be unique to each network environment (e.g. `host_vars/`, `group_vars/`, `inventories/`, `files/vpn/`, and `files/ssh/`). In the `environments/` folder, you will see multiple folders. In our case, `environments/dev/` contains sensible configurations for testing the playbook and its' roles. The production environment is a seperate git submodule that links to a private git repository that contains our Ansible-vaulted API keys and passwords. When you are ready to set up your production configurations, you can use this method of storing your environment-specific folders in the `environments/` folder as well. But if you are just starting off, you do not have to worry about this since, by default, this playbook is configured to run with the settings included in the `/environments/dev/` folder.

### Switching Between Environments

If you already have the project bootstrapped (i.e. already ran `bash .config/scripts/start.sh`), you can switch environments with an interactive prompt by running:

```shell
task ansible:playbook:environment
```

Alternatively, you can run the following if you would like to bypass the prompt:

```shell
task ansible:playbook:environment -- environmentName
```

<a href="#contributing" style="width:100%"><img style="width:100%" src="https://gitlab.com/megabyte-labs/assets/-/raw/master/png/aqua-divider.png" /></a>

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/megabyte-labs/Gas-Station/issues). If you would like to contribute, please take a look at the [contributing guide](https://github.com/megabyte-labs/Gas-Station/blob/master/docs/CONTRIBUTING.md).

<details>
<summary><b>Sponsorship</b></summary>
<br/>
<blockquote>
<br/>
Dear Awesome Person,<br/><br/>
I create open source projects out of love. Although I have a job, shelter, and as much fast food as I can handle, it would still be pretty cool to be appreciated by the community for something I have spent a lot of time and money on. Please consider sponsoring me! Who knows? Maybe I will be able to quit my job and publish open source full time.
<br/><br/>Sincerely,<br/><br/>

**_Brian Zalewski_**<br/><br/>

</blockquote>

<a title="Support us on Open Collective" href="https://opencollective.com/megabytelabs" target="_blank">
  <img alt="Open Collective sponsors" src="https://img.shields.io/opencollective/sponsors/megabytelabs?logo=opencollective&label=OpenCollective&logoColor=white&style=for-the-badge" />
</a>
<a title="Support us on GitHub" href="https://github.com/ProfessorManhattan" target="_blank">
  <img alt="GitHub sponsors" src="https://img.shields.io/github/sponsors/ProfessorManhattan?label=GitHub%20sponsors&logo=github&style=for-the-badge" />
</a>
<a href="https://www.patreon.com/ProfessorManhattan" title="Support us on Patreon" target="_blank">
  <img alt="Patreon" src="https://img.shields.io/badge/Patreon-Support-052d49?logo=patreon&logoColor=white&style=for-the-badge" />
</a>

</details>

<a href="#license" style="width:100%"><img style="width:100%" src="https://gitlab.com/megabyte-labs/assets/-/raw/master/png/aqua-divider.png" /></a>

## License

Copyright © 2020-2021 [Megabyte LLC](https://megabyte.space). This project is [MIT](https://gitlab.com/megabyte-labs/gas-station/-/blob/master/LICENSE) licensed.
