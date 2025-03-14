# 📜 Registro de Versiones

## 🚀 Versión 5.5.0 - 🗓️ *12/02/2024 (11:38)*  

📢 **¡Atención!** En el **Drive** y en **GitHub** se encuentra el archivo `crm-marcablancasaas.zip` con nuevas correcciones.  

### 🛠️ Archivos corregidos:  
- `queues.ts`: ✅ Corrección en el envío de texto + imagen en campañas.  
- `SendWhatsAppMedia.ts`: ✅ Solución para envío de audios en respuestas rápidas.  
- `wbotMessageListener.ts`: ✅ Se corrigió la duplicación en el menú.  

### 🔧 Correcciones específicas:  
- ✔️ **Envío de medios en la cola:** Ajustes en `QueueOptionController.ts`, `QueueController.ts` y `wbotMessageListener.ts`.  
- ✔️ **Corrección de error tipográfico en `Contact`:** Ajuste en `wbotMessageListener.ts` (Línea 2108).  
- ✔️ **Corrección en la asignación del departamento en el CRM:**  
  - Se eliminó la restricción basada en regex.  
  - Ahora cualquier número válido puede ser ingresado sin importar la última respuesta del bot.  

📌 **¡Actualiza siguiendo los pasos de `actualizar.sh`!**  

---

## 🚀 Versión 5.5.0 - 🗓️ *13/11/2024 (13:17)*  

### ✅ Correcciones y mejoras:  
- 🔄 **Corrección al redimensionar el área de ticket.**  
- 🛑 **Solución de errores en `toastError.js`.**  
- 📞 **Validación mejorada en números dentro del `ContactModal`.**  
- 🤖 **Actualización de OpenAI:** Versión `"openai": "3.3.0"` con mejoras en `wbotMessageListener.ts`.  
- ⭐ **Ajuste en las evaluaciones (de 1 a 5 estrellas).**  
- 📝 **Mensajes de evaluación solo cuando el ticket esté activo.**  
- 🕰️ **Implementación de horarios intercalados.**  
- 🎨 **Cambio de logo automático según modo Light/Dark.**  
- 📌 **Integración en Kanban y rediseño de interfaz.**  
- 🔊 **Corrección de audio en iPhone.**  
- 🌙 **Corrección en el chat modo Dark.**  
- 📂 **Se añadió la opción de carpetas separadas por empresa en "public".**  

---

## 🚀 Versión 5.3.5 - 🗓️ *07/11/2024*  

### ✅ Correcciones y nuevas funciones:  
- 📅 **La fecha de vencimiento ahora permanece fija en la parte superior.**  
- 🚫 **Las automatizaciones ya no se ejecutan en grupos.**  
- 🔧 **Nuevo botón `disableBot` para desactivar bots o automatizaciones.**  
- 💬 **Corrección en mensajes citados.**  
- 🔄 **Permiso para conexiones con el mismo nombre.**  
- ⏳ **Las conexiones expiran automáticamente cuando vence la empresa.**  
- 🗑️ **Nueva opción para eliminar contactos en la página de "Contactos".**  
- 🔊 **Corrección en el envío de audios OGG en respuestas rápidas.**  
- 👀 **Los tickets cerrados por un operador ya no se muestran en su panel.**  
- 📑 **Los grupos ahora solo son visibles para operadores con permisos.**  
- 💰 **Actualización automática en Finanzas tras cambiar un plan.**  

---

## 🚀 Versión 5.2.6 - 🗓️ *31/08/2024*  

### ✅ Novedades:  
- 🔒 **Cerrar todos los tickets abiertos o en espera.**  
- 😊 **Posibilidad de reaccionar a un mensaje.**  
- 📤 **Encaminamiento de mensajes a otro ticket.**  
- 🎨 **Mejoras en el diseño del menú.**  
- 🚪 **Nuevo botón "Salir" en el menú.**  
- 🔔 **Notificación cuando un mensaje es eliminado en WhatsApp.**  
- 🚀 **API actualizada.**  
- 🔑 **Nuevo diseño en la página de inicio de sesión.**  
- ✍️ **Indicadores de "Escribiendo" o "Grabando" dentro del ticket.**  

---

## 🗓️ 24/07/2024  

### ✅ Otras correcciones y mejoras:  
- 🆕 **Corrección en la visualización de VCard.**  
- 🔄 **Función para habilitar/deshabilitar nuevos registros.**  
- ⏳ **Tiempo de prueba (Trial) ahora visible en el panel.**  
- 💬 **Respuestas rápidas accesibles para todos los usuarios.**  
- ☎️ **Los contactos muestran si el número es válido y su última interacción.**  
- 📞 **Ahora se puede ver qué número está conectado al CRM.**  
- 🔄 **Botón para reiniciar conexiones.**  
- 🎨 **Cambio de logo desde el panel de administración.**  
- 🏢 **Nueva pestaña "Registrar Empresa".**  
- 📊 **Opción para planes internos.**  

---

🔄 **Mantente actualizado y sigue las instrucciones de cada versión para evitar problemas. 🚀🔥**
