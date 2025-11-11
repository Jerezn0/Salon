#Salon Appointment Scheduler

Un proyecto del curso **Relational Database** de [freeCodeCamp](https://www.freecodecamp.org/).  
Este script en **Bash** junto con una base de datos **PostgreSQL** permite gestionar citas de un salón de belleza o barbería.

---

## 🧠 Descripción

El sistema permite:
- Mostrar los servicios disponibles.
- Registrar clientes nuevos con su número de teléfono.
- Guardar las citas agendadas en la base de datos.
- Evitar duplicados de clientes mediante el teléfono.

Todo desde un simple script de terminal. 💻

---

## 🗃️ Estructura de la base de datos

**Tablas principales:**
- `customers`: almacena clientes (`customer_id`, `phone`, `name`).
- `services`: almacena los servicios ofrecidos (`service_id`, `name`).
- `appointments`: registra las citas (`appointment_id`, `customer_id`, `service_id`, `time`).

---

## ⚙️ Archivos del proyecto

| Archivo | Descripción |
|----------|--------------|
| `salon.sh` | Script principal en Bash que gestiona las citas |
| `salon.sql` | Script SQL con la creación y datos de la base de datos |

---
