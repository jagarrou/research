# Productos del análisis ENAHO 2025 para AGSCR

**Insumo para el taller de actualización del Programa Educativo · Mayo 2026**

> **Importante.** Todas las cifras de estos productos se reportan en personas expandidas a la población nacional, aplicando el factor de expansión `FACTOR` de la encuesta. Cuando aparece un porcentaje, este se calcula sobre la población expandida correspondiente. Las cifras absolutas se redondean al entero. Los valores muestrales (n no expandido) se documentan únicamente en la sección metodológica del informe técnico.

## Productos principales

### 1. Presentación para el taller
**`Presentacion_Taller_AGSCR_ENAHO2025.pptx`** (18 diapositivas, 16:9)

Lista para proyección. Incluye notas para el facilitador en cada diapositiva. Cada gráfico y KPI muestra la cifra absoluta expandida junto con su porcentaje (ej. "100% (390 mil de 391 mil)").

### 2. Tablero interactivo
**`dashboard_AGSCR_ENAHO2025.html`** (autocontenido)

Para abrir en navegador. Los KPIs muestran cifras absolutas expandidas (ej. "318 472") con la proporción entre paréntesis. Los gráficos exhiben los porcentajes y los datalabels combinan % con cifras expandidas. Los tooltips amplían la información con `personas afectadas / total expandido`. Filtros por dimensión (quintil, región, sexo, zona, migración, pobreza, discapacidad).

### 3. Informe técnico
**`Informe_Tecnico_AGSCR_ENAHO2025.docx`**

Tablas con cuatro columnas tipo: Personas afectadas (expandido), %, IC95% y Total expandido (denominador). Cada porcentaje viene acompañado de la magnitud absoluta de personas que está detrás.

### 4. Banco de gráficos PNG
**`/graficos/g01–g24.png`**

24 visualizaciones individuales con el formato unificado: % + magnitud absoluta en miles ("X% (Y mil personas)").

### 5. Tablas de datos
**`/data/`**

Más de 60 CSV con resultados detallados (proporciones, IC95%, n, n_eff, **pop_pos**, **pop_total**) por objetivo y dimensión. Las columnas `pop_pos` y `pop_total` son las personas expandidas y el total expandido respectivamente.

## Cifras de referencia (para citar)

### Marco poblacional 6-25 años
- **1 428 572** personas (n muestral = 8 118)
- 727 605 hombres · 700 967 mujeres
- 819 591 en Región Central · 991 539 en zona urbana
- 292 275 migrantes (interna o externa)
- 57 033 con discapacidad

### Educación e inclusión digital
- 1 296 000 (90%) usaron internet en los últimos 3 meses
- 564 000 (40%) usan computadora portátil; 217 000 (15%) escritorio
- Asistencia educativa por etapa: 390 mil (6-11), 212 mil (12-14), 217 mil (15-17), 128 mil (18-20), 146 mil (21-25)

### Condiciones de vida
- 318 282 personas en pobreza monetaria (22%)
- 243 207 en pobreza multidimensional (17%)
- 1 305 247 con seguro de salud (91%)

### Subpoblación 15-25 (n = 4 641; expandido = 821 988)
- Tasa de desempleo abierto: 14,5%
- 116 110 personas NINI (14,1%)
- 12 252 personas reportan voluntariado o trabajo comunal (1,5%)

## Aspectos metodológicos clave

- **Fuente:** ENAHO 2025 (INEC), base con variables nuevas elaborada por la AGSCR
- **Población objetivo:** 6 a 25 años residentes en hogares particulares
- **Subpoblación laboral:** 15 a 25 años
- **Ponderación:** factor de expansión `FACTOR` aplicado a todas las estimaciones
- **IC95%:** aproximación de Wilson sobre tamaño efectivo de Kish (`n_eff`). Sin acceso a UPM/estratos del diseño muestral, los IC95% son aproximaciones ligeramente conservadoras
- **Recodificaciones notables:** la variable `ActComVol` fue recodificada de su código original (0/8) a binaria (0/1) para evitar inflar la proporción
- **Validación:** todas las cifras agregadas verificadas contra rangos esperables del INEC

## Énfasis de lectura crítica

Los productos enfatizan cuatro ejes de brecha:

- **Territoriales** — región y zona urbana/rural
- **Socioeconómicas** — quintiles y pobreza monetaria/multidimensional
- **Sexo y curso de vida** — desagregación por los 5 grupos etarios y por sexo
- **Vulnerabilidades específicas** — migración, discapacidad y NINI

## Limitaciones reconocidas

- ENAHO es transversal: las "trayectorias" se infieren por comparación entre cohortes
- Sin acceso a UPM/estratos del diseño muestral, los IC95% son aproximaciones conservadoras
- Definiciones operacionales pueden diferir de informes oficiales (NINI usa definición OIT simplificada)
- Subgrupos pequeños (p. ej., quintil 5 × adolescencia, regiones × discapacidad) tienen IC95% más amplios
- El indicador de voluntariado/comunal capta solo formas estructuradas de servicio en la última semana, lo que probablemente subestima el voluntariado total

---

*Elaboración: Dirección de Programa Educativo, Asociación de Guías y Scouts de Costa Rica · Mayo 2026*
