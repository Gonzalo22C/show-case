# Instrucciones de trabajo

## Estado y alcance

Este repositorio contiene únicamente la preparación documental del portafolio. Next.js, TypeScript, CSS Modules y Motion son tecnologías propuestas, todavía no implementadas. No asumas que existen una aplicación, dependencias, API o pruebas.

En la fase actual, conserva el contenido previo y limita los cambios a documentación y preparación del repositorio. No instales dependencias ni construyas pantallas sin una nueva instrucción. No hagas commit ni push salvo petición explícita.

## Convenciones de código para la implementación futura

- Usa TypeScript con tipado estricto; evita `any` y define los tipos de datos y contratos en sus límites.
- Usa nombres descriptivos en inglés para código, PascalCase para componentes y camelCase para funciones y variables. Mantén la documentación en español.
- Prefiere componentes pequeños, responsabilidades claras y CSS Modules. Centraliza colores, espacios y tipografía mediante variables CSS.
- En Next.js, prioriza componentes de servidor y añade componentes de cliente cuando una interacción los requiera.
- Valida entradas en el servidor y no expongas secretos al cliente. Versiona un solo lockfile del gestor elegido.
- Evita dependencias y abstracciones sin una necesidad concreta. Documenta versiones y comandos cuando se incorporen.

## Accesibilidad

- Usa HTML semántico, jerarquía coherente de encabezados, etiquetas de formularios y textos alternativos útiles.
- Permite navegación completa por teclado, foco visible y orden lógico de lectura. Usa enlaces para navegar y botones para acciones.
- Busca cumplir WCAG 2.2 AA: contraste suficiente, mensajes de error comprensibles y contenido que no dependa solo del color.
- Comprueba accesibilidad con revisión manual y herramientas automáticas cuando estén configuradas; una herramienta por sí sola no demuestra cumplimiento.

## Responsive y temas

- Diseña desde pantallas pequeñas y adapta los puntos de ruptura al contenido. Evita desbordamientos y comprueba zoom, textos largos y distintas anchuras.
- Propón temas claro y oscuro con tokens compartidos. Respeta inicialmente `prefers-color-scheme` y permite una elección explícita del usuario cuando se implemente el selector.
- Verifica contraste, foco, estados interactivos e imágenes en ambos temas. Evita destellos de un tema incorrecto al cargar.

## Animaciones

- Usa Motion para interacciones justificadas y evita efectos que dificulten leer o navegar.
- Respeta `prefers-reduced-motion` y las utilidades de movimiento reducido de Motion. Reduce o elimina desplazamientos, parallax y animaciones no esenciales.
- Ninguna información o acción debe depender de una animación. Comprueba que el flujo siga funcionando con movimiento reducido.

## Verificaciones

- En esta fase, revisa enlaces relativos, coherencia entre documentos y reglas de `.gitignore`. No declares comprobaciones de aplicación como ejecutadas.
- Cuando exista la aplicación, documenta y ejecuta los scripts disponibles de lint, tipos, pruebas y build según el cambio.
- Añade pruebas que verifiquen comportamientos relevantes, incluyendo errores de API e interacciones críticas; no pruebas que solo repliquen la implementación.
- Comprueba teclado, responsive, temas y movimiento reducido en navegador. Informa por separado resultados aprobados, fallidos y no ejecutados.
- Antes de entregar, revisa el diff y el estado de Git para detectar archivos generados o secretos accidentales.

## Decisiones y documentación

- Mantén README y roadmap alineados con lo que realmente existe. Marca cada elemento como propuesto, en curso o implementado con evidencia.
- Para decisiones significativas, crea un documento en `docs/decisions/` con contexto, alternativas, decisión, estado y consecuencias. No crees registros vacíos.
- Documenta contratos de API y diagramas cuando se definan, indicando si representan una propuesta o el sistema implementado.
- No inventes experiencia, clientes, métricas, proyectos ni datos de contacto del propietario.
