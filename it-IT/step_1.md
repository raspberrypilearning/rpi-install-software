Il tuo Raspberry Pi dovrà essere online per l'installazione dei pacchetti. Prima di installare un pacchetto, fai update e upgrade di Raspbian, il sistema operativo del tuo Raspberry Pi.

+ Apri il terminale e inserisci i seguenti comandi per procedere:

![Apri il terminale](images/terminal.png)

```bash
sudo apt-get update
sudo apt-get upgrade
```

+ Ora puoi installare i pacchetti di cui hai bisogno digitando i comandi `install` nel terminale. Per esempio, ecco come installare il software Sense HAT:

```bash
sudo apt-get install sense-hat
```
