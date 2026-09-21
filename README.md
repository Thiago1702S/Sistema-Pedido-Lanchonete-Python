# 🍔 Sistema de Pedido – Lanchonete

Sistema de pedidos para lanchonetes desenvolvido em **Python**, executado via terminal.

O projeto simula o processo de realização de um pedido, desde a escolha dos produtos até o pagamento, incluindo cálculo de valores, descontos e troco.

## 📋 Funcionalidades

* Exibição de cardápio com lanches e bebidas
* Seleção de produtos e quantidades
* Cálculo automático do subtotal
* Aplicação de taxa de serviço de 10%
* Aplicação de cupons de desconto:

  * `DESC10` → 10% de desconto
  * `DESC20` → 20% de desconto
  * `FRETEGRATIS` → 5% de desconto
* Seleção da forma de pagamento:

  * Dinheiro
  * PIX
  * Cartão de débito
  * Cartão de crédito
* Cálculo de troco para pagamentos em dinheiro
* Validação básica das entradas
* Interface via terminal

## 🛠️ Tecnologias utilizadas

* **Python 3**
* Biblioteca `time`

## 🚀 Como executar

### Pré-requisitos

Tenha o **Python 3** instalado em sua máquina.

### Clone o repositório

```bash
git clone https://github.com/Thiago1702S/Sistema-Pedido-Lanchonete-Python.git
```

Entre na pasta do projeto:

```bash
cd Sistema-Pedido-Lanchonete-Python
```

Execute o programa:

```bash
python nome_do_arquivo.py
```

> Substitua `nome_do_arquivo.py` pelo nome do arquivo principal do projeto.

## 🧩 Estrutura do código

O projeto utiliza:

* Dicionários para organização do cardápio
* Estruturas de repetição `while` para controle dos pedidos
* Cálculos de subtotal, taxa de serviço e descontos
* Estruturas condicionais para regras de negócio
* Simulação do processo de pagamento
* Validação básica das entradas do usuário

## 💻 Exemplo de uso

Durante a execução, o sistema apresenta informações sobre os itens adicionados ao pedido, por exemplo:

```text
>>> 2x XBURGUER adicionado(s). Subtotal: R$ 40.00 <<<
```

Ao finalizar o pedido:

```text
TOTAL A PAGAR: R$ 55.00
Pagamento aprovado!
Obrigado pela preferência!
```

## 🎯 Objetivo do projeto

Projeto desenvolvido como prática de **programação em Python**, com foco em lógica de programação, estruturas de dados, controle de fluxo, validação de entradas e implementação de regras de negócio.
