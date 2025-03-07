# Niina's notes

## Install

With uv

```bash
uv tool install mkdocs
uvx mkdocs new notes && cd notes
uv init .
source .venv/bin/activate.fish # it's up to your shell
rm ./main.py

git clone https://github.com/TonyCrane/mkdocs-toolchain.git
uv add mkdocs-toolchain/mkdocs-toc-plugin/
uv add git+https://github.com/KinnariyaMamaTanha/mkdocs-statistics-plugin.git
```
