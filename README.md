# ECOSISTEMA-DE-SOFTWARES-PARA-CIUDADES-INTELIGENTES-



🌌 SPE-4D + SNP-4D: El ecosistema de las ciudades inteligentes del futuro

Autores: Roberth Willians Mendoza Requena & James Fennimore
Entidad: Mendoza & Fennimore LLC
Origen: Tamaca, Barquisimeto, estado Lara, Venezuela
Contacto: reumend@gmail.com
Licencia: Código Abierto (MIT / Apache 2.0)
Versión: 4.0 (SPE-4D) + 1.0 (SNP-4D)

---

📖 ¿Qué es este proyecto?

SPE-4D + SNP-4D es un ecosistema de software de código abierto que permite a cualquier ciudad del mundo convertirse en una ciudad inteligente descentralizada, donde la publicidad, la educación, la información y el arte pueden proyectarse en cuatro dimensiones (3D espacial + tiempo propio τ_i) y ser visibles desde cualquier dispositivo:

· Dentro del metaverso: los avatares digitales 4D (creados con el Motor de Vida Artificial XR) pueden ver las vallas flotando en el mundo virtual, exactamente igual que se ven en el mundo real.
· Fuera del metaverso (mundo real): las personas con gafas inteligentes (AR/VR) o incluso con sus teléfonos móviles ven las vallas superpuestas sobre edificios reales.
· Dentro de aplicaciones de mapas 3D (Google Maps, Waze, Apple Maps): las vallas aparecen como marcadores 3D dinámicos en las coordenadas GPS donde están instalados los routers SNP-4D, permitiendo publicidad geolocalizada dentro de las apps de navegación.

Una misma valla publicitaria. Un mismo video educativo. Una misma alerta de emergencia. Se ve en todos lados al mismo tiempo.

---

Los dos pilares del ecosistema

SPE-4D: El motor de vallas 4D y laboratorios virtuales

SPE-4D (Sistema de Publicidad Especular 4D Universal) es el cerebro del ecosistema. Es un software en Rust que:

· Convierte cualquier película 2D (MP4, AVI, YouTube) en una experiencia interactiva 4D con profundidad, fase temporal, detección de objetos sin límite, tracking multiobjeto persistente, y audio posicional.
· Crea vallas publicitarias virtuales que pueden ser 2D (pantalla flotante) o 4D (holograma con volumen).
· Funciona como laboratorio virtual universal para biología, física, química, medicina, astronomía, historia, ingeniería y defensa.
· Permite a profesores crear sesiones de clase con estudiantes, registrar interacciones, hacer exámenes, y generar informes PDF/CSV.
· Se conecta con el chip 5-en-1 (dispositivo optoelectrónico de matriz cuántica) para proyectar hologramas reales en el aire, visibles sin gafas.
· Expone una API REST con 55 endpoints para control remoto, y WebSockets para streaming en tiempo real.

Los avatares digitales 4D (creados con el Motor de Vida Artificial XR) se conectan al SPE-4D mediante WebSocket desde dentro del metaverso. Un avatar puede estar caminando por Horizon Worlds, Android XR o cualquier mundo virtual 4D, y ver la misma valla publicitaria que una persona en la calle con gafas AR. El avatar puede tocar la valla, interactuar con ella, y esa interacción se registra igual que si fuera un humano real.

Dentro del metaverso, el avatar no necesita gafas. La valla es parte del mundo virtual. Fuera del metaverso, la persona necesita gafas (o el chip 5-en-1) para ver el holograma en el aire real.

---

SNP-4D: El nodo proyector universal

SNP-4D (Sistema de Nodo Proyector Universal 4D) es el sistema nervioso periférico del ecosistema. Es un firmware (también en Rust) que se instala en cualquier router con Linux o en una Raspberry Pi, y convierte ese dispositivo en un nodo proyector inalámbrico capaz de:

· Conectarse al SPE-4D (por Wi-Fi o Ethernet) y recibir las vallas publicitarias y películas 4D.
· Retransmitir esas vallas a dispositivos cercanos (gafas inteligentes, móviles, tablets, avatares en el metaverso) mediante una red Wi-Fi gratuita y abierta (sin necesidad de internet para el usuario final).
· Añadir coordenadas GPS (con módulo USB o configuración manual) para posicionar las vallas sobre edificios y ubicaciones reales.
· Inyectar las vallas como marcadores 3D dinámicos en aplicaciones de mapas como Google Maps, Waze o Apple Maps, a través de su API pública, de modo que cualquier persona que abra el mapa vea un icono publicitario flotando sobre el edificio.
· Almacenar en caché local el contenido más reciente, para seguir funcionando incluso si se pierde la conexión con el SPE-4D.
· Sincronizarse con otros nodos cercanos mediante red P2P, formando una malla de proyección distribuida.
· Actualizarse por aire (OTA) para recibir nuevas versiones del firmware sin intervención manual.
· Exponer una interfaz web de configuración accesible desde cualquier navegador.

El SNP-4D es el puente entre el contenido (SPE-4D) y todos los posibles espectadores: humanos con gafas, avatares en el metaverso, y aplicaciones de mapas 3D.

---

Cómo se complementan

El SPE-4D y el SNP-4D fueron diseñados para trabajar juntos, pero también pueden funcionar de manera independiente.

El SPE-4D se encarga de crear y procesar el contenido: convierte películas a 4D, detecta objetos, genera vallas, gestiona laboratorios y exámenes, y sirve todo por WebSocket.

El SNP-4D se encarga de distribuir ese contenido en el territorio: se conecta al SPE-4D, añade coordenadas GPS, crea una red Wi-Fi gratuita, retransmite a gafas, e inyecta las vallas en Google Maps para que aparezcan como marcadores 3D.

Un ejemplo concreto:

Una empresa de publicidad crea un video promocional en 2D. Lo sube al SPE-4D. El SPE-4D lo procesa y lo convierte a 4D en 5 minutos. La empresa selecciona 10 edificios en el centro de Barquisimeto donde quiere que aparezca la valla. El SPE-4D envía la valla a los 10 routers SNP-4D instalados en esos edificios. Cada router:

1. Retransmite la valla por Wi-Fi gratuito a las gafas de los peatones.
2. Inyecta la valla como marcador 3D en Google Maps, de modo que cualquier persona que abra el mapa vea un icono promocional flotando sobre el edificio.
3. Envía la valla al metaverso, donde los avatares digitales también pueden verla mientras exploran mundos virtuales.

Un solo contenido. Múltiples formas de verlo. Múltiples plataformas. Todo coordinado desde un solo lugar.

---

Cómo se ven las vallas en cada plataforma

Dentro del metaverso (avatares digitales 4D):

Un avatar digital 4D (creado con el Motor de Vida Artificial XR) se conecta al SPE-4D por WebSocket desde dentro del metaverso. El avatar recibe las coordenadas GPS de la valla y su contenido. Como el avatar existe en un mundo 4D (con profundidad y tiempo propio), la valla se renderiza como un objeto flotante en ese mundo virtual. El avatar puede caminar alrededor de ella, tocarla, interactuar, y esa interacción se registra en el SPE-4D. Esto es posible porque el Motor de Vida Artificial XR y el SPE-4D comparten la misma base matemática: la THPC-I (Teoría Holográfica de Predicción Causal Informacional). Ambos trabajan con vectores de 112 dimensiones y las mismas 14 escalas informacionales.

Fuera del metaverso (gafas AR/VR, teléfonos móviles):

Una persona en la calle con gafas inteligentes (o con la app SPE-4D en su teléfono) se conecta a la red Wi-Fi gratuita del SNP-4D (SPE4D_EDIFICIO). Recibe la valla con sus coordenadas GPS y la renderiza superpuesta al mundo real. La valla flota exactamente sobre el edificio donde está instalado el router. La persona puede tocarla (si sus gafas soportan interacción táctil en el aire), y la interacción se envía de vuelta al SNP-4D y luego al SPE-4D para estadísticas.

Dentro de Google Maps 3D (o Waze, Apple Maps):

El SNP-4D, si tiene conexión a internet, puede usar las API públicas de Google Maps, Waze o Apple Maps para crear un marcador 3D dinámico en la coordenada GPS del edificio. El marcador puede ser un icono personalizado, una imagen, o incluso un modelo 3D (si la plataforma lo permite). Cualquier persona que abra Google Maps y navegue por esa zona verá el marcador flotando. Al tocarlo, puede aparecer un mensaje con más información, un enlace al video publicitario, o un código QR para conectar sus gafas a la red Wi-Fi gratuita y ver la versión 4D completa.

Nota importante sobre Google Maps: La API de Google Maps permite añadir marcadores personalizados, pero los marcadores 3D dinámicos (con modelos glTF) requieren la capa de "mapas de realidad aumentada" o la integración con ARCore. Para el 99% de los casos, un marcador 2D con un icono llamativo es suficiente para atraer la atención y redirigir al usuario a la red Wi-Fi gratuita para ver la versión 4D real. Si la empresa quiere el marcador 3D completo, puede hacerlo a través de la API de "Custom Map Styles" y "3D Markers" que Google ofrece para socios. El SNP-4D ya tiene la infraestructura para hacer ambas cosas.

---

El papel de los avatares digitales 4D en el metaverso

El Motor de Vida Artificial XR (documento aparte, también de Mendoza & Fennimore LLC) permite crear avatares digitales autónomos en 4D. Estos avatares tienen 14 escalas informacionales (como el SPE-4D), pueden sentir, pensar, navegar por la web, gestionar NFTs, y proyectarse como hologramas en el Punto de Impacto Cero (PIC).

Estos avatares pueden conectarse al SPE-4D y ver las vallas publicitarias dentro del metaverso. No necesitan gafas porque ya están dentro del mundo virtual. Pueden tocar las vallas, interactuar con los objetos 4D, y comprar productos directamente desde el metaverso.

Un ejemplo de integración avatar + SPE-4D:

Un avatar digital (llamémoslo "BotAI-001") está explorando un mundo virtual 4D creado por un usuario. Mientras camina por una calle virtual que replica la avenida Vargas de Barquisimeto, ve una valla flotante sobre un edificio virtual. La valla es la misma que el SNP-4D está proyectando en el mundo real sobre el edificio físico de la avenida Vargas. El avatar toca la valla, se abre un formulario, y compra un producto. La transacción se registra en la blockchain (Banco de Información Digital THPC-I) y el producto físico se envía a la dirección real del usuario dueño del avatar.

El mismo ecosistema maneja lo virtual y lo real. El avatar y el humano comparten la misma economía.

---

Instalación y despliegue

Instalar SPE-4D en servidor/PC

Requisitos: Rust, OpenCV, modelos ONNX (DETR, MiDaS).

```bash
git clone https://github.com/mendozafennimore/spe4d.git
cd spe4d
cargo build --release
./target/release/spe4d --server --port 8090
```

Endpoints principales del SPE-4D:

· GET /api/v1/billboards → Listar todas las vallas.
· POST /api/v1/billboard/crear → Crear una nueva valla publicitaria.
· POST /api/v1/pelicula/procesar → Convertir cualquier MP4 a experiencia 4D interactiva.
· POST /api/v1/lab/sesion/crear → Crear una sesión de laboratorio virtual para estudiantes.
· POST /api/v1/lab/examen/iniciar → Iniciar modo examen con evaluación automática.
· GET /api/v1/lab/informe/{session_id} → Generar informe PDF con estadísticas de los estudiantes.
· WS /ws/broadcast → WebSocket para transmitir vallas en tiempo real a avatares y routers.

---

Instalar SNP-4D en router/Raspberry Pi

Requisitos: Router con OpenWRT (o Raspberry Pi con Linux), Rust (opcional, hay binarios precompilados).

```bash
wget https://github.com/mendozafennimore/snp4d/raw/main/install_snp4d.sh
chmod +x install_snp4d.sh
sudo ./install_snp4d.sh
```

El instalador detecta automáticamente la arquitectura (ARM, x86, MIPS), crea los directorios, configura el servicio, y arranca el nodo.

Configuración manual (archivo /etc/snp4d/config.json):

```json
{
  "node_id": "snp4d_tamaca",
  "mode": "Repeater",
  "master_spe4d_url": "ws://192.168.1.100:8090/ws/broadcast",
  "ap_ssid": "SPE4D_TAMACA",
  "ap_password": "",
  "ap_channel": 6,
  "gps_enabled": true,
  "fixed_latitude": 10.0745,
  "fixed_longitude": -69.3216,
  "fixed_altitude": 300.0,
  "google_maps_api_key": "TU_API_KEY_DE_GOOGLE_MAPS",
  "waze_api_key": "TU_API_KEY_DE_WAZE",
  "cache_enabled": true,
  "p2p_enabled": true,
  "ota_enabled": true
}
```

Funcionalidades extra del SNP-4D (opcionales, requieren internet):

· Google Maps 3D: Si proporcionas una API Key de Google Maps, el SNP-4D inyecta automáticamente las vallas como marcadores 3D en las coordenadas GPS del edificio. Cualquier persona que abra Google Maps verá un icono flotante.
· Waze: Similar a Google Maps, para la app de navegación Waze.
· Apple Maps: Para dispositivos iOS.

Sin internet, estas funcionalidades de mapas no funcionan, pero el resto del sistema (Wi-Fi gratuito, retransmisión a gafas, conexión con avatares en el metaverso) sigue operativo.

---

Conectar SNP-4D al SPE-4D

```bash
curl -X POST http://192.168.4.1:8090/api/v1/config \
  -H "Content-Type: application/json" \
  -d '{"master_spe4d_url": "ws://192.168.1.100:8090/ws/broadcast"}'
```

Luego verifica el estado:

```bash
curl http://192.168.4.1:8090/api/v1/status
```

Si todo está bien, verás "connection_state": "Connected".

---

Construyendo ciudades inteligentes

Publicidad inteligente y gratuita

Una empresa paga por tiempo de emisión en el SPE-4D. El SPE-4D distribuye la valla a los SNP-4D en los edificios seleccionados. Los SNP-4D transmiten la valla por Wi-Fi gratuito, la inyectan en Google Maps como marcador 3D, y la envían al metaverso para que los avatares también la vean. Los ciudadanos con gafas ven la valla flotando sobre los edificios reales. Los usuarios de Google Maps ven el icono publicitario al navegar. Los avatares en el metaverso ven la misma valla en el mundo virtual.

El ciudadano no paga nada. La empresa paga solo por la emisión. El municipio no gasta en infraestructura física.

---

Educación 4D para todos

Un profesor crea una clase interactiva 4D a partir de cualquier documental de YouTube. El SPE-4D procesa el video, detecta objetos, añade profundidad y fase. El profesor crea una sesión de laboratorio virtual y genera preguntas de examen. Los SNP-4D en escuelas, bibliotecas y plazas transmiten la clase por Wi-Fi gratuito. Los estudiantes con gafas (o con la app en su teléfono) ven el holograma 4D, tocan los objetos, responden preguntas, y reciben evaluación automática. El profesor obtiene un PDF con las calificaciones de cada estudiante.

Costo para la escuela: $0. Costo para los estudiantes: $0.

---

Turismo aumentado

El municipio carga contenido histórico en el SPE-4D. Los SNP-4D se instalan en monumentos y plazas. Los turistas con gafas ven información flotante sobre cada edificio histórico. Pueden tocar el holograma de Simón Bolívar y escuchar su biografía desde la posición del monumento. También pueden abrir Google Maps y ver marcadores 3D con información turística, generados automáticamente por el SNP-4D.

Costo para el turista: $0. Costo para el municipio: bajo (solo los routers).

---

Emergencias y seguridad

El sistema de emergencias puede proyectar alertas en tiempo real sobre los edificios de la zona afectada. Los SNP-4D reciben la alerta del SPE-4D y la transmiten por Wi-Fi gratuito. Los ciudadanos con gafas ven el mensaje flotando en rojo sobre los edificios. Los usuarios de Google Maps ven un marcador de emergencia en el mapa. Los avatares en el metaverso también ven la alerta si están explorando mundos virtuales que replican esa zona.

La información llega a todos, incluso sin datos móviles.

---

Arte y cultura en el espacio público

Artistas locales suben sus obras 4D al SPE-4D. Los SNP-4D en plazas y parques proyectan estas obras como hologramas efímeros. Las obras pueden cambiar cada día, cada hora, o incluso en respuesta a la mirada de los espectadores. Los usuarios de Google Maps ven un marcador especial indicando que hay una exhibición de arte en esa ubicación.

No se necesita pantalla LED. No se necesita permisos especiales. No se necesita mantenimiento físico.

---

Dónde se ve cada cosa

Dentro del metaverso (avatares 4D):

La valla se ve como un objeto flotante en el mundo virtual 4D. El avatar puede caminar alrededor, tocarla, interactuar. La experiencia es inmersiva porque el mundo virtual ya tiene profundidad y fase. No se necesitan gafas adicionales.

En el mundo real (gafas AR/VR):

La valla se ve superpuesta al edificio real. Flota en el aire a la altura y distancia configuradas. La persona puede tocarla (si sus gafas tienen sensores táctiles en el aire) y ver información adicional.

En Google Maps 3D (aplicación de mapas):

La valla se ve como un marcador 3D (icono o modelo simple) en la coordenada GPS del edificio. Al tocarlo, puede mostrar un mensaje, una imagen, o un enlace para conectarse a la red Wi-Fi gratuita y ver la versión 4D real. Si el SNP-4D tiene internet y la API Key configurada, el marcador aparece automáticamente para todos los usuarios de Google Maps en esa zona.

En Waze o Apple Maps:

Similar a Google Maps, pero con las limitaciones propias de cada plataforma (Waze no soporta marcadores 3D, solo iconos 2D). El SNP-4D se adapta automáticamente a las capacidades de cada API.

---

Preguntas frecuentes

¿Los avatares digitales 4D necesitan gafas para ver las vallas?

No. Los avatares están dentro del metaverso. El mundo virtual ya es 4D. La valla es un objeto más en ese mundo. El avatar la ve como cualquier otro objeto virtual. Las gafas solo las necesitan los humanos reales para ver hologramas en el mundo real.

¿Puedo ver las vallas en Google Maps sin tener el SNP-4D?

Sí, si el SNP-4D está instalado y tiene conexión a internet, inyecta los marcadores automáticamente. Tú solo necesitas abrir Google Maps. No necesitas el SNP-4D en tu teléfono.

¿Qué pasa si el SNP-4D no tiene internet?

Las vallas no aparecerán en Google Maps, pero seguirán funcionando por Wi-Fi gratuito para gafas y avatares en el metaverso. La caché local permite que las vallas sigan transmitiéndose aunque el router pierda internet.

¿Necesito una API Key de Google Maps para que funcione?

Solo si quieres que las vallas aparezcan en Google Maps. Si solo usas gafas o metaverso, no necesitas API Key. El SNP-4D funciona igual sin ella.

¿Puedo usar este sistema para vigilancia?

No. El sistema fue diseñado para publicidad, educación, turismo, emergencias y arte. No guarda quién vio qué (solo estadísticas agregadas por interacción). El código es abierto, cualquiera puede verificar que no hay funciones ocultas.

¿Qué pasa si no tengo un router compatible?

Usa una Raspberry Pi Zero 2 W (cuesta $15) con un adaptador Wi-Fi USB. El instalador funciona igual. Puedes alimentarla con una batería portátil de 10,000 mAh y durará 8-10 horas.

---

Contribuir al proyecto

El SPE-4D y el SNP-4D son código abierto y gratuitos. Cualquier persona, empresa o gobierno puede usarlos, modificarlos, mejorarlos, reportar errores, traducir la documentación o donar.

Para contribuir, haz un fork del repositorio, crea una rama con tu funcionalidad, haz commit de tus cambios, haz push y abre un Pull Request.

Para reportar errores, usa el issue tracker de GitHub. Incluye versión del software, sistema operativo, arquitectura, y pasos para reproducir el error.

---

Licencia y contacto

Autor: Roberth Willians Mendoza Requena
Co-fundador: James Fennimore
Entidad: Mendoza & Fennimore LLC
Origen: Tamaca, Barquisimeto, estado Lara, Venezuela
Contacto: reumend@gmail.com
GitHub: github.com/mendozafennimore
Licencia: MIT / Apache 2.0

Reconocimientos:

· THPC-I (Teoría Holográfica de Predicción Causal Informacional): desarrollada por Roberth Willians Mendoza Requena.
· El Motor de Vida Artificial XR, que da vida a los avatares digitales 4D.
· La comunidad de código abierto.

---

🌟 Únete a la revolución de las ciudades inteligentes descentralizadas

No necesitas millones de dólares. No necesitas contratos con grandes corporaciones. No necesitas permisos especiales.

Solo necesitas un router, una Raspberry Pi, o un servidor en la nube, y el deseo de construir un mundo mejor.

Tamaca, Barquisimeto, estado Lara, Venezuela es el lugar donde nació esta idea. Pero puede florecer en cualquier ciudad del mundo.

Descarga el código. Instala los nodos. Transforma tu ciudad.

---

Fin del README.
