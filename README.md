🏆 Prode Oficina 2026

Una app web moderna, mobile-first y en tiempo real para jugar al Prode del Mundial 2026 con los compañeros de la oficina. Cero plata, pura gloria y el derecho a gastar al que sale último. 
⚽️🌎✨ Características☁️ Multijugador en Tiempo Real: Todos los pronósticos y las tablas se sincronizan al instante usando Firebase.📱 Diseño Mobile-First: Interfaz en modo oscuro (Dark Mode) con detalles en verde lima tipo neón, optimizada para usar con una mano mientras te tomás un café en el break.
📊 Ranking Automático: Tabla de posiciones general de la oficina que se actualiza sola a medida que se cargan los resultados reales.
🌍 Fixture del Mundial: Pestaña dedicada para ver cómo van quedando los países en la fase de grupos real (Puntos, Diferencia de Gol, Partidos Jugados).
🕵️‍♂️ Login sin fricción: Autenticación anónima transparente. Los usuarios solo ponen su nombre y entran a la cancha.🛠️ Tecnologías UtilizadasFrontend: React.jsEstilos: Tailwind CSSÍconos: Lucide ReactBackend / DB: Firebase (Auth Anónimo + Firestore)
📋 Reglas del Juego (Puntuación)Para mantener la paz en Recursos Humanos, las reglas son simples:El Pleno (3 Puntos): Acertar el resultado exacto del partido (ej. pronosticas 2-1 y termina 2-1).El Acierto (1 Punto): Acertar el ganador o el empate, pero sin adivinar los goles exactos (ej. pronosticas 1-0 y termina 3-0).Nada (0 Puntos): Le erraste fiero.Desempate: En caso de igualdad de puntos en el ranking, queda arriba quien tenga mayor cantidad de "Plenos".🚀 Instalación y Desarrollo LocalSi querés clonar este repo y correrlo en tu máquina:Cloná el repositorio:git clone [https://github.com/TU_USUARIO/prode-oficina-2026.git](https://github.com/TU_USUARIO/prode-oficina-2026.git) cd prode-oficina-2026
Instalá las dependencias (asumiendo que usas Vite o Create React App):npm install
Configuración de Firebase:El proyecto utiliza Firebase. Asegurate de crear un proyecto en la consola de Firebase, habilitar Authentication (Anónimo) y Firestore Database, y reemplazar la variable __firebase_config en el código con tus credenciales reales si lo vas a sacar de este entorno.Levantá el servidor de desarrollo:npm run dev
🌐 Cómo publicar en GitHub PagesPara publicar tu Prode directamente en GitHub Pages gratis:Asegurate de instalar el paquete gh-pages:npm install gh-pages --save-dev
Agregá estas líneas a tu package.json:"homepage": "https://TU_USUARIO.github.io/prode-oficina-2026",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist" // (o "build" dependiendo si usas Vite o CRA)
}
Ejecutá el comando de deploy:npm run deploy
¡Listo! Compartile el link a tus compañeros.Hecho con 🧉 y mucho fútbol para la muchachada de la ofi.
