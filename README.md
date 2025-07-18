# Práctica 0: Instalación de herramientas

¡Hola! El objetivo de este documento es guiarte en la instalación de las herramientas necesarias para comenzar a programar en C++ en el curso de Introducción a la Computación 2025. Sabemos que quizás sea su primera experiencia programando, así que vamos a tratar de hacerlo lo más sencillo posible. Si tenés dudas, no dudes en preguntar o pedir ayuda.

---
## Opción recomendada: **WSL2 + Ubuntu + VSCode** (Ideal si anda internet)

1. **WSL2 y Ubuntu**  
   - Abrí PowerShell como administrador y ejecutá:
     ```
     wsl --install
     ```
      - Normalmente puede fallar porque no tenés habilitada la virtualización en la BIOS. En ese caso, seguí las instrucciones de tu placa madre para habilitarla.
      - Si falla, seguí las instrucciones de la [documentación oficial de Microsoft](https://docs.microsoft.com/en-us/windows/wsl/install).
   - Reiniciá la PC si te lo pide.
   - Busca "Ubuntu" en la Tienda de Microsoft y seleccionalo, luego hacé click en "Instalar". 
   - Completá la configuración de Ubuntu (usuario y contraseña).

2. **Visual Studio Code**  
   - Descargalo de: https://code.visualstudio.com/, o
   - Utilizá el instalador que está en esta carpeta (VSCodeSetup.exe).
   - Instalá las extensiones:
     - **Remote - WSL**
     - **C/C++** (de Microsoft)

3. **Compilador de C++ y herramientas**  
   - Abrí la terminal de Ubuntu y ejecutá:
     ```
     sudo apt update
     sudo apt install build-essential
     ```

---
## Opción alternativa: **Windows + MinGW + Git + VSCode** (Ideal si no anda internet)

1. **Visual Studio Code**  
   - Igual que arriba.

2. **MinGW**  
   - Corré el instalador de MinGW que está en esta carpeta (mingw-19.0.exe).
   - Agregalo al PATH de Windows, así ejecutar los comandos funciona.
   - Instalá el compilador (g++) y agregalo al PATH de Windows.

3. **Git**
   - Instalá Git desde https://git-scm.com/downloads o utilizá el instalador que está en esta carpeta (Git-2.XX.X-64-bit.exe).
   - Agregalo al PATH de Windows, así ejecutar los comandos funciona.

---