\# 3. Patrones de diseño



Los patrones de diseño son soluciones reutilizables a problemas habituales en el desarrollo de software. En el Sistema de Control de Rescate y Adopción Animal se aplicarán patrones que faciliten la organización, el mantenimiento y la ampliación del sistema.



\## 3.1 Singleton



\*\*Propósito:\*\* garantizar que una clase tenga una única instancia accesible desde diferentes partes del sistema.



\*\*Aplicación:\*\* se utilizará en la clase `GestorCasos`, encargada de centralizar las operaciones de gestión y consulta de los casos registrados.



\*\*Justificación:\*\* permite mantener un punto de acceso común para las operaciones de gestión de casos y evita crear múltiples gestores independientes cuando no sean necesarios.



\## 3.2 Observer



\*\*Propósito:\*\* establecer una relación de suscripción para que varios objetos reciban notificaciones cuando otro objeto experimenta un cambio.



\*\*Aplicación:\*\* cuando cambia el estado de un caso, el sistema notificará a los usuarios interesados, como los voluntarios asignados o el administrador.



\*\*Clases relacionadas:\*\* `ObservadorCaso`, `Notificador` y `NotificacionVoluntario`.



\*\*Justificación:\*\* facilita la comunicación entre componentes y permite incorporar nuevos tipos de notificaciones sin modificar toda la lógica de gestión de casos.



\## 3.3 Factory Method



\*\*Propósito:\*\* delegar la creación de objetos a una fábrica, evitando concentrar toda la lógica de construcción en el código principal.



\*\*Aplicación:\*\* la clase `FabricaExpedientes` permitirá crear diferentes tipos de expedientes, como `Perro`, `Gato` y `FaunaSilvestre`, a partir del tipo de animal registrado.



\*\*Justificación:\*\* facilita la incorporación de nuevos tipos de animales y reduce el acoplamiento entre el proceso de registro y las clases concretas.



\## 3.4 Modelo-Vista-Controlador (MVC)



\*\*Propósito:\*\* separar la interfaz de usuario, la lógica de control y la gestión de los datos.



\*\*Aplicación:\*\*

\- \*\*Modelo:\*\* representa las entidades y reglas del sistema, como los expedientes y las solicitudes de adopción.

\- \*\*Vista:\*\* presenta formularios, listados y detalles de los casos.

\- \*\*Controlador:\*\* recibe las acciones del usuario y coordina las operaciones necesarias.



\*\*Justificación:\*\* permite organizar el código, facilita las pruebas y simplifica el mantenimiento de la aplicación.



\## 3.5 Relación entre los patrones



Los patrones trabajarán de forma complementaria. Factory Method facilitará la creación de expedientes; Singleton centralizará la gestión de casos; Observer comunicará los cambios relevantes; y MVC organizará la interacción entre la interfaz, la lógica y los datos.



La aplicación de estos patrones corresponde al diseño propuesto. Su implementación completa deberá verificarse durante la etapa de desarrollo del software.

