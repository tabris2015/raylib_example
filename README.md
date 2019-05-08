# raylib_example
Projecto de ejemplo para programación de interfaces gráficas con raylib

# Instalacion de dependencias
Este proyecto cuenta con algunas librerías y dependencias que deben ser instaladas para poder compilar los programas adecuadamente, a continuación se detalla el proceso de instalación de las mismas.

1. Instalar dependencias y librerías del sistema:

    ```bash
    sudo apt install build-essential git cmake libasound2-dev mesa-common-dev libx11-dev libxrandr-dev libxi-dev xorg-dev libgl1-mesa-dev libglu1-mesa-dev
    ```

2. Instalar raylib en el sistema

    ```bash
    git clone https://github.com/raysan5/raylib.git raylib
    cd raylib
    mkdir build && cd build
    cmake -DSHARED=ON -DSTATIC=ON ..
    make
    sudo make install
    sudo ldconfig
    ```

# Configuración y compilación del proyecto
Una vez instaladas todas las dependencias, se puede proceder a compilar el presente proyecto.

1. Crear la carpeta build

    ```bash
    mkdir build
    cd build
    ```

2. Desde la carpeta build, generar los archivos de compilación. Compilar.

    ```bash
    cmake ..  
    make
    ```

3. Probar el programa.

    ```bash
    ./teclas
    ```

debe observar una nueva ventana de la siguiente manera:
