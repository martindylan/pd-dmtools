# pd-dmtools
Surtido de herramientas básicas de audio y de control, desarrolladas en [Pure Data](https://github.com/pure-data/pure-data).  
  
Incluye las siguientes abstracciones:
- `[3band~]`: Ecualizador de tres bandas.
- `[3bandsplit~]`: Divide la señal en tres bandas frecuenciales.
- `[comp~]`: Compresor con sidechain, lookahead y detección RMS/peak.
- `[crushy~]`: Reductor de profundidad de bits y de frecuencia de muestro.
- `[ctlmng]`: Interfaz que permite controlar y modificar controles midi recibidos mediante el objeto [ctlin].
- `[dbgain~]`: Control de ganancia en dB.
- `[del4~]`: Interfaz simple para los objetos [delwrite~] y [delread~].
- `[esofilt~]`: Filtro esotérico basado en tres delays en serie.
- `[evenodd~]`: Detecta si la parte entera de una señal (obtenida mediante floor, round o ceil) es par o impar.
- `[hide~]`: Sintetizador percusivo.
- `[hrtimer]`: Contador legible por humanos (mm:ss:ms).
- `[infinifold~]`: Wavefolder "infinito".
- `[keytog]`: Devuelve 1 o 0 si la tecla indicada es presionada o no, respectivamente.
- `[linease]`: Generador de rampas similar al objeto [line] pero que cuenta con las formas ease-in, ease-out y ease-in-out.
- `[lrtoms~]`: Conversor de estéreo izquierda-derecha a mid-side.
- `[master~]`: Pensada para utilizar al final de la cadena, esta abstracción cuenta con: control de ganancia en dB, vúmetro, conversión de estéreo a mono, eliminación de DC offset y clipeo a -1 1.
- `[mstolr~]`: Conversor de estéreo mid-side a izquierda-derecha.
- `[pan~]`: Herramienta para panear una señal mono.
- `[panstereo~]`: Herramienta para panear una señal estéreo.
- `[pw~]`: Generador de pulsos u oscilador con forma de onda rectangular.
- `[scale]`: Escala un número de un rango inicial a un nuevo rango, con la posibilidad de agregar un valor exponencial para la escala.
- `[seq1]`: Secuenciador con diversas escalas y operaciones.
- `[signsplit~]`: Separa las partes negativa y positiva de una señal.
- `[stom~]`: Herramienta para reducir la imagen estéreo.
- `[tanh~]`: Devuelve una aproximación de la tangente hiperbólica de una señal.

## créditos
- [Pure Data](https://github.com/pure-data/pure-data) por Miller Puckette y muchxs más.
