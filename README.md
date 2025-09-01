# Apuntes sobre Radiación y Organismos Vivos

## 1. ¿Qué entendemos por radiación?
En física, **radiación** se refiere a la propagación de energía a través del espacio.  
Puede presentarse como:
- **Radiación electromagnética (EM):** ondas que combinan campos eléctricos y magnéticos oscilantes.
- **Radiación de partículas:** corrientes de electrones, protones u otras partículas con masa.

Aquí nos centraremos en la **energía electromagnética**, que abarca desde ondas de radio hasta rayos gamma.

---

## 2. Energía electromagnética: campos eléctrico y magnético
Una onda electromagnética se describe como:

$$
\vec{E}(z,t) = E_0 \cos(kz - \omega t) \, \hat{x}
$$

$$
\vec{B}(z,t) = \frac{E_0}{c}\cos(kz - \omega t) \, \hat{y}
$$

- $\vec{E}$: campo eléctrico (V/m).  
- $\vec{B}$: campo magnético (T).  
- Ambos están en fases y orientaciones perpendiculares, propagándose en conjunto.  

La energía transportada se mide con el **vector de Poynting**:

$$
I = \tfrac{1}{2} c \epsilon_0 E_0^2
$$

---

## 3. Tipos de radiación y efectos en seres vivos
Según la **frecuencia** ($\nu$) o **energía de fotón** ($E=h\nu$):

- **No ionizante:** radio, microondas, infrarrojo, visible.  
  - Efectos principales: calor, excitación molecular, estimulación sensorial (visión, fotosíntesis).  
- **Ionizante:** ultravioleta, rayos X, rayos gamma.  
  - Efectos principales: ruptura de enlaces químicos, daño celular y genético.

---

## 4. Radiación de baja frecuencia (ELF)
Ejemplo: **líneas de transmisión de alta tensión (50–60 Hz)**.

### 4.1 Caracterización
- **Frecuencia:**

$$
f \approx 50 \,\text{Hz} \quad \text{o} \quad 60 \,\text{Hz}
$$

- **Longitud de onda:**

$$
\lambda = \frac{c}{f} \sim 5000 \,\text{km}
$$

- **Campos generados:**

Campo eléctrico por el voltaje:

$$
E(r) \sim \frac{V}{d}
$$

Campo magnético por la corriente:

$$
B(r) = \frac{\mu_0 I}{2 \pi r}
$$

- **Intensidades típicas medidas cerca de líneas de alta tensión:**
  - Campo eléctrico: $0.1 - 10 \,\text{kV/m}$  
  - Campo magnético: $0.01 - 20 \,\mu\text{T}$

---

### 4.2 Energía de los fotones
Un fotón de 60 Hz tiene energía:

$$
E_\gamma = h \nu \approx 4 \times 10^{-14} \,\text{eV}
$$

👉 Esto es **14 órdenes de magnitud menor** que la energía necesaria para romper un enlace químico (~1–10 eV).  
Por lo tanto, **no hay ionización directa ni ruptura de ADN con ELF**.

---

### 4.3 Corrientes inducidas
Por la **ley de Faraday**, un campo magnético variable induce un campo eléctrico:

$$
E_{\text{inducido}}(r) = \frac{r}{2} \, \omega B_0
$$

La densidad de corriente en un organismo conductor:

$$
J = \sigma \, E_{\text{inducido}} = \sigma \, \frac{r}{2} \, \omega B_0
$$

- $\sigma$: conductividad del tejido ($\sim 0.3 \,\text{S/m}$).  
- $r$: tamaño característico del organismo.  

**Ejemplo:** para un humano bajo $B_0 = 10 \,\mu\text{T}$:  

$$
J \approx 10^{-4} \,\text{A/m}^2
$$

muy por debajo del umbral de estimulación nerviosa ($\sim 0.1 \,\text{A/m}^2$).

---

### 4.4 Modelos de riesgo biológico
- Los efectos son **macroscópicos/inducidos**, no cuánticos.  
- **Modelo básico:**

$$
J_{\text{inducido}} \propto f \, B \, r
$$

donde $B$ es el campo magnético y $r$ la dimensión característica del cuerpo.

- **Límites recomendados (ICNIRP, 2010):**
  - **Exposición pública:**
    - $E < 5 \,\text{kV/m}$  
    - $B < 200 \,\mu\text{T}$  
  - **Exposición ocupacional:**
    - $E < 10 \,\text{kV/m}$  
    - $B < 1000 \,\mu\text{T}$  

---

## 5. Escalamiento en organismos vivos
- **Grandes organismos (humanos, ganado):** mayor $r$ → mayor corriente inducida.  
- **Pequeños organismos (ratones, insectos):** menor $r$ → corrientes despreciables.  
- **Plantas:** al tener tejidos poco conductores, la corriente inducida es mínima.

---

## 6. Interpretación biológica

### 6.1 Exposición típica
- **Valores ambientales (<0.5 μT):** corrientes inducidas despreciables frente al ruido bioeléctrico natural.  
- **Exposición cercana a líneas de transmisión (>10 μT):** corrientes inducidas mayores, pero aún pequeñas frente a umbrales de estimulación.  
- **Riesgo a largo plazo:** debate epidemiológico. ICNIRP e IARC clasifican ELF como **posible carcinógeno (grupo 2B)**.

---

### 6.2 Magnetorrecepción
La magnetorrecepción no se basa en corrientes inducidas clásicas, sino en mecanismos especializados:

#### a) Magnetita (Fe₃O₄) intracelular
- Cristales encontrados en bacterias magnetotácticas, peces, tortugas, aves e insectos (abejas, hormigas).  
- Energía de interacción magnética:

$$
E = -\vec{m} \cdot \vec{B}
$$

donde $\vec{m}$ es el momento magnético del cristal y $\vec{B}$ el campo externo.  
- Diferencias de pocos μT pueden alinear cristales y activar canales iónicos.  
- Sensibles a **campos estáticos (DC)** como el terrestre (~50 μT).

#### b) Pares radicales en criptocromo
- Moléculas fotoactivas (ej. criptocromo en retina de aves e insectos).  
- Forman pares radicales cuyo destino depende de $B$:  

$$
P_{\text{reacción}} = f(B, \Delta g, \tau)
$$

donde $\Delta g$ es la diferencia de factores giromagnéticos y $\tau$ el tiempo de coherencia.  
- Sensibles a **campos débiles y variables (AC o ELF)**, incluso de decenas de μT.

---

### 6.3 Implicaciones ecológicas
- **Aves migratorias:** desorientación en presencia de ELF.  
- **Insectos:** posible interferencia en navegación de abejas/hormigas.  
- **Peces y tortugas:** riesgo en migración si hay campos artificiales submarinos.  

👉 Los campos ELF (10–100 μT) pueden actuar como **“ruido magnético”** que perturba la brújula biológica natural.

---

## 7. Síntesis
- La radiación electromagnética se describe mediante campos $E$ y $B$ acoplados.  
- Los efectos biológicos dependen de la frecuencia: térmicos, fotoquímicos o ionizantes.  
- La radiación de **baja frecuencia (50–60 Hz)** no ioniza, pero induce corrientes mínimas en organismos grandes.  
- En organismos con **magnetorreceptores**, incluso campos artificiales del orden de decenas de μT pueden alterar la orientación, con consecuencias ecológicas.

---

✍️ Documento pensado como **apuntes de física aplicados a la biología**, útil para dialogar 
