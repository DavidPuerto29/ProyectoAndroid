# 📱AndroidApp-Kotlin

Aplicación móvil desarrollada en **Kotlin** con **Jetpack Compose**.  
Integración de datos en la nube mediante **Firebase**, enfocada en funcionalidad más que en diseño visual.

## ⚡ Demostración de la aplicación  

<div align="center">
  <img width="394" height="878" alt="01 Inicio De Sesión" src="https://github.com/user-attachments/assets/edd3d47e-bcb5-4626-9849-6e752408b420" />
  
  Pantalla de inicio de sesión que permite autenticarse de manera básica, con todos los datos almacenados en la base de datos Firestore.
  
<img width="390" height="879" alt="02 Lista De Recambios" src="https://github.com/user-attachments/assets/0bfe49bb-5bc2-4176-b49d-6b192d9b7938" />

  Una vez iniciada la sesión, el usuario será redirigido a una pantalla donde se listan los diferentes tipos de recambios registrados en la base de datos, con la opción de añadir un nuevo recambio mediante un botón.
  
<img width="394" height="874" alt="03 Añadir Recambio" src="https://github.com/user-attachments/assets/a29b2739-a5f4-4687-a3bc-b345bc4c8868" />

  En la pantalla de añadir un recambio, el usuario debe introducir todos los datos del nuevo recambio y pulsar el botón Añadir para registrarlo en la base de datos.
  
<img width="390" height="880" alt="04 Modificar Recambio" src="https://github.com/user-attachments/assets/9b6fe991-788a-4c90-8610-258842ddf902" />

  El usuario también podrá modificar un recambio, siendo redirigido a un listado con los datos del producto, donde podrá editar cualquier información que desee.
  
</div>

📂 Otras capas y utilidades

Repositorios (Repository): Gestionan la comunicación con Firebase y centralizan el acceso a los datos.

ViewModels: Orquestan la lógica entre la interfaz y los datos, siguiendo la arquitectura MVVM.

Utilidades: Funciones y componentes reutilizables para manejar formularios, validaciones y operaciones con Firebase.

🎯 Conclusión
El proyecto demuestra buenas prácticas y una estructura clara, aplicando MVVM, persistencia en la nube con Firebase y gestión de datos en tiempo real.
Aunque el diseño visual es básico, el código enfatiza organización, mantenibilidad y escalabilidad, dejando la puerta abierta para interfaces más complejas o integración con otras APIs.
