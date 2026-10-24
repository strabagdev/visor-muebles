# Visor Muebles

Visor Three.js para documentar y revisar muebles a medida. Conserva los controles del proyecto original.

## Modelo actual: isla comedor

Medidas nominales calculadas con 1 pulgada = 25,4 mm:

- Dimensión total: 1500 × 700 × 900 mm.
- Marco exterior: 1400 × 600 mm; voladizo de 50 mm por lado.
- Cuatro patas 2×4": sección 101,6 × 50,8 mm, largo 874,6 mm. Cara de 101,6 mm orientada al largo de la isla.
- Cubierta de 25,4 mm: cuatro tablas 1500 × 152,4 mm y una recortada a 1500 × 90,4 mm.
- Marco y tres apoyos interiores 2×3": sección 50,8 × 76,2 mm.
- Dos largueros superiores de 1196,8 mm.
- Dos laterales superiores, tres apoyos interiores y dos laterales inferiores de 498,4 mm.
- Apoyapiés centrado: dos piezas 1×2" de 1247,6 mm unidas para formar una sección de 50,8 × 50,8 mm.
- Cara superior del apoyapiés y laterales inferiores a 200 mm del piso.
- Los laterales inferiores se centran en el espesor de las patas; el apoyapiés termina en sus caras interiores.
- Total: 20 piezas.

Verificar medidas reales de madera antes de cortar. El modelo no define las uniones ni sustituye la comprobación estructural.

## Controles

- Rotación y zoom con OrbitControls.
- Vistas ISO, frente, atrás, izquierda, derecha y superior.
- Selección por listado o doble clic en el modelo.
- Aislar, ocultar, mostrar todo y detalle de pieza.
- Vista explotada y encuadre.
- Despiece, detalles, exportación CSV y JSON, impresión/PDF.

## Uso

Abre `index.html` en un navegador con WebGL y aceleración gráfica disponibles.
Three.js 0.128.0 y OrbitControls se cargan desde CDN; se requiere conexión a internet.
Se conserva la versión de Three.js del proyecto original.

## Verificación de esta actualización

Se comprobó sintaxis JavaScript, cantidad y dimensiones de las piezas, coherencia del despiece y conservación de controles/exportaciones. La validación visual WebGL quedó pendiente porque el navegador de pruebas tiene WebGL deshabilitado.
