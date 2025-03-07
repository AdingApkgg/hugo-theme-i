# hugo-theme-i

A responsive and minimalist Hugo theme designed for simplicity and flexibility. Perfect for those who value clean design and are open to frequent, bold layout changes with each update. Stay ahead with a theme that evolves with your needs.

## Install or Update

- Themes reside in `iHugo/themes` directory.
- `i` will be installed in `iHugo/themes/i`

**INSTALL** : Inside the folder of your Hugo site `iHugo`, run:

```sh
git submodule add --depth=1 https://github.com/AdingApkgg/hugo-theme-i.git themes/i
git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)

```

Read more about git submodules [here](https://www.atlassian.com/git/tutorials/git-submodule).

**UPDATE**: Inside the folder of your Hugo site `iHugo`, run:

```sh
git submodule update --remote --merge

```

Finally set theme as `i` in your site config

In `hugo.toml` add:

```yaml
theme = 'i'

```
