# dependencies-completion

<div align="right">
  Language:
  🇺🇸
  <a title="Chinese" href="README-CN.md">🇨🇳</a>
</div>

This is an Android Studio / IntelliJ IDEA plugin for search and complete dependencies from google() and mavenCentral()
in Gradle projects.

This project base on [android-dependencies-completion](https://github.com/HitenDev/android-dependencies-completion) ,
reference project [TranslationPlugin](https://github.com/YiiGuxing/TranslationPlugin).

> This plugin is inspired by [android-dependencies-completion](https://github.com/HitenDev/android-dependencies-completion) and uses some of its source code.

## Features

- support [google](https://maven.google.com) and [mavenCentral](https://search.maven.org)
  and <font color="red">**nexus**</font>，include android's `jetpack`/`androidx`/`support` packages.
- <font color="red">support add custom repository.</font>
- support generating variable and custom variable.
- dependencies variable offline covert.
- simple and clear UI.

## Installation

- Plugin website:
- Download file: https://github.com/RootCluster/dependencies-completion/releases

## Usage

**Settings**
：<kbd>Code Completion</kbd> -> <kbd>SmartType Completion</kbd> -> <kbd>Smart Type Completion（Enabled）</kbd>

**Default Shortcut Key**

- macOS：<kbd>^(control)</kbd> + <kbd>⇧(shift)</kbd> + <kbd>Space</kbd>
- Windows：<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Space</kbd>
- Linux：<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Space</kbd>

*All the following operations are manual, please note.*

## Normal Operation

1. input dependencies info in `xxx.gradle` file
2. then press `Shortcut Key` (eg：<kbd>^(control)</kbd> + <kbd>⇧(shift)</kbd> + <kbd>Space</kbd>)

## Generating Variable

1. append placeholder
    - append `'#'` to the end of the input string will generate a version variable
    - append `'##'` to the end of the input string will generate a full variable
2. then press `Shortcut Key`

## Custom Variable

1. append placeholder
    - append `'#'+custom` to the end of the input string will generate a version variable
    - append `'##'+custom` to the end of the input string will generate a full variable
2. then press `Shortcut Key`

## License

dependencies-completion is Open Source software plugins released under
the [MIT License](https://opensource.org/licenses/MIT).


