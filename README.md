## Dependências externas

Os notebooks de árvores de decisão usam o executável `dot`, fornecido pelo
[Graphviz](https://graphviz.org/). Essa dependência não é instalada pelo `uv`.

No macOS, instale-a com:

```bash
brew install graphviz
```

Verifique a instalação com:

```bash
dot -V
```
