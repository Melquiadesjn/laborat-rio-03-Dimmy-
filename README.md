
## Objetivos

1. Implementar o **Look-Ahead Mask** (mascaramento causal)
2. Implementar a **Cross-Attention** (ponte Encoder → Decoder)
3. Simular o **loop de inferência auto-regressiva**

## Estrutura

```
lab3_decoder/
├── tarefa1_causal_mask.py     # Look-Ahead Mask
├── tarefa2_cross_attention.py # Cross-Attention Encoder-Decoder
├── tarefa3_autoregressive.py  # Loop de inferência auto-regressiva
└── main.py                    # Executa as três tarefas em sequência
```

## Execução

```bash
python main.py
```

## Dependências

- Python 3.x
- NumPy
