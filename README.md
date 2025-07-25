# Gitly

> Una CLI todo-en-uno para trabajar con Git de forma rápida, limpia y segura.

`Gitly` es una herramienta de línea de comandos construida en Python que centraliza operaciones comunes de Git como `status`, `commit`, `push`, `pull`, y manejo de ramas. Está diseñada para acelerar tu flujo de trabajo y evitar errores comunes mediante validaciones automatizadas y una interfaz clara.

---

## Funcionalidades (en desarrollo)

- `gitly status` — Muestra el estado del repositorio con formato legible  
- `gitly commit -m "mensaje"` — Realiza commits con validaciones  
- `gitly push` — Hace push seguro con revisión previa  
- `gitly pull` — Pull con validaciones  
- `gitly branch` — Lista, crea, elimina o cambia ramas  
- Más funciones por venir...

---

## Instalación (modo desarrollo)

```bash
git clone https://github.com/tuusuario/gitly.git
cd gitly
pip install -e .
