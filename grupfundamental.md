# Grupo fundamental. 


Recordemos que los espacios topologicos $X$ , $Y$ son homeomorfos si existen funciónes continuas $f:X \to Y$ y $g:Y\to X$ tal que $g\circ f=\text{Id}{X}$ y $f\circ g=\text{Id}{Y}$ , diremos que $f$ y $g$ homeomorfismos. Por ejemplo si consideramos como espacios topologicos a las letras $M$ y $N$ podemos construir un homeomorfismo entre ellas. 

Vamos a denotar con $I$ al intervalo unitario $[0,1]$ y sea $X$ un espacio topologico vamos a comenzar con la siguiente definición :

**Definición 0 :** Un camino es una función continua $f:I\to X$. 

La imagen de $f$ puede pensarse como su nombre lo dice , como un camino en el espacio topologico $X$ , usualmente a este camino lo vamos a visualizar como una cuerda (o liga) por conveniencia (nos permitira entender y motivar definiciones sobre caminos mas claramente). No debemos de confundir la imagen de $f$ (la representación de verlo como una cuerda) con $f$ misma (un camino es una función) , o sea vamos a considerar caminos parametrizados. 


**Observación :** Recordemos que podemos representar a un camino como una cuerda/liga. Entonces podemos deformar caminos continuamente en un tiempo finito. 
Esto lo podemos formalizar mediante la siguiente definición :

**Definición 1:** Una homotopia de caminos en $X$ es una familia $f_{t} : I\to X$  , $0\leq t \leq 1$ tal que la función asociada $F:I\times I \to X$ dada por $F(s,t)=f_{t}(s)$ es continua. 

Podemos pensar a $t$ como un parametro de tiempo. Entonces nuestra deformación de un camino sera la familia (sucesión) de caminos $f_{t}$ , donde el $t$-esimo camino es la etapa $t$ de la deformación , comenzando desde $f_{0}$ hasta llegar a $f_{1}$ , el cuadrado $I\times I$ sera el que nos de la familia de funciones (cada una de sus "lineas" sera un camino que forma parte de la deformación). 

**Definición 2:** Diremos que la homotopia de caminos $F:I\times I\to X$ es relativa a los extremos , denotado $\text{rel} \ 0,1$ si $F(0,t)=x_{0}$ para todo $t$ y $F(1,t)=x_{1}$ para todo $t$ , donde $x_{0},$x_{1}\in X$. 

Dos caminos $f_{0}$ y $f_{1}$ tales que $f_{0}=f_{1}(0)$ y $f_{1}(1)=f_{1}(1)$ (ambos tienen los mismos puntos iniciales y finales) en $X$ son homotopicos en $\text{rel} \ 0,1$ si hay una homotopia entre ellos , es decir que a $f_{0}$ lo puedo deformar a  $f_{1}$ dejando fijos a los extremos. Lo anterior lo podemos denotar $f_{0}\cong f_{1} \ \text{rel} \ 0,1$. 


Ahora vamos a considerar el conjunto de todos los caminos en $X$ : $\Omega(X) =\left\{f : I\to X \right\}$ , a partir de este conjunto es muy natural pensar en esta relacion de equivalencia para $f_{0},f_{1}\in \Omega(X)$ , $f_{0}\sim f_{1} \Leftrightarrow f_{0}\cong f_{1} \ \text{rel} \ 0,1$. 

**Proposición 0:** La relacion $\sim$ en $\Omega(X)$ es una relación de equivalencia.

**Demostración :**

Sean $f,g,h\in \Omega(X)$. 

+ Necesitamos que $f\cong f $ $\text{rel}$ $0,1$ (reflexividad) , esto lo conseguimos con la homotopia $F:I\times I \to X$ dada por $F(s,t)=f(t)$. 
+ Queremos ver que $f\cong g$ $\text{rel}$ $0,1$ implica $g\cong f$ $\text{rel}$ $0,1$. Ahora , si consideramos la homotopia $F:I\times I\to X$ de $f$ a $g$ $\text{rel}$ $0,1$ , definimos $G:I\times I\to X$ como $G(s,t)=F(1-s,t)$ (el $1-s$ "voltea" la homotopia). 
+ Por ultimo requerimos que si $f\cong g$ $\text{rel}$ $0,1$ y $g\cong h$ $\text{rel}$ $0,1$ entonces $f\cong h$ $\text{rel}$ $0,1$. Si $F:I\times I \to X$ y $G: I\times I \to X$ son homotopias de $f$ a $g$ y de $g$ a $h$ respectivamente , definimos $H:I\times I \to X$ como sigue $$H(s,t)=\begin{cases}
F(s,2t) & \text{ si } t\in [0,\frac{1}{2}] \\
G(s,2t-1) & \text{ si } t\in [\frac{1}{2},1] 
\end{cases}$$


$\blacksquare$















### Ejercicios



