1)¿Por qué un sistema de delivery usa Queue para los pedidos pero Stack para la bitácora? ¿Qué problema surgiría si invertimos las estructuras?
R:Se utiliza porque los clientes llaman y sus pedidos se registran. Por norma de la casa, se preparan y entregan estrictamente por orden de llegada, si este se invierte, el problema seria que el ultimo seria el primero en llegar.

2)¿Por qué es obligatorio verificar Count == 0 antes de Dequeue() o Pop()? ¿Qué ocurre en ejecución si se omite?
R:Es obligatorio porque necesitan extraer un elemento que exista, si este se omite la validacion no existiria y no podra poner ningun elemento.

3)En el método Deshacer, ¿por qué es necesario analizar el texto con .StartsWith() antes de revertir? ¿Qué error lógico evitaría esto?
R:Es necesario analizar el texto con .StrarWith() para saber que revertir, evitaria que revirtiera pedidos que no se pueden revertir.
, 
4)¿Qué ventaja tiene entregar mediante Fork + Pull Request en lugar de un archivo comprimido? ¿Cómo facilita la la retroalimentación?
R:La ventaja es que permite ver que lineas de codigo cambiaron y quien las cambió, también el fork funciona como una copia hasta entregarlo, facilita a la retroalimentación porque el profesor o un compañero puede dejar comentarios para ayudarlo.