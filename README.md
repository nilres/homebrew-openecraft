# Homebrew tap of OpenECraft

[OpenECraft](https://openecraft.org/) is an open source electrical CAE editor:
schematics, reports and panel layout in 3D.

```bash
brew install --cask nilres/openecraft/openecraft
```

The cask installs the editor and the parts manager from the disk image of the
[GitHub release](https://github.com/nilres/OpenECraft/releases), and links
`openecraft-cli` (command line and MCP server), `openecraft-parts-server` and
`openecraft-project-server`. The apps are not notarized yet, so Gatekeeper asks once on
the first start (System Settings > Privacy & Security > Open Anyway).

The source of the cask is `installer/stores/homebrew/` of the
[OpenECraft repository](https://github.com/nilres/OpenECraft); issues go there.
