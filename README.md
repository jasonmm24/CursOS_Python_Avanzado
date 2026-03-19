<h1 align="center">🐍 Python Avanzado: Interfaces Gráficas, Comunicación y Visión</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Qt_Designer-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="Qt">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/Hardware-SimulIDE-blue?style=for-the-badge" alt="SimulIDE">
</p>

> **Mención Especial:** Este curso y sus materiales de código abierto han sido organizados e impulsados gracias a la asociación **OPEN SOURCE**.

## 📖 Acerca del Curso

Este repositorio contiene el material oficial, códigos base y ejercicios prácticos del curso de Python Avanzado. El proyecto está diseñado con un enfoque práctico en ingeniería, cerrando la brecha entre el desarrollo de software y el control de sistemas físicos reales. 

A través de este material, los estudiantes aprenderán a integrar **Interfaces Gráficas de Usuario (GUI)**, **Protocolos de Comunicación con Hardware** y algoritmos de **Visión Artificial**.

---

## 🗂️ Estructura del Repositorio

El material está organizado en cuatro módulos principales de complejidad progresiva:

📦 CursOS_Python_Avanzado

 | 📂 Modulo_1_POO             # Clases, Herencia y Polimorfismo
 
 | 📂 Modulo_2_Interfaces      # Archivos .ui y conexión de Señales/Ranuras en PyQt
 
 | 📂 Modulo_3_Conexiones      # Scripts Seriales, Bluetooth, TCP-IP y SimpleController
 
 | 📂 Modulo_4_Vision          # Filtros HSV, segmentación espacial y tracking (OpenCV)
 
 | 📜 README.md

---

## 🛠️ Entorno de Trabajo y Requisitos

Para garantizar la accesibilidad, **no se requiere hardware físico (Arduino/ESP32) para tomar este curso**. Todas las prácticas de electrónica e integración se realizarán en entornos de simulación y emulación.

### Dependencias de Software
Asegúrate de tener instalado lo siguiente antes de comenzar:
* **Python 3.x**
* **Librerías principales:** Se instalarán mediante el archivo de requerimientos (PyQt5, opencv-python, pyserial, numpy).
* **Herramientas de Simulación:**
  * Qt Widgets Designer - Para el diseño visual de ventanas.
  * SimulIDE - Para la simulación de circuitos y microcontroladores.
  * com0com (Windows) o socat (Linux) - Para la creación de puertos COM virtuales.

---

## 🚀 Instalación y Uso

Sigue estos pasos para configurar tu entorno local:

1. Clona este repositorio:
   git clone [https://github.com/OPEN-SOURCE-UPIITA/CursOS_Python_Avanzado.git](https://github.com/OPEN-SOURCE-UPIITA/CursOS_Python_Avanzado.git)

2. Accede al directorio del proyecto:
   cd CursOS_Python_Avanzado

3. Crea un entorno virtual (Recomendado):

   python -m venv env
   
   source env/bin/activate  # En Linux/Mac
   
   env\Scripts\activate     # En Windows

5. Instala las dependencias:
   pip install -r requirements.txt

---

## 👨‍💻 Autores y Contribuciones

* **Medina Martinez Jonathan Jason** - Instructor principal y Desarrollo - @jasonmm24 (https://github.com/jasonmm24)
* **Asociación OPEN SOURCE** - Organización e impartición del curso - @OPEN-SOURCE-UPIITA (https://github.com/OPEN-SOURCE-UPIITA)

¿Tienes alguna sugerencia para mejorar el código o el material didáctico? ¡Los Pull Requests son bienvenidos! Siéntete libre de explorar, romper el código y aprender.
