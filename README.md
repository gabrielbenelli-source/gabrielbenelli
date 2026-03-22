RDM - Repositorio de Documentación Municipal

Estado del Proyecto: Evolución estratégica basada en la arquitectura BookList SPA.
🌟 Visión General

Este proyecto nace de la necesidad de resolver la fragmentación de información en las administraciones locales. RDM transforma procesos burocráticos en una experiencia digital fluida, centrada en la eficiencia del funcionario y el servicio al ciudadano.
🎯 Caso de Estudio: Digitalización de Activos Normativos

RDM es una Single Page Application (SPA) diseñada para la gestión y clasificación de documentos, decretos y manuales de gestión territorial. Permite a departamentos clave (DIDECO, Obras, SECPLAC) centralizar activos que suelen estar dispersos en archivos físicos o silos digitales.

    Base Técnica: El proyecto utiliza como núcleo lógico la estructura de BookList, adaptando su capacidad de gestión de registros hacia un entorno de documentación institucional escalable.

🚀 El Desafío

La información municipal suele vivir en "islas" departamentales. El reto técnico consistió en construir una interfaz reactiva de alto rendimiento capaz de filtrar grandes volúmenes de documentos por categorías (Vivienda, Urbanismo, Social) sin recargas de página, optimizando el consumo de recursos en equipos institucionales limitados.
💡 Propuesta de Solución

Implementación de una arquitectura de componentes desacoplados con Vue.js, utilizando un sistema de filtrado dinámico en el lado del cliente. Se transformó la lógica de una lista simple a una estructura de datos documental, garantizando:

    Búsqueda avanzada en tiempo real.

    Navegación intuitiva segmentada por departamentos.

    Persistencia de datos optimizada.

🛠️ Stack Tecnológico

    Framework: Vue.js para una reactividad eficiente.

    Estilos: SASS/SCSS bajo una arquitectura de diseño limpia y profesional.

    Gestión de Rutas: Vue Router para la segmentación lógica de departamentos.

    Despliegue: GitHub Pages para asegurar disponibilidad y acceso inmediato.

📈 Métricas de Impacto

    Eficiencia: Estimación de un 60% de reducción en el tiempo de búsqueda de documentos técnicos en comparación con métodos tradicionales.

    Accesibilidad: Interfaz 100% responsiva, permitiendo consultas en terreno durante intervenciones territoriales.

🧬 Perfil Híbrido: Tecnología con Sentido Social

Este repositorio define mi valor profesional: la capacidad de actuar como traductor técnico-social. Entiendo el flujo operativo municipal desde el territorio y utilizo Vue.js para construir herramientas que democratizan el acceso a la información. Mi objetivo es alinear el desarrollo de software con las metas de transformación digital del Estado.
💡 Justificación para el Portafolio

Elegí este proyecto porque demuestra mi habilidad para transformar una necesidad administrativa real en una solución tecnológica concreta. Al evolucionar una base de código hacia una herramienta de GovTech, acredito agilidad, visión estratégica y alineación con la innovación pública.
🛠️ Instalación y Uso
Bash

# Instalar dependencias
npm install

# Compilar para desarrollo con Hot-Reload
npm run dev

# Compilar y minificar para producción
npm run build
