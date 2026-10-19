# Códigos para Práctico — Prof. Cecilia Mateu (LAPIS 2026)

Repositorio de materiales y códigos para el práctico de la Profesora Cecilia Mateu (*RR Lyrae stars: Lessons and outlook from the Milky Way to the Local Group*) en la escuela de astrofísica **XII LAPIS 2026**.

## Proyecto y Datos

- **Proyecto**: Exploración de la estructura tridimensional de la Vía Láctea y las Nubes de Magallanes (LMC/SMC) usando estimadores no paramétricos de densidad de estrellas RR Lyrae, corrección por función de selección/completitud y búsqueda de la estela gravitacional de la LMC.
- **Datos y catálogos**: Serán provistos por la profesora.

## Software y Estructura

- `rrl_completeness/` — Submódulo con el fork de [cmateu/rrl_completeness](https://github.com/cmateu/rrl_completeness) en [`LAPIS-2026/rrl_completeness`](https://github.com/LAPIS-2026/rrl_completeness).

## Lecturas Previas Sugeridas

- [Lucey et al. (2026)](https://ui.adsabs.harvard.edu/abs/2026AJ....171..249L/abstract)
- [Cabrera-Gadea, Mateu & Ramos (2025)](https://www.aanda.org/articles/aa/full_html/2025/09/aa52736-24/aa52736-24.html)
- [Mateu et al. (2020)](https://academic.oup.com/mnras/article/496/3/3291/5856583)
- [Mateu et al. (2024, AAS notes)](https://iopscience.iop.org/article/10.3847/2515-5172/ad3540)
- [Ivezić et al. (2005, Appendix B)](https://iopscience.iop.org/article/10.1086/427392)

## Cómo clonar este repositorio (incluyendo submódulos)

```bash
git clone --recurse-submodules https://github.com/LAPIS-2026/ceciliamateu.git
```

Si ya clonaste el repositorio sin `--recurse-submodules`, inicializa y descarga todos los submódulos con:

```bash
git submodule update --init --recursive
```
