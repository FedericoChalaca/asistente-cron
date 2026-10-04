# asistente-cron

Disparador de respaldo de mi asistente personal. Cada 5 minutos le pide al
servidor que envíe los recordatorios vencidos. Cuando mi PC está prendido lo
hace él cada minuto; esto cubre cuando está apagado.

Es público solo para que GitHub Actions sea gratis. No contiene secretos: la
dirección y la clave están cifradas en los Secrets del repositorio.

GitHub pausa los workflows programados tras 60 días sin actividad en el repo;
si eso pasa, se reactivan desde la pestaña Actions.
