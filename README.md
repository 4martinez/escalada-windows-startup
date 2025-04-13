# escalada-windows-startup

# 🧬 Escalada de Privilegios en Windows – Payload via Startup Folder

**Autor:** Álvaro Martínez Cutillas  
**Fecha:** Abril 2025  
**Entorno:** Laboratorio simulado – Kali Linux + Windows 10

---

## 🎯 Objetivo

Ejecutar una escalada de privilegios en una máquina Windows usando el método “Startup Others”, partiendo de un acceso de usuario limitado.

---

## ⚙️ Herramientas utilizadas

- **Kali Linux** – Sistema atacante
- **Windows 10** – Máquina víctima
- **Metasploit (msfvenom, handler)** – Generación y escucha de payload
- **Python3 HTTP server** – Transferencia del payload
- **xfreerdp** – Conexión remota RDP
- **certutil** – Descarga del ejecutable en Windows

---

Este proyecto fue realizado como parte de un proceso formativo. La máquina analizada es de acceso público y el contenido aquí compartido es de elaboración propia, con fines educativos y demostrativos.
