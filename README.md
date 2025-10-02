# HACKATON

HACKATON DE PROGRAMACION:
PROYECTO DE EJEMPLO, PLANTILLAS CON LO REQUERIDO.
Frontend: React + TypeScript + React Router + Bootstrap 5
Backend: Node.js + Express + CORS + Morgan
FUNCIONALIDADES:
CRUD completo (GET, POST, PUT, DELETE) sobre items
Login dinámico y estético
Formularios con campo de fecha
Slider, Header, Footer con Bootstrap
Manejo de excepciones y concurrencia en backend
Sección de “Líneas de profundización en Ingeniería de Sistemas”
ESTRUCTURA DEL PROYECTO:
HACKATON WEB, II/
├── client/      # Frontend (React + TypeScript + Vite)
└── server/      # Backend (Node.js + Express)

PARA EJECUTAR EL PROYECTO:
* TENER VISUAL STUDIO CODE CON LAS EXTENSIONES NECESARIAS.
* SE DEBE TENER INSTALADO Node.js y el Package Manager de Node (npm).
* CLONAR EL REPOSITORIO: git clone (https://github.com/UNITEDMQUIA/HACKATON)
  cd HACKATON WEB, II

* EJECUTAR LOS SIGUIENTES COMANDOS DESDE LA TERMINAL DE VS CODE.
	* cd server
	* npm install
	* npm run dev
DE ESTA MANERA YA ESTA CORRIENDO EL BACKEND: http://localhost:4000
RUTAS HTTP DISPONIBLES: 
GET /api/items

GET /api/items/:id

POST /api/items

PUT /api/items/:id

DELETE /api/items/:id

GET /api/compute

EN OTRA TERMINAL DE VISUAL STUDIO CODE DIFERENTE EN LA QUE SE EJECUTO EL SERVIDOR:
	* cd client
	* npm install
	* npm run dev
QUEDARA CORRIENDO EL FRONTEND EN: http://localhost:5173
TECNOLOGIAS USADAS:
Frontend:

React 18

TypeScript

React Router DOM

Bootstrap 5

Vite

Backend:

Node.js

Express

Morgan

CORS
