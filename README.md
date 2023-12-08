# Marketplace

## Descrição do Projeto

O Marketplace é um projeto completo construído do zero utilizando Next.js 14. Oferece uma experiência única para compradores e vendedores, proporcionando um ambiente seguro e eficiente para a compra e venda de produtos digitais. O projeto inclui uma landing page atrativa, páginas de produtos personalizadas, um painel administrativo completo e recursos avançados para uma experiência de usuário excepcional.

## Principais Funcionalidades

- **Landing Page e Páginas de Produto:** Desenvolvi páginas visualmente atraentes para a landing page e produtos, proporcionando uma experiência de navegação envolvente.

- **Compra e Venda de Produtos:** Os usuários podem comprar e vender produtos digitais de forma conveniente, facilitando a transação e entrega dos itens.

- **Carrinho de Compras Persistente:** Implementei um carrinho de compras que é localmente persistido, permitindo aos usuários retomarem suas compras mesmo após fechar a janela do navegador.

- **Autenticação com Verificação por E-mail:** Utilizei um sistema de autenticação que inclui verificação por e-mail, garantindo a segurança e validade das contas dos usuários.

- **Painel Administrativo Completo:** Incluí um painel administrativo robusto, permitindo que os administradores verifiquem produtos para garantir alta qualidade no marketplace.

- **UI Moderna com Shadcn-UI:** Utilizei a biblioteca shadcn-ui para criar uma interface de usuário limpa e moderna, proporcionando uma experiência visualmente agradável.

- **E-mails Atraentes:** Desenvolvi e-mails bonitos tanto para o processo de inscrição quanto após a conclusão de uma compra, oferecendo uma comunicação eficaz e esteticamente agradável.

- **Verificação de Produtos por Administradores:** Os administradores têm a capacidade de verificar produtos, assegurando a qualidade e confiabilidade dos itens no marketplace.

- **Escrito 100% em TypeScript:** O código do projeto é totalmente escrito em TypeScript, garantindo maior robustez e segurança durante o desenvolvimento.

## Dependências

A plataforma utiliza várias dependências para garantir seu funcionamento suave. Algumas das principais dependências incluem:

- `@hookform/resolvers`: ^3.3.2
- `@payloadcms/bundler-webpack`: ^1.0.5
- `@payloadcms/db-mongodb`: ^1.0.8
- `@payloadcms/richtext-slate`: ^1.2.0
- `@radix-ui/react-dialog`: ^1.0.5
- `@radix-ui/react-dropdown-menu`: ^2.0.6
- `@radix-ui/react-label`: ^2.0.2
- `@radix-ui/react-scroll-area`: ^1.0.5
- `@radix-ui/react-separator`: ^1.0.3
- `@radix-ui/react-slot`: ^1.0.2
- `@react-email/components`: ^0.0.12
- `@tanstack/react-query`: ^4.36.1
- `@trpc/client`: ^10.44.1
- `@trpc/next`: ^10.44.1
- `@trpc/react-query`: ^10.44.1
- `@trpc/server`: ^10.44.1
- `body-parser`: ^1.20.2
- `class-variance-authority`: ^0.7.0
- `clsx`: ^2.0.0
- `cross-env`: ^7.0.3
- `date-fns`: ^2.30.0
- `dotenv`: ^16.3.1
- `express`: ^4.18.2
- `lucide-react`: ^0.293.0
- `next`: ^14.0.3
- `nodemailer`: ^6.9.7
- `payload`: ^2.2.2
- `react`: ^18
- `react-dom`: ^18
- `react-hook-form`: ^7.48.2
- `resend`: ^2.0.0
- `sonner`: ^1.2.4
- `stripe`: ^14.7.0
- `swiper`: ^11.0.5
- `tailwind-merge`: ^2.0.0
- `tailwindcss-animate`: ^1.0.7
- `zod`: ^3.22.4
- `zustand`: ^4.4.7

## Como Executar o Projeto

1. Clone este repositório em sua máquina local.
2. Certifique-se de ter o Node.js e o npm (ou yarn) instalados.
3. Instale as dependências do projeto utilizando o seguinte comando:

```bash
npm install
# ou
yarn install
```

4. Crie um arquivo `.env` na raiz do projeto com as seguintes chaves e valores correspondentes:

```env
NEXT_PUBLIC_SERVER_URL=seu_valor_aqui
PAYLOAD_SECRET=seu_valor_aqui
MONGODB_URL=seu_valor_aqui
STRIPE_SECRET_KEY=seu_valor_aqui
STRIPE_WEBHOOK_SECRET=seu_valor_aqui
RESEND_API_KEY=seu_valor_aqui
```

Certifique-se de substituir `seu_valor_aqui` pelos valores corretos.

5. Para iniciar o servidor de desenvolvimento, utilize o seguinte comando:

```bash
npm run dev
# ou
yarn dev
```

6. Acesse a plataforma em `http://localhost:3000` e explore todas as funcionalidades do marketplace digital, incluindo a compra e venda de produtos digitais.
