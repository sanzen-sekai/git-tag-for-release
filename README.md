# git-tag-for-release

create version tag, and push remote

## Usage

```bash
git tag-for-release <remote> [-m] [-p] [-b]
```

options

* <remote> : target remote name
* no option : minor version up
* -m : major version up
* -p : patch version up
* -b : beta version up: minor 999's patch version up

## Installation

```bash
git clone https://github.com/sanzen-sekai/git-tag-for-release.git
export PATH=$PATH:/path/to/git-tag-for-release/bin
```
