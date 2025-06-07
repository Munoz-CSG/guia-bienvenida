# 🚀 DevOps - Ejercicio Guiado: Iniciándome en Git

> **Curso**: BOTIC-SOFOF-24-28-05-0013 – Fundamentos DevOps  
> **Módulo**: Control de Versiones con Git  
> **Ejercicio**: _Simulación de trabajo colaborativo en equipo de desarrollo_

---

## 📘 Descripción

¡Bienvenido/a a este repositorio! Este ejercicio guiado marca el inicio de nuestra aventura DevOps. En este trabajo, como equipo de desarrollo, practicamos el uso de **Git** para gestionar versiones, ramas, fusiones y conflictos mientras redactamos colaborativamente una **Guía de Bienvenida para nuevos integrantes**. ✨

---

## 🎯 Objetivos del Ejercicio

- 🛠️ Instalar y configurar Git en nuestros entornos.
- 📁 Crear un repositorio local.
- 💬 Realizar commits con mensajes descriptivos.
- 🌿 Crear y gestionar ramas para simular trabajo colaborativo.
- 🔀 Realizar merges y resolver conflictos de edición.
- ☁️ Sincronizar cambios con un repositorio remoto en GitHub (opcional).

---

## 🧩 Estructura del Ejercicio

```
guia-bienvenida/
├── bienvenida.txt  # Documento de bienvenida colaborativo
├── .git/           # Carpeta interna de Git
└── README.md       # ¡Este mismo archivo!
```

---

## 🧪 Comandos Git Utilizados

Algunos de los comandos clave que practicamos:

```bash
git init
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail"

git add bienvenida.txt
git commit -m "Mensaje del commit"

git branch estilo
git checkout estilo
git merge estilo

git checkout -b nueva-rama
git log --oneline
```

También aprendimos a:

✅ Resolver conflictos  
✅ Mantener un historial limpio  
✅ Usar ramas para trabajo simultáneo

---

## 🧠 Lo que Aprendimos

Durante este ejercicio:

- Comprendimos el **flujo de trabajo colaborativo** en un equipo DevOps.
- Aprendimos que los conflictos no son errores, sino **parte natural del trabajo en equipo**.
- Practicamos el uso correcto de ramas y la importancia de los mensajes de commit descriptivos.
- Enfrentamos un **conflicto de fusión real** y lo resolvimos de forma ordenada.

🧩 Además, este ejercicio sienta las bases para la próxima etapa: el diseño de un **plan de trabajo DevOps**, donde definiremos procesos de integración y despliegue continuo (CI/CD), automatización y control de calidad.

---

## 🧭 ¿Qué sigue?

Como parte del proyecto del curso, estamos construyendo un **plan de trabajo DevOps** para un proyecto de software simulado. Este plan integrará:

- 📦 Control de versiones (¡lo que hicimos aquí!)
- 🧪 Testing automático
- ⚙️ Automatización con CI/CD
- 🗂️ Gestión de ramas y entornos
- 🔐 Seguridad desde el inicio

🔜 Pronto compartiremos más avances en este mismo repositorio o en uno nuevo con todo el stack DevOps.

---


## 📎 Recursos útiles

- [Sitio oficial de Git](https://git-scm.com/)
- [Guía rápida de comandos Git](https://education.github.com/git-cheat-sheet-education.pdf)
- [Documentación GitHub](https://docs.github.com/es)

---

## 💡 Créditos

Repositorio creado por Carlo Gonzalez y Jorge Muñoz como parte del curso **Fundamentos DevOps - BOTIC-SOFOF-24-28-05-0013**, facilitado por Brayan C.

---

## 🧑‍💻 ¡Gracias por visitar este repositorio!

Siéntete libre de clonar, explorar y adaptarlo.  
¡Nos vemos en el siguiente sprint! 🚀
