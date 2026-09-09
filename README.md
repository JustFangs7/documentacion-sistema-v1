# Sistema de Gestión de Inventario - TechStore

## 1. Descripción del Proyecto
El **Sistema de Gestión de Inventario** permite automatizar el registro de productos, control de stock y facturación para *TechStore*. Ofrece una administración centralizada y eficiente de las operaciones comerciales de la empresa.

## 2. Requisitos del Sistema
- [x] Python 3.10 o superior instalado
- [x] Base de Datos MySQL configurada
- [ ] Documentación técnica completada

## 3. Módulos del Sistema

| Módulo | Descripción | Estado |
| :--- | :--- | :---: |
| Autenticación | Control de acceso y roles de usuario | Completado |
| Inventario | Registro y conteo de productos | En Proceso |
| Facturación | Generación de comprobantes de pago | Pendiente |

## 4. Código del Sistema
```python
def calcular_total(precio, cantidad):
    return precio * cantidad

print("Sistema TechStore iniciado con éxito")