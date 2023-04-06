# Clase 01
Bienvendixs a la primer clase!!

Los temas que abordamos fueron:
- Confirmar que todxs tengan su Git instalado
```
Pueden econtrar las indicaciones de instalación en la pestaña RECURSOS ADICIONALES del Índice de Recursos 
```
- Resolver problemas de instalación / configuración de Git  
    1. Durante la instalación de Git les va a pedir que seleccionen su editor de código/texto preferido. Pueden seleccionar el que ya tengan instalado o el bloc de notas. 
    **EVITAR** seleccionar Vim (a menos que ya sepas como usarlo).
    Si eligen Visual Studio Code, **EVITEN** la opción de insiders.
    ![Menu de elegir editor por defecto](https://github.com/Jebushdd/BAM23_Programacion_Web/blob/source/readme_clase_01/git-default-editor.png?raw=true)
    2. Si intentan conectarse a GitHub por primera vez usando el comando git add remote origin, asegúrense de tomar el link SSH de su repositorio. Ejemplo: 
    ```git add remote origin git@github.com:Jebushdd/BAM23_Programacion_Web.git```  
    El git bash les va a preguntar si se quieren conectar y responden con yes.
    ![Mensaje de autenticación](https://github.com/Jebushdd/BAM23_Programacion_Web/blob/source/readme_clase_01/autenticar_ssh.png?raw=true)

- Configurando el user name y user email para Git  
    Una vez tienen instalado Git Bash deben configurar el usuario y el email que se agregará como firma cada vez que guarden una versión de su proyecto
    ```
    git config --global user.name 'mi_nombre'
    git config --global user.email 'mi_correo@electronico.com'
    ```
- Flujo básico de Git (init, add, commit)  
    Recordemos que Git es un sistema de control de versiones y es **distinto** de GitHub (que es una plataforma en internet donde pueden compartir sus proyectos y trabajar colaborativamente con otras personas en el mismo proyecto). En criollo: Git es para trabajar individualmente en tu PC.  
    Hay tres etapas generales en el proceso de versiones de un proyecto con Git:  
    ![Flujo básico de Git](https://github.com/Jebushdd/BAM23_Programacion_Web/blob/source/readme_clase_01/flujo_git.jpg?raw=true)
- Crear un proyecto en GitHub y conectarlo a mi carpeta local (git add remote ssh:<user>@github.com/<repositorio>)
- Subir mis cambios locales a GitHub (git push)