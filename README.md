# Product Microservice  
## Dev  
1. Clonar el repositorio  
2. Instalar dependencias  
3. Crear un achivo `.env` con las variables de entorno  
4. Ejecutar la migración de Prisma  
```bash
npx prisma migrate dev
```
5. Levantar el servidor de NATS
```bash
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
6. Ejecutar  
```bash
npm run start:dev
```
