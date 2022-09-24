### clonar el repo :

Paso 1 :

```
1. git clone git clone https://github.com/sumysol1021/MineScape.git
```

esto va a crear un directorio MineScape

Paso 2:

```
git checkout -b mi-rama
```

esto creara la rama mi-rama y me posicionara dentro de ella para trabajar.

### Una vez que terminamos de trabajar, enviamos mi rama a github:

PASO 3:

```
 git add .
```

esto agrega los archivos modificados a un stage local

Paso 4

```
git commit -m "un mensaje lo mas breve y descriptico de que hicimos"

```

esto preprara los archivos a enviar

Paso 5:

```
git push --set-upstream origin mi-rama
```

esto envia mi rama a github para que el admin la una con la rama principal esto se llama merge

nota:
si les da errores de permisos:

paso adicional : https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token

```

git push --set-upstream origin ivan
pedira usuario y token
Username for 'https://github.com': mi-usuario
Password for 'https://ivandonoso@github.com': token_que_creaste_segun_el_link:

```
