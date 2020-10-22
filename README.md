# gitjacker

[![Travis Build Status](https://travis-ci.org/liamg/gitjacker.svg?branch=master)](https://travis-ci.org/liamg/gitjacker)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Ftrentontemple%2Fgitjacker.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Ftrentontemple%2Fgitjacker?ref=badge_shield)

Gitjacker downloads git repositories and extracts their contents from sites where the `.git` directory has been mistakenly uploaded. It will still manage to recover a significant portion of a repository even where directory listings are disabled.

For educational/penetration testing use only.

More information at [https://liam-galvin.co.uk/security/2020/09/26/leaking-git-repos-from-misconfigured-sites.html](https://liam-galvin.co.uk/security/2020/09/26/leaking-git-repos-from-misconfigured-sites.html)

![Demo Gif](demo.gif)

## Installation

```bash
curl -s "https://raw.githubusercontent.com/liamg/gitjacker/master/scripts/install.sh" | bash
```

...or grab a [precompiled binary](https://github.com/liamg/gitjacker/releases).

You will need to have `git` installed to use Gitjacker.


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Ftrentontemple%2Fgitjacker.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Ftrentontemple%2Fgitjacker?ref=badge_large)