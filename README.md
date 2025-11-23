# Sistema ERP Hospitalario - Módulo de Servicios Generales 🏥

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Livewire](https://img.shields.io/badge/Livewire-4E5D94?style=for-the-badge&logo=livewire&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu_Server-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

> **Contexto:** Sistema Integral de 9 módulos para el H. Ayuntamiento de Chiconcuac.
> **Mi Rol:** Desarrollador Full Stack (Responsable del Módulo de Servicios Generales e Infraestructura).

## 📖 Descripción del Proyecto
Este sistema es un ERP masivo diseñado para digitalizar todas las áreas del Hospital Municipal. Fue un esfuerzo colaborativo donde cada módulo se conecta a una base central.

Mi responsabilidad principal fue la **arquitectura y desarrollo completo del módulo de Servicios Generales**, encargado de la gestión del ciclo de vida de los activos hospitalarios (inventarios, mantenimiento y bajas).

---

## 📸 Funcionalidades de mi Módulo

### 1. Dashboard y Métricas
Implementé un tablero de control específico para el área de mantenimiento, permitiendo visualizar el estado operativo de los equipos en tiempo real.
![Dashboard](assets/dashboard.png)

### 2. Gestión de Inventario con Livewire
Desarrollé la lógica para el filtrado dinámico de miles de activos. El reto fue mantener la fluidez de la interfaz utilizando **Livewire** para evitar recargas de página innecesarias.
![Inventario](assets/inventario.png)

### 3. Sistema de Trazabilidad QR 📱
Diseñé e integré la generación de etiquetas QR.
* **Mi aporte:** Logré que el sistema generara PDFs masivos con códigos QR que, al ser escaneados, redirigen a una vista móvil (PWA) con la ficha técnica del equipo.
![Impresión QR](assets/qr_print.png)

### 4. Flujos de Mantenimiento y Bajas
Digitalicé los procesos burocráticos de "Bajas de Activo". El sistema genera automáticamente las actas administrativas en PDF listas para firma, reduciendo el error humano.
![Bajas](assets/bajas.png)

---

## 🛠 Stack Tecnológico & Colaboración

* **Trabajo en Equipo:** Integración de mi módulo con el sistema de autenticación central y bases de datos compartidas.
* **Infraestructura:** Configuración del servidor **Ubuntu** local para el despliegue de todos los módulos del equipo.
* **Tecnologías:** PHP 8.2, Laravel 10, MySQL, TailwindCSS.

---

### 📬 Contacto
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/eddaann)
