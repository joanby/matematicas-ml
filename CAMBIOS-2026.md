# Cambios 2026 (rama `update-2026`)

Puesta al día de los cuadernos que usan los vídeos del curso: 1–4, `artificial-neurons`, `regression-in-pytorch`, `single-point-regression-gradient` y `batch-regression-gradient`. Ningún cambio toca el código que se ve en un vídeo, salvo una línea que hoy falla (`np.product`).

## Versiones con las que se ha comprobado

Las de Google Colab el 26 de noviembre de 2026: Python 3.13, NumPy 2.4.6, SciPy 1.16.3, scikit-learn 1.6.1, TensorFlow 2.21.0 y PyTorch 2.14.1. Se han ejecutado de principio a fin, antes y después del cambio, los ocho cuadernos de arriba y `gradient-descent-from-scratch`.

## Qué cambia y por qué

**Lo que fallaba**

- `2-linear-algebra-ii`, producto de los valores propios: `np.product` ya no existe en NumPy 2 (`AttributeError`). Ahora es `np.prod`, que da el mismo resultado.

**Enlaces rotos**

- Botón «Open in Colab» de los cuadernos 1–4, `regression-in-pytorch`, `single-point-regression-gradient` y `batch-regression-gradient`: apuntaba a un fichero que no existe (sin la carpeta `notebooks/` y con guiones bajos). Ahora abre el cuaderno de este repositorio.
- `artificial-neurons`: el botón abría el repositorio del autor original; ahora abre el de este.
- `1-intro-to-linear-algebra`: el tutorial de PyTorch en la GPU ya no existe en esa dirección; ahora enlaza a [Learning PyTorch with Examples](https://pytorch.org/tutorials/beginner/pytorch_with_examples.html).
- `2-linear-algebra-ii`, final del ACP: el servidor del cuaderno original (`jupyter.brynmawr.edu`) no responde. Se quita el enlace y se deja el crédito en texto.

**Texto que no se correspondía con el código o con la matemática**

- `1-intro-to-linear-algebra`: `tf.placeholder` salía entre los tensores de TensorFlow 2, pero era de TensorFlow 1 (hoy solo existe `tf.compat.v1.placeholder`).
- `1-intro-to-linear-algebra`: el error de `np.dot(B, A)` no se debe a que el producto de matrices no sea conmutativo, sino a que las formas (2, 2) y (3, 2) no encajan.
- `2-linear-algebra-ii`: el cizallamiento no cambia la longitud de los vectores; desplaza cada punto en paralelo a un eje, en proporción a la otra coordenada.
- `3-calculus-i`: `sin_fxn(0)` no da un error, devuelve `nan` con un `RuntimeWarning`, que es lo que se ve en el vídeo.
- `4-calculus-ii`: la fórmula de ∂v/∂r usaba `\parcial` y no se veía; ahora es `\partial`.
- `single-point-regression-gradient`: «la pendiente de la recta viene dada por y = mx + b» pasa a «la recta viene dada por y = mx + b» (la pendiente es m).
- Cuadernos 2 y 4: la presentación remitía a la serie del autor original; ahora, como el 1, a este curso.

**README**

- Se quitan los enlaces y las menciones a Udemy. El resto no cambia.

## Lo que puede verse distinto al vídeo

- NumPy 2 muestra los escalares con su tipo (`np.float64(19.99999999999999)` en vez de `19.99999999999999`). El valor es el mismo.

## Lo que no se ha tocado a propósito

Arreglarlo cambiaría lo que enseña el vídeo:

- La forma de mostrar los escalares de NumPy 2 (`np.int64(25)`).
- El `DeprecationWarning` de `np.dot` con tensores de PyTorch (cuaderno 1, celda 154; cuaderno 2, celdas 187–191).
- El `UserWarning` de `x_p.T` en un tensor 1D (cuaderno 2, celda 15, que ningún vídeo ejecuta) y el de `V_cplx.float()` (cuaderno 2, celda 138).

Los cuadernos 5–8, `SGD-from-scratch`, `learning-rate-scheduling` y `gradient-descent-from-scratch` no son de este curso y no se han cambiado.

## Lo que sigue dependiendo de fuera

- La foto de la SVD (cuaderno 2) se descarga de `joanby/DLTFpT`. Hoy responde; si ese repositorio desaparece, esa celda fallará.
