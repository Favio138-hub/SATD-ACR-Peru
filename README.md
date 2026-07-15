<p align="center">
  <img src="regiones/ATD_Loreto/logos/logo_gfp.png" alt="GFP Subnacional" height="88" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="regiones/ATD_Loreto/logos/logo_SECO.jpg" alt="SECO" height="72" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="regiones/ATD_Loreto/logos/logo_basel.png" alt="Basel Institute" height="72" />
</p>

<h1 align="center">Alertas Tempranas de Deforestación<br/>para Áreas de Conservación Regional</h1>

<p align="center">
  <strong>Aplicación en San Martín, Loreto y Cusco</strong><br/>
  <em>GFP Subnacional · Suiza apoyando al Perú</em>
</p>

<p align="center">
  <a href="https://favio138-hub.github.io/SATD-ACR-Peru/docs/GUIA_VISUAL.html"><strong>Abrir guía visual completa (con capturas H1 · H2 · H3)</strong></a><br/>
  <a href="https://favio138-hub.github.io/SATD-ACR-Peru/INDICE.html">Índice del sistema</a><br/>
  <sub>Si el enlace aún no carga: <a href="https://html-preview.github.io/?url=https://raw.githubusercontent.com/Favio138-hub/SATD-ACR-Peru/main/docs/GUIA_VISUAL.html">vista previa HTML</a> · o abra <code>INDICE.html</code> en su PC</sub>
</p>

<p align="center">
  <a href="#para-quién-es">Para quién es</a> ·
  <a href="#cómo-trabajar-en-3-pasos">Cómo trabajar</a> ·
  <a href="#las-tres-regiones">Las 3 regiones</a> ·
  <a href="#descarga-y-espacio-en-disco">Descarga</a> ·
  <a href="#qué-incluye-cada-paquete">Qué incluye</a>
</p>

---

## Para quién es

Este sistema es para el **personal de las ACR** y equipos de monitoreo regional.  
No necesita ser programador: solo **ArcGIS Pro** y seguir la guía de su región.

En las **tres regiones** el trabajo es el mismo:

1. Bajar alertas  
2. Revisarlas con satélite  
3. Generar el **informe PDF oficial**

---

## Cómo trabajar (en 3 pasos)

| Paso | Herramienta | Qué hace usted |
|:----:|-------------|----------------|
| **1** | **H1 — Geobosques** | Descarga alertas del periodo a la base de datos |
| **2** | **H2 — Visor satelital** | Compara ANTES / DESPUÉS y clasifica la alerta |
| **3** | **H3 — Reporte PDF** | Genera el informe técnico institucional |

```text
  Alertas Geobosques  →  Fotointerpretación  →  Informe PDF
         (H1)                   (H2)                (H3)
```

### Guía visual (recomendado)

Abra la **[guía visual completa](docs/GUIA_VISUAL.html)**: muestra capturas reales de H1, del visor H2 y del PDF final H3, con el mismo flujo para San Martín, Loreto y Cusco.

<p align="center">
  <img src="docs/guia/guia_h1_descarga_geobosques.png" alt="H1 Descarga Geobosques" width="520" />
</p>
<p align="center"><em>H1 — Descarga de alertas en ArcGIS Pro</em></p>

<p align="center">
  <img src="docs/guia/guia_h2_visor_antes_despues.png" alt="H2 Visor satelital" width="720" />
</p>
<p align="center"><em>H2 — Visor satelital ANTES / DESPUÉS</em></p>

<p align="center">
  <img src="docs/guia/guia_h3_reporte_pdf.png" alt="H3 Reporte PDF" width="720" />
</p>
<p align="center"><em>H3 — Reporte PDF institucional (resultado final)</em></p>

### Primera vez

1. Descargue el repositorio (**Code → Download ZIP**) o clónelo.  
2. Abra [`INDICE.html`](INDICE.html) y elija **su región**.  
3. En ArcGIS Pro abra **solo la carpeta de esa región**.  
4. **Catálogo → Toolboxes → Add Toolbox** → agregue H1, H2 y H3.  
5. Ejecute `DIAGNOSTICO_ENTORNO.bat`.  
6. Siga la [guía visual](docs/GUIA_VISUAL.html) o la guía HTML de su región.

> **Importante:** no mueva solo `toolbox/`. Trabaje siempre con la carpeta completa de la región.

---

## Las tres regiones

| Región | ACR | Carpeta | Guía | PDF ejemplo |
|--------|-----|---------|------|-------------|
| **Loreto** | Ampiyacu, Tamshiyacu Tahuayo, Maijuna Kichwa, Alto Nanay | [`regiones/ATD_Loreto/`](regiones/ATD_Loreto/) | [Guía](regiones/ATD_Loreto/guia/GUIA_ATD_LORETO.html) | [PDF](regiones/ATD_Loreto/docs/EJEMPLO_reporte_ATD_Loreto.pdf) |
| **San Martín** | Cordillera Escalera (CE), BOSHUMI | [`regiones/ATD_San_Martin/`](regiones/ATD_San_Martin/) | [Guía](regiones/ATD_San_Martin/guia/GUIA_ATD_SAN_MARTIN.html) | [PDF](regiones/ATD_San_Martin/docs/EJEMPLO_reporte_ATD_San_Martin.pdf) |
| **Cusco** | Choquequirao, Chuyapi Urusayhua, Q'eros Kosnipata | [`regiones/ATD_Cuzco/`](regiones/ATD_Cuzco/) | [Guía](regiones/ATD_Cuzco/guia/GUIA_ATD_CUZCO.html) | [PDF](regiones/ATD_Cuzco/docs/EJEMPLO_reporte_ATD_Cuzco.pdf) |

Las tres tienen **toolbox H1–H2–H3**, GDB, logos, guía y PDF de ejemplo. Loreto es el paquete de referencia (más documentado), pero **el flujo es el mismo en las tres**.

### Documentación visual Loreto 2026 (referencia nacional)

<p align="center">
  <img src="docs/cuadro_causas_deforestacion_loreto_2026.png" alt="Causas de deforestación ACR Loreto 2026" width="700" />
</p>
<p align="center">
  <img src="docs/grafico_alertas_atd_acr_loreto_2026.png" alt="Alertas ATD Loreto 2026" width="700" />
</p>

---

## Descarga y espacio en disco

Cada región es un paquete listo para trabajar. El repositorio completo (las tres regiones) ocupa aproximadamente **180 MB**.

| Si trabaja en… | Carpeta | Tamaño aproximado |
|----------------|---------|------------------:|
| **Loreto** | `regiones/ATD_Loreto/` | ~45 MB |
| **San Martín** | `regiones/ATD_San_Martin/` | ~65 MB |
| **Cusco** | `regiones/ATD_Cuzco/` | ~67 MB |

**Consejo:** si solo necesita una región, descargue el ZIP del repositorio y conserve únicamente la carpeta de su región; las otras puede eliminarlas en su equipo.

### Qué encontrará en su carpeta
Herramientas H1–H2–H3, geodatabases de trabajo, logos institucionales, guía de uso y un PDF de ejemplo.

### Qué se genera al usar el sistema
Al fotointerpretar y emitir reportes, ArcGIS Pro creará archivos en `pdfs/`, `imagenes_sentinel/` y carpetas similares. Esos archivos son **suyos** (resultados de su monitoreo) y pueden ocupar más espacio con el tiempo; no forman parte de la descarga inicial.


---

## Qué incluye cada paquete

| Carpeta | En la descarga | Contenido |
|---------|:--------------:|-----------|
| `toolbox/` | Sí | H1, H2, H3 |
| `GDB/` | Sí | Datos base de la región |
| `logos/` | Sí | Logos del informe |
| `guia/` · `docs/` | Sí | Guías + 1 PDF de ejemplo |
| `pdfs/` | Se crea al trabajar | Reportes que usted genere |
| `imagenes_sentinel/` | Se crea al trabajar | Exportaciones del visor |
| `mapas/` · `documentacion_atd/` | Se crea al trabajar | Archivos de apoyo temporales |

### Estado verificado

| Componente | Loreto | San Martín | Cusco |
|------------|:------:|:----------:|:-----:|
| Toolbox H1 · H2 · H3 | Sí | Sí | Sí |
| Geodatabases | 2 | 2 | 1 |
| Logos | Sí | Sí | Sí |
| Guía HTML | Sí | Sí | Sí |
| PDF de ejemplo | Sí | Sí | Sí |

**Sí: el producto está armado de punta a punta** (herramientas + datos + logos + guías) para las tres regiones.

---

## Requisitos

- ArcGIS Pro 3.x  
- Internet para H1 (Geobosques) y para imágenes en H2  
- *(Opcional)* clave Planet para el visor  

Si algo falla: ejecute `DIAGNOSTICO_ENTORNO.bat` en la carpeta de su región.

---

## Otros repositorios

| Repositorio | Uso |
|-------------|-----|
| **Este** — [SATD-ACR-Peru](https://github.com/Favio138-hub/SATD-ACR-Peru) | Producto final **3 regiones** |
| [ATD-Loreto-GFP](https://github.com/Favio138-hub/ATD-Loreto-GFP) | Solo Loreto (~25–35 MB) |

---

## Créditos

**GFP Subnacional** · GORE Loreto, San Martín y Cusco · SECO / Basel Institute on Governance

<sub>Versión 2026 · Uso institucional ATD ACR</sub>
