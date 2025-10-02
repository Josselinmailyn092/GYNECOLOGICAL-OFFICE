## **2. Alcance del Sistema**

**Funcionalidades incluidas:**

- Gestión de pacientes y doctores.
- Agenda de citas médicas (paciente y secretaria).
- GESTIÓN DE DISPONIBILIDAD DEL DOCTOR ALAGENDAR UNA CITA MÉDICA JUNTO A SUS HORARIOS DE TRABAJO
- Control de embarazos y registro de partos.
- Emisión y envío de recetas electrónicas.
- CONTROL DE HORARIO DE TRABJO DE SERETARIA Y DOCTORES PARA AGENDAR CITAS MEDICAS
- Acceso y funcionalidades diferenciadas según rol: paciente, doctor, secretaria y admin.
- Primer MVP: login, agendar y ver citas, registro básico de pacientes y doctores.

**Exclusiones para MVP:**

- IA avanzada de predicción de resultados clínicos.
- Reportes estadísticos completos.
- Integración con laboratorios externos.

---

## **3. Roles y Permisos**

| Rol | Funcionalidades principales |
| --- | --- |
| Paciente | Registrarse, iniciar sesión, agendar/ver/cancelar citas, recibir recordatorios, ver historial básico |
| Doctor | Iniciar sesión, consultar pacientes asignados, emitir recetas, actualizar seguimiento de embarazos, consultar historial de pacientes  |
| Secretaria | Registrar pacientes y doctores, agendar citas, enviar recetas electrónicas de los doctores, modificar horarios laborales  |
| Admin | Gestionar usuarios, doctores, secretarias, permisos y configuraciones del sistema, GESTION DE HORARIO DE TRABAJO O DISPONIBILIDAD DEL DOCTORES Y SECRETARIAS  |

---

## **4. Requisitos Funcionales**

- **Paciente:**
- Registrarse y hacer login seguro.
- Agendar, ver y cancelar citas.
- Recibir recordatorios automáticos de citas.
  
- **Doctor:**
  
- Iniciar sesión.
- Consultar pacientes asignados y su historial médico.
- Emitir recetas electrónicas y actualizar control de embarazo.
  
- **Secretaria:**
  
- Registrar pacientes y doctores.
- Agendar citas por pacientes o de forma interna.
- Enviar recetas digitales emitidas por doctores.
  
- **Admin:**
  
- Crear, editar o eliminar usuarios y roles.
- Configurar permisos y módulos del sistema.
- Configurr horario disponible de doctores y secretaria

---

## **5. Requisitos No Funcionales**

- **Seguridad:**
  
- Login seguro con cifrado de contraseñas.
- Protección de datos médicos según normativas locales.
  
- **Escalabilidad:**
  
- Capacidad de manejar múltiples pacientes y doctores simultáneamente.
- Tiempo máximo de respuesta <2s para consultas críticas.
  
- **Usabilidad:**
  
- Interfaz responsive, intuitiva y accesible.
- Fluida para usuarios con poca experiencia tecnológica.

- **Disponibilidad:**
  
- Uptime esperado del 99% en servidores principales.