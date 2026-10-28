🏨 HotelApp - Gestión de Reservas

Proyecto de interfaz gráfica en JavaFX y FXML para la gestión de reservas de un hotel, con persistencia de datos en local usando XML. Realizado para el ciclo de Desarrollo de Aplicaciones Multiplataforma (DAM).

🚀 Características

Interfaz visual: Diseñada con FXML (vista.fxml) y CSS (estilos.css).

Patrón MVC: Lógica separada en HotelController.java y Main.java.

Persistencia: Carga y guardado de reservas en archivo XML (reservas.xml).

📁 Estructura del Proyecto

HotelApp/
├── .vscode/               # Configuración para ejecución en VS Code
├── src/
│   └── main/
│       ├── java/
│       │   ├── Main.java            # Clase principal (Launcher JavaFX)
│       │   └── HotelController.java # Lógica e interacción de la GUI
│       └── resources/
│           ├── estilos.css          # Hojas de estilo CSS
│           ├── reservas.xml         # Datos de las reservas
│           └── vista.fxml           # Interfaz gráfica
└── README.md


🛠️ Requisitos

Java JDK 17 o superior.

JavaFX SDK (configurado en las variables globales o mediante la carpeta .vscode).

💻 Cómo Ejecutar

Abre el proyecto en VS Code.

Asegúrate de tener instalada la extensión Extension Pack for Java.

Revisa que el path de JavaFX en .vscode/launch.json coincida con la ruta de tu equipo.

Ejecuta Main.java o pulsa F5.
