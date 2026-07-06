# Laboratorio de Seguridad 01

## Configuración de Red
<img width="824" height="516" alt="nat" src="https://github.com/user-attachments/assets/a541f650-96a5-41c3-b0a1-5aa37bea92d4" />

**Justificación Técnica:**
•	Configuración: Se ha configurado el adaptador de red de la máquina virtual en modo NAT (Network Address Translation).
•	Justificación de Seguridad: El modo NAT actúa como un firewall de facto entre la máquina virtual y la red local (LAN). Permite que la VM acceda a internet para descargar actualizaciones y paquetes de herramientas (usando la conexión del Host), pero impide que dispositivos externos en la misma red física vean o inicien conexiones directamente hacia nuestra máquina virtual. Esto aísla el entorno de pruebas, protegiendo al equipo Host de posibles amenazas o escaneos que puedan originarse dentro del sistema virtualizado.

## Snapshot Inicial
<img width="1788" height="1024" alt="image" src="https://github.com/user-attachments/assets/bfb81c0e-428e-482d-a2df-c42f68657f26" />
