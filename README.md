# [Computación Gráfica](https://github.com/DrakeDX/Computacion-Grfica)

```bash
git clone --recursive https://github.com/DrakeDX/Computacion-Grfica.git
cd Computacion-Grfica
```
Configurar vcpkg

```bash
.\vcpkg\bootstrap-vcpkg.bat
.\vcpkg\vcpkg integrate install
```
Instalar las siguientes librerias con vcpkg:

```bash
.\vcpkg\vcpkg install freeglut:x64-windows
.\vcpkg\vcpkg install glew:x64-windows
.\vcpkg\vcpkg install glfw3:x64-windows
.\vcpkg\vcpkg install glm:x64-windows
.\vcpkg\vcpkg install glad:x64-windows
.\vcpkg\vcpkg install stb:x64-windows
```
