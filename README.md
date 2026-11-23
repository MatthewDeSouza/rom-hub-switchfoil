# rom-hub-switchfoil

A [ROM Hub](https://github.com/BlizzHacker/rom-hub) plugin for
[ROMarr](https://github.com/BlizzHacker/romarr) that searches Tinfoil and
CyberFoil shops, such as a self-hosted [Ownfoil](https://github.com/a1ex4/ownfoil),
and hands Nintendo Switch files to ROMarr's import. It ships with no sources.
Configure only shops you run or are authorised to use.

The plugin is under development and is not yet in the ROM Hub catalogue.

## Development

The Nix flake provides Python 3.12 with ROM Hub at the revision ROMarr's
Docker image pins, along with `just`, `ruff` and `gh`.

```bash
nix develop
nix flake check
```

## Licence

MIT. See `LICENSE`.
