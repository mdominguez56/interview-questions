# Interview questions - 2022

## Frontend questions - Javascript y React

1. [DOM](#dom)
2. [Virtual-DOM](#virtual-dom)
3. [HOC](#hoc)
4. [Hooks](#hooks)
5. [Context](#context)
6. [Lazy loading](#lazy-loading)
7. [Children prop](#children-prop)
8. [Life cycling](#life-cycling)
9. [Referencias](#referencias)

### 1.DOM

---

Qué es el DOM, la estructura de objetos que genera el navegador en memoria para cada uno de los elementos de la página.
Las siglas DOM significan Document Object Model, o lo que es lo mismo, la estructura del documento HTML. Una página HTML está formada por múltiples etiquetas HTML, anidadas una dentro de otra, formando un árbol de etiquetas relacionadas entre sí, que se denomina árbol DOM (o simplemente DOM).

![DOM image](https://www.aprenderaprogramar.com/images/stories/Cursos/CU011/CU01123E_2.png "Title")

---

### 2. Virtual-DOM

---

El Virtual DOM es una representación virtual del DOM, una "versión liviana" (un gran objeto JS) del DOM real que encontramos en el browser, que React utiliza para mapear elementos del DOM real y poder realizar cambios en este de una forma mucho más rápida y eficiente. Cada vez que el state de nuestra aplicación cambia, se actualiza el Virtual DOM y no el DOM real.

![virtual-dom](https://camo.githubusercontent.com/b83301522c381ca893aa81e4aaa2a22280dfe493bb2edf57fbbd67221a48baaf/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f323034382f312a7772685f6c57366d70514852737547747731467571412e706e67 "Title")

Básicamente, cada vez que agregamos nuevos elementos (componentes) a la UI, un nuevo virtual DOM (representado como un árbol) es creado. Cada elemento es un nodo de este árbol. React toma un snapshot de los elementos de nuestra aplicación y lo carga en este árbol. Si el state de alguno de estos elementos cambia, se genera un nuevo virtual DOM. Este DOM (virtual) es entonces comparado con el DOM (virtual) previo y se calculan las diferencias a través de un algoritmo de diffing. Utilizando esta información, React calcula la forma más eficiente de realizar los cambios en el DOM real, actualizando sólo los nodos que cambiaron, reduciendo el impacto en la performance de nuestra aplicación.

---

### 3. HOC

---

Completar con HOC

### 4. HOOKS

---

Completar con todos los hooks, con un ejemplo de cada uno

### 5. CONTEXT

---

Completar con que es el context

### 6. Lazy Loading

---

Completar con lazy loading

### 7. Children component

---

Completar con Children component

### 8. Life Cycling

---

Completar con Life Cycling

### 9. Referencias

---

Completar con Referencias
