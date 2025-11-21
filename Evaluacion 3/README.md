# Archivos de Caso: Evaluación Sumativa 3

Este directorio contiene los recursos técnicos necesarios para el desarrollo de los casos prácticos de la asignatura CSY4132.

## 📦 Listado de Archivos

| Archivo | Descripción Técnica |
|:---|:---|
| **`capturatraficolan.pcapng`** | Captura de tráfico (Wireshark) para análisis de protocolos LAN y extracción de objetos HTTP. |
| **`capturaattackserver.pcapng`** | Captura de tráfico con evidencia de escaneo de puertos y denegación de servicio. |
| **`auth.log`** | Log de sistema Linux con registros de autenticación SSH (fuerza bruta y accesos). |
| **`DNS-Exfil.csv`** | Dataset en formato CSV con logs de consultas DNS anómalas (Tunneling/Exfiltration). |

## 📥 Instrucciones de Descarga

### Opción 1: Desde Terminal (Kali Linux)

Para descargar los archivos directamente a tu máquina virtual, abre una terminal y utiliza `wget`.
```bash
# 1. Descargar Captura LAN
wget "https://raw.githubusercontent.com/nicsanchezr/CSY4132-2025/main/Evaluacion%203/capturatraficolan.pcapng"

# 2. Descargar Captura Ataque Servidor
wget "https://raw.githubusercontent.com/nicsanchezr/CSY4132-2025/main/Evaluacion%203/capturaattackserver.pcapng"

# 3. Descargar Log SSH
wget "https://raw.githubusercontent.com/nicsanchezr/CSY4132-2025/main/Evaluacion%203/auth.log"

# 4. Descargar Dataset DNS
wget "https://raw.githubusercontent.com/nicsanchezr/CSY4132-2025/main/Evaluacion%203/DNS-Exfil.csv"
```

### Opción 2: Vía Web (Raw)

1. Haz clic en el nombre del archivo que deseas descargar en la lista de arriba.
2. Busca el botón "Download raw file" (icono de descarga) en la esquina superior derecha del visor de archivos.
3. Guarda el archivo en tu equipo.

---

**Nota:** Asegúrate de verificar la integridad de los archivos descargados antes de utilizarlos en tus análisis.
