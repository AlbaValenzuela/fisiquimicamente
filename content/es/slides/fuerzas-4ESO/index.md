---
title: Fuerzas
summary: "Leyes de Newton y fuerzas de especial interés."

slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: white
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: tomorrow
---

# Fuerzas

- [Naturaleza vectorial de las fuerzas](#/1)
- [Leyes de Newton](#/2)
- [Fuerzas de especial interés](#/3)
- [Ejemplo](#/4)
- [Simulación](#/5)

Descarga estas diapositivas en formato PDF[{{< icon name="download" pack="fas" >}}](?print-pdf#)

---

{{% section %}}

## Naturaleza vectorial de las fuerzas

Las **fuerzas** son **magnitudes vectoriales**, lo que significa que quedan definidas por un **vector**, del cual hay que definir su:

---

### Módulo
Longitud del segmento.

---

### Dirección
Recta que lo contiene.

---

### Sentido
Dado por la punta de la flecha.

---

{{< figure library="true" src="fuerzas-4ESO/vector.svg" title="En dos dimensiones, un vector se puede escribir como $\newcommand{\ihat}{\hat{\imath}}\newcommand{\jhat}{\hat{\jmath}}\vec a = a_x \ihat + a_y \jhat$, donde $\ihat$ y $\jhat$ son vectores unitarios ($\text{módulo} = 1$) a lo largo de los ejes $x$ e $y$. El módulo de $\vec a$, $|\vec a|$, se calcula como (teorema de Pitágoras) $|\vec a| = \sqrt{a_x^2+a_y^2}$." lightbox="false" width="50%" >}}

---

### Suma o resta de vectores
Gráficamente, dibujando un vector a continuación del otro y uniendo el origen con el punto final:

{{< figure library="true" src="fuerzas-4ESO/suma-vectores.svg" lightbox="false" width="100%" >}}

---

O analíticamente, componente a componente:
$$
\vec a + \vec b = (a_x+b_x)\ihat + (a_y+b_y)\jhat
$$

---

Puedes prácticar a sumar vectores con la siguiente **simulación**:

<iframe src="https://phet.colorado.edu/sims/html/vector-addition/latest/vector-addition_es.html" width="100%" height="500" scrolling="no" allowfullscreen></iframe>

{{% /section %}}

---

{{% section %}}

## Leyes de Newton

- [1ª ley (ley de la inercia)]()
- [2ª ley (ley fundamental de la dinámica)]()
- [3ª ley (ley de la acción-reacción)]()

(continúa hacia abajo)

👇

---

### 1ª ley (ley de la inercia)
> Todo cuerpo preserva su estado de reposo o movimiento rectilíneo uniforme salvo que actúe una fuerza sobre él.

---

### 2ª ley (ley fundamental de la dinámica)
> El cambio de movimiento es proporcional a la fuerza ejercida y se hace en la dirección de la línea recta en que se ejerce la fuerza.

Matemáticamente, se escribe como
$$
\sum\vec F = m\vec a\quad \text{(la aceleración es proporcional a la fuerza neta)}
$$

En el SI la fuerza se mide en Newton (N): $1\thinspace\mathrm N = 1\thinspace \mathrm{kg\thinspace m\thinspace s^{-2}}$.

---

### 3ª ley (ley de la acción-reacción)
> Para toda acción siempre hay una reacción igual y opuesta.

Si un cuerpo A ejerce una fuerza sobre otro cuerpo B, éste ejercerá sobre A una fuerza igual y de sentido contrario ($\vec F_\text{AB} = -\vec F_\text{BA}$).

{{% /section %}}

---

{{% section %}}

## Fuerzas de especial interés

- [Peso $\vec P$]
- [Normal $\vec N$]
- [Rozamiento $\vec f_\mathrm r$]
- [Centrípeta $\vec f_\mathrm c$]

(continúa hacia abajo)

👇

---

### Peso $\vec P$
El **peso** es la fuerza con la que la Tierra atrae a un objeto. Se calcula como:
$$
\vec P = m\vec g,
$$
donde $m$ es la masa del objeto y $\vec g$ es la aceleración de la gravedad. Siempre se dirige hacia el centro de la Tierra (hacia abajo en la mayoría de los casos).

---

### Normal $\vec N$
También llamada fuerza de **reacción**, se define como la fuerza que ejerce una superficie sobre un cuerpo apoyado sobre ella.

Es de igual magnitud y dirección, pero de sentido contrario a la fuerza ejercida por el cuerpo sobre la superficie.

---

{{< figure library="true" src="fuerzas-4ESO/normal.svg" title="Fuerza normal en a) una superficie horizontal, b) un plano inclinado y c) una superficie vertical." lightbox="false" width="100%" >}}

---

### Rozamiento $\vec f_\mathrm r$
La **fuerza de rozamiento** es la fuerza que existe entre dos superficies en contacto, oponiéndose siempre al movimiento relativo entre ambas superficies.

La fuerza de rozamiento es proporcional a la normal $N$:
$$
f_\mathrm r = \mu N,
$$
donde $\mu$ es el coeficiente de rozamiento.

---

{{< figure library="true" src="fuerzas-4ESO/rozamiento.svg" title="Fuerza de rozamiento en a) una superficie horizontal, b) un plano inclinado y c) una superficie vertical." lightbox="false" width="100%" >}}

---

Puedes aprender más sobre la naturaleza del rozamiento con esta **simulación**:

<iframe src="https://phet.colorado.edu/sims/html/friction/latest/friction_es.html" width="100%" height="500" scrolling="no" allowfullscreen></iframe>

---

### Centrípeta $\vec f_\mathrm c$
Se llama **fuerza centrípeta** a la fuerza o a la componente de la fuerza que actúa sobre un objeto en movimiento sobre una trayectoria curvilínea y que está dirigida hacia el centro de curvatura de la trayectoria. Su módulo se calcula a partir de la **aceleración centrípeta**, haciendo uso de la **2ª ley de Newton**:
$$
f_\mathrm c = m a_\mathrm c = m\cdot \frac{v^2}{R} = \frac{mv^2}{R}
$$

{{% /section %}}