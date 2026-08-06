# Sistema de Controle de Pedidos

Protótipo de interface web para apresentação de produtos, preços e fluxo de pedidos. O projeto reúne páginas de navegação comercial, checkout, contato e confirmação em uma experiência responsiva.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

## Sobre o projeto

Este projeto demonstra a construção de uma interface multipágina para um fluxo comercial. A proposta inclui descoberta de serviços, consulta de preços, contato, checkout e página de confirmação.

Por ser um protótipo front-end, o repositório concentra a camada visual e a navegação. Integrações com banco de dados, autenticação e processamento real de pagamentos não fazem parte desta versão.

## Páginas disponíveis

- **Página inicial** — apresentação da solução
- **Preços** — consulta de planos e ofertas
- **Checkout** — estrutura visual do fluxo de pedido
- **Contato** — formulário e canais de atendimento
- **Blog** — espaço para conteúdo informativo
- **Confirmação** — retorno visual após o fluxo
- **Página 404** — tratamento de endereço inexistente

## Tecnologias e conceitos

- HTML5 semântico
- CSS3 e layout responsivo
- JavaScript e jQuery
- Bootstrap
- Navegação entre múltiplas páginas
- Componentes visuais reutilizáveis
- Formulários e experiência de checkout

## Como executar

Não é necessário instalar dependências.

```bash
git clone https://github.com/frostx25/sistemacontrolepedidos.git
cd sistemacontrolepedidos
```

Abra o arquivo `index.html` no navegador. Para uma experiência mais próxima de produção, também é possível utilizar uma extensão de servidor local, como o Live Server.

## Estrutura principal

```text
index.html       # Página inicial
price.html       # Preços e planos
checkout.html    # Fluxo visual de pedido
contact.html     # Contato
blog.html        # Conteúdo
thanks.html      # Confirmação
404.html         # Página de erro
```

## Possíveis evoluções

- API para cadastro e acompanhamento de pedidos
- Persistência em banco de dados
- Autenticação de usuários e painel administrativo
- Validação de formulários
- Integração com meios de pagamento
- Conteinerização com Docker e publicação automatizada

## Autor

**Leonardo Cali** — Desenvolvedor Full Stack Pleno

- [GitHub](https://github.com/frostx25)
- [LinkedIn](https://www.linkedin.com/in/leonardo-cali-7567222a9/)

## Licença

Distribuído sob a licença Apache 2.0. Consulte o arquivo [LICENSE](LICENSE).
