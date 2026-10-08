# CEI Pagos — Sistema de Control de Pagos

Sistema interno de CEI Corporation para gestión de promesas de compraventa, clientes y control de pagos — **Altos de Buena Vista**.

## Stack

| Capa | Herramienta |
|---|---|
| Frontend | HTML / CSS / JS (sin framework) |
| Base de datos | Supabase (PostgreSQL) |
| Deploy | Netlify |
| Dominio | pagos.ceicorporationgt.com |

## Módulos

- **Control de Pagos** — Registro de cuotas, estados, exportación CSV
- **Promesas de Compraventa** — Creación con cálculo automático de cuotas
- **Clientes** — Base de datos vinculada a promesas
- **Lotes** — Inventario de 58 lotes Altos de Buena Vista

## Estructura

```
cei-pagos/
  index.html     ← app completa
  README.md
```

## Variables de entorno (Netlify)

```
SUPABASE_URL=https://emdrrbwokgaithgcyaey.supabase.co
SUPABASE_KEY=sb_publishable_...
```

## Deploy

1. Conectar repo a Netlify
2. Publish directory: `/`
3. Build command: *(vacío)*
4. Deploy

---

**CEI Corporation GT** · Uso interno · Confidencial
