---
title: Enlace químico
url: "/recursos-fisica-quimica/apuntes/2bach-quimica/enlace-quimico"
subtitle: Enlace iónico, covalente y metálico. Geometría molecular. Fuerzas intermoleculares
summary: "Enlace iónico, covalente y metálico. Geometría molecular. Fuerzas intermoleculares."
breadcrumbs: ["recursos-fisica-quimica","apuntes","2bach-quimica"]
tags:
- 2º Bach
- enlace-químico
categories:
- Química

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Imagen de [**Tomislav Jakupec**](https://pixabay.com/es/users/tommyvideo-3092371/) en [Pixabay](https://pixabay.com/es/)
  focal_point: Smart

links:
- icon_pack: fas
  icon: file-download
  name: Póster
  url: enlace-quimico-poster.pdf
  
slides: enlace-quimico-2Bach-quimica
---

{{% toc %}}

## Regla del octeto

> La **configuración más estable** para cualquier átomo es contar con **ocho electrones** en la **capa exterior**.

Los elementos tenderán a **unirse** para completar su capa exterior, **intercambiando** (cediendo/captando $\rightarrow$ enlace **iónico**) o **compartiendo electrones** (enlace **covalente**), y así **ganar estabilidad**.

## Parámetros moleculares

{{< figure library="true" src="enlace-quimico-2Bach-quimica/parametros-moleculares.svg" title="Traducida y adaptada de https://ch301.cm.utexas.edu/section2.php?target=atomic/bonding/covalent-bonding.html." lightbox="false" width="100%" >}}

### Energía de enlace
Es una medida de la **fortaleza** de un **enlace químico**.

### Longitud de enlace
Distancia media entre los núcleos de dos átomos enlazados.

### Ángulo de enlace
Ángulo formado por tres átomos enlazados consecutivamente.

### Polaridad de enlace
Es la separación de cargas eléctricas a lo largo de un enlace, dando lugar a un **momento dipolar eléctrico**. La diferencia de electronegatividad, $\Delta \chi$, entre los átomos de un enlace determina su polaridad:

{{< figure library="true" src="enlace-quimico-2Bach-quimica/polaridad.svg" title="Imágenes adaptadas de https://www.chegg.com/learn/chemistry/introduction-to-chemistry/bond-polarity-and-dipole-moments." lightbox="false" width="100%" >}}
		
Una molécula será polar si el momento dipolar total (suma vectorial) es distinto de cero.

{{< figure library="true" src="enlace-quimico-2Bach-quimica/BF3.png" title="La molécula de BF<sub>3</sub> tiene tres enlaces polares pero debido a su geometría trigonal plana el momento dipolar resultante es nulo.  Fuente: https://commons.wikimedia.org/wiki/File:Boron-trifluoride-elpot-3D-vdW.png." lightbox="true" >}}		

## Enlace iónico

Es un enlace que involucra la **atracción electrostática** entre **iones** de **signo opuesto**. El **enlace iónico** suele darse **entre metales** (tienden a ceder electrones, convirtiéndose en cationes) **y no metales** (tienden a captar electrones, convirtiéndose en aniones). Los compuestos iónicos forman **redes cristalinas** compactas y **neutras** con diferentes geometrías según el tipo de iones que las forman.

{{< figure library="true" src="enlace-quimico-4ESO/enlace-ionico.svg" title="Representación de la **unión iónica** entre el **litio** (Li) y el **flúor** (F) para formar el **fluoruro de litio** (LiF). El litio cede fácilmente su único electrón de valencia a un átomo de flúor, que acepta el electrón donado.<br>Adaptada de https://commons.wikimedia.org/wiki/File:Ionic_bonding.svg." lightbox="false" width="100%" >}}

{{< figure library="true" src="enlace-quimico-4ESO/Lewis-LiF.svg" lightbox="false" width="100%" >}}

### Energía de red $U_\mathrm R$

Es la **energía liberada** al **formar** la **red** a partir de sus iones en estado gaseoso.

#### Ciclo de Born-Haber
Formación de un compuesto iónico a partir de sus elementos.

{{< figure library="true" src="enlace-quimico-2Bach-quimica/Born-Haber.svg" title="Ciclo de Born-Haber para la formación del fluoruro de litio (LiF). Basada en https://commons.wikimedia.org/wiki/File:Born-haber_cycle_LiF.svg." lightbox="false" width="100%" >}}

#### Ecuación de Born-Landé
Permite calcular la **energía de red** $U_\mathrm R$:

$$
U_\mathrm R = -\frac{N_\mathrm A M z^+ z^- e^2}{4\pi\epsilon_0 r_0}\left(1-\frac{1}{n}\right),
$$

donde $N_\mathrm A = 6.022\times 10^{23}\thinspace\mathrm{mol^{-1}}$ es la constante de Avogadro; $M$ es la constante de Madelung, relacionada con la geometría del cristal; $z^+$ y $z^-$ son los números de carga del catión y del anión, respectivamente; $e = 1.6\times 10^{-19}\thinspace\mathrm{C}$ es la carga elemental, $\epsilon_0 = 8.85\times 10^{-12}\thinspace\mathrm{C^2N^{-1}m^{-2}}$ es la permitividad eléctrica del vacío; $r_0$ es la distancia al ion más cercano; y $5<n<12$ es el exponente de Born (experimental).

Se comprueba que la **energía** de **red** es:

- **Directamente proporcional** al **producto** de las **cargas** de los iones.
- **Inversamente proporcional** a la **distancia** interiónica.

### Propiedades de las sustancias iónicas
- Debido a las **intensas fuerzas electrostáticas** entre los iones, suelen tener **temperaturas** de **fusión** y **ebullición** muy **elevadas**, por lo que la mayoría son **sólidos cristalinos** a **temperatura ambiente**.

{{< figure library="true" src="elementos-compuestos-2ESO-3ESO/cristal.svg" title="**Cristal** de **cloruro de sodio** (sal común, NaCl). <br> 🔵 $\rightarrow$ sodio (Na); 🟢 $\rightarrow$ cloro (Cl). <br> https://freesvg.org/sodium-chloride-crystal" lightbox="false" width="100%" >}}

- Ante **golpes**, el **alineamiento** de los **iones** positivos y negativos **puede perderse**, por lo que son muy **frágiles**, aunque también muy **duros**.
- **Fundidos** o en **disolución**, **conducen** la **corriente eléctrica**.

## Enlace covalente
Es un enlace químico que implica la **compartición** de **pares** de **electrones** entre átomos. El **enlace covalente** suele darse **entre no metales** (tendencia a captar electrones).

{{< figure library="true" src="enlace-quimico-4ESO/enlace-covalente.svg" title="Representación de la **unión covalente** entre dos átomos de **flúor** (F) para formar F<sub>2</sub>, con un par de electrones compartidos. Adaptada de https://commons.wikimedia.org/wiki/File:Covalent_bond_fluorine.svg." lightbox="false" width="100%" >}}

### Estructuras de Lewis
Se trata de **diagramas** que **muestran** la **unión** entre los **átomos** de una **molécula** y los **pares solitarios** de **electrones** que pueden existir en la molécula.

Las estructuras de Lewis muestran cada átomo y su posición en la estructura de la molécula usando su símbolo químico. Se dibujan líneas entre los átomos que están unidos entre sí (se pueden utilizar pares de puntos en lugar de líneas). El exceso de electrones que forman pares solitarios se representan como pares de puntos, y se colocan junto a los átomos.

{{< spoiler text="Pincha aquí para ver cómo construir <strong>estructuras</strong> de <strong>Lewis</strong> <strong>paso a paso</strong>" >}}

1. Dibujar la molécula de la forma más simétrica posible, colocando los elementos más electronegtivos en los extremos.
2. Rodear cada elemento del número de electrones de valencia ($N_\mathrm v$).
3. Calcular el número máximo de electrones de valencia cumpliendo la regla del octeto ($N_\mathrm{máx}$).
4. Calcular el número de electrones enlazantes ($N_\mathrm{e} = N_\mathrm{máx} - N_\mathrm{v}$).
5. Calcular el número de electrones no enlazantes ($N_\mathrm{ne} = N_\mathrm{v} - N_\mathrm{e}$).

{{< /spoiler >}}

#### Ejemplos
##### Agua (H<sub>2</sub>O)
{{< figure library="true" src="enlace-quimico-4ESO/Lewis-H2O.svg" lightbox="false" width="100%" >}}

##### Oxígeno (O<sub>2</sub>)
{{< figure library="true" src="enlace-quimico-4ESO/Lewis-O2.svg" lightbox="false" width="100%" >}}

##### Dióxido de carbono (CO<sub>2</sub>)
{{< figure library="true" src="enlace-quimico-4ESO/Lewis-CO2.svg" lightbox="false" width="100%" >}}

### Resonancia
La **resonancia** es una forma de describir el enlace en ciertas moléculas mediante la combinación de varias **estructuras resonantes** cuyo conjunto se conoce como un **híbrido** de **resonancia**. Es especialmente útil para describir los **electrones deslocalizados** (enlaces $=$ en distintas posiciones) en ciertas moléculas o iones poliatómicos.

{{< figure library="true" src="enlace-quimico-2Bach-quimica/resonancia.svg" title="Basada en https://commons.wikimedia.org/wiki/File:Benzene_delocalization.svg." lightbox="false" width="100%" >}}		

### Propiedades de las sustancias covalentes moleculares
{{< figure library="true" src="elementos-compuestos-2ESO-3ESO/molecula.svg" title="Representación esquemática en 3D de una **molécula** de **sacarosa**. <br> ⚫ $\rightarrow$ carbono (C); 🔴 $\rightarrow$ oxígeno (O); ⚪ $\rightarrow$ hidrógeno (H). <br>Fuente: https://commons.wikimedia.org/wiki/File:Sucrose_molecule.svg" lightbox="false" width="100%" >}}

- Debido a las **débiles interacciones entre moléculas** covalentes, suelen tener **temperaturas** de **fusión** y **ebullición bajas** (muchos compuestos covalentes son **líquidos** o **gases** a **temperatura ambiente**).
- En estado sólido son compuestos **blandos** y **frágiles**.
- Son **malos conductores** del **calor** y de la **electricidad**.

### Propiedades de las sustancias covalentes cristalinas
Las **sustancias covalentes cristalinas** contienen un gran número de **átomos neutros** unidos entre sí mediante **enlaces covalentes**, formando **láminas bidimensionales**, como el grafito o el grafeno, o **estructuras tridimensionales**, como el diamante 💎 o el cuarzo.

{{< figure library="true" src="enlace-quimico-4ESO/grafito-grafeno.svg" title="Estructura cristalina del **grafito**, formado por capas de **grafeno** (átomos de **carbono**, C, unidos mediante **enlaces covalentes** en una red hexagonal).<br>Fuente: https://commons.wikimedia.org/wiki/File:Graphit_gitter.svg." lightbox="false" width="100%" >}}

{{< figure library="true" src="enlace-quimico-4ESO/diamante.svg" title="Estructura tetraédrica del **diamante** 💎, formado por átomos de **carbono** (C) unidos mediante **enlaces covalentes**. Fuente: https://www.physics-in-a-nutshell.com/article/13/diamond-structure." lightbox="false" width="100%" >}}

- Debido a los **fuertes enlaces covalentes** entre los átomos, suelen tener **temperaturas** de **fusión** y **ebullición altas**, por lo que son **sólidos** a **temperatura ambiente**.
- Son sustancias muy **duras** aunque **frágiles**.
- Suelen ser **malos conductores** (no así el grafito o el grafeno).

## Geometría molecular

### TRPECV
La **Teoría de Repulsión de Pares de Electrones de la Capa de Valencia** (TRPECV) se basa en que, como los electrones de valencia se repelen unos a otros, éstos tienden a adoptar una disposición espacial que minimiza dicha repulsión.

{{< figure library="true" src="enlace-quimico-2Bach-quimica/TRPECV.svg" title="Imágenes adaptadas de https://www.sigmaaldrich.com/technical-documents/articles/chemistry/vsepr-chart-valence-shell-electron-pair-repulsion-theory.html." lightbox="false" width="100%" >}}

### TEV
La **Teoría del Enlace de Valencia** (TEV) se basa en que los e<sup>&ndash;</sup> compartidos se encuentran en una zona de **solapamiento orbital**:

{{< figure library="true" src="enlace-quimico-2Bach-quimica/TEV.svg" title="Imágenes adaptadas de https://www.coursehero.com/sg/general-chemistry/valence-bond-theory/." lightbox="false" width="100%" >}}

#### Hibridación

La **hibridación** consiste en combinar orbitales atómicos del átomo central para formar **orbitales híbridos** energéticamente iguales y orientados en la dirección del enlace.

{{< figure library="true" src="enlace-quimico-2Bach-quimica/hibridacion.svg" title="Imágenes tomadas de https://www.coursehero.com/sg/general-chemistry/types-of-hybrid-orbitals/" lightbox="false" width="100%" >}}

## Enlace metálico

El **enlace metálico** es el enlace químico que **mantiene unidos** a los **átomos** de un **metal** entre sí. Surge de la **atracción electrostática** entre los **electrones** de conducción y los **cationes** metálicos.

### Modelo del gas electrónico

{{< figure library="true" src="enlace-quimico-4ESO/enlace-metalico.svg" title="Modelo del **gas electrónico**, con los **cationes** en **posiciones fijas** y los **electrones moviéndose libremente** en una ***nube***. Fuente: https://commons.wikimedia.org/wiki/File:Metalic_bond_model.svg." lightbox="false" width="100%" >}}

### Teoría de bandas

{{< figure library="true" src="enlace-quimico-2Bach-quimica/teoria-bandas.svg" title="Comparación de la **estructura** de **bandas** electrónicas de un **metal**, un **semiconductor** y un **aislante**. Traducida y adaptada de https://commons.wikimedia.org/wiki/File:Isolator-metal.svg." lightbox="false" width="100%" >}}

{{% callout note %}}
Puedes aprender más sobre la **teoría** de **bandas** y cómo ésta explica la **conductividad eléctrica** en [este excelente artículo](https://culturacientifica.com/2020/04/21/la-teoria-de-bandas-explica-la-conduccion-electrica/).
{{% /callout %}}

También te recomiendo echar un vistazo a este magnífico **vídeo** de [Quantum Made Simple](https://toutestquantique.fr/en/) (en inglés) donde explican la **diferencia** entre un **metal** y un **aislante**:

{{< youtube LNsSS6Id6bM >}}

### Propiedades de las sustancias metálicas
- **Apariencia brillante**.
- Son **buenos conductores** del **calor** y de la **electricidad**.
- Forman **aleaciones** con otros metales.
- **Tienden** a **ceder** (perder) **electrones** al reaccionar con otras sustancias.
- La mayoría son **sólidos** a temperatura ambiente (**Hg** es 💧).

## Fuerzas intermoleculares
Las **fuerzas intermoleculares** son las **fuerzas** que existen **entre** las **moléculas**, incluyendo las fuerzas de atracción o repulsión que actúan entre las moléculas y otros tipos de partículas vecinas, por ejemplo, átomos o iones. Las fuerzas intermoleculares son **débiles en relación con** las **fuerzas intramoleculares** (las que mantienen unida una molécula).

### Fuerzas de van der Waals

{{< figure library="true" src="enlace-quimico-4ESO/fuerzas-intermoleculares.svg" title="**Atracción intermolecular** entre moléculas de **cloruro de hidrógeno**, HCl. Traducida y adaptada de https://www.coursehero.com/sg/organic-chemistry/intermolecular-forces/." lightbox="false" width="100%" >}}

Se pueden dar entre **moléculas polares** (más fuertes cuanto mayor sea la polaridad de la molécula), y **apolares** (llamadas **fuerzas** de **dispersión** de **London**, más fuertes cuanto más grandes y masivas son las moléculas involucradas).

### Enlaces de hidrógeno
También llamados *puentes de hidrógeno*, son las **fuerzas** intermoleculares más **intensas**. Se dan entre moléculas que contienen átomos de **hidrógeno** unidos a átomos de **nitrógeno** (N), **oxígeno** (O) o **flúor** (F).

{{< figure library="true" src="enlace-quimico-4ESO/enlaces-hidrogeno.svg" title="**Enlaces de hidrógeno** entre átomos de H y O en moléculas de **agua** (H<sub>2</sub>O). Traducida y adaptada de https://www.coursehero.com/sg/organic-chemistry/intermolecular-forces/." lightbox="false" width="100%" >}}

Los **enlaces** de **hidrógeno** son **responsables** de:

- Que el **agua** (H<sub>2</sub>O) tenga una **temperatura** de **ebullición anormalmente alta** (100 &deg;C a presión atmosférica).
- La **estructura** de **proteínas** y **ácidos nucleicos**, como la **doble hélice** del **ADN** 🧬.
- La **estructura** de **polímeros**.

{{< figure library="true" src="enlace-quimico-2Bach-quimica/comparacion-fortaleza-enlaces.svg" lightbox="false" width="100%" >}}