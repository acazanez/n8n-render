# n8n en Render

Este repositorio permite desplegar **n8n** gratis en [Render](https://render.com) usando Docker.

## 🚀 Despliegue en Render

1. Crea un nuevo servicio en Render: **New → Web Service**.
2. Selecciona este repositorio.
3. Configura con:
   - **Environment:** Docker
   - **Branch:** main
   - **Plan:** Free

## 🔑 Variables de entorno necesarias

En Render → *Environment* añade estas variables:

N8N_BASIC_AUTH_ACTIVE=true
N8N_BASIC_AUTH_USER=admin
N8N_BASIC_AUTH_PASSWORD=tu_contraseña_segura
N8N_HOST=https://tuapp.onrender.com

WEBHOOK_URL=https://tuapp.onrender.com/


## 🌍 Acceso

Una vez desplegado, Render te dará una URL como:

https://n8n-render.onrender.com

css
Copiar
Editar

Ingresa con el usuario y contraseña que definiste
