# pd-dmtools
Surtido de herramientas básicas de audio y de control, desarrolladas en [Pure Data](https://github.com/pure-data/pure-data).  
  
Incluye las siguientes abstracciones:
- `[3band~]`: Ecualizador de tres bandas.
- `[3bandsplit~]`: Divide la señal en tres bandas frecuenciales.
- `[comp~]`: Compresor con sidechain, lookahead y detección RMS/peak.
- `[comp-ladspa~]`: Interfaz simple para el plugin LADSPA sc3 (requiere [pd-plugin](https://github.com/teaecetyrannis/pd-plugin) y el paquete [swh-plugins](hhttps://github.com/swh/ladspa)).
- `[crushy~]`: Reductor de profundidad de bits y de frecuencia de muestro.
- `[ctlmng]`: Interfaz que permite controlar y modificar controles midi recibidos mediante el objeto [ctlin].
- `[dbgain~]`: Control de ganancia en dB.
- `[del4~]`: Interfaz simple para los objetos [delwrite~] y [delread~].
- `[evenodd~]`: Detecta si la parte entera de una señal (obtenida mediante floor, round o ceil) es par o impar.
- `[fv~]`: Interfaz simple para el plugin LADSPA freeverb3 (requiere [pd-plugin](https://github.com/teaecetyrannis/pd-plugin) y el paquetes [cmt](https://www.ladspa.org/cmt/overview.html)).
- `[gv~]`: Interfaz simple para el plugin LADSPA gverb (requiere [pd-plugin](https://github.com/teaecetyrannis/pd-plugin) y el paquete [swh-plugins](hhttps://github.com/swh/ladspa)).
- `[infinifold~]`: Wavefolder "infinito".
- `[linease]`: Generador de rampas similar al objeto [line] pero que cuenta con las formas ease-in, ease-out y ease-in-out.
- `[lrtoms~]`: Conversor de estéreo izquierda-derecha a mid-side.
- `[master~]`: Pensada para utilizar al final de la cadena, esta abstracción cuenta con: control de ganancia en dB, vúmetro, conversión de estéreo a mono, eliminación de DC offset y clipeo a -1 1.
- `[mstolr~]`: Conversor de estéreo mid-side a izquierda-derecha.
- `[pan~]`: Herramienta para panear una señal mono.
- `[panstereo~]`: Herramienta para panear una señal estéreo.
- `[probs]`: Generador de bangs en base a una probabilidad de 0-100%.
- `[pw~]`: Generador de pulsos u oscilador con forma de onda rectangular.
- `[signsplit~]`: Separa las partes negativa y positiva de una señal.
- `[stom~]`: Herramienta para reducir la imagen estéreo.
- `[tanh~]`: Devuelve una aproximación de la tangente hiperbólica de una señal.

## créditos
- [Pure Data](https://github.com/pure-data/pure-data) por Miller Puckette y muchxs más.
- [CMT](https://www.ladspa.org/cmt/overview.html) por Richard W.E. Furse y otrxs.
- [SWH](https://github.com/swh/ladspa) por Steve Harris.
- [plugin~](https://github.com/teaecetyrannis/pd-plugin) por Jarno Seppänen.
