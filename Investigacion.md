Rostro Díaz Jesús Ignacio - 22310397 - 4P - Estructura de datos y algoritmia.
Tópico: Investigar sobre el bubble sort, insertion sort y selection sort.
Bubble sort.
    El Bubble Sort es un algoritmo de clasificación simple que funciona recorriendo repetidamente la lista que se va a ordenar, comparando cada par de elementos adyacentes y cambiándolos de posición si están en el orden incorrecto. Este proceso se repite hasta que no se requieran más intercambios, lo que indica que la lista está ordenada.
    El algoritmo recibe su nombre porque en cada pasada, los elementos más grandes "flotan" hacia su posición correcta como las burbujas en una bebida carbonatada. 
Selection sort.
    Funciona dividiendo la lista en dos partes: una parte ordenada y una parte no ordenada. En cada paso, el algoritmo busca el elemento más pequeño (o más grande, dependiendo del orden deseado) en la parte no ordenada y lo intercambia con el primer elemento de la parte no ordenada. Como resultado, el elemento más pequeño se coloca en su posición final en la parte ordenada.

    Este proceso se repite hasta que la parte no ordenada se vacía y toda la lista está ordenada. Aunque el Selection Sort también tiene una complejidad de tiempo de O(n^2), como el Bubble Sort, generalmente es más eficiente en términos de rendimiento debido a un menor número de intercambios realizados.
Insertion sort.
    Funciona de manera similar a cómo una persona ordenaría cartas en su mano mientras juega a las cartas. El algoritmo recorre la lista de elementos uno por uno e inserta cada elemento en su lugar correcto en la parte ya ordenada de la lista.

    El proceso comienza con el segundo elemento de la lista y compara este elemento con los elementos anteriores en la parte ordenada. Si el elemento es menor que el elemento anterior, se desplaza el elemento anterior una posición hacia la derecha para hacer espacio para el nuevo elemento. Este proceso continúa hasta que se encuentra el lugar correcto para el elemento en la parte ordenada.