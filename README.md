# Gasti Developers

Portal para developers de Gasti: integraciones "Conectar mi Gasti", autenticación OAuth y referencia preliminar de la Public API.

## Contenido

- **Empezar**: Introducción, guía end-to-end de Conectar mi Gasti y registro manual de integraciones
- **Autenticación**: Flujo OAuth, scopes, tokens, refresh y errores
- **API Reference**: Especificación OpenAPI preliminar de la futura Public API

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
├── conectar-mi-gasti.mdx
├── registrar-integracion.mdx
├── openapi.json
└── oauth/
    ├── flujo.mdx
    ├── scopes.mdx
    ├── tokens-y-refresh.mdx
    └── errores.mdx
```

## Configuración

La configuración de la documentación se encuentra en `docs.json`. Este archivo controla:

- Navegación y estructura del portal
- Colores y branding
- Links del navbar
- Opciones de contexto de Mintlify

## Cambios Recientes

- Conversión del sitio en un portal exclusivo para developers
- Actualización a formato docs.json de Mintlify
- Documentación OAuth y referencia OpenAPI preliminar

## Recursos

- [Documentación de Mintlify](https://mintlify.com/docs)
