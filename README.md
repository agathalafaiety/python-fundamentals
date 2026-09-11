# Python Fundamentals

Trilha prática e progressiva para aprender os fundamentos de Python e os principais conceitos de Programação Orientada a Objetos (POO).

O projeto contém 10 notebooks executáveis, com explicações, exemplos, exercícios e soluções sugeridas. Todos os exemplos usam apenas a biblioteca padrão do Python.

## Trilha de estudos

| # | Notebook | Principais conceitos |
| --- | --- | --- |
| 01 | [Primeiros passos](./notebooks/01-primeiros-passos.ipynb) | Sintaxe, variáveis, tipos, conversões, entrada, saída e operadores |
| 02 | [Controle de fluxo](./notebooks/02-controle-de-fluxo.ipynb) | Comparações, lógica booleana, condicionais, `match`, `while`, `break` e `continue` |
| 03 | [Coleções](./notebooks/03-colecoes.ipynb) | Listas, tuplas, conjuntos, dicionários, mutabilidade e estruturas aninhadas |
| 04 | [Strings](./notebooks/04-strings.ipynb) | Fatiamento, métodos, validação, formatação, Unicode e expressões regulares |
| 05 | [Laços e compreensões](./notebooks/05-lacos-e-compreensoes.ipynb) | `for`, `range`, `enumerate`, `zip`, compreensões e geradores |
| 06 | [Funções, módulos e tipagem](./notebooks/06-funcoes-modulos-e-tipagem.ipynb) | Parâmetros, retorno, escopo, `lambda`, type hints, módulos e recursão |
| 07 | [Arquivos e exceções](./notebooks/07-arquivos-excecoes-e-contextos.ipynb) | `pathlib`, arquivos, JSON, CSV, exceções e gerenciadores de contexto |
| 08 | [POO: classes e objetos](./notebooks/08-poo-classes-e-objetos.ipynb) | Classes, instâncias, encapsulamento, propriedades, métodos especiais e dataclasses |
| 09 | [POO: herança e polimorfismo](./notebooks/09-poo-heranca-composicao-e-polimorfismo.ipynb) | Herança, composição, abstração, polimorfismo e duck typing |
| 10 | [Projeto final: biblioteca](./notebooks/10-projeto-final-biblioteca.ipynb) | Projeto integrado com regras de negócio, POO, exceções, pesquisa, JSON e testes |

## Estrutura

```text
python-fundamentals/
├── notebooks/
│   ├── 01-primeiros-passos.ipynb
│   ├── 02-controle-de-fluxo.ipynb
│   ├── 03-colecoes.ipynb
│   ├── 04-strings.ipynb
│   ├── 05-lacos-e-compreensoes.ipynb
│   ├── 06-funcoes-modulos-e-tipagem.ipynb
│   ├── 07-arquivos-excecoes-e-contextos.ipynb
│   ├── 08-poo-classes-e-objetos.ipynb
│   ├── 09-poo-heranca-composicao-e-polimorfismo.ipynb
│   └── 10-projeto-final-biblioteca.ipynb
├── .gitignore
├── requirements.txt
└── README.md
```

## Pré-requisitos

- Python 3.10 ou superior;
- `pip` para instalar o JupyterLab.

## Instalação

Clone o repositório e entre na pasta:

```bash
git clone https://github.com/agathalafaiety/python-fundamentals.git
cd python-fundamentals
```

Crie e ative um ambiente virtual.

No Windows:

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

No Linux ou macOS:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Instale e abra o JupyterLab:

```bash
python -m pip install -r requirements.txt
jupyter lab
```

Também é possível abrir os notebooks diretamente no VS Code com a extensão Jupyter.

## Como estudar

1. Siga os notebooks na ordem numérica.
2. Execute as células de cima para baixo.
3. Altere os exemplos e observe os resultados.
4. Resolva cada seção **Pratique** antes de consultar a solução sugerida.
5. No projeto final, implemente os desafios propostos para consolidar o aprendizado.

## O que você será capaz de fazer

Ao concluir a trilha, você terá praticado:

- os tipos e estruturas essenciais da linguagem;
- decisões, repetições, funções e organização de código;
- leitura, escrita e serialização de dados;
- tratamento de erros e validação de regras;
- modelagem orientada a objetos;
- criação de um pequeno sistema completo e testável.

## Autoria

Desenvolvido por [Agatha Lafaiety](https://github.com/agathalafaiety).
