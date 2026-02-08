📒 AGENDA ELECTRÓNICA – Proyecto en Java (NetBeans)
PABEA

        AGENDA ELECTRÓNICA
Una aplicación desarrollada en Java (Swing) utilizando NetBeans, diseñada para gestionar contactos de forma sencilla mediante una interfaz gráfica intuitiva.
El proyecto combina diseño visual, lógica de programación y organización de datos en memoria.
🖥️ Descripción general
La Agenda Electrónica permite almacenar y navegar entre registros de personas, incluyendo:

DNI

Nombre

Apellido

Dirección

Teléfono

Fecha de nacimiento

El usuario puede avanzar o retroceder entre registros, así como guardar nuevos datos o modificar los existentes.
<img width="1230" height="610" alt="Captura de pantalla 2026-02-08 224854" src="https://github.com/user-attachments/assets/87486211-315b-4ed1-bff4-f303c342a2bc" />
🧩 Arquitectura del proyecto
El proyecto sigue una estructura MVC simplificada:

Vista (GUI): Interfaz gráfica creada con Swing y el editor visual de NetBeans.

Modelo: Clase Persona que representa cada registro.

Controlador: Lógica que gestiona la navegación, validación y almacenamiento de datos.
🏗️ Documentación técnica
1. Clase AgendaFrame (Vista)
Responsable de la interfaz gráfica y de la interacción con el usuario.

Funciones principales:

Mostrar los campos de entrada.

Gestionar los botones de navegación (<<, >>) y el botón Guardar.

Actualizar la vista según el registro actual.

Mostrar el índice del registro.

Componentes clave:

JTextField para cada dato.

JButton para navegación y guardado.

JLabel para el índice.
2. Clase Persona (Modelo)
Representa un contacto dentro de la agenda.

Atributos típicos:
private String dni;
private String nombre;
private String apellido;
private String direccion;
private String telefono;
private String fechaNacimiento;
Métodos:

Getters y setters.

Constructores.
🔄 Flujo de funcionamiento
La aplicación inicia mostrando un registro vacío o el primero existente.

El usuario ingresa datos o navega entre registros.

Al presionar Guardar, el controlador actualiza la lista interna.

La vista se refresca mostrando el registro actual.
🧪 Validaciones implementadas
Comprobación de campos vacíos.

Validación básica del formato del teléfono.

Control de límites al navegar entre registros.

Evitar sobrescribir datos sin intención.
🛠️ Tecnologías utilizadas
Java (JDK 8 o superior)

NetBeans IDE

Swing

POO (Programación Orientada a Objetos)

🚀 Cómo ejecutar el proyecto
Clonar el repositorio:
git clone: https://github.com/lautarocallupilmizzau-coder/Agenda_Electronica

Abrir NetBeans.

Ir a File → Open Project.

Seleccionar la carpeta del proyecto.

Ejecutar con Run Project o presionar F6.

🌱 Futuras mejoras
Persistencia de datos en archivo o base de datos.

Búsqueda por nombre o DNI.

Eliminación de registros.

Exportación de contactos a CSV.

Interfaz más moderna con JavaFX.
👨‍💻 Autor
Lautaro Callupil  
Analista de Datos Jr. | Estudiante de DAW
GitHub:   https://github.com/lautarocallupilmizzau-coder
LinkedIn: https://www.linkedin.com/in/lautaro-callupil-53947a186/
