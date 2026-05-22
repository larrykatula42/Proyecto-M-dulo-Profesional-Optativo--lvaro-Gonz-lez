# Proyecto-M-dulo-Profesional-Optativo--lvaro-Gonz-lez
Proyecto Integral SMRº1 Descripción

Este proyecto ha sido desarrollado como parte del módulo Fundamentos de Computación en la Nube del ciclo formativo de Sistemas Microinformáticos y Redes (SMR).

El objetivo es diseñar una solución cloud para una pequeña empresa ficticia llamada TallerTec S.L., dedicada a la reparación y mantenimiento de equipos informáticos. La propuesta busca ofrecer una infraestructura sencilla, segura y económica utilizando servicios de Microsoft Azure.

Objetivos del proyecto Diseñar una arquitectura basada en servicios cloud. Seleccionar un proveedor de nube adecuado para las necesidades de la empresa. Identificar los servicios necesarios para alojar una aplicación web y su base de datos. Aplicar conceptos básicos de seguridad y almacenamiento en la nube. Realizar una estimación aproximada de costes. Empresa analizada

TallerTec S.L. es una pequeña empresa con cuatro empleados que necesita:

Gestionar clientes, equipos y reparaciones mediante una aplicación web. Almacenar la información de forma segura. Permitir el acceso desde diferentes dispositivos. Reducir costes de infraestructura y mantenimiento. Tecnologías y servicios utilizados

La solución propuesta utiliza los siguientes servicios de Microsoft Azure:

Azure Virtual Machines Azure Database for MySQL Azure Blob Storage Azure Virtual Network (VNet) Network Security Group (NSG) Azure Backup Arquitectura propuesta

La infraestructura está compuesta por:

Una máquina virtual donde se ejecuta la aplicación web. Una base de datos MySQL gestionada por Azure. Un sistema de almacenamiento para documentos y archivos. Una red privada virtual para la comunicación interna. Reglas de seguridad para controlar el acceso a los recursos. Esquema simplificado Usuario │ HTTPS │ ▼ Aplicación Web (Azure VM) │ ├──► Base de Datos MySQL │ └──► Blob Storage Seguridad

Las principales medidas de seguridad incluidas son:

Uso de conexiones HTTPS. Acceso restringido a la base de datos. Configuración de Network Security Groups. Copias de seguridad automáticas. Separación de servicios mediante red privada virtual. Estimación de costes

La solución ha sido diseñada pensando en una pequeña empresa con pocos usuarios concurrentes.

Escenario Coste estimado Primer año (con servicios gratuitos) 6 - 7 €/mes A partir del segundo año 32 - 35 €/mes

Los precios son orientativos y pueden variar según la región y las tarifas vigentes de Microsoft Azure.

Autor:

Álvaro González Proyecto realizado para el módulo Fundamentos de Computación en la Nube del ciclo formativo de Sistemas Microinformáticos y Redes (SMR).
