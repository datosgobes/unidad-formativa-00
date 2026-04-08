<!--
author:   Equipo gestor de la plataforma datos.gob.es
email:    contacto@datos.gob.es
version:  1.0.0
language: es
narrator: Spanish Female

comment:  Unidad 00 - **Materiales formativos datos.gob.es (2026). Materiales formativos de la Iniciativa Aporta.
-->

# Unidad 00 - Materiales formativos datos.gob.es (2026)

<p align="center">
  <img src="https://raw.githubusercontent.com/datosgobes/unidad-formativa-00/refs/heads/main/assets/img/logo_dge_normal.svg" alt="datos.gob.es" width="300">
</p>

Las unidades formativas de datos.gob.es tienen como propósito principal fomentar el conocimiento, la capacitación y el uso efectivo de los datos abiertos en el ámbito público y privado. 

Estas unidades buscan:

- Concienciar sobre la importancia de los datos abiertos y su utilidad práctica.
- Promover la publicación de datos abiertos de calidad, accesibles y reutilizables.
- Impulsar la reutilización de datos abiertos para generar valor económico, social y administrativo.
- Ofrecer herramientas y conocimientos técnicos, normativos y estratégicos relacionados con los datos abiertos y adaptados a distintos perfiles profesionales.

[![Abrir en LiaScript](https://img.shields.io/badge/Ver%20curso-Abrir%20en%20LiaScript-brightgreen)](https://liascript.github.io/course/?https://raw.githubusercontent.com/datosgobes/unidad-formativa-00/refs/heads/main/CURSO.md)
[![License: CC-BY 4.0](https://img.shields.io/badge/CC%20BY-4.0-lightgrey?logo=creativecommons)](LICENSE)
[![Hecho con Markdown](https://img.shields.io/badge/Made%20with-Markdown-blueviolet)](https://spec.commonmark.org/0.31.2/)

## Contenido de la unidad

Esta unidad formativa aborda:

- Elementos comunes de la **navegación y funcionalidades** de las unidades formativas.
- **Reutilización** del material formativo.

## Ver la unidad

<p align="center" style="font-size: 1.3em;">
  <a href="https://liascript.github.io/course/?https://raw.githubusercontent.com/datosgobes/unidad-formativa-00/refs/heads/main/CURSO.md#1" target="_blank" rel="noopener">▶️ Abrir curso interactivo en LiaScript</a>
</p>


## Unidades formativas disponibles

Actualmente están disponibles las unidades siguientes:


| Unidad formativa | Curso interactivo | Código |
|---------|-------------|--------|
| **Unidad 00 - Materiales formativos datos.gob.es (2026)** | [Ver en LiaScript](https://liascript.github.io/course/?https://raw.githubusercontent.com/datosgobes/unidad-formativa-00/refs/heads/main/CURSO.md#1)  | [Ver en Github](https://github.com/datosgobes/unidad-formativa-00) |
| **Unidad 01 - Datos abiertos: conceptos básicos y beneficios** | [Ver en LiaScript](https://liascript.github.io/course/?https://raw.githubusercontent.com/datosgobes/unidad-formativa-01/refs/heads/main/CURSO.md#1)  | [Ver en Github](https://github.com/datosgobes/unidad-formativa-01) |


Poco a poco iremos liberando otros contenidos de forma progresiva.


## ¿Cómo usar estos materiales?

### LiaScript

Los módulos formativos están diseñados para ser ejecutados con LiaScript, que es es un lenguaje y un intérprete de código abierto, basado en Markdown, diseñado para crear cursos en línea interactivos, libros digitales y recursos educativos abiertos

- [Documentación LiaScript](https://liascript.github.io/)


### Ejecutar el curso en el navegador

Ábre en tu navegador `https://liascript.github.io/course/?https://github.com/<usuario>/<repo>/<archivo>.md`. Ejemplo:    https://liascript.github.io/course/?https://github.com/datosgobes/materiales-formativos/blob/main/unidades/06.md

### Reutilización de los materiales formativos

#### Descarga o clona la unidad
Para reutilizar y editar los materiales formativos es necesario desacargarlos previamente:

 - Desde el github de la unidad descarga la unidad. 
 Ej: la unidad 01 https://github.com/datosgobes/unidad-formativa-01/archive/refs/heads/main.zip

 - Por línea de comandos 
    ```sh
    # Clona un repositorio de materiales formativas, ej la unidad 01
    git clone https://github.com/datosgobes/unidad-formativa-01.git
    ```

#### Edita el código

Para editar el material se puede hacer de diversas maneras, que se presentan a continuación.

#####  **METODO 1. LiveEditor (desarrollo on line)**

1. Abre [LiveEditor](https://liascript.github.io/liveeditor/) pasando la unidad. Ej: [Unidad 01](https://liascript.github.io/LiveEditor/?/show/file/https://raw.githubusercontent.com/datosgobes/unidad-formativa-01/refs/heads/main/CURSO.md)
2. Modifica el contenido en el editor y clicka en *parse* para ver el resultado.
3. Descarga el contenido


#####  **METODO 2. IDE, editor de código fuente ligero (desarrollo local)**

Como muestra se indica el uso del IDE Visual Studio Code (VS Code).

1. Descargar el IDE
2. Instalar las extensiones LiasCript para VS Code siguiendo las instrucciones [las instrucciones](https://liascript.github.io/vscode/)


##### **METODO 3. LiaScript DevServer (desarrollo local)**

Requisitos previos:

- [Node.js](https://nodejs.org/) (recomendado: la versión LTS moderna). Instálalo desde https://nodejs.org/
- [npm](https://www.npmjs.com/) (viene con Node.js)


Instala el `devserver` globalmente (en una terminal Bash en Windows o WSL):

```sh
npm install -g @liascript/devserver
```

Levanta el servidor desde la carpeta del proyecto (por ejemplo, desde la raíz del repositorio `unidad-formativa-01`):

```sh
# en el directorio del proyecto
liascript-devserver

# o para abrir el navegador automáticamente en la vista del archivo actual
liascript-devserver --open
# usar una carpeta concreta como raíz
liascript-devserver --input .\CURSO.md -o
# puerto alternativo
liascript-devserver -p 3001 -o
# live reload (recarga automática al guardar)
liascript-devserver --input .\CURSO.md --live -o
```

>[!TIP]
> Para modificar el CSS en local, puedes modificar en las opciones de configuracion (inicio del Markdown) `link: https://raw.githack.com/datosgobes/unidad-formativa-00/refs/heads/main/assets/css/dge-styles.css` por una hoja CSS situada en el mismo directorio que el documento, ej `./dge-styles.css`


Salida esperada (ejemplo):

```sh
 _     _       ____            _       _
| |   (_) __ _/ ___|  ___ _ __(_)_ __ | |_
| |   | |/ _` \___ \ / __| '__| | '_ \| __|
| |___| | (_| |___) | (__| |  | | |_) | |_
|_____|_|\__,_|____/ \___|_|  |_| .__/ \__|
                                |_|

✨ watching for changes on: "CURSO.md"
📡 starting server
   - local:           http://localhost:3000
   - on your network: http://192.168.68.102:3000
✨ hit Ctrl-c to close the server
```






## Más información

- [Todos los materiales formativos RISP](https://datos.gob.es/es/conocimiento/materiales-formativos-risp-de-iniciativa-aporta)
- [Portal datos.gob.es](https://datos.gob.es)
- [Iniciativa Aporta](https://datos.gob.es/acerca-de-la-iniciativa-aporta)

## Licencia

Contenido con licencia **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

Puedes reutilizar y adaptar estos materiales citando:

> *"Ministerio para la Transformación Digital y de la Función Pública a través de la Entidad Pública Empresarial Red.es"*

Más información en [LICENSE](LICENSE).

## Créditos y contacto

- **Autoría**: Equipo gestor de la plataforma datos.gob.es (Iniciativa Aporta)
- **Contacto**: [comunicar sugerencias, mejoras o incidencias en la plataforma de datos.gob.es](https://datos.gob.es/es/form/contact)
- **Web**: [datos.gob.es](https://datos.gob.es)

---

<p align="center">
  <img src="https://raw.githubusercontent.com/datosgobes/unidad-formativa-00/refs/heads/main/assets/img/logo_iniciativa-aporta.svg" alt="Iniciativa Aporta" width="200">

</p>
