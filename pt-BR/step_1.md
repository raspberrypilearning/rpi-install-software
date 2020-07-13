Seu Raspberry Pi precisará estar online para instalar pacotes. Antes de instalar um pacote, atualize o Raspberry Pi OS (anteriormente chamado Raspbian), o sistema operacional do seu Raspberry Pi.

+ Abra uma janela do terminal e insira os seguintes comandos para fazer isso:

![Abra o terminal](images/terminal.png)

```bash
sudo apt-get update
sudo apt-get upgrade
```

+ Agora você pode instalar os pacotes que você vai precisar digitando os comandos `install` na janela do terminal. Por exemplo, aqui está como instalar o software Sense HAT:

```bash
sudo apt-get install sense-hat
```
