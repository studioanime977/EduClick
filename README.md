# 🎓 EduClick - Plataforma Educativa de Tecnología

![EduClick Logo](img/logo.png)

**EduClick** es una plataforma educativa moderna y profesional diseñada para democratizar el acceso a la educación tecnológica en Latinoamérica. Conectamos estudiantes con expertos en tecnología a través de cursos interactivos, metodología innovadora y un sistema de suscripción justo para todos.

## 🌟 Características Principales

### 🎯 **Para Estudiantes**
- **Cursos Interactivos**: Aprende HTML, CSS, JavaScript, Python, UX/UI, Marketing Digital y más
- **Videos en Alta Calidad**: Contenido 4K con descarga offline disponible
- **Certificaciones Verificadas**: Certificados profesionales reconocidos
- **Proyectos Prácticos**: Aplica lo aprendido en proyectos reales
- **Comunidad Activa**: Networking con otros estudiantes y expertos
- **Acceso Multiplataforma**: Disponible en web y móvil

### 👨‍🏫 **Para Creadores y Profesores**
- **Reparto Justo**: 60% para creadores, 40% para profesores de las utilidades
- **Herramientas de Creación**: Sistema fácil para subir y gestionar contenido
- **Analytics Detallados**: Seguimiento del progreso de estudiantes
- **Soporte Técnico**: Asistencia completa para creadores de contenido

### 💼 **Para Empresas**
- **Planes Corporativos**: Suscripciones grupales con descuentos
- **Capacitación Empresarial**: Cursos especializados para equipos
- **Certificaciones Corporativas**: Validación de habilidades técnicas

## 🚀 Tecnologías Utilizadas

### Frontend
- **HTML5** - Estructura semántica moderna
- **CSS3** - Diseño responsive con gradientes y animaciones
- **JavaScript ES6+** - Interactividad y funcionalidad dinámica
- **Font Awesome** - Iconografía profesional
- **Google Fonts (Inter)** - Tipografía moderna y legible

### Diseño
- **Responsive Design** - Adaptable a todos los dispositivos
- **CSS Grid & Flexbox** - Layouts modernos y flexibles
- **Gradientes Personalizados** - Identidad visual única
- **Animaciones CSS** - Transiciones suaves y profesionales

### Funcionalidades
- **LocalStorage** - Persistencia de sesión de usuario
- **Sistema de Autenticación** - Login/registro simulado
- **Calculadoras Financieras** - Simulación de pagos y ganancias
- **Navegación SPA** - Experiencia de aplicación de una sola página

## 📁 Estructura del Proyecto

```
EduClick/
├── index.html                 # Página principal
├── finanzas.html             # Plan financiero y precios
├── simulacion-pagos.html     # Calculadora de pagos
├── HTML/
│   ├── login.html            # Sistema de autenticación
│   ├── registro.html         # Registro de usuarios
│   ├── app.html              # Dashboard del usuario
│   ├── cursos.html           # Catálogo de cursos
│   ├── curso-videos.html     # Reproductor de videos
│   ├── ver curso.html        # Vista individual de curso
│   └── perfil.html           # Gestión de perfil
├── img/                      # Recursos gráficos
├── docs/                     # Documentación del negocio
│   ├── Plan de Negocios para EducaClick.docx
│   ├── Plan financiero EducaClick.docx
│   └── EDUCLICK_20250815_215840_0000.pdf
└── README.md                 # Este archivo
```

## 💰 Modelo de Negocio

### Planes de Suscripción

| Plan | Mensual | Anual | Descuento | Características |
|------|---------|-------|-----------|----------------|
| **Básico** | $100,000 COP | $83,333 COP/mes | 17% | 5 cursos básicos, certificados |
| **Intermedio** | $100,000 COP | $83,333 COP/mes | 17% | 15 cursos, proyectos prácticos |
| **Avanzado** | $100,000 COP | $83,333 COP/mes | 17% | Todos los 30 cursos, mentoría personalizada |

### Distribución de Ganancias
- **60%** para creadores de contenido
- **40%** para profesores y tutores
- **Comisión de plataforma**: Cubierta por suscripciones

## 🎯 Objetivos del Proyecto

### Visión
Ser la plataforma educativa líder en Latinoamérica que conecta a estudiantes y expertos en todas las áreas del conocimiento, fomentando el aprendizaje colaborativo y accesible para todos.

### Misión
Proveer una plataforma intuitiva y segura donde estudiantes y profesores compartan, creen y accedan a cursos de alta calidad, asegurando oportunidades educativas para mayores de 18 años en cualquier parte del mundo.

### Meta a 5 Años
- **50,000+ estudiantes activos**
- **500+ cursos disponibles**
- **100+ creadores de contenido**
- **Presencia en 10+ países de Latinoamérica**

## 🚀 Instalación y Uso

### Requisitos Previos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional para desarrollo)

### Instalación Local

1. **Clonar el repositorio**
```bash
git clone https://github.com/tu-usuario/educlick.git
cd educlick
```

2. **Iniciar servidor local**
```bash
# Opción 1: Python
python -m http.server 8000

# Opción 2: Node.js
npx http-server

# Opción 3: PHP
php -S localhost:8000
```

3. **Abrir en navegador**
```
http://localhost:8000
```

### Uso de la Plataforma

1. **Registro/Login**: Crea una cuenta o inicia sesión
2. **Explorar Cursos**: Navega por el catálogo de cursos disponibles
3. **Suscribirse**: Elige un plan que se adapte a tus necesidades
4. **Aprender**: Accede a videos, proyectos y certificaciones
5. **Comunidad**: Interactúa con otros estudiantes y profesores

## 🎨 Características de Diseño

### Paleta de Colores
- **Primario**: `#667eea` (Azul violeta)
- **Secundario**: `#764ba2` (Púrpura)
- **Gradiente**: `linear-gradient(45deg, #667eea, #764ba2)`
- **Texto**: `#333` (Gris oscuro)
- **Fondo**: `#f8f9fa` (Gris claro)

### Tipografía
- **Fuente Principal**: Inter (Google Fonts)
- **Pesos**: 300, 400, 500, 600, 700
- **Uso**: Moderna, legible y profesional

### Componentes Reutilizables
- **Botones**: Primarios, secundarios, outline
- **Cards**: Cursos, estadísticas, información
- **Navegación**: Header fijo con dropdown
- **Formularios**: Login, registro, configuración

## 📊 Funcionalidades Implementadas

### ✅ Completadas
- [x] Página principal moderna y responsive
- [x] Sistema de autenticación (simulado)
- [x] Dashboard de usuario personalizado
- [x] Catálogo de cursos con filtros
- [x] Reproductor de videos con progreso
- [x] Simulador de pagos y ganancias
- [x] Plan financiero interactivo
- [x] Menú desplegable de usuario
- [x] Navegación suave entre secciones
- [x] Diseño responsive completo

### 🔄 En Desarrollo
- [ ] Backend con base de datos
- [ ] Sistema de pagos real
- [ ] API REST para cursos
- [ ] Chat en tiempo real
- [ ] Notificaciones push
- [ ] App móvil nativa

### 🎯 Próximas Funcionalidades
- [ ] Integración con Zoom/Teams
- [ ] Sistema de calificaciones
- [ ] Foros de discusión
- [ ] Gamificación con badges
- [ ] Análisis de aprendizaje con IA
- [ ] Marketplace de cursos

## 🤝 Contribuir al Proyecto

### Cómo Contribuir

1. **Fork** el repositorio
2. **Crea** una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. **Commit** tus cambios (`git commit -m 'Agregar nueva funcionalidad'`)
4. **Push** a la rama (`git push origin feature/nueva-funcionalidad`)
5. **Abre** un Pull Request

### Estándares de Código

- **HTML**: Semántico y accesible
- **CSS**: BEM methodology, mobile-first
- **JavaScript**: ES6+, comentarios claros
- **Commits**: Mensajes descriptivos en español

### Reportar Bugs

Usa el sistema de Issues de GitHub con:
- **Descripción clara** del problema
- **Pasos para reproducir** el bug
- **Capturas de pantalla** si es necesario
- **Información del navegador** y dispositivo

## 📈 Métricas y Analytics

### KPIs Principales
- **Tasa de conversión**: Visitantes → Suscriptores
- **Retención de usuarios**: Usuarios activos mensuales
- **Completación de cursos**: % de cursos terminados
- **NPS (Net Promoter Score)**: Satisfacción del usuario

### Herramientas de Análisis
- Google Analytics 4
- Hotjar (Heatmaps)
- Mixpanel (Eventos)
- Zendesk (Soporte)

## 🔒 Seguridad y Privacidad

### Medidas de Seguridad
- **HTTPS** en producción
- **Sanitización** de inputs
- **Validación** del lado del servidor
- **Rate limiting** en APIs
- **Backup** automático de datos

### Privacidad
- **GDPR** compliant
- **Política de privacidad** clara
- **Opt-in** para comunicaciones
- **Derecho al olvido** implementado

## 📞 Soporte y Contacto

### Canales de Soporte
- **Email**: soporte@educlick.com
- **WhatsApp**: +57 300 123 4567
- **Chat en vivo**: Disponible en la plataforma
- **Centro de ayuda**: help.educlick.com

### Redes Sociales
- **Facebook**: [@EduClickOficial](https://facebook.com/educlick)
- **Twitter**: [@EduClick_](https://twitter.com/educlick)
- **LinkedIn**: [EduClick](https://linkedin.com/company/educlick)
- **YouTube**: [EduClick Channel](https://youtube.com/educlick)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 🙏 Agradecimientos

### Equipo de Desarrollo
- **Frontend Developer**: Desarrollo de interfaces modernas
- **UX/UI Designer**: Diseño de experiencia de usuario
- **Content Creator**: Creación de cursos y materiales
- **Business Analyst**: Estrategia y modelo de negocio

### Tecnologías y Recursos
- [Font Awesome](https://fontawesome.com/) - Iconografía
- [Google Fonts](https://fonts.google.com/) - Tipografía
- [Unsplash](https://unsplash.com/) - Imágenes de stock
- [GitHub](https://github.com/) - Control de versiones

---

## 🚀 ¡Únete a la Revolución Educativa!

**EduClick** no es solo una plataforma, es un movimiento para democratizar la educación tecnológica en Latinoamérica. Cada línea de código, cada curso creado y cada estudiante que aprende contribuye a un futuro más próspero y tecnológicamente avanzado.

### 💡 ¿Listo para comenzar?

1. **Estudiantes**: [Regístrate gratis](https://educlick.com/registro) y comienza tu viaje de aprendizaje
2. **Creadores**: [Únete como instructor](https://educlick.com/instructores) y comparte tu conocimiento
3. **Empresas**: [Contáctanos](https://educlick.com/empresas) para planes corporativos
4. **Desarrolladores**: [Contribuye al proyecto](https://github.com/educlick/educlick) y ayúdanos a crecer

---

**© 2025 EduClick. Transformando la educación, un estudiante a la vez.**

[![Website](https://img.shields.io/badge/Website-educlick.com-blue)](https://educlick.com)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0.0-orange.svg)](https://github.com/educlick/educlick/releases)
[![Contributors](https://img.shields.io/badge/Contributors-Welcome-brightgreen.svg)](CONTRIBUTING.md)
