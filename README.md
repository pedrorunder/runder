# Runder - Plataforma de Questões do ENEM

A Runder é a maior plataforma de questões do ENEM, oferecendo mais de 10.000 questões organizadas, provas anteriores e ferramentas de estudo para ajudar estudantes a se prepararem para o exame.

## 🚀 Funcionalidades

- Acesso a todas as provas anteriores do ENEM
- Questões organizadas por área do conhecimento
- Sistema de login e registro de usuários
- Interface responsiva e moderna
- Estatísticas de desempenho
- Planos personalizados

## 🛠️ Tecnologias Utilizadas

- Next.js 14
- React 18
- TypeScript
- Tailwind CSS
- Prisma
- NextAuth.js
- PostgreSQL

## 📦 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/runder.git
cd runder
```

2. Instale as dependências:
```bash
npm install
```

3. Configure as variáveis de ambiente:
```bash
cp .env.example .env.local
```

4. Configure o banco de dados:
```bash
npx prisma migrate dev
```

5. Inicie o servidor de desenvolvimento:
```bash
npm run dev
```

## 🔧 Configuração do Ambiente

Crie um arquivo `.env.local` na raiz do projeto com as seguintes variáveis:

```env
DATABASE_URL="postgresql://user:password@localhost:5432/runder"
NEXTAUTH_SECRET="seu-secret-aqui"
NEXTAUTH_URL="http://localhost:3000"
GOOGLE_CLIENT_ID="seu-client-id"
GOOGLE_CLIENT_SECRET="seu-client-secret"
```

## 📚 Estrutura do Projeto

```
src/
  ├── app/              # Páginas e rotas da aplicação
  ├── components/       # Componentes React reutilizáveis
  ├── lib/             # Utilitários e configurações
  ├── prisma/          # Schema e migrações do Prisma
  └── styles/          # Estilos globais
```

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📞 Contato

- Email: contato@questfy.com
- Website: https://questfy.com
- LinkedIn: [Questfy](https://linkedin.com/company/questfy)

## 🙏 Agradecimentos

- Equipe de desenvolvimento
- Comunidade open source
- Todos os estudantes que utilizam nossa plataforma    