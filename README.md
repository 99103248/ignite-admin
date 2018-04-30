![](https://github.com/go-ignite/ignite-admin/raw/master/snapshots/ignite-admin.png)
---

[![Release](http://github-release-version.herokuapp.com/github/go-ignite/ignite-admin/release.svg?style=flat)](https://github.com/go-ignite/ignite-admin/releases/latest)
[![Go Report Card](https://goreportcard.com/badge/github.com/go-ignite/ignite-admin)](https://goreportcard.com/report/github.com/go-ignite/ignite-admin)
[![Chat Telegram](https://img.shields.io/badge/chat-telegram-brightgreen.svg)](https://t.me/joinchat/FuddvBLqni3u5wJmNwnc0w)
[![Microbadger Image](https://images.microbadger.com/badges/image/goignite/ignite-admin.svg)](https://microbadger.com/images/goignite/ignite-admin)
[![DUB](https://img.shields.io/dub/l/vibe-d.svg)](https://github.com/go-ignite/ignite-admin/blob/master/LICENSE)

Admin panel for go-ignite.

* [Features](#features)
* [Snapshots](#snapshots)
* [Install](#install)
* [Build](#build)
* [Contributing](#contributing)
* [License](#license)

# Features

* User account is activated by unique invitation code.
* You can create multiple invitation codes by batch operation.
* User's account will be suspended automatically by background job if it exceeds the max bandwidth limit or the expired date.
* Stop / Reset / Destroy docker server by one-click.

# Snapshots

![https://github.com/go-ignite/ignite-admin/raw/master/snapshots/1.png](https://github.com/go-ignite/ignite-admin/raw/master/snapshots/1.png)

![https://github.com/go-ignite/ignite-admin/raw/master/snapshots/2.png](https://github.com/go-ignite/ignite-admin/raw/master/snapshots/2.png)

![https://github.com/go-ignite/ignite-admin/raw/master/snapshots/3.png](https://github.com/go-ignite/ignite-admin/raw/master/snapshots/3.png)

![https://github.com/go-ignite/ignite-admin/raw/master/snapshots/4.png](https://github.com/go-ignite/ignite-admin/raw/master/snapshots/4.png)

![https://github.com/go-ignite/ignite-admin/raw/master/snapshots/5.png](https://github.com/go-ignite/ignite-admin/raw/master/snapshots/5.png)

# Install

Please refer to [《ignite中文安装指南》](https://github.com/go-ignite/ignite/wiki)

# Build

To build ignite-admin, you need to prepare your Go development environment first, then follow the steps:

* Clone ignite to your go workspace
* Use ```yarn && yarn build``` to build frontend pages and resources in `/fe`.
* Use ```go build``` to build ignite-admin program.
* Rename conf/config-temp.toml to conf/config.toml and config it.
* Run it.

# Contributing

Pull request is welcome!

* Fork ignite-admin
* Clone it: ```git clone https://github.com/yourname/ignite-admin```
* Create your feature branch: ```git checkout -b my-new-feature```
* Make changes and add them: ```git add .```
* Commit changes: ```git commit -m "Add some feature"```
* Push your commits: ```git push origin my-new-feature```
* Create pull request

# License
[MIT License](https://github.com/go-ignite/ignite-admin/blob/master/LICENSE)
