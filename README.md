# Apunts de Stop Motion - MkDocs Material

Projecte preparat per a la tasca final de MkDocs Material.

## Què inclou

- Tema `material` configurat en `mkdocs.yml`.
- Búsqueda interna amb el plugin `search`.
- Panells i pestanyes de navegació.
- Canvi entre tema clar i tema fosc.
- Admonitions normals i plegables.
- Fragments de codi amb numeració de línies i botó de còpia.
- Diagrames Mermaid.
- Plugin `page-to-pdf` i botó de descàrrega del PDF.
- PDF generat: `docs/pdf/apunts_stop_motion_material.pdf`.

## Enllaços de lliurament

Web publicada:
https://arialandete.github.io/Apunts-Stop-Motion/

Repositori amb les fonts i `mkdocs.yml`:
https://github.com/arialandete/Apunts-Stop-Motion

## Instal·lació local

```bash
pip install -r requirements.txt
mkdocs serve
```

## Publicació en GitHub Pages

El projecte inclou un workflow en `.github/workflows/deploy.yml`. En GitHub cal activar:

`Settings > Pages > Build and deployment > GitHub Actions`
