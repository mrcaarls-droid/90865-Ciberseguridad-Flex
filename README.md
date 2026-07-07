# Proyecto: Bóveda y Contenedor Seguro

## Descripción
Este proyecto forma parte del Módulo 4 de Coderhouse. El objetivo es implementar un entorno de seguridad robusto combinando la gestión de identidad mediante un gestor de contraseñas y el cifrado de datos en reposo.

## Componentes de Seguridad

### 1. Gestión de Identidad (KeePassXC)
* **Herramienta:** KeePassXC
* **Protección:** Se ha configurado una **Contraseña Maestra** (frase de seguridad) junto con un **Archivo Llave (Key File)**. Esto establece un factor de autenticación doble (algo que sé + algo que tengo).

### 2. Cifrado de Datos (VeraCrypt)
* **Herramienta:** VeraCrypt
* **Configuración:** Contenedor cifrado de 100 MB utilizando algoritmos estándar AES y SHA-512.
* **Uso:** Volumen montado como unidad local para almacenamiento de archivos sensibles.

## Evidencias

### Bóveda de Credenciales
<img width="643" height="187" alt="image" src="https://github.com/user-attachments/assets/39f2ce5b-86e8-4c83-9a15-0ce2cd3d446b" />

<img width="778" height="587" alt="image" src="https://github.com/user-attachments/assets/47094638-d8c5-4c27-be42-66b17f0b582d" />


### Configuración de Seguridad (Key File)
<img width="713" height="264" alt="image" src="https://github.com/user-attachments/assets/9123614d-ad04-454b-954f-4b2ffca69e72" />


### Volumen Cifrado Montado
<img width="1294" height="721" alt="image" src="https://github.com/user-attachments/assets/6114f272-7422-447e-8073-9d9f52201f42" />
<img width="843" height="408" alt="image" src="https://github.com/user-attachments/assets/afd45e9b-c2b3-4029-a1c1-be4723ad066f" />



---
## Aprendizajes (aprendizajes.txt)
1. La importancia de la redundancia en la seguridad (Contraseña + Archivo Llave).
2. La diferencia entre cifrado en reposo (VeraCrypt) y gestión de acceso (KeePassXC).
3. Cómo la entropía (movimiento del mouse) influye en la generación de claves seguras.
