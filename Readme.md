# Projeto de Agendamento de Horários

Este é um projeto fullstack desenvolvido utilizando Next.js, Prisma, MySQL, autenticação com Google, integração com o calendário do Google e React Query. O objetivo do projeto é permitir aos usuários agendar horários e adicionar lembretes diretamente em seus calendários.

Certamente! Aqui está a seção adicionada para incluir uma imagem de preview do projeto:

## Preview

Aqui está uma imagem de preview do projeto:

![Preview do Projeto](./public/preview.png)

Esta imagem oferece uma prévia visual do projeto e suas principais características. Aproveite para conferir o projeto em ação!

## Demonstração

Você pode conferir uma demonstração do projeto em produção através do seguinte link: [Link da Demo](https://ignite-call-nu-nine.vercel.app/)

Certifique-se de acessar o link acima para explorar o projeto em ação!

## Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas em seu sistema:

- Node.js (v16 ou superior)
- MySQL

## Configuração

Siga as etapas abaixo para configurar e executar o projeto em sua máquina local:

1. Clone o repositório para sua máquina local:

```bash
git clone https://github.com/kevenpacheco/ignite-call.git
```

2. Acesse o diretório do projeto:

```bash
cd ignite-call
```

3. Instale as dependências do projeto:

```bash
# Instale as dependências do projeto usando NPM
npm install

# OU

# Instale as dependências do projeto usando Yarn
yarn install

```

4. Crie um arquivo `.env.local` na raiz do projeto e defina as seguintes variáveis de ambiente:

```bash
DATABASE_URL="mysql://user:password@localhost:3306/nome-do-banco-de-dados"
GOOGLE_CLIENT_ID="seu-client-id-do-google"
GOOGLE_CLIENT_SECRET="seu-client-secret-do-google"
NEXTAUTH_SECRET="seu-next-auth-secret"
```

Certifique-se de substituir as informações relevantes pelas suas próprias.

5. Execute as migrações do banco de dados:

```bash
npx prisma migrate dev
```

6. Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

O projeto estará sendo executado em `http://localhost:3000`.

## Uso

Após iniciar o servidor de desenvolvimento, acesse `http://localhost:3000` em seu navegador.

1. Faça login utilizando sua conta do Google.

2. Na página inicial, você poderá visualizar os horários disponíveis e agendar novos horários.

3. Ao agendar um horário, um lembrete será automaticamente adicionado ao seu calendário do Google.

## Tecnologias utilizadas

- [Next.js](https://nextjs.org/) - Framework de React para renderização do lado do servidor (SSR).
- [Prisma](https://www.prisma.io/) - ORM (Object-Relational Mapping) para interagir com o banco de dados MySQL.
- MySQL - Banco de dados relacional para armazenamento dos dados do projeto.
- Autenticação com Google - Integração com a API de autenticação do Google para autenticar os usuários.
- Integração com o Calendário do Google - Utilização da API do Google Calendar para adicionar lembretes nos calendários dos usuários.
- [React Query](https://react-query.tanstack.com/) - Biblioteca para gerenciamento de estado e cache dos dados no cliente.

## Contribuição

Se você deseja contribuir para este projeto, fique à vontade para enviar pull requests. Será um prazer receber sua contribuição!

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).