# Projeto-Pratico-2.2

## Estrutura do projeto

```
Projeto-Pratico-2.2/
├── Bibliografias/
│   ├── Brink - Real-World Machine Learning.pdf
│   ├── Koklu - Multiclass classification of dry beans using computer vision and machine learning techniques.pdf
│   └── Palit - Computational Intelligence in Time Series Forecasting.pdf
├── DryBeanDataset/                 
│   ├── Dry_Bean_Dataset.arff
│   ├── Dry_Bean_Dataset.txt
│   └── Dry_Bean_Dataset.xlsx
├── Notebooks/
│   ├── PP2.2.1 - Conhecendo o Conjunto de Dados.ipynb
│   ├── PP2.2.2 - Proposição e Avaliação de RNAs.ipynb
│   └── PP2.2.3 - Validação Cruzada e Busca em Grade.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

| Pasta / arquivo | Conteúdo |
|---|---|
| `Bibliografias/` | Referências de apoio: artigo de origem da base (Koklu e Ozkan, 2020), livros da disciplina |
| `DryBeanDataset/` | Base de dados *Dry Bean Dataset* nos formatos `.xlsx` (usado nos notebooks), `.arff` e a documentação `.txt` |
| `Notebooks/` | Notebooks das três etapas do Projeto Prático 2.2 |
| `requirements.txt` | Dependências Python do projeto |

### Base de dados

A pasta `DryBeanDataset/` está no `.gitignore` e não foi para o repositório. Para executar os notebooks, baixar a base em <https://archive.ics.uci.edu/dataset/602/dry+bean> e extrair os arquivos nessa pasta, na raiz do projeto. Os notebooks leem a base pelo caminho relativo `../DryBeanDataset/Dry_Bean_Dataset.xlsx`.
