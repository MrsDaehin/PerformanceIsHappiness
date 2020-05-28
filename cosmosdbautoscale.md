# ¡¡¡AutoScale para CosmosDB!!!

Una de las cosas que nos preocupa cuando estamos en cloud es aquellos procesos que usan nuestro performance budget.

Procesos puntuales que hacen que nuestras Bases de Datos se pongan al 100% durante unas horas y esten al 0% el resto del tiempo. 

Necesitabamos el llamado Autopilot de la CosmosDB ahora llamado Autoscale y lo estábamos esperando como agua de mayo :)

# Primer día

En cuanto vi la noticia empecé a pedir un tiempo de pruebas para esta nueva funcionalidad que necesitaba para optimizar nuestros procesos de carga. Pero el primer día me encontré problemas para poder seguir el proceso correctamente. 

Al final acabé abriendo un caso a support de azure y aún está ahí. Pero con un pequeño workaround creando un contenedor en modo manual y luego cambiándolo a AutoScale todo funcionaba correctamente. 

