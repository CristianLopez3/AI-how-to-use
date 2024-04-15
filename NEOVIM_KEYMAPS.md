# Guía de Keymaps para Neovim

Este repositorio contiene una guía detallada de los keymaps utilizados en Neovim. Los keymaps son atajos de teclado que pueden mejorar significativamente la productividad al utilizar el editor de texto Neovim.

## Keymaps Disponibles

### Modo Normal

En el modo normal, se pueden utilizar los siguientes keymaps:

> [!IMPORTANT]
> Por defecto, en Neovim, la tecla <Leader> está configurada como la barra invertida (\), pero puedes cambiarla a cualquier tecla que prefieras en tu archivo de configuración (init.vim o init.lua).

    dd: Borra la línea actual sin afectar el registro.
    <Leader>p: Pega el contenido del registro "0" después del cursor.
    <Leader>P: Pega el contenido del registro "0" antes del cursor.
    <Leader>c: Cambia el texto seleccionado sin afectar el registro.
    <Leader>C: Cambia desde la posición del cursor hasta el final de la línea sin afectar el registro.
    <Leader>d: Borra la palabra actual sin afectar el registro.
    <Leader>D: Borra desde la posición del cursor hasta el final de la línea sin afectar el registro.

## Otros Keymaps Útiles

    +: Incrementa el número debajo del cursor.
    -: Decrementa el número debajo del cursor.
    dw: Borra la palabra anterior al cursor sin afectar el registro.
    <C-a>: Selecciona todo el documento.
    <C-m>: Navega hacia adelante en la jumplist.

## Manipulación de Ventanas

    te: Abre un nuevo archivo en una nueva pestaña.
    <tab>: Navega a la siguiente pestaña.
    <s-tab>: Navega a la pestaña anterior.
    ss: Divide la ventana horizontalmente.
    sv: Divide la ventana verticalmente.
    sh: Mueve el foco a la ventana izquierda.
    sk: Mueve el foco a la ventana arriba.
    sj: Mueve el foco a la ventana abajo.
    sl: Mueve el foco a la ventana derecha.
    <C-w><left>: Reduce el ancho de la ventana actual.
    <C-w><right>: Aumenta el ancho de la ventana actual.
    <C-w><up>: Aumenta la altura de la ventana actual.
    <C-w><down>: Reduce la altura de la ventana actual.

## Funciones Especiales

    <C-j>: Navega hacia el siguiente error o advertencia en el documento.
    <leader>r: Reemplaza el código hexadecimal con HSL.
    <leader>i: Activa/desactiva las sugerencias de contexto LSP.
