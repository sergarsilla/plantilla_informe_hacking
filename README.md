# Plantilla LaTeX para Informes de Hacking Ético

![Licencia](https://img.shields.io/badge/license-MIT-blue.svg)

Plantilla LaTeX modular y profesional para la creación de informes de pentesting y resolución de salas de Hacking (TryHackMe, Hack The Box, etc.).

## 📂 Estructura del Proyecto

```
.
├── images/                 # Capturas de pantalla y recursos gráficos
├── build/                  # Carpeta de salida para el PDF y ficheros temporales
├── rooms/                  # Ficheros .tex para cada informe individual
│   └── plantilla_room.tex
├── .gitignore
├── .vscode/
│   └── settings.json
├── main.tex                # Fichero maestro que compila el documento
└── README.md
```

## 🚀 Uso

1.  **Requisitos:** Tener instalada una distribución de LaTeX (TeX Live, MiKTeX) y VS Code con la extensión [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.LaTeX-Workshop).
2.  **Añadir Sala:** Duplica `rooms/plantilla_room.tex`, renómbralo y edita su contenido.
3.  **Incluir en el Informe:** Añade la línea `\input{rooms/tu_nueva_sala.tex}` en `main.tex`.
4.  **Compilar:** Compila siempre el fichero `main.tex` para generar el documento PDF en la carpeta `/build`.

## 🤝 Contribuciones

Las sugerencias y mejoras son bienvenidas. Para proponer cambios, se recomienda **abrir un "Issue"** para discutir la idea o **enviar un "Pull Request"** con una descripción clara de la mejora.

## 👤 Autor

-   **[Sergio García Mansilla]**
-   **GitHub:** [@sergarsilla](https://github.com/sergarsilla)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.