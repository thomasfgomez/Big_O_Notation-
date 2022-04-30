# Big_O_Notation
Implementing some algorithms with different Big O Notation.

### Based on this video
- https://www.youtube.com/watch?v=5yJ_QLec0Lc
- https://pablocianes.com/big-o-ejemplos-basicos/ | https://www.youtube.com/watch?v=PfG1dCZBzWA
- https://www.youtube.com/watch?v=6aDHWSNKlVw (Tech with tim)
- brillant.org

![image](https://user-images.githubusercontent.com/84288864/166108203-5f12825a-f213-4937-a502-e600a62f4216.png)

### Resolving Time Complexity Algorithms 

To solve this problems, we first think how much time

- We have to take into account if the operations have a constant time complexity, if so we can discard them, if not we must take them into account.
- Recursive functions: To solve this, the important thing to look here is, how many recursive functions calls in every step. How many times recursive function is going to run, and multipling by the number of operations ocuring in the function. 
- The most efficent way to sort ANYTHING is log(n). Whenever there is a sorted function, we will consider its time complexity as n. log(n)
- La primer linea de un inner loop suele ser la que mas veces se repite/ejecuta. 
- Para averiguar el Big O, siempre tomamos el peor caso del algoritmo. 
