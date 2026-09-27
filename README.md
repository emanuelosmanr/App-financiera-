# App Finanzas Personales 1.2

Perfiles locales independientes, contraseña y pregunta de seguridad creada por cada usuario. El asistente financiero funciona de forma local con análisis determinístico de los datos del perfil; no utiliza un modelo de lenguaje remoto ni envía datos a un servidor.

Sube todos los archivos a la raíz del repositorio y conserva `assets/icons`.

## Corrección de inicio de sesión
Se añadió una regla global para respetar el atributo `hidden`, apertura defensiva del perfil, contraseña sensible a mayúsculas y compatibilidad con perfiles creados por la versión anterior.
