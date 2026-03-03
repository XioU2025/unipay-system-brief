
---

## 📄 docs/requirements.md

```markdown
# Requirements – UniPay

## Link al Backlog
(Colocar aquí el link del tablero Trello)

---

# Historias de Usuario

## 1. Registro de estudiante – Must

Como administrador  
quiero registrar estudiantes  
para que puedan realizar pagos.

### Criterios de aceptación

Given que ingreso los datos obligatorios  
When guardo el formulario  
Then el estudiante queda registrado correctamente  

Given que el estudiante ya existe  
When intento registrarlo nuevamente  
Then el sistema muestra mensaje de error  

---

## 2. Consultar saldo – Must

Como estudiante  
quiero consultar mi saldo pendiente  
para saber cuánto debo pagar.

### Criterios de aceptación

Given que el estudiante tiene saldo pendiente  
When accede a su perfil  
Then el sistema muestra el monto actualizado  

Given que el estudiante no tiene deuda  
When consulta su saldo  
Then el sistema muestra saldo en cero  

---

## 3. Realizar pago mensual – Must
## 4. Marcar mes como pagado – Must
## 5. Historial de pagos – Should
## 6. Generar comprobante PDF – Should
## 7. Reporte financiero – Could
## 8. Bloqueo por mora – Won’t (por ahora)

---

# MVP Rationale

El MVP incluye las historias clasificadas como Must porque representan el flujo mínimo funcional del sistema: registrar estudiante, consultar saldo y realizar pagos. Sin estas funcionalidades el sistema no cumple su objetivo principal. Las historias Should y Could agregan valor pero no son críticas para la primera versión.
