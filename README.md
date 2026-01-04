# Clonación de Discos con Clonezilla

![Portada del proyecto](cover.png)

## Descripción
Implementación de clonación de discos en entornos Linux usando Clonezilla. Incluye dos escenarios:
- Clonación local a USB (sin encriptación, modo automático).
- Clonación por red con DHCP multicast para despliegue masivo en múltiples equipos.

Objetivo: Explorar técnicas de backup y recuperación eficientes para administración de sistemas.

## Tecnologías utilizadas
- Clonezilla Live
- VirtualBox (para pruebas)
- Redes DHCP
- Linux

## Escenarios implementados
### Clonación a USB
- Configuración de dispositivo destino
- Selección automática de ruta
- Modo principiante con apagado automático

### Clonación por red (multicast)
- Servidor lite-server en máquina master
- Detección automática de clientes vía DHCP
- Clonación simultánea de múltiples equipos

## Relevancia profesional
- **Cloud Computing**: Similar a creación de imágenes AMI en AWS o snapshots de discos en Azure para provisioning rápido.
- **Ciberseguridad**: Generación de imágenes forenses limpias o despliegue masivo de sistemas endurecidos (hardening).

## Recursos
- Capturas del proceso en `/screenshots/`
- Guías detalladas en archivos Markdown

¡Gracias por visitar el repositorio! ⭐
