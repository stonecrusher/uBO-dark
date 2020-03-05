# uBO-dark
Additional CSS to ShadowFox - rewrite

See [here](https://github.com/stonecrusher/ShadowFox/blob/patch-1/css/userContent-files/webextension-tweaks/ublock_origin.css) for the current working version (replace `uBlock0@raymondhill.net` with your uBO UUID as seen at `about:debugging` --> `This Firefox`).

Unfinished attempt to rewrite dark uBO.

Took all the original uBO css and filtered everything that relates to colors.
Unfortunately it's no find and replace job as uBO has a mess of a color palette (57 unique colors).

further tasks:
- check for updates in the original project
- reduce color palette a lot (maybe push to upstream)
- replace colors with variables
- set dark colors for those variables
- check contrast / readability
- don't forget colorblind mode
