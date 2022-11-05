# Equivalencias de Homotopia. 


Recordemos que los espacios topologicos $X$ , $Y$ son homeomorfos si existen funciónes continuas $f:X \to Y$ y $g:Y\to X$ tal que $g\circ f=\text{Id}{X}$ y $f\circ g=\text{Id}{Y}$ , diremos que $f$ y $g$ homeomorfismos. Por ejemplo si consideramos como espacios topologicos a las letras $M$ y $N$ podemos construir un homeomorfismo entre ellas. 

Vamos a denotar con $I$ al intervalo unitario $[0,1]$ y sea $X$ un espacio topologico vamos a comenzar con la siguiente definición :

**Definición 0 :** Un camino es una función continua $f:I\to X$. 

La imagen de $f$ puede pensarse como su nombre lo dice , como un camino en el espacio topologico $X$ , usualmente a este camino lo vamos a visualizar como una cuerda (o liga) por conveniencia (nos permitira entender y motivar definiciones sobre caminos mas claramente). No debemos de confundir la imagen de $f$ (la representación de verlo como una cuerda) con $f$ misma (un camino es una función) , o sea vamos a considerar caminos parametrizados. 


**Observación :** Recordemos que podemos representar a un camino como una cuerda/liga. Entonces podemos deformar caminos continuamente en un tiempo finito. 
Esto lo podemos formalizar mediante la siguiente definición :

**Definición 1:** Una homotopia de caminos en $X$ es una familia $f_{t} : I\to X$  , $0\leq t \leq 1$ tal que la función asociada $F:I\times I \to X$ dada por $F(s,t)=f_{t}(s)$ es continua. 

Podemos pensar a $t$ como un parametro de tiempo. Entonces nuestra deformación de un camino sera la familia (sucesión) 










