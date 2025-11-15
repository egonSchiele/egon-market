# egon-market

This is a Claude plugin marketplace with a bunch of plugins available. To use it, you need to first add the marketplace:

```
/plugin marketplace add egonSchiele/egon-market
```

then you can install plugins:

```
/plugin install greeting@egon-market
```

Marketplace docs:
https://code.claude.com/docs/en/plugin-marketplaces

Note, I have found that uninstalling or updating plug-ins or marketplaces is quite buggy. If you are not able to do so, you can simply start over using:

```bash
cd .claude
rm -rf plugins
```

You may also need to edit `enabledPlugins` in `.claude/settings.json`.