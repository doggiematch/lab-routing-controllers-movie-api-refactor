### ¿Por qué es mejor tener el controlador separado de las rutas?

El código está más ordenado, y cuando algo está organizado, es más fácil de entender.

---

### Si mañana quisieras cambiar los datos en memoria por una base de datos PostgreSQL, ¿en qué archivo harías el cambio principalmente?

Entiendo que en el archivo donde actualmente tengo los arrays, es decir, en `data/peliculas.js`.

---

### ¿Qué pasaría si en el router tuvieras `/:id` antes que `/:id/resenas`?

`/:id/resenas` es más específica que `/:id`, que es más genérica. Así que la lógica primero debería funcionar desde lo más concreto a lo más genérico.
