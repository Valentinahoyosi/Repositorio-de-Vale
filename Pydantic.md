#  ¿Qué es Pydantic?

Pydantic es una librería de Python que permite **validar y gestionar datos** de manera sencilla utilizando las **anotaciones de tipo** (type hints) del lenguaje.  
Su objetivo principal es asegurar que los datos que entran en tu aplicación tengan el formato y los tipos correctos, simplificando la validación y reduciendo errores.

Se utiliza ampliamente en proyectos modernos, especialmente junto con **FastAPI**, para la construcción de **APIs rápidas y seguras**.

---

##  Ventajas de Pydantic
- **Validación automática de datos** → Si un valor no cumple con el tipo esperado, Pydantic genera un error.  
- **Conversión de tipos** → Intenta convertir datos al tipo definido (ejemplo: `"25"` → `int`).  
- **Simplicidad y rapidez** → Modelos fáciles de crear y mantener.  
- **Integración con FastAPI** → Documentación automática con OpenAPI/Swagger.  
- **Mejora la confiabilidad** → Reduce errores al trabajar con datos externos (formularios, JSON, bases de datos).  

---

##  Características principales
- Uso de **clases y anotaciones de tipo** para definir modelos.  
- **Manejo de errores estructurado** mediante `ValidationError`.  
- Posibilidad de crear **validaciones personalizadas** con `@validator`.  
- Definición de **restricciones** con `Field` (ejemplo: valores mínimos, máximos, longitud, regex).  
- **Conversión automática** de tipos de datos.  
- Compatible con **entornos asincrónicos (async/await)**.  

