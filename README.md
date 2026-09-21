# 🍔 Sistema de Pedido – Lanchonete

Sistema simples de pedidos para lanchonetes desenvolvido em **Python**, executado via terminal.

O projeto simula o processo de realização de um pedido, permitindo selecionar produtos, informar quantidades, calcular valores, aplicar cupons de desconto e simular diferentes formas de pagamento.

## 📋 Funcionalidades

* Exibição de cardápio de lanches e bebidas
* Seleção de produtos por código
* Definição da quantidade de cada produto
* Cálculo do subtotal dos itens
* Aplicação de taxa de serviço de 10%
* Aplicação de cupons de desconto:

  * `DESC10` → 10%
  * `DESC20` → 20%
  * `FRETEGRATIS` → 5%
* Escolha da forma de pagamento:

  * Dinheiro / PIX
  * Cartão de débito
  * Cartão de crédito
* Cálculo de troco
* Mensagens de confirmação e finalização do pedido
* Interface via terminal

## 🛠️ Tecnologias utilizadas

* **Python 3**
* Biblioteca padrão `time`

## 🚀 Como executar

### Pré-requisito

É necessário ter o **Python 3** instalado.

### Clone o repositório

```bash
git clone https://github.com/Thiago1702S/Sistema-Pedido-Lanchonete-Python.git
```

Entre na pasta:

```bash
cd Sistema-Pedido-Lanchonete-Python
```

Execute o arquivo Python:

```bash
python nome_do_arquivo.py
```

> Substitua `nome_do_arquivo.py` pelo nome do arquivo principal do projeto.

## 🧩 Conceitos praticados

O projeto utiliza conceitos fundamentais de programação, como:

* Variáveis e tipos de dados
* Dicionários
* Estruturas condicionais `if / else`
* Estrutura de repetição `while`
* Entrada e saída de dados
* Operações matemáticas
* Formatação de valores
* Manipulação de strings
* Validação básica de opções
* Simulação de regras de negócio

## 💻 Exemplo de execução

Ao adicionar um produto, o sistema apresenta uma mensagem semelhante a:

```text
>>> 2x XBURGUER adicionado(s). Subtotal: R$ 40.00 <<<
```

Ao finalizar o pedido, o sistema apresenta o resumo e solicita a forma de pagamento.

## 🎯 Objetivo do projeto

Projeto desenvolvido como prática de **Python e lógica de programação**, com foco na utilização de estruturas de controle, dicionários, operações matemáticas, entrada de dados e implementação de regras simples de negócio.
