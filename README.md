Informe de Auditoría de Red Wi-Fi Insegura
Introducción
Este informe documenta el análisis de una conexión a un sitio web sin cifrado (HTTP), realizado para comprender los riesgos inherentes al navegar en redes Wi-Fi públicas y la importancia de utilizar tecnologías de protección como las VPN.

Sitio Analizado
URL: [http://neverssl.com](http://neverssl.com)

Evidencia Observada
A través de las herramientas de desarrollador (F12), se obtuvieron los siguientes datos técnicos de la solicitud:

Protocolo: HTTP (sin cifrado SSL/TLS).
<img width="1914" height="992" alt="image" src="https://github.com/user-attachments/assets/bafbaf24-bc67-42ca-bbaf-e08068733865" />

Método HTTP: GET.
<img width="567" height="803" alt="image" src="https://github.com/user-attachments/assets/c160911e-eb82-4a68-addc-dae25dde53a6" />


Host: soothingwonderouswholespell.neverssl.com.
<img width="572" height="773" alt="image" src="https://github.com/user-attachments/assets/b1df70c6-8299-4a70-83ea-5c8e85dcbd88" />

User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64)
<img width="567" height="798" alt="image" src="https://github.com/user-attachments/assets/4d362925-8d32-45f9-b360-8fcb45c06286" />


Riesgos Encontrados
Al navegar mediante HTTP, la comunicación ocurre en texto plano. En una red Wi-Fi pública, un atacante podría:

Interceptar tráfico (Sniffing): Capturar la información enviada, incluyendo credenciales, cookies de sesión o datos personales.

Manipulación de datos (Man-in-the-Middle): Modificar el contenido de la página que recibes o inyectar scripts maliciosos antes de que lleguen a tu navegador.

Exposición de metadatos: Información como tu sistema operativo, versión del navegador y patrones de navegación son visibles para cualquier nodo intermedio en la red.

Cómo ayuda una VPN
El uso de una Red Privada Virtual (VPN) transforma radicalmente este escenario:

Cifrado: Todos los datos que salen de tu equipo se cifran antes de abandonar el dispositivo, haciéndolos ilegibles para terceros.

Túnel Seguro: Se crea un túnel privado y cifrado entre tu equipo y un servidor VPN remoto.

Protección del tráfico: Incluso si utilizas un sitio inseguro (HTTP), el tráfico dentro del túnel está protegido, evitando que el administrador de la red Wi-Fi o atacantes puedan ver o modificar lo que envías.

Privacidad: Tu dirección IP real queda oculta, reemplazándola por la del servidor VPN.

3 Reglas de Oro
Prioriza siempre HTTPS: Evita introducir información sensible en sitios que no cuenten con un certificado SSL válido.

Utiliza una VPN en redes públicas: Considera cualquier red Wi-Fi abierta o pública como no confiable y utiliza una VPN para cifrar tu conexión.

Desactiva la conexión automática: Configura tus dispositivos para que no se conecten automáticamente a redes Wi-Fi conocidas, evitando posibles suplantaciones (Evil Twin).
