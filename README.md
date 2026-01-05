# Clonación y Despliegue Masivo de Sistemas con Clonezilla Live

![Portada del proyecto](cover.png)

## Descripción del Proyecto
Proyecto personal de **Administración de Sistemas** enfocado en la clonación de discos y despliegue masivo utilizando **Clonezilla Live** en entornos virtualizados con VirtualBox.

Se implementan dos escenarios reales y escalables:

1. **Clonación local**: Creación de una imagen completa de disco maestro y almacenamiento en dispositivo USB.
2. **Despliegue masivo por red**: Configuración de Clonezilla Lite Server con modo multicast para restaurar la imagen simultáneamente en múltiples clientes (simulado con 2 máquinas virtuales, fácilmente escalable).

Todo el proceso se realiza en un entorno controlado y reproducible, ideal para laboratorios, aulas o empresas.

## Tecnologías y Herramientas Utilizadas
- **Clonezilla Live** (versión estable 20241010-oracular-amd64)
- **VirtualBox** para virtualización
- Redes internas con configuración DHCP automática
- Multicast para optimización de ancho de banda
- Partclone como motor de clonación

## Objetivos Alcanzados
- Dominio completo del flujo de creación y restauración de imágenes de disco.
- Configuración avanzada de Clonezilla Lite Server para despliegues masivos.
- Optimización de red (multicast + DHCP auto-detect) para eficiencia en entornos con múltiples equipos.
- Buenas prácticas en documentación visual y reproducibilidad.

## Proceso Completo – Capturas Paso a Paso

<div style="display: grid; grid-template-columns: repeat(auto-fill, minmax(320px, 1fr)); gap: 15px; margin: 30px 0;">

  <img src="screenshots/screenshots (1).png" alt="Paso 1">
  <img src="screenshots/screenshots (2).png" alt="Paso 2">
  <img src="screenshots/screenshots (3).png" alt="Paso 3">
  <img src="screenshots/screenshots (4).png" alt="Paso 4">
  <img src="screenshots/screenshots (5).png" alt="Paso 5">
  <img src="screenshots/screenshots (6).png" alt="Paso 6">
  <img src="screenshots/screenshots (7).png" alt="Paso 7">
  <img src="screenshots/screenshots (8).png" alt="Paso 8">
  <img src="screenshots/screenshots (9).png" alt="Paso 9">
  <img src="screenshots/screenshots (10).png" alt="Paso 10">
  <img src="screenshots/screenshots (11).png" alt="Paso 11">
  <img src="screenshots/screenshots (12).png" alt="Paso 12">
  <img src="screenshots/screenshots (13).png" alt="Paso 13">
  <img src="screenshots/screenshots (14).png" alt="Paso 14">
  <img src="screenshots/screenshots (15).png" alt="Paso 15">
  <img src="screenshots/screenshots (16).png" alt="Paso 16">
  <img src="screenshots/screenshots (17).png" alt="Paso 17">
  <img src="screenshots/screenshots (18).png" alt="Paso 18">
  <img src="screenshots/screenshots (19).png" alt="Paso 19">
  <img src="screenshots/screenshots (20).png" alt="Paso 20">
  <img src="screenshots/screenshots (21).png" alt="Paso 21">
  <img src="screenshots/screenshots (22).png" alt="Paso 22">
  <img src="screenshots/screenshots (23).png" alt="Paso 23">
  <img src="screenshots/screenshots (24).png" alt="Paso 24">
  <img src="screenshots/screenshots (25).png" alt="Paso 25">
  <img src="screenshots/screenshots (26).png" alt="Paso 26">
  <img src="screenshots/screenshots (27).png" alt="Paso 27">
  <img src="screenshots/screenshots (28).png" alt="Paso 28">
  <img src="screenshots/screenshots (29).png" alt="Paso 29">
  <img src="screenshots/screenshots (30).png" alt="Paso 30">
  <img src="screenshots/screenshots (31).png" alt="Paso 31">
  <img src="screenshots/screenshots (32).png" alt="Paso 32">

</div>

> Las capturas muestran el flujo completo: desde la configuración de VirtualBox (USB, red interna, ISO), creación de la imagen (modo savedisk), hasta el servidor lite con multicast y restauración simultánea en clientes.

## Aprendizajes Clave
- **Gestión eficiente de imágenes de disco** en entornos sin sistema operativo instalado.
- **Configuración de redes para multicast** y uso óptimo del ancho de banda en despliegues masivos.
- **Automatización completa** mediante modo beginner y opciones por defecto seguras.
- **Reproducibilidad total** gracias al uso de máquinas virtuales.
- Aplicación práctica de conceptos de **provisioning**, **imaging** y **bare-metal deployment**.

## Relevancia Profesional
Este tipo de habilidades son altamente demandadas en:
- **Administración de sistemas** (despliegue de estaciones de trabajo en empresas o centros educativos).
- **Cloud & DevOps** (base para creación de imágenes golden en AWS AMI, Azure Images, GCP, etc.).
- **Ciberseguridad** (generación de imágenes limpias para análisis forense o recuperación ante ransomware).

## Conclusión
Proyecto 100% funcional, documentado visualmente paso a paso y preparado para escalar a decenas o cientos de equipos reales.

¡Gracias por visitar mi repositorio! Si te interesa la administración de sistemas, cloud o ciberseguridad, dale una ⭐

---
**Autor**: Pau Olivé Moreno  
**Fecha**: Principios de 2025