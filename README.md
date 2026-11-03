# Reglas de mis repositorios

Criterio único para nombrar y ordenar mis repos. Sirve para que el perfil se lea por temáticas en vez de por orden alfabético aleatorio.

```
<tema>-<nombre-en-minusculas-con-guiones>
```

- Todo en minúsculas.
- Guiones (`-`), nunca guiones bajos ni espacios.
- Sin acentos ni `ñ` (rompen URLs, badges y CI).
- Nombre corto y descriptivo. Si dudas entre el tema, elige por **origen** (universidad > temática) o **para qué sirve**.

## Temas

| Prefijo | Qué va aquí | Ejemplo |
|---|---|---|
| `uni-` | Todo lo académico: UCAM, DeSales, bachillerato, prácticas y entregas | `uni-desales-capstone` |
| `ml-` | Modelos, notebooks, visión por computador, ciencia de datos | `ml-wound-segmentation` |
| `ai-` | Aplicaciones con LLM: agentes, RAG, asistentes | `ai-rag-motor` |
| `web-` | Webs, portfolios, maquetación, páginas de cliente | `web-portfolio` |
| `lab-` | Prácticas sueltas, demos, pruebas de concepto | `lab-oracle-db` |
| `notes-` | Apuntes y vaults | `notes-vault` |

Si un repo no encaja en ninguno, no se inventa un prefijo nuevo: se usa `lab-` como cajón de sastre. Un prefijo nuevo solo si hay **tres o más** repos de esa temática.

## Índice

### `uni-` — Universidad

| Repositorio | Descripción |
|---|---|
| [uni-dam-android](https://github.com/Carlos-PC05/uni-dam-android) | Práctica final de Android para Desarrollo de Aplicaciones Móviles (UCAM) |
| [uni-dam-tarea-android](https://github.com/Carlos-PC05/uni-dam-tarea-android) | Tarea en clase de DAM |
| [uni-desales-capstone](https://github.com/Carlos-PC05/uni-desales-capstone) | Marketplace universitario con Flask |
| [uni-desales-cs362-ml](https://github.com/Carlos-PC05/uni-desales-cs362-ml) | Proyecto final de CS-362 Intro to Machine Learning |
| [uni-desales-wpd-portfolio](https://github.com/Carlos-PC05/uni-desales-wpd-portfolio) | Portfolio final de Web Page Design (DeSales) |
| [uni-desales-scs-portfolio](https://github.com/Carlos-PC05/uni-desales-scs-portfolio) | Portfolio final de Senior Coordinating Seminar (DeSales) |
| [uni-pva](https://github.com/Carlos-PC05/uni-pva) | Práctica final de Programación Visual Avanzada |
| [uni-tic2-maquetacion](https://github.com/Carlos-PC05/uni-tic2-maquetacion) | Maquetación web para TIC 2º Bachillerato |
| [uni-test](https://github.com/Carlos-PC05/uni-test) | Repositorio de pruebas |

### `ml-` — Machine learning

| Repositorio | Descripción |
|---|---|
| [ml-wound-segmentation](https://github.com/Carlos-PC05/ml-wound-segmentation) | Segmentación de heridas con PyTorch |
| [ml-pneumonia-detection](https://github.com/Carlos-PC05/ml-pneumonia-detection) | Detección de neumonía en radiografías con Keras |

### `ai-` — Aplicaciones con LLM

| Repositorio | Descripción |
|---|---|
| [ai-rag-motor](https://github.com/Carlos-PC05/ai-rag-motor) | Backend de búsqueda semántica y generación sobre documentos propios |
| [ai-agente-local](https://github.com/Carlos-PC05/ai-agente-local) | Agente de IA ligero para administrar el equipo local |

### `web-` — Web

| Repositorio | Descripción |
|---|---|
| [web-portfolio](https://github.com/Carlos-PC05/web-portfolio) | Portfolio personal |
| [web-portfolio-ivan](https://github.com/Carlos-PC05/web-portfolio-ivan) | Portfolio de estudiante de física |
| [web-vesta](https://github.com/Carlos-PC05/web-vesta) | Web del proyecto Vesta |
| [web-gifersa-mock](https://github.com/Carlos-PC05/web-gifersa-mock) | Mock de la página web de Gifersa |

### `lab-` — Experimentos y demos

| Repositorio | Descripción |
|---|---|
| [lab-oracle-db](https://github.com/Carlos-PC05/lab-oracle-db) | Laboratorio de Oracle Database |
| [lab-report-audit](https://github.com/Carlos-PC05/lab-report-audit) | Laboratorio de auditoría y reportes |
| [lab-burp-suite-demo](https://github.com/Carlos-PC05/lab-burp-suite-demo) | Demo de formulario para el proyecto final de ciberseguridad |
| [lab-api-basica](https://github.com/Carlos-PC05/lab-api-basica) | API básica sin IA |
| [lab-react-tutorial](https://github.com/Carlos-PC05/lab-react-tutorial) | Aprendiendo React + TypeScript |

## Excepciones

| Repositorio | Motivo |
|---|---|
| [Carlos-PC05](https://github.com/Carlos-PC05/Carlos-PC05) | El repo de perfil **debe** llamarse igual que el usuario |
| [GLM-OCR-AMALIOMETRIA](https://github.com/Carlos-PC05/GLM-OCR-AMALIOMETRIA) | Es un fork: el nombre debe coincidir con el upstream |
| [ObsidianVault](https://github.com/Carlos-PC05/ObsidianVault) | Vault de Obsidian; nombre fijado por la app |
| [estudio-itz](https://github.com/Carlos-PC05/estudio-itz) | Tiene GitHub Pages con URL compartida con el cliente |

## Cómo añadir un repositorio nuevo

1. Elegir el tema de la tabla.
2. `gh repo create Carlos-PC05/<tema>-<nombre> --public`
3. Añadirlo al índice de este README.
4. Poner descripción en GitHub: se ve en el perfil y en los listados.
5. Si es una web publicable, activar Pages y apuntar la URL en el índice.

## Renombrados (2026-11-03)

GitHub mantiene redirecciones de las URLs antiguas, pero **no reutilizar nunca un nombre antiguo**: el redirect moriría y los enlaces viejos pasarían a apuntar al repo nuevo.

| Antes | Ahora |
|---|---|
| practica-moviles_android | uni-dam-android |
| tareaclaseandroid | uni-dam-tarea-android |
| CapstoneProject | uni-desales-capstone |
| FinalProjectCS-362 | uni-desales-cs362-ml |
| Portfolio_WPD | uni-desales-wpd-portfolio |
| Portfolio_SCS | uni-desales-scs-portfolio |
| PracticaPVA | uni-pva |
| TIC2 | uni-tic2-maquetacion |
| test-uni | uni-test |
| WoundSegmentation | ml-wound-segmentation |
| Pneumonia | ml-pneumonia-detection |
| motor-RAG | ai-rag-motor |
| agente-IA-local | ai-agente-local |
| portfolio | web-portfolio |
| portfolioIvan | web-portfolio-ivan |
| VestaWeb | web-vesta |
| gifersa-mock | web-gifersa-mock |
| oracle-database-lab | lab-oracle-db |
| reportaudit-lab | lab-report-audit |
| BurpSuitDemo | lab-burp-suite-demo |
| api-sin-IA | lab-api-basica |
| ReactTutorial | lab-react-tutorial |
