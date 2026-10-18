\# 4. Control de versiones con Gitflow



\## 4.1 Descripción



Gitflow es una estrategia de trabajo con Git que utiliza diferentes ramas para organizar el desarrollo, la integración y las versiones estables de un proyecto.



En este proyecto se utiliza una estructura simplificada de Gitflow para separar la versión principal de la integración de los avances y de la documentación en desarrollo.



\## 4.2 Ramas utilizadas



\- \*\*main:\*\* contiene la versión principal y estable del proyecto.

\- \*\*develop:\*\* sirve para integrar los avances antes de incorporarlos a la versión principal.

\- \*\*feature/documentacion:\*\* se utiliza para desarrollar y actualizar la documentación, los requisitos y los diagramas UML.



\## 4.3 Flujo de trabajo aplicado



1\. Se creó el repositorio remoto en GitHub con el archivo README.md.

2\. Se clonó el repositorio en la computadora local mediante Git.

3\. Se creó y publicó la rama develop a partir de main.

4\. Se creó la rama feature/documentacion a partir de develop.

5\. Se añadieron archivos de documentación y diagramas UML.

6\. Se registraron los cambios mediante commits con mensajes descriptivos.

7\. Se publicaron los cambios de la rama feature/documentacion en GitHub.

8\. Se integrarán los avances en develop mediante un Pull Request después de revisar los archivos.



\## 4.4 Ejemplos de comandos utilizados



Crear la rama develop:



&#x20;   git switch -c develop



Publicar develop:



&#x20;   git push -u origin develop



Crear la rama de documentación:



&#x20;   git switch develop

&#x20;   git switch -c feature/documentacion



Preparar los cambios:



&#x20;   git add docs/



Registrar un commit:



&#x20;   git commit -m "docs: actualizar documentacion"



Publicar los cambios:



&#x20;   git push



\## 4.5 Beneficios



\- Separa los avances de la versión principal.

\- Facilita la revisión de los cambios.

\- Permite mantener un historial de commits.

\- Favorece la colaboración y el trabajo organizado.

\- Facilita la integración de nuevas funcionalidades en el futuro.



\## 4.6 Estado actual



La documentación y los diagramas UML se han desarrollado en la rama feature/documentacion y se han publicado en GitHub. La integración en develop y la posterior actualización de main se realizarán después de revisar y aprobar los cambios.

