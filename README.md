# Interfaz grafica menú de productos
El codigo implementa una interfaz grafica en Python usando Tkinter, se muestra distintos componentes distribuidos ewn cinto pestañas (tabs) mediante la utilización de ttk.Notebook.

# Resumen general del programa:
1. Se crea una ventana principal titulada 'Productos en venta' con un tamañp de 800x600.
2. Se organiza la interfaz en conto tabuladores, cada uno con funcionalidas distintas para demotrar el uso de elementos gráficos como entrada de texto, texto con scroll, combobox, imagenes y una barra de progreso.

# Resumen del tabulador:

Tab1: "Productos"
- Contiene un etiqueta y una entrada de texto para el nombre del un producto.
- Un Botón que permite moestrar el valor ingreso mediante un MessageBox emergente.

Tab2: "Caracteristicas"
- Muestra un área de testo con scroll (scrilledtext) que contiene texto predefinido.

Tab3: "Cantidad"
- Incluye un ComboBox con números del 1 al 101.
- Un botón permite mostrar el valor seleccionado.

Tab4: "Image"
- Muestra imagen en formato png.
- Al hacer click se muetra su nomebre de archivo en un MessageBox.

  Tab5: " Barra de progreso"
  Presenta un barra de progreso horizontal y botones para controlarla:
  - Ejecutar barra de progreso: avanza la barra de 0 a 100
  - Ejecutar cilcis: inicia la barra de forma continua.
  - Detener ejecucuón: detiene la barra.
  - Despues: detiene la barra despues de un segundo.
 
    # Aspectos técnicos
    - Uso de tk.Tk() para inicar la ventana principal.
    - Cada sección está modularizada en funciones independientes (crear_componetes_tabuladorx) para facilitar la lectura y mantenimiento.
    - Uso del grid() para poscionamiento.
    - Uso de ttk para widgets modernos.

El final del código se denomina crear_tabs() y se utiliza para inicializar todo y ventana.mainloop() para mentener la ventana activa hasta que el usuario la cierre.
