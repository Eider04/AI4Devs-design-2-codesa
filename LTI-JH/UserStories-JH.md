# 1. Historias de Usuario para LTI

## Historia de Usuario 1: Publicar Ofertas de Trabajo

**Como** reclutador,  
**quiero** publicar ofertas de trabajo de manera automática en múltiples portales y redes sociales,  
**para que** pueda atraer un mayor número de candidatos sin invertir tiempo manualmente.

### Criterios de Aceptación:
- El sistema debe permitir la creación de una oferta de trabajo con detalles como puesto, ubicación, salario y requisitos.
- Una vez creada, la oferta debe publicarse automáticamente en portales de empleo y redes sociales seleccionadas.
- El usuario debe recibir una confirmación de las plataformas donde se publicó la oferta.

### Notas Adicionales:
- Integración con LinkedIn, Indeed y otras plataformas populares.  
- **Historias de Usuario Relacionadas:** Gestión de Candidatos, Colaboración en Equipo.

---

## Historia de Usuario 2: Gestionar Candidatos

**Como** gerente de reclutamiento,  
**quiero** gestionar los perfiles de los candidatos y hacer seguimiento de sus postulaciones,  
**para que** pueda evaluar y seleccionar a los mejores postulantes de manera eficiente.

### Criterios de Aceptación:
- El sistema debe permitir la creación y edición de perfiles de candidatos.
- Debe haber un tablero de seguimiento visual para cada etapa del proceso de selección.
- Notificaciones automáticas para cambios de estado de postulación.

### Notas Adicionales:
- Uso de IA para preselección según criterios definidos.  
- **Historias de Usuario Relacionadas:** Publicación de Ofertas, Entrevistas y Evaluaciones.

---

## Historia de Usuario 3: Programar Entrevistas

**Como** analista de RRHH,  
**quiero** programar entrevistas y grabarlas automáticamente,  
**para que** pueda analizarlas posteriormente usando herramientas de IA.

### Criterios de Aceptación:
- Debe existir un calendario de entrevistas integrado.
- Las entrevistas deben poder grabarse y almacenarse en el sistema.
- La IA debe proporcionar análisis de sentimientos y palabras clave después de cada entrevista.

### Notas Adicionales:
- Integración con Zoom, Google Meet o herramientas similares.  
- **Historias de Usuario Relacionadas:** Gestión de Candidatos, Colaboración en Equipo.

---

## Historia de Usuario 4: Personalizar Flujos de Trabajo

**Como** administrador del sistema,  
**quiero** personalizar los flujos de trabajo de reclutamiento,  
**para que** el proceso se adapte a las necesidades específicas de mi empresa.

### Criterios de Aceptación:
- El sistema debe ofrecer una interfaz para crear y modificar flujos de trabajo.
- Debe permitir la asignación de responsables en cada etapa.
- Soporte para automatizar tareas repetitivas.

### Notas Adicionales:
- Plantillas predefinidas para flujos comunes.  
- **Historias de Usuario Relacionadas:** Gestionar Candidatos, Onboarding Automatizado.

---

## Historia de Usuario 5: Automatizar Onboarding

**Como** coordinador de RRHH,  
**quiero** automatizar el proceso de onboarding,  
**para que** los nuevos empleados se integren rápidamente y sin problemas.

### Criterios de Aceptación:
- Debe existir un checklist automático para el onboarding.
- Integración con sistemas de RRHH existentes para contratos, beneficios, etc.
- Notificaciones automáticas al empleado y al equipo de RRHH sobre el progreso.

### Notas Adicionales:
- Personalización de listas de tareas según el rol del nuevo empleado.  
- **Historias de Usuario Relacionadas:** Personalizar Flujos de Trabajo, Gestionar Candidatos.


---
# 2. Backlog del Producto para LTI

## Descripción del Proyecto
LTI es un innovador sistema de gestión de candidatos (ATS) diseñado para revolucionar los procesos de reclutamiento en empresas de cualquier tamaño. A través de inteligencia artificial, automatización avanzada y una experiencia de usuario optimizada, LTI permite a los equipos de talento encontrar, evaluar y contratar a los mejores candidatos de manera rápida y eficiente.

## Funcionalidades Principales
1. **Publicación de Ofertas** – Difusión automatizada en portales y redes sociales.
2. **Gestión de Candidatos** – Creación de perfiles, seguimiento de postulaciones y gestión del pipeline.
3. **Entrevistas y Evaluaciones** – Programación, grabación y análisis de entrevistas mediante IA.
4. **Flujos de Trabajo Personalizados** – Adaptables a cada empresa y tipo de proceso de selección.
5. **Colaboración en Equipo** – Espacios compartidos para feedback y toma de decisiones conjunta.
6. **Onboarding Automatizado** – Integración con RRHH para agilizar la incorporación de nuevos empleados.

## Backlog Priorizado
| Prioridad | Elemento                                        | Tipo               | Puntuación |
|-----------|--------------------------------------------------|--------------------|------------|
| Alta      | Publicar Ofertas de Trabajo                     | Historia de Usuario| 9          |
| Alta      | Gestionar Candidatos                            | Historia de Usuario| 9          |
| Alta      | Programar Entrevistas                           | Historia de Usuario| 8          |
| Media     | Personalizar Flujos de Trabajo                  | Historia de Usuario| 7          |
| Media     | Automatizar Onboarding                          | Historia de Usuario| 7          |

---


# 3. Tickets Técnicos para Historia de Usuario: Publicar Ofertas de Trabajo

## Ticket 1: Implementar Formulario de Publicación de Ofertas
1. **Título:** Implementar Formulario de Publicación de Ofertas
2. **Descripción:**
   - **Propósito:** Crear un formulario para ingresar detalles de ofertas de trabajo.
   - **Detalles Específicos:** El formulario debe incluir campos para puesto, ubicación, salario, requisitos y descripción, con validación de datos.
3. **Criterios de Aceptación:**
   - El formulario debe validar campos obligatorios.
   - Los datos ingresados deben almacenarse correctamente en la base de datos.
4. **Prioridad:** Alta
5. **Estimación de Esfuerzo:** 8 horas
6. **Asignación:** Equipo Frontend
7. **Etiquetas:** Frontend, UI, Formulario
8. **Comentarios y Notas:** Revisar diseño UI aprobado.
9. **Enlaces:** [Prototipo UI](https://enlace-prototipo)
10. **Historial de Cambios:** N/A

---

## Ticket 2: Desarrollar Integración con APIs de Portales de Empleo
1. **Título:** Integrar API de LinkedIn e Indeed para Publicación Automática
2. **Descripción:**
   - **Propósito:** Implementar integraciones API para publicar ofertas automáticamente.
   - **Detalles Específicos:** Usar las API públicas de LinkedIn e Indeed; incluir autenticación y manejo de errores.
3. **Criterios de Aceptación:**
   - La oferta debe publicarse en las plataformas seleccionadas.
   - Manejo adecuado de errores y mensajes de éxito.
4. **Prioridad:** Muy Alta
5. **Estimación de Esfuerzo:** 16 horas
6. **Asignación:** Equipo Backend
7. **Etiquetas:** Backend, API, Integración
8. **Comentarios y Notas:** Verificar tokens de acceso a las API.
9. **Enlaces:** [Docs API LinkedIn](https://api-linkedin), [Docs API Indeed](https://api-indeed)
10. **Historial de Cambios:** N/A

---

## Ticket 3: Implementar Sistema de Notificaciones para Publicación
1. **Título:** Crear Sistema de Notificaciones para Confirmar Publicación
2. **Descripción:**
   - **Propósito:** Informar al usuario sobre el estado de la publicación.
   - **Detalles Específicos:** Notificación por email y dentro de la aplicación.
3. **Criterios de Aceptación:**
   - El usuario recibe una notificación cuando la publicación es exitosa o falla.
   - El sistema registra el historial de notificaciones.
4. **Prioridad:** Media
5. **Estimación de Esfuerzo:** 6 horas
6. **Asignación:** Equipo Backend
7. **Etiquetas:** Backend, Notificaciones
8. **Comentarios y Notas:** Integrar con el módulo de alertas existente.
9. **Enlaces:** [Módulo Alertas](https://alertas)
10. **Historial de Cambios:** N/A

---

## Ticket 4: Crear Base de Datos para Ofertas de Trabajo
1. **Título:** Diseñar y Crear Base de Datos para Ofertas
2. **Descripción:**
   - **Propósito:** Crear la estructura de base de datos para almacenar las ofertas.
   - **Detalles Específicos:** Crear tablas con campos necesarios, relaciones y constraints.
3. **Criterios de Aceptación:**
   - La base de datos debe almacenar correctamente las ofertas.
   - Debe incluir índices para búsqueda rápida.
4. **Prioridad:** Alta
5. **Estimación de Esfuerzo:** 10 horas
6. **Asignación:** Equipo Backend
7. **Etiquetas:** Backend, Base de Datos
8. **Comentarios y Notas:** Validar con equipo de datos.
9. **Enlaces:** [Esquema DB](https://esquema-db)
10. **Historial de Cambios:** N/A

---

## Ticket 5: Configurar Autenticación para APIs Externas
1. **Título:** Implementar Autenticación para APIs de Publicación
2. **Descripción:**
   - **Propósito:** Asegurar autenticación segura al consumir APIs de portales.
   - **Detalles Específicos:** Usar OAuth 2.0 para LinkedIn e Indeed.
3. **Criterios de Aceptación:**
   - La autenticación debe ser segura y reutilizable.
   - Debe manejarse la renovación de tokens.
4. **Prioridad:** Alta
5. **Estimación de Esfuerzo:** 8 horas
6. **Asignación:** Equipo Backend
7. **Etiquetas:** Backend, Seguridad
8. **Comentarios y Notas:** Revisar permisos de acceso.
9. **Enlaces:** [Docs OAuth](https://oauth-docs)
10. **Historial de Cambios:** N/A



