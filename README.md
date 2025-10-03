# 🖥️ Challenge Frontend Senior – Dashboard Analítico

## Contexto

En Colppy queremos evaluar tus habilidades como **Frontend Developer Senior**.  
El objetivo de este challenge es construir un **dashboard analítico en tiempo real** que muestre métricas de negocio, se actualice automáticamente y esté diseñado con foco en **arquitectura de componentes, estado, rendimiento y experiencia de usuario**.

---

## 🎯 Objetivo

Desarrollar una **aplicación web frontend** que:

- Visualice métricas en tiempo real provenientes de una API simulada.
- Muestre un dashboard con KPIs y al menos un gráfico.
- Destaque visualmente alertas (ejemplo: churn > 5% en rojo).
- Se pueda **desplegar en producción** (Netlify, Vercel o Railway).

---

## 📊 Requerimientos funcionales

1. **Visualización de métricas**
   - Mostrar al menos 3 widgets:
     - Usuarios activos
     - Ingresos
     - Churn (%)
   - Incluir un gráfico de líneas o barras para evolución en el tiempo.

2. **Datos en tiempo real**
   - Consumir una API mock que entrega datos cada pocos segundos.
   - Actualizar el dashboard automáticamente (polling cada 5s).

3. **Alertas**
   - Resaltar con color cuando algún indicador supere un umbral (ej: churn > 5%).

4. **Diseño y experiencia**
   - UI responsive y usable en desktop y mobile.
   - Uso de componentes reutilizables.
   - Estilos con TailwindCSS (sugerido).

5. **Deploy obligatorio**
   - La aplicación debe estar online usando **Netlify**, **Vercel** o **Railway**.  
   - Incluir en el README el link de acceso.

---

## 🛠️ Setup inicial

### 1. Clonar el repo
```bash
git clone https://github.com/AleSotoColppy/challenge-frontend-sr.git
cd challenge-frontend-sr

## Setup

### 1. Instalar API
```bash
cd api
npm install
npm start
```

### 2. Instalar Frontend
```bash
cd frontend
npm install
npm run dev
```

Abrir en: http://localhost:5173
