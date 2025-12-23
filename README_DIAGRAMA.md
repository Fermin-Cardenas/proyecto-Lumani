# Diagrama de Tiempo Estimativo - Sistema de Gestión de Reclutamiento

## 📋 Descripción

Este archivo XML contiene la planeación completa del proyecto usando metodología SCRUM, con un diagrama de Gantt que muestra todas las tareas, dependencias, recursos y tiempos estimados.

## 📅 Información del Proyecto

- **Duración total**: 12 semanas (3 meses)
- **Equipo**: 2 desarrolladores
- **Horas diarias por persona**: 4 horas
- **Total horas disponibles**: 480 horas (240 por persona)

## 🛠️ Cómo usar este archivo

### Opción 1: GanttProject (Recomendado - Gratis y Open Source)

1. Descargar GanttProject desde: https://www.ganttproject.biz/
2. Instalar la aplicación
3. Abrir GanttProject
4. File → Open → Seleccionar `diagrama_tiempo_estimativo.xml`
5. El diagrama se cargará automáticamente con todas las tareas y dependencias

### Opción 2: ProjectLibre (Alternativa Gratuita)

1. Descargar ProjectLibre desde: https://www.projectlibre.com/
2. Instalar la aplicación
3. Abrir ProjectLibre
4. File → Open → Seleccionar `diagrama_tiempo_estimativo.xml`
5. Si no carga directamente, puedes importarlo como XML

### Opción 3: Microsoft Project

1. Abrir Microsoft Project
2. File → Open → Seleccionar `diagrama_tiempo_estimativo.xml`
3. Microsoft Project puede requerir ajustes menores en el formato

### Opción 4: Visualización Online

Si prefieres visualizar online, puedes usar herramientas como:
- **GanttProject Cloud** (si está disponible)
- Convertir el XML a otros formatos usando herramientas de conversión

## 📊 Estructura del Diagrama

### Sprints (6 sprints de 2 semanas cada uno)

1. **Sprint 1**: Fundaciones (Semanas 1-2)
   - Autenticación, Modelos BD, CRUD Vacantes, Postulaciones básicas

2. **Sprint 2**: Visualización y Gestión (Semanas 3-4)
   - Ver postulaciones, CVs, Sistema ATS básico, Búsqueda

3. **Sprint 3**: Mejoras y Extracción (Semanas 5-6)
   - Extracción estructurada de CVs, Historial, Setup OpenRouter

4. **Sprint 4**: IA y Categorización (Semanas 7-8)
   - Asistente IA para vacantes, Sistema Tier List, Categorización

5. **Sprint 5**: Evaluación por Voz (Semanas 9-10)
   - Grabación de voz (máx 5 preguntas), Transcripción, Visualización

6. **Sprint 6**: Reportes y Deployment (Semanas 11-12)
   - Dashboard con gráficas, Responsive design, Deployment producción

### Recursos Asignados

- **Persona 1 - Backend Developer**: Todas las tareas de backend
- **Persona 2 - Frontend Developer**: Todas las tareas de frontend
- **Ambos**: Tareas de integración entre sprints

## 📝 Notas Importantes

### Fechas

Las fechas en el XML están configuradas con una fecha de inicio del **8 de enero de 2024**. 

**Para ajustar las fechas a tu proyecto real:**
1. Abre el archivo XML en GanttProject
2. Selecciona todas las tareas (Ctrl+A)
3. Usa la función "Shift Tasks" para mover todas las tareas a la fecha deseada

### Duración de Tareas

- La duración está en **días laborables** (lunes a viernes)
- Considera que cada persona trabaja **4 horas/día**
- Las estimaciones de horas están documentadas en las notas de cada tarea

### Dependencias

El diagrama incluye todas las dependencias entre tareas:
- Las tareas de backend deben completarse antes de que frontend pueda integrarlas
- Cada sprint tiene tareas de integración al final
- Las tareas de un sprint dependen de la integración del sprint anterior

## 🔄 Actualización del Diagrama

Si necesitas actualizar el diagrama:

1. Realiza cambios en GanttProject o tu herramienta preferida
2. Guarda el archivo como XML
3. Actualiza este README si hay cambios significativos en la estructura

## 📈 Métricas del Proyecto

- **Total de tareas**: 63 tareas principales
- **Total de User Stories**: 43 historias de usuario
- **Horas backend estimadas**: ~240 horas
- **Horas frontend estimadas**: ~240 horas
- **Horas integración**: ~32 horas (compartidas)

## ⚠️ Consideraciones

1. **Fechas de inicio**: Ajusta las fechas según tu fecha de inicio real del proyecto
2. **Buffer**: Las últimas semanas incluyen buffer para imprevistos
3. **Cambios de scope**: Si cambias el alcance, actualiza el diagrama antes de iniciar
4. **Seguimiento**: Usa este diagrama para trackear el progreso real vs. estimado

## 📞 Soporte

Si tienes problemas para abrir o usar el archivo:
- Verifica que estés usando una versión reciente de GanttProject o ProjectLibre
- Asegúrate de que el archivo XML esté completo y no corrupto
- Revisa la documentación de la herramienta que estés usando

---

**Última actualización**: Enero 2024
**Versión del diagrama**: 1.0

