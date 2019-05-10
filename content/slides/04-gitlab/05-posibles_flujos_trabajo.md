### Git Flow Workflow

* Se utilizan dos ramas:
  * Master: Código listo para desplegar en producción
  * Develop: Código en desarrollo.

![centralized](/media/git_flow_1.png)

Notes:
* El código que se fusiona/mezcla con la rama master se suele desplegar con herramientas CI/CD, ejemplo: Jenkins.
* Se hace uso de ramas temporales que utilizan como base la rama de desarrollo.