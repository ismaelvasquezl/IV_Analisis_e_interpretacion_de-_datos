# Agenda de cupos + Programación ProgramAPS — CESFAM Tongoy 2026

Fuentes: Listado de cupos agendados (RAYEN, Consultorio Tongoy, anonimizado, 86.329 filas, año 2026) + ProgramAPS Informe de programación 2026 (escenario Base) + balance oferta/demanda. Datos anonimizados; dashboard HTML único offline entregado.

## Diagnóstico de datos (clave)
- El archivo "anonimizado" TRAÍA PII (Profesional, Paciente, Documento/RUN, Nota, Emisor): se eliminaron antes de analizar. Hoja1 = diccionario IDKEY_P→profesional→Categoría (valida IDKEY_P = profesional).
- IDKEY_U = paciente (8.424 únicos, estable). 113 profesionales. 133 prestaciones.
- Estados: VISITADO 62.182, NO PRESENTADO 11.253, CITADO 8.605 (futuro), EN ESPERA 1.159, NO ATENDIDO 685 (ambiguo), EN CONSULTA 48, sin estado 2.397.
- Ventana con resultado = ENE–OCT 2026 (nov–dic = 96% CITADO futuro). Corte emisión 30-oct-2026.
- "Sector" = sector de inscripción, NO identifica establecimiento (programación declara sector único Tongoy). 66% sin sector útil.

## Indicadores validados (ene–oct 2026)
- **Tasa de inasistencia (NSP) global = 15,3%** (11.229 NSP / 73.313 citas resueltas). Asistencia efectiva 84,7%.
- NSP por estamento: **Nutrición 33,9%**, Técnico Paramédico 33,8%, **Terapia Ocupacional 24,4%**, Podología 21,6%, **Psicología 20,9%**, Fonoaudiología 20,5%, Kinesiología 18,2%, Educadora Párvulos 18,0%, Enfermería 17,5%, Matronería 17,5%, Odontología 15,2%, Asistente Social 15,2%, TENS 10,9%, **Médico 8,0%** (más bajo).
- NSP mensual estable 11,9%–16,9% (sin tendencia). Anticipación: 37,7% mismo día, mediana 2 días.

## Cruce programación × ejecución (hallazgo central)
- **Déficit de horas + NSP alto** (peor): Odontología (util 116%, NSP 15,2%) y Podología (util 158%, NSP 21,6%) — cupos escasos que se pierden.
- **Holgura de horas + NSP alto**: Nutrición (util 32%, NSP 34%), Psicología (37%, 21%), Kinesiología (21%, 18%) — capacidad ociosa + cupos desperdiciados.
- Holguras grandes: TENS +664,9 h/sem, Enfermería +169,1, Kinesiología +151,1, Médico +118,9.
- Infraestructura: Box dental 115% y Sala IRA-ERA 130% saturados; Box matrona 89%, multipropósito 94%.
- Insumos ProgramAPS: población 11.273, dotación 78 personas/3.124 h, 236 prestaciones, 219 días/44 semanas.

## No calculable (declarado)
Ocupación real/vacancia (archivo es de cupos agendados, no oferta total); productividad por hora (sin horas confiables); cobertura poblacional; cumplimiento directo de metas (horas vs cupos); separación Tongoy/Guanaqueros.

## Escenario (ilustrativo, no demostrado)
Bajar NSP 5 pp en estamentos con NSP≥15% recuperaría ~2.000+ cupos atendidos/año; 10 pp casi el doble. Requiere demanda, dotación y box reales.

Fuente programación citable: ProgramAPS https://ismaelvasquezl.github.io/HTA_Matriz_Programacion_Tongoy_2026/
