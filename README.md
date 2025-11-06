```bash
# Hotel Microservices

Proyecto basado en arquitectura de microservicios para una aplicación hotelera.
Incluye un backend con Node.js, dos frontends HTML, una base de datos MySQL, y un balanceador de carga con Nginx.
Todo está orquestado mediante Docker Compose.

## Tecnologías utilizadas

- Node.js / Express → Backend principal
- MySQL → Base de datos
- Nginx → Balanceador de carga y proxy reverso
- Docker Compose → Orquestación de contenedores
- HTML + CSS + JS → Frontends livianos

## Estructura del proyecto

hotel-microservices/
│
├── backend/         # API principal (Node.js + Express)
├── front1/          # Frontend 1 (HTML)
├── front2/          # Frontend 2 (HTML)
├── nginx/           # Configuración del balanceador (nginx.conf)
├── docker-compose.yml
└── README.md

## Cómo ejecutar el proyecto

1️⃣ Clonar el repositorio

git clone https://github.com/jonathanParamo/hotel-microservices
cd hotel-microservices

2️⃣ Construir e iniciar los servicios

docker compose up --build

3️⃣ Acceder desde el navegador

Frontend balanceado: http://localhost
Backend API: http://localhost:3000

## Servicios incluidos

MySQL      → Puerto 3306   → Base de datos
Backend    → Puerto 3000   → API principal (Node.js + Prisma)
Frontend 1 → Puerto 80     → Interfaz 1 (balanceada por Nginx)
Frontend 2 → Puerto 80     → Interfaz 2 (balanceada por Nginx)
Nginx      → Puerto 80     → Balanceador de carga

## Autor

Jonathan Páramo
Desarrollador Web | Node.js | React | Docker
📧 jonathan-and@outlook.com
```
