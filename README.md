# flake-hub-example

Smallest repo [flake-hub](https://github.com/Fomiller/flake-hub) can manage:
`golden-base` plus `golden-github`. No language, no service, no infra.

Everything except this file, `flake.nix` and `repo.nix` is generated. The
header at the top of a generated file names the pack that owns it.

To change something, edit `repo.nix` and run:

```sh
nix run .#generate
```

Docs: https://fomiller.github.io/flake-hub/
