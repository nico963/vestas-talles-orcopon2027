# 🧥 Registro de Talles Ropa 2027 — Vestas Wind Systems AR/UY

Formulario digital para que los técnicos de Vestas registren sus talles de ropa de trabajo para la temporada 2027.

## ¿Para qué sirve?

Cada técnico ingresa su nombre e iniciales SAP, selecciona su talle para cada prenda y envía el registro. El supervisor puede ver el conteo general y exportar los datos a Excel/CSV.

## Prendas incluidas

- Mamelucos
- Chomba Manga Larga
- Campera de Abrigo
- Camisa Manga Larga
- Primera Piel
- Campera Liviana y Chaleco
- Pantalón (sistema Talle C con guía de medidas)
- Calzado
- Medias
- Varios / Observaciones

## Cómo usarlo

1. Abrir el link público del formulario (GitHub Pages)
2. Ingresar nombre completo e iniciales SAP (opcionales)
3. Seleccionar el talle de cada prenda — hay guías de medidas por prenda
4. Confirmar el registro

## Vista Supervisor

Accesible desde la pestaña **Supervisor** en el formulario. Muestra:
- Conteo de talles por prenda
- Lista de técnicos registrados
- Botón de exportación CSV (compatible con Excel)

## Configuración del Webhook (Power Automate)

Para que los datos se guarden en SharePoint, completar la variable en `index.html`:

```js
const WEBHOOK_URL = 'https://prod-xx.westus.logic.azure.com/...';
```

Sin webhook configurado, los datos quedan guardados localmente en el navegador de cada técnico.

## Tecnología

- HTML / CSS / JavaScript puro — sin frameworks, sin dependencias externas
- Google Fonts: Montserrat + Inter
- Colores corporativos Vestas
- Compatible con PC, tablet y celular

## Mantenimiento

Desarrollado por **NOLRE** — Stock Keeper, Vestas Wind Systems AR/UY  
Temporada: **2027**
