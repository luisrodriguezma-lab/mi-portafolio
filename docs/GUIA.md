# Guía del proyecto: Trabajo Colaborativo con Repositorios Remotos

Documentación del Laboratorio 03 del curso Diseño de Interfaces de Programación Avanzado.

## Sobre este trabajo

Este laboratorio consistió en practicar un flujo de trabajo colaborativo real usando Git y GitHub: hacer fork de un repositorio, corregir errores en ramas separadas, crear Issues y enviar Pull Requests al repositorio original.

## Herramientas usadas

- **Git** para el control de versiones
- **GitHub** para el repositorio remoto y los Pull Requests
- *Visual Studio Code* como editor

## Pasos para reproducir este trabajo

1. Hacer fork del repositorio original en GitHub
2. Clonar el fork a la computadora con `git clone`
3. Crear una rama nueva para cada corrección
4. Confirmar los cambios con commits descriptivos
5. Subir la rama con `git push`
6. Abrir un Pull Request hacia el repositorio original

## Avance del laboratorio

- [x] Fork del repositorio creado
- [x] Primer error corregido y Pull Request enviado
- [ ] Segundo Pull Request en revisión

## Archivos y comandos del proyecto

| Archivo/Comando | Qué hace |
|---|---|
| `index.html` | Estructura principal de la página de la tienda |
| `estilos.css` | Define los colores y la tipografía del curso |
| `git checkout -b` | Crea y cambia a una rama nueva |

## Comando más usado

Para revisar en qué rama estoy antes de hacer cualquier cambio, uso `git branch`.

```bash
git add .
git commit -m "Corrige el nombre del archivo CSS enlazado"
git push origin fix-estilos-css
```

> Trabajar con ramas separadas evita mezclar cambios que no tienen relación entre sí.

## Enlaces útiles

- [Documentación oficial de Git](https://git-scm.com/doc)
- [Mi perfil de GitHub](https://github.com/luisrodriguezma-lab)

## Captura de mi trabajo

![Terminal mostrando el flujo de git](../img/captura.png)