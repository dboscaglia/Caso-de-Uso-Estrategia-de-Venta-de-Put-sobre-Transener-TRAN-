# 📈 Cash-Secured Put sobre Transener (TRAN)

![Mercado](https://img.shields.io/badge/Mercado-BYUMA-blue?style=flat-square)
![Activo](https://img.shields.io/badge/Activo-TRAN-green?style=flat-square)
![Estrategia](https://img.shields.io/badge/Estrategia-Cash--Secured%20Put-purple?style=flat-square)
![Riesgo](https://img.shields.io/badge/Riesgo-Medio--Alto-orange?style=flat-square)
![Uso](https://img.shields.io/badge/Uso-Educativo-lightgrey?style=flat-square)

> 📘 Documentación de un caso de uso financiero sobre venta de opciones Put cubiertas con efectivo en el mercado argentino.

---

## 📑 Tabla de contenidos

- [📌 Descripción general](#-descripción-general)
- [🎯 Objetivo](#-objetivo)
- [🧩 Ficha técnica](#-ficha-técnica)
- [⚙️ Mecánica de la estrategia](#️-mecánica-de-la-estrategia)
- [📊 Escenarios al vencimiento](#-escenarios-al-vencimiento)
- [🧮 Punto de equilibrio](#-punto-de-equilibrio)
- [✅ Ventajas](#-ventajas)
- [⚠️ Riesgos](#️-riesgos)
- [🗺️ Hoja de ruta paso a paso](#️-hoja-de-ruta-paso-a-paso)
- [📈 Métricas clave](#-métricas-clave)
- [🔁 Salida anticipada](#-salida-anticipada)
- [🚨 Advertencia de riesgo](#-advertencia-de-riesgo)
- [📂 Estructura del repositorio](#-estructura-del-repositorio)
- [🛠️ Cómo usar este repositorio](#️-cómo-usar-este-repositorio)
- [🤝 Contribuciones](#-contribuciones)
- [📬 Contacto](#-contacto)

---

## 📌 Descripción general

Este repositorio documenta una estrategia de **venta de un PUT cubierto con efectivo** sobre acciones de **Transener S.A. (TRAN)**.

La estrategia busca:

- 💵 Cobrar una prima inmediata.
- 🛡️ Generar un margen de seguridad ante caídas del activo.
- 🎯 Comprar el activo a un precio efectivo menor si la opción se ejerce.
- 📈 Optimizar el rendimiento del capital reservado con instrumentos de corto plazo.

---

## 🎯 Objetivo

- Educar sobre la mecánica de las opciones financieras en el mercado local.
- Ejemplificar una estrategia conservadora de generación de ingresos.
- Destacar la importancia del respaldo en efectivo para mitigar riesgos.
- Documentar un caso de uso replicable y adaptable.

---

## 🧩 Ficha técnica

| Parámetro | Valor |
|---|---|
| 🏢 Activo subyacente | Transener S.A. (TRAN) |
| 🏛️ Mercado | BYMA |
| 📉 Estrategia | Venta de 1 PUT |
| 📅 Vencimiento | Octubre |
| 🎯 Strike | $3,800 |
| 💰 Prima cobrada | $28,000 por lote |
| 💵 Prima por acción | $280 |
| 📦 Tamaño del lote | 100 acciones |
| 🛡️ Capital comprometido | $380,000 |
| ⚖️ Breakeven | $3,520 por acción |
| 📈 Rendimiento máximo | 7.36% sobre capital comprometido |

**Fórmula del breakeven:**

```text
Precio efectivo = Strike − Prima por acción
Precio efectivo = $3,800 − $280 = $3,520
