# Laboratorio 2 – Dulce Hogar
 
**Universidad de Oriente – Facultad de Ingeniería y Arquitectura**
Gestión de Servidores Web – Ciclo 02-2026

Docente: Ing. Alberto Turcios Ortez
 
**Equipo N.º:** 01  |  **Sección:** A
 
## Descripción
 
Implementación de la infraestructura web para la repostería artesanal "Dulce Hogar": instalación de Apache, Virtual Host con Reverse Proxy hacia una API en el puerto 9000 y HTTPS local con mkcert en el puerto 8900. El trabajo se realizó sobre una máquina virtual Ubuntu Server accedida por SSH mediante Tailscale.
 
## Integrantes y aportes
 
| Integrante | Rol | Qué hizo |
|---|---|---|
| José Aristides Zelaya Parada | Coordinador / Git  | Encargado del repositorio: estructura, commits y consolidación de la entrega. |
| Oscar Stanley Marquez Portillo | Adm. de Servidor Base | Instaló Apache, verificó su estado, habilitó módulos y creó la estructura de directorios. |
| Kennet Jared Mejia Portillo | Adm. de Redes / Proxy  | Configuró los Virtual Hosts, ProxyPass/ProxyPassReverse y la gestión de puertos (80 y 8900). |
| Anderson Isaac Ortiz Canizález | Adm. de Certificados (SSL) | Instaló mkcert, generó los certificados y configuró el Virtual Host HTTPS. |
| Kevin Alejandro Granillo Soto | Adm. de Permisos (OS) | Aplicó menor privilegio (chown/chmod), validó el usuario www-data y configuró la confianza en la CA en Windows. |
| Diana Damary García Ambrocio | Documentador / QA | Redactó el informe,  README. |
 
## Estructura del repositorio
 
```
Laboratorio 2/
├── README.md
├── informe-final.pdf
├── fase1-dimensionamiento.txt
├── fase2-apache.txt
├── fase3-virtualhost.txt
├── fase4-https.txt
├── config/
│   ├── dulcehogar.local.conf
│   ├── dulcehogar.local-ssl.conf
│   └── ports.conf
└── capturas/
    ├── fase2-apache-activo.png
    ├── fase3-curl-exitoso.png
    └── fase4-https-sin-advertencia.jpg
```
