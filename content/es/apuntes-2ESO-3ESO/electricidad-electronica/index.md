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
## Dispositivos electrónicos
### Transistores
### Diodos
### Circuitos integrados
## Aspectos industriales de la energía
### Generación
### Transporte
### Distribución