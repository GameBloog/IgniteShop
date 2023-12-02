# Ignite Shop

Este projeto Next.js, denominado Ignite Shop, é uma aplicação de comércio eletrônico simples que utiliza a API do Stripe para gerenciar transações de pagamento. O objetivo deste README é fornecer informações sobre a estrutura do projeto, suas dependências principais e como configurar o ambiente de desenvolvimento.

## Estrutura do Projeto

O projeto está estruturado com base em páginas e componentes, utilizando o framework Next.js. Abaixo estão alguns dos principais arquivos e diretórios:

- **`/pages`**: Contém as páginas da aplicação, como `index.tsx` (página inicial) e `product/[id].tsx` (página do produto).
- **`/components`**: Armazena componentes reutilizáveis, como `Product.tsx` e `Success.tsx`.
- **`/styles`**: Contém estilos globais e específicos de página, organizados em diretórios como `global.ts` e `pages/success.ts`.
- **`/lib`**: Inclui arquivos utilitários, como `stripe.ts` para a configuração da API do Stripe.

## Dependências Principais

O projeto utiliza várias dependências essenciais, incluindo:

- **Next.js**: Framework React para desenvolvimento web.
- **Stripe API**: Integração com a API de pagamento da Stripe.
- **keen-slider**: Biblioteca para criação de carrosséis responsivos.
- **axios**: Cliente HTTP para fazer requisições à API.

Certifique-se de instalar essas dependências antes de iniciar o desenvolvimento.

## Configuração do Stripe

O arquivo `lib/stripe.ts` contém a configuração da instância do Stripe. Certifique-se de criar uma conta no [Stripe](https://stripe.com/) e obter suas chaves de API (chave secreta e pública). Substitua `process.env.STRIPE_SECRET_KEY!` no arquivo pelo valor da sua chave secreta.

## Ambiente de Desenvolvimento

1. Clone o repositório: `git clone https://github.com/seu-usuario/ignite-shop.git`.
2. Instale as dependências: `npm install`.
3. Configure as chaves de API do Stripe no arquivo `lib/stripe.ts`.
4. Inicie o servidor de desenvolvimento: `npm run dev`.
5. Acesse a aplicação em [http://localhost:3000](http://localhost:3000).

## Desenvolvimento Adicional

Para desenvolver novas funcionalidades ou aprimorar o projeto, considere explorar as pastas `pages`, `components`, e `styles` para ajustar páginas existentes, criar novos componentes ou personalizar estilos.

## Colaboração e Problemas

Se você encontrar problemas ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma [issue](https://github.com/GameBloog/IgniteShop). Além disso, aceitamos contribuições através de [pull requests](https://github.com/GameBloog/IgniteShop/pullshttps://github.com/GameBloog/IgniteShop/pulls).

Divirta-se desenvolvendo o Ignite Shop! 🚀
