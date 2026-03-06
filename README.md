# Detección de fraude en Redes Complejas (Bitcoin OTC) mediante el uso de herramientas topológicas y algebraicas
El problema a resolver consiste en analizar la red como un grafo buscando posibles estafadores sin usar modelos predictivos como el de la caja negra. 

## 📌 El problema
En primer lugar, hacemos un barrido de los datos de la base de datos de la Universidad de Stanford identificando los pares de valoraciones como aristas y extraemos sus vértices mediante la definición de una biyección que indexe el espacio vectorial para poder estudiar el digrafo que forman. 

## ♾️ Enfoque matemático y herramientas topológicas y algebraicas
A continuación, estudiamos los subespacios de Krylov resultantes de la matriz ponderada con los pesos de las aristas mediante iteraciones de Arnoldi y observamos el autovector dominante por la izquierda representa un posible caso de fraude. 

En base a dicho análisis, aplicamos álgebra de caminos y el producto de Hadamard para ver como el sujeto interactúa con otros usuarios y encontramos su posible anillo de colusión. 

Por último, realizamos una auditoría topológica estricta comprobando que, efectívamente, el usuario encontrado tiene un comportamiento fraudulento. 

## 📄 Conclusiones. 
Tras finalizar, concluimos que el enfoque utilizado, aparte de ser eficiente, ofrece una interpretabilidad y rigurosidad matemática absolutas. 
