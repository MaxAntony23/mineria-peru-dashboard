# Dashboard Minería Perú 🇵🇪⛏️

Dashboard interactivo con los principales indicadores del sector minero peruano, construido con HTML, CSS y Chart.js — sin frameworks, sin dependencias externas más allá de CDN.

## Demo en vivo

**[Ver Dashboard](https://MaxAntony23.github.io/mineria-peru-dashboard/)**

---

## Características

- **Ticker de precios** — Oro, Plata, Cobre, Zinc, Plomo, Molibdeno
- **KPI Cards animadas** — Producción, exportaciones, empleo, PBI
- **8 tipos de gráficos interactivos:**
  - Línea con tabs (precio del oro 2018–2025)
  - Donut (cuota de mercado por empresa)
  - Barras verticales (producción por mineral)
  - Radar (ranking mundial de Perú)
  - Área apilada (tendencia histórica)
  - Barras horizontales (top regiones)
  - Burbuja (volumen vs valor de exportación)
  - Barras apiladas (ingresos fiscales)
- **Tabla interactiva** — Top 10 empresas mineras
- **Cards de regiones** — Áncash, Arequipa, Apurímac, Cajamarca y más
- **Partículas animadas** de fondo
- **Tema oscuro elegante** — totalmente responsive

---

## Tecnologías

| Tecnología | Uso |
|---|---|
| HTML5 / CSS3 | Estructura y estilos |
| JavaScript (Vanilla) | Lógica e interactividad |
| [Chart.js 4.4](https://www.chartjs.org/) | Gráficos |
| CSS Animations | Partículas, counters, transiciones |

> **Sin frameworks.** Un único archivo `.html` autónomo.

---

## Datos incluidos

Los datos son referenciales basados en fuentes oficiales:

- **MINEM** — Ministerio de Energía y Minas del Perú
- **BCRP** — Banco Central de Reserva del Perú
- **Kitco / MetalPriceAPI** — Precios de metales 2024–2025
- **InfoMine** — Rankings mundiales

> Los precios del ticker son estáticos (snapshot Marzo 2025). Para integración con API en tiempo real, ver sección de contribuciones.

---

## Cómo usar

### Opción 1 — Directamente en el navegador

Clona el repositorio y abre el archivo en tu navegador:

```bash
git clone https://github.com/MaxAntony23/mineria-peru-dashboard.git
cd mineria-peru-dashboard
# Abre mineria-peru-dashboard.html en tu navegador
```

### Opción 2 — GitHub Pages (recomendado)

El dashboard está publicado automáticamente en GitHub Pages. Ve a:

```
https://MaxAntony23.github.io/mineria-peru-dashboard/
```

---

## Estructura del proyecto

```
mineria-peru-dashboard/
├── mineria-peru-dashboard.html   # Archivo principal (todo en uno)
└── README.md                     # Este archivo
```

---

## Roadmap

- [ ] Integrar API de precios en tiempo real (MetalPriceAPI / Alpha Vantage)
- [ ] Agregar mapa interactivo de regiones mineras
- [ ] Filtros por año y mineral
- [ ] Exportar gráficos como imagen PNG
- [ ] Modo claro / oscuro

---

## Contribuciones

¿Tienes ideas o mejoras? ¡Los PRs son bienvenidos!

1. Fork este repositorio
2. Crea una rama: `git checkout -b feature/nueva-funcionalidad`
3. Commit: `git commit -m 'Add: nueva funcionalidad'`
4. Push: `git push origin feature/nueva-funcionalidad`
5. Abre un Pull Request

---

## Licencia

MIT License — libre para uso personal y comercial.

---

*Desarrollado con Claude Code · Datos: MINEM, BCRP, Kitco · Marzo 2025*
