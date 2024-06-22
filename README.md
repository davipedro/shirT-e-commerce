# ShirT - E-commerce

## Índice
- [Sobre o Projeto](#sobre-o-projeto)
- [MVP](#mvp)
- [Funcionalidades](#funcionalidades)

## Sobre o Projeto
Um projeto de e-commerce para estudo e prática de desenvolvimento de aplicações web e arquitetura de sistemas. O projeto é um MVP (Produto Mínimo Viável) de uma plataforma de e-commerce, com funcionalidades essenciais para usuários e administradores.

A ideia é que o projeto seja desenvolvido em partes, onde cada parte do sistema corresponde a um módulo ou funcionalidade específica. O objetivo é implementar um sistema completo, com frontend, backend e banco de dados, utilizando tecnologias modernas e boas práticas de desenvolvimento.

```
Este é o repositório principal do projeto
```

### ✍ Documentação de Aprendizado
```
O projeto terá um Readme com a jornada de desenvolvimento, onde serão documentadas as decisões de design, arquitetura, tecnologias utilizadas, funcionalidades implementadas e próximos passos.
```

## MVP
Para um MVP (Produto Mínimo Viável) de uma plataforma de e-commerce, o objetivo é implementar as funcionalidades essenciais que permitam aos usuários realizar compras básicas e ao administrador gerenciar produtos e pedidos. Esse MVP deve ser funcional, mas com um escopo limitado para permitir um lançamento rápido e iterativo.

### Visão Geral do MVP

O MVP focará em fornecer uma plataforma básica onde usuários podem:

- Navegar por um catálogo de produtos.
- Adicionar produtos ao carrinho de compras.
- Realizar a finalização da compra com informações de pagamento simuladas.
- Administrar produtos e visualizar pedidos.

### Componentes Principais do MVP

1. **Gerenciamento de Produtos**
2. **Autenticação e Autorização de Usuários**
3. **Carrinho de Compras**
4. **Processamento de Pedidos**
5. **Interface do Usuário**
6. **Dashboard de Administração**

## Funcionalidades

1. **Gerenciamento de Produtos**
   - **API para CRUD de Produtos**: Permitir ao administrador criar, ler, atualizar e deletar produtos.
   - **Catálogo de Produtos**: Exibição de uma lista de produtos disponíveis para os usuários, com detalhes como nome, descrição, preço e imagem.

2. **Autenticação e Autorização de Usuários**
   - **Registro e Login de Usuários**: Funcionalidade básica para que os usuários possam se registrar e fazer login na plataforma.
   - **Gestão de Sessões**: Gerenciamento de sessões do usuário, incluindo logout e proteção de endpoints.

3. **Carrinho de Compras**
   - **API para Gerenciamento do Carrinho**: Adicionar, remover e atualizar a quantidade de produtos no carrinho.
   - **Visualização do Carrinho**: Permitir aos usuários ver os itens adicionados ao carrinho, com subtotal calculado.

4. **Processamento de Pedidos**
   - **API de Checkout**: Processar a finalização da compra, incluindo coleta de informações de pagamento (simulada) e detalhes de envio.
   - **Confirmação de Pedido**: Página ou endpoint que confirma o pedido e fornece um resumo.

5. **Interface do Usuário**
   - **Frontend Básico**: Implementação de uma interface mínima para usuários navegarem, adicionarem produtos ao carrinho e finalizarem compras.
   - **Dashboard de Administração**: Uma interface simples para administradores gerenciarem produtos e visualizarem pedidos.
