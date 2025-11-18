```markdown
# BOM (Bill of Materials) - Variador SCADA/HMI (ESP32)

Esta tabla es orientativa. Ajusta las referencias y precios según tu proveedor/localidad.

| Ítem | Cantidad | Part Number / Ejemplo | Descripción | Precio aprox (USD) | Notas |
|---|---:|---|---|---:|---|
| ESP32 DevKit v1 | 1 | ESP32-WROOM-32 DevKit | Controlador principal | 5–10 | Modelo común, 4MB flash |
| Driver para motor / VFD | 1 | Depende del motor | Driver para controlar potencia | 20–120 | Seleccionar según motor (corriente y voltaje) |
| Fuente de alimentación DC | 1 | 24V 5A SMPS | Alimentación para driver | 10–30 | Si motor requiere más, aumentar A |
| Convertidor 5V DC-DC | 1 | Buck 24V→5V | Alimentación lógica para ESP32 | 3–8 | Si la fuente principal no tiene salida 5V |
| Display / HMI | 1 | TFT 3.5" (opcional) | Interfaz local | 8–25 | Alternativa: usar Web UI en navegador |
| Relés / Contactores | según necesidad | Ej.: SSR/relay | Control de potencia / seguridad | variable | Usar según aplicación |
| Cables y conectores | varios | - | Cableado y bornes | variable | - |
| Caja / Montaje | 1 | - | Caja protectora | variable | - |

Notas:
- Actualiza marcas y referencias con tus proveedores.
- Indica corriente nominal del motor para dimensionar el driver y la fuente.
```