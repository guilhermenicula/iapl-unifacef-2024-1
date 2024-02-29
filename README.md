# iapl-unifacef-2024-1
Repositório da disciplina Integração de Aplicações, 7º semestre Engenharia de Software Uni-FACEF 2024/1

# Instalação do Prisma
npm install prisma --save-dev

# inicialização do prisma
npx prisma init

# executando uma migration
npx prisma migrate dev --name create-users

# Exibindo os dados com Prisma Studio
npx prisma studio