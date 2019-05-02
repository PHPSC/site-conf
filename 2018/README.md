# PHP-SC Conference 2018 - Hotsite

Hotsite para a PHPCONF-SC 2018

## Rodando localmente

```console
docker build -t phpsc-conf .
docker run -it --name phpsc-conf -p 4000:4000 --rm -v `pwd`:/usr/src/app phpsc-conf
```