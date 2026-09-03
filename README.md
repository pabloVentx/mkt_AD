# mkt_AD
Herramienta útil para entornos de Active Directory, para agilizar la organización y limpieza de nuestro entorno de trabajo. Inspirado en la herramienta de s4vitar "mkt".

## ¿COMO USARLO DIRECTAMENTE DESDE NUESTRA SHELL?

Primero debemos identificar que tipo de shell tenemos para ello:

```
echo $SHELL
```

Luego dependiendo del tipo de shell, por ejemplo **zsh**, nos metemos dentro:

```
nano ~/.zshrc
```

Alfinal del todo pegamos el código de ![](https://github.com/pabloVentx/mkt_AD/blob/main/mkt_AD)[mkt_AD], guardamos y salimos. Seguidamente recargamos la configuración:

```
source ~/.zshrc
```

Ejecutamos la herramienta:

```
mkt_AD
```
