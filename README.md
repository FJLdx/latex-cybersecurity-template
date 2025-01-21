Plantilla en LaTeX para Informes de Ciberseguridad
Descripción
Esta es una plantilla profesional en LaTeX diseñada para crear informes de ciberseguridad de
manera clara, organizada y elegante. Incluye soporte para resaltar código, personalización de
encabezados y pies de página, y un diseño que resalta profesionalismo.
Características
- Configuración profesional de encabezados con logos personalizados.
- Índice interactivo con enlaces internos en rojo y enlaces externos en azul.
- Personalización para informes de máquinas de plataformas como HackTheBox y TryHackMe.
- Integración de resaltado de código mediante el paquete minted.
- Diseño adaptable para reportes técnicos detallados.
Requisitos
Para utilizar esta plantilla necesitas:
- LaTeX instalado en tu sistema.
- Paquete Minted para resaltar código.
- Compilador con soporte para -shell-escape (necesario para minted).
Instalación en Debian/Ubuntu:
sudo apt update
sudo apt install texlive texlive-latex-extra texlive-fonts-recommended python3-pygments
Uso
1. Descarga o Clona este Repositorio
git clone https://github.com/tu-usuario/latex-cybersecurity-template.git
cd latex-cybersecurity-template
2. Modifica las Variables de la Plantilla
Edita las variables clave en el archivo .tex para personalizar tu informe:
\newcommand{\machineName}{Test}
\newcommand{\platformName}{Hack The Box}
\newcommand{\authorName}{Franco Javier Lazzarini}
3. Compila el Documento
Usa pdflatex o lualatex para compilar el archivo:
pdflatex -shell-escape plantilla.tex
Esto generará un archivo PDF con tu informe.
Estructura del Repositorio
latex-cybersecurity-template/
??? plantilla.tex # Archivo principal de la plantilla
??? images/ # Carpeta para logos y capturas de pantalla
? ??? my_logo.png # Tu logo personal
? ??? platform_logo.png # Logo de la plataforma (Hack The Box, TryHackMe, etc.)
??? README.md # Este archivo
Personalización
- Colores de enlaces: Personaliza en la sección \hypersetup del archivo .tex.
- Encabezados: Modifica los logos en la configuración del paquete fancyhdr.
- Estilo de títulos: Personaliza con titlesec.
Licencia
Este proyecto se distribuye bajo la MIT License. Puedes usarlo y modificarlo libremente.
Contribuciones
Las contribuciones son bienvenidas. Si tienes ideas para mejorar esta plantilla:
1. Haz un fork del repositorio.
2. Crea una rama nueva: git checkout -b mejora-nueva.
3. Haz tus cambios y envía un pull request.
Créditos
Creado por Franco Javier Lazzarini.
Inspirado en las necesidades del pentesting profesional.
