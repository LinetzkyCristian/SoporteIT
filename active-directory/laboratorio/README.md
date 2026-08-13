# Laboratorio de Active Directory - Entorno Corporativo

## 🎯 Descripción del Proyecto
Este repositorio contiene todo el desarrollo práctico, configuraciones y documentación de un entorno de red corporativo simulado utilizando **Active Directory (AD)**. El objetivo de este espacio es mostrar de forma directa la implementación técnica, administración de identidades y resolución de escenarios orientados a un puesto de **Soporte IT / Help Desk**.

---

## 📚 Estructura del Repositorio
* **`Active_Directory.pdf`**: Una introducción teórica y conceptual detallada sobre qué es Active Directory, su arquitectura y sus componentes principales.
* **`laboratorio/`**: Carpeta donde se irá subiendo todo el contenido práctico, guías paso a paso y configuraciones del entorno virtualizado.

---

## 🏗️ Arquitectura del Laboratorio
El entorno se levanta utilizando virtualización para simular una red empresarial real:

* **Controlador de Dominio (DC):** Windows Server 2022 (Roles: AD DS, DNS).
* **Máquina Cliente:** Windows 11 Enterprise (Unido al dominio corporativo).

---

## 🛠️ Prácticas y Escenarios Implementados
A medida que avance el laboratorio, se irán documentando los siguientes hitos técnicos:

1. **Configuración Inicial del Servidor** (IP estática, promoción a DC, rol DNS).
2. **Gestión de Identidades** (Creación de Unidades Organizacionales - OUs, usuarios y grupos).
3. **Integración de Clientes** (Unión de Windows 11 al dominio corporativo).
4. **Políticas de Grupo (GPOs)** (Aplicación y resolución de políticas de seguridad).

---

## 🧰 Tecnologías y Herramientas
* **Sistemas Operativos:** Windows Server 2022, Windows 11 Enterprise.
* **Servicios:** Active Directory Domain Services (AD DS), DNS.
* **Virtualización:** Entorno local (VirtualBox/VMware).
