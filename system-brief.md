# System Brief – UniPay

## Visión

Desarrollar una plataforma web que permita gestionar los pagos de colegiatura de forma segura, automatizada y trazable.

## Problema

Las universidades presentan errores administrativos debido a procesos manuales de registro de pagos.

## Stakeholders

- Estudiantes
- Administración
- Departamento financiero
- Soporte técnico

## Scope

- Registro de estudiantes
- Consulta de saldo
- Pago mensual
- Actualización automática
- Historial de pagos

## No-Scope

- Integración bancaria real
- Facturación electrónica
- Gestión académica

## Diagrama de Contexto

```mermaid
flowchart LR
    Estudiante -->|Realiza pago| UniPay
    Administracion -->|Gestiona registros| UniPay
    UniPay -->|Actualiza saldo| BaseDeDatos
