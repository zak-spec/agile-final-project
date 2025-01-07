---
name: Historia de Usuario
about: Una Historia de Usuario es una herramienta en metodologías ágiles que describe
  una funcionalidad desde la perspectiva del usuario final, enfocándose en el valor
  que aporta.
title: ''
labels: ''
assignees: ''

---

Como: Administrador del sistema.
Necesito: La capacidad de crear un nuevo producto en el catálogo.
Para que: Pueda mantener el inventario actualizado y agregar productos para los usuarios.

Criterios de Aceptación
Dado: Que soy un administrador autenticado en el sistema.

Cuando: Accedo al formulario de creación de productos y completo los campos requeridos.

Entonces: El sistema debe guardar el producto en la base de datos y mostrarlo en el catálogo.

Dado: Que no he completado todos los campos obligatorios.

Cuando: Intento guardar el producto.

Entonces: El sistema debe mostrar un mensaje de error indicando los campos faltantes.
