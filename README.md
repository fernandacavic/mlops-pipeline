# mlops-pipeline

Autor: Fernanda Cavicchioli Zola



## Estrutura

```
mlops-pipeline/
├── data/
│   └── raw/
│       └── points.csv       # gerado pelo generate_data.py
├── src/
│   ├── data.py              # carregamento e preparação dos dados
│   ├── train.py             # treinamento do modelo
│   ├── evaluate.py          # avaliação do modelo
│   └── predict.py           # predição
├── outputs/
│   └── metrics.json         # gerado pelo main.py
├── generate_data.py
├── main.py
└── requirements.txt
```

## Como executar

1. Instalar dependências:
   ```bash
   pip install -r requirements.txt
   ```

2. Gerar os dados:
   ```bash
   python generate_data.py
   ```

3. Implementar os módulos em `src/` 

4. Executar o pipeline:
   ```bash
   python main.py
   ```

## Como subir no GitHub

```bash
git init
git add .
git commit -m "exercicio de modularizacao"
git remote add origin https://github.com/fernandacavic/mlops-pipeline.git
git push -u origin main
```


