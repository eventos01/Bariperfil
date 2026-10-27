# Jornada Técnica Profesional: Mapei & Bariperfil Málaga

Landing page y cartel interactivo de programa para la **Jornada Técnica de Diagnóstico, Reparación y Preparación de Soportes**, organizada conjuntamente por **MAPEI** y **Bariperfil Málaga**.

---

## 📌 Datos Clave del Evento

* **Fecha y Hora:** Lunes, **4 de Noviembre** a las **09:00 h**.
* **Ubicación:** Instalaciones de **Bariperfil Málaga**  
  *Av. de José Ortega y Gasset, 288, Cruz de Humilladero, 29006 Málaga*.  
  [Ver en Google Maps](https://www.google.com/maps/search/?api=1&query=Bariperfil+M%C3%A1laga+Av.+de+Jos%C3%A9+Ortega+y+Gasset+288+29006+M%C3%A1laga)
* **Formato:** Sesión presencial teórico-práctica para instaladores y profesionales del pavimento.
* **Coste:** Gratuito con plazas limitadas (sin necesidad de crear cuenta ni registros previos).

---

## 📋 Orden del Día (Programa Técnico)

1. **01. Valorar e identificar soportes:**  
   Tipologías de base: soleras de hormigón, recrecidos de mortero, soportes cerámicos y diagnosis previa de resistencia.
2. **02. Reparar patologías en soportes:**  
   Tratamiento de fisuras activas, consolidación de soleras disgregadas, regularización y morteros autonivelantes.
3. **03. Comprobar humedad y límites permitidos:**  
   Métodos de medición (carburo de calcio vs higrómetro digital). Tolerancias y porcentajes máximos admisibles según normativa.
4. **04. Uso y sistemas de barrera:**  
   Barreras de vapor epoxi/poliuretano, bloqueo de remonte capilar, imprimaciones técnicas y puentes de unión Mapei.

---

## 👥 Equipo y Contactos

1. **Millán Álvarez** — *Delegado Comercial · BARIPERFIL*  
   * Teléfono Móvil: `678 054 733`  
   * Teléfono Almacén: `952 00 97 43`
2. **David Pérez** — *Product Specialist · MAPEI*  
   * Teléfono: `670 275 741`  
   * Email: `davidperez@mapei.es`
3. **J. Antonio Sánchez** — *Agente Comercial · MAPEI*  
   * Teléfono: `637 814 079`  
   * Email: `jasanchez@mapei.es`

---

## 🚀 Flujo de Confirmación de Asistencia ("Sin Registro")

La web ofrece dos vías directas y sin fricción:

### 1. Vía Formulario (Email)
* Solicita: *Nombre / Empresa* y *Teléfono / Email*.
* Botón: **"Confirmar Asistencia por Email"**.
* Acción: Genera automáticamente un enlace `mailto:` listo para enviar al correo:
  * **Destino:** `malaga@bariperfil.es`
  * **Asunto:** *Confirmación de Asistencia - Jornada Técnica Mapei en Bariperfil (4 Nov)*
  * **Cuerpo:** Incluye automáticamente el nombre y contacto introducidos.
* Muestra en pantalla el estado de éxito con botones directos para añadir la cita a **Google Calendar** y descargar archivo **.ics** para Outlook y iPhone.

### 2. Vía WhatsApp (Dinámica)
* Separador: *"Si prefieres lo puedes hacer por whatsapp"*.
* Botón: **"Confirmar por WhatsApp"**.
* Acción: Si el usuario ya ha escrito su nombre o contacto en los campos, la función JavaScript los extrae e inserta en el mensaje de WhatsApp dirigido a Millán Álvarez (`678 054 733`):
  > *Hola, confirmo mi asistencia a la Jornada Técnica Mapei en Bariperfil Málaga el 4 de noviembre a las 9:00 h.*  
  > *• Asistente / Empresa: [Nombre]*  
  > *• Contacto: [Teléfono o email]*

---

## 🔒 Panel Privado de Estadísticas (`/estadisticas.html`)

Página oculta y protegida para medir la actividad del evento en tiempo real.

* **Ruta:** `estadisticas.html` (ej. `https://tu-usuario.github.io/tu-repo/estadisticas.html`).
* **Clave de Acceso:** **`4662`**
* **Métricas monitorizadas:**
  * **Visitas Únicas:** Filtradas por `sessionStorage` para **no computar duplicados por recarga (F5)**.
  * **Confirmaciones por WhatsApp.**
  * **Confirmaciones por Email.**
  * **Clics en ruta Google Maps.**
  * **Guardados en Calendario** (Google / Apple / Outlook).
  * **Llamadas telefónicas directas.**
  * **Tasa de conversión** estimada y canal preferido.
* **Infraestructura de datos:** Micro-API global anónima [CounterAPI](https://counterapi.dev) (Namespace: `mapei-bariperfil-malaga-2026`) combinada con almacenamiento de respaldo en `localStorage`.
* **Privacidad RGPD:** 100% Anónimo. No registra IPs, cookies de seguimiento ni datos personales.

---

## 📂 Estructura de Archivos

```
landing-evento/
├── index.html          # Web principal del evento y formulario de asistencia
├── estadisticas.html   # Panel privado de analítica con clave 4662
└── README.md           # Esta documentación técnica
```

---

## 🌐 Publicación y Actualización en GitHub Pages

1. Sube los archivos a tu repositorio público de GitHub (`index.html`, `estadisticas.html`, `README.md`).
2. En el repositorio: **Settings > Pages > Branch: `main` / Folder: `/(root)` > Save**.
3. Tu web estará operativa de inmediato en:
   * **Web del evento:** `https://<usuario>.github.io/<repositorio>/`
   * **Panel privado de estadísticas:** `https://<usuario>.github.io/<repositorio>/estadisticas.html`

---

## 💻 Instrucciones para Continuar en Otro PC con Antigravity

1. Copia la carpeta `landing-evento` a la máquina nueva (o descárgala como ZIP desde tu repositorio de GitHub).
2. En la nueva instancia de Antigravity, selecciona **"Open Folder"** y elige la carpeta `landing-evento`.
3. Antigravity leerá este archivo `README.md` y tendrá todo el contexto técnico, claves, contactos y flujos de trabajo listos para seguir programando.
