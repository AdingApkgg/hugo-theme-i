# hugo-theme-i

Easily & powerful theme for Hugo engine.

## Install or Update

- Themes reside in `iHugo/themes` directory.
- `i` will be installed in `iHugo/themes/i`

**INSTALL** : Inside the folder of your Hugo site `iHugo`, run:

```sh
git submodule add --depth=1 https://github.com/AdingApkgg/hugo-theme-i.git themes/PaperMod
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
