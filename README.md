# Simpact-preCICE
## Branches
* main: solo para versiones probadas, para compartir (release)
* develope: crear branches a partir de este para hacer desarrollos, hacer merge hacia este cuando se considere que los cambios funcionan para terminar de probarlos
* Simpact-base-Win-VS2026-IFX: creado a partir de develope, es la versión de Simpact obtenida de quitarle a SimpactA (de abo/2026) todo lo referente a AeroM, ya está compilado en Debug y Release y corre con un ejemplo de turbina (caso solo estructural) y da lo mismo que SimpactA - en la carpeta "Simpact-preCICE\vs\spp\x64\Debug\run" hay un archivo de prueba "snl.dat" - NO BORRAR
* adapter_linux (a ser creado): a partir de develop, para incorporar el adaptador de preCICE (antes hay que compilar Simpact para Linux (en otro branch)) (probalbmente nunco se haga merge hacia develope)
* simpact_linux: a partir de develop, para compilar en Linux el programa base - luego hacer merge hacia adapter_linux (probalbmente nunco se haga merge hacia develope)
* adapter_win: a partir de develope, para ir incorporando cambios y compilando con VS2026 en Windows (se puede ir trabajando en paralelo a los otros, pero no sé si es lo mejor)
