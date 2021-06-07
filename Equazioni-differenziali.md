# Equazioni differenziali

## Che cos'è un'equazione differenziale

> **`DEFINIZIONE`**
> 
> Un'**equazione differenziale** è un'equazione che ha per incognita una funzione *y* nella variabile *x* e che stabilisce una relazione fra *x*, *y* e almeno una delle sue derivate (*y'*, *y"*, ...), cioè è un'equazione del tipo *F*(*x*; *y*; *y'*; ...; *y*<sup>(<i>n</i>)</sup>; ...) = 0.

L'**ordine** di un'equazione differenziale è l'ordine massimo delle derivate che compaiono in essa.\
Per esempio, un'equazione del tipo *F*(*x*; *y*; *y'*; *y"*) = 0 è detta del secondo ordine.

Ognuna delle funzioni che verifica un'equazione differenziale si chiama **soluzione** o **integrale** dell'equazione. Il suo grafico si chiama **curva integrale**.\
Le soluzioni di un'equazione differenziale sono infinite.\
Risolverla significa trovare tutte le sue soluzioni.

L'insieme delle soluzioni, che dipendono da uno o più parametri, è detto **integrale generale**.\
Se impostiamo questi parametri ad un valore particolare si dice **integrale particolare**.\
Una soluzione che non si può trovare usando l'integrale generale è detta **integrale singolare**.

## Equazioni differenziali del primo ordine

> **`DEFINIZIONE`**
> 
> **Problema di Cauchy**
> 
> Trovare una soluzione particolare a una equazione differenziale del primo ordine che passa per un determinato punto (*x*<sub>0</sub>; *y*<sub>0</sub>).\
> Serve quindi determinare una funzione *y* = *&fnof;*(*x*) che soddisfi due condizioni (a sistema):
> - *F*(*x*; *y*; *y'*) = 0
> - *y*<sub>0</sub> = *&fnof;*(*x*<sub>0</sub>)
> 
> La condizione *y*<sub>0</sub> = *&fnof;*(*x*<sub>0</sub>) è detta **condizione iniziale del problema di Cauchy**.

> **`TEOREMA`**
> 
> **Teorema di Cauchy**
> 
> Sia *G*(*x*; *y*) una funzione di due variabili reali, continua in un sottoinsieme aperto *A* del piano e dotata di derivata parziale rispetto a *y*, anch'essa continua in *A*. Sia poi *P*(*x*<sub>0</sub>; *y*<sub>0</sub>) un punto qualsiasi appartenente ad *A*. Allora il problema di Cauchy, espresso dal sistema
> - *y'* = *G*(*x*; *y*)
> - *y*<sub>0</sub> = *&fnof;*(*x*<sub>0</sub>)
> 
> ammette una e una sola soluzione *y* = *&fnof;*(*x*), definita in un intorno di *x*<sub>0</sub>.

### Equazioni del tipo *y'* = *&fnof;*(*x*)

**In generale**, per risolvere un'equazione differenziale del primo ordine, riconducibile al tipo *y'* = *&fnof;*(*x*), si integrano entrambi i membri:

&int; *y'* *dx* = &int; *&fnof;*(*x*) *dx*.

L'integrale generale è: <code><i>y</i> = &int; <i>&fnof;</i>(<i>x</i>) <i>dx</i></code>.

### Equazioni a *variabili separabili*

> **`DEFINIZIONE`**
> 
> Un'equazione differenziale del primo ordine è **a variabili separabili** quando può essere scritta nella forma *y'* = *g*(*x*) &sdot; *h*(*y*), con *g*(*x*) e *h*(*y*) funzioni continue rispettivamente nella sola variabile *x* e nella sola *y*.

### Equazioni *omogenee*

> **`DEFINIZIONE`**
> 
> Dati i polinomi *A*(*x*; *y*) e *B*(*x*; *y*), un'equazione differenziale del primo ordine del tipo
> 
> *y'* = *A*(*x*; *y*) &divide; *B*(*x*; *y*)
> 
> si dice **omogenea** quando *A*(*x*; *y*) e *B*(*x*; *y*) sono omogenei di grado *n*.

### Equazioni *lineari*

> **`DEFINIZIONE`**
> 
> Un'equazione differenziale del primo ordine è **a variabili separabili** quando può essere scritta nella forma *y'* = *g*(*x*) &sdot; *h*(*y*), con *g*(*x*) e *h*(*y*) funzioni continue rispettivamente nella sola variabile *x* e nella sola *y*.

### Equazioni *di Bernoulli*

> **`DEFINIZIONE`**
> 
> Un'equazione differenziale del primo ordine è **a variabili separabili** quando può essere scritta nella forma *y'* = *g*(*x*) &sdot; *h*(*y*), con *g*(*x*) e *h*(*y*) funzioni continue rispettivamente nella sola variabile *x* e nella sola *y*.
