Sistema de Pedido – Lanchonete (Python)

Este projeto é um sistema simples de pedidos para lanchonetes, desenvolvido em Python, que permite ao usuário escolher lanches e bebidas, calcular o total da compra, aplicar cupons de desconto e finalizar o pagamento.

Funcionalidades:

Exibe um cardápio com lanches e bebidas

Permite escolher itens e quantidades

Calcula subtotal automaticamente

Aplica taxa de serviço de 10%

Aceita cupons de desconto

DESC10 – 10%

DESC20 – 20%

FRETEGRATIS – 5%

Permite escolher forma de pagamento

Dinheiro/PIX

Cartão (débito/crédito)

Calcula troco (quando necessário)

Interface simples via terminal

Tecnologias Utilizadas:

Python 3

Biblioteca: time (para pequenos delays)

Como Executar:

Certifique-se de ter o Python 3 instalado.

Clone o repositório:

git clone https://github.com/seu-usuario/seu-repo.git


Execute o script:

python nome_do_arquivo.py

Estrutura do Código:

Cardápio organizado com dicionários

Laço while para controlar pedidos

Cálculo de subtotal, taxa de serviço e descontos

Simulação de pagamento

Validação de entradas básicas

Exemplo de Uso:

O programa mostra o cardápio, permite a seleção de itens e mostra mensagens como:

>>> 2x XBURGUER adicionado(s). Subtotal: R$ 40.00 <<<


E no final:

TOTAL A PAGAR: R$ 55.00
Pagamento aprovado! Obrigado pela preferência!
