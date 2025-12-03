## 🎨 Concepto Básico de Capas y Modos de Fusión

Una **capa** en Photoshop es como una hoja de acetato transparente que se coloca encima de otras. Una imagen de Photoshop es una pila de estas capas, y la vista final es la combinación de todas ellas.

* **Capas:** Permiten editar elementos individuales de una imagen (texto, ajustes, imágenes) sin alterar permanentemente el resto.
* **Modos de Fusión:** Son algoritmos que determinan **cómo los píxeles de la capa superior (capa de fusión) interactúan y se combinan con los píxeles de las capas que se encuentran debajo (capa base)**, generando un color final. 

---

## 🎚️ Grupos de Modos de Fusión (Blending Modes)

Los modos de fusión están organizados en grupos lógicos, separados por una línea en el menú desplegable, como se ve en tu imagen.

### 1. Grupo de Contraste (Contrast)

Este grupo combina los efectos de los modos de fusión de oscurecimiento y aclaramiento para aumentar el contraste de la imagen. El gris medio (50% de brillo) no produce efecto.

| Modo de Fusión | Explicación | Efecto Común |
| :--- | :--- | :--- |
| **Superponer (Overlay)** | Combina Multiplicar (Multiplican) en las sombras y Trama (Screen) en las luces. Las áreas oscuras se oscurecen, y las claras se aclaran. | Aumento de **contraste** y saturación. Muy utilizado. |
| **Luz Suave (Soft Light)** | Similar a Superponer, pero con un efecto mucho más **sutil** y suave. Es ideal para ajustes ligeros. | Suave realce de luces y sombras. |
| **Luz Fuerte (Hard Light)** | Similar a Superponer, pero con un efecto mucho más **drástico** e intenso. Otorga mayor contraste. | Alto contraste; las luces pueden saturar más. |
| **Luz Intensa (Vivid Light)** | Combina Subexposición lineal (Linear Burn) y Sobreexposición lineal (Linear Dodge), creando un contraste más fuerte y a menudo **saturando** los colores. | Contraste muy fuerte y colores saturados. |
| **Luz Lineal (Linear Light)** | Combina Subexposición lineal y Sobreexposición lineal. Similar a Luz Intensa, pero maneja las transiciones de forma diferente. | Acentúa el contraste de forma intensa. |
| **Luz Focal (Pin Light)** | Combina Aclarar (Lighten) y Oscurecer (Darken). Sustituye los píxeles más oscuros o más claros que el gris medio, creando áreas de contraste extremo. | Crea zonas de contraste muy marcadas. |
| **Mezcla Definida (Hard Mix)** | Simplifica la imagen a ocho colores básicos, forzando los componentes RGB a $0$ o $255$. | Crea un efecto de **color plano** o cómic (posterización extrema). |

---

### 2. Grupo de Diferencia (Difference)

Estos modos se centran en la diferencia entre los valores de brillo o color de las capas.

| Modo de Fusión | Explicación | Efecto Común |
| :--- | :--- | :--- |
| **Diferencia (Difference)** | Resta el valor de brillo del píxel de la capa base del píxel de la capa de fusión (o viceversa), tomando el valor absoluto. | **Invierte colores**. El negro no produce efecto; el blanco invierte completamente el color de la capa base. |
| **Exclusión (Exclusion)** | Crea un efecto similar a Diferencia, pero con un contraste más bajo y un resultado **más suave**. | Inversión de color más suave y menor contraste. |

*(Nota: En tu imagen, también aparecen "Restar" y "Dividir", que forman parte del grupo de **Componentes** o **Matemáticos** y realizan operaciones directas entre los valores de brillo).*

---

### 💡 Consejo para Usar las Capas

Para dominar las capas, recuerda siempre que puedes controlar tres aspectos clave:

1.  **Opacidad (Opacity):** Qué tan transparente es la capa.
2.  **Relleno (Fill):** Similar a la opacidad, pero afecta de manera diferente a los **Estilos de Capa** (como sombras y biselados).
3.  **Modo de Fusión (Blending Mode):** La regla matemática para combinar los colores de los píxeles.