# CONTRIBUCIONES

¿Cómo contribuir?

## 1. Hacer un fork del repositorio

Primero, necesitas hacer un fork del repositorio en tu cuenta de GitHub.

## 2. Configurar el ambiente de trabajo

Para preparar tu entorno de desarrollo, sigue estos pasos:

- Instala Quarto.
- Crea un ambiente virtual.
- Activa el ambiente virtual.
- Instala las dependencias del proyecto ejecutando:

```sh
$ pip install -r requirements.txt
```

Una vez configurado, deberías poder renderizar el proyecto con los siguientes comandos:

```sh
$ quarto render .
```

o

```sh
$ make render
```
(en Linux/Mac)

## 3. Crear una nueva rama

Antes de empezar a trabajar en tus cambios, crea una nueva rama para tu trabajo:

```sh
$ git checkout -b nombre-de-tu-rama
```

## 4. Realizar tus cambios

Haz los cambios que consideres necesarios en el código del proyecto.

## 5. Hacer commits de tus cambios

Guarda tus cambios con mensajes de commit descriptivos:

```sh
$ git add .
$ git commit -m "Descripción de tus cambios"
```

## 6. Enviar tus cambios a GitHub

Envía tus cambios a tu repositorio fork en GitHub:

```sh
$ git push origin nombre-de-tu-rama
```

## 7. Crear un Pull Request

Finalmente, crea un Pull Request desde tu repositorio fork hacia el repositorio original. Asegúrate de describir claramente los cambios y la razón detrás de ellos.

¡Gracias por tu contribución!