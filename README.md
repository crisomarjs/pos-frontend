# ⚙️ POS - Next.js / Nest.js

POS - Next.js / Nest.js es una interfaz moderna e intuitiva para la gestión de ventas, productos y transacciones en un entorno de punto de venta.  
Desarrollado con **Next.js 16**, **TypeScript** y **TailwindCSS**, este frontend ofrece una experiencia fluida y eficiente para el usuario final.

---

## 🚀 Características principales

- 💳 Gestión de ventas 
- 🧾 Administración de productos y cupones  
- 🛍️ Carrito de compras interactivo  
- 🧠 Manejo global del estado con TypeScript  
- ⚙️ Integración con el backend mediante API REST (NestJS)  
- 🎨 Interfaz moderna con TailwindCSS  
- 🔒 Acciones del servidor con Server Actions de Next.js 16  

---

## 🧱 Tecnologías utilizadas

- **Next.js 16**
- **TypeScript**
- **TailwindCSS**
- **Node.js**
- **Zustand / Context API (para manejo de estado)**
- **Server Actions (Next.js 16)**
---

## 📂 Estructura del proyecto

- `app/` → Páginas y rutas principales del proyecto  
  - `(store)/` → Sección principal del punto de venta  
  - `admin/` → Panel administrativo  
  - `coupon/` → Gestión y aplicación de cupones  
  - `layout.tsx` → Estructura global del layout  
  - `providers.tsx` → Proveedores globales (contextos, temas, etc.)  

- `components/` → Componentes reutilizables de la interfaz  
  - `cart/` → Componentes relacionados con el carrito de compras  
  - `products/` → Componentes para la gestión y visualización de productos  
  - `transactions/` → Componentes para las transacciones de venta  
  - `ui/` → Elementos de interfaz de usuario (botones, modales, inputs, etc.)  

- `src/` → Lógica de negocio y configuración  
  - `api.ts` → Conexión con el backend y manejo de endpoints  
  - `schemas.ts` → Esquemas y validaciones con TypeScript  
  - `store.ts` → Manejo del estado global (context o Zustand)  
  - `utils.ts` → Funciones de utilidad  

- `public/` → Archivos estáticos (imágenes, íconos, etc.)  
- `actions/` → Acciones del servidor (Server Actions de Next.js)  

---

## ⚙️ Configuración del entorno

Crea un archivo `.env` en la raíz del proyecto con la siguiente variable:

```env
API_URL=
DOMAIN=
NEXT_PUBLIC_API_URL=
NEXT_PUBLIC_DOMAIN=
```

## 🔗 Repositorios relacionados

- [Frontend - Next.js + TS](https://github.com/crisomarjs/pos-frontend)
- [Backend - Node + Express + TS + PostgreSQL](https://github.com/crisomarjs/pos-backend)
