# GBrain Knowledge Graph

Knowledge graph extraído do repositório [GBrain](https://github.com/garrytan/gbrain) via [Graphify](https://github.com/graphifyy/graphify).

## Sobre

- **Arquivos processados**: 679 arquivos `.ts`
- **Nós**: 7.495
- **Arestas**: 19.785
- **Tamanho**: 7.1 MB
- **Data**: 2026-06-07
- **Atualização**: Automática (cron 1º e 15 de cada mês às 4h BRT)

## Hubs principais

| Nó | Conexões |
|---|---|
| `core_engine` | 352 |
| `BrainEngine` | 325 |
| `ai_gateway` | 230 |

## Estrutura

```
graphify-out/
└── graph.json   # Knowledge graph completo (JSON)
```

## Uso

O `graph.json` pode ser importado no [Graphify](https://github.com/graphifyy/graphify) ou processado via script Python para análise de dependências.
