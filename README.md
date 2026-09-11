# Python Fundamentals

Fundamentos de Python e os principais conceitos de Programação Orientada a Objetos (POO).

Este repositório reúne materiais de estudo, exemplos práticos e exercícios que podem ser utilizados tanto para consulta pessoal quanto por outras pessoas que estejam aprendendo Python.

## Conteúdos

- Sintaxe, variáveis e tipos de dados
- Operadores e estruturas condicionais
- Listas, tuplas, conjuntos e dicionários
- Strings e processamento de texto
- Laços de repetição e compreensões
- Funções, módulos e tipagem
- Manipulação de arquivos, JSON e CSV
- Tratamento de exceções
- Classes, objetos e encapsulamento
- Herança, abstração, composição e polimorfismo
- Projeto prático usando POO

## Estrutura

Os estudos estão organizados em 10 notebooks:

1. [`01-primeiros-passos.ipynb`](./notebooks/01-primeiros-passos.ipynb): sintaxe, variáveis, tipos, conversões, entrada, saída e operadores
2. [`02-controle-de-fluxo.ipynb`](./notebooks/02-controle-de-fluxo.ipynb): comparações, lógica booleana, condicionais, `match` e `while`
3. [`03-colecoes.ipynb`](./notebooks/03-colecoes.ipynb): listas, tuplas, conjuntos e dicionários
4. [`04-strings.ipynb`](./notebooks/04-strings.ipynb): manipulação, validação e formatação de textos
5. [`05-lacos-e-compreensoes.ipynb`](./notebooks/05-lacos-e-compreensoes.ipynb): `for`, `range`, `enumerate`, `zip`, compreensões e geradores
6. [`06-funcoes-modulos-e-tipagem.ipynb`](./notebooks/06-funcoes-modulos-e-tipagem.ipynb): funções, parâmetros, escopo, módulos e type hints
7. [`07-arquivos-excecoes-e-contextos.ipynb`](./notebooks/07-arquivos-excecoes-e-contextos.ipynb): arquivos, JSON, CSV, exceções e gerenciadores de contexto
8. [`08-poo-classes-e-objetos.ipynb`](./notebooks/08-poo-classes-e-objetos.ipynb): classes, objetos, propriedades, métodos especiais e dataclasses
9. [`09-poo-heranca-composicao-e-polimorfismo.ipynb`](./notebooks/09-poo-heranca-composicao-e-polimorfismo.ipynb): herança, abstração, composição e polimorfismo
10. [`10-projeto-final-biblioteca.ipynb`](./notebooks/10-projeto-final-biblioteca.ipynb): sistema de biblioteca integrando os conceitos estudados

Cada notebook possui explicações, exemplos executáveis, exercícios e soluções sugeridas. Os arquivos podem ser estudados em sequência ou consultados individualmente por tema.

## Tecnologias

- Python 3.10 ou superior
- Jupyter Notebook ou JupyterLab
- Biblioteca padrão do Python

## Como executar

Clone o repositório:

```bash
git clone https://github.com/agathalafaiety/python-fundamentals.git
cd python-fundamentals
```

Crie um ambiente virtual:

```bash
python -m venv .venv
```

Ative o ambiente no Windows:

```powershell
.venv\Scripts\Activate.ps1
```

No Linux ou macOS:

```bash
source .venv/bin/activate
```

Instale o JupyterLab e inicie o ambiente:

```bash
python -m pip install -r requirements.txt
jupyter lab
```

Os notebooks também podem ser abertos pelo VS Code com a extensão Jupyter ou visualizados diretamente no GitHub.

##
Desenvolvido por [Agatha Lafaiety](https://github.com/agathalafaiety).
