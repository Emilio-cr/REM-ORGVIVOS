# Apuntes de Radiación Electromagnética: Enfoque Físico

## 1. Radiación como solución de las ecuaciones de Maxwell
La radiación electromagnética surge naturalmente de las **ecuaciones de Maxwell** en el vacío:

$$
\nabla \cdot \vec{E} = 0, \quad 
\nabla \cdot \vec{B} = 0
$$

$$
\nabla \times \vec{E} = - \frac{\partial \vec{B}}{\partial t}, \quad
\nabla \times \vec{B} = \mu_0 \epsilon_0 \frac{\partial \vec{E}}{\partial t}
$$

De estas se obtiene la **ecuación de onda**:

$$
\nabla^2 \vec{E} - \mu_0 \epsilon_0 \frac{\partial^2 \vec{E}}{\partial t^2} = 0
$$

y análogamente para $\vec{B}$.  
La velocidad de propagación es:

$$
c = \frac{1}{\sqrt{\mu_0 \epsilon_0}}
$$

---

## 2. Forma de onda electromagnética
Una onda plana en el vacío se describe como:

$$
\vec{E}(z,t) = E_0 \cos(kz - \omega t + \phi)\, \hat{x}
$$

$$
\vec{B}(z,t) = \frac{E_0}{c}\cos(kz - \omega t + \phi)\, \hat{y}
$$

- $E_0$: amplitud del campo eléctrico.  
- $B_0 = E_0/c$: amplitud del campo magnético.  
- Relación fundamental: **los campos eléctrico y magnético están en fase, son perpendiculares entre sí y a la dirección de propagación.**

---

## 3. Energía y flujo de radiación
La energía se transporta mediante el **vector de Poynting**:

$$
\vec{S} = \frac{1}{\mu_0} \, \vec{E} \times \vec{B}
$$

Su promedio temporal da la **intensidad de la radiación**:

$$
I = \frac{1}{2} c \epsilon_0 E_0^2
$$

---

## 4. Espectro electromagnético
La radiación se clasifica por su **frecuencia ($\nu$)** o su **longitud de onda ($\lambda$):**

$$
\nu = \frac{c}{\lambda}, \quad E_\gamma = h\nu
$$

| Región | Frecuencia | Longitud de onda | Energía fotón | Ejemplos |
|--------|------------|------------------|---------------|----------|
| Radio  | Hz – MHz   | km – m           | $10^{-9}$ eV  | Comunicaciones |
| Microondas | GHz | cm – mm | $10^{-5}$ eV | Hornos, radares |
| Infrarrojo | $10^{12}$–$10^{14}$ Hz | mm – μm | meV | Calor, sensores |
| Visible | $4–7.5 \times 10^{14}$ Hz | 700–400 nm | 1–3 eV | Visión humana |
| Ultravioleta | $10^{15}$ Hz | 400–10 nm | 3–100 eV | Fotoquímica, ADN |
| Rayos X | $10^{16}$–$10^{18}$ Hz | nm – pm | keV | Medicina, materiales |
| Rayos γ | $>10^{19}$ Hz | < pm | MeV–GeV | Física nuclear |

---

## 5. Fuentes de radiación
- **Cuerpos calientes (cuerpo negro):** emiten un espectro continuo descrito por la ley de Planck:

$$
u(\nu,T) = \frac{8\pi h \nu^3}{c^3} \cdot \frac{1}{e^{h\nu/k_BT} - 1}
$$

- **Transiciones atómicas y moleculares:** generan espectros discretos (líneas de emisión/absorción).  
- **Oscilaciones de cargas aceleradas:** cualquier carga acelerada emite radiación (Larmor):

$$
P = \frac{\mu_0 q^2 a^2}{6 \pi c}
$$

---

## 6. Regímenes de interacción física
La radiación electromagnética se distingue por cómo interactúa con la materia:

1. **Baja energía (radio, microondas):** interacción macroscópica → corrientes inducidas, rotación de dipolos.  
2. **Media energía (IR, visible, UV):** excitación vibracional, electrónica, fotoquímica.  
3. **Alta energía (X, γ):** ionización, procesos nucleares.

---

## 7. Síntesis física
- La radiación es una **onda de campos eléctricos y magnéticos acoplados**.  
- Su intensidad depende de la amplitud de campo ($E_0$).  
- Su capacidad de interactuar con la materia depende de la **energía del fotón ($E=h\nu$)**.  
- Desde este punto de vista, lo que distingue la radiación peligrosa de la inocua no es la “cantidad” de energía, sino la **energía cuántica de cada fotón**.

---
