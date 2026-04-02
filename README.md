# Sistema Híbrido de Control de Accesos
## Barrio Privado San José III-IV

Repositorio de documentación funcional, académica y comercial del proyecto de control de accesos para el Barrio Privado San José III-IV.

## Objetivo del proyecto
Diseñar e implementar una solución robusta para digitalizar el control de ingresos y egresos en garita, reemplazando el registro manual en papel por un sistema con trazabilidad operativa, mejor seguridad y mayor velocidad de acceso.

## Enfoque funcional
La solución se plantea en dos etapas.

### Fase 1
- Núcleo robusto de acceso con TelePASE para propietarios
- Registro centralizado de eventos de entrada y salida
- Gestión de roles y auditoría de acciones

### Fase 2 opcional
- Evolución del canal QR para visitas y excepciones
- Variante económica asistida por garita
- Variante robusta con lectura automática en campo
- Presupuesto y ejecución independientes de la Fase 1

## Estado actual del repositorio
Este repositorio está orientado a documentación y propuesta.
Por ahora no incluye código fuente productivo del sistema.

## Contenido
### 1. Entrega académica inicial
- Ruta: `Actividad1/Seminario Integrador 2026- Grupo xx- Actividad 1.pdf`
- Incluye relevamiento del caso real, entrevista preliminar, alcance funcional y lineamientos de diseño inicial.

### 2. Propuesta técnico-comercial para cliente
- Ruta: `PDFPropuestaCliente/Propuesta_Tecnico_Comercial_B2B_San_Jose_III_IV.pdf`
- Incluye alcance comercial, arquitectura funcional, robustez esperada, escenarios de inversión y plan de implementación por etapas.

## Alcance del equipo de software
Incluido:
- Diseño funcional del sistema
- Desarrollo de backend, frontend y lógica de validación
- Auditoría y trazabilidad de eventos
- Operación por roles de administración, garita y propietario

No incluido:
- Montaje físico de hardware en campo
- Cableado y adecuación electromecánica
- Instalación de sensores de seguridad de barrera como fotocélulas o equivalentes de cruce

## Requisitos de infraestructura para operación completa
Para una operación totalmente automática, la barrera debe proveer señal digital de cruce vehicular al sistema.
Si esa señal no está disponible, el flujo puede operar en modo asistido por garita, manteniendo la trazabilidad.

## Beneficio esperado para el barrio
- Reducción de tiempos de ingreso en picos de tránsito
- Menor carga manual del personal de guardia
- Mayor control de visitantes y contratistas
- Historial confiable para auditoría y seguimiento de incidentes
- Base escalable para más de diez años de evolución

## Uso de este repositorio
1. Revisar la entrega académica para contexto y criterios de diseño.
2. Revisar la propuesta técnico-comercial para presupuesto, alcance y estrategia de implementación.
3. Usar ambos documentos como base para la definición final con la comisión del barrio.

## Nota
Los costos de hardware e instalación dependen de cotizaciones vigentes y validación en campo.
Siempre deben reconfirmarse antes de la decisión de compra.
