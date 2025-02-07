# desafio-modelo-eer

# Desafio de Projeto - Modelo Conceitual e Relacional

Este projeto foi desenvolvido como parte do desafio proposto no curso de Refinando um Projeto Conceitual de Banco de Dados..

## Objetivo do Projeto

Criar e refinar o esquema conceitual de um sistema de gerenciamento de pedidos, integrando especialização e novas entidades.

## Requisitos:

1. **Cliente PF e PJ:**  
   - Uma conta pode ser de Pessoa Física (PF) ou Pessoa Jurídica (PJ), mas não ambas ao mesmo tempo.

2. **Pagamento:**  
   - Permitir múltiplas formas de pagamento vinculadas a cada pedido.

3. **Entrega:**  
   - Adicionar status e código de rastreio à entidade de entrega.

## Modelo Conceitual

![Diagrama Conceitual]([path/to/image.png](https://github.com/lvvieira/desafio-modelo-eer/blob/main/diagrama_eer_projeto.pdf))

## Scripts

O projeto inclui um script SQL para criação das tabelas no banco de dados relacional. O arquivo `schema.sql` contém a implementação completa.

