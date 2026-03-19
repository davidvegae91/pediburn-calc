# PediBurn Calc 🩺

Calculadora interactiva y Aplicación Web Progresiva (PWA) para la estimación de la Superficie Corporal Quemada (SCQ) y el cálculo de líquidos de reanimación en pacientes pediátricos.

## Descripción

PediBurn Calc es una herramienta clínica de apoyo a la decisión diseñada para profesionales de la salud. Permite estimar de forma precisa el porcentaje de quemaduras mediante un mapeo anatómico de alta fidelidad basado en la tabla de Lund-Browder modificada por edad. Asimismo, automatiza el cálculo de requerimientos de fluidos de acuerdo con los estándares de reanimación inicial.

## Características Principales

* **Mapeo Anatómico Interactivo:** Interfaz gráfica (SVG + Canvas) que permite "pintar" las áreas afectadas directamente sobre un esquema corporal pediátrico con contornos delimitados.
* **Ajuste Dinámico por Edad:** Adaptación automática de los porcentajes de superficie corporal según el grupo etario del paciente (Tabla de Lund-Browder).
* **Clasificación de Profundidad:** Soporte multiescala para registrar quemaduras desde Grado I (Superficial) hasta Grado IV (Lesión más profunda), con análisis de área parcial por píxeles.
* **Algoritmos de Reanimación:** Procesamiento simultáneo y en tiempo real de los requerimientos de líquidos a 24 horas utilizando las fórmulas de **Parkland** y **Carvajal** (basada en ASC).
* **Arquitectura Offline (PWA):** Instalable en dispositivos iOS y Android, operando de manera nativa y funcional al 100% sin necesidad de conexión a internet (ideal para entornos hospitalarios cerrados).

## Tecnologías Utilizadas

* **Frontend:** HTML5, JavaScript (Vanilla) ES6+, Tailwind CSS.
* **Motor Gráfico:** Manipulación de SVG y análisis de datos de píxeles vía la API de HTML5 `<canvas>`.
* **Despliegue Móvil:** Arquitectura Progressive Web App (Manifest, Service Workers).

## Instalación y Despliegue

La aplicación es puramente del lado del cliente (Client-side) y no requiere ejecución de código en servidor.

### Uso Local
1. Clona este repositorio: 
   ```bash
   git clone [https://github.com/TU_USUARIO/pediburn-calc.git](https://github.com/TU_USUARIO/pediburn-calc.git)
