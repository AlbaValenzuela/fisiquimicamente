---
title: Electricidad y electrónica
subtitle: Circuitos eléctricos, ley de Ohm, dispositivos electrónicos y aspectos industriales de la energía
summary: "Electricidad y circuitos eléctricos. Ley de Ohm. Dispositivos electrónicos. Aspectos industriales de la energía."
tags:
- 2º ESO
- 3º ESO
- electricidad-electrónica
categories:
- Física

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Imagen de [**Hans Braxmeier**](https://pixabay.com/es/users/hans-2/) en [Pixabay](https://pixabay.com/es/)
  focal_point: Smart

links:
# - icon_pack: fas
# icon: download
#  name: PDF Texto
#  url: movimientos_texto.pdf
  
- icon_pack: fas
  icon: file-download
  name: Póster
  url: electricidad-electronica-poster.pdf  
---

{{% toc %}}

## Corriente eléctrica
Definimos la **corriente eléctrica** como **cargas** en **movimiento** a través de un conductor.

{{< figure library="true" src="electricidad-electronica-2ESO-3ESO/corriente.svg" title="Adaptada de https://commons.wikimedia.org/wiki/File:Electric_charge_and_electric_current.svg." lightbox="false" width="100%" >}}

## Magnitudes eléctricas
### Intensidad de corriente $I$
La intensidad de corriente es la **cantidad** de **carga** eléctrica que **circula** por un circuito por unidad de **tiempo**. En el **SI** se mide en **amperios** (A).
### Diferencia de potencial $V$
También llamada **tensión**, es la **diferencia** de **energía** eléctrica por unidad de carga que hay entre dos puntos de un circuito. En el **SI** se mide en **voltios** (V).

### Resistencia $R$
La resistencia es una medida de la **oposición** que ofrece un material al **paso** de la **corriente** eléctrica. En el **SI** se mide en **ohmios** ($\Omega$).

{{< spoiler text="¿De qué depende la <strong>resistencia</strong> en un <strong>alambre</strong>? Averígualo con esta <strong>simulación</strong>" >}}
<iframe src="https://phet.colorado.edu/sims/html/resistance-in-a-wire/latest/resistance-in-a-wire_es.html" width="100%" height="600" scrolling="no" allowfullscreen></iframe>

[Aquí](https://es.wikipedia.org/wiki/Resistividad#Tabla_de_resistividades_de_algunos_materiales) tienes los valores de resistividad $\rho$ de algunos materiales.
{{< /spoiler >}}

## Ley de Ohm

La **ley** de **Ohm** establece que la **diferencia** de **potencial** $V$ que aplicamos en los extremos de un conductor es **proporcional** a la **intensidad** de corriente $I$ que circula por él, siendo la constante de proporcionalidad la resistencia $R$ del conductor:		
$$
V = R\cdot I
$$

Puedes aprender más sobre la **ley** de **Ohm** con esta **simulación**:

<iframe src="https://phet.colorado.edu/sims/html/ohms-law/latest/ohms-law_es.html" width="100%" height="600" scrolling="no" allowfullscreen></iframe>

## Buenos y malos conductores
Según su **comportamiento** frente a la **corriente eléctrica**, distinguimos entre:

### Buenos conductores
O **conductores** a secas. **Permiten** el **paso** de la **corriente** eléctrica, ofreciendo poca o ninguna resistencia al flujo de electrones. Los **metales** son buenos conductores.

### Malos conductores
O **aislantes**, son materiales que **impiden** el **paso** de la **corriente** eléctrica, ofreciendo mucha resistencia al flujo de electrones. La **madera** y el **plástico** son ejemplos de aislantes.

### Semiconductores
Materiales que pueden comportarse como **conductores** o como **aislantes**. El **silicio** (Si) es el semiconductor más empleado y es la base de la **electrónica** actual.

## Máquinas eléctricas
Una **máquina eléctrica** es un dispositivo capaz de **transformar** cualquier **forma** de **energía** en energía **eléctrica** o a la inversa. Distinguimos entre:

### Generadores
Transforman **energía mecánica en eléctrica**.

{{< figure library="true" src="electricidad-electronica-2ESO-3ESO/generadores.jpg" title="Generadores eléctricos de principios del siglo XX en una central hidroeléctrica de Budapest.<br>https://commons.wikimedia.org/wiki/File:Gorskii_04414u.jpg" lightbox="true" >}}

### Motores
Transforman **energía eléctrica en mecánica**.

{{< figure library="true" src="electricidad-electronica-2ESO-3ESO/motor-electrico.jpg" title="Rotor, estátor y ventilador de un motor eléctrico.<br> https://commons.wikimedia.org/wiki/File:Rotterdam_Ahoy_Europort_2011_(14).JPG" lightbox="true" >}}

### Transformadores
Transforman las **características** de la **energía**.

{{< figure library="true" src="electricidad-electronica-2ESO-3ESO/transformador.jpg" title="Foto de [**Iqram-O-dowla Shawon**](https://unsplash.com/@iqram_shawon) en [Unsplash](https://unsplash.com/)." lightbox="true" >}}

## Circuitos eléctricos
Llamamos **circuito eléctrico** al conjunto de elementos que, interconectados entre sí, posibilitan que se establezca una **corriente eléctrica**.

### Componentes básicos
#### Conductores
**Hilos/cables** por donde **circulan** las **cargas** eléctricas.

{{< figure library="true" src="electricidad-electronica-2ESO-3ESO/cable.jpg" title="Conductor eléctrico de cobre (Cu).<br> https://commons.wikimedia.org/wiki/File:Stranded_lamp_wire.jpg" lightbox="true" >}}

#### Generadores
**Producen** y **mantienen** la **corriente eléctrica** por el circuito, como las **pilas** 🔋 o las **baterías**.

{{< figure library="true" src="electricidad-electronica-2ESO-3ESO/baterias.png" title="Pilas y baterías de distintos tamaños (voltajes).<br> http://totexmfg.com/totexmfg.com/capabilities-2/battery-knowledge/index.html" lightbox="true" >}}

#### Receptores
Elementos que **transforman** la **energía eléctrica** en otro tipo de energía, como las **resistencias**, las **bombillas** 💡 o los **motores**.

{{< figure library="true" src="electricidad-electronica-2ESO-3ESO/resistencias.jpg" title="Conjunto de resistores axiales de eje de plomo y distintas resistencias.<br> https://commons.wikimedia.org/wiki/File:Electronic-Axial-Lead-Resistors-Array.jpg" lightbox="true" >}}

{{< spoiler text="¿Quieres saber qué significan las <strong>bandas</strong> de <strong>color</strong> que aparecen en las <strong>resistencias</strong>? Pincha aquí" >}}
{{< figure library="true" src="electricidad-electronica-2ESO-3ESO/resistencia-colores.svg" title="**Código** de **colores** para conocer el **valor** de una **resistencia**.<br> Adaptada de https://commons.wikimedia.org/wiki/File:Resistencia.svg" lightbox="false" width="100%" >}}

| Color | 1ª cifra | 2º cifra | Multiplicador | Tolerancia |
| --- | :---: | :---: | :---: | :---: |
| Negro | $0$ | $0$ | $10^0$ | &ndash; |
| Marrón | $1$ | $1$ | $10^1$ | $\pm 1\thinspace\\%$ |
| Rojo | $2$ | $2$ | $10^2$ | $\pm 2\thinspace\\%$ |
| Naranja | $3$ | $3$ | $10^3$ | &ndash; |
| Amarillo | $4$ | $4$ | $10^4$ | $\pm 4\thinspace\\%$ |
| Verde | $5$ | $5$ | $10^5$ | $\pm 0.5\thinspace\\%$ |
| Azul | $6$ | $6$ | $10^6$ | $\pm 0.25\thinspace\\%$ |
| Violeta | $7$ | $7$ | $10^7$ | $\pm 0.1\thinspace\\%$ |
| Gris | $8$ | $8$ | $10^8$ | $\pm 0.05\thinspace\\%$ |
| Blanco | $9$ | $9$ | $10^9$ | &ndash; |
| Dorado | &ndash; | &ndash; | $10^{-1}$ | $\pm 5\thinspace\\%$ |
| Plateado | &ndash; | &ndash; | $10^{-2}$ | $\pm 10\thinspace\\%$ |
| Rosa | &ndash; | &ndash; | $10^{-3}$ | &ndash; |
| Ninguno | &ndash; | &ndash; | &ndash; | $\pm 20\thinspace\\%$ |

{{< /spoiler >}}

#### Elementos de control
Permiten **dirigir** o **interrumpir** el paso de la **corriente eléctrica**, como los **interruptores**.

{{< figure library="true" src="electricidad-electronica-2ESO-3ESO/interruptores.webp" title="https://www.thespruce.com/types-of-electrical-switches-in-the-home-1824672" lightbox="true" >}}

#### Elementos de protección
**Protegen** los **circuitos** y a las **personas**, como los **fusibles**.

{{< figure library="true" src="electricidad-electronica-2ESO-3ESO/fusibles.jpg" title="Fusibles capaces que cortar una intensidad de corriente de hasta 120 kA.<br> Imagen de [**Bruno /Germany**](https://pixabay.com/es/users/bru-no-1161770/) en [Pixabay](https://pixabay.com/es/)." lightbox="true" >}}

{{< figure library="true" src="electricidad-electronica-2ESO-3ESO/elementos-circuito.svg" title="**Símbolos** de algunos de los **elementos** típicos de un **circuito eléctrico**." lightbox="false" width="100%" >}}

### En serie
En los **circuitos** conectados en **serie**, la intensidad $I$ es la misma, mientras que la diferencia de potencial $V$ es la suma.

Los **generadores** han de conectarse entre polos de **distinto signo**. La resistencia equivalente $R_\text{eq}$ es mayor que la mayor de todas las resistencias:

$$
R_\text{eq} = R_1 + R_2
$$

{{< figure library="true" src="electricidad-electronica-2ESO-3ESO/resistencias-serie.svg" title="Circuito eléctrico con dos **resistencias** conectadas en **serie**. La **resistencia equivalente** viene dada por $R_\text{eq} = R_1 + R_2$." lightbox="false" width="100%" >}}

### En paralelo				
En los **circuitos** conectados en **paralelo**, la diferencia de potencial $V$ es el mismo, mientras que la intensidad $I$ es la suma.

Los **generadores** han de conectarse entre polos del **mismo signo**. La resistencia equivalente $R_\text{eq}$ es menor que la menor de todas las resistencias:

$$
\frac{1}{R_\text{eq}} = \frac{1}{R_1} + \frac{1}{R_2}
$$

{{< figure library="true" src="electricidad-electronica-2ESO-3ESO/resistencias-paralelo.svg" title="Circuito eléctrico con dos **resistencias** conectadas en **paralelo**. La **resistencia equivalente** viene dada por $1/R_\text{eq} = 1/R_1 + 1/R_2$." lightbox="false" width="100%" >}}

Puedes jugar a **construir circuitos eléctricos** con esta excelente **simulación**:
<iframe src="https://phet.colorado.edu/sims/html/circuit-construction-kit-dc/latest/circuit-construction-kit-dc_es.html" width="100%" height="600" scrolling="no" allowfullscreen></iframe>

## Dispositivos electrónicos
La **electrónica** comprende la **física**, la **ingeniería**, la **tecnología** y las **aplicaciones** que tratan con la **emisión**, el **flujo** y el **control** de los **electrones** en el vacío y la materia.

### Transistores
Son dispositivos electrónicos semiconductores utilizados para **amplificar** o **cambiar** las **señales electrónicas** y la **energía eléctrica**. El término **transistor** es la contracción en inglés de *transfer resistor*. Actualmente la mayoría de los transistores se encuentran dentro de los llamados **circuitos integrados**.

### Diodos
### Circuitos integrados
## Aspectos industriales de la energía
### Generación
### Transporte
### Distribución