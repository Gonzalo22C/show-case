# Roadmap del portafolio

## Estado inicial

**Implementado:** README, `.gitignore`, instrucciones de trabajo y este roadmap.

**Propuesto:** todas las fases de producto descritas a continuación. No existe una aplicación ni se han instalado dependencias. Los criterios de aceptación son verificaciones futuras, no resultados obtenidos.

## 1. Estructura — propuesto

- Definir el contenido real: perfil, habilidades, proyectos, servicios y contacto para empleadores y clientes.
- Acordar rutas, navegación y organización de componentes, estilos, datos y recursos.
- Elegir versiones compatibles de Next.js, TypeScript, CSS Modules y Motion, y un gestor de paquetes.
- Inicializar el proyecto cuando se autorice la implementación, conservando estos archivos; documentar scripts y configuración de ejemplo sin secretos.

**Criterio de aceptación:** estructura acordada y, después de inicializar, instalación reproducible y arranque verificados con comandos documentados.

## 2. Diseño — propuesto

- Preparar wireframes y definir tipografía, espaciado, colores y estados interactivos.
- Diseñar navegación y contenido para móvil y escritorio, con temas claro/oscuro.
- Definir foco, contraste, comportamiento por teclado y alternativas de movimiento reducido.

**Criterio de aceptación:** diseño revisable para las secciones iniciales, ambos temas y tamaños representativos, con requisitos de accesibilidad explícitos.

## 3. Implementación — propuesto

- Construir presentación, perfil, proyectos, servicios y contacto con contenido proporcionado por el propietario.
- Aplicar CSS Modules, tokens de diseño y componentes tipados.
- Incorporar animaciones de Motion que respeten movimiento reducido.
- Añadir metadatos, optimización de imágenes y estados de carga/error donde sean necesarios.

**Criterio de aceptación:** navegación y contenido funcionales, temas y responsive comprobados, sin depender de animaciones para completar acciones.

## 4. API REST — propuesto

- Determinar qué requiere backend; los contenidos estáticos y enlaces de contacto pueden cubrir el primer lanzamiento.
- Si se necesita API, definir recursos, endpoints, métodos, formatos, códigos de estado y errores antes de implementarla.
- Evaluar handlers de Next.js frente a un servicio separado y documentar la decisión.
- Para un eventual formulario, definir validación de servidor, protección contra abuso, tratamiento de datos personales y proveedor de entrega. Solicitar configuración segura solo cuando sea necesaria.
- Implementar y probar únicamente los endpoints aprobados; documentar el contrato y ejemplos sin datos sensibles.

**Criterio de aceptación:** alcance de API decidido y documentado; si se implementa, respuestas válidas y errores verificados. Si se aplaza, dejar explícita la decisión y el comportamiento de contacto disponible.

## 5. Diagramas — propuesto

- Crear diagramas Mermaid de navegación y componentes principales.
- Añadir un diagrama de arquitectura y, si existe API, secuencias de petición, validación, respuesta y fallos.
- Marcar cada diagrama como propuesto o implementado y actualizarlo al cambiar la arquitectura.

**Criterio de aceptación:** diagramas legibles y coherentes con las decisiones y el estado del proyecto. Pueden elaborarse desde las fases de estructura y diseño.

## 6. Verificación — propuesto

- Ejecutar lint, comprobación de tipos, pruebas relevantes y build con los scripts definidos.
- Comprobar navegación y contacto, enlaces, teclado, foco, contraste, zoom y textos alternativos.
- Revisar móvil/escritorio, ambos temas y movimiento reducido.
- Si existe API, verificar entradas inválidas, errores y protecciones acordadas además del flujo exitoso.
- Evaluar rendimiento y metadatos; documentar resultados, defectos conocidos y comprobaciones pendientes antes de publicar.

**Criterio de aceptación:** resultados reproducibles documentados y defectos que bloqueen el lanzamiento resueltos o alcance ajustado explícitamente. Estas comprobaciones acompañan cada fase, no solo el cierre.

## Siguiente paso

Revisar el alcance y proporcionar el contenido inicial del portafolio. Después, autorizar la inicialización técnica y elegir versiones y gestor de paquetes. Esta preparación no incluye instalación, pantallas ni publicación.
