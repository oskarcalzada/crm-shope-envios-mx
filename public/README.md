# CRM Shope Envíos MX

Sistema CRM para gestión de envíos y clientes.

## Variables de Entorno Requeridas

Crea un archivo `.env` en la raíz del proyecto con las siguientes variables:

```
# Base de datos
DATABASE_URL=

# JWT
JWT_SECRET=your-super-secret-jwt-key

# Puerto del servidor (opcional)
PORT=3001

# Configuración de la aplicación
NODE_ENV=production
```

## Instalación Local

```bash
npm install
npm run start
```

## Despliegue en Vercel

1. Conecta tu repositorio con Vercel
2. Configura las variables de entorno en el dashboard de Vercel
3. El despliegue será automático

## Estructura del Proyecto

- `client/` - Frontend React con Vite
- `server/` - Backend Express.js
- `data/` - Base de datos SQLite
