# flake-hub-example

Smallest repo [flake-hub](https://github.com/Fomiller/flake-hub) can manage:
`golden-base` plus `golden-github`. No language, no service, no infra.

Everything except this file, `AGENTS.md`, `flake.nix` and `repo.nix` is
generated. The header at the top of a generated file names the pack that owns
it. This file and `AGENTS.md` are scaffold: written once, then left alone.

To change something, edit `repo.nix` and run:

```sh
nix run .#generate
```

Docs: https://fomiller.github.io/flake-hub/
