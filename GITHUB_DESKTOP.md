# Subir Sistema_ATD_ACR con GitHub Desktop

Repositorio **producto final** (3 regiones). El repo solo Loreto sigue en `ATD-Loreto-GFP`.

## 1. Crear repositorio en GitHub.com

1. **New repository**
2. Nombre sugerido: `SATD-ACR-Peru` o `Sistema-ATD-ACR-GFP`
3. Descripción: *Sistema de Alertas Tempranas de Deforestación para Áreas de Conservación Regional — Aplicación en San Martín, Loreto y Cusco*
4. **No** marque "Add README" (ya existe)
5. Copie la URL, p. ej. `https://github.com/SU_USUARIO/SATD-ACR-Peru.git`

## 2. GitHub Desktop

1. **File → Add local repository**
2. Carpeta: `...\salidas\Sistema_ATD_ACR`
3. Si no es repo git: **create a repository** (respete `.gitignore` existente)

## 3. Primer commit

```
Publicar SATD ACR: San Martín, Loreto y Cusco — H1, H2, H3, GDB y guías
```

## 4. Publish repository → Push

## Regenerar antes de publicar

Desde `salidas/`:

```bash
python generar_paquete_sistema_acr.py --distribucion
```

`--distribucion` copia GDB físicas (recomendado para GitHub/zip).

## Qué NO se sube

Ver `.gitignore`: PDFs de trabajo en `pdfs/`, locks ArcGIS, salidas temporales.
