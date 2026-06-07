# GBrain Knowledge Graph — Graphify Output

> Knowledge graph extraído do repositório [GBrain](https://github.com/garrytan/gbrain) via [Graphify](https://github.com/graphifyy/graphify) • Atualizado automaticamente (dias 1 e 15 de cada mês, 4h BRT)

## Stats (2026-06-07)

| Métrica | Valor |
|---|---|
| Arquivos `.ts` processados | 679 |
| Nós | 7.495 |
| Arestas | 19.785 |
| Tamanho (JSON) | 7.1 MB |
| Tamanho (gzip) | 387 KB |

## Top Hubs

| Nó | Conexões |
|---|---|
| `core_engine` | 352 |
| `BrainEngine` | 325 |
| `ai_gateway` | 230 |
| `doctor` | 122 |

## Estrutura

```
graphify-out/
├── graph.json.gz   # Knowledge graph comprimido (gzip -9)
└── metadata.json   # Estatísticas e metadados da extração
```

## Como usar

### Descomprimir
```bash
gunzip -k graphify-out/graph.json.gz
# → graphify-out/graph.json (7.1MB)
```

### Visualizar com Graphify
```bash
pip install graphifyy
graphify view graphify-out/graph.json
```

### Processar com Python
```python
import gzip, json
with gzip.open("graphify-out/graph.json.gz") as f:
    graph = json.load(f)
print(f"Nodes: {len(graph['nodes'])}, Edges: {len(graph['edges'])}")
```

## Backup
Google Drive: [Ver no Drive](https://drive.google.com/file/d/15R0bCZ2h7rGBMeBXZA21_l3vNy9yKbNe/view)
