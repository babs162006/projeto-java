# MACKSHOP - Sistema de Vendas em Java 

## Descrição

O **MACKSHOP** é um sistema de vendas desenvolvido em Java para execução em ambiente de terminal.  

O sistema simula o funcionamento básico de um ponto de venda, permitindo:

- Cadastro e inicialização de produtos
- Controle de estoque
- Registro de vendas
- Geração de nota fiscal
- Armazenamento de histórico
- Consulta de vendas específicas
- Relatórios administrativos

O projeto foi desenvolvido com foco na prática de estruturas de dados utilizando vetores, controle de fluxo e organização modular do código.

---

## Funcionalidades

1. Inicializar base de produtos
2. Exibir catálogo de produtos com estoque disponível
3. Adicionar item à venda
4. Visualizar resumo da venda atual
5. Finalizar venda (gera histórico e nota fiscal)
6. Consultar histórico de vendas
7. Buscar venda específica pelo ID do pedido

### Operações Administrativas
8. Repor estoque
9. Gerar relatório de produtos com estoque abaixo do limite

---


## Conceitos Aplicados

- Programação Estruturada
- Métodos estáticos
- Manipulação de Arrays
- Matrizes bidimensionais
- Controle de fluxo (`if`, `switch`, `do-while`)
- Validação de entrada
- Separação de responsabilidades
- Controle de estoque
- Simulação de sistema de vendas

---

## 🏗 Estrutura do Sistema

O sistema é organizado em módulos funcionais:

- **Catálogo de Produtos**
  - Armazena ID, nome, preço e estoque.
  
- **Venda Atual**
  - Controla os itens adicionados antes da finalização.
  
- **Histórico de Vendas**
  - Guarda:
    - ID do pedido
    - Valor total
    - Itens vendidos (ID + quantidade)
  
- **Nota Fiscal**
  - Impressão formatada simulando cupom fiscal.

---

## 🧾 Exemplo de Nota Fiscal Gerada

<img width="853" height="385" alt="image" src="https://github.com/user-attachments/assets/13900c2f-fea0-4f6d-aee0-0120282c0da6" />

