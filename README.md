[![cv](./cv.png?v=2)](https://lopezac.github.io/cv/)

# Instrucciones de instalacion

Instalar latex, en Ubuntu usar el comando `sudo apt-get install texlive-full poppler-utils`

Uso el paquete de `moderncv` de [moderncv/moderncv](https://github.com/moderncv/moderncv)

# Instrucciones para correr el programa

`moderncv/template.tex` es el template original

`moderncv/cv.tex` es mi cv, una modificacion del template original

Compilar el `cv.tex` en pdf se hace con este comando `latexmk -pdf ./moderncv/template.tex ./moderncv/manual/moderncv_userguide.tex`

Para convertir `cv.pdf` en un archivo png se hace con este comando `pdftoppm -singlefile ./cv.pdf cv -png`
