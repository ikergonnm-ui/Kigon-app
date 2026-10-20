Kigon — Consigue tus objetivos (prototipo v2)

NOVEDADES DE V2
- Plan semanal editable con checklist y porcentaje completado.
- Gráficos de barras de minutos de programación y horas de sueño por día.
- Resumen semanal de programación, gimnasio, días registrados y alcohol.
- Menú orientativo según objetivo (definir gradualmente, mantener o ganar masa) y preferencia (variada, económica/rápida o vegetariana).
- Biblioteca para guardar aprendizajes, vídeos/recursos, ideas, proyectos, dudas y notas, con búsqueda y filtros.
- Apartado “Pregunta a Kigon” con orientación local básica y enfoque en prioridades.
- Se conservan el onboarding, check-in diario, objetivos, calendario, diario, finanzas, fotos y copias de seguridad.

IMPORTANTE: LIMITACIONES DEL PROTOTIPO
- El asesor todavía NO está conectado a una IA real. Sus respuestas se generan con reglas locales y son orientativas. Para un chat de IA abierto se necesita integrar un proveedor de IA mediante un backend seguro; nunca poner una clave secreta dentro del HTML.
- El menú es una plantilla general, no una dieta clínica ni un cálculo personalizado de calorías/macros.
- Los datos se guardan localmente en el navegador de cada dispositivo. No hay cuenta, backend ni sincronización entre ordenador e iPhone.
- Las notificaciones de esta versión son limitadas; no garantiza avisos cuando la app está cerrada.
- Para instalarla como web app en iPhone y usar el service worker, publícala en un hosting HTTPS. En iPhone, abre la URL con Safari > Compartir > Añadir a pantalla de inicio.
- Exporta copias de seguridad con frecuencia. Las fotos ocupan almacenamiento local.

PUBLICACIÓN SENCILLA
1. Descomprime el ZIP en Windows.
2. Crea un repositorio público en GitHub (por ejemplo, kigon-app).
3. Sube al nivel principal del repositorio el contenido de la carpeta kigon_app: index.html, manifest.webmanifest, sw.js e icon.svg.
4. En GitHub, abre Settings > Pages y activa la publicación desde la rama main y la carpeta /(root).
5. Espera a que GitHub Pages indique la URL HTTPS. Abre esa URL en Safari en el iPhone y usa Compartir > Añadir a pantalla de inicio.

Antes de guardar datos personales reales, ten en cuenta que esta es una primera versión local y no sincronizada.
