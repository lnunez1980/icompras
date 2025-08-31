# iCompras - Asistente Inteligente de Compras y Restaurantes

## 📋 Descripción del Proyecto

**iCompras** es una aplicación web que presenta un chatbot inteligente diseñado para revolucionar la experiencia de compra de los usuarios. Utiliza inteligencia artificial para ayudar a encontrar productos, comparar precios y descubrir opciones en restaurantes, proporcionando un asistente personal para mejores decisiones de compra.

### 🎯 Propósito
- Facilitar la búsqueda y comparación de productos
- Asistir en la selección de opciones gastronómicas
- Proporcionar recomendaciones personalizadas
- Optimizar el proceso de toma de decisiones de compra

---

## 🏗️ Arquitectura del Proyecto

### Frontend Web
- **Tipo**: Single Page Application (SPA) estática
- **Arquitectura**: Cliente-servidor tradicional con enfoque en experiencia de usuario
- **Patrón**: Landing page con secciones modulares

### Estructura de Capas
```
┌─────────────────────┐
│   Presentación      │  ← HTML semántico + CSS moderno
├─────────────────────┤
│   Interfaz          │  ← Componentes visuales reutilizables
├─────────────────────┤
│   Lógica de Negocio │  ← JavaScript (futuro)
├─────────────────────┤
│   Assets Estáticos  │  ← Imágenes, estilos, recursos
└─────────────────────┘
```

---

## 🛠️ Tecnologías Utilizadas

### Frontend
- **HTML5**: Estructura semántica con SEO optimizado
- **CSS3**: Estilos modernos con variables CSS y responsive design
- **JavaScript**: (Preparado para implementación futura)

### Librerías y Frameworks
- **Google Fonts**: Tipografías Poppins, Plus Jakarta Sans, Inter
- **CSS Grid & Flexbox**: Layout responsivo
- **CSS Variables**: Sistema de diseño consistente

### SEO y Metadatos
- **Open Graph**: Integración para redes sociales
- **Twitter Cards**: Optimización para Twitter
- **JSON-LD Schema**: Marcado estructurado para buscadores
- **Meta tags optimizados**: SEO técnico implementado

### Herramientas de Desarrollo
- **IntelliJ IDEA**: IDE principal de desarrollo
- **Git**: Control de versiones
- **Favicon**: Identidad visual consistente

---

## 📁 Organización del Proyecto

```
icompras/
├── README.md                    # Documentación principal
├── index.html                   # Página principal de la aplicación
├── delete_account.html          # Página de eliminación de cuenta
├── terms_and_conditions.html    # Términos y condiciones
├── icompras.iml                # Configuración de IntelliJ IDEA
├── .gitignore                  # Archivos excluidos del repositorio
├── .git/                       # Control de versiones Git
├── .idea/                      # Configuraciones del IDE
└── assets/                     # Recursos estáticos
    ├── css/
    │   └── styles.css          # Estilos principales de la aplicación
    └── img/
        ├── logo-icompras.png   # Logo principal de la aplicación
        └── logo.png            # Logo alternativo
```

### Descripción de Archivos Principales

- **`index.html`**: Landing page principal con hero section, servicios, características y contacto
- **`delete_account.html`**: Página de gestión de privacidad para eliminación de cuentas
- **`terms_and_conditions.html`**: Términos legales y condiciones de uso
- **`styles.css`**: Sistema de diseño completo con variables CSS y componentes reutilizables

---

## ✨ Funcionalidades Principales

### 🤖 Servicios del Chatbot
- **Búsqueda Inteligente**: Sistema de IA para encontrar productos específicos
- **Comparación de Precios**: Análisis multi-tienda en tiempo real
- **Asistencia en Restaurantes**: Recomendaciones gastronómicas personalizadas
- **Recomendaciones Personalizadas**: Sugerencias basadas en preferencias del usuario
- **Alertas Inteligentes**: Notificaciones sobre ofertas y disponibilidad
- **Listas Personales**: Organización de productos y favoritos

### 🎨 Características de la Interfaz
- **Diseño Responsivo**: Optimizado para dispositivos móviles y desktop
- **Accesibilidad**: Estructura semántica y navegación intuitiva
- **SEO Optimizado**: Meta tags y schema markup implementados
- **Sistema de Colores**: Variables CSS para consistencia visual
- **Tipografía Moderna**: Fuentes web optimizadas para legibilidad

---

## 👨‍💻 Información del Desarrollador

- **Autor**: Luis Rafael Nuñez Barrientos
- **Contacto**: lnunezb6@gmail.com
- **Ubicación**: Bogotá, Colombia
- **Dominio**: https://icompras.app (futuro)

---

## 🚀 Roadmap de Desarrollo

### Fase Actual: Frontend Estático ✅
- Landing page responsive
- Sistema de diseño implementado
- SEO y metadatos optimizados

### Próximas Fases:
1. **Backend Integration**: Implementación del chatbot con IA
2. **Database**: Sistema de usuarios y preferencias
3. **API Integration**: Conexión con tiendas y restaurantes
4. **Mobile App**: Aplicación nativa para iOS y Android
5. **Analytics**: Sistema de métricas y seguimiento

---

## 📋 Instalación y Uso

### Requisitos
- Navegador web moderno
- Servidor web local (opcional para desarrollo)

### Instalación
```bash
# Clonar el repositorio
git clone [URL_DEL_REPOSITORIO]
cd icompras

# Abrir en navegador
open index.html
# o usar un servidor local
python -m http.server 8000
```

---

## 🔒 Privacidad y Seguridad

- Cumplimiento con normas de protección de datos
- Página dedicada para eliminación de cuentas
- Términos y condiciones claros
- Política de privacidad implementada

---

## 📞 Soporte y Contacto

- **Email de Soporte**: lnunezb6@gmail.com
- **Consultas de Privacidad**: lnunezb6@gmail.com
- **Issues**: A través del repositorio Git

---

*Proyecto desarrollado con ❤️ para revolucionar la experiencia de compras inteligentes*

