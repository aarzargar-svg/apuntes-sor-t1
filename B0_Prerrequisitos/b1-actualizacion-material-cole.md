- **Alumno:** Aarón Zaragoza García 
- **Bloque:** B0 — Prerrequisitos
- **Fase / ejercicio:** 0120.1_1 Actualización de Material
- **Fecha de inicio:** 27/11/2026
- **Fecha de entrega:** 27/11/2026

---

## 🎯 Qué se pedía

Actualizar el repositorio del Bloque 1, eliminando la versión antigua y sustituyéndola por una nueva creada desde la plantilla del profesor. También había que comprobar que estaba actualizado y completar esta bitácora.

## ⌨️ Comandos y pasos importantes

- `cd ~` → Ir a la carpeta de usuario.
- `git clone git@github.com:TU-USUARIO/bloque-1-entorno.git B1_Entorno` → Clonar el repositorio con el nombre B1_Entorno.
- `ls` → Comprobar los archivos y carpetas que hay.
- `git log --oneline -1` → Consultar el último commit del repositorio

## 🛠️ Qué he hecho

He comprobado que no tenía archivos personales importantes en el repositorio antiguo. Después, he eliminado el repositorio viejo de GitHub y la carpeta local. He creado uno nuevo utilizando Use this template desde el repositorio del profesor y lo he clonado en mi ordenador con el nombre B1_Entorno.

Por último, he comprobado que aparecen las tres carpetas nuevas: B1_Lab_VirtualBox, B1_Lab_HyperV y B1_Lab_Comun, y que el último commit corresponde al 26 de noviembre de 2026.

## 🚩 Qué me ha fallado y cómo lo he resuelto

No he tenido ningún problema importante durante la actualización. He seguido los pasos indicados para sustituir el repositorio antiguo por el nuevo y comprobar que todo estaba actualizado.

## 🤔 Respuestas a las preguntas

**Pregunta 1.** ¿Qué tres carpetas tiene el repositorio nuevo y qué guarda cada una?

- B1_Lab_VirtualBox: prácticas relacionadas con VirtualBox.
- B1_Lab_HyperV: prácticas relacionadas con Hyper-V.
- B1_Lab_Comun: prácticas que sirven para los dos programas.

**Pregunta 2.** ¿Por qué el segundo argumento de git clone es obligatorio? ¿Qué habría pasado sin él?

Porque indica el nombre que tendrá la carpeta local. Sin él, Git habría creado una carpeta llamada `bloque-1-entorno` en lugar de `B1_Entorno`.

**Pregunta 3.** ¿Qué se puede deshacer: borrar la carpeta local o borrar el repositorio de GitHub?

Se puede volver a descargar la carpeta local clonando el repositorio. En cambio, borrar el repositorio de GitHub es permanente y no se puede recuperar fácilmente.

**Pregunta 4.** ¿Con qué comando compruebas que estás en la versión nueva? ¿Qué tiene que decir la respuesta?

Con el comando `git log --oneline -1`. El último commit debe indicar la fecha `2026-11-26`.

**Pregunta 5.** ¿Qué es Use this template y en qué se diferencia de un fork?

Use this template permite crear un repositorio nuevo a partir de otro, copiando sus archivos sin mantener la relación con el original. Un fork crea una copia que mantiene la relación con el repositorio original.

**Pregunta 6.** ¿Había algo tuyo en el repositorio viejo? Si lo había, ¿dónde lo guardaste?

No había nada mío importante en el repositorio viejo, así que no tuve que guardar ningún archivo.

## 🔗 Enlaces

- **Vídeo de esta fase:** https://youtu.be/onJ0ClTOhWw
- **Playlist:** B0_Prerrequisitos

## 💭 Dudas / a repasar

- [ ] Nada.