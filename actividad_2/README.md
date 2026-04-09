# Actividad 2: Estudio de Viabilidad de Proyecto IA en la UE

## Objetivo
Desarrollar un estudio de viabilidad de un sistema de inteligencia artificial para **triaje médico automatizado en urgencias hospitalarias**, analizando su conformidad con la Ley de IA de la Unión Europea y aplicando la metodología CRISP-DM.

## Propuesta del Sistema
Sistema de IA para clasificar y priorizar pacientes en servicios de urgencias utilizando:
- **NLP (BioBERT)**: Para analizar descripciones de síntomas en lenguaje natural
- **Clasificación multiclase**: Para asignar nivel de urgencia (escala Manchester: rojo, naranja, amarillo, verde, azul)
- **Fusión de datos**: Combina texto libre con constantes vitales

## Clasificación Regulatoria
- **Alto Riesgo**: Según el Anexo III, punto 5.d del Reglamento de IA de la UE (sistemas de triaje de pacientes en urgencias)
- **No Riesgo Inaceptable**: No vulnera los criterios del Art. 5 (sin manipulación subliminal, sin discriminación, con supervisión humana activa)

## Metodología CRISP-DM (Fase 1)
### Objetivos del Negocio
- Reducir errores de priorización y tiempos de espera críticos
- Apoyar la decisión del personal sanitario en situaciones de alta demanda

### Criterios de Éxito
- Precisión ≥ 90% (F1-score macro)
- Reducción ≥ 30% de errores vs. triaje manual
- Tiempo ≤ 2 minutos por paciente
- Aceptación ≥ 80% del personal sanitario

### Viabilidad
- **Técnica**: Alta - datos disponibles, dominio bien documentado
- **Legal**: Requiere DPIA y documentación de cumplimiento
- **Económica**: ROI positivo desde el 1er año, break-even ~0.5 años

## Contenido
Ejecutar el notebook para ver:
- Componentes técnicos del sistema
- Análisis comparativo: Alto Riesgo vs. Riesgo Inaceptable
- Criterios de éxito cuantitativos y cualitativos
- Análisis coste-beneficio detallado

## Archivo Principal
`actividad_2_viabilidad_IA_UE.ipynb` - Notebook completo con el estudio de viabilidad