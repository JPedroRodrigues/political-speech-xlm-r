# Aplicação do Modelo Multilíngue XLM-RoBERTa na Análise e Identificação de Grupos de Similaridade de Discursos Políticos
Repositório destinado à aplicação do modelo XLM-RoBERTa na geração de embeddings e análise de similaridade entre discursos de membros da Câmara dos Deputados do Brasil.

## Identificação

| Nome | RA |
| --- | --- |
| João Pedro Rodrigues Vieira | 10403595 |

## Como Executar Localmente

Para executar este projeto localmente, é recomendável a criação de um ambiente virtual em Python. Supondo que a ambientação é feita em um sistema Linux, basta executar os seguintes comandos:

> Caso o Sistema Operacional (SO) não seja Linux, verifique a [documentação oficial do Python](https://docs.python.org/3/library/venv.html) para compreender as particularidades deste processo em seu SO.

### Criação do Ambiente Virtual

Aqui, é feita a criação da pasta `.venv/`, que condensará o ambiente virtual recém criado.

```sh
python3 -m venv .venv
```

### Execução do Ambiente

```sh
source .venv/bin/activate
```

### Instalação das Dependências

Todas as dependências utilizadas para a execução do notebook deste projeto são listadas no arquivo `requirements.txt`. Para instalar cada uma delas, basta executar:

```sh
pip install -r requirements.txt
```