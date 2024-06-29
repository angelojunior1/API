npm init -y

npm install express typescript ts-node @types/node @types/express prisma @prisma/client sqlite3

npx prisma generate

npx prisma migrate dev --name init

npm start