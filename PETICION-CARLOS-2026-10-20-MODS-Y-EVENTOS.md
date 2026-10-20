# Petición de Carlos — ampliar lane de mods y herramientas de staff
Fecha: 2026-10-20 (America/Monterrey).
Estado: PETICIÓN REGISTRADA; pendiente de recepción por el orquestador, investigación, integración y pruebas.

## Para Claude que está orquestando Create / go-karts / guns / sentry
Carlos pidió expresamente publicar este mismo aviso en todos sus repos de Bolillo para que la sesión activa pueda detectarlo. Es un único encargo replicado, no seis tareas independientes. Al detectarlo, reconciliarlo con la lane activa y registrar dónde se atiende, evitando integraciones duplicadas. Este commit no demuestra que Claude lo haya leído.

## Ampliación solicitada
1. Añadir a la evaluación e integración de la lane el mod indicado por Carlos:
   https://www.curseforge.com/minecraft/mc-mods/create-copper-zinc
   Verificar nombre, release exacto, Minecraft 1.20.1, Forge 47.4.23, versión de Create y dependencias reales. No se afirma compatibilidad comprobada en este aviso.
2. Investigar y seleccionar un mod que permita al staff poseer y controlar realmente un mob: entrar en su perspectiva, moverlo y manejar sus acciones. Observar desde su cámara o adoptar sólo su apariencia no satisface la petición. Preferir control amplio, incluidas habilidades/ataques/interacciones cuando sea técnicamente posible, y documentar límites para mobs vanilla y de mods.
3. Carlos autoriza ampliar la búsqueda e incorporar herramientas complementarias útiles de staff para organizar eventos. Cuantas más funciones útiles y coherentes aporte el conjunto, mejor: controlar entidades/NPC, preparar encuentros y oleadas, disparar acciones, ambientación, efectos/sonidos y escenas de misterio/terror. Estas son capacidades a evaluar; no se afirma que un mod concreto las ofrezca. Evitar sumar mods redundantes por cantidad.

## Criterios para resolver
- Comparar candidatos con fuentes oficiales y archivos exactos para Forge 1.20.1; distinguir posesión real de cámara, morph y simple espectador.
- Elegir el conjunto más capaz y mantenible para eventos manuales del staff. Si no existe posesión completa compatible, explicar la limitación y la mejor alternativa verificable, sin marcarla como equivalente.
- Restringir las funciones administrativas al staff; verificar permisos con cuenta sin OP y restauración del jugador al salir del mob, morir o desconectarse.
- Reconciliar con la base y el trabajo en curso de Create/go-karts/guns/sentry; respetar AGENTS.md y contratos vigentes del repo principal.
- Integrar sólo mediante el flujo de la lane, con dependencias, metadata packwiz y refresh cuando corresponda. No versionar JAR ni modificar el mundo oficial.
- Probar carga de servidor/cliente, posesión y movimiento/acciones reales con jugador, permisos, compatibilidad y coste de rendimiento. Separar evidencia estática, headless y con cliente.
- Dejar recepción, selección, integración y resultados verificables en la coordinación. Este aviso documenta autorización/intención del usuario, no instalación ni aprobación técnica de candidatos específicos.

## Alcance de esta publicación
Sólo documentación de la petición. No se han instalado mods, alterado configs ni ejecutado pruebas de Minecraft. Las copias en repos de carteles, wiki y catálogos son avisos para descubrimiento; la implementación corresponde a la lane del modpack.
