# 🦷 DentalOS — ERP Dental Consultorio 2025

Sistema de gestión integral para consultorio dental. Desarrollado como aplicación web de una sola página (SPA), sin dependencias externas ni backend requerido.

**[🚀 Ver demo en vivo →](https://dentalos.netlify.app)**

---

## ✨ Funcionalidades

| Módulo | Descripción |
|--------|-------------|
| 📊 **Dashboard** | KPIs en tiempo real: ingresos, 60/40, saldo pendiente, resumen ejecutivo |
| 📅 **Agenda** | Calendario semanal con citas, colores por tratamiento, alta de nuevas citas |
| 👥 **Pacientes** | Lista completa, búsqueda, filtros, registro de nuevos pacientes |
| 🦷 **Expediente** | Odontograma FDI interactivo, notas clínicas con firma, antecedentes |
| 💳 **Cobros** | 96 registros reales, filtro por mes, registro de cobros con autofill |
| 📉 **Egresos** | Renta, PAU, insumos, laboratorio — registro y totales automáticos |
| 💰 **División 60/40** | Cálculo automático por cobro: Dra. Andrea vs Consultorio |
| 📊 **Reportes** | Top tratamientos, formas de pago, exportar CSV |
| 🔄 **Flujo** | Diagrama operativo paso a paso con acceso directo a cada módulo |
| 👤 **Roles** | 6 roles con permisos granulares |

---

## 📊 Datos reales integrados (Ene–May 2025)

- **$145,200** ingresos totales
- **96** tratamientos registrados
- **52+** pacientes únicos
- **$87,120** → 60% Dra. Andrea
- **$58,080** → 40% Consultorio
- **$51,780** egresos (renta, PAU, insumos, laboratorio)
- **$6,300** neto consultorio

---

## 🚀 Deploy rápido

### Netlify (1 clic)

1. Haz fork de este repo en GitHub
2. Entra a [app.netlify.com](https://app.netlify.com)
3. "New site from Git" → selecciona el repo
4. Build: dejar vacío / Publish directory: `.`
5. Click **Deploy**

### O arrastra la carpeta

1. Entra a [app.netlify.com/drop](https://app.netlify.com/drop)
2. Arrastra la carpeta del proyecto
3. ¡Listo! Netlify genera una URL pública

### GitHub Pages

```bash
git clone https://github.com/tu-usuario/dentalos
cd dentalos
# No hay build step — es HTML puro
# Activa GitHub Pages desde Settings → Pages → Branch: main / root
```

---

## 🛠 Stack

```
Frontend: HTML5 + CSS3 + Vanilla JavaScript (ES2020)
Datos:    Arrays JavaScript con datos reales del consultorio
Export:   CSV nativo vía Blob + DataURL
Deploy:   Netlify / GitHub Pages / cualquier hosting estático
```

**Sin dependencias. Sin npm. Sin bundler. Sin backend.**
Abre `index.html` directo en el navegador y funciona.

---

## 📁 Estructura

```
dentalos/
├── index.html        ← Aplicación completa (todo en un archivo)
├── netlify.toml      ← Configuración de Netlify
├── .gitignore
└── README.md
```

---

## 🔑 Credenciales demo

```
Email:      andrea@consultorio.mx
Contraseña: (cualquiera)
```

---

## 📋 Módulos con datos en vivo

Al registrar un nuevo cobro, paciente, cita o egreso, **el sistema actualiza en tiempo real**:
- El dashboard recalcula ingresos, 60/40 y saldo pendiente
- La división 60/40 incluye el nuevo registro
- Los reportes reflejan el cambio inmediatamente
- Los datos persisten durante la sesión del navegador

---

## 📤 Exportación

Todos los módulos tienen exportación CSV:
- `pagos_2025.csv` — todos los cobros
- `egresos_2025.csv` — todos los egresos
- `pacientes_2025.csv` — lista de pacientes con totales

---

## 📝 Licencia

Proyecto privado — Consultorio Dental 2025.
Desarrollado con [DentalOS](https://dentalos.netlify.app).
