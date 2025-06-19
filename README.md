# 🖨️ Sistema de Registro e Impresión en PHP

Este proyecto fue desarrollado con el objetivo de registrar impresiones en base de datos antes de ejecutar el proceso de impresión, asegurando trazabilidad y confirmación del estado de cada impresión realizada.

# 📌 Descripción

El flujo del sistema es el siguiente:

Se registra en una base de datos un nuevo intento de impresión, incluyendo el nombre del archivo y marcándolo como Pendiente.

Se obtiene el ID de ese registro.

Se solicita toda la información al sistema para imprimir el ticket.

Se genera un archivo temporal con los datos del ID y el contenido original.

Se envía a impresión dicho archivo.

Se actualiza el estado en la base de datos como Impreso o Error, dependiendo del resultado.

Este proceso garantiza que toda impresión esté trazada y validada.

# ⚙️ Tecnologías utilizadas

PHP

MySQL (PDO)

Shell (lp / print) para ejecutar comandos del sistema

Servidor web Apache

# 🔒 Información sensible

Este repositorio no contiene datos privados, archivos de producción, ni credenciales.
El proyecto fue desarrollado para uso interno y privado.

# 📫 Contacto

Para más información técnica o detalles de implementación, puedes comunicarte directamente conmigo.

---

# 🧑‍💻 Montaje




