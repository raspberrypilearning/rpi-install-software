Your Raspberry Pi will need to be online to install packages. Antes de instalar un paquete, utiliza los comandos update y upgrade para actualizar Raspbian, el sistema operativo de tu Raspberry Pi.

+ Para hacer esto, abre una ventana de terminal e introduce los siguientes comandos:

![Abrir la Terminal](images/terminal.png)

```bash
sudo apt-get update
sudo apt-get upgrade
```

+ Ahora puedes instalar los paquetes que necesitarás escribiendo los comandos `install` en la ventana de la terminal. Por ejemplo, así se instala el software Sense HAT:

```bash
sudo apt-get install sense-hat
```
