# Entrega 2 - Ciberseguridad (Coderhouse)

**Checkpoint: Mi primer laboratorio seguro de ciberseguridad**
Alumno: Sebastián Felipe Muñoz Rivera

## Contenido

- [`Reporte_Tecnico_Configuracion_Laboratorio.pdf`](Reporte_Tecnico_Configuracion_Laboratorio.pdf): reporte técnico completo, con la explicación de cada paso.
- [`evidencias/`](evidencias): capturas de pantalla usadas en el reporte.

## Resumen

| Punto | Qué se hizo | Evidencia |
|---|---|---|
| 1. VirtualBox y red aislada | VM *Lab-Ubuntu-Seguro* (Ubuntu 24.04.5 LTS, 4 GB RAM, 2 CPU) con la red en **NAT**, configurada antes del primer arranque | `01_red_nat.png`, `02_vm_resumen_apagada.png` |
| 2. Capa Windows | Usuario **Estándar** separado de la cuenta Administrador y Windows Update al día | `09a_windows_cuentas.png`, `09b_windows_tipo_cuenta.png`, `11_windows_update.png`, `10_windows_rdp.png` |
| 3. Capa Linux | `sudo apt update` / `upgrade` con el sistema actualizado, usuario sin privilegios `practicas` y permisos revisados con `ls -l` | `03` a `07` |
| 4. Snapshot | Instantáneas **"Hardening Inicial"** y **"Clean Install - Hardening applied"** con la VM apagada | `08_snapshots.png` |

## Entorno

- Host: Windows 11 Home
- Hipervisor: Oracle VirtualBox 7.2.20
- Invitado: Ubuntu Desktop 24.04.5 LTS (ISO oficial, verificada con SHA-256)
