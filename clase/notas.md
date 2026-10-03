# 🗒️ Registro de Trabajo en Clase - Taller 3

## 📆 Fecha de la sesión
4 de septiembre de 2026

## 👥 Integrantes presentes
* Jorge Steven Doncel Bejarano — Código: 282296 / [gevengood](https://github.com/gevengood) / [jorgedobe@unisabana.edu.co](mailto:jorgedobe@unisabana.edu.co)
* David Santiago Buendia Londoño — Código: 306487 / [Santiagoob7](https://github.com/Santiagoob7) / [davidbulo@unisabana.edu.co](mailto:davidbulo@unisabana.edu.co)

## 🧠 Actividades realizadas en clase
* **Revisión del caso base RedExpress:** Se analizó la jerarquía del modelo C4, aplicando las vistas de Contexto (C1) y Contenedores (C2) sobre la plataforma de mensajería y logística RedExpress, comprendiendo la separación de actores externos, sistema en alcance, contenedores de aplicación e infraestructura de soporte (Balanceador Nginx y BD PostgreSQL).
* **Decisiones de modelado para el caso real:** Dado que Insuclínicos Ltda. no cuenta con un backend formal web tradicional ni microservicios, se tomó la decisión arquitectónica de representar sus archivos de MS Excel como "Contenedores" lógicos de datos en la vista C2. Esto permite mapear con precisión las interacciones manuales ("Lectura cruzada y actualización manual") como el cuello de botella central del flujo operativo.
* **Herramientas usadas:** draw.io con la librería oficial de formas C4.
* **Avance en clase:** Se estructuraron los modelos borrador del caso base RedExpress (`c1-contexto-borrador.drawio` y `c2-contenedores-borrador.drawio`) y se definió la frontera del sistema para Insuclínicos Ltda.

## 🧩 Bocetos iniciales del caso base (RedExpress)
Los archivos borrador desarrollados durante la sesión de clase se encuentran disponibles en esta misma carpeta:
* [Borrador Vista de Contexto C1 — RedExpress](c1-contexto-borrador.drawio)
* [Borrador Vista de Contenedores C2 — RedExpress](c2-contenedores-borrador.drawio)

## 🔁 Tareas definidas para la entrega del cliente (Insuclínicos Ltda.)

| Tarea asignada | Responsable | Fecha estimada |
| :--- | :--- | :--- |
| Modelado final en draw.io de Vistas C1 y C2 de Insuclínicos | Jorge Steven Doncel | 05/09/2026 |
| Redacción del informe técnico (`entrega/informe.md`) | David Santiago Buendia | 06/09/2026 |
| Validación de trazabilidad C1 vs C2 y verificación de enlaces | David Santiago Buendia | 06/09/2026 |
| Consolidación de referencias bibliográficas (`entrega/referencias.md`) | Jorge Steven Doncel | 06/09/2026 |
