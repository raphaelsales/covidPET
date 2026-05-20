# Perfil epidemiológico da COVID-19 no Estado do Tocantins

Este repositório reúne scripts em **Python** e materiais auxiliares para análise do perfil epidemiológico da COVID-19 no **Estado do Tocantins**, com foco na influência de **condições socioeconômicas** e **qualidade da atenção à saúde**.

> **Título do projeto**: Perfil Epidemiológico da COVID-19 no Estado do Tocantins: a influência da situação socioeconômica e da qualidade da atenção à saúde.

## Objetivos

- Consolidar e preparar bases de dados epidemiológicas e (quando aplicável) socioeconômicas.
- Produzir análises descritivas (tabelas, séries temporais, indicadores) para apoiar o estudo.
- Gerar visualizações e/ou relatórios reprodutíveis a partir dos dados processados.

## Estrutura sugerida do repositório

> A estrutura pode variar conforme a organização atual do projeto.

- `data/` – dados brutos e/ou processados *(recomendado não versionar dados sensíveis; usar `.gitignore`)*
- `notebooks/` – análises exploratórias em Jupyter Notebooks
- `src/` – módulos e funções reutilizáveis
- `reports/` – figuras, tabelas e relatórios exportados
- `requirements.txt` – dependências do Python

## Requisitos

- Python 3.10+ (recomendado)

Instale as dependências (se houver `requirements.txt`):

```bash
pip install -r requirements.txt
```

## Como executar

Como o repositório pode conter diferentes scripts/notebooks, seguem exemplos comuns.

### Jupyter Notebook

```bash
pip install jupyter
jupyter notebook
```

### Scripts Python

```bash
python caminho/do/script.py
```

## Dados

- Verifique a pasta `data/` (caso exista) para entender o formato e a origem dos dados.
- Se os dados não estiverem no repositório (por tamanho, licenças ou privacidade), documente aqui como obtê-los.

## Reprodutibilidade

Para facilitar a reprodutibilidade:

- Prefira manter transformações de dados em scripts versionados.
- Fixe versões das dependências (`requirements.txt` ou `poetry.lock`).
- Registre parâmetros e fontes de dados usadas em cada análise.

## Como citar

Se você utilizar este repositório em trabalhos acadêmicos, recomendamos citar o projeto e/ou incluir o link do repositório.

## Contribuição

Contribuições são bem-vindas!

1. Faça um fork do repositório
2. Crie uma branch (`git checkout -b minha-feature`)
3. Commit suas alterações (`git commit -m "Minha feature"`)
4. Push para a branch (`git push origin minha-feature`)
5. Abra um Pull Request

## Licença

Defina a licença do projeto (por exemplo, MIT, GPL-3.0, CC BY 4.0). Se ainda não houver, adicione um arquivo `LICENSE`.
