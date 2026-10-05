# Edificio HC2, Ampliación Clínica U Andes · Informes ejecutivos ITO

Informe ejecutivo mensual de inspección técnica de obra de la Ampliación Clínica U Andes, Edificio HC2 (código GIP_267), cliente Universidad de los Andes, constructora CYPCO. Publicado por GIP Inspección Técnica de Obras.

Publicado en https://informes.gip.cl/Clinica-UAndes/ (portada de todas las obras: https://informes.gip.cl).

La página `index.html` muestra cada informe en una pestaña, con el más reciente marcado como vigente. Cada informe se puede abrir directo con `#n` y su número, por ejemplo `index.html#n10`.

## Informes cargados

| N° | Período | Cierre | PDF |
|----|---------|--------|-----|
| 10 | Septiembre 2026 | 30-09-2026 | `pdf/GIP_267_Informe_N10_2026-09.pdf` |

Los informes N° 1 a 9 no se publicaron en este sitio; la serie publicada parte en el N° 10.

## Estructura

- `index.html`: la aplicación completa. Los datos de cada informe están en el arreglo `INFORMES`, al comienzo del script.
- `media/AAAA-MM/`: fotos del período (`foto-NN.jpg` y su miniatura `foto-NN-mini.jpg`, numeradas como en el informe), curva S (`curvaS.png`) y foto de portada (`hero.jpg`).
- `media/marca/`: logos de GIP.
- `pdf/`: informe del período en PDF A4, impreso desde la misma página con pie de página numerado (mismo formato que Carrera y Torre 1).

## Agregar un mes nuevo

1. Copiar las fotos, la curva S y la portada en `media/AAAA-MM/`.
2. Copiar el PDF en `pdf/`.
3. Agregar un objeto nuevo al comienzo de `INFORMES` en `index.html`, junto con su constante `MEDIA_AAAA_MM`.

## Particularidades de esta obra

- Dos anticipos (10% y 5%) garantizados con 37 boletas en Banco Consorcio y BancoEstado; el estado de cada boleta sale del anexo A.2.
- Las obras adicionales son notas de cambio (anexo A.4.1, montos con IVA) y se pagan en estados de pago propios (anexo A.4). Los valores proforma salen del anexo A.4 (RVP).
- Las RDI pendientes salen de la hoja de estatus de RFI; los días en consulta se cuentan al cierre del período.
