# Projeto Loja Virtual - **Luciano Persianas**

> Projeto da disciplina de Front-End sob a orientação dos Professores Pedro Camara, Ana Scharf e Cleber Joerge Amaral (IFSC). 
> 
> **Contexto da Loja Virtual:** A empresa do meu pai, **Luciano Persianas** não possui nenhum site e como a disciplina de Front-End 1 solicita fazer uma loja virtual, decidi fazer esse projeto sobre uma empresa real. Meu pai é um profissional autônomo nesse ramo de persianas e ele é representante comercial de uma fabricante de persianas da Grande Florianópolis.

## Requisitos do Projeto

Este projeto foi desenvolvido seguindo estritamente as regras do edital (Projeto 1 - HTML e CSS). As principais especificações incluem:

* **Tecnologias:** Uso exclusivo de **HTML5 e CSS3**.
* **Sem Frameworks**
* **Estilização e Layout:** Uso de variavéis CSS para as cores do projeto, Flexbox e CSS Grid.
* **Responsividade:**
  * Desktop: `> 1024px`
  * Tablet: `≥ 768px` e `≤ 1024px`
  * Smartphone: `≤ 320px`

### Para mais detalhes: [PDF com os requisitos do projeto](requisitos.pdf)

## Estrutura de Páginas

O sistema é composto por 6 páginas navegáveis, conforme o escopo do projeto:

* **`index.html`:** Página inicial - Contém uma galeria de produtos, seção com uma logo, campo de texto contando sobre a empresa e uma seção de contato com informações de endereço.
* **`cadastro.html`:** Formulário de registro de novos clientes.
* **`login.html`:** Tela de autenticação com campos de e-mail e senha.
* **`perfil.html`:** Área restrita do cliente contendo o formulário de edição de dados cadastrais e a tabela demonstrativa de "Meus Pedidos".
* **`loja.html`:** O catálogo principal de produtos, equipado com filtros visuais e barra de busca. Ao lado, encontra-se o carrinho de compras com botão de Finalizar Compra.
* **`relatorio.html`:** Área administrativa. Conta com cabeçalho e rodapé distintos do resto do site, formulários de busca integrados e tabelas com os relatórios de Vendas e de Clientes.

## Como visualizar o Alerta de "Compra Finalizada"?
Para simular o comportamento de uma compra realizada, existe uma mensagem de confirmação com o número do pedido oculta na página
[Loja.html](projeto-luciano-persianas/pages/loja.html). 
* **Para visualizar:** Abra o arquivo [Loja.html](projeto-luciano-persianas/pages/loja.html), procure a `div` com a mensagem de confirmação (geralmente abaixo do carrinho) e **remova o atributo `hidden`** da tag.

## Validação W3C
O código fonte (HTML) foi submetido ao validador do W3C sem apresentar erros. Os *prints* comprovando as validações encontram-se nesta **[pasta](projeto-luciano-persianas/assets/validacao)**.

##  Licença

Este projeto está sob a licença [MIT](https://opensource.org/licenses/MIT). 

Copyright (c) 2026 Luciano Simas Junior