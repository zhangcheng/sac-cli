# Slides as Code CLI

`sac` command line is used to:
- install, update, delete Slides as Code themes on your computer
- develop slides deck
- share slides

# Demo
[Check out the live demo.](https://sacproj.github.io/demo/)

# Usage
```
Usage: sac <command>

Available commands:
  doctor      Show information about the installed tooling
  theme       Theme management
  deck        Deck management
  slide       Slide management
```

## Theme Management
```
Theme sub-commands
  list <owner>/<theme> [<version>]    List theme from GitHub
  install                             Install theme
    github <owner>/<theme>            Install theme from Github latest release
    git <git> [<tag>]                 Install theme from Git URL (with optional <tag>)
    tarball <tarball>                 Install theme from tarball
  installed                           List installed themes and versions
  remove <theme> <version>            Remove installed <theme>/<version>
```

## Deck Management
```
Deck sub-commands
  new <deck-directory> <theme>...     Create a new slides deck with themes
  code                                Serve slides deck with live updates
  html                                Build slides deck in HTML into public directory
  pdf [<pdf>] [<timeout>]             Build slides deck in PDF (default <pdf>=slides.pdf <timeout>=10000)
```

## Slide Management
```
Slide sub-commands
  new <slide-name.md>                 Create a new slide
```

# Project Management
This project adheres to:
- [Developer Certificate of Origin](https://developercertificate.org/)
- [Conventional Commit Messages](https://www.conventionalcommits.org/en/v1.0.0/)
- [Semantic Versioning](https://semver.org/spec/v2.0.0.html)
- [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

# Authors
Developed with passion by Stéphane Este-Gracias and great open source [contributors](https://github.com/sacproj/sac-cli/graphs/contributors).

# License
sac's code is released under [MIT license](LICENSE).

# Acknowledgments
- [Data Essential](https://www.data-essential.com/) to give me the time to develop this project.
