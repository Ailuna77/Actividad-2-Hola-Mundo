# Actividad-2-Hola-Mundo
## Proyecto Integrador Anual - LPR 2026

* **Institución:** E.E.S.T. N.º 1 "Eduardo Ader" - Vicente López
* **Curso:** 5° Año 3° (A-B)
* **Materia:** Laboratorio de Programación (LPR)
* **Profesor:** Prof. York
* **Actividad:** Actividad 2: El Taller del Programador (Glosario y Entorno C++)

---

## Descripción del Proyecto
Este proyecto corresponde a la Actividad 2 del laboratorio. Resuelve el problema de la configuración inicial del entorno de desarrollo (IDE) para programación estructurada de bajo nivel. Está dirigido a estudiantes del taller para dominar conceptos técnicos clave (*compilador, depurador, PATH*) y validar el correcto funcionamiento del compilador mediante un programa clásico de prueba "Hola Mundo" adaptado con datos del estudiante.

## Integrantes (Grupo N.º 3)
* **Zacarias, Gabriel**
* **Mojica, Sofia**
* **De Armas, Leonel**
* **Roberts, Mateo**

---

## Requisitos e Instalación
1. Tener instalado **Git** y un editor como **VS Code** junto con sus extensiones esenciales (*C/C++ de Microsoft, Code Runner*).
2. Tener configurado el compilador **MinGW (GCC)** mediante **MSYS2** en las Variables de Entorno (**PATH**) del sistema operativo.

### Clonar el repositorio de la actividad:
```bash
git clone https://github.com/GabZac/Actividad-2-Hola-Mundo.git
```

### Dirigirse a la carpeta del reto práctico:
```bash
cd holamundo
```

---

## Ejecución
Para compilar y correr el programa de C++ utilizando **PowerShell** en la terminal interna de VS Code, ejecute los siguientes comandos estando parado en la raíz de la carpeta `holamundo`:

### 1. Compilación
Genera un archivo ejecutable personalizado dentro de la carpeta `src/`:
```powershell
g++ src/main.cpp -o src/holamundo.exe
```

### 2. Ejecución
Corra el programa compilado en Windows:
```powershell
.\src\holamundo.exe
```

---

## Estructura Obligatoria del Repositorio

```text
holamundo/
├── .gitignore              <-- Archivo para que Git ignore carpetas de configuración (.vscode)
├── README.md               <-- Portada técnica del proyecto (Este archivo)
├── LICENSE                 <-- Descripción breve de la licencia
├── docs/                   <-- Carpeta exclusiva para documentación
│   └── InformeProyectoHOLAMUNDO.pdf <-- ENTREGABLE (Formato APA v7)
├── src/                    <-- Carpeta para los códigos fuente
│   └── main.cpp            <-- Primer código de prueba en C++ (Modificado con datos del alumno)
└── capturas/               <-- Carpeta para guardar las evidencias en imágenes
    ├── gpp_version.png        <-- Captura de la consola verificando el compilador (g++ --version)
    ├── extensiones_vscode.png <-- Captura de las extensiones C/C++ instaladas
    └── ejecucion_hola_mundo.png <-- Captura de la terminal compilando y corriendo el programa
```
