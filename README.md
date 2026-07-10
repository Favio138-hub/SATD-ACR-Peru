<p align="center">
  <img src="regiones/ATD_Loreto/logos/logo_gfp.png" alt="GFP Subnacional" height="88" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="regiones/ATD_Loreto/logos/logo_SECO.jpg" alt="SECO" height="72" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="regiones/ATD_Loreto/logos/logo_basel.png" alt="Basel Institute" height="72" />
</p>

<h1 align="center">Sistema de Alertas Tempranas de Deforestación<br/>para Áreas de Conservación Regional</h1>

<p align="center">
  <strong>Aplicación en San Martín, Loreto y Cusco</strong><br/>
  <em>GFP Subnacional · Suiza apoyando al Perú</em>
</p>

<p align="center">
  <a href="INDICE.html"><strong>Abrir el índice del sistema (recomendado)</strong></a>
</p>

<p align="center">
  <a href="#para-quién-es">Para quién es</a> ·
  <a href="#cómo-trabajar-en-3-pasos">Cómo trabajar</a> ·
  <a href="#regiones">Regiones</a> ·
  <a href="#loreto-en-detalle">Loreto en detalle</a> ·
  <a href="#qué-incluye-cada-paquete">Qué incluye</a>
</p>

---

## Para quién es

Este sistema está pensado para **personal de las ACR** y equipos de monitoreo regional que necesitan:

1. Bajar las alertas de deforestación  
2. Revisarlas con imágenes satelitales  
3. Generar el **informe PDF oficial**

No necesita ser programador. Solo necesita **ArcGIS Pro** y seguir la guía de su región.

---

## Cómo trabajar (en 3 pasos)

En **todas** las regiones el flujo es el mismo:

| Paso | Herramienta | Qué hace usted |
|:----:|-------------|---------------|
| **1** | **H1 — Descarga Geobosques** | Trae las alertas del periodo y las guarda en la base de datos de su región |
| **2** | **H2 — Visor satelital** | Compara imágenes *antes* y *después*, clasifica la alerta (antrópico, natural o falsa alerta) |
| **3** | **H3 — Reporte PDF** | Genera el informe institucional listo para entregar |

```text
  Alertas Geobosques  →  Fotointerpretación  →  Informe PDF
         (H1)                   (H2)                (H3)
```

### Primera vez (instalación simple)

1. Descargue este repositorio (**Code → Download ZIP**) o clónelo.  
2. Abra el archivo [`INDICE.html`](INDICE.html) y elija **su región**.  
3. En ArcGIS Pro, abra **solo la carpeta de su región** (por ejemplo `regiones/ATD_Loreto/`).  
4. En **Catálogo → Toolboxes → Add Toolbox**, agregue los tres archivos de la carpeta `toolbox/`.  
5. Ejecute `DIAGNOSTICO_ENTORNO.bat` (está en la carpeta de su región).  
6. Abra la **guía HTML** de su región y siga el ejemplo.

> **Importante:** no mueva solo la carpeta `toolbox/` a otro sitio. Trabaje siempre con la carpeta completa de la región (datos + logos + herramientas juntos).

---

## Regiones

| Región | ACR incluidas | Carpeta de trabajo | Guía | PDF de ejemplo |
|--------|---------------|--------------------|------|----------------|
| **Loreto** | Ampiyacu Apayacu, Tamshiyacu Tahuayo, Maijuna Kichwa, Alto Nanay | [`regiones/ATD_Loreto/`](regiones/ATD_Loreto/) | [Guía Loreto](regiones/ATD_Loreto/guia/GUIA_ATD_LORETO.html) | [Ver PDF](regiones/ATD_Loreto/docs/EJEMPLO_reporte_ATD_Loreto.pdf) |
| **San Martín** | Cordillera Escalera (CE), BOSHUMI | [`regiones/ATD_San_Martin/`](regiones/ATD_San_Martin/) | [Guía San Martín](regiones/ATD_San_Martin/guia/GUIA_ATD_SAN_MARTIN.html) | [Ver PDF](regiones/ATD_San_Martin/docs/EJEMPLO_reporte_ATD_San_Martin.pdf) |
| **Cusco** | Choquequirao, Chuyapi Urusayhua, Q'eros Kosnipata | [`regiones/ATD_Cuzco/`](regiones/ATD_Cuzco/) | [Guía Cusco](regiones/ATD_Cuzco/guia/GUIA_ATD_CUZCO.html) | [Ver PDF](regiones/ATD_Cuzco/docs/EJEMPLO_reporte_ATD_Cuzco.pdf) |

---

## Loreto en detalle

Loreto es el paquete **más completo** del sistema: sirve de referencia para las otras regiones y para talleres GFP.

### ACR de Loreto

| Código | Área de Conservación Regional |
|--------|-------------------------------|
| **ACR09** | Ampiyacu Apayacu |
| **ACR04** | Comunal Tamshiyacu Tahuayo |
| **ACR17** | Maijuna Kichwa |
| **ACR10** | Alto Nanay Pintuyacu Chambira |

### Qué trae el paquete Loreto

| Contenido | Para qué sirve |
|-----------|----------------|
| **Toolbox H1, H2 y H3** | Flujo completo: descarga → fotointerpretación → PDF |
| **GDB de línea base** (`Linea_base_deforestación_Loreto.gdb`) | Alertas vigentes (`MonitoreoDeforestacion`) e histórico (`MonitoreoDeforestacionAcumulado`), límites ACR y capas de apoyo |
| **GDB de gestión** (`GestionACR_16012024.gdb`) | Información de gestión / lugares poblados para el PDF |
| **Logos** (GORE, GRRNGA, GFP, SECO, Basel, logos ACR) | Encabezado institucional del informe |
| **Guía HTML** | Paso a paso en lenguaje claro |
| **PDF de ejemplo** | Cómo debe verse el reporte final |
| **Gráficos 2026** | Causas de deforestación y resumen de alertas |

### Flujo recomendado en Loreto

| Momento | Qué hacer |
|---------|-----------|
| **Demo rápida (≈ 5 min)** | Saltar H1 si ya hay alertas en la GDB → abrir **H2** con 1 polígono → generar **H3** y comparar con el PDF de ejemplo |
| **Taller / trabajo real** | **H1** descarga Geobosques → **H2** clasifica causa y confianza → **H3** Diagnóstico Pre-Vuelo + Generar Reporte |
| **Entregable** | PDF en `pdfs/` + documentación de apoyo en `documentacion_atd/` |

### Documentación visual Loreto 2026

<p align="center">
  <img src="docs/cuadro_causas_deforestacion_loreto_2026.png" alt="Causas de deforestación ACR Loreto 2026" width="720" />
</p>

<p align="center">
  <em>Cuadro de causas de deforestación — ACR Loreto 2026</em>
</p>

<p align="center">
  <img src="docs/grafico_alertas_atd_acr_loreto_2026.png" alt="Gráfico de alertas ATD Loreto 2026" width="720" />
</p>

<p align="center">
  <em>Alertas ATD por ACR — Loreto 2026</em>
</p>

Más detalle operativo: [`regiones/ATD_Loreto/README.md`](regiones/ATD_Loreto/README.md) y la [guía completa](regiones/ATD_Loreto/guia/GUIA_ATD_LORETO.html).

---

## Qué incluye cada paquete

Cada carpeta regional es **autocontenida** (todo lo necesario para trabajar):

| Carpeta | Contenido |
|---------|-----------|
| `toolbox/` | Herramientas H1, H2 y H3 para ArcGIS Pro |
| `GDB/` | Bases de datos geográficas de la región |
| `logos/` | Logos institucionales y de las ACR |
| `guia/` | Guía de uso en HTML (abrir con el navegador) |
| `docs/` | PDF de ejemplo (y gráficos en Loreto) |
| `pdfs/` | Aquí se guardan los reportes que usted genere |
| `DIAGNOSTICO_ENTORNO.bat` | Verifica que el equipo esté listo |

### Estado del producto (verificado)

| Componente | Loreto | San Martín | Cusco |
|------------|:------:|:----------:|:-----:|
| Toolbox H1 · H2 · H3 | Sí | Sí | Sí |
| Geodatabases | 2 | 2 | 1 |
| Logos regionales | Sí | Sí | Sí |
| Guía HTML | Sí | Sí | Sí |
| PDF de ejemplo | Sí | Sí | Sí |

**Sí: el sistema está armado de punta a punta** (herramientas + datos + logos + guías) para las tres regiones.

---

## Tamaño aproximado

| Paquete | Peso aproximado |
|---------|-----------------|
| **Todo el sistema** (3 regiones) | **≈ 2,9 GB** |
| Solo Loreto | ≈ 1,8 GB |
| Solo San Martín | ≈ 0,7 GB |
| Solo Cusco | ≈ 0,4 GB |

> La mayor parte del peso son las **geodatabases**. En GitHub los archivos grandes van con **Git LFS**.

---

## Requisitos

- **ArcGIS Pro 3.x**
- Conexión a internet para H1 (Geobosques) y para imágenes satelitales en H2  
- *(Opcional)* clave Planet si desea usar imágenes Planet en el visor

Si algo falla al abrir las herramientas, ejecute primero `DIAGNOSTICO_ENTORNO.bat` en la carpeta de su región.

---

## Otros repositorios

| Repositorio | Uso |
|-------------|-----|
| **Este** — [SATD-ACR-Peru](https://github.com/Favio138-hub/SATD-ACR-Peru) | Producto final con las **3 regiones** |
| [ATD-Loreto-GFP](https://github.com/Favio138-hub/ATD-Loreto-GFP) | Paquete **solo Loreto** (capacitaciones / entrega regional) |

---

## Créditos

**GFP Subnacional** · GORE Loreto, San Martín y Cusco · SECO / Basel Institute on Governance

<sub>Versión 2026 · Uso institucional ATD ACR</sub>
