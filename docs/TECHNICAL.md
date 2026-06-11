# Documentación Técnica - CRM con Clientes y Notas

## Información General
- **Aplicación**: CRM (Customer Relationship Management) con gestión de clientes y notas
- **Tecnologías**: HTML + JavaScript (Frontend vanilla)
- **Repositorio**: https://github.com/luisernestosalas/app-za4c3
- **URL de producción**: https://app-za4c3-md8yj1kee-luisernestosalas-2775s-projects.vercel.app
- **Plataforma de deploy**: Vercel

## Arquitectura
- **Tipo**: Aplicación web del lado del cliente (Client-side)
- **Patrón**: SPA (Single Page Application)
- **Almacenamiento**: Local Storage del navegador
- **Framework**: Vanilla JavaScript (sin frameworks externos)

## Funcionalidades Principales
1. **Gestión de Clientes**
   - Crear nuevos clientes
   - Editar información existente
   - Eliminar registros
   - Visualización en lista

2. **Sistema de Notas**
   - Agregar notas por cliente
   - Editar notas existentes
   - Eliminar notas
   - Asociación cliente-nota

## Estructura del Proyecto
```
/
├── index.html          # Página principal
├── style.css          # Estilos CSS
├── script.js          # Lógica JavaScript
└── README.md          # Documentación del proyecto
```

## Características Técnicas
- **Persistencia**: Local Storage para mantener datos entre sesiones
- **