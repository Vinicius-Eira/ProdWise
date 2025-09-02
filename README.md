# ProdWise

Projeto **pessoal** desenvolvido para praticar e demonstrar habilidades em desenvolvimento **full stack**, integrando back-end em **NestJS** com **Prisma ORM** e front-end moderno. O objetivo é servir como estudo e também como parte do meu **portfólio no GitHub**.

---

## 🚀 Tecnologias Utilizadas

### Back-end

* [NestJS](https://nestjs.com/) - Framework Node.js para construção de APIs escaláveis.
* [Prisma](https://www.prisma.io/) - ORM moderno para Node.js e TypeScript.
* [TypeScript](https://www.typescriptlang.org/) - Superset tipado do JavaScript.
* [PostgreSQL](https://www.postgresql.org/) - Banco de dados relacional.

### Front-end

* [React](https://react.dev/) - Biblioteca para interfaces de usuário.
* [Vite](https://vitejs.dev/) - Ferramenta de build rápida para front-end.
* [TailwindCSS](https://tailwindcss.com/) - Estilização utilitária.

### Outros

* [Docker](https://www.docker.com/) - Containerização e ambientes isolados.
* [ESLint](https://eslint.org/) e [Prettier](https://prettier.io/) - Padrões e formatação de código.
* GitHub Actions (CI/CD) - Integração e entrega contínua.

---

## 📂 Estrutura do Projeto

```
notra-corner-main/
├── .github/workflows   → Configurações de CI/CD
├── notra-api/          → Back-end (NestJS + Prisma)
│   ├── prisma/         → Schema, migrations e diagramas
│   ├── src/            → Código-fonte do back-end
│   ├── package.json    → Dependências do back-end
│   └── ...
└── notra-front/        → Front-end (React + Vite + Tailwind)
    ├── src/            → Código-fonte do front-end
    ├── package.json    → Dependências do front-end
    └── ...
```

---

## ⚙️ Como Rodar o Projeto Localmente

### Pré-requisitos

* Node.js (>= 18)
* NPM ou Yarn
* Docker e Docker Compose
* PostgreSQL (caso não use Docker)

### Passo 1: Clonar o repositório

```bash
git clone https://github.com/Vinicius-Eira/notra-corner.git
cd notra-corner-main
```

### Passo 2: Rodar o back-end

```bash
cd notra-api
npm install
npx prisma migrate dev
npm run start:dev
```

### Passo 3: Rodar o front-end

```bash
cd ../notra-front
npm install
npm run dev
```

O front ficará disponível em: **[http://localhost:5173](http://localhost:5173)**

---

## 🛠 Funcionalidades

* ✅ Autenticação de usuários (login/registro)
* ✅ Gestão de tarefas e quadros (to-do board)
* ✅ Migrations de banco de dados com Prisma
* ✅ API estruturada com NestJS
* ✅ Integração front-end + back-end
* ✅ Configuração de CI/CD no GitHub Actions

---

## 🤝 Contribuição

Este projeto é pessoal, mas contribuições são bem-vindas 🙂

1. Faça um fork do projeto
2. Crie uma branch (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Faça o push (`git push origin feature/nova-feature`)
5. Abra um Pull Request

---

## 📜 Licença

Este projeto é de uso pessoal e está sob a licença **MIT**. Sinta-se livre para usar como referência.

---

### 👨‍💻 Autor

**Vinícius Eira**
📌 Desenvolvedor Full Stack
🌐 [Meu GitHub](https://github.com/Vinicius-Eira)
