# Vivienda y habitabilidad en el Perú hacia 2030

Investigación independiente del Dr. Magdiel Torres Vanegas.

Visor y base documental reproducible Vivienda Perú 2026. Autor: Dr. Magdiel Torres Vanegas, ORCID https://orcid.org/0000-0002-7913-214X.

Versión 1.0.2. Evidencia hasta 2026-10-26; auditoría 2026-10-30.

## Alcance

9 fuentes oficiales, 76 observaciones, 7 cálculos y 12 hallazgos. Estudio documental descriptivo y analítico. No es evaluación causal, revisión sistemática, auditoría de ejecución física ni pronóstico a 2030.

## Uso

El repositorio contiene la fuente completa en Vivienda_Peru_2026_Datos_Protocolo_Visor_v1_0_2.zip. Extraiga ese archivo y abra Vivienda_Peru_2026/docs/index.html en un navegador. Funciona sin servicios externos ni conexión para la consulta; los enlaces a fuentes requieren internet. La base canónica está en docs/data/dataset.json y los CSV equivalentes. SQLite y Excel están en docs/downloads. Ejecute `python scripts/validate.py` para comprobar integridad y derivaciones. El visor conserva accesibilidad, filtros y exportación de CSV y SVG.

## Trazabilidad

Cada observación incluye source_id, localizador, población, base, año, periodo, estado y límites. Las banderas distinguen precisión rural y cambios de levantamiento. Las cifras reportadas, parciales, convocadas y programadas no se suman. La verificación del acceso se publica por fuente, sin afirmar que todo documento fue preservado íntegramente.

## Protocolo y archivo
El protocolo documenta retrospectivamente la línea base y propone una ampliación futura. Registro público OSF: https://doi.org/10.17605/OSF.IO/KWMA5 . Archivo de la release v1.0.2 generado por la integración GitHub–Zenodo: https://doi.org/10.5281/zenodo.23829470 . DOI de todas las versiones: https://doi.org/10.5281/zenodo.23829469 .

La release inmutable corresponde al commit `9abe830e64e00109d7181bb958cb11e455a696a0`: https://github.com/vanegasmagdiel/visor-vivienda-peru-2030/releases/tag/v1.0.2 . Los enlaces de publicación incorporados después de recibir el DOI se mantienen en main y en `docs/publication.json`; los datos, cálculos y protocolo no cambiaron. Para reproducir exactamente el snapshot citable, descargue el archivo del registro Zenodo o de la etiqueta v1.0.2.

## Referencia de diseño

Se toma como referencia el portal Democracia Perú 2020-2030 v2.1.1 del mismo autor: tipografía editorial, fondo marfil, acento ocre, trazabilidad y descargas. No se reutilizan sus datos, hipótesis, escenarios ni DOI.

## Licencias

Código MIT. Documentación y compilación original CC BY 4.0. Datos y documentos originales de terceros conservan sus condiciones. El manuscrito SCIÉNDO no se deposita como publicación o preprint en esta release.

## Estado de entrega
Visor publicado: https://vanegasmagdiel.github.io/visor-vivienda-peru-2030/ . Registro OSF público: https://doi.org/10.17605/OSF.IO/KWMA5 . Zenodo publicado y conectado a la release GitHub: https://doi.org/10.5281/zenodo.23829470 . El despliegue utiliza permisos de lectura del repositorio y no genera commits automáticos. El manuscrito final incorpora las referencias a estas plataformas, sin depositarse aquí como preprint.
