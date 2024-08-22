# Taller de GIT

## Prerrequisitos

- Tener una cuenta de Github creada (se sugiere optar por plan educativo),
- Tener instalado Github Desktop.

## Actividades

- Formar grupos de 4 o 5 integrantes.

### Actividad 1

1. Uno de los integrantes deberá crear un repositorio GIT local con un archivo Readme.md donde se consigne el número de grupo del equipo además de su nombre y código, tal como el siguiente ejemplo:

```
# Grupo 1

## Integrantes

- Percy Gonzalez (20222323)
```

2. Ese integrante (desde ahora llamado capitán) deberá de commitear y pushear su trabajo a la rama master (o main) del repositorio en Github. Para esto debe configurar Github para realizarlo.

3. Cada integrante del equipo (menos el capitán) deberá hacer un pull del proyecto que subió a Github el capitán, para luego aumentar su nombre, como el siguiente ejemplo:

```
# Grupo 1

## Integrantes

- Percy Gonzalez (20222323)
- Victoria Lopez (20231234)
```

**Nota:** Tomar en cuenta que pueden haber conflictos. Por lo tanto se sugiere que el equipo coordine las secuencias de pull y push.

4. Una vez que ya se tengan todos los códigos en github, el capitán debe de pullear la última versión y crear un tag llamado **v1.0**.

### Actividad 2

1. El capitán del equipo debe hacer un pull y tener la última versión del proyecto.

2. Posteriormente, debe de crear un archivo llamado **TecnologiasWeb.md** que tenga el siguiente contenido:

```
# Tecnologías Web

## Frontend

## Backend

```

3. El capitán debe de commitear y pushear estos últimos cambios al proyecto en Github.

4. Cada integrante del equipo deberá hacer un pull del proyecto. Posteriormente debe crear su propia *branch* llamada **feature/<codigo>** con su código de alumno. **OJO:** No olvidarse que para crear la nueva branch debe estar en la última versión de la rama master (o main).

5. Cada integrante del equipo deberá modificar el archivo **TecnologiasWeb.md** agregando y explicando tecnologías web del frontend y backend. Para esto puede utilizar *chatgpt* o cualquier otra inteligencia artificial. Tomar en cuenta que no solo debe poner el nombre de la tecnología, si no también una pequeña explicación.

```
# Tecnologías Web

## Frontend

- Tailwind CSS: Un framework de utilidades CSS que permite diseñar interfaces directamente desde el HTML utilizando clases predefinidas.

## Backend

```

6. Posterior al llenado del archivo, debe proceder a *pushear* su branch (no master ni main) a github. Antes de realizar el pusheo, es **MUY IMPORTANTE** que se cerciore que se encuentra con la última versión del repositorio. Para esto, debe volver a hacer un *pull* por si acaso. En caso que tenga conflicto, ver de solucionarlo de forma local.

7. Al pushear su branch, automáticamente se creará un **pull request**. Un **pull request** es una petición de cambio al branch principal (master o main) desde el branch que acaba de subir.

8. El capitán deberá aprobar el pull request en caso no haya conflictos. En caso que si los haya, el capitán deberá de resolver los conflictos antes de volver a hacer un *commit* y *push*. Esto lo debe de hacer para todos los pull request.

9. Una vez que ya se tenga todo integrado, el capitán debe de crear un tag llamado **v2.0**.



