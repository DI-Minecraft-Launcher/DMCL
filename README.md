# DI Minecraft Launcher

## Introduction

DMCL is a Minecraft launcher which supports Mod management, game customizing, auto installing(Forge, LiteLoader and OptiFine), modpack creating, UI customizing and so on.

No plugin API is provided.

## Download
Download the latest version [from the official website](https://hmcl.huangyuhui.net/download)

Note: Github releases are outdated.

## License
The software is distributed under [GPL v3](https://www.gnu.org/licenses/gpl-3.0.html) with additional terms.


## Contribution

If you want to submit a pull request, there're some requirements:
* IDE: Intellij IDEA.
* Compiler: Java 1.8.
* Do NOT modify `gradle` files.

## JVM Options (for debugging)
|Parameter|Description|
|---------|-----------|
|`-Dhmcl.self_integrity_check.disable=true`|Bypass the self integrity check when checking for update.|
|`-Dhmcl.version.override=<version>`|Override the version number.|
|`-Dhmcl.update_source.override=<url>`|Override the update source.|
|`-Dhmcl.authlibinjector.location=<path>`|Use specified authlib-injector (instead of downloading one).|

## Copyright
This Minecraft Launcher is based on HMCL.

Copyright © 2019-2020 DIstudio

Copyright © 2019-2020 帝圣君丶
