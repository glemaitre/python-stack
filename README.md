# python-stack

Experimental development environment managed using `pixi` workspace.

## Getting started

Install `pixi` as indicated at https://pixi.sh/latest/

Then, you can clone all repositories using:

```shell
pixi run --as-is clone-all
```

Then, each folder has its own `pixi.toml` manifest that depends on other folders.
There is a top-level `pixi.toml` and you can use the libraries from the stack using:

```shell
pixi shell -e source
cd scratch
jupyter-lab
```
