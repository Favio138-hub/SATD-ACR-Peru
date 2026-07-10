<p align="center">
  <img src="regiones/ATD_Loreto/logos/logo_gfp.png" alt="GFP Subnacional" height="80" />
</p>

<h1 align="center">Sistema de Alertas Tempranas de Deforestación para Áreas de Conservación Regional</h1>

<p align="center">
  <strong>Aplicación en San Martín, Loreto y Cusco</strong><br/>
  <em>GFP Subnacional · Suiza apoyando al Perú</em>
</p>

<p align="center">
  <a href="INDICE.html"><strong>Abrir índice del sistema</strong></a>
</p>

<p align="center">
  <a href="#regiones">Regiones</a> ·
  <a href="#inicio-rápido">Inicio rápido</a> ·
  <a href="INDICE.html">Índice HTML</a> ·
  <a href="https://github.com/Favio138-hub/SATD-ACR-Peru">GitHub</a>
</p>

---

## ¿Qué es este repositorio?

Producto **institucional final** del flujo ATD (Alertas Tempranas de Deforestación) en **Áreas de Conservación Regional** de tres regiones del Perú. Cada región es un paquete autocontenido para ArcGIS Pro 3.x con geodatabases, toolbox H1–H3, logos y guías.

| Región | Carpeta | ACR |
|--------|---------|-----|
| **Loreto** | [`regiones/ATD_Loreto/`](regiones/ATD_Loreto/) | Ampiyacu, Tamshiyacu Tahuayo, Maijuna Kichwa, Alto Nanay |
| **San Martín** | [`regiones/ATD_San_Martin/`](regiones/ATD_San_Martin/) | Cordillera Escalera, BOSHUMI |
| **Cusco** | [`regiones/ATD_Cuzco/`](regiones/ATD_Cuzco/) | Choquequirao, Chuyapi Urusayhua, Q'eros Kosnipata |

### Herramientas (por región)

| | Herramienta | Función |
|---|-------------|---------|
| **H1** | Descarga Geobosques | Inserta alertas en la GDB |
| **H2** | Visor satelital | Fotointerpretación antes/después (Planet, S2, Landsat) |
| **H3** | Reporte PDF | Diagnóstico + informe institucional |

---

## Inicio rápido

1. Elija su región en [`INDICE.html`](INDICE.html) o entre a `regiones/ATD_<Region>/`.
2. Abra **solo esa carpeta** en ArcGIS Pro (no mueva el toolbox fuera).
3. **Catalog → Add Toolbox** → los tres `.pyt` en `toolbox/`.
4. Lea `guia/GUIA_ATD_<REGION>.html` de la región elegida.
5. Ejecute `DIAGNOSTICO_ENTORNO.bat` antes del primer uso.

---

## Desarrollo vs producto

| Carpeta | Uso |
|---------|-----|
| `Informe_ATD_preliminar/` | Desarrollo, GDB de las 3 regiones, scripts de mantenimiento |
| `Sistema_ATD_ACR/` (este repo) | **Producto final** para presentación e instalación |
| `ATD_Loreto/` (repo aparte) | Paquete Loreto solo — [ATD-Loreto-GFP](https://github.com/Favio138-hub/ATD-Loreto-GFP) |

Regenerar todo desde `salidas/`:

```bash
python generar_paquete_sistema_acr.py --distribucion
```

---

## Créditos

**GFP Subnacional** · GORE Loreto, San Martín y Cusco · SECO / Basel Institute

<sub>Versión 2026 · Uso institucional ATD ACR</sub>
