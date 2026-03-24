# sitio-sistemas-distribuidos
Sitio web sobre Sistemas Distribuidos - Actividad Practica
# Reflexiones sobre el Desarrollo Web en la Nube

---

### 1. ¿Qué ventajas encuentras en trabajar directamente en la nube con GitHub?
* **Disponibilidad inmediata:** Puedes programar desde cualquier dispositivo con navegador (tablet, otra PC o móvil) sin instalar dependencias.
* **Colaboración en tiempo real:** El control de versiones es nativo; los cambios se sincronizan al instante, facilitando que otros revisen el código mediante *Pull Requests*.
* **Integración Continua (CI/CD):** Permite desplegar automáticamente el sitio (vía GitHub Pages) al hacer `push`, eliminando la subida manual de archivos.

---

### 2. ¿Qué desafíos tuviste al crear el sitio sin usar herramientas locales?
* **Dependencia de la conexión:** Sin internet, el flujo de trabajo se detiene; no hay previsualización ni edición posible.
* **Latencia en la previsualización:** El *Live Preview* en la nube puede tener retrasos comparado con un servidor local (`localhost`), dificultando ajustes finos de CSS.
* **Limitaciones de herramientas:** Algunos editores web carecen de atajos de teclado complejos o extensiones avanzadas presentes en un IDE local como VS Code.

---

### 3. ¿Cómo podrías mejorar este sitio web en el futuro?
* **Interactividad con JavaScript:** Añadir validaciones dinámicas al formulario o un conmutador de **Modo Oscuro**.
* **Optimización de Rendimiento:** Implementar *Lazy Loading* para imágenes y minificar el CSS para cargas instantáneas.
* **Diseño Adaptativo Extremo:** Usar *Media Queries* avanzadas para asegurar una experiencia perfecta en cualquier resolución.
* **Frameworks Modernos:** Migrar a **Tailwind CSS** para gestionar estilos vibrantes de forma más escalable.

---

### 4. ¿Qué aprendiste sobre Sistemas Distribuidos al crear este sitio?
* **Arquitectura Cliente-Servidor:** La comprensión de que el navegador (cliente) solicita recursos alojados en servidores remotos (GitHub) donde la renderización final ocurre en el extremo del usuario.
* **Consistencia y Sincronización:** Cómo Git gestiona la integridad de los datos entre múltiples nodos y resuelve conflictos para mantener una "fuente única de verdad".
* **Latencia y Redes:** La percepción de cómo la distancia física a los centros de datos afecta la velocidad de respuesta, concepto clave en sistemas geográficamente distribuidos.

### 5.  URL del sitio publicado: 
