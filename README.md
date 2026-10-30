# Jornada Técnica Profesional: Mapei & Bariperfil Málaga

Landing page interactiva de convocatoria y confirmación para la **Jornada Técnica sobre Preparación de Soportes**, organizada conjuntamente por **MAPEI** y **Bariperfil Málaga**.

---

## 📌 Datos Clave del Evento

* **Fecha y Hora:** **Miércoles, 4 de Noviembre** a las **09:00 h**.
* **Ubicación:** Instalaciones de **Bariperfil Málaga**  
  *Av. de José Ortega y Gasset, 288, Cruz de Humilladero, 29006 Málaga*.  
  [Ver en Google Maps](https://www.google.com/maps/search/?api=1&query=Bariperfil+M%C3%A1laga+Av.+de+Jos%C3%A9+Ortega+y+Gasset+288+29006+M%C3%A1laga)
* **Formato:** Jornada presencial teórico-práctica para instaladores y profesionales del pavimento.
* **Coste:** Gratuito con plazas limitadas.

---

## 🧭 Estructura y Flujo de Respuesta (3 Opciones)

La página mantiene la cabecera co-branding (**MAPEI × Bariperfil**), la barra de datos clave con cuenta atrás automática hasta el **4 de noviembre a las 09:00 h**, un bloque central interactivo con **3 opciones de respuesta**, y las tarjetas de contacto en el pie de página.

### 1. «Sí, asistiré»
* Pregunta al asistente si desea confirmar sus datos para reservar plaza nominal:
  * **«Sí, confirmar mis datos»:** Abre el formulario (Nombre/Empresa y Teléfono/Email). Al rellenar ambos campos se activan dinámicamente los botones **Confirmar por Email** (`malaga@bariperfil.es`) y **Confirmar por WhatsApp** (`678 054 733`).
  * **«No hace falta, solo avisar de que iré»:** Registra la asistencia de forma anónima y muestra la pantalla de cierre y agradecimiento.

### 2. «Me interesa, pero no puedo ese día»
* Agradece el interés y ofrece avisar en una próxima convocatoria.
* Incluye **casillas de selección múltiple (checkboxes)** con los temas de especial interés:
  * *Preparación de soportes*
  * *Humedad*
  * *Adhesivos*
  * *Autonivelantes*
  * *Acabados para el parquet*
* Al completar **Nombre/Empresa** y **Teléfono/Email**, se muestran las dos vías de envío (**Email** a `malaga@bariperfil.es` y **WhatsApp** a Millán Álvarez `678 054 733`), incluyendo automáticamente en el borrador los temas marcados.

### 3. «No podré asistir»
* Registra el clic en estadísticas y muestra un mensaje directo de agradecimiento por responder.

---

## 👥 Equipo y Contactos (Pie de Página)

1. **Millán Álvarez** — *Delegado Comercial · BARIPERFIL*  
   * Teléfono Móvil / WhatsApp: `678 054 733`  
   * Teléfono Almacén: `952 00 97 43`
2. **David Pérez** — *Product Specialist · MAPEI*  
   * Teléfono: `670 275 741`  
   * Email: `davidperez@mapei.es`
3. **J. Antonio Sánchez** — *Agente Comercial · MAPEI*  
   * Teléfono: `637 814 079`  
   * Email: `jasanchez@mapei.es`

* **Correo receptor de inscripciones y nuevas convocatorias:** `malaga@bariperfil.es`

---

## 📊 Estadísticas con GoatCounter (`/estadisticas.html`)

La web utiliza **GoatCounter** (`https://gemayrafa.goatcounter.com`) para registrar visitas y eventos de forma 100% anónima y conforme al RGPD.

* **Panel oficial de GoatCounter:** [https://gemayrafa.goatcounter.com](https://gemayrafa.goatcounter.com)
* **Resumen privado en la web:** `estadisticas.html` (Clave de acceso: **`4662`**)
  * Incluye un botón directo para **Abrir el panel completo de GoatCounter** y un resumen automático de las respuestas y temas de interés.
  * **Requisito en GoatCounter para ver los contadores dentro de `estadisticas.html`:** En tu cuenta de GoatCounter, entra en **Settings → Main** y marca la casilla **"Allow adding visitor counts on your website"**, luego pulsa **Save**.

### Eventos registrados en GoatCounter

| Código de evento en GoatCounter | Qué mide |
| :--- | :--- |
| `/` | Visitas a la página principal |
| `respuesta-asistire` | Clic en opción 1: «Sí, asistiré» |
| `respuesta-interesa` | Clic en opción 2: «Me interesa, pero no puedo ese día» |
| `respuesta-no-asistire` | Clic en opción 3: «No podré asistir» |
| `asistire-datos-si` | Asistentes que eligen dejar sus datos |
| `asistire-datos-no` | Asistentes que eligen «No hace falta, solo avisar de que iré» |
| `inscripcion-email` | Confirmación de asistencia enviada por Email |
| `inscripcion-whatsapp` | Confirmación de asistencia enviada por WhatsApp |
| `interes-email` | Solicitud de próxima convocatoria enviada por Email |
| `interes-whatsapp` | Solicitud de próxima convocatoria enviada por WhatsApp |
| `interes-tema-soportes` | Interés marcado en: *Preparación de soportes* |
| `interes-tema-humedad` | Interés marcado en: *Humedad* |
| `interes-tema-adhesivos` | Interés marcado en: *Adhesivos* |
| `interes-tema-autonivelantes` | Interés marcado en: *Autonivelantes* |
| `interes-tema-parquet` | Interés marcado en: *Acabados para el parquet* |
| `mapa` | Clic en cómo llegar (Google Maps) |
| `llamada` | Clic en números de teléfono del pie de página |

---

## 📂 Estructura de Archivos

```
landing-evento/
├── index.html          # Web principal con cuenta atrás, 3 opciones de respuesta y GoatCounter
├── estadisticas.html   # Panel privado (clave 4662) conectado a GoatCounter
└── README.md           # Documentación del proyecto
```
