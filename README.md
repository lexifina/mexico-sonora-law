# Sonora: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Sonora, Mexico, which global-law reads at `mexico/sonora/acts/`.

The law of the State of Sonora (Estado Libre y Soberano de Sonora, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-son/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

141 ordenamientos with 1066 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO DE SONORA | 135 | as first published, then each reform: 18 September 1917 to 29 May 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE SONORA | 35 | as first published, then each reform: 23 September 1949 to 15 May 2021 |
| `codigo-de-disciplina-del-cuerpo-de-bomberos-del-municipio-de/` | CODIGO DE DISCIPLINA DEL CUERPO DE BOMBEROS DEL MUNICIPIO DE HUATABAMPO, SONORA | 1 | as first published: 23 March 2011 |
| `codigo-de-familia/` | CODIGO DE FAMILIA PARA EL ESTADO DE SONORA | 18 | as first published, then each reform: 1 March 2011 to 17 January 2023 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO DE SONORA | 30 | as first published, then each reform: 23 September 1949 to 2 October 2018 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE SONORA | 29 | as first published, then each reform: 27 June 2000 to 1 January 2026 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE SONORA | 100 | as first published, then each reform: 1 May 1994 to 14 June 2026 |
| `ley-de-acceso-a-la-informacion-publica-y-de-proteccion-de-da/` | LEY DE ACCESO A LA INFORMACION PUBLICA Y DE PROTECCION DE DATOS PERSONALES DEL ESTADO DE SONORA -ANTES LEY DE ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE SONORA- | 7 | as first published, then each reform: 26 February 2005 to 4 August 2017 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA PARA EL ESTADO DE SONORA | 15 | as first published, then each reform: 30 October 2007 to 12 June 2026 |
| `ley-de-agua/` | LEY DE AGUA DEL ESTADO DE SONORA | 8 | as first published, then each reform: 11 July 2006 to 1 July 2026 |
| `ley-de-alianzas-publico-privadas-de-servicios/` | LEY DE ALIANZAS PUBLICO PRIVADAS DE SERVICIOS DEL ESTADO DE SONORA | 7 | as first published, then each reform: 15 July 2008 to 4 August 2017 |
| `ley-de-amnistia/` | LEY DE AMNISTIA PARA EL ESTADO DE SONORA | 1 | as first published: 20 January 1979 |
| `ley-de-aparceria/` | LEY DE APARCERIA DEL ESTADO DE SONORA | 3 | as first published, then each reform: 24 October 1931 to 2 May 1934 |
| `ley-de-asistencia-social/` | LEY DE ASISTENCIA SOCIAL | 7 | as first published, then each reform: 17 June 1986 to 28 September 2018 |
| `ley-de-atencion-a-victimas/` | LEY DE ATENCION A VICTIMAS PARA EL ESTADO DE SONORA | 5 | as first published, then each reform: 29 November 2015 to 2 March 2021 |
| `ley-de-atencion-y-gestion-ciudadana-en-la-administracion-pub/` | LEY DE ATENCION Y GESTION CIUDADANA EN LA ADMINISTRACION PUBLICA ESTATAL Y MUNICIPAL DEL ESTADO DE SONORA | 1 | as first published: 8 July 2023 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO DEL ESTADO DE SONORA | 1 | as first published: 28 November 2017 |
| `ley-de-cardioproteccion/` | LEY DE CARDIOPROTECCION PARA EL ESTADO DE SONORA | 1 | as first published: 5 May 2017 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE DEL ESTADO DE SONORA | 10 | as first published, then each reform: 17 February 2009 to 16 December 2025 |
| `ley-de-defraudacion-impositiva/` | LEY DE DEFRAUDACION IMPOSITIVA PARA EL ESTADO DE SONORA | 1 | as first published: 14 January 1950 |
| `ley-de-derechos-de-los-pueblos-y-comunidades-indigenas-de-so/` | LEY DE DERECHOS DE LOS PUEBLOS Y COMUNIDADES INDIGENAS DE SONORA | 4 | as first published, then each reform: 19 December 2010 to 3 October 2023 |
| `ley-de-desarrollo-rural-sustentable/` | LEY DE DESARROLLO RURAL SUSTENTABLE DEL ESTADO DE SONORA | 3 | as first published, then each reform: 18 September 2009 to 2 December 2025 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL DEL ESTADO DE SONORA | 6 | as first published, then each reform: 31 March 2006 to 19 November 2021 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA DEL ESTADO DE SONORA | 9 | as first published, then each reform: 7 July 1995 to 22 October 2016 |
| `ley-de-donacion-y-trasplantes-para-organismos-humanos-sonora/` | LEY DE DONACION Y TRASPLANTES PARA ORGANISMOS HUMANOS, SONORA | 7 | as first published, then each reform: 21 June 2005 to 24 July 2020 |
| `ley-de-ejecucion-de-sanciones-penales-y-medidas-de-seguridad/` | LEY DE EJECUCION DE SANCIONES PENALES Y MEDIDAS DE SEGURIDAD DEL ESTADO DE SONORA | 3 | as first published, then each reform: 18 June 2014 to 4 August 2017 |
| `ley-de-escalafon-del-magisterio/` | LEY DE ESCALAFON DEL MAGISTERIO DEL ESTADO DE SONORA | 1 | as first published: 1 January 1943 |
| `ley-de-expropiacion/` | LEY DE EXPROPIACION PARA EL ESTADO DE SONORA | 1 | as first published: 18 September 2009 |
| `ley-de-fiscalizacion-superior/` | LEY DE FISCALIZACION SUPERIOR PARA EL ESTADO DE SONORA | 11 | as first published, then each reform: 15 July 2008 to 30 January 2020 |
| `ley-de-fomento-a-la-cultura-de-la-legalidad-civilidad-y-valo/` | LEY DE FOMENTO A LA CULTURA DE LA LEGALIDAD, CIVILIDAD Y VALORES DEL ESTADO DE SONORA | 1 | as first published: 14 June 2013 |
| `ley-de-fomento-al-empleo/` | LEY DE FOMENTO AL EMPLEO PARA EL ESTADO DE SONORA | 2 | as first published, then each reform: 3 June 2014 to 4 August 2017 |
| `ley-de-fomento-de-energias-renovables-y-eficiencia-energetic/` | LEY DE FOMENTO DE ENERGIAS RENOVABLES Y EFICIENCIA ENERGETICA DEL ESTADO DE SONORA | 2 | as first published, then each reform: 28 August 2009 to 26 January 2018 |
| `ley-de-fomento-de-la-cultura-del-cuidado-del-agua/` | LEY DE FOMENTO DE LA CULTURA DEL CUIDADO DEL AGUA PARA EL ESTADO DE SONORA | 1 | as first published: 13 April 2010 |
| `ley-de-fomento-de-la-cultura-y-proteccion-del-patrimonio-cul/` | LEY DE FOMENTO DE LA CULTURA Y PROTECCION DEL PATRIMONIO CULTURAL DEL ESTADO DE SONORA | 6 | as first published, then each reform: 2 December 2011 to 5 May 2021 |
| `ley-de-fomento-para-el-desarrollo-forestal-sustentable/` | LEY DE FOMENTO PARA EL DESARROLLO FORESTAL SUSTENTABLE DEL ESTADO DE SONORA | 2 | as first published, then each reform: 16 December 2005 to 4 August 2017 |
| `ley-de-fomento-para-la-produccion-industrializacion-y-comerc/` | LEY DE FOMENTO PARA LA PRODUCCION, INDUSTRIALIZACION Y COMERCIALIZACION DEL BACANORA DEL ESTADO DE SONORA | 2 | as first published, then each reform: 9 December 2008 to 19 October 2012 |
| `ley-de-ganaderia/` | LEY DE GANADERIA PARA EL ESTADO DE SONORA | 5 | as first published, then each reform: 8 November 2005 to 16 October 2024 |
| `ley-de-gobierno-digital/` | LEY DE GOBIERNO DIGITAL PARA EL ESTADO DE SONORA | 1 | as first published: 14 June 2023 |
| `ley-de-gobierno-y-administracion-municipal/` | LEY DE GOBIERNO Y ADMINISTRACION MUNICIPAL DEL ESTADO DE SONORA | 42 | as first published, then each reform: 14 November 2001 to 13 October 2026 |
| `ley-de-hacienda/` | LEY DE HACIENDA DEL ESTADO DE SONORA | 105 | as first published, then each reform: 1 January 1977 to 1 January 2026 |
| `ley-de-hacienda-municipal/` | LEY DE HACIENDA MUNICIPAL | 39 | as first published, then each reform: 1 January 1984 to 2 July 2024 |
| `ley-de-ingresos-y-presupuesto-de-ingresos-del-ayuntamiento-d/` | LEY DE INGRESOS Y PRESUPUESTO DE INGRESOS DEL AYUNTAMIENTO DEL MUNICIPIO DE CAJEME, SONORA, PARA EL EJERCICIO FISCAL DE 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-y-presupuesto-de-ingresos-del-ayuntamiento-d-2/` | LEY DE INGRESOS Y PRESUPUESTO DE INGRESOS DEL AYUNTAMIENTO DEL MUNICIPIO DE CUCURPE, SONORA, PARA EL EJERCICIO FISCAL DE 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-y-presupuesto-de-ingresos-del-ayuntamiento-d-3/` | LEY DE INGRESOS Y PRESUPUESTO DE INGRESOS DEL AYUNTAMIENTO DEL MUNICIPIO DE ETCHOJOA, SONORA, PARA EL EJERCICIO FISCAL DE 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-y-presupuesto-de-ingresos-del-ayuntamiento-d-4/` | LEY DE INGRESOS Y PRESUPUESTO DE INGRESOS DEL AYUNTAMIENTO DEL MUNICIPIO DE GUAYMAS DE ZARAGOZA, SONORA, PARA EL EJERCICIO FISCAL DE 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-y-presupuesto-de-ingresos-del-ayuntamiento-d-5/` | LEY DE INGRESOS Y PRESUPUESTO DE INGRESOS DEL AYUNTAMIENTO DEL MUNICIPIO DE OPODEPE, SONORA, PARA EL EJERCICIO FISCAL DE 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-y-presupuesto-de-ingresos/` | LEY DE INGRESOS Y PRESUPUESTO DE INGRESOS DEL ESTADO DE SONORA PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 1 | as first published: 15 December 2025 |
| `ley-de-ingresos-y-presupuesto-de-ingresos-del-h-ayuntamiento/` | LEY DE INGRESOS Y PRESUPUESTO DE INGRESOS DEL H. AYUNTAMIENTO DEL MUNICIPIO DE HUATABAMPO, SONORA, PARA EL EJERCICIO FISCAL DE 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-y-presupuesto-de-ingresos-del-h-ayuntamiento-2/` | LEY DE INGRESOS Y PRESUPUESTO DE INGRESOS DEL H. AYUNTAMIENTO DEL MUNICIPIO DE SANTA ANA, SONORA, PARA EL EJERCICIO FISCAL DE 2026 | 2 | as first published, then each reform: 1 January 2026 to 9 March 2026 |
| `ley-de-inquilinato/` | LEY DE INQUILINATO DEL ESTADO DE SONORA | 1 | as first published: 16 September 1959 |
| `ley-de-la-defensoria-publica/` | LEY DE LA DEFENSORIA PUBLICA DEL ESTADO DE SONORA | 3 | as first published, then each reform: 29 November 2015 to 1 February 2024 |
| `ley-de-los-derechos-de-las-personas-adultas-mayores/` | LEY DE LOS DERECHOS DE LAS PERSONAS ADULTAS MAYORES DEL ESTADO DE SONORA ANTES - LEY DE LOS ADULTOS MAYORES DEL ESTADO DE SONORA | 11 | as first published, then each reform: 8 September 2007 to 12 May 2026 |
| `ley-de-los-derechos-del-contribuyente/` | LEY DE LOS DERECHOS DEL CONTRIBUYENTE DEL ESTADO DE SONORA | 2 | as first published, then each reform: 12 June 2014 to 4 August 2017 |
| `ley-de-mecanismos-alternativos-de-solucion-de-controversias/` | LEY DE MECANISMOS ALTERNATIVOS DE SOLUCION DE CONTROVERSIAS PARA EL ESTADO DE SONORA | 3 | as first published, then each reform: 8 April 2008 to 12 June 2026 |
| `ley-de-movilidad/` | LEY DE MOVILIDAD DEL ESTADO DE SONORA Y SUS MUNICIPIOS | 1 | as first published: 25 September 2018 |
| `ley-de-movilidad-y-seguridad-vial/` | LEY DE MOVILIDAD Y SEGURIDAD VIAL PARA EL ESTADO DE SONORA | 1 | as first published: 6 January 2024 |
| `ley-de-obras-publicas-y-servicios-relacionados-con-las-misma/` | LEY DE OBRAS PUBLICAS Y SERVICIOS RELACIONADOS CON LAS MISMAS PARA EL ESTADO DE SONORA | 9 | as first published, then each reform: 30 April 2007 to 1 February 2024 |
| `ley-de-ordenamiento-territorial-y-desarrollo-urbano/` | LEY DE ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO DEL ESTADO DE SONORA | 6 | as first published, then each reform: 12 June 2018 to 15 May 2021 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA DEL ESTADO DE SONORA | 4 | as first published, then each reform: 2 July 2011 to 13 July 2018 |
| `ley-de-pesca-y-acuicultura/` | LEY DE PESCA Y ACUICULTURA PARA EL ESTADO DE SONORA | 2 | as first published, then each reform: 29 August 2008 to 4 August 2017 |
| `ley-de-prevencion-del-suicidio/` | LEY DE PREVENCION DEL SUICIDIO PARA EL ESTADO DE SONORA | 1 | as first published: 28 September 2018 |
| `ley-de-prevencion-y-atencion-de-la-violencia-familiar-antes/` | LEY DE PREVENCION Y ATENCION DE LA VIOLENCIA FAMILIAR -ANTES LEY DE PREVENCION Y ATENCION DE LA VIOLENCIA INTRAFAMILIAR PARA EL ESTADO DE SONORA- | 9 | as first published, then each reform: 30 January 2000 to 15 May 2021 |
| `ley-de-prevencion-y-combate-de-la-trata-de-personas/` | LEY DE PREVENCION Y COMBATE DE LA TRATA DE PERSONAS PARA EL ESTADO DE SONORA | 1 | as first published: 11 March 2011 |
| `ley-de-prevencion-atencion-y-combate-a-los-problemas-de-obes/` | LEY DE PREVENCION, ATENCION Y COMBATE A LOS PROBLEMAS DE OBESIDAD PARA EL ESTADO DE SONORA | 2 | as first published, then each reform: 30 June 2013 to 23 December 2016 |
| `ley-de-prevencion-tratamiento-rehabilitacion-y-control-de-ad/` | LEY DE PREVENCION, TRATAMIENTO, REHABILITACION Y CONTROL DE ADICCIONES DEL ESTADO DE SONORA | 4 | as first published, then each reform: 6 March 2009 to 1 January 2020 |
| `ley-de-procedimiento-administrativo/` | LEY DE PROCEDIMIENTO ADMINISTRATIVO DEL ESTADO DE SONORA | 1 | oldest version available: 19 February 2008 |
| `ley-de-profesiones/` | LEY DE PROFESIONES DEL ESTADO DE SONORA | 7 | as first published, then each reform: 21 March 2008 to 11 April 2025 |
| `ley-de-promocion-y-fomento-minero/` | LEY DE PROMOCION Y FOMENTO MINERO PARA EL ESTADO DE SONORA | 2 | as first published, then each reform: 23 November 2007 to 9 October 2020 |
| `ley-de-propiedad-en-condominio-de-inmuebles/` | LEY DE PROPIEDAD EN CONDOMINIO DE INMUEBLES PARA EL ESTADO DE SONORA | 2 | as first published, then each reform: 20 December 2016 to 22 June 2018 |
| `ley-de-proteccion-a-las-industrias-de-transformacion-nuevas/` | LEY DE PROTECCION A LAS INDUSTRIAS DE TRANSFORMACION NUEVAS O UTILES O NECESARIAS EN EL ESTADO DE SONORA | 1 | as first published: 17 November 1943 |
| `ley-de-proteccion-a-madres-jefas-de-familia/` | LEY DE PROTECCION A MADRES JEFAS DE FAMILIA | 1 | as first published: 9 December 2008 |
| `ley-de-proteccion-ciudadana-contra-los-efectos-nocivos-del-t/` | LEY DE PROTECCION CIUDADANA CONTRA LOS EFECTOS NOCIVOS DEL TABACO | 5 | as first published, then each reform: 7 March 2006 to 7 June 2022 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL PARA EL ESTADO DE SONORA | 3 | as first published, then each reform: 12 June 2018 to 1 January 2021 |
| `ley-de-proteccion-y-apoyo-a-migrantes/` | LEY DE PROTECCION Y APOYO A MIGRANTES | 2 | as first published, then each reform: 7 December 2007 to 29 May 2026 |
| `ley-de-proteccion-y-bienestar-animal/` | LEY DE PROTECCION Y BIENESTAR ANIMAL PARA EL ESTADO DE SONORA | 2 | as first published, then each reform: 13 September 2024 to 6 November 2024 |
| `ley-de-reconocimientos-al-merito-civico/` | LEY DE RECONOCIMIENTOS AL MERITO CIVICO DEL ESTADO DE SONORA | 3 | as first published, then each reform: 21 May 2004 to 4 August 2017 |
| `ley-de-regulacion-y-fomento-de-tiempo-compartido/` | LEY DE REGULACION Y FOMENTO DE TIEMPO COMPARTIDO PARA EL ESTADO DE SONORA | 2 | as first published, then each reform: 9 July 1991 to 4 August 2017 |
| `ley-de-salud-mental/` | LEY DE SALUD MENTAL DEL ESTADO DE SONORA | 6 | as first published, then each reform: 17 December 2013 to 17 June 2025 |
| `ley-de-salud/` | LEY DE SALUD PARA EL ESTADO DE SONORA | 43 | as first published, then each reform: 25 June 1992 to 25 April 2026 |
| `ley-de-seguridad-escolar/` | LEY DE SEGURIDAD ESCOLAR PARA EL ESTADO DE SONORA | 4 | as first published, then each reform: 18 January 2009 to 22 February 2024 |
| `ley-de-seguridad-privada/` | LEY DE SEGURIDAD PRIVADA PARA EL ESTADO DE SONORA | 1 | as first published: 28 November 2017 |
| `ley-de-sociedades-mutualistas/` | LEY DE SOCIEDADES MUTUALISTAS PARA EL ESTADO DE SONORA | 1 | as first published: 7 March 2006 |
| `ley-de-transito/` | LEY DE TRANSITO DEL ESTADO DE SONORA | 23 | as first published, then each reform: 28 February 1984 to 1 January 2026 |
| `ley-de-transporte/` | LEY DE TRANSPORTE DEL ESTADO DE SONORA | 2 | as first published, then each reform: 6 January 2024 to 27 December 2025 |
| `ley-de-vias-de-comunicacion-en-el-estado-de-sonora/` | LEY DE VIAS DE COMUNICACION EN EL ESTADO DE SONORA | 1 | as first published: 31 December 1930 |
| `ley-de-vivienda/` | LEY DE VIVIENDA PARA EL ESTADO DE SONORA | 6 | as first published, then each reform: 6 January 2012 to 27 April 2018 |
| `ley-del-ahorro-escolar-en-el-estado-de-sonora/` | LEY DEL AHORRO ESCOLAR EN EL ESTADO DE SONORA | 1 | as first published: 9 February 1952 |
| `ley-del-boletin-oficial/` | LEY DEL BOLETIN OFICIAL | 3 | as first published, then each reform: 28 July 1993 to 10 January 2014 |
| `ley-del-equilibrio-ecologico-y-proteccion-al-ambiente/` | LEY DEL EQUILIBRIO ECOLOGICO Y PROTECCION AL AMBIENTE DEL ESTADO DE SONORA | 16 | as first published, then each reform: 24 November 2008 to 2 July 2024 |
| `ley-del-instituto-de-becas-y-credito-educativo/` | LEY DEL INSTITUTO DE BECAS Y CREDITO EDUCATIVO DEL ESTADO DE SONORA | 5 | as first published, then each reform: 30 January 2018 to 23 October 2023 |
| `ley-del-instituto-de-seguridad-y-servicios-sociales-de-los-t/` | LEY DEL INSTITUTO DE SEGURIDAD Y SERVICIOS SOCIALES DE LOS TRABAJADORES DEL ESTADO DE SONORA | 25 | as first published, then each reform: 1 January 1963 to 1 January 2026 |
| `ley-del-notariado/` | LEY DEL NOTARIADO PARA EL ESTADO DE SONORA | 1 | as first published: 6 April 2024 |
| `ley-del-presupuesto-de-egresos-y-gasto-publico-estatal/` | LEY DEL PRESUPUESTO DE EGRESOS Y GASTO PUBLICO ESTATAL DEL ESTADO DE SONORA - ANTES LEY DEL PRESUPUESTO DE EGRESOS, CONTABILIDAD GUBERNAMENTAL Y GASTO PUBLICO ESTATAL - | 12 | as first published, then each reform: 20 November 1987 to 23 May 2025 |
| `ley-del-registro-civil/` | LEY DEL REGISTRO CIVIL PARA EL ESTADO DE SONORA | 12 | as first published, then each reform: 8 February 2014 to 7 June 2022 |
| `ley-del-servicio-civil/` | LEY DEL SERVICIO CIVIL PARA EL ESTADO DE SONORA | 21 | as first published, then each reform: 27 August 1977 to 27 February 2026 |
| `ley-del-servicio-profesional-de-carrera-en-la-administracion/` | LEY DEL SERVICIO PROFESIONAL DE CARRERA EN LA ADMINISTRACION PUBLICA DEL ESTADO DE SONORA | 1 | as first published: 20 February 2024 |
| `ley-del-sistema-integral-para-erradicar-el-ausentismo-y-la-d/` | LEY DEL SISTEMA INTEGRAL PARA ERRADICAR EL AUSENTISMO Y LA DESERCION EN LA EDUCACION BASICA Y MEDIA SUPERIOR PUBLICAS EN EL ESTADO DE SONORA | 1 | as first published: 3 March 2017 |
| `ley-estatal-de-mejora-regulatoria/` | LEY ESTATAL DE MEJORA REGULATORIA DEL ESTADO DE SONORA | 2 | as first published, then each reform: 4 October 2019 to 2 March 2021 |
| `ley-no-251-de-las-juventudes/` | LEY NO. 251 DE LAS JUVENTUDES DEL ESTADO DE SONORA | 1 | as first published: 30 September 2025 |
| `ley-no-80-organica-del-poder-judicial/` | LEY NO. 80 ORGANICA DEL PODER JUDICIAL DEL ESTADO DE SONORA | 2 | as first published, then each reform: 30 August 2025 to 12 May 2026 |
| `ley-no-81-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY NO. 81 DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE SONORA | 1 | as first published: 30 August 2025 |
| `ley-no-82-de-proteccion-de-datos-personales-en-posesion-de-s/` | LEY NO. 82 DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE SONORA | 1 | as first published: 30 August 2025 |
| `ley-numero-109-que-establece-el-arancel-para-los-notarios/` | LEY NUMERO 109 QUE ESTABLECE EL ARANCEL PARA LOS NOTARIOS DEL ESTADO DE SONORA | 2 | as first published, then each reform: 30 December 1989 to 4 August 2017 |
| `ley-numero-140-de-bienes-y-concesiones/` | LEY NUMERO 140 DE BIENES Y CONCESIONES DEL ESTADO DE SONORA | 9 | as first published, then each reform: 1 January 1993 to 27 April 2024 |
| `ley-numero-158-que-establece-el-secreto-profesional-periodis/` | LEY NUMERO 158 QUE ESTABLECE EL SECRETO PROFESIONAL PERIODISTICO EN EL ESTADO DE SONORA | 1 | as first published: 29 April 2011 |
| `ley-numero-160-de-austeridad-y-ahorro/` | LEY NUMERO 160 DE AUSTERIDAD Y AHORRO DEL ESTADO DE SONORA Y SUS MUNICIPIOS | 1 | as first published: 1 January 2020 |
| `ley-numero-161-de-fomento-al-emprendimiento-juvenil/` | LEY NUMERO 161, DE FOMENTO AL EMPRENDIMIENTO JUVENIL DEL ESTADO DE SONORA | 1 | as first published: 6 March 2020 |
| `ley-numero-162-de-fomento-y-apoyo-a-la-proveeduria/` | LEY NUMERO 162, DE FOMENTO Y APOYO A LA PROVEEDURIA DEL ESTADO DE SONORA | 1 | as first published: 17 April 2020 |
| `ley-numero-163-de-educacion/` | LEY NUMERO 163, DE EDUCACION DEL ESTADO DE SONORA | 16 | as first published, then each reform: 16 May 2020 to 19 May 2026 |
| `ley-numero-165-que-declara-las-fechas-civicas/` | LEY NUMERO 165 QUE DECLARA LAS FECHAS CIVICAS DEL ESTADO DE SONORA | 1 | as first published: 24 July 2020 |
| `ley-numero-166-de-archivos/` | LEY NUMERO 166 DE ARCHIVOS PARA EL ESTADO DE SONORA | 2 | as first published, then each reform: 18 September 2020 to 28 October 2022 |
| `ley-numero-167-para-la-proteccion-del-personal-sanitario-en/` | LEY NUMERO 167 PARA LA PROTECCION DEL PERSONAL SANITARIO EN EL ESTADO DE SONORA | 1 | as first published: 28 August 2020 |
| `ley-numero-168-de-ciencia-tecnologia-e-innovacion/` | LEY NUMERO 168 DE CIENCIA, TECNOLOGIA E INNOVACION DEL ESTADO DE SONORA | 1 | as first published: 15 September 2020 |
| `ley-numero-170-de-servicios-inmobiliarios/` | LEY NUMERO 170 DE SERVICIOS INMOBILIARIOS PARA EL ESTADO DE SONORA | 2 | as first published, then each reform: 9 October 2020 to 19 May 2026 |
| `ley-numero-172-para-el-desarrollo-y-fomento-de-la-agricultur/` | LEY NUMERO 172 PARA EL DESARROLLO Y FOMENTO DE LA AGRICULTURA ORGANICA PARA EL ESTADO DE SONORA | 1 | as first published: 20 November 2020 |
| `ley-numero-174-que-crea-el-centro-de-valor-agregado/` | LEY NUMERO 174, QUE CREA EL CENTRO DE VALOR AGREGADO DEL ESTADO DE SONORA | 1 | as first published: 1 January 2021 |
| `ley-numero-177-de-instituciones-y-procedimientos-electorales/` | LEY NUMERO 177 DE INSTITUCIONES Y PROCEDIMIENTOS ELECTORALES PARA EL ESTADO DE SONORA | 9 | as first published, then each reform: 1 July 2014 to 5 June 2026 |
| `ley-numero-179-para-prevenir-combatir-y-eliminar-actos-de-di/` | LEY NUMERO 179 PARA PREVENIR, COMBATIR Y ELIMINAR ACTOS DE DISCRIMINACION EN EL ESTADO DE SONORA | 5 | as first published, then each reform: 25 November 2014 to 7 March 2023 |
| `ley-numero-180-para-la-atencion-integral-del-cancer-de-mama/` | LEY NUMERO 180 PARA LA ATENCION INTEGRAL DEL CANCER DE MAMA DEL ESTADO DE SONORA | 2 | as first published, then each reform: 1 January 2015 to 5 September 2025 |
| `ley-numero-182-para-prevenir-sancionar-y-erradicar-la-tortur/` | LEY NUMERO 182 PARA PREVENIR, SANCIONAR Y ERRADICAR LA TORTURA EN EL ESTADO DE SONORA | 2 | as first published, then each reform: 28 November 2014 to 4 August 2017 |
| `ley-numero-183-anticorrupcion-en-cotrataciones-publicas/` | LEY NUMERO 183 ANTICORRUPCION EN COTRATACIONES PUBLICAS PARA EL ESTADO DE SONORA | 2 | as first published, then each reform: 28 November 2014 to 4 August 2017 |
| `ley-numero-185-de-justicia-administrativa/` | LEY NUMERO 185 DE JUSTICIA ADMINISTRATIVA PARA EL ESTADO DE SONORA | 10 | as first published, then each reform: 5 December 2014 to 25 October 2022 |
| `ley-numero-185-del-sistema-estatal-anticorrupcion/` | LEY NUMERO 185 DEL SISTEMA ESTATAL ANTICORRUPCION DEL ESTADO DE SONORA | 4 | as first published, then each reform: 11 May 2017 to 25 October 2022 |
| `ley-numero-187-que-regula-a-la-televisora-de-hermosillo-s-a/` | LEY NUMERO 187 QUE REGULA A LA TELEVISORA DE HERMOSILLO S.A DE C.V., SONORA | 1 | as first published: 23 December 2014 |
| `ley-numero-189-para-la-prevencion-y-atencion-integral-a-pers/` | LEY NUMERO 189 PARA LA PREVENCION Y ATENCION INTEGRAL A PERSONAS CON LUDOPATIA DEL ESTADO DE SONORA | 1 | as first published: 23 June 2017 |
| `ley-numero-194-que-traslada-provisionalmente-la-residencia-d/` | LEY NUMERO 194 QUE TRASLADA PROVISIONALMENTE LA RESIDENCIA DE LOS PODERES DEL ESTADO AL AYUNTAMIENTO DEL MUNICIPIO DE MAGDALENA, SONORA, Y LA DECLARA CAPITAL | 1 | as first published: 15 September 2017 |
| `ley-numero-197-para-la-inclusion-y-desarrollo-de-las-persona/` | LEY NUMERO 197 PARA LA INCLUSION Y DESARROLLO DE LAS PERSONAS CON DISCAPACIDAD O EN SITUACION DE DISCAPACIDAD DEL ESTADO DE SONORA | 7 | as first published, then each reform: 14 April 2019 to 19 April 2024 |
| `ley-numero-2-que-establece-el-dia-02-de-octubre-como-dia-de/` | LEY NUMERO 2 QUE ESTABLECE EL DIA 02 DE OCTUBRE COMO DIA DE LUTO ESTATAL DEL ESTADO DE SONORA | 1 | as first published: 9 November 2018 |
| `ley-numero-200-de-competitividad-y-desarrollo-economico/` | LEY NUMERO 200 DE COMPETITIVIDAD Y DESARROLLO ECONOMICO DEL ESTADO DE SONORA | 3 | as first published, then each reform: 28 November 2017 to 12 March 2021 |
| `ley-numero-246-que-aprueba-el-lema-para-toda-correspondencia/` | LEY NUMERO 246 QUE APRUEBA EL LEMA PARA TODA CORRESPONDENCIA OFICIAL EN EL ESTADO DURANTE EL AÑO 2021 | 1 | as first published: 14 March 2021 |
| `ley-numero-247-de-fomento-cooperativo/` | LEY NUMERO 247, DE FOMENTO COOPERATIVO PARA EL ESTADO DE SONORA | 2 | as first published, then each reform: 2 March 2021 to 16 October 2024 |
| `ley-numero-248-que-instituye-la-presea-del-poderio-de-las-mu/` | LEY NUMERO 248, QUE INSTITUYE LA PRESEA DEL PODERIO DE LAS MUJERES SONORENSES | 1 | as first published: 2 March 2021 |
| `ley-numero-249-que-declara-el-dia-estatal-de-la-lucha-contra/` | LEY NUMERO 249 QUE DECLARA EL "DIA ESTATAL DE LA LUCHA CONTRA LA HOMOFOBIA, LESBOFOBIA, TRANSFOBIA Y BIFOBIA EL 17 DE MAYO" | 1 | as first published: 12 March 2021 |
| `ley-numero-250-de-responsabilidad-ambiental/` | LEY NUMERO 250 DE RESPONSABILIDAD AMBIENTAL DEL ESTADO DE SONORA | 1 | as first published: 29 March 2021 |
| `ley-numero-250-sobre-el-uso-de-firma-electronica-avanzada/` | LEY NUMERO 250 SOBRE EL USO DE FIRMA ELECTRONICA AVANZADA PARA EL ESTADO DE SONORA | 2 | as first published, then each reform: 6 January 2007 to 23 November 2018 |
| `ley-numero-251-estatal-de-turismo-de-sonora/` | LEY NUMERO 251 ESTATAL DE TURISMO DE SONORA | 3 | as first published, then each reform: 30 March 2021 to 19 May 2026 |
| `ley-numero-252-que-regula-la-produccion-manejo-y-disposicion/` | LEY NUMERO 252 QUE REGULA LA PRODUCCION, MANEJO Y DISPOSICION FINAL DE RESIDUOS SOLIDOS URBANOS Y DE MANEJO ESPECIAL Y PRODUCTOS PLASTICOS DE UN SOLO USO EN EL ESTADO DE SONORA | 1 | as first published: 1 January 2022 |
| `ley-numero-253-que-crea-el-centro-de-conciliacion-laboral/` | LEY NUMERO 253 QUE CREA EL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE SONORA | 2 | as first published, then each reform: 5 May 2021 to 9 January 2024 |
| `ley-numero-254-de-voluntad-anticipada/` | LEY NUMERO 254 DE VOLUNTAD ANTICIPADA PARA EL ESTADO DE SONORA | 1 | as first published: 17 May 2021 |
| `ley-numero-256-que-traslada-provisionalmente-la-residencia-d/` | LEY NUMERO 256 QUE TRASLADA PROVISIONALMENTE LA RESIDENCIA DE LOS PODERES DEL ESTADO AL AYUNTAMIENTO DEL MUNICIPIO DE LA HEROICA GUAYMAS, SONORA, Y LA DECLARA CAPITAL | 1 | as first published: 13 July 2009 |
| `ley-numero-276-de-sanidad-vegetal-e-inocuidad-agricola/` | LEY NUMERO 276 DE SANIDAD VEGETAL E INOCUIDAD AGRICOLA DEL ESTADO DE SONORA | 2 | as first published, then each reform: 30 January 2018 to 28 September 2018 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Hermosillo, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
