# Sistema de Control Médico: Citas y Expedientes Clínicos

Este sistema está diseñado para organizar y digitalizar el día a día de una clínica médica u hospital. Su objetivo principal es conectar de forma fluida a los **pacientes**, los **médicos especialistas** y sus **historiales de salud** en un solo lugar.

## ¿Qué resuelve este sistema?

El diseño está estructurado para cubrir cuatro áreas críticas de cualquier centro de salud:

* **Gestión de Pacientes:** Registra los datos personales y de contacto de cada paciente de forma única y segura.
* **Expediente Clínico Base:** Cada paciente cuenta con una ficha permanente donde se guardan sus datos más importantes y estables: su tipo de sangre, alergias conocidas y enfermedades crónicas.
* **Control de Agenda y Consultorios:** Permite que un paciente solicite una cita, para luego asignarle un médico especialista, un consultorio físico, un horario específico (matutino/vespertino) y llevar el control de si la cita está pendiente, confirmada o cancelada.
* **Historial de Consultas y Diagnósticos:** Cada vez que el paciente acude a una cita, el médico registra su evolución física (peso, altura, presión arterial, cálculo de IMC) junto con el diagnóstico médico y la receta de medicamentos generada.

---

## ¿Cómo fluye la información en el negocio?

Para entender cómo funciona el sistema, imagina el recorrido natural de un paciente en la clínica:

1. **El Registro:** El paciente llega por primera vez; se guardan sus datos y se le crea un **Expediente** único con sus alergias y antecedentes.
2. **La Solicitud:** El paciente solicita una **Cita** para una fecha estimada.
3. **La Programación:** El personal de la clínica procesa la solicitud (**Agendar Cita**), le asigna un **Especialista** disponible y le aparta un consultorio.
4. **La Consulta:** El día de la cita, el médico atiende al paciente y genera un reporte detallado (**Expediente Diagnóstico**) con los síntomas, la presión, el peso actual y su receta médica. Este diagnóstico se guarda para siempre en el historial de ese paciente.

---

## Roles que interactúan con el sistema

* **Pacientes:** Los beneficiarios del servicio que solicitan atención médica.
* **Personal Administrativo / Recepción:** Encargados de organizar la agenda, confirmar estados de las citas y asignar los consultorios físicos.
* **Médicos Especialistas:** Encargados de consultar el expediente del paciente, realizar la evaluación física en el consultorio y emitir las recetas y diagnósticos.

---

## Beneficios de esta estructura

* **Seguridad:** Evita que se dupliquen números telefónicos o registros de pacientes.
* **Historial Clínico Continuo:** El médico siempre puede ver el pasado del paciente para no recetar algo que le cause alergia.
* **Cero Confusión de Horarios:** El control de agendas evita que dos médicos usen el mismo consultorio a la misma hora o que se empalmen citas de un mismo especialista.
