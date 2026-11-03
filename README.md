# Capo-Light for JetBrains IDEs

The Capo-Light editor colors from the [Capo-Light VS Code theme](https://github.com/gerane/VSCodeThemes) by gerane, with the VS Code light workbench colors around them. Works in Android Studio, IntelliJ IDEA, WebStorm and any other JetBrains IDE on 2023.3 or later.

## Install

1. Download `capo-light-theme.jar` from the latest release.
2. In the IDE, open Settings → Plugins → ⚙ → Install Plugin from Disk and pick the jar.
3. Restart, then choose Capo-Light under Settings → Appearance & Behavior → Appearance.

Choosing the theme also switches the editor color scheme to Capo-Light.

## Build

```sh
zip -r capo-light-theme.jar META-INF Capo-Light.theme.json Capo-Light.icls
```
