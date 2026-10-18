\# 2. Análisis del problema



\## 2.1 Descripción del problema



Los procesos de rescate y adopción animal pueden presentar dificultades cuando la información se registra de manera dispersa o manual. Esto puede provocar duplicación de reportes, falta de seguimiento de los casos, problemas para coordinar voluntarios y poca organización de la información veterinaria y de las solicitudes de adopción.



Para solucionar estas dificultades, se propone un sistema informático centralizado que permita registrar los reportes, gestionar los rescates, controlar los estados de los casos y facilitar la coordinación entre ciudadanos, voluntarios, veterinarios y administradores.



\## 2.2 Actores del sistema



\- \*\*Ciudadano o reportante:\*\* registra reportes de animales que necesitan ayuda y consulta el seguimiento de sus casos.

\- \*\*Voluntario:\*\* recibe asignaciones y participa en las actividades de rescate y seguimiento.

\- \*\*Veterinario:\*\* registra diagnósticos, tratamientos y atenciones médicas.

\- \*\*Administrador:\*\* supervisa los casos, administra usuarios y coordina las actividades del sistema.

\- \*\*Adoptante:\*\* consulta los animales disponibles y presenta solicitudes de adopción.



\## 2.3 Requisitos funcionales



\- \*\*RF01.\*\* El sistema permitirá registrar reportes de animales en situación de abandono, peligro o maltrato.

\- \*\*RF02.\*\* El sistema permitirá almacenar los datos básicos del animal y la ubicación del reporte.

\- \*\*RF03.\*\* El sistema permitirá consultar el estado de cada caso.

\- \*\*RF04.\*\* El administrador podrá asignar voluntarios a los casos registrados.

\- \*\*RF05.\*\* El sistema permitirá registrar el rescate y las actividades realizadas.

\- \*\*RF06.\*\* El veterinario podrá registrar diagnósticos, tratamientos y atenciones médicas.

\- \*\*RF07.\*\* El sistema permitirá actualizar el estado del animal durante el proceso de atención.

\- \*\*RF08.\*\* El sistema permitirá registrar animales disponibles para adopción.

\- \*\*RF09.\*\* Los interesados podrán presentar solicitudes de adopción.

\- \*\*RF10.\*\* El administrador podrá revisar y actualizar el estado de las solicitudes de adopción.

\- \*\*RF11.\*\* El sistema notificará a los usuarios correspondientes cuando existan cambios relevantes en un caso.

\- \*\*RF12.\*\* El sistema permitirá consultar el historial de acciones y atenciones de cada animal.



\## 2.4 Requisitos no funcionales



\- \*\*RNF01. Seguridad:\*\* el acceso a las funciones estará controlado según el rol del usuario.

\- \*\*RNF02. Usabilidad:\*\* la interfaz deberá ser clara y fácil de utilizar.

\- \*\*RNF03. Rendimiento:\*\* las consultas habituales deberán responder en un tiempo razonable.

\- \*\*RNF04. Disponibilidad:\*\* la información deberá estar accesible cuando el sistema esté operativo.

\- \*\*RNF05. Integridad:\*\* los datos de los casos y las solicitudes deberán mantenerse consistentes.

\- \*\*RNF06. Mantenibilidad:\*\* el diseño deberá facilitar futuras modificaciones y ampliaciones.

\- \*\*RNF07. Trazabilidad:\*\* las acciones relevantes deberán quedar registradas para facilitar el seguimiento.



\## 2.5 Estados de un caso



Los casos podrán pasar por los siguientes estados:



1\. \*\*Reportado:\*\* se ha registrado un reporte y está pendiente de revisión.

2\. \*\*Rescatado:\*\* el animal ha sido localizado y puesto bajo atención.

3\. \*\*En tratamiento:\*\* el animal recibe evaluación o atención veterinaria.

4\. \*\*Disponible para adopción:\*\* el animal cumple las condiciones establecidas para iniciar el proceso de adopción.

5\. \*\*Adoptado:\*\* se ha completado el proceso de adopción.

6\. \*\*Cerrado:\*\* el caso se ha finalizado administrativamente.



Las transiciones entre estados deberán ser coherentes con las actividades realizadas y las condiciones del caso.

