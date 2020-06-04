# Volcano

A shitty plugin loader for [Obsidian](https://obsidian.md/). **No Linux support currently.**

I hacked this together in a few hours because there's currently no way to load your own plugins, I'll probably archive this when the awesome Obsidian team opens up an official API.

## Installation

Until I stop being lazy and add packing, you'll need [Node.js](https://nodejs.org/) to install Volcano. Once it's installed, run the following in a terminal:

```
npm install -g @kognise/volcano
```

Then, run `volcano` to inject the plugin loader into the Obsidian executable. You'll have to re-run this whenever Obsidian updates.

## Plugins

Plugins are stored in the form of JavaScript files in the `~/volcano/plugins/` directory. See the wiki (TODO) for more information on writing plugins.