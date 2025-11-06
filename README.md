# Documentación de Gasti

Documentación oficial y guías de usuario para Gasti - Tu asistente financiero con IA desde WhatsApp.

## Contenido

- **Comenzar**: Introducción, inicio rápido, visión general de funcionalidades y límites de plan
- **Funcionalidades**: Documentación detallada de cada característica (Transacciones, Presupuestos, Metas de Ahorro, Multi-moneda, WhatsApp)
- **Guías de Usuario**: Guías paso a paso para las principales tareas

## Desarrollo Local

### Requisitos

- Node.js 18+
- pnpm o npm

### Instalación

```bash
npm install
# o
pnpm install
```

### Ejecutar en desarrollo

```bash
npm run dev
# o
pnpm dev
```

La documentación estará disponible en `http://localhost:3000`

### Compilar para producción

```bash
npm run build
# o
pnpm build
```

### Vista previa de producción

```bash
npm run preview
# o
pnpm preview
```

## Estructura

```
docs/
├── introduccion.mdx
├── inicio-rapido.mdx
├── funcionalidades.mdx
├── limites-de-plan.mdx
├── features/
│   ├── whatsapp.mdx
│   ├── transacciones.mdx
│   ├── presupuestos.mdx
│   ├── metas-ahorro.mdx
│   └── multi-moneda.mdx
└── guides/
    ├── empezar.mdx
    ├── gestionar-transacciones.mdx
    ├── crear-presupuestos.mdx
    ├── configurar-metas-ahorro.mdx
    └── usar-multi-moneda.mdx
```

## Configuración

La configuración de la documentación se encuentra en `docs.json`. Este archivo controla:

- Navegación y estructura del sitio
- Colores y branding
- Links del navbar
- Enlaces globales (community, support, etc.)

## Cambios Recientes

- Migración desde `gasti-core/apps/customers/customers-docs/`
- Actualización a formato docs.json de Mintlify
- Eliminación de contenido template
- Limpieza de texto en inglés

## Recursos

- [Documentación de Mintlify](https://mintlify.com/docs)
- [Gasti App](https://app.gasti.com)
- [Blog de Gasti](https://blog.gasti.com)
