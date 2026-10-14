# Terminal

Apuntes generales de **conceptos y uso de la terminal**

## Definiciones

### Terminal tradicional

Es un dispositivo físico con teclado y pantalla conectado a una computadora que permite introducir texto y recibir la salida textual de un sistema o programa.

### Emulador de terminal

Es una aplicación que reproduce el comportamiento de una terminal tradicional dentro de un entorno gráfico. Ejemplos: GNOME Terminal, Konsole, Windows Terminal, iTerm2 y Alacritty.

### Consola

Tradicionalmente, una consola era el dispositivo principal para controlar un sistema. En sistemas operativos modernos, el término puede referirse a una terminal del sistema, una consola virtual, una consola de administración o una interfaz de texto.

### Shell

Es un programa que lee los comandos introducidos, interpreta su sintaxis y ejecuta programas o realiza operaciones. Ejemplos: Bash, Zsh, Fish y PowerShell.

### CLI

Significa *Command Line Interface* (interfaz de línea de comandos). Es una forma de interacción basada en comandos de texto, en lugar de botones, menús o elementos gráficos.

## Comandos

### Estructura básica

```text
prompt + comando + opciones + argumentos
```

```bash
usuario@equipo:~$ ls -l /home
```

- **Prompt**: indicador que muestra que el shell está listo para recibir una instrucción. Puede mostrar el usuario, el equipo y el directorio actual.
- **Comando**: indica qué acción o programa quieres ejecutar.
- **Opciones**: modifican el comportamiento del comando. A menudo comienzan con `-` o `--`.
- **Argumentos**: especifican sobre qué elemento debe actuar el comando, como un archivo, una carpeta o una dirección.

### Comandos básicos

| Acción                              | Linux   | CMD     | PowerShell      |
| :---                                | :---    | :---    | :---            |
| Mostrar directorio actual           | `pwd`   | `cd`    | `Get-Location`  |
| Listar archivos y carpetas          | `ls`    | `dir`   | `Get-ChildItem` |
| Cambiar de directorio               | `cd`    | `cd`    | `Set-Location`  |
| Crear un directorio                 | `mkdir` | `mkdir` | `New-Item`      |
| Crear un archivo vacío si no existe | `touch` | `type`  | `New-Item`      |
| Mostrar el contenido de un archivo  | `cat`   | `type`  | `Get-Content`   |
| Limpiar la pantalla de la terminal  | `clear` | `cls`   | `Clear-Host`    |
| Consultar el manual de un comando   | `man`   | `help`  | `Get-Help`      |

- La mayoría de comandos en **CMD** también funcionan en **PowerShell**
- Para cambiar de unidad en **CMD** usar `C:`, `D:`, etc.

### Gestionar archivos

| Acción               | Linux      | CMD     | PowerShell      |
| :---                 | :---       | :---    | :---            |
| Abrir un archivo     | `xdg-open` | `start` | `Start-Process` |
| Copiar un archivo    | `cp`       | `copy`  | `Copy-Item`     |
| Mover un archivo     | `mv`       | `move`  | `Move-Item`     |
| Renombrar un archivo | `mv`       | `ren`   | `Rename-Item`   |
| Eliminar un archivo  | `rm`       | `del`   | `Remove-Item`   |

## Atajos

### Teclado

- `Tab`      → Autocompletar
- `↑ / ↓`    → Comando anterior/siguiente
- `Ctrl + C` → Cancelar
- `Ctrl + A` → Inicio de línea
- `Ctrl + E` → Final de línea

### Directorios

- `.`  → Carpeta actual
- `..` → Carpeta superior
- `/`  → Raíz de la unidad actual
- `~`  → Carpeta del usuario (`%USERPROFILE%` en **CMD**)
