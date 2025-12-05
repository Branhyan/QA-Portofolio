# 🧪 Proyecto QA Testing - Sistema Veterinaria Guau Guau
![Status](https://img.shields.io/badge/Status-Completed-success)
![Test Cases](https://img.shields.io/badge/Test%20Cases-100+-blue)
![Coverage](https://img.shields.io/badge/Coverage-85.7%25-green)
![Team](https://img.shields.io/badge/Team-6%20people-orange)
![Duration](https://img.shields.io/badge/Duration-8%20weeks-purple)

Proyecto de testing exhaustivo de un sistema de gestión veterinaria desarrollado como trabajo final en JAP 2025. Este repositorio contiene la documentación completa del proceso de QA, desde planificación hasta evaluación de resultados.

---

## 📊 Resultados Clave

- **100+ casos de prueba** diseñados con metodología formal
- **27 defectos** identificados y documentados
- **47 ideas de mejora** propuestas al equipo de desarrollo
- **+31 puntos** de mejora en calidad medida (43% → 74%)
- **0 retrasos** en entregas durante 4 semanas

---

## 🎯 Mi Rol: Team Manager & QA Tester

**Liderazgo Técnico**
* Diseñé la arquitectura completa del proyecto de testing (4 fases, 8 semanas)
* Configuré Jira desde cero con workflows personalizados y sistema de trazabilidad
* Coordiné equipo de 6 testers con horarios diversos, logrando 0 retrasos

**Expertise Técnica Aplicada**
* Diseñé y ejecuté 13 casos de pruebas no funcionales (rendimiento, accesibilidad WCAG 2.1, compatibilidad)
* Implementé partición de equivalencias y análisis de valores límite en 50+ casos
* Lideré el diseño de pruebas basadas en casos de uso y requerimientos

**Gestión de Calidad**
* Establecí criterios de severidad para clasificación de defectos (Alta/Media/Baja)
* Conduje hackathon de mejoras que generó 33 ideas priorizadas
* Documenté changelog completo entre versiones con impacto medible

---

## 🔬 Highlights Técnicos

### Testing No Funcional (Primera Experiencia Práctica)

**Performance Analysis**
* Medí tiempos de carga usando Chrome DevTools
* Métrica: Largest Contentful Paint (LCP) - 0.065s promedio
* Simulé condiciones de red (3G, 4G lento, 4G rápido) para validar rendimiento
* Límite establecido: 2s

**Accesibilidad Web (WCAG 2.1 Level AA)**
* Validé contraste de colores con WebAIM Contrast Checker
  - Texto normal: 7.45:1 (supera mínimo de 4.5:1)
  - Títulos: 12.63:1 (supera mínimo de 3:1)
* Verifiqué navegación completa por teclado
* Usé Accessibility Insights for Web para validar orden de tabulación

**Compatibilidad Cross-Browser**
* Ejecuté pruebas en Chrome, Edge y Opera GX
* Validé que no hubiera errores en JavaScript console
* Verifiqué consistencia visual entre navegadores

### Gestión de Proyecto

**Jira desde Cero**
* Configuración completa de workflow personalizado
* Estados definidos para casos (Exitoso/Fallido/Bloqueado)
* Sistema de etiquetas por módulo y técnica de diseño
* Trazabilidad completa: Requerimiento → Caso → Incidencia → Corrección

**Coordinación de Equipo Distribuido**
* 6 personas con horarios diversos durante 8 semanas
* Trabajo asíncrono con responsabilidades individuales
* 2 reuniones semanales de sincronización
* 0 retrasos en entregas (4 fases completadas a tiempo)

## 📁 Documentación Disponible

| Documento | Descripción | Páginas | Link |
|-----------|-------------|---------|------|
| **Resumen Ejecutivo** | Resumen profesional del proyecto | 10 | [Ver PDF](docs/Resumen_Ejecutivo.pdf) |
| **Casos de Prueba** | Ejemplos de test cases diseñados | - | [Ver PDF](docs/Casos_de_Muestra.pdf) |
| **Muestra uso de JIRA** | Capturas de implementación de JIRA en el proyecto | - | (En preparación) |
| **Estadísticas Visuales** | Métricas clave y gráficas del proyecto | 4 | (En preparación) |
| **Informe Técnico Completo** | Documentación exhaustiva del proyecto | 312 | [Ver PDF](docs/Informe_Completo.pdf) |


---

## 🔍 Metodología

### Diseño de Casos de Prueba

- **50%** Partición de Equivalencias
- **18.2%** Casos de Uso  
- **14.8%** Requerimientos No Funcionales
- **14.8%** Requerimientos Funcionales
- **2.3%** Dashboard (testing de nuevo módulo)

### Fases del Proyecto

1. **Planificación** - Definición de roles, configuración de herramientas, diseño de casos
2. **Testing** - Ejecución de 100+ casos, documentación de hallazgos
3. **Retesting** - Verificación de correcciones, pruebas de regresión
4. **Evaluación** - Análisis de métricas, retrospectiva, documentación final

---

## 🛠️ Stack Técnico

**Gestión de Testing**
* Jira (configuración personalizada, workflows, etiquetas)
* Trello + Planyway (planificación con Gantt)
* SQL (validación de límites de campos)

**Testing Tools**
* Chrome DevTools (Performance, Network throttling, Console)
* WebAIM Contrast Checker (ratios WCAG)
* Accessibility Insights for Web (navegación por teclado)

**Ambiente de Pruebas**
* Navegadores: Chrome, Edge, Opera GX
* Condiciones de red simuladas: 3G, 4G lento, 4G rápido
* Local environment (validación pre-despliegue)

**Documentación**
* Canva (diseño visual de informes)
* Microsoft Office (documentación técnica)
* XMind (mapas mentales para estructuración)

---

## 📈 Métricas del Proyecto

### Casos de Prueba
- **Total ejecutados:** 100+
- **Pruebas de regresión:** 42
- **Pruebas de confirmación:** 58

### Defectos Encontrados
- **Total:** 27 incidencias
- **Severidad Alta:** 46.2%
- **Severidad Media:** 23.1%
- **Severidad Baja:** 30.8%
- **Solucionados en V1.0:** 10

### Ideas de Mejora
- **Total propuestas:** 47
- **Prioridad Alta:** 27.5%
- **Prioridad Media:** 47.5%
- **Implementadas:** 3
- **Parcialmente implementadas:** 2

---

## 🎓 Aprendizajes Clave

1. **Liderazgo técnico:** Coordinación de equipos con diferentes horarios y niveles de experiencia
2. **Metodología formal:** Aplicación de técnicas de diseño de casos (particiones, valores límite)
3. **Herramientas profesionales:** Configuración de Jira para proyectos de testing
4. **Testing no funcional:** Performance, accesibilidad WCAG 2.1, compatibilidad
5. **Transferencia de conocimiento:** De centralización táctica a distribución del equipo

---

## 👥 Equipo

**Team Manager:** Branhyan Bernaschina  
**Documentation Lead:** Natasha  
**Technical Advisor:** Matias  
**Communication Coordinator:** Gwyneth  
**Language Specialist:** Carolina  
**Feedback Coordinator:** Kevin

---

## 🔗 Links Relacionados

- **LinkedIn:** [Mi perfil](www.linkedin.com/in/branhyan-bernas)
- **Video del Proyecto:** [Video en Youtube](https://youtu.be/3O-5FduUvjM)

---

## 📫 Contacto

**Branhyan Bernaschina**  
QA Tester | Coordinador de Equipos de Testing

- 📧 Email: branhyan.bernaschina@outlook.com
- 💼 LinkedIn: www.linkedin.com/in/branhyan-bernas
- 📍 Canelones, Uruguay

---
