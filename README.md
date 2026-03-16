🧠 Algoritmos de Búsqueda, Heurísticas y Teoría de Juegos

Este repositorio contiene ejemplos y explicaciones de algunos conceptos importantes en inteligencia artificial y optimización, incluyendo:

🔍 Algoritmo A*

⚡ Heurísticas

🎮 Teoría de Juegos

🐍 Implementaciones en Python

El objetivo es mostrar cómo estos conceptos pueden utilizarse para resolver problemas de búsqueda, toma de decisiones y optimización.

🔍 Algoritmo A*

El Algoritmo A* es un algoritmo de búsqueda utilizado para encontrar el camino más corto entre dos puntos.

Es muy utilizado en:

🗺️ navegación de mapas

🤖 robótica

🎮 videojuegos

🚗 sistemas de rutas (GPS)

El algoritmo evalúa cada nodo usando la función:

f(n) = g(n) + h(n)

Donde:

g(n) → costo real desde el nodo inicial hasta el nodo actual

h(n) → estimación heurística desde el nodo actual hasta el objetivo

f(n) → costo total estimado del camino

Funcionamiento

1️⃣ Se agrega el nodo inicial a la lista de abiertos
2️⃣ Se selecciona el nodo con menor costo estimado
3️⃣ Se exploran los nodos vecinos
4️⃣ Se calcula el costo de cada vecino
5️⃣ Se repite hasta encontrar el objetivo

Ejemplo de uso

El algoritmo puede aplicarse a:

matrices (grids)

grafos

árboles de búsqueda

⚡ Heurísticas

Una heurística es una estrategia que permite encontrar soluciones de manera más rápida, aunque no siempre garantiza la solución perfecta.

Las heurísticas ayudan a:

reducir el espacio de búsqueda

mejorar la eficiencia de los algoritmos

encontrar soluciones aproximadas en menos tiempo

Tipos de heurísticas

🔹 Heurística por valor
Selecciona primero los elementos con mayor valor.

🔹 Heurística por peso
Selecciona primero los elementos más ligeros.

🔹 Heurística por densidad
Selecciona los elementos con mayor relación:

valor / peso

Esta heurística es muy utilizada en el problema de la mochila fraccionada.

Ejemplo: Mochila Fraccionada

En este problema se busca maximizar el valor dentro de una mochila con capacidad limitada, permitiendo tomar fracciones de objetos.

🎮 Teoría de Juegos

La teoría de juegos es una rama de las matemáticas y la economía que estudia la toma de decisiones entre varios agentes que interactúan entre sí.

Se utiliza en:

economía 💰

inteligencia artificial 🤖

estrategia militar ⚔️

política 🏛️

negociación 📊

Tipos de juegos
⚔️ Juegos de suma cero

En estos juegos lo que gana un jugador lo pierde el otro.

Ejemplo:

Ganancia total = 0

Ejemplos:

ajedrez

póker

piedra papel o tijera

🤝 Juegos de suma distinta de cero

En estos juegos todos los jugadores pueden ganar o perder al mismo tiempo.

Ejemplo clásico:

🧩 Dilema del prisionero

Los jugadores deben decidir entre cooperar o traicionar.

📊 Criterios Maximin y Minimax

Estos criterios se utilizan en teoría de juegos y toma de decisiones.

Maximin

El jugador elige la estrategia que maximiza su ganancia mínima posible.

Es una estrategia conservadora.

max(min(resultado))
Minimax

El jugador busca minimizar la pérdida máxima posible.

min(max(resultado))

Este criterio es muy utilizado en IA para juegos como ajedrez o tic-tac-toe.

🐍 Implementaciones en Python

En este repositorio se incluyen ejemplos de:

✔ algoritmo A* para búsqueda de caminos
✔ heurísticas voraces aplicadas al problema de la mochila
✔ teoría de juegos con matrices de pagos

Ejemplo de ejecución:

pesos = [10, 20, 30]
valores = [60, 100, 120]
capacidad = 50

Resultado:

Heurística: densidad
Valor total: 240
📚 Tecnologías utilizadas

🐍 Python

📊 Algoritmos de optimización

🧠 Inteligencia artificial

🔢 Matemáticas aplicadas

👩‍💻 Autor

Luisa Gonzalez
Estudiante de Ingeniería de Sistemas
BIBLIOGRAFIA 



Machine Learning 🧠
