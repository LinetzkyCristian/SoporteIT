# Laboratorio de Active Directory - Entorno Corporativo

## 🎯 Descripción del Proyecto
Este repositorio documenta la creación y configuración de un entorno de red corporativo simulado utilizando **Active Directory (AD)**. El objetivo de este proyecto es demostrar habilidades fundamentales en administración de sistemas, gestión de identidades, control de accesos y resolución de problemas, orientadas a un perfil de **Soporte IT / Help Desk**.

---

## 🏗️ Arquitectura del Laboratorio
El entorno fue levantado utilizando herramientas de virtualización, simulando una red empresarial estándar:

* **Controlador de Dominio (DC):** Windows Server 2022
  * Roles instalados: Active Directory Domain Services (AD DS), DNS Server.
* **Máquina Cliente:** Windows 11 Enterprise
  * Estado: Unido al dominio corporativo.
* **Red:** Configuración de red interna / adaptador puente para permitir la comunicación y resolución de nombres (DNS) entre el servidor y el cliente.

---

## 🛠️ Tareas y Escenarios Implementados
A lo largo de este laboratorio se llevaron a cabo los siguientes procedimientos técnicos:

1. **Configuración del Servidor:**
   * Asignación de IP estática y configuración de parámetros de red.
   * Promoción del servidor a Controlador de Dominio (creación del bosque y dominio).
   * Configuración del servicio DNS para la correcta resolución de nombres en la red.

2. **Gestión de Identidades y Objetos:**
   * Creación y estructuración de **Unidades Organizacionales (OUs)** basadas en departamentos (ej. Administración, Soporte, Ventas).
   * Creación masiva e individual de cuentas de usuarios y grupos de seguridad.

3. **Integración de Clientes:**
   * Configuración de la máquina cliente (Windows 11) para apuntar al DNS del servidor.
   * Unión exitosa del equipo cliente al dominio corporativo de Active Directory.
   * Verificación de inicio de sesión en el equipo cliente utilizando credenciales centralizadas del dominio.

4. **Políticas de Grupo (GPOs) - *Próximamente / Implementado*:**
   * Creación y aplicación de políticas a nivel de OU (ej. restricciones de seguridad, estandarización de equipos).

---

## 📁 Documentación Adjunta
* En este repositorio podés encontrar el archivo `Active_Directory.pdf`, el cual contiene el paso a paso detallado y capturas de pantalla de la implementación completa del laboratorio.

---

## 🧰 Tecnologías y Herramientas Utilizadas
* **Sistemas Operativos:** Windows Server 2022, Windows 11 Enterprise.
* **Servicios de Red:** Active Directory Domain Services (AD DS), DNS.
* **Virtualización:** (VirtualBox / VMware).
